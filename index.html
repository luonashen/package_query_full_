<!DOCTYPE html>
<html lang="zh-Hant"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>A1 戶型・北歐簡約 3D 設計</title>
<style>
:root{--bg:#eef0f2;--fg:#2b2f33;--card:rgba(255,255,255,.92);--bd:#d3d8dc;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#1e2225;--fg:#e8eaec;--card:rgba(40,45,49,.92);--bd:#3b4247}}
:root[data-theme="dark"]{--bg:#1e2225;--fg:#e8eaec;--card:rgba(40,45,49,.92);--bd:#3b4247}
html,body{height:100%;margin:0}
body{position:relative;background:var(--bg);color:var(--fg);font-family:-apple-system,"PingFang TC","Noto Sans TC",sans-serif;overflow:hidden}
#c{display:block;width:100%;height:100%;touch-action:none}
#tags{position:absolute;inset:0;overflow:hidden;pointer-events:none}
.tag{position:absolute;transform:translate(-50%,-50%);background:#161616;color:#fff;padding:4px 10px;border-radius:8px;font-size:13px;white-space:nowrap}
.top{position:absolute;left:12px;right:12px;top:10px;background:var(--card);border:1px solid var(--bd);border-radius:12px;padding:8px 12px;font-size:13px;line-height:1.4;pointer-events:none}
.top b{font-size:15px}
.bar{position:absolute;left:12px;right:12px;bottom:12px;display:flex;gap:8px}
.bar button{flex:1;padding:11px 4px;font-size:14px;color:var(--fg);background:var(--card);border:1px solid var(--bd);border-radius:10px}
.bar button.on{outline:2px solid #7fa38a}
</style></head><body>
<canvas id="c"></canvas><div id="tags"></div>
<div class="top"><b>A1 戶型・北歐簡約</b><br>3房2衛・30.87坪（示意）｜單指旋轉，雙指縮放</div>
<div class="bar">
<button id="b1">俯視</button><button id="b2">斜視</button><button id="b3" class="on">矮牆</button><button id="b4" class="on">標籤</button>
<button id="b5" class="on">旋轉</button></div>
<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
<script>
const WALL=0xffffff,FLOOR=0xebd8b4,OAK=0xc9a77c,WH=0xf7f6f3,GR=0xb4babe,SG=0x9db7a2,BK=0x2f3236,TILE=0xcfd5d8,BL=0xdfe6ea;
const cv=document.getElementById('c');
const r=new THREE.WebGLRenderer({canvas:cv,antialias:true});
r.shadowMap.enabled=false;
const sc=new THREE.Scene();
const cam=new THREE.PerspectiveCamera(40,1,.1,200);
sc.add(new THREE.HemisphereLight(0xffffff,0xd8d4cc,.65));
const dl=new THREE.DirectionalLight(0xffffff,.5);dl.position.set(4,16,12);dl.castShadow=true;
dl.shadow.mapSize.set(2048,2048);Object.assign(dl.shadow.camera,{left:-12,right:12,top:12,bottom:-12,far:50});sc.add(dl);
const cache={};const OM=new THREE.MeshBasicMaterial({color:0x1c1c1c,side:THREE.BackSide}),LM=new THREE.LineBasicMaterial({color:0x1c1c1c});
const M=c=>cache[c]||(cache[c]=new THREE.MeshStandardMaterial({color:c,roughness:.9}));
const G=new THREE.Group();sc.add(G);
function b(x,z,w,d,h,c,y=0){const m=new THREE.Mesh(new THREE.BoxGeometry(w,h,d),M(c));m.position.set(x+w/2,y+h/2,z+d/2);G.add(m);
if(h>=.05&&Math.min(w,d)>=.04){m.add(new THREE.LineSegments(new THREE.EdgesGeometry(m.geometry),LM));const o=new THREE.Mesh(new THREE.BoxGeometry(w+.035,h+.035,d+.035),OM);o.position.copy(m.position);G.add(o)}return m}
const walls=[];let WH_=.9;
function wl(x1,z1,x2,z2,col=WALL){const t=.12,hz=z1===z2;const w=hz?x2-x1:t,d=hz?t:z2-z1;
const m=new THREE.Mesh(new THREE.BoxGeometry(1,1,1),M(col));m.add(new THREE.LineSegments(new THREE.EdgesGeometry(m.geometry),LM));
m.userData={cx:hz?(x1+x2)/2:x1,cz:hz?z1:(z1+z2)/2,w:hz?w+t:w,d:hz?d:d+t};G.add(m);const o=new THREE.Mesh(new THREE.BoxGeometry(1,1,1),OM);G.add(o);m.userData.o=o;walls.push(m)}
function setH(h){WH_=h;walls.forEach(m=>{const u=m.userData;m.scale.set(u.w,h,u.d);m.position.set(u.cx,h/2,u.cz);if(u.o){u.o.scale.set(u.w+.05,h+.05,u.d+.05);u.o.position.set(u.cx,h/2,u.cz)}})}
const gm=new THREE.MeshStandardMaterial({color:0xbfe3f2,transparent:true,opacity:.28,roughness:.2});
function gl(x,z,w,d,h,y=0){const m=new THREE.Mesh(new THREE.BoxGeometry(w,h,d),gm);m.position.set(x+w/2,y+h/2,z+d/2);G.add(m)}
const rkc=document.createElement('canvas');rkc.width=128;rkc.height=8;const rg=rkc.getContext('2d');for(let i=0;i<128;i+=8){rg.fillStyle='rgba(255,255,255,.85)';rg.fillRect(i,0,4,8);rg.fillStyle='rgba(190,206,212,.55)';rg.fillRect(i+4,0,4,8)}
const rkt=new THREE.CanvasTexture(rkc);rkt.wrapS=rkt.wrapT=THREE.RepeatWrapping;rkt.repeat.set(4,1);
const rm=new THREE.MeshStandardMaterial({color:0xeef2f3,transparent:true,opacity:.82,roughness:.9});
function rgl(x,z,w,d,h,y=0){const m=new THREE.Mesh(new THREE.BoxGeometry(w,h,d),rm);m.position.set(x+w/2,y+h/2,z+d/2);G.add(m)}
function plant(x,z,s=1){return;b(x-.12*s,z-.12*s,.24*s,.24*s,.3*s,WH);const l=new THREE.Mesh(new THREE.SphereGeometry(.28*s,12,10),M(0x6f9a74));l.position.set(x,.55*s,z);l.castShadow=true;G.add(l)}
// floors
function tex(draw,rx,ry){const k=document.createElement('canvas');k.width=k.height=512;draw(k.getContext('2d'));const t=new THREE.CanvasTexture(k);t.wrapS=t.wrapT=THREE.RepeatWrapping;t.repeat.set(rx,ry);t.anisotropy=4;return t}
const drawWood=g=>{for(let i=0;i<8;i++){const o=(i*97)%256;for(let k=-1;k<3;k++){const x=o+k*256;g.fillStyle='hsl(34,'+(42+(i*7+k*3+9)%9)+'%,'+(66+(i*5+k*11+7)%7)+'%)';g.fillRect(x,i*64,256,64);g.strokeStyle='rgba(110,80,45,.5)';g.lineWidth=2;g.strokeRect(x,i*64,256,64)}}};
const drawTile=g=>{const c=['#b6bbbf','#adb3b7','#b2b7bb','#a9afb3'];for(let i=0;i<2;i++)for(let j=0;j<2;j++){g.fillStyle=c[i*2+j];g.fillRect(j*256,i*256,256,256);g.strokeStyle='rgba(60,65,70,.55)';g.lineWidth=4;g.strokeRect(j*256,i*256,256,256)}};
const fl=new THREE.Mesh(new THREE.BoxGeometry(10,.04,6.9),new THREE.MeshStandardMaterial({map:tex(drawWood,10/1.2,6.9/1.2),roughness:.8}));fl.position.set(5,-.02,3.45);G.add(fl);
const bf=new THREE.Mesh(new THREE.BoxGeometry(3.45,.02,2.8),new THREE.MeshStandardMaterial({map:tex(drawTile,3.45/1.2,2.8/1.2),roughness:.5}));bf.position.set(5.475,.01,1.4);G.add(bf);
const fl2=new THREE.Mesh(new THREE.BoxGeometry(1.93,.04,4.1),new THREE.MeshStandardMaterial({map:tex(drawWood,1.93/1.2,4.1/1.2),roughness:.8}));fl2.position.set(9.035,-.02,-2.05);G.add(fl2);
const ef=new THREE.Mesh(new THREE.BoxGeometry(1.93,.02,1.1),new THREE.MeshStandardMaterial({map:tex(drawTile,1.93/1.2,1.1/1.2),roughness:.5}));ef.position.set(9.035,.01,-3.55);G.add(ef);
b(8.2,-4.16,1.2,.06,2.1,0x3a3d41);b(8.13,-4.18,.07,.14,2.15,OAK);b(9.4,-4.18,.07,.14,2.15,OAK);b(8.13,-4.18,1.34,.14,.07,OAK,2.15);b(9.1,-4.04,.15,.04,.04,0xc8c8c8,1.0);b(8.4,-3.7,.8,.5,.03,0x6b6f73,.02);
b(9.6,-3.5,.4,7.4,2.1,WH);for(let i=1;i<6;i+=2)b(9.59,-3.45+i*1.23,.012,1.15,2.0,OAK,.05);b(9.1,-3.3,.5,.9,.45,OAK);
const pm=new THREE.MeshStandardMaterial({map:tex(drawTile,1,1),roughness:.5});
function tw(x1,z1,x2,z2){const hz=z1===z2;const m=new THREE.Mesh(new THREE.BoxGeometry(1,1,1),pm);m.add(new THREE.LineSegments(new THREE.EdgesGeometry(m.geometry),LM));m.userData={cx:(x1+x2)/2,cz:(z1+z2)/2,w:hz?x2-x1:.02,d:hz?.02:z2-z1};G.add(m);walls.push(m)}
tw(3.81,.07,5.44,.07);tw(3.82,.06,3.82,1.6);tw(3.82,2.5,3.82,2.74);tw(3.81,2.73,5.44,2.73);tw(5.44,.06,5.44,2.74);
tw(5.57,.07,7.13,.07);tw(5.56,.06,5.56,2.74);tw(7.14,.06,7.14,2.74);tw(5.57,2.73,6.4,2.73);b(5,6.9,3.8,1.9,.04,0xb9bfc2,-.04);
// walls
wl(0,0,8.07,0);wl(0,0,0,6.9);wl(10,-4.1,10,6.9);wl(8.07,-4.1,8.07,0);wl(8.07,-4.1,8.2,-4.1);wl(9.4,-4.1,10,-4.1);wl(0,6.9,5,6.9);wl(8.8,6.9,10,6.9);
wl(0,2.8,2.7,2.8);wl(3.7,2.8,5.5,2.8,0xbcd0c0);wl(5.5,2.8,6.4,2.8);wl(7.1,2.8,7.2,2.8);
wl(3.75,0,3.75,1.6,0xbcd0c0);wl(3.75,2.5,3.75,2.8,0xbcd0c0);wl(5.5,0,5.5,2.8);wl(7.2,0,7.2,2.8);
wl(2.45,4,2.45,6.9);wl(2.5,4,3.1,4);wl(4.2,4,4.95,4);wl(4.95,4,4.95,6.9);
setH(.9);
// windows & balcony glass
gl(-.01,.5,.14,1.9,1.3,.9);gl(-.01,4.4,.14,2,1.3,.9);gl(3,6.84,1.5,.14,1.3,.9);
gl(5,6.88,3.8,.05,2.3);gl(5,8.78,3.8,.04,1.1);gl(5,6.9,.04,1.9,1.1);gl(8.76,6.9,.04,1.9,1.1);
function toilet(x,z){b(x,z,.4,.2,.75,WH);const bw=new THREE.Mesh(new THREE.CylinderGeometry(.19,.16,.4,20),M(WH));bw.scale.z=1.35;bw.position.set(x+.2,.2,z+.45);G.add(bw);const o=new THREE.Mesh(bw.geometry,OM);o.scale.set(1.12,1.04,1.51);o.position.copy(bw.position);G.add(o);const ld=new THREE.Mesh(new THREE.CylinderGeometry(.17,.17,.03,20),M(0xe9e6e0));ld.scale.z=1.35;ld.position.set(x+.2,.42,z+.45);G.add(ld)}
function openWard(x,z,w,d){const h=1.5,t=.04;
b(x,z,t,d,h,OAK);b(x+w-t,z,t,d,h,OAK);b(x+w/2-t/2,z,t,d,h,OAK);b(x,z,w,d,t,OAK,h-t);b(x,z+d-.02,w,.02,h,0xefe6d6);
const rc=[WH,GR,SG,0xd9c7a8,0xb8a89a,0xe6e1da];
for(let i=0;i<6;i++)b(x+.09+i*.14,z+.08,.06,d-.2,.75,rc[i],.4);
b(x+t,z+d/2-.01,w/2-t*1.5,.02,.02,BK,1.2);
b(x+w/2+t/2,z,w/2-t*1.5,d,.4,OAK);b(x+w/2+.3,z-.02,.4,.02,.03,BK,.2);
[.45,.8,1.15].forEach((y,i)=>{b(x+w/2+t/2,z,w/2-t*1.5,d,.03,OAK,y);b(x+w/2+.1,z+.08,.5,d-.2,.25,rc[i+1],y+.03)})}
// master bedroom
b(1.0,.1,1.5,2,.42,WH);b(.95,.04,1.6,.08,.9,OAK);b(1.0,.9,1.5,1.2,.5,SG,.0);b(1.1,.2,.5,.3,.12,WH,.42);b(1.9,.2,.5,.3,.12,WH,.42);
b(.4,.1,.4,.4,.45,OAK);b(2.6,.1,.4,.4,.45,OAK);openWard(.1,2.15,2,.6);b(.6,.6,2.6,1.5,.02,0xe9e5dc);plant(3.4,.4,.9);
// bedroom B
b(.1,4.3,1.9,1.5,.42,WH);b(.05,4.25,.08,1.6,.9,OAK);b(.9,4.3,1.1,1.5,.5,GR);b(.15,4.45,.3,.5,.12,WH,.42);b(.15,5.2,.3,.5,.12,WH,.42);b(.1,3.7,.4,.4,.45,OAK);openWard(.1,5.95,2.2,.55);plant(2.1,3.2,.8);
b(.5,3.1,1.6,1,.02,0xe9e5dc);
// guest room C with desk
b(2.55,4.5,.6,1.6,.05,OAK,.72);b(2.58,4.52,.04,.56,.72,OAK);b(2.58,5.54,.04,.56,.72,OAK);
b(3.25,5.0,.45,.45,.45,BK);b(3.65,5.0,.05,.45,.45,BK,.45);b(2.7,4.7,.2,.2,.04,BK,.77);
b(4.0,4.9,.9,1.9,.4,GR);b(4.0,6.7,.9,.1,.8,GR);b(4.1,6.35,.5,.3,.12,WH,.4);plant(4.65,4.4,.7);
// bathrooms
toilet(5.0,.1);b(3.85,.1,.8,.5,.8,WH);toilet(6.7,.1);b(5.55,.1,.8,.5,.8,WH);b(5.6,1.5,.78,1.22,.04,0xaab8bf);gl(5.56,1.4,.84,.04,1.6);gl(6.38,1.43,.04,1.31,1.6);b(6.36,1.4,.06,.06,1.6,BK);b(6.36,2.04,.04,.04,1.6,BK);b(6.36,2.68,.06,.06,1.6,BK);b(5.7,2.2,.08,.08,.04,BK,2.1);
b(3.69,1.6,.12,.9,.04,OAK);b(4.52,1.78,.92,.96,.04,0xaab8bf);gl(4.5,1.72,.94,.04,1.6);gl(4.46,1.75,.04,.99,1.6);b(4.44,1.72,.06,.06,1.6,BK);b(4.44,2.05,.04,.04,1.6,BK);b(4.44,2.7,.06,.06,1.6,BK);b(5.3,2.2,.08,.08,.04,BK,2.1);
// living
b(5.5,4.1,2.6,2.6,.02,0xe9e5dc);
b(7.4,4.3,.85,2.2,.4,GR);b(8.1,4.3,.15,2.2,.85,GR);b(7.4,4.3,.85,.15,.6,GR);b(7.4,6.35,.85,.15,.6,GR);b(7.55,4.6,.5,.7,.12,WH,.4);b(7.55,5.5,.5,.7,.12,SG,.4);
b(6.3,4.9,.6,1,.35,OAK);b(5.02,4.6,.35,1.6,.4,OAK);b(5.02,4.9,.05,1,.6,BK,.9);
plant(5.2,3.2,1.1);
// dining
b(7.3,.55,.8,1.6,.05,OAK,.72);b(7.35,.6,.06,.06,.72,OAK);b(7.99,.6,.06,.06,.72,OAK);b(7.35,2.04,.06,.06,.72,OAK);b(7.99,2.04,.06,.06,.72,OAK);
[[8.15,.55],[8.15,1.1],[8.15,1.65],[7.5,.1],[7.5,2.2]].forEach(p=>b(p[0],p[1],.42,.42,.45,WH));
const lp=new THREE.Mesh(new THREE.CylinderGeometry(.1,.3,.25,16),M(OAK));lp.position.set(7.7,1.9,1.35);G.add(lp);
b(7.69,1.34,.03,.03,.55,BK,2.03);
// kitchen
b(8.3,3.9,1.7,3,.03,0xd9dde0);b(9.4,5.4,.6,1.5,.9,OAK);b(9.4,5.4,.6,1.5,.04,WH,.9);b(9.5,5.55,.4,.6,.02,BK,.94);b(9.5,6.3,.4,.5,.02,GR,.94);
b(9.4,4,.6,.7,1.8,0x4a4e52);b(9.37,4.15,.03,.04,.5,0xc8c8c8,.9);b(9.37,4.55,.03,.04,.5,0xc8c8c8,.9);b(9.4,3.95,.6,.75,.7,0xd6d2cc,1.85);
b(9.92,4.7,.08,.7,2.55,0xece8e2);b(9.4,4.7,.6,.03,2.55,WH);b(9.4,5.37,.6,.03,2.55,WH);
[.35,.8,1.25,1.7,2.15].forEach((y,i)=>{b(9.4,4.7,.55,.7,.03,WH,y);b(9.55,4.78,.18,.2,.22,[0xb88a5a,0x8a5a3a,0xd9c7a8,0x6f8f6f,0xc9a27a][i],y+.03);b(9.55,5.05,.18,.2,.22,[0xd9c7a8,0xb88a5a,0x6f8f6f,0x8a5a3a,0xe8e0d0][i],y+.03)});
b(9.45,5.5,.5,.7,.3,GR,1.7);b(9.62,5.7,.16,.16,.6,GR,2.0);rgl(8.28,3.9,.05,3,2.6);rgl(9.2,3.88,.8,.05,2.6);rgl(8.35,3.86,.81,.04,2.4);b(8.35,3.84,.81,.06,.05,WH,2.4);b(8.35,3.84,.81,.06,.04,WH,0);b(8.26,3.86,.09,.09,2.6,WH);b(9.16,3.86,.09,.09,2.6,WH);b(8.26,3.9,.06,3,.04,WH,2.56);
// balcony
b(8.1,6.95,.65,.65,.9,WH);const wd=new THREE.Mesh(new THREE.CylinderGeometry(.2,.2,.04,24),M(0x59656b));wd.rotation.x=Math.PI/2;wd.position.set(8.425,.45,7.62);G.add(wd);
b(5.5,7.98,.04,.04,1.9,BK);b(7.9,7.98,.04,.04,1.9,BK);b(5.5,7.98,2.44,.03,.03,GR,1.85);
for(let i=0;i<9;i++)b(5.65+i*.25,7.81,.04,.34,.75,[WH,GR,0xd9c7a8,0x9db7a2,0xb8a89a][i%5],1.08);plant(8.4,8.4,1.3);plant(8.4,7.2,.9);
// labels
const labels=new THREE.Group();sc.add(labels);
const tagEl=document.getElementById('tags'),tagList=[];
function lab(t,x,z){const d=document.createElement('div');d.className='tag';d.textContent=t+' ›';tagEl.appendChild(d);tagList.push({d,v:new THREE.Vector3(x,1.7,z)})}
function place(){tagList.forEach(o=>{const p=o.v.clone().project(cam);o.d.style.left=((p.x+1)/2*innerWidth)+'px';o.d.style.top=((1-p.y)/2*innerHeight)+'px';o.d.style.display=p.z<1?'block':'none'})}
function labOld(t,x,z){const k=document.createElement('canvas');k.width=256;k.height=96;const g=k.getContext('2d');
g.font='bold 42px sans-serif';g.textAlign='center';g.textBaseline='middle';g.lineWidth=8;g.strokeStyle='rgba(255,255,255,.9)';g.strokeText(t,128,48);g.fillStyle='#2f3236';g.fillText(t,128,48);
const m=new THREE.Mesh(new THREE.PlaneGeometry(1.6,.6),new THREE.MeshBasicMaterial({map:new THREE.CanvasTexture(k),transparent:true}));
m.rotation.x=-Math.PI/2;m.position.set(x,.05,z);labels.add(m)}
lab('主臥',1.9,2.4);lab('次臥',1.25,3.4);lab('客房＋書桌',3.9,5.55);lab('主臥浴室',4.6,2.2);lab('公共衛浴',6.3,2.2);
lab('客廳',6.4,6.55);lab('餐廳',7.7,1.35);lab('廚房',8.85,5.6);lab('陽台',6.5,8.45);lab('洗衣機',8.4,7.3);lab('曬衣區',6.7,8.0);lab('玄關',8.6,-2.6);lab('收納牆',9.8,.5);lab('大門',8.8,-4.1);lab('冰箱',9.7,4.35);lab('廚房收納',9.7,5.05);
// camera
let auto=true,th=0,ph=.9,rad=16;const tg=new THREE.Vector3(5,0,2.6);let dirty=true;
const req=()=>{dirty=true};
function fit(){return Math.min(45,Math.max(17,11.5/(.728*cam.aspect)))}
function upd(){cam.position.set(tg.x+rad*Math.sin(ph)*Math.sin(th),rad*Math.cos(ph),tg.z+rad*Math.sin(ph)*Math.cos(th));cam.lookAt(tg);req()}
function rs(){r.setPixelRatio(Math.min(devicePixelRatio,2));r.setSize(innerWidth,innerHeight);cam.aspect=innerWidth/innerHeight;cam.updateProjectionMatrix();rad=fit()*(ph<.3?1:.92);upd()}
addEventListener('resize',rs);
const bg=()=>{sc.background=new THREE.Color(getComputedStyle(document.body).backgroundColor);req()};
matchMedia('(prefers-color-scheme: dark)').addEventListener('change',()=>setTimeout(bg,50));
const pts=new Map();let pd=0;
cv.addEventListener('pointerdown',e=>{auto=false;$('b5').classList.remove('on');cv.setPointerCapture(e.pointerId);pts.set(e.pointerId,e)});
cv.addEventListener('pointerup',e=>{pts.delete(e.pointerId);pd=0});
cv.addEventListener('pointermove',e=>{const p=pts.get(e.pointerId);if(!p)return;
if(pts.size===1){th-=(e.clientX-p.clientX)*.008;ph=Math.min(1.45,Math.max(.05,ph-(e.clientY-p.clientY)*.006))}
else if(pts.size===2){pts.set(e.pointerId,e);const a=[...pts.values()],d=Math.hypot(a[0].clientX-a[1].clientX,a[0].clientY-a[1].clientY);if(pd)rad=Math.min(45,Math.max(4,rad*pd/d));pd=d}
pts.set(e.pointerId,e);upd()});
cv.addEventListener('wheel',e=>{e.preventDefault();rad=Math.min(45,Math.max(4,rad*(1+e.deltaY*.001)));upd()},{passive:false});
const $=i=>document.getElementById(i);
$('b1').onclick=()=>{auto=false;$('b5').classList.remove('on');th=0;ph=.05;rad=fit();upd()};
$('b2').onclick=()=>{auto=false;$('b5').classList.remove('on');th=-.35;ph=.9;rad=fit()*.92;upd()};
$('b3').onclick=e=>{const full=WH_<2;setH(full?2.6:.9);e.target.textContent=full?'全高牆':'矮牆';e.target.classList.toggle('on',!full);req()};
$('b4').onclick=e=>{labels.visible=!labels.visible;tagEl.style.display=labels.visible?'block':'none';e.target.classList.toggle('on',labels.visible);req()};
$('b5').onclick=e=>{auto=!auto;e.target.classList.toggle('on',auto)};
bg();rs();
(function loop(){requestAnimationFrame(loop);if(auto){th+=.004;upd()}if(dirty){dirty=false;r.render(sc,cam);place()}})();
</script></body></html>
