[index (1).html](https://github.com/user-attachments/files/33029578/index.1.html)
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Список желаний 2026–2030</title>
<meta name="description" content="101 желание на 2026–2030: личное исследование того, чего я на самом деле хочу.">
<meta property="og:image" content="hero.png">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;1,400&family=Inter:wght@400;500&display=swap" rel="stylesheet">
<style>
:root{--cream:#f6efe4;--beige:#e9dcc6;--brown:#3a2a21;--soft:#7a6657;--olive:#7d8761;--pink:#c98791;--line:#d9c9b0;
--serif:"Cormorant Garamond",Georgia,serif;--sans:Inter,system-ui,sans-serif}
*{box-sizing:border-box;margin:0}
html{scroll-behavior:smooth;scroll-padding-top:64px}
body{background:var(--cream);color:var(--brown);font:16px/1.55 var(--sans);overflow-x:hidden}
button{font:inherit;color:inherit;background:none;border:0;cursor:pointer}
:focus-visible{outline:2px solid var(--pink);outline-offset:2px}
h1,h2{font-family:var(--serif);font-weight:400;line-height:1.05}
section{padding:96px 24px;max-width:1180px;margin:0 auto}
h2{font-size:clamp(34px,5vw,56px);margin-bottom:14px}
.lead{max-width:60ch;color:var(--soft);font-family:var(--serif);font-size:21px;margin-bottom:44px}

nav{position:fixed;inset:0 0 auto 0;z-index:20;display:flex;justify-content:space-between;align-items:center;padding:14px 24px;color:#fff;transition:.3s}
nav.solid{background:rgba(246,239,228,.95);color:var(--brown);border-bottom:1px solid var(--line)}
nav .links{display:flex;gap:22px;font-size:14px}
nav a{color:inherit;text-decoration:none}
nav .brand{font-family:var(--serif);font-size:20px}
.fab{position:fixed;right:16px;bottom:16px;z-index:20;background:var(--brown);color:var(--cream);padding:8px 16px;border-radius:99px;font-size:14px;font-variant-numeric:tabular-nums}

.hero{min-height:100svh;max-width:none;padding:0 24px;display:flex;align-items:flex-end;position:relative;color:#fff;
background:linear-gradient(180deg,rgba(40,24,14,.25),rgba(40,24,14,.7)),url(hero.png) center 35%/cover}
.hero div{max-width:1180px;margin:0 auto;width:100%;padding-bottom:9vh}
.hero h1{font-size:clamp(48px,9vw,128px);animation:rise 1.2s ease both}
.hero h1 i{display:block;font-size:.62em;margin-top:.1em}
.hero p{max-width:46ch;font-size:19px;margin:22px 0 30px;opacity:.92}
.btn{display:inline-block;background:var(--cream);color:var(--brown);padding:14px 30px;border-radius:99px;text-decoration:none;font-weight:500}
.btn:hover{background:#fff}
@keyframes rise{from{opacity:0;transform:translateY(24px)}}

.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
.card{background:#fbf7ef;border:1px solid var(--line);border-radius:6px;display:flex;flex-direction:column;height:480px}
.card header{padding:20px 22px 12px;border-bottom:1px solid var(--line)}
.card h3{font:400 28px var(--serif)}
.card small{color:var(--soft);font-size:13px}
.card ul{list-style:none;padding:8px 14px 14px;overflow:auto;flex:1;scrollbar-width:thin;scrollbar-color:var(--line) transparent}
.w{display:grid;grid-template-columns:22px 26px 1fr auto;gap:8px;align-items:start;padding:9px 6px;border-bottom:1px dashed var(--line);font-size:14.5px;line-height:1.4}
.w:last-child{border:0}
.n{color:var(--soft);font-size:12px;padding-top:2px;font-variant-numeric:tabular-nums}
.ck{width:18px;height:18px;margin-top:1px;border:1.5px solid var(--soft);border-radius:50%;transition:.25s}
.ck:disabled{cursor:default}
.owner .ck{cursor:pointer;border-color:var(--pink)}
.w.done .ck{background:var(--pink);border-color:var(--pink);transform:scale(1.1)}
.w.done .t{color:var(--soft);text-decoration:line-through;text-decoration-color:var(--pink)}
.lk{display:flex;align-items:center;gap:4px;font-size:12px;color:var(--soft);padding:0 2px}
.lk svg{width:16px;height:16px;fill:none;stroke:var(--soft);stroke-width:1.8;transition:.2s}
.lk.on svg{fill:var(--pink);stroke:var(--pink)}
.lk.pop svg{animation:pop .4s}
@keyframes pop{50%{transform:scale(1.5)}}

.prog{background:var(--beige);max-width:none}
.prog>div{max-width:1180px;margin:0 auto;display:grid;grid-template-columns:1fr 1fr;gap:40px;align-items:center}
.count{font:400 clamp(64px,10vw,120px)/1 var(--serif)}
.count span{color:var(--soft);font-size:.5em}
.stats{display:flex;gap:36px;margin:28px 0}
.stats b{display:block;font:400 40px var(--serif)}
.stats span{font-size:13px;color:var(--soft)}
.cap{color:var(--soft);font-family:var(--serif);font-size:20px;max-width:34ch}
#heart{position:relative;width:min(100%,440px);aspect-ratio:1/.95;margin:0 auto}
#heart i{position:absolute;border-radius:50%;border:1.5px solid var(--olive);background:transparent;transform:translate(-50%,-50%);transition:background .6s,border-color .6s}
#heart i.f{background:var(--pink);border-color:var(--pink)}
#heart .r{transition:transform 1s}

.masonry{columns:3 280px;column-gap:20px}
.rep{break-inside:avoid;margin-bottom:20px;background:#fbf7ef;border:1px solid var(--line);border-radius:6px;overflow:hidden;cursor:pointer;display:block;width:100%;text-align:left}
.rep:hover img{transform:scale(1.04)}
.rep .im{overflow:hidden;background:linear-gradient(135deg,var(--beige),#d8c6b0);aspect-ratio:4/5}
.rep img{width:100%;height:100%;object-fit:cover;display:block;transition:.5s}
.rep div.b{padding:16px 18px 20px}
.rep h4{font:400 24px/1.15 var(--serif);margin:4px 0 6px}
.rep small{color:var(--soft)}
.empty{text-align:center;padding:60px 20px;border:1px dashed var(--line);border-radius:6px}
.empty p{font:italic 32px/1.2 var(--serif);color:var(--soft)}
.empty svg{width:120px;margin-bottom:12px}

#modal{position:fixed;inset:0;z-index:50;background:rgba(40,24,14,.8);display:none;align-items:center;justify-content:center;padding:24px}
#modal.open{display:flex}
.mb{background:var(--cream);max-width:760px;width:100%;max-height:92vh;overflow:auto;border-radius:6px;position:relative}
.mb img{width:100%;display:block}
.mb .tx{padding:28px 32px 36px}
.mb h3{font:400 38px/1.1 var(--serif);margin:6px 0 4px}
.mb p{margin-top:16px;white-space:pre-line}
.x{position:absolute;right:12px;top:12px;width:38px;height:38px;border-radius:50%;background:var(--cream);font-size:22px;z-index:2}

footer{background:var(--brown);color:var(--cream);max-width:none;text-align:center;padding:64px 24px}
footer h3{font:400 34px var(--serif)}
footer p{opacity:.75;margin:8px 0 24px}
.soc{display:flex;gap:14px;justify-content:center}
.soc a{width:44px;height:44px;border:1px solid rgba(246,239,228,.4);border-radius:50%;display:grid;place-items:center}
.soc a:hover{background:var(--pink);border-color:var(--pink)}
.soc svg{width:20px;height:20px;fill:none;stroke:var(--cream);stroke-width:1.7}
.ob{margin:20px 0 0;font-size:13px}

@media(max-width:900px){.grid{grid-template-columns:repeat(2,1fr)}.prog>div{grid-template-columns:1fr}}
@media(max-width:600px){.grid{grid-template-columns:1fr}.card{height:420px}nav .links{gap:14px;font-size:13px}nav .brand{display:none}
section{padding:72px 18px}.mb{max-height:100vh;height:100%;border-radius:0}#modal{padding:0}}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important;scroll-behavior:auto!important}}
</style>
</head>
<body>
<nav id="nav"><a class="brand" href="#top">Go create</a>
  <div class="links"><a href="#wishes">Желания</a><a href="#progress">Прогресс</a><a href="#reports">Отчёт</a><a href="#contacts">Контакты</a></div></nav>
<div class="fab" id="fab">0 / 101</div>

<header class="hero" id="top"><div>
  <h1>Go create <i>new experience</i></h1>
  <p>Список желаний 2026–2030 для внутреннего исследования: чего я на самом деле хочу.</p>
  <a class="btn" href="#wishes">Посмотреть список</a>
</div></header>

<section id="wishes">
  <h2>Мой список желаний</h2>
  <p class="lead">101 желание — не план на пятилетку и не список достижений. Скорее способ посмотреть на себя со стороны и понять, куда мне действительно хочется.</p>
  <div class="grid" id="grid"></div>
</section>

<section class="prog" id="progress"><div>
  <div>
    <h2>Желания исполнены</h2>
    <div class="count" id="count">0<span> / 101</span></div>
    <div class="stats">
      <div><b>101</b><span>желание</span></div>
      <div><b id="sDone">0</b><span>исполнено</span></div>
      <div><b id="sPct">0%</b><span>пути пройдено</span></div>
    </div>
    <p class="cap">Каждое исполненное желание — ещё один кусочек жизни, который становится реальностью.</p>
  </div>
  <div id="heart" aria-label="Сердце из 101 кружка"></div>
</div></section>

<section id="reports">
  <h2>Отчёт об исполнении</h2>
  <p class="lead">Не просто галочки. Истории о том, как желания становятся воспоминаниями.</p>
  <div id="reps"></div>
</section>

<footer id="contacts">
  <h3>Солянникова Олеся</h3>
  <p>101 желание. 5 лет. И одна жизнь, чтобы всё это попробовать.</p>
  <div class="soc" id="soc"></div>
  <div class="ob" id="ob"></div>
</footer>

<div id="modal"><div class="mb" id="mb"></div></div>

<script src="data.js"></script>
<script>
(function(){
const $=s=>document.querySelector(s);
const OWNER=new URLSearchParams(location.search).has('owner');
const ld=k=>{try{return JSON.parse(localStorage.getItem(k))||{}}catch(e){return {}}};
const sv=(k,v)=>{try{localStorage.setItem(k,JSON.stringify(v))}catch(e){}};
let localDone=ld('wl_done'), liked=ld('wl_liked');
const TOTAL=WISHES.reduce((a,c)=>a+c.items.length,0);
let n=0; const flat=[];
WISHES.forEach(c=>c.items.forEach(t=>flat.push({n:++n,cat:c.cat,t})));
const isDone=i=>DONE.includes(i)||!!REPORTS[i]||(OWNER&&!!localDone[i]);
const HEART='<svg viewBox="0 0 24 24"><path d="M12 21s-7.5-4.6-9.5-9.3C1.2 8.4 3 5 6.4 5c2 0 3.6 1.1 5.6 3.2C14 6.1 15.600 5 17.600 5 21 5 22.800 8.400 21.500 11.700 19.500 16.400 12 21 12 21z"/></svg>';

/* карточки */
const grid=$('#grid');
WISHES.forEach(c=>{
  const card=document.createElement('article');card.className='card'+(OWNER?' owner':'');
  card.innerHTML='<header><h3>'+c.cat+'</h3><small></small></header><ul></ul>';
  const ul=card.querySelector('ul');
  flat.filter(w=>w.cat===c.cat).forEach(w=>{
    const li=document.createElement('li');li.className='w';li.dataset.n=w.n;
    li.innerHTML='<button class="ck" '+(OWNER?'':'disabled ')+'aria-label="Исполнено"></button><span class="n">'+String(w.n).padStart(2,'0')+'</span><span class="t"></span><button class="lk" aria-label="Нравится">'+HEART+'<span></span></button>';
    li.querySelector('.t').textContent=w.t;
    ul.appendChild(li);
  });
  card._small=card.querySelector('small');card._cat=c.cat;
  grid.appendChild(card);
});
grid.addEventListener('click',e=>{
  const li=e.target.closest('.w');if(!li)return;const i=+li.dataset.n;
  if(e.target.closest('.ck')&&OWNER){localDone[i]=!localDone[i];sv('wl_done',localDone);render()}
  if(e.target.closest('.lk')){liked[i]=!liked[i];sv('wl_liked',liked);const b=li.querySelector('.lk');render();
    const nb=grid.querySelector('.w[data-n="'+i+'"] .lk');nb.classList.add('pop')}
});

/* сердце: ячейки внутри формулы сердца, «трещина» посередине */
const heart=$('#heart');
const inH=(x,y)=>Math.pow(x*x+y*y-1,3)-x*x*y*y*y<=0;
const crack=(x,y,s)=>Math.abs(x-0.18*Math.sin(y*5))<s*.6;
let cells=[];
for(let s=0.3;s>0.08;s-=0.002){
  cells=[];
  for(let y=1.3;y>=-1.3;y-=s)for(let x=-1.3;x<=1.3;x+=s){const xx=x+(Math.round(y/s)%2?s/2:0);
    if(inH(xx,y)&&!crack(xx,y,s))cells.push({x:xx,y,s})}
  if(cells.length>=TOTAL)break;
}
cells.sort((a,b)=>(b.x*b.x+b.y*b.y)-(a.x*a.x+a.y*a.y));
cells=cells.slice(cells.length-TOTAL);               /* убираем лишние по краям */
cells.sort((a,b)=>b.y-a.y||a.x-b.x);                  /* порядок заполнения: сверху вниз */
const sz=cells[0].s;
cells.forEach(c=>{
  const d=document.createElement('i');
  d.style.left=((c.x+1.3)/2.6*100)+'%';d.style.top=((1.3-c.y)/2.6*100*1.0-8)+'%';
  d.style.width=d.style.height=(sz/2.6*100*.78)+'%';
  d.style.aspectRatio='1';d.style.height='auto';
  d.className=c.x>0?'r right':'r left';
  heart.appendChild(d);
});
const dots=[...heart.children];

function render(){
  const done=flat.filter(w=>isDone(w.n)).length, pct=Math.round(done/TOTAL*100);
  document.querySelectorAll('.w').forEach(li=>{
    const i=+li.dataset.n;li.classList.toggle('done',isDone(i));
    const l=li.querySelector('.lk');l.classList.toggle('on',!!liked[i]);l.classList.remove('pop');
    l.querySelector('span').textContent=liked[i]?1:0;
  });
  document.querySelectorAll('.card').forEach(c=>{
    const ws=flat.filter(w=>w.cat===c._cat),d=ws.filter(w=>isDone(w.n)).length;
    c._small.textContent=ws.length+' желаний, исполнено '+d;
  });
  $('#count').innerHTML=done+'<span> / '+TOTAL+'</span>';
  $('#fab').textContent=done+' / '+TOTAL;
  $('#sDone').textContent=done;$('#sPct').textContent=pct+'%';
  dots.forEach((d,k)=>d.classList.toggle('f',k<done));
  const gap=(1-done/TOTAL)*10;                         /* половинки сходятся */
  dots.forEach(d=>d.style.transform='translate(calc(-50% '+(d.classList.contains('right')?'+':'-')+' '+gap+'px),-50%)');
  if(OWNER)$('#ob').innerHTML='Режим владельца. Вставь в data.js: <code>window.DONE = ['+flat.filter(w=>isDone(w.n)).map(w=>w.n)+'];</code>';
}
render();

/* отчёты */
const reps=$('#reps'),keys=Object.keys(REPORTS);
if(!keys.length){
  reps.innerHTML='<div class="empty"><svg viewBox="0 0 120 80" fill="none" stroke="#c98791" stroke-width="1.5"><path d="M10 70 L45 25 L65 50 L80 35 L110 70 Z"/><circle cx="92" cy="18" r="8"/></svg><p>Здесь пока пусто.<br>Но это ненадолго.</p></div>';
}else{
  reps.className='masonry';
  keys.forEach(k=>{
    const r=REPORTS[k],w=flat[k-1]||{t:''},b=document.createElement('button');b.className='rep';
    const ph=(r.photos||[])[0];
    b.innerHTML=(ph?'<div class="im"><img src="'+ph+'" alt="" loading="lazy"></div>':'')+'<div class="b"><small>№'+k+'</small><h4></h4><small></small></div>';
    b.querySelector('h4').textContent=w.t;
    b.querySelectorAll('small')[1].textContent=[r.location,r.date].filter(Boolean).join(' · ');
    b.onclick=()=>openM(k);reps.appendChild(b);
  });
}
const modal=$('#modal'),mb=$('#mb');
function openM(k){
  const r=REPORTS[k],w=flat[k-1];
  mb.innerHTML='<button class="x" aria-label="Закрыть">×</button>';
  (r.photos||[]).forEach(p=>{const im=new Image();im.src=p;im.alt='';mb.appendChild(im)});
  const t=document.createElement('div');t.className='tx';
  t.innerHTML='<small>№'+k+'</small><h3></h3><small></small><p></p>';
  t.querySelector('h3').textContent=w.t;
  t.querySelectorAll('small')[1].textContent=[r.location,r.date].filter(Boolean).join(' · ');
  t.querySelector('p').textContent=r.story||'';
  mb.appendChild(t);modal.classList.add('open');document.body.style.overflow='hidden';
}
function closeM(){modal.classList.remove('open');document.body.style.overflow=''}
modal.addEventListener('click',e=>{if(e.target===modal||e.target.closest('.x'))closeM()});
addEventListener('keydown',e=>{if(e.key==='Escape')closeM()});

/* соцсети */
const ic={instagram:'<rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.500" cy="6.500" r=".6"/>',
telegram:'<path d="M21 4 3 11l5 2 2 6 3-4 5 4z"/><path d="M8 13l9-6"/>',
threads:'<path d="M17 8.500C16 5 11 4 8.500 7S6 15 9 18s8 1 8-3-6-3-6-1 3 2 4 0"/>'};
$('#soc').innerHTML=Object.keys(ic).map(k=>'<a href="'+SOCIAL[k]+'" aria-label="'+k+'" target="_blank" rel="noopener"><svg viewBox="0 0 24 24">'+ic[k]+'</svg></a>').join('');

/* навигация */
const nav=$('#nav'),onS=()=>nav.classList.toggle('solid',scrollY>innerHeight*.7);
addEventListener('scroll',onS,{passive:true});onS();
})();
</script>
</body>
</html>
