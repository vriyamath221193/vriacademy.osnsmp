<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>VriAcademy – Olimpiade Matematika SMP</title>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@600;800&family=Nunito+Sans:wght@400;600;700&display=swap" rel="stylesheet">
<script>window.MathJax={tex:{inlineMath:[['$','$']],displayMath:[['$$','$$']]},svg:{fontCache:'global'},options:{enableMenu:false}};</script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/3.2.2/es5/tex-svg.min.js" async></script>
<style>
:root{--paper:#f4f7fc;--surface:#fff;--ink:#0f1e3d;--muted:#52607a;--line:#d5deee;--blue:#2447d6;--blue-soft:#e4eafc;--gold:#f5b83d;--mint:#0e8f7e;--grid:rgba(36,71,214,.07);
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);color-scheme:light}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--paper:#0c1428;--surface:#142042;--ink:#eaf0ff;--muted:#a3b1d1;--line:#27365f;--blue:#7d9bff;--blue-soft:#1b2a57;--gold:#f5b83d;--mint:#43d1bd;--grid:rgba(125,155,255,.08);color-scheme:dark}}
:root[data-theme="dark"]{--paper:#0c1428;--surface:#142042;--ink:#eaf0ff;--muted:#a3b1d1;--line:#27365f;--blue:#7d9bff;--blue-soft:#1b2a57;--gold:#f5b83d;--mint:#43d1bd;--grid:rgba(125,155,255,.08);color-scheme:dark}
html{scroll-behavior:smooth;scroll-padding-top:calc(env(safe-area-inset-top,0px) + 70px)}
*{box-sizing:border-box}
body{margin:0;background:var(--paper);color:var(--ink);font:400 1.05rem/1.65 "Nunito Sans",system-ui,sans-serif}
h1,h2,h3{font-family:"Bricolage Grotesque","Trebuchet MS",sans-serif;line-height:1.15;margin:0}
a{color:inherit;text-decoration:none}
button{font:inherit;cursor:pointer}
:focus-visible{outline:3px solid var(--gold);outline-offset:2px}
.wrap{max-width:1080px;margin:0 auto;padding:0 20px}
header{position:sticky;top:0;z-index:20;background:var(--paper);border-bottom:1px solid var(--line);padding-top:env(safe-area-inset-top,0px)}
header .wrap{display:flex;align-items:center;justify-content:space-between;height:60px}
.logo{font:800 1.3rem "Bricolage Grotesque",sans-serif;display:flex;align-items:center;gap:9px}
.logo i{width:30px;height:30px;border-radius:8px;background:var(--blue);color:#fff;display:grid;place-items:center;font:800 1rem "Bricolage Grotesque",sans-serif;font-style:normal}
nav{display:flex;gap:22px;font-weight:700;font-size:.95rem}
nav a{color:var(--muted)}nav a:hover{color:var(--blue)}
.hero{background-image:linear-gradient(var(--grid) 1px,transparent 1px),linear-gradient(90deg,var(--grid) 1px,transparent 1px);background-size:32px 32px;padding:64px 0 72px}
.hero .wrap{display:grid;grid-template-columns:1.1fr .9fr;gap:44px;align-items:center}
.hero h1{font-size:clamp(2.2rem,5.2vw,3.6rem);font-weight:800;letter-spacing:-.02em}
.hero p.lead{color:var(--muted);font-size:1.15rem;max-width:34em;margin:18px 0 26px}
.btn{display:inline-block;background:var(--blue);color:#fff;border:0;padding:13px 24px;border-radius:10px;font-weight:700}
:root[data-theme="dark"] .btn{color:#0c1428}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]) .btn{color:#0c1428}}
.btn.ghost{background:transparent;color:var(--ink);border:2px solid var(--line);margin-left:8px}
.stats{display:flex;gap:30px;margin-top:34px;color:var(--muted);font-size:.95rem}
.stats b{display:block;font:800 1.5rem "Bricolage Grotesque",sans-serif;color:var(--ink)}
.card{background:var(--surface);border:1px solid var(--line);border-radius:16px;padding:24px}
.warm{border-top:6px solid var(--gold);box-shadow:6px 6px 0 var(--blue-soft)}
.warm h3{font-size:1.15rem;margin-bottom:10px}
.warm .q{font-size:1.25rem;font-weight:700;margin:6px 0 16px}
.row{display:flex;gap:8px}
input{flex:1;min-width:0;padding:11px 14px;border:2px solid var(--line);border-radius:10px;font:inherit;background:var(--paper);color:var(--ink)}
.fb{min-height:1.6em;margin:10px 0 0;font-weight:700}
.ok{color:var(--mint)}.no{color:#d6453d}
section{padding:68px 0}
h2{font-size:clamp(1.7rem,3.5vw,2.3rem);font-weight:800;margin-bottom:10px}
.sub{color:var(--muted);max-width:38em;margin:0 0 30px}
.tabs{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:20px}
.tab{background:var(--surface);border:2px solid var(--line);color:var(--ink);padding:10px 18px;border-radius:999px;font-weight:700}
.tab[aria-selected="true"]{background:var(--blue);border-color:var(--blue);color:#fff}
:root[data-theme="dark"] .tab[aria-selected="true"]{color:#0c1428}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]) .tab[aria-selected="true"]{color:#0c1428}}
.panel{display:grid;grid-template-columns:1fr 1fr;gap:20px}
.panel h3{font-size:1.2rem;margin-bottom:12px}
.panel ul{margin:0;padding-left:20px}.panel li{margin-bottom:8px}
.formula{background:var(--blue-soft);border-radius:10px;padding:10px 14px;margin:10px 0;font-weight:700}
.prob{border-top:1px dashed var(--line);padding-top:14px;margin-top:14px}
.prob:first-of-type{border:0;padding:0;margin:0}
.prob p{margin:0 0 8px;font-weight:600}
.sol{background:transparent;border:2px solid var(--mint);color:var(--mint);border-radius:8px;padding:6px 14px;font-weight:700;font-size:.9rem}
.sol[aria-expanded="true"]{background:var(--mint);color:var(--paper)}
.ans{display:none;margin-top:10px;padding:12px 14px;background:var(--paper);border-left:4px solid var(--mint);border-radius:0 10px 10px 0;font-size:.98rem}
.ans.open{display:block}
.band{background:var(--surface);border-block:1px solid var(--line)}
.steps{display:grid;grid-template-columns:repeat(4,1fr);gap:16px}
.steps .card{padding:20px}.steps h3{font-size:1.05rem;margin-bottom:6px}.steps p{margin:0;color:var(--muted);font-size:.95rem}
.n{display:inline-grid;place-items:center;width:30px;height:30px;border-radius:50%;background:var(--gold);color:#0f1e3d;font-weight:800;margin-bottom:10px}
footer{padding:36px 0;color:var(--muted);font-size:.92rem}
footer .wrap{display:flex;justify-content:space-between;flex-wrap:wrap;gap:12px}
.opt{display:block;width:100%;text-align:left;background:var(--paper);border:2px solid var(--line);color:var(--ink);border-radius:10px;padding:11px 14px;margin-top:8px}.opt:hover:not(:disabled){border-color:var(--blue)}.opt:disabled{cursor:default}.opt.good{border-color:var(--mint);background:var(--blue-soft)}.opt.bad{border-color:#d6453d}.qm{display:flex;justify-content:space-between;color:var(--muted);font-weight:700;font-size:.92rem;margin-bottom:8px}.bar{height:8px;background:var(--line);border-radius:99px;overflow:hidden;margin-bottom:18px}.bar i{display:block;height:100%;background:var(--gold);transition:width .3s}.score{font:800 3rem 'Bricolage Grotesque',sans-serif;color:var(--blue)}.panel{grid-template-columns:1.1fr .9fr;align-items:start}
details{border:1px solid var(--line);border-radius:12px;background:var(--surface);margin-bottom:10px;padding:0 16px}
summary{cursor:pointer;font:700 1.05rem 'Bricolage Grotesque',sans-serif;padding:14px 0}
details[open] summary{border-bottom:1px dashed var(--line);margin-bottom:10px}
details ul{margin:0 0 12px;padding-left:20px}details li{margin-bottom:10px}
.tip{background:var(--blue-soft);border-left:4px solid var(--gold);border-radius:0 10px 10px 0;padding:12px 16px;margin:14px 0}
mjx-container{max-width:100%;overflow-x:auto;overflow-y:hidden}
.fig{margin:8px 0 0}.fig svg{display:block;width:100%;max-width:240px;height:auto;fill:none;stroke:var(--ink);stroke-width:2;stroke-linejoin:round}.fig .f{fill:var(--blue-soft)}.fig .d{stroke:var(--blue);stroke-dasharray:5 4}.fig .k{fill:var(--ink)}.fig text{fill:var(--ink);stroke:none;font:700 13px 'Nunito Sans',sans-serif}.fig figcaption{font-size:.88rem;color:var(--muted);margin-top:2px}
.chips{display:flex;gap:6px;flex-wrap:wrap;margin-bottom:14px}.chip{border:1.5px solid var(--line);background:var(--paper);color:var(--ink);border-radius:999px;padding:4px 12px;font-size:.85rem;font-weight:700;cursor:pointer}.chip[aria-pressed="true"]{background:var(--ink);border-color:var(--ink);color:var(--paper)}
.lv{display:inline-block;border-radius:6px;padding:1px 8px;font-size:.78rem;font-weight:800;margin-right:6px;color:#0f1e3d}.lvD{background:var(--blue-soft);color:var(--ink)}.lvK{background:#bde8df}.lvP{background:#ffe3a3}.lvN{background:#ffc9c4}
.hall{display:grid;grid-template-columns:1.25fr .75fr;gap:26px;align-items:center;padding:18px}
@media (max-width:820px){.hall{grid-template-columns:1fr}}
@media (max-width:820px){.hero .wrap,.panel,.steps{grid-template-columns:1fr}nav{display:none}.hero{padding:40px 0 48px}.stats{gap:20px}}
@media (prefers-reduced-motion:reduce){html{scroll-behavior:auto}}
</style>
</head>
<body>
<header><div class="wrap">
<a href="#atas" class="logo"><i>∑</i>VriAcademy</a>
<nav><a href="#materi">Materi</a><a href="#kuis">Kuis</a><a href="#alur">Cara belajar</a><a href="#kontak">Kontak</a></nav>
</div></header>

<main id="atas">
<div class="hero"><div class="wrap">
<div>
<h1>Latihan olimpiade matematika SMP, dari dasar sampai level OSN.</h1>
<p class="lead">Materi ringkas, soal bertingkat, dan pembahasan langkah demi langkah untuk siswa SMP yang ingin lolos OSN dan kompetisi matematika lainnya.</p>
<a class="btn" href="#materi">Mulai belajar</a><a class="btn ghost" href="#alur">Lihat alur belajar</a>
<div class="stats"><div><b>5</b>topik utama</div><div><b>64</b>soal berpembahasan</div><div><b>Gratis</b>diakses kapan saja</div></div>
</div>
<div class="card warm" role="group" aria-labelledby="pt">
<h3 id="pt">Soal pemanasan</h3>
<div class="q">Berapa angka satuan dari $7^{2026}$?</div>
<div class="row"><input id="jw" inputmode="numeric" placeholder="Jawabanmu" aria-label="Jawaban"><button class="btn" id="cek" type="button">Periksa</button></div>
<p class="fb" id="fb" aria-live="polite"></p>
<button class="sol" id="hs" type="button" aria-expanded="false">Lihat pembahasan</button>
<div class="ans" id="hsa">Angka satuan $7^n$ berulang tiap 4: $7,9,3,1$. Karena $2026\equiv2\pmod4$, angka satuannya sama dengan $7^2=49$, yaitu <b>9</b>.</div>
</div>
</div></div>

<section id="juara" style="padding:44px 0 0"><div class="wrap"><div class="card hall">
<svg viewBox="0 0 640 310" role="img" aria-label="Kartun tiga siswa juara di podium mengangkat tangan dan memakai medali emas, perak, dan perunggu olimpiade matematika" style="width:100%;height:auto;border-radius:14px">
<defs><linearGradient id="sky" x1="0" y1="0" x2="0" y2="1"><stop offset="0" stop-color="#cfdcff"/><stop offset="1" stop-color="#f4f7ff"/></linearGradient>
<g id="kid"><rect x="-16" y="-14" width="13" height="14" fill="#25324f"/><rect x="3" y="-14" width="13" height="14" fill="#25324f"/><path d="M-22 -52L-42 -84M22 -52L42 -84" stroke-width="10" stroke-linecap="round" fill="none" style="stroke:var(--skin)"/><rect x="-24" y="-62" width="48" height="50" rx="14" style="fill:var(--shirt)"/><path d="M-8 -62L0 -44L8 -62Z" fill="#d6453d"/><circle cy="-40" r="10" style="fill:var(--medal)" stroke="#0003" stroke-width="2"/><text y="-36" font-size="12" text-anchor="middle" fill="#fff">★</text><circle cy="-90" r="27" style="fill:var(--skin)"/><path d="M-28 -92a28 28 0 0 1 56 0q-14 -14 -28 -8q-14 -6 -28 8Z" style="fill:var(--hair)"/><circle cx="-10" cy="-88" r="4.5" fill="#1b1b1b"/><circle cx="10" cy="-88" r="4.5" fill="#1b1b1b"/><circle cx="-8.5" cy="-89.5" r="1.5" fill="#fff"/><circle cx="11.5" cy="-89.5" r="1.5" fill="#fff"/><path d="M-11 -78Q0 -64 11 -78Z" fill="#8c2f2f"/><circle cx="-18" cy="-80" r="4.5" fill="#ff8f8f" opacity=".55"/><circle cx="18" cy="-80" r="4.5" fill="#ff8f8f" opacity=".55"/></g>
<g id="k1" style="--shirt:#2447d6;--skin:#f1c27d;--hair:#2b1b12;--medal:#aab6cf"><use href="#kid"/><circle cx="-31" cy="-84" r="9" style="fill:var(--hair)"/><circle cx="31" cy="-84" r="9" style="fill:var(--hair)"/><path d="M-7 -118L0 -112L-7 -106ZM7 -118L0 -112L7 -106Z" fill="#d6453d"/></g>
<g id="k2" style="--shirt:#0e8f7e;--skin:#8d5a3b;--hair:#14100d;--medal:#f5b83d"><use href="#kid"/><g fill="none" stroke="#1b1b1b" stroke-width="2"><circle cx="-10" cy="-88" r="8"/><circle cx="10" cy="-88" r="8"/><path d="M-2 -88H2"/></g></g>
<g id="k3" style="--shirt:#d6453d;--skin:#ffd9b3;--hair:#7a3f12;--medal:#c98a55"><use href="#kid"/><path d="M-27 -102Q0 -114 27 -102" stroke="#2447d6" stroke-width="5" fill="none"/></g></defs>
<rect width="640" height="310" rx="16" fill="url(#sky)"/>
<polygon points="320,0 190,300 450,300" fill="#fff" opacity=".4"/><polygon points="320,0 260,300 380,300" fill="#fff" opacity=".4"/>
<g font-family="Georgia,serif" font-size="34" fill="#2447d6" opacity=".3"><text x="36" y="110">∑</text><text x="560" y="112">π</text><text x="70" y="190">√x</text><text x="540" y="190">x²</text></g>
<rect x="150" y="12" width="340" height="38" rx="19" fill="#2447d6"/><text x="320" y="38" text-anchor="middle" font-family="Trebuchet MS,sans-serif" font-weight="800" font-size="19" fill="#fff">JUARA OLIMPIADE MATEMATIKA</text><text x="174" y="38" font-size="20" fill="#f5b83d" text-anchor="middle">★</text><text x="466" y="38" font-size="20" fill="#f5b83d" text-anchor="middle">★</text>
<g><rect x="90" y="80" width="10" height="5" fill="#f5b83d" transform="rotate(30 90 80)"/><rect x="230" y="70" width="10" height="5" fill="#d6453d" transform="rotate(-20 230 70)"/><rect x="410" y="76" width="10" height="5" fill="#0e8f7e" transform="rotate(40 410 76)"/><rect x="520" y="84" width="10" height="5" fill="#f5b83d" transform="rotate(-30 520 84)"/><rect x="150" y="140" width="10" height="5" fill="#2447d6" transform="rotate(20 150 140)"/><rect x="480" y="150" width="10" height="5" fill="#d6453d" transform="rotate(-40 480 150)"/><circle cx="260" cy="110" r="4" fill="#f5b83d"/><circle cx="390" cy="120" r="4" fill="#0e8f7e"/><circle cx="120" cy="120" r="4" fill="#d6453d"/><circle cx="560" cy="130" r="4" fill="#2447d6"/></g>
<rect x="110" y="225" width="140" height="75" fill="#aab6cf"/><rect x="250" y="190" width="140" height="110" fill="#f5b83d"/><rect x="390" y="245" width="140" height="55" fill="#c98a55"/>
<g font-family="Trebuchet MS,sans-serif" font-weight="800" font-size="30" fill="#0f1e3d" text-anchor="middle"><text x="180" y="270">2</text><text x="320" y="250">1</text><text x="460" y="280">3</text></g>
<use href="#k1" x="180" y="225"/><use href="#k2" transform="translate(320 190) scale(1.15)"/><use href="#k3" x="460" y="245"/>
</svg>
<div><h2 style="font-size:1.6rem">Jadilah juara berikutnya</h2><p class="sub" style="margin:0">Setiap peraih medali OSN mulai dari latihan rutin dan rasa ingin tahu. Mulai satu subbab hari ini.</p></div>
</div></div></section>

<section id="materi"><div class="wrap">
<h2>Materi lengkap OSN SMP</h2>
<p class="sub">Lima bidang yang sering muncul di OSN SMP. Buka tiap subbab, pahami rumus dan teoremanya, lalu uji dengan soal latihan.</p>
<div class="tabs" role="tablist" id="tabs"></div>
<div id="isi"></div>
</div></section>

<section id='kuis'><div class='wrap'><h2>Kuis berskor</h2><p class='sub'>Pilih tingkat kesulitan, jawab 4 soal, lalu lihat skor dan pembahasannya.</p><div class='card'><div class='tabs' id='lv'></div><div id='qa'></div></div></div></section>

<section id="alur" class="band"><div class="wrap">
<h2>Cara belajar yang efektif</h2>
<p class="sub">Urutan ini membantu kamu memahami konsep, bukan sekadar menghafal rumus.</p>
<div class="steps">
<div class="card"><span class="n">1</span><h3>Pahami konsep</h3><p>Baca ringkasan materi dan tulis ulang rumus intinya dengan kata-katamu sendiri.</p></div>
<div class="card"><span class="n">2</span><h3>Coba dulu</h3><p>Kerjakan soal minimal 10 menit sebelum membuka pembahasan.</p></div>
<div class="card"><span class="n">3</span><h3>Bandingkan cara</h3><p>Cocokkan langkahmu dengan pembahasan, lalu catat ide yang belum terpikir.</p></div>
<div class="card"><span class="n">4</span><h3>Ulangi berkala</h3><p>Kerjakan ulang soal yang salah setelah satu minggu.</p></div>
</div>
</div></section>

<section id="kontak"><div class="wrap">
<div class="card" style="text-align:center;padding:40px 24px">
<h2>Siap berlatih bersama VriAcademy?</h2>
<p class="sub" style="margin-inline:auto">Mulai dari satu topik hari ini. Konsisten 30 menit per hari lebih berguna daripada belajar maraton sehari sebelum lomba.</p>
<a class="btn" href="#materi">Pilih topik</a>
</div>
</div></section>
</main>

<footer><div class="wrap"><span>© 2026 VriAcademy. Belajar olimpiade matematika SMP.</span><span>Dibuat untuk calon juara OSN.</span></div></footer>

<script>
var R=String.raw;
var CH=['Semua','Dasar','Kabupaten','Provinsi','Nasional'].map(function(c,i){return `<button class='chip' type='button' aria-pressed='${i==0}'>${c}</button>`}).join('');
var X=function(x,y,s){return `<text x='${x}' y='${y}'>${s}</text>`};
var F=function(c,s){return `<figure class='fig'><svg viewBox='0 0 220 140' role='img' aria-label='${c}'>${s}</svg><figcaption>${c}</figcaption></figure>`};
function tx(el){if(window.MathJax&&MathJax.typesetPromise){MathJax.typesetPromise([el]).catch(function(){})}}
var T=[
{n:'Teori Bilangan',ring:'Keterbagian, faktorisasi, kongruensi, dan persamaan bilangan bulat.',
s:[['Keterbagian dan faktorisasi prima',[
R`Setiap bilangan bulat $n>1$ ditulis tunggal sebagai $n=p_1^{a_1}p_2^{a_2}\cdots p_k^{a_k}$ (Teorema Dasar Aritmetika).`,
R`Banyak faktor positif: $d(n)=(a_1+1)(a_2+1)\cdots(a_k+1)$. Jumlah faktor: $\sigma(n)=\prod\dfrac{p_i^{a_i+1}-1}{p_i-1}$.`,
R`Ciri habis dibagi: 3 dan 9 (jumlah digit), 4 (dua digit terakhir), 8 (tiga digit terakhir), 11 (selisih jumlah digit posisi ganjil dan genap).`,
R`Kuadrat sempurna memiliki semua pangkat prima genap, sehingga banyak faktornya ganjil.`]],
['FPB, KPK, dan algoritma Euclid',[
R`$\gcd(a,b)\cdot\operatorname{lcm}(a,b)=ab$.`,
R`Algoritma Euclid: $\gcd(a,b)=\gcd(b,\;a\bmod b)$.`,
R`Identitas Bezout: ada bilangan bulat $x,y$ sehingga $ax+by=\gcd(a,b)$.`,
R`Dua bilangan berurutan selalu saling prima: $\gcd(n,n+1)=1$.`]],
['Kongruensi (modulo)',[
R`$a\equiv b\pmod n$ berarti $n\mid(a-b)$. Penjumlahan, pengurangan, perkalian, dan pangkat boleh dikerjakan per sisa.`,
R`Kuadrat sempurna bersisa $0$ atau $1$ modulo $3$ dan modulo $4$; kuadrat ganjil bersisa $1$ modulo $8$. Dipakai untuk membuktikan persamaan tidak punya solusi.`,
R`Teorema Fermat kecil: jika $p$ prima dan $p\nmid a$, maka $a^{p-1}\equiv1\pmod p$.`,
R`Angka satuan $a^n$ berpola berulang dengan periode 1, 2, atau 4.`]],
['Persamaan bilangan bulat',[
R`Trik Simon: $ab+a+b=n\iff(a+1)(b+1)=n+1$.`,
R`$ax+by=c$ punya solusi bulat jika dan hanya jika $\gcd(a,b)\mid c$.`,
R`Batasi variabel dengan ketidaksamaan, lalu periksa kasus yang tersisa.`]]],
tip:R`Strategi OSN: coba nilai kecil untuk menemukan pola, gunakan modulo untuk membuktikan ketidakmungkinan, dan faktorkan sebelum mencari solusi bulat.`,
p:[[R`Berapa banyak bilangan bulat positif $\le100$ yang habis dibagi 3 atau 5?`,R`Kelipatan 3: $33$, kelipatan 5: $20$, kelipatan 15: $6$. Jadi $33+20-6=$ <b>47</b>.`],
[R`Tentukan sisa $2^{50}$ jika dibagi $7$.`,R`$2^3=8\equiv1\pmod7$ dan $50=3\cdot16+2$, sehingga $2^{50}\equiv2^2=$ <b>4</b>.`],
[R`Tentukan $\gcd(84,126)$.`,R`$84=2^2\cdot3\cdot7$ dan $126=2\cdot3^2\cdot7$. Ambil pangkat terkecil: $2\cdot3\cdot7=$ <b>42</b>.`],
[R`Berapa bilangan tiga digit terkecil yang bersisa 3 jika dibagi 5, 7, maupun 9?`,R`Bilangan itu berbentuk kelipatan $\operatorname{lcm}(5,7,9)=315$ ditambah 3, sehingga yang terkecil $315+3=$ <b>318</b>.`]]},
{n:'Aljabar',ring:'Pemfaktoran, persamaan kuadrat, barisan, ketidaksamaan, dan fungsi.',
s:[['Identitas dan pemfaktoran',[
R`$a^2-b^2=(a-b)(a+b)$ dan $(a\pm b)^2=a^2\pm2ab+b^2$.`,
R`$a^3\pm b^3=(a\pm b)(a^2\mp ab+b^2)$ dan $(a+b)^3=a^3+3a^2b+3ab^2+b^3$.`,
R`Jika $a+b+c=0$ maka $a^3+b^3+c^3=3abc$.`,
R`Sophie Germain: $x^4+4y^4=(x^2+2xy+2y^2)(x^2-2xy+2y^2)$.`]],
['Persamaan kuadrat dan rumus Vieta',[
R`Akar $ax^2+bx+c=0$ adalah $x=\dfrac{-b\pm\sqrt D}{2a}$ dengan diskriminan $D=b^2-4ac$.`,
R`Vieta: $x_1+x_2=-\dfrac ba$ dan $x_1x_2=\dfrac ca$, sehingga $x_1^2+x_2^2=(x_1+x_2)^2-2x_1x_2$.`,
R`$D>0$: dua akar real berbeda; $D=0$: akar kembar; $D<0$: tidak ada akar real.`]],
['Barisan dan deret',[
R`Aritmetika: $U_n=a+(n-1)b$ dan $S_n=\dfrac n2\,(2a+(n-1)b)$.`,
R`Geometri: $U_n=ar^{n-1}$ dan $S_n=\dfrac{a(r^n-1)}{r-1}$.`,
R`$1+2+\cdots+n=\dfrac{n(n+1)}2$ dan $1^2+2^2+\cdots+n^2=\dfrac{n(n+1)(2n+1)}6$.`,
R`Teleskopik: $\dfrac1{k(k+1)}=\dfrac1k-\dfrac1{k+1}$.`]],
['Ketidaksamaan, nilai mutlak, dan fungsi',[
R`$(a-b)^2\ge0\Rightarrow a^2+b^2\ge2ab$. AM-GM: untuk $a,b\ge0$, $\dfrac{a+b}2\ge\sqrt{ab}$, sama jika $a=b$.`,
R`Definisi: $|x|=x$ jika $x\ge0$ dan $|x|=-x$ jika $x<0$. Sifat: $|x|\ge0$, $|x|=\sqrt{x^2}$, $|ab|=|a|\,|b|$, dan $\left|\dfrac ab\right|=\dfrac{|a|}{|b|}$ untuk $b\ne0$.`,
R`Untuk $a>0$:$$\begin{aligned}|x|=a&\iff x=-a\text{ atau }x=a,\\|x|\lt a&\iff -a\lt x\lt a,\\|x|>a&\iff x<-a\text{ atau }x>a.\end{aligned}$$`,
R`Arti geometri: $|x-y|$ adalah jarak titik $x$ dan $y$ pada garis bilangan. Karena itu, untuk $r>0$:$$|x-c|\lt r\iff c-r\lt x\lt c+r.$$Contoh: $|x-2|<3$ berarti jarak $x$ ke $2$ kurang dari $3$, sehingga$$|x-2|<3\iff -1\lt x<5.$$`+F('Titik yang jaraknya ke 2 kurang dari 3',`<path d='M10 70H210M50 63V77M110 63V77M170 63V77'/><path d='M50 70H170' stroke='var(--blue)' stroke-width='6'/><circle cx='50' cy='70' r='5' style='fill:var(--paper)'/><circle cx='170' cy='70' r='5' style='fill:var(--paper)'/><circle class='k' cx='110' cy='70' r='4'/>`+X(42,94,'−1')+X(106,94,'2')+X(166,94,'5')+X(74,52,'jarak < 3')+X(130,52,'jarak < 3')),
R`Pertidaksamaan segitiga: $|a+b|\le|a|+|b|$ dan $\big||a|-|b|\big|\le|a-b|$. Selain itu $|a|=|b|\iff a=b$ atau $a=-b$.`,
R`Jika $x+\dfrac1x=k$ maka $x^2+\dfrac1{x^2}=k^2-2$.`,
R`Persamaan fungsi: substitusikan nilai khusus ($x=0$, $x=1$, $y=x$) untuk menemukan pola $f$.`]]],
tip:R`Strategi OSN: kenali bentuk yang bisa difaktorkan, gunakan pemisalan variabel baru, dan cek hasil dengan substitusi nilai kecil.`,
p:[[R`Hitunglah $2026^2-2025^2$.`,R`$(2026-2025)(2026+2025)=1\cdot4051=$ <b>4051</b>.`],
[R`Jika $x+\dfrac1x=5$, tentukan $x^2+\dfrac1{x^2}$.`,R`$x^2+\dfrac1{x^2}=5^2-2=$ <b>23</b>.`],
[R`Jika $a+b=7$ dan $ab=10$, tentukan $a^2+b^2$.`,R`$a^2+b^2=(a+b)^2-2ab=49-20=$ <b>29</b>.`],
[R`Hitunglah $1+2+3+\cdots+100$.`,R`$\dfrac{100\cdot101}2=$ <b>5050</b>.`]]},
{n:'Geometri',ring:'Sudut, segitiga, kesebangunan, segiempat, lingkaran, dan segi banyak, lengkap dengan gambar tiap rumus.',
s:[['Sudut dan garis sejajar',[
R`Sudut berpelurus berjumlah $180^\circ$; sudut bertolak belakang sama besar. Pada dua garis sejajar yang dipotong garis lain: sudut sehadap dan dalam berseberangan sama besar, sudut dalam sepihak berjumlah $180^\circ$.`+F('Sehadap dan berseberangan sama besar (α); sepihak: α + β = 180°',`<path d='M10 40H210M10 100H210M70 10L150 130'/>`+X(96,34,'α')+X(72,56,'α')+X(136,94,'α')+X(112,114,'α')+X(98,58,'β')),
R`Jumlah sudut dalam segitiga $180^\circ$. Sudut luar sama dengan jumlah dua sudut dalam yang tidak bersisian dengannya.`+F('Sudut luar di B = α + β',`<polygon class='f' points='30,110 130,110 90,30'/><path d='M130 110H200'/>`+X(44,104,'α')+X(84,52,'β')+X(142,102,'α+β'))]],
['Segitiga: luas dan garis istimewa',[
R`Pertidaksamaan segitiga: sisi-sisi $a,b,c$ membentuk segitiga jika dan hanya jika$$a+b>c,\quad b+c>a,\quad a+c>b.$$Ketiga syarat itu sekaligus ekuivalen dengan$$|a-b|\lt c\lt a+b,$$karena $|a-b|\lt c$ berarti $a-b\lt c$ dan $b-a\lt c$. Jika $a+b=c$, ketiga titik segaris sehingga tidak terbentuk segitiga. Contoh: sisi $3,4,8$ tidak bisa karena $3+4<8$.`+F('Tiap sisi lebih pendek dari jumlah dua sisi lainnya',`<polygon class='f' points='30,110 190,110 110,30'/>`+X(106,128,'c')+X(58,66,'a')+X(160,66,'b')),
R`Segitiga sama kaki mempunyai dua sisi sama panjang dan dua sudut alas yang sama besar.`,
R`Luas segitiga: $L=\tfrac12at$.`+F('Luas = ½ × alas × tinggi',`<polygon class='f' points='30,110 170,110 110,30'/><path class='d' d='M110 30V110M110 100H120V110'/>`+X(98,128,'a')+X(116,74,'t')),
R`Luas dengan sinus: $L=\tfrac12ab\sin C$.`+F('Luas = ½ · a · b · sin C',`<polygon class='f' points='30,110 170,110 90,30'/>`+X(98,128,'a')+X(48,66,'b')+X(46,104,'C')),
R`Rumus Heron: $L=\sqrt{s(s-a)(s-b)(s-c)}$ dengan $s=\tfrac{a+b+c}2$.`+F('Heron: s = (a + b + c) / 2',`<polygon class='f' points='30,110 190,110 125,25'/>`+X(106,128,'a')+X(64,62,'c')+X(166,62,'b')),
R`Segitiga sama sisi: $t=\dfrac{a\sqrt3}2$ dan $L=\dfrac{a^2\sqrt3}4$.`+F('Tinggi t = a√3 / 2',`<polygon class='f' points='40,115 160,115 100,11'/><path class='d' d='M100 11V115'/>`+X(96,132,'a')+X(106,70,'t')),
R`Titik berat $G$ membagi garis berat dengan perbandingan $2:1$. Tiga garis berat membagi luas segitiga menjadi enam bagian sama.`+F('Titik berat G: perbandingan 2 : 1',`<polygon class='f' points='110,20 30,115 190,115'/><path d='M110 20V115M30 115L150 67M190 115L70 67'/><circle class='k' cx='110' cy='83' r='3.5'/>`+X(116,80,'G')+X(96,56,'2')+X(96,104,'1')),
R`Teorema garis bagi: jika $AD$ garis bagi $\angle A$, maka $\dfrac{BD}{DC}=\dfrac{AB}{AC}$.`+F('AD garis bagi: BD/DC = AB/AC',`<polygon class='f' points='60,20 20,115 200,115'/><path class='d' d='M60 20L88 115'/>`+X(54,16,'A')+X(6,130,'B')+X(202,130,'C')+X(84,132,'D'))]],
['Pythagoras dan kesebangunan',[
R`Pythagoras: $a^2+b^2=c^2$. Tripel: $(3,4,5)$, $(5,12,13)$, $(8,15,17)$, $(7,24,25)$.`+F('Segitiga siku-siku: a² + b² = c²',`<polygon class='f' points='40,110 140,110 40,40'/><path d='M40 98H52V110'/>`+X(86,128,'a')+X(24,78,'b')+X(104,66,'c')),
R`Tinggi $AD$ ke sisi miring: $AD^2=BD\cdot DC$, $\;AB^2=BD\cdot BC$, $\;AC^2=DC\cdot BC$.`+F('t² = p · q (A sudut siku-siku)',`<polygon class='f' points='20,115 200,115 80,30'/><path class='d' d='M80 30V115M80 105H90V115'/>`+X(50,132,'p')+X(138,132,'q')+X(86,76,'t')+X(76,24,'A')+X(6,130,'B')+X(202,130,'C')),
R`Kesebangunan: sisi bersesuaian sebanding. Jika perbandingan sisi $k$, maka perbandingan luas $k^2$.`+F('Sisi a dan k·a; luas L dan k²·L',`<polygon class='f' points='14,115 74,115 44,75'/><polygon class='f' points='104,115 194,115 149,55'/>`+X(38,132,'a')+X(140,132,'k·a')+X(14,66,'luas L')+X(112,40,'luas k²L')),
R`Garis sejajar sisi: jika $DE\parallel BC$, maka $\dfrac{AD}{AB}=\dfrac{AE}{AC}=\dfrac{DE}{BC}$.`+F('DE sejajar BC',`<polygon class='f' points='110,15 30,120 190,120'/><path d='M72 65H148'/>`+X(116,13,'A')+X(14,132,'B')+X(192,132,'C')+X(54,64,'D')+X(152,64,'E'))]],
['Segiempat',[
R`Persegi panjang $L=pl$; jajar genjang $L=at$; trapesium $L=\dfrac{(a+b)\,t}2$.`+F('Trapesium: L = ½ (a + b) t',`<polygon class='f' points='50,30 150,30 190,110 20,110'/><path class='d' d='M50 30V110'/>`+X(96,24,'b')+X(100,128,'a')+X(56,74,'t')),
R`Layang-layang dan belah ketupat: $L=\dfrac{d_1d_2}2$.`+F('Luas = ½ × diagonal₁ × diagonal₂',`<polygon class='f' points='100,10 150,60 100,130 50,60'/><path class='d' d='M100 10V130M50 60H150'/>`+X(106,100,'d₁')+X(118,54,'d₂'))]],
['Lingkaran',[
R`Sudut pusat $=2\times$ sudut keliling yang menghadap busur yang sama.`+F('Sudut pusat = 2θ, sudut keliling = θ',`<circle cx='110' cy='70' r='56'/><path d='M62 98L110 70L158 98M110 14L62 98M110 14L158 98'/><circle class='k' cx='110' cy='70' r='3'/>`+X(100,92,'2θ')+X(104,36,'θ')+X(48,106,'A')+X(160,106,'B')),
R`Sudut keliling yang menghadap diameter selalu $90^\circ$.`+F('Menghadap diameter AB = 90°',`<circle cx='110' cy='70' r='56'/><path d='M54 70H166M54 70L110 14L166 70M104 22L110 28L116 22'/>`+X(40,74,'A')+X(168,74,'B')+X(116,12,'P')+X(98,52,'90°')),
R`Segiempat tali busur: sudut berhadapan berjumlah $180^\circ$.`+F('∠A + ∠C = 180°, ∠B + ∠D = 180°',`<circle cx='110' cy='70' r='56'/><polygon class='f' points='82,21.5 158.5,42 138,118.5 57.4,89'/>`+X(70,20,'A')+X(162,40,'B')+X(142,130,'C')+X(40,96,'D')),
R`Kuasa titik (dua tali busur berpotongan di $P$): $PA\cdot PB=PC\cdot PD$.`+F('PA · PB = PC · PD',`<circle cx='110' cy='70' r='56'/><path d='M56 84.5H164M100 15L120 125'/><circle class='k' cx='112.5' cy='84.5' r='3'/>`+X(44,92,'A')+X(166,92,'B')+X(94,12,'C')+X(122,136,'D')+X(118,76,'P')),
R`Garis singgung tegak lurus jari-jari. Dari titik luar $P$: $PT=PU=\sqrt{OP^2-r^2}$.`+F('PT = PU, OT tegak lurus PT',`<circle cx='80' cy='70' r='45'/><path d='M200 70L97 28M200 70L97 112M80 70L97 28M80 70L97 112'/><circle class='k' cx='80' cy='70' r='3'/>`+X(70,86,'O')+X(204,74,'P')+X(99,22,'T')+X(99,126,'U')),
R`Panjang busur $=\dfrac{\theta}{360^\circ}\cdot2\pi r$ dan luas juring $=\dfrac{\theta}{360^\circ}\cdot\pi r^2$.`+F('Juring dengan sudut pusat θ',`<circle cx='110' cy='70' r='56'/><path class='f' d='M110 70L166 70A56 56 0 0 0 138 21.5Z'/>`+X(128,64,'θ')+X(136,86,'r'))]],
['Lingkaran dalam dan luar segitiga',[
R`Jari-jari lingkaran dalam $r=\dfrac Ls$. Segitiga siku-siku: $r=\dfrac{a+b-c}2$.`+F('Lingkaran dalam menyinggung ketiga sisi: r = L / s',`<polygon class='f' points='110,20 30,115 190,115'/><circle cx='110' cy='78' r='37'/><path class='d' d='M110 78V115'/><circle class='k' cx='110' cy='78' r='3'/>`+X(116,100,'r')+X(116,72,'I')),
R`Jari-jari lingkaran luar $R=\dfrac{abc}{4L}$. Segitiga siku-siku: $R=\dfrac c2$.`+F('Lingkaran luar melalui ketiga titik sudut',`<circle cx='110' cy='70' r='56'/><polygon class='f' points='110,14 61.5,98 158.5,98'/><path class='d' d='M110 70L158.5 98'/><circle class='k' cx='110' cy='70' r='3'/>`+X(100,66,'O')+X(136,76,'R'))]],
['Segi banyak dan teorema Ptolemy',[
R`Jumlah sudut dalam segi-$n$ adalah $(n-2)\cdot180^\circ$; sudut dalam segi-$n$ beraturan $\dfrac{(n-2)\,180^\circ}n$; banyak diagonal $\dfrac{n(n-3)}2$.`+F('Segi-6: 4 segitiga, 4 × 180° = 720°',`<polygon class='f' points='165,70 137.5,22.4 82.5,22.4 55,70 82.5,117.6 137.5,117.6'/><path class='d' d='M165 70L82.5 22.4M165 70L55 70M165 70L82.5 117.6'/>`),
R`Teorema Ptolemy (segiempat tali busur $ABCD$): $AC\cdot BD=AB\cdot CD+AD\cdot BC$.`+F('Hasil kali diagonal = jumlah hasil kali sisi berhadapan',`<circle cx='110' cy='70' r='56'/><polygon points='82,21.5 158.5,42 138,118.5 57.4,89'/><path class='d' d='M82 21.5L138 118.5M158.5 42L57.4 89'/>`+X(70,20,'A')+X(162,40,'B')+X(142,130,'C')+X(40,96,'D'))]]],
tip:R`Strategi OSN: gambar dengan rapi, tambahkan garis bantu (tinggi, sejajar, jari-jari ke titik singgung), cari sudut dan segitiga sebangun, hitung luas dengan dua cara, dan cek apakah segiempat bisa dibuat siklis.`,
p:[[R`Segitiga siku-siku bersisi 6 dan 8. Berapa jari-jari lingkaran dalamnya?`,R`Sisi miring $=10$, maka $r=\dfrac{6+8-10}2=$ <b>2</b>. Cek: $L=24$, $s=12$, $r=\dfrac{24}{12}=2$.`],
[R`Segi banyak beraturan memiliki sudut dalam $144^\circ$. Berapa banyak sisinya?`,R`$\dfrac{(n-2)180}{n}=144\Rightarrow36n=360\Rightarrow n=$ <b>10</b>.`],
[R`Lingkaran berjari-jari 5 memiliki tali busur 8. Berapa jarak tali busur ke pusat?`,R`Garis dari pusat tegak lurus tali busur membaginya menjadi $4$ dan $4$: jarak $=\sqrt{5^2-4^2}=\sqrt9=$ <b>3</b>.`],
[R`Berapa banyak diagonal pada segi-12?`,R`$\dfrac{n(n-3)}2=\dfrac{12\cdot9}2=$ <b>54</b>.`],
[R`Segitiga $ABC$ bersisi $13,14,15$. Berapa luasnya?`,R`$s=21$, maka $L=\sqrt{21\cdot8\cdot7\cdot6}=\sqrt{7056}=$ <b>84</b>.`],
[R`Dari titik $P$ di luar lingkaran, sebuah garis memotong lingkaran di $A$ dan $B$ dengan $PA=4$ dan $AB=5$. Berapa panjang garis singgung $PT$?`,R`Kuasa titik: $PT^2=PA\cdot PB=4\cdot9=36$, sehingga $PT=$ <b>6</b>.`]]},
{n:'Kombinatorika',ring:'Pencacahan, kombinasi, inklusi-eksklusi, dan sarang merpati.',
s:[['Aturan dasar pencacahan',[
R`Aturan penjumlahan (kasus saling lepas) dan aturan perkalian (tahap berurutan).`,
R`$n!=n(n-1)\cdots1$, permutasi $P(n,r)=\dfrac{n!}{(n-r)!}$, permutasi siklis $(n-1)!$.`,
R`Permutasi dengan unsur sama: $\dfrac{n!}{n_1!\,n_2!\cdots n_k!}$.`]],
['Kombinasi dan binomial',[
R`$\dbinom nr=\dfrac{n!}{r!(n-r)!}=\dbinom n{n-r}$ dan $\dbinom nr+\dbinom n{r+1}=\dbinom{n+1}{r+1}$.`,
R`$(a+b)^n=\sum_{k=0}^{n}\dbinom nk a^{n-k}b^k$ dan $\sum_{k=0}^{n}\dbinom nk=2^n$.`,
R`Bintang dan pembatas: banyak solusi bulat tak negatif $x_1+\cdots+x_k=n$ adalah $\dbinom{n+k-1}{k-1}$.`]],
['Inklusi-eksklusi dan komplemen',[
R`$|A\cup B|=|A|+|B|-|A\cap B|$.`,
R`$|A\cup B\cup C|=\sum|A|-\sum|A\cap B|+|A\cap B\cap C|$.`,
R`Untuk kasus "paling sedikit satu", hitung komplemennya: $n(S)-n(\text{tidak ada})$.`]],
['Sarang merpati, invarian, dan peluang',[
R`Jika $m$ benda dimasukkan ke $n$ kotak, ada kotak berisi minimal $\left\lceil\dfrac mn\right\rceil$ benda.`,
R`Invarian dan pewarnaan (papan catur) dipakai untuk membuktikan suatu konfigurasi mustahil.`,
R`Peluang: $P(A)=\dfrac{n(A)}{n(S)}$.`]]],
tip:R`Strategi OSN: tentukan dulu apakah urutan penting, pisahkan kasus yang saling lepas, dan gunakan komplemen atau sarang merpati saat langsung menghitung terlalu rumit.`,
p:[[R`Dari angka $1,2,3,4,5$, berapa banyak bilangan 3 digit dengan digit berbeda?`,R`$5\cdot4\cdot3=$ <b>60</b>.`],
[R`Dalam kelas 25 siswa, buktikan minimal 3 siswa lahir di bulan yang sama.`,R`Ada 12 bulan. Jika tiap bulan paling banyak 2 siswa, totalnya paling banyak $24<25$. Jadi ada bulan dengan minimal <b>3 siswa</b>.`],
[R`Berapa cara memilih 3 orang dari 6 calon sebagai pengurus tanpa jabatan berbeda?`,R`$\dbinom63=\dfrac{6\cdot5\cdot4}{3\cdot2\cdot1}=$ <b>20</b>.`],
[R`Berapa susunan berbeda dari huruf kata BANANA?`,R`$\dfrac{6!}{3!\,2!}=\dfrac{720}{12}=$ <b>60</b>.`]]},
{n:'Logika dan Pembuktian',ring:'Cara bernalar runtut dan menulis bukti yang rapi.',
s:[['Logika proposisi',[
R`$p\Rightarrow q$ salah hanya jika $p$ benar dan $q$ salah. Kontraposisi $\neg q\Rightarrow\neg p$ setara dengannya; konvers dan invers tidak.`,
R`De Morgan: $\neg(p\land q)\equiv\neg p\lor\neg q$. Negasi "semua A adalah B" adalah "ada A yang bukan B".`]],
['Metode pembuktian',[
R`Langsung: mulai dari yang diketahui. Bilangan genap $=2k$, ganjil $=2k+1$.`,
R`Kontradiksi: andaikan kesimpulan salah lalu turunkan hal mustahil (contoh: $\sqrt2$ irasional).`,
R`Induksi: tunjukkan $P(1)$ benar, lalu $P(k)\Rightarrow P(k+1)$.`,
R`Kasus: bagi menurut sisa modulo atau urutan nilai.`]],
['Prinsip ekstremal dan teka-teki logika',[
R`Ambil unsur terbesar atau terkecil, lalu manfaatkan sifat khususnya.`,
R`Ksatria selalu jujur dan penipu selalu bohong: andaikan satu orang jujur, lalu uji konsistensinya.`]]],
tip:R`Strategi OSN: tulis bukti dengan kalimat lengkap, sebutkan setiap alasan, dan pastikan semua kasus tercakup.`,
p:[[R`Tentukan negasi dari "Semua siswa kelas 8 menyukai matematika".`,R`Negasi "semua" adalah "ada yang tidak": <b>ada siswa kelas 8 yang tidak menyukai matematika</b>.`],
[R`Tentukan kontraposisi dari "Jika $n$ genap maka $n^2$ genap".`,R`Tukar dan negasikan: <b>jika $n^2$ ganjil maka $n$ ganjil</b>.`],
[R`Buktikan jumlah dua bilangan ganjil selalu genap.`,R`Misalkan $2a+1$ dan $2b+1$. Jumlahnya $2a+2b+2=2(a+b+1)$, kelipatan 2, jadi <b>genap</b>.`],
[R`Ksatria selalu jujur dan penipu selalu bohong. A berkata: "Kami berdua penipu." Tentukan jenis A dan B.`,R`Andaikan A ksatria: ucapannya benar, padahal A bukan penipu, kontradiksi. Jadi A penipu, ucapannya salah, sehingga tidak keduanya penipu. Jadi <b>A penipu dan B ksatria</b>.`]]}
];
var EXTRA={
'Teori Bilangan':[
[R`Berapa banyak faktor positif dari $360$?`,R`Faktorisasi $360=2^3\cdot3^2\cdot5$. Banyak faktor positif $=(3+1)(2+1)(1+1)=$ <b>24</b>.`,'Kabupaten'],
[R`Tentukan dua digit terakhir dari $7^{2026}$.`,R`Dua digit terakhir berarti sisa modulo $100$. $7^2=49$ dan $7^4=2401\equiv1\pmod{100}$. Karena $2026=4\cdot506+2$, maka $7^{2026}\equiv7^2=$ <b>49</b>.`,'Kabupaten'],
[R`Tentukan semua bilangan prima $p$ sehingga $p+2$ dan $p+4$ juga prima.`,R`Periksa sisa $p$ modulo $3$. Jika $p\equiv1$, maka $3\mid p+2$; jika $p\equiv2$, maka $3\mid p+4$. Keduanya lebih besar dari $3$, sehingga bukan prima. Jadi $p\equiv0$, yaitu $p=3$. Cek: $3,5,7$ semuanya prima. Jawaban: <b>$p=3$</b>.`,'Provinsi'],
[R`Tentukan banyaknya pasangan bilangan bulat positif $(x,y)$ yang memenuhi $\dfrac1x+\dfrac1y=\dfrac16$.`,R`$\dfrac1x+\dfrac1y=\dfrac16\Rightarrow6x+6y=xy\Rightarrow(x-6)(y-6)=36$. Karena $\dfrac1x\lt\dfrac16$ dan $\dfrac1y\lt\dfrac16$, haruslah $x>6$ dan $y>6$, sehingga kedua faktor positif. Banyak faktor positif $36=2^2\cdot3^2$ adalah $3\cdot3=9$. Jadi ada <b>9</b> pasangan terurut.`,'Provinsi'],
[R`Buktikan bahwa $n^5-n$ habis dibagi $30$ untuk setiap bilangan bulat $n$.`,R`Faktorkan $n^5-n=n(n-1)(n+1)(n^2+1)$. Tiga bilangan berurutan $n-1,n,n+1$ memuat kelipatan $2$ dan kelipatan $3$, jadi hasilnya habis dibagi $6$. Untuk $5$: jika $n\equiv0,\pm1\pmod5$, salah satu dari $n,n-1,n+1$ habis dibagi $5$; jika $n\equiv\pm2$, maka $n^2+1\equiv5\equiv0$. Karena $6$ dan $5$ saling prima, $30\mid n^5-n$. $\blacksquare$`,'Nasional'],
[R`Adakah pasangan bilangan bulat positif $(a,b)$ sehingga $a^2-b^2=2026$? Buktikan jawabanmu.`,R`Tulis $a^2-b^2=(a-b)(a+b)$. Kedua faktor selalu sama paritas karena selisihnya $2b$ genap. Jika keduanya ganjil, hasil kalinya ganjil; jika keduanya genap, hasil kalinya kelipatan $4$. Padahal $2026=2\cdot1013$ genap tetapi bukan kelipatan $4$. Jadi <b>tidak ada</b> pasangan seperti itu. $\blacksquare$`,'Nasional']],
'Aljabar':[
[R`Jika $x+y=5$ dan $xy=3$, tentukan nilai $x^3+y^3$.`,R`$x^3+y^3=(x+y)^3-3xy(x+y)=125-3\cdot3\cdot5=125-45=$ <b>80</b>.`,'Kabupaten'],
[R`Hitunglah $\dfrac1{1\cdot2}+\dfrac1{2\cdot3}+\cdots+\dfrac1{99\cdot100}$.`,R`Gunakan $\dfrac1{k(k+1)}=\dfrac1k-\dfrac1{k+1}$. Jumlahnya teleskopik: $\left(1-\dfrac12\right)+\left(\dfrac12-\dfrac13\right)+\cdots+\left(\dfrac1{99}-\dfrac1{100}\right)=1-\dfrac1{100}=$ <b>$\dfrac{99}{100}$</b>.`,'Kabupaten'],
[R`Bilangan real $a,b,c$ memenuhi $a+b+c=0$ dan $a^2+b^2+c^2=6$. Tentukan $a^4+b^4+c^4$.`,R`Dari $a+b+c=0$: $ab+bc+ca=\dfrac{(a+b+c)^2-(a^2+b^2+c^2)}2=-3$. Lalu $a^2b^2+b^2c^2+c^2a^2=(ab+bc+ca)^2-2abc(a+b+c)=9$. Maka $a^4+b^4+c^4=(a^2+b^2+c^2)^2-2(a^2b^2+b^2c^2+c^2a^2)=36-18=$ <b>18</b>.`,'Provinsi'],
[R`Tentukan semua bilangan real $x$ yang memenuhi $|x-1|+|x-3|=6$.`,R`Titik kritis $x=1$ dan $x=3$. Untuk $x\ge3$: $2x-4=6\Rightarrow x=5$ (memenuhi). Untuk $1\le x\lt3$: $(x-1)+(3-x)=2\ne6$. Untuk $x\lt1$: $4-2x=6\Rightarrow x=-1$ (memenuhi). Jadi <b>$x=-1$ atau $x=5$</b>.`,'Provinsi'],
[R`Jika $x$ bilangan real dengan $x^2-3x+1=0$, tentukan $x^5+\dfrac1{x^5}$.`,R`Karena $x\ne0$, bagi dengan $x$: $x+\dfrac1x=3$. Misalkan $s_n=x^n+\dfrac1{x^n}$. Dari $\left(x+\dfrac1x\right)s_n=s_{n+1}+s_{n-1}$ didapat $s_{n+1}=3s_n-s_{n-1}$ dengan $s_0=2$, $s_1=3$. Maka $s_2=7$, $s_3=18$, $s_4=47$, $s_5=$ <b>123</b>.`,'Nasional'],
[R`Fungsi $f$ memenuhi $f(x)+2f\left(\dfrac1x\right)=3x$ untuk semua $x\ne0$. Tentukan $f(2)$.`,R`Ganti $x$ dengan $\dfrac1x$: $f\left(\dfrac1x\right)+2f(x)=\dfrac3x$. Misalkan $u=f(x)$ dan $v=f\left(\dfrac1x\right)$: $u+2v=3x$ dan $2u+v=\dfrac3x$. Kalikan persamaan kedua dengan $2$, lalu kurangkan persamaan pertama: $3u=\dfrac6x-3x$, jadi $f(x)=\dfrac2x-x$. Maka $f(2)=1-2=$ <b>$-1$</b>.`,'Nasional']],
'Geometri':[
[R`Persegi panjang $ABCD$ mempunyai $AB=8$ dan $BC=6$. Tentukan jarak titik $A$ ke diagonal $BD$.`,R`Diagonal $BD=\sqrt{8^2+6^2}=10$. Luas $\triangle ABD=\tfrac12\cdot8\cdot6=24$. Tinggi dari $A$ ke $BD$ adalah $\dfrac{2\cdot24}{10}=$ <b>4,8</b>.`,'Kabupaten'],
[R`Besar sudut-sudut sebuah segitiga berbanding $2:3:4$. Tentukan besar sudut terbesar.`,R`Jumlah perbandingan $2+3+4=9$, satu bagian $=\dfrac{180^\circ}9=20^\circ$. Sudut terbesar $4\cdot20^\circ=$ <b>$80^\circ$</b>.`,'Kabupaten'],
[R`Segitiga $ABC$ siku-siku di $A$ dengan $AB=15$ dan $AC=20$. Titik $D$ pada $BC$ sehingga $AD$ garis bagi $\angle A$. Tentukan panjang $AD$.`,R`Karena $\angle A=90^\circ$, maka $\angle BAD=\angle DAC=45^\circ$. Luas $\triangle ABC=\tfrac12\cdot15\cdot20=150$ sama dengan $L_{ABD}+L_{ACD}=\tfrac12\cdot15\cdot AD\sin45^\circ+\tfrac12\cdot20\cdot AD\sin45^\circ=\dfrac{35\sqrt2}4\,AD$. Jadi $AD=\dfrac{600}{35\sqrt2}=$ <b>$\dfrac{60\sqrt2}7$</b>.`,'Provinsi'],
[R`Lingkaran dalam segitiga $ABC$ dengan $AB=13$, $BC=14$, $CA=15$ menyinggung $BC$ di $D$. Tentukan $BD$.`,R`Panjang singgung dari titik sudut $B$ ke lingkaran dalam adalah $s-AC$, dengan $s=\dfrac{13+14+15}2=21$. Maka $BD=21-15=$ <b>6</b>.`,'Provinsi'],
[R`Dua lingkaran berjari-jari $3$ dan $5$ bersinggungan di luar. Tentukan panjang garis singgung persekutuan luarnya.`,R`Jarak kedua pusat $d=3+5=8$. Panjang garis singgung persekutuan luar $=\sqrt{d^2-(R-r)^2}=\sqrt{64-4}=\sqrt{60}=$ <b>$2\sqrt{15}$</b>.`,'Nasional'],
[R`Pada segitiga $ABC$, $\angle A=60^\circ$, $AB=8$, dan $AC=5$. Tentukan panjang $BC$ dan jari-jari lingkaran luarnya.`,R`Aturan kosinus: $BC^2=8^2+5^2-2\cdot8\cdot5\cos60^\circ=89-40=49$, jadi $BC=$ <b>7</b>. Luas $L=\tfrac12\cdot8\cdot5\sin60^\circ=10\sqrt3$. Maka $R=\dfrac{abc}{4L}=\dfrac{7\cdot8\cdot5}{40\sqrt3}=$ <b>$\dfrac{7\sqrt3}3$</b>.`,'Nasional']],
'Kombinatorika':[
[R`Berapa banyak bilangan genap empat digit yang semua digitnya berbeda?`,R`Pisahkan menurut digit terakhir. Berakhir $0$: tiga digit depan dari 9 angka tersisa, $9\cdot8\cdot7=504$. Berakhir $2,4,6,8$ (4 pilihan): digit pertama bukan $0$ dan bukan digit terakhir ($8$ pilihan), lalu $8$ dan $7$ pilihan, sehingga $4\cdot8\cdot8\cdot7=1792$. Total $504+1792=$ <b>2296</b>.`,'Kabupaten'],
[R`Dari 5 pria dan 4 wanita dipilih panitia 4 orang yang memuat minimal 2 wanita. Berapa banyak cara memilihnya?`,R`Hitung komplemen. Semua cara: $\dbinom94=126$. Tanpa wanita: $\dbinom54=5$. Tepat 1 wanita: $\dbinom41\dbinom53=40$. Jadi $126-5-40=$ <b>81</b>.`,'Kabupaten'],
[R`Berapa banyak solusi bilangan bulat $(x,y,z)$ dari $x+y+z=10$ dengan $x\ge1$, $y\ge2$, $z\ge3$?`,R`Misalkan $x=x'+1$, $y=y'+2$, $z=z'+3$ dengan $x',y',z'\ge0$. Persamaan menjadi $x'+y'+z'=10-6=4$. Dengan bintang dan pembatas: $\dbinom{4+3-1}{3-1}=\dbinom62=$ <b>15</b>.`,'Provinsi'],
[R`Berapa banyak susunan huruf kata MATEMATIKA sehingga ketiga huruf A selalu berdampingan?`,R`Gabungkan ketiga huruf A menjadi satu blok. Objeknya: blok AAA, M, M, T, T, E, I, K, yaitu 8 objek dengan M dan T masing-masing dua kali. Banyak susunan $\dfrac{8!}{2!\,2!}=\dfrac{40320}4=$ <b>10080</b>.`,'Provinsi'],
[R`Berapa banyak bilangan bulat positif $\le1000$ yang tidak habis dibagi $2$, $3$, maupun $5$?`,R`Misalkan $A,B,C$ himpunan kelipatan $2,3,5$. $|A|=500$, $|B|=333$, $|C|=200$, $|A\cap B|=166$, $|A\cap C|=100$, $|B\cap C|=66$, $|A\cap B\cap C|=33$. Yang habis dibagi minimal satu: $1033-332+33=734$. Jadi yang tidak habis dibagi ketiganya: $1000-734=$ <b>266</b>.`,'Nasional'],
[R`Dua kotak pojok yang berseberangan pada papan catur $8\times8$ dibuang. Dapatkah sisanya ditutup tepat oleh 31 domino $2\times1$ tanpa tumpang tindih?`,R`Warnai papan seperti papan catur: 32 kotak hitam dan 32 putih. Dua pojok berseberangan berwarna sama, misalnya hitam, sehingga tersisa 30 hitam dan 32 putih. Setiap domino menutup tepat satu hitam dan satu putih, jadi 31 domino menutup 31 hitam, padahal hanya ada 30. Jadi <b>tidak mungkin</b>.`,'Nasional']],
'Logika dan Pembuktian':[
[R`Pernyataan "Jika hari hujan maka jalan basah" benar, dan jalan tidak basah. Apa kesimpulan yang pasti benar?`,R`Ini modus tollens: jika $p\Rightarrow q$ benar dan $q$ salah, maka $p$ salah. Kesimpulannya: <b>hari tidak hujan</b>.`,'Kabupaten'],
[R`Buktikan: jika $n^2$ habis dibagi $3$ maka $n$ habis dibagi $3$.`,R`Gunakan kontraposisi: jika $n$ tidak habis dibagi 3 maka $n^2$ tidak habis dibagi 3. Tulis $n=3k\pm1$. Maka $n^2=9k^2\pm6k+1=3(3k^2\pm2k)+1$ bersisa $1$ jika dibagi 3. Kontraposisinya benar, sehingga pernyataan awal juga benar. $\blacksquare$`,'Kabupaten'],
[R`Buktikan bahwa $\sqrt2$ irasional.`,R`Andaikan $\sqrt2=\dfrac pq$ dengan $p,q$ bulat positif dan pecahan sudah sederhana. Maka $p^2=2q^2$, sehingga $p^2$ genap dan $p$ genap; tulis $p=2m$. Didapat $4m^2=2q^2$, yaitu $q^2=2m^2$, sehingga $q$ genap. Maka $p$ dan $q$ sama-sama genap, bertentangan dengan pecahan sederhana. Jadi $\sqrt2$ irasional. $\blacksquare$`,'Provinsi'],
[R`Buktikan dengan induksi: $1+3+5+\cdots+(2n-1)=n^2$ untuk semua bilangan asli $n$.`,R`Basis: $n=1$, $1=1^2$ benar. Langkah: anggap $1+3+\cdots+(2k-1)=k^2$. Tambahkan $2k+1$ pada kedua ruas: $k^2+2k+1=(k+1)^2$. Jadi benar untuk $k+1$, dan menurut induksi benar untuk semua $n$. $\blacksquare$`,'Provinsi'],
[R`Buktikan bahwa dari 5 bilangan bulat sembarang selalu dapat dipilih 3 bilangan yang jumlahnya habis dibagi $3$.`,R`Lihat sisa tiap bilangan modulo $3$. Kasus 1: ada sisa $r$ yang muncul minimal 3 kali. Pilih tiga bilangan itu: jumlahnya $\equiv3r\equiv0\pmod3$. Kasus 2: tiap sisa muncul paling banyak 2 kali. Karena ada 5 bilangan, dua sisa saja hanya menampung $2+2=4$ bilangan, jadi ketiga sisa $0,1,2$ pasti muncul. Pilih satu bilangan untuk tiap sisa: jumlahnya $\equiv0+1+2=3\equiv0$. $\blacksquare$`,'Nasional'],
[R`Dalam sebuah pesta dengan $n\ge2$ orang, pertemanan bersifat timbal balik. Buktikan ada dua orang dengan jumlah teman yang sama.`,R`Banyak teman tiap orang adalah salah satu dari $0,1,\dots,n-1$. Nilai $0$ dan $n-1$ tidak mungkin muncul bersamaan: orang dengan $n-1$ teman berteman dengan semua orang, sedangkan orang dengan $0$ teman tidak berteman dengan siapa pun. Jadi paling banyak $n-1$ nilai berbeda untuk $n$ orang. Menurut prinsip sarang merpati, ada dua orang dengan banyak teman yang sama. $\blacksquare$`,'Nasional']]};
T.forEach(function(t){(EXTRA[t.n]||[]).forEach(function(q){t.p.push(q)})});
var tabs=document.getElementById('tabs'),isi=document.getElementById('isi');
function show(i){
 [].forEach.call(tabs.children,function(b,j){b.setAttribute('aria-selected',j===i)});
 var t=T[i];
 isi.innerHTML=`<div class='panel'><div><h3 style='margin-bottom:6px'>Materi lengkap: ${t.n}</h3><p style='margin:0 0 14px;color:var(--muted)'>${t.ring}</p>`+t.s.map(function(s,k){return `<details${k?'':' open'}><summary>${s[0]}</summary><ul>${s[1].map(function(x){return '<li>'+x+'</li>'}).join('')}</ul></details>`}).join('')+`<div class='tip'>${t.tip}</div></div><div class='card'><h3>Latihan dan pembahasan</h3><div class='chips'>`+CH+`</div>`+t.p.map(function(s,k){return `<div class='prob' data-lv='${s[2]||'Dasar'}'><p><span class='lv lv${(s[2]||'Dasar')[0]}'>${s[2]||'Dasar'}</span>Soal ${k+1}. ${s[0]}</p><button class='sol' type='button' aria-expanded='false'>Lihat pembahasan</button><div class='ans'>${s[1]}</div></div>`}).join('')+`</div></div>`;
 tx(isi);
}
T.forEach(function(t,i){var b=document.createElement('button');b.className='tab';b.type='button';b.setAttribute('role','tab');b.textContent=t.n;b.onclick=function(){show(i)};tabs.appendChild(b)});
show(0);
function tog(b){var a=b.nextElementSibling,o=a.classList.toggle('open');b.setAttribute('aria-expanded',o);b.textContent=o?'Sembunyikan pembahasan':'Lihat pembahasan'}
isi.addEventListener('click',function(e){if(e.target.classList.contains('sol'))tog(e.target)});
isi.addEventListener('click',function(e){var c=e.target.closest('.chip');if(!c)return;var card=c.closest('.card'),v=c.textContent;card.querySelectorAll('.chip').forEach(function(x){x.setAttribute('aria-pressed',x===c)});card.querySelectorAll('.prob').forEach(function(q){q.style.display=(v==='Semua'||q.dataset.lv===v)?'':'none'})});
document.getElementById('hs').onclick=function(){tog(this)};
document.getElementById('cek').onclick=function(){var v=document.getElementById('jw').value.trim(),f=document.getElementById('fb');
 if(!v){f.textContent='';return}
 var ok=v==='9';f.className='fb '+(ok?'ok':'no');f.textContent=ok?'Benar! Angka satuannya 9.':'Belum tepat. Coba cari pola angka satuan pangkat 7.'};
var Q={'Mudah':[
{q:R`Berapa $\gcd(12,18)$?`,o:[R`$2$`,R`$3$`,R`$6$`,R`$36$`],a:2,e:R`$12=2^2\cdot3$ dan $18=2\cdot3^2$, sehingga $\gcd=2\cdot3=6$.`},
{q:R`Hasil dari $15^2-14^2$ adalah ...`,o:[R`$1$`,R`$28$`,R`$29$`,R`$31$`],a:2,e:R`$(15-14)(15+14)=1\cdot29=29$.`},
{q:R`Jumlah sudut dalam segi enam adalah ...`,o:[R`$360^\circ$`,R`$540^\circ$`,R`$720^\circ$`,R`$900^\circ$`],a:2,e:R`$(6-2)\cdot180^\circ=720^\circ$.`},
{q:R`Ada berapa cara menyusun 3 buku berbeda dalam satu baris di rak?`,o:[R`$3$`,R`$6$`,R`$9$`,R`$12$`],a:1,e:R`$3!=3\cdot2\cdot1=6$.`}],
'Sedang':[
{q:R`Angka satuan dari $3^{2026}$ adalah ...`,o:[R`$1$`,R`$3$`,R`$7$`,R`$9$`],a:3,e:R`Angka satuan $3^n$ berulang: $3,9,7,1$. Karena $2026\equiv2\pmod4$, angka satuannya $9$.`},
{q:R`Jika $x+\dfrac1x=3$, maka $x^2+\dfrac1{x^2}=$ ...`,o:[R`$5$`,R`$7$`,R`$9$`,R`$11$`],a:1,e:R`$x^2+\dfrac1{x^2}=3^2-2=7$.`},
{q:R`Segitiga siku-siku bersisi $5,12,13$. Jari-jari lingkaran dalamnya adalah ...`,o:[R`$2$`,R`$2{,}5$`,R`$3$`,R`$4$`],a:0,e:R`$r=\dfrac{5+12-13}2=2$.`},
{q:R`Banyak cara memilih 2 orang dari 8 orang adalah ...`,o:[R`$16$`,R`$28$`,R`$56$`,R`$64$`],a:1,e:R`$\dbinom82=\dfrac{8\cdot7}2=28$.`}],
'OSN':[
{q:R`Banyak bilangan bulat positif $\le1000$ yang habis dibagi 4 tetapi tidak habis dibagi 6 adalah ...`,o:[R`$166$`,R`$167$`,R`$168$`,R`$250$`],a:1,e:R`Habis dibagi 4: $250$. Habis dibagi 4 dan 6 berarti habis dibagi 12: $\lfloor1000/12\rfloor=83$. Jadi $250-83=167$.`},
{q:R`Sisa pembagian $2^{2026}$ oleh $7$ adalah ...`,o:[R`$1$`,R`$2$`,R`$4$`,R`$6$`],a:1,e:R`$2^3\equiv1\pmod7$ dan $2026=3\cdot675+1$, sehingga $2^{2026}\equiv2$.`},
{q:R`Banyak pasangan terurut bilangan bulat positif $(a,b)$ dengan $ab-a-b=5$ adalah ...`,o:[R`$2$`,R`$4$`,R`$6$`,R`$8$`],a:1,e:R`Trik Simon: $(a-1)(b-1)=6$. Pasangan faktor positif $1\cdot6,\,2\cdot3,\,3\cdot2,\,6\cdot1$ memberi $(a,b)=(2,7),(3,4),(4,3),(7,2)$: ada 4.`},
{q:R`Minimal berapa bilangan yang harus diambil dari $\{1,2,\dots,10\}$ agar pasti ada dua yang berjumlah $11$?`,o:[R`$5$`,R`$6$`,R`$7$`,R`$8$`],a:1,e:R`Ada 5 pasangan berjumlah 11: $(1,10),(2,9),(3,8),(4,7),(5,6)$. Lima bilangan bisa satu dari tiap pasangan, tetapi enam bilangan pasti memuat kedua anggota satu pasangan.`}]};
var cur,idx,sc,lv=document.getElementById('lv'),qa=document.getElementById('qa');
qa.innerHTML=`<p style='margin:0;color:var(--muted)'>Pilih tingkat kesulitan di atas untuk memulai.</p>`;
Object.keys(Q).forEach(function(k){var b=document.createElement('button');b.className='tab';b.type='button';b.textContent=k;b.onclick=function(){start(k)};lv.appendChild(b)});
function start(k){cur=k;idx=0;sc=0;[].forEach.call(lv.children,function(b){b.setAttribute('aria-selected',b.textContent===k)});ask()}
function ask(){var q=Q[cur][idx],n=Q[cur].length;qa.innerHTML=`<div class='qm'><span>Soal ${idx+1} dari ${n}</span><span>Skor: ${sc}</span></div><div class='bar'><i style='width:${idx/n*100}%'></i></div><p style='font-weight:700;font-size:1.15rem;margin:0'>${q.q}</p>`+q.o.map(function(o,i){return `<button class='opt' type='button' data-i='${i}'>${o}</button>`}).join('')+`<div class='ans' id='ex'></div><p style='margin:14px 0 0'><button class='btn' id='nx' type='button' style='display:none'></button></p>`;tx(qa)}
function fin(){var n=Q[cur].length,m=sc===n?'Sempurna! Coba tingkat berikutnya.':sc>=n/2?'Bagus. Pelajari pembahasan soal yang salah, lalu ulangi kuis ini.':'Tidak apa-apa. Baca lagi materinya, lalu coba kuis ini sekali lagi.';qa.innerHTML=`<div class='qm'><span>Tingkat ${cur}</span></div><div class='score'>${sc} / ${n}</div><p>${m}</p><button class='btn' id='ulang' type='button'>Ulangi kuis</button>`}
qa.addEventListener('click',function(e){var t=e.target.closest('button');if(!t)return;if(t.classList.contains('opt')&&!t.disabled){var q=Q[cur][idx],i=+t.dataset.i;qa.querySelectorAll('.opt').forEach(function(b,j){b.disabled=true;if(j===q.a)b.classList.add('good')});if(i===q.a)sc++;else t.classList.add('bad');var ex=document.getElementById('ex');ex.innerHTML=(i===q.a?'<b>Benar.</b> ':'<b>Belum tepat.</b> ')+q.e;ex.classList.add('open');var nx=document.getElementById('nx');nx.style.display='inline-block';nx.textContent=idx<Q[cur].length-1?'Soal berikutnya':'Lihat skor';tx(ex)}else if(t.id==='nx'){idx++;if(idx<Q[cur].length)ask();else fin()}else if(t.id==='ulang'){start(cur)}});
</script>
</body>
</html>
