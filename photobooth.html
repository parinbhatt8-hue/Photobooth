<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Navratri Photo Booth</title>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,500;12..96,800&display=swap">
<style>
:root{--bg:#5a0b4d;--bg2:#2b0a3d;--paper:#fff8ea;--ink:#4a0a40;--hot:#ff8a00;--gold:#f7b500;--text:#fff8ea;--chip:rgba(255,255,255,.14);--chipOn:#f7b500;--chipOnText:#3a0838;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:light){:root:not([data-theme="dark"]){--bg:#ffe9c7;--bg2:#ffd29a;--text:#4a0a40;--chip:rgba(74,10,64,.1);--chipOn:#4a0a40;--chipOnText:#fff8ea}}
:root[data-theme="light"]{--bg:#ffe9c7;--bg2:#ffd29a;--text:#4a0a40;--chip:rgba(74,10,64,.1);--chipOn:#4a0a40;--chipOnText:#fff8ea}
*{box-sizing:border-box}
html{height:100%;scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;height:100%;background:radial-gradient(120% 90% at 50% 0%,var(--bg),var(--bg2));color:var(--text);font-family:"Bricolage Grotesque",system-ui,sans-serif;overflow:hidden;-webkit-tap-highlight-color:transparent}
button{font:inherit;color:inherit;border:0;cursor:pointer}
button:focus-visible{outline:3px solid var(--hot);outline-offset:3px}
.screen{position:absolute;inset:0;display:none;flex-direction:column;align-items:center;padding:38px 16px 20px}
.screen.on{display:flex}
/* intro */
#intro{justify-content:center;text-align:center;gap:18px}
#intro h1{font-size:clamp(2.6rem,14vw,5.2rem);line-height:.88;margin:0;font-weight:800;letter-spacing:-.04em}
#intro p{margin:0;max-width:26ch;font-size:1.1rem;opacity:.85}
.toran{position:fixed;inset:0 0 auto 0;height:30px;z-index:5;pointer-events:none;background:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='72' height='30'%3E%3Crect width='72' height='4' fill='%23f7b500'/%3E%3Cpath d='M3 4h30l-15 24z' fill='%23ff8a00'/%3E%3Cpath d='M10 4h16l-8 13z' fill='%23d6247a'/%3E%3Cpath d='M39 4h30l-15 24z' fill='%2300a5a8'/%3E%3Cpath d='M46 4h16l-8 13z' fill='%23f7b500'/%3E%3C/svg%3E") repeat-x;background-size:72px 30px}
.diya{font-size:3.2rem;filter:drop-shadow(0 0 18px #f7b500)}
.go{background:var(--hot);color:#3a0838;font-weight:800;font-size:1.2rem;padding:16px 34px;border-radius:999px;box-shadow:0 6px 0 rgba(0,0,0,.28)}
.go:active{transform:translateY(3px);box-shadow:0 3px 0 rgba(0,0,0,.28)}
.err{color:#fff;background:rgba(0,0,0,.35);padding:10px 14px;border-radius:12px;max-width:34ch;font-size:.95rem}
/* booth */
#booth{gap:10px}
.top{width:100%;max-width:520px;display:flex;justify-content:space-between;align-items:center}
.top b{font-size:1.3rem;letter-spacing:-.02em}
.round{width:44px;height:44px;border-radius:50%;background:var(--chip);display:grid;place-items:center;font-size:1.2rem}
.stage{flex:1;min-height:0;width:100%;position:relative;display:grid;place-items:center}
.vf{position:relative;overflow:hidden;border-radius:6px;background:#000;border:6px solid var(--gold);box-shadow:0 10px 30px rgba(0,0,0,.35)}
.vf video{position:absolute;inset:0;width:100%;height:100%;object-fit:cover}
.vf.mirror video{transform:scaleX(-1)}
.count{position:absolute;inset:0;display:grid;place-items:center;font-size:min(34vw,10rem);font-weight:800;color:#fff;text-shadow:0 4px 24px rgba(0,0,0,.5);pointer-events:none}
.count span{animation:pop .9s ease-out}
@keyframes pop{0%{transform:scale(1.7);opacity:0}25%{opacity:1}100%{transform:scale(.9);opacity:.2}}
.flash{position:absolute;inset:0;background:#fff;opacity:0;pointer-events:none}
.flash.fire{animation:fl .35s ease-out}
@keyframes fl{0%{opacity:.95}100%{opacity:0}}
.dots{position:absolute;bottom:8px;left:0;right:0;display:flex;gap:6px;justify-content:center}
.dots i{width:10px;height:10px;border-radius:50%;border:2px solid #fff;background:transparent}
.dots i.done{background:#fff}
.chips{display:flex;gap:8px;overflow-x:auto;max-width:100%;padding:2px}
.chip{background:var(--chip);padding:9px 15px;border-radius:999px;font-weight:500;white-space:nowrap}
.chip[aria-pressed="true"]{background:var(--chipOn);color:var(--chipOnText);font-weight:800}
.shutter{width:78px;height:78px;border-radius:50%;background:var(--hot);border:6px solid var(--paper);box-shadow:0 5px 0 rgba(0,0,0,.28)}
.shutter:active{transform:translateY(3px)}
.shutter:disabled{opacity:.4}
/* result */
#result{gap:14px;overflow:hidden}
.slot{flex:1;min-height:0;width:100%;display:flex;justify-content:center;overflow:hidden;border-top:10px solid rgba(0,0,0,.35);border-radius:8px}
.slot img{height:100%;width:auto;max-width:100%;object-fit:contain;background:var(--paper);box-shadow:0 10px 30px rgba(0,0,0,.35);animation:print 1.2s cubic-bezier(.2,.8,.2,1)}
@keyframes print{from{transform:translateY(-100%)}to{transform:none}}
.row{display:flex;gap:10px;flex-wrap:wrap;justify-content:center}
.btn{background:var(--chip);padding:14px 22px;border-radius:999px;font-weight:800}
.btn.main{background:var(--hot);color:#3a0838}
.hint{position:absolute;top:8px;left:8px;right:8px;text-align:center;font-weight:800;font-size:.95rem;color:#fff;text-shadow:0 2px 10px rgba(0,0,0,.7);pointer-events:none}
@media (prefers-reduced-motion:reduce){.count span,.slot img{animation:none}.flash.fire{animation-duration:.01s}}
</style>
</head>
<body>
<div class="toran" aria-hidden="true"></div>

<section class="screen on" id="intro">
  <div class="diya" aria-hidden="true">🪔</div>
  <h1>Navratri<br>photo booth</h1>
  <p>Dress up, strike a pose, and take four quick shots.</p>
  <button class="go" id="start">Step inside</button>
  <div class="err" id="err" hidden></div>
</section>

<section class="screen" id="booth">
  <div class="top"><b>Navratri booth</b><button class="round" id="flip" aria-label="Switch camera">⟲</button></div>
  <div class="stage" id="stage">
    <div class="vf mirror" id="vf">
      <video id="video" autoplay playsinline muted></video>
      <div class="hint" id="hint"></div>
      <div class="count" id="count"></div>
      <div class="flash" id="flash"></div>
      <div class="dots" id="dots"></div>
    </div>
  </div>
  <div class="chips" id="layouts" role="group" aria-label="Layout"></div>
  <div class="chips" id="filters" role="group" aria-label="Filter"></div>
  <button class="shutter" id="shutter" aria-label="Take photos"></button>
</section>

<section class="screen" id="result">
  <div class="slot"><img id="out" alt="Your photo strip"></div>
  <div class="row">
    <button class="btn" id="retake">Retake</button>
    <button class="btn" id="share" hidden>Share</button>
    <button class="btn main" id="save">Save photo</button>
  </div>
</section>

<script>
const LAYOUTS={
  strip:{label:"Strip of 4",cols:1,rows:4,fw:520,fh:390},
  grid:{label:"Grid of 4",cols:2,rows:2,fw:380,fh:380},
  single:{label:"Single",cols:1,rows:1,fw:520,fh:693}
};
const mk=p=>{const{gray=0,sep=0,sat=1,con=1,bri=1,mul=[1,1,1],add=[0,0,0]}=p;return(r,g,b)=>{
  let l=.3*r+.59*g+.11*b;
  if(gray){r+=(l-r)*gray;g+=(l-g)*gray;b+=(l-b)*gray}
  if(sep){const a=.393*r+.769*g+.189*b,c=.349*r+.686*g+.168*b,d=.272*r+.534*g+.131*b;r+=(a-r)*sep;g+=(c-g)*sep;b+=(d-b)*sep}
  l=.3*r+.59*g+.11*b;r=l+(r-l)*sat;g=l+(g-l)*sat;b=l+(b-l)*sat;
  return[r*mul[0]+add[0],g*mul[1]+add[1],b*mul[2]+add[2]].map(v=>((v-128)*con+128)*bri)}};
const FILTERS={
  none:{label:"Natural",css:"none",fn:null},
  vivid:{label:"Vivid",css:"saturate(1.5) contrast(1.1)",fn:mk({sat:1.5,con:1.1})},
  mono:{label:"Black & white",css:"grayscale(1) contrast(1.15)",fn:mk({gray:1,con:1.15})},
  noir:{label:"Noir",css:"grayscale(1) contrast(1.5) brightness(.9)",fn:mk({gray:1,con:1.5,bri:.9})},
  sepia:{label:"Sepia",css:"sepia(.9)",fn:mk({sep:.9})},
  vintage:{label:"Vintage",css:"sepia(.45) contrast(.9) saturate(.85) brightness(1.05)",fn:mk({sep:.45,con:.9,sat:.85,bri:1.05})},
  warm:{label:"Diya glow",css:"sepia(.25) saturate(1.3) brightness(1.05)",fn:mk({sep:.25,sat:1.3,bri:1.05})},
  golden:{label:"Golden hour",css:"sepia(.4) saturate(1.5) contrast(1.05) brightness(1.08)",fn:mk({sep:.4,sat:1.5,con:1.05,bri:1.08})},
  rose:{label:"Rose",css:"saturate(1.2) sepia(.15) hue-rotate(-20deg) brightness(1.04)",fn:mk({sat:1.2,mul:[1.08,.96,1.04],bri:1.04})},
  cool:{label:"Cool",css:"saturate(1.1) hue-rotate(10deg) brightness(1.03)",fn:mk({sat:1.1,mul:[.92,1,1.1]})},
  fade:{label:"Faded",css:"contrast(.85) brightness(1.1) saturate(.8)",fn:mk({con:.85,bri:1.1,sat:.8})}
};
const $=id=>document.getElementById(id);
const FIRST=5,BETWEEN=5,PAUSE=1200;
const CTXF=typeof CanvasRenderingContext2D!=="undefined"&&"filter" in CanvasRenderingContext2D.prototype;
const hint=t=>{$("hint").textContent=t};
const stopCam=()=>{if(stream){stream.getTracks().forEach(t=>t.stop());stream=null}};
let layout="strip",filter="none",facing="user",stream=null,busy=false,blobUrl=null,blob=null;

function show(id){document.querySelectorAll(".screen").forEach(s=>s.classList.toggle("on",s.id===id));if(id==="booth")fit()}

async function openCam(){
  if(stream)stream.getTracks().forEach(t=>t.stop());
  stream=await navigator.mediaDevices.getUserMedia({video:{facingMode:facing,width:{ideal:1280},height:{ideal:960}},audio:false});
  const v=$("video");v.srcObject=stream;await v.play().catch(()=>{});
  $("vf").classList.toggle("mirror",facing==="user");
}

$("start").onclick=async()=>{
  const e=$("err");e.hidden=true;
  try{
    if(!navigator.mediaDevices||!navigator.mediaDevices.getUserMedia)throw new Error("nocam");
    await openCam();show("booth");
  }catch(x){
    e.hidden=false;
    e.textContent=x.name==="NotAllowedError"
      ?"Camera access is blocked. Allow the camera in your browser settings, then try again."
      :"The camera couldn't start. Open this page directly in Safari or Chrome, not inside another app.";
  }
};
$("flip").onclick=async()=>{if(busy)return;facing=facing==="user"?"environment":"user";try{await openCam()}catch(e){facing=facing==="user"?"environment":"user";openCam()}};

function chips(box,items,get,set){
  const el=$(box);el.innerHTML="";
  Object.entries(items).forEach(([k,v])=>{
    const b=document.createElement("button");b.className="chip";b.textContent=v.label;
    b.setAttribute("aria-pressed",get()===k);
    b.onclick=()=>{if(busy&&box==="layouts")return;set(k);[...el.children].forEach((c,i)=>c.setAttribute("aria-pressed",Object.keys(items)[i]===k))};
    el.appendChild(b);
  });
}
function applyLayout(){const L=LAYOUTS[layout];$("vf").dataset.r=L.fw/L.fh;fit();dots(0)}
chips("layouts",LAYOUTS,()=>layout,k=>{layout=k;applyLayout()});
chips("filters",FILTERS,()=>filter,k=>{filter=k;$("video").style.filter=FILTERS[k].css});

function fit(){
  const st=$("stage"),vf=$("vf"),r=parseFloat(vf.dataset.r||1.333);
  const W=st.clientWidth,H=st.clientHeight;if(!W||!H)return;
  let w=Math.min(W,H*r),h=w/r;vf.style.width=w+"px";vf.style.height=h+"px";
}
addEventListener("resize",fit);
function dots(n){const L=LAYOUTS[layout],t=L.cols*L.rows,d=$("dots");d.innerHTML="";if(t<2)return;for(let i=0;i<t;i++){const e=document.createElement("i");if(i<n)e.className="done";d.appendChild(e)}}

const wait=ms=>new Promise(r=>setTimeout(r,ms));

async function countdown(n){
  const c=$("count");
  for(let i=n;i>0;i--){c.innerHTML="<span>"+i+"</span>";await wait(900)}
  c.innerHTML="";
}
function grab(){
  const L=LAYOUTS[layout],v=$("video"),S=1.5,cw=Math.round(L.fw*S),ch=Math.round(L.fh*S);
  const c=document.createElement("canvas");c.width=cw;c.height=ch;const x=c.getContext("2d");
  const vw=v.videoWidth,vh=v.videoHeight,tr=cw/ch;
  let sw=vw,sh=vw/tr;if(sh>vh){sh=vh;sw=vh*tr}
  const sx=(vw-sw)/2,sy=(vh-sh)/2;
  const F=FILTERS[filter],nat=CTXF&&F.css!=="none";
  if(nat)x.filter=F.css;
  if(facing==="user"){x.translate(cw,0);x.scale(-1,1)}
  x.drawImage(v,sx,sy,sw,sh,0,0,cw,ch);
  x.setTransform(1,0,0,1,0,0);x.filter="none";
  const fn=nat?null:F.fn;
  if(fn){
    const d=x.getImageData(0,0,cw,ch),p=d.data;
    for(let i=0;i<p.length;i+=4){const o=fn(p[i],p[i+1],p[i+2]);p[i]=o[0];p[i+1]=o[1];p[i+2]=o[2]}
    x.putImageData(d,0,0);
  }
  return c;
}

$("shutter").onclick=async()=>{
  if(busy)return;busy=true;$("shutter").disabled=true;
  const L=LAYOUTS[layout],total=L.cols*L.rows,shots=[];
  for(let i=0;i<total;i++){
    hint(total>1?"Shot "+(i+1)+" of "+total+". Pick a filter now.":"Pick a filter now.");await countdown(i===0?FIRST:BETWEEN);hint("");
    $("flash").classList.remove("fire");void $("flash").offsetWidth;$("flash").classList.add("fire");
    shots.push(grab());dots(i+1);
    await wait(i<total-1?PAUSE:300);
  }
  await compose(shots);stopCam();
  busy=false;$("shutter").disabled=false;dots(0);
  show("result");
};

async function compose(shots){
  const L=LAYOUTS[layout],S=2,pad=36,gap=20,foot=layout==="single"?110:96;
  const W=pad*2+L.cols*L.fw+(L.cols-1)*gap;
  const H=pad*2+L.rows*L.fh+(L.rows-1)*gap+foot;
  const c=document.createElement("canvas");c.width=W*S;c.height=H*S;
  const x=c.getContext("2d");x.scale(S,S);
  x.fillStyle="#fff8ea";x.fillRect(0,0,W,H);
  const pal=["#f7b500","#ff8a00","#d6247a","#00a5a8"];
  const dia=(cx,cy,i)=>{x.fillStyle=pal[i%4];x.beginPath();x.moveTo(cx,cy-7);x.lineTo(cx+7,cy);x.lineTo(cx,cy+7);x.lineTo(cx-7,cy);x.fill()};
  for(let i=0,t=9;t<W;i++,t+=18){dia(t,10,i);dia(t,H-10,i+2)}
  for(let i=0,t=9;t<H;i++,t+=18){dia(10,t,i);dia(W-10,t,i+2)}
  shots.forEach((s,i)=>{
    const col=i%L.cols,row=Math.floor(i/L.cols);
    x.drawImage(s,pad+col*(L.fw+gap),pad+row*(L.fh+gap),L.fw,L.fh);
  });
  x.fillStyle="#4a0a40";x.textAlign="center";
  x.font='800 34px "Bricolage Grotesque",system-ui,sans-serif';
  x.fillText("Shubh Navratri",W/2,H-foot/2-4+pad/4);
  x.font='500 18px "Bricolage Grotesque",system-ui,sans-serif';x.globalAlpha=.7;
  x.fillText(new Date().toLocaleDateString(undefined,{day:"numeric",month:"long",year:"numeric"}),W/2,H-foot/2+28+pad/4);
  x.globalAlpha=1;
  blob=await new Promise(r=>c.toBlob(r,"image/jpeg",.92));
  if(blobUrl)URL.revokeObjectURL(blobUrl);
  blobUrl=URL.createObjectURL(blob);
  const img=$("out");img.src="";img.src=blobUrl;
  const f=new File([blob],"navratri-photo-booth.jpg",{type:"image/jpeg"});
  $("share").hidden=!(navigator.canShare&&navigator.canShare({files:[f]}));
}

$("retake").onclick=async()=>{show("booth");try{await openCam()}catch(e){}};
$("save").onclick=()=>{
  const a=document.createElement("a");a.href=blobUrl;a.download="navratri-photo-booth.jpg";
  document.body.appendChild(a);a.click();a.remove();
};
$("share").onclick=async()=>{
  try{await navigator.share({files:[new File([blob],"navratri-photo-booth.jpg",{type:"image/jpeg"})],title:"Navratri photo booth"})}catch(e){}
};

applyLayout();
</script>
</body>
</html>
