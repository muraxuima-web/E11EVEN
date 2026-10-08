<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>E11EVEN — Premium Esports Club | Каспийск</title>
<meta name="description" content="E11EVEN Computer Game Club — новый уровень гейминга в РД. Каспийск, Амет-хана Султана 2/5. Бронирование по телефону 56-10-11.">
<link rel="icon" href="https://placehold.co/100x100/101014/ff6a00?text=E11EVEN">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Russo+One&family=Oswald:wght@300;400;500;600;700&family=Rubik:wght@300;400;500;700&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#070708;
  --bg2:#0c0c0f;
  --panel:#101014;
  --orange:#ff6a00;
  --orange2:#ffa04d;
  --text:#f2f2f5;
  --muted:#9a9aa3;
  --line:rgba(255,106,0,.28);
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  background:var(--bg);
  color:var(--text);
  font-family:'Rubik',sans-serif;
  overflow-x:hidden;
}
::selection{background:var(--orange);color:#000}
h1,h2,h3,.russ{font-family:'Russo One',sans-serif;font-weight:400}
.osw{font-family:'Oswald',sans-serif}

/* ===== фоновая сетка / неон ===== */
.bg-fx{
  position:fixed;inset:0;z-index:0;pointer-events:none;
  background:
    radial-gradient(60% 45% at 85% -5%, rgba(255,106,0,.10), transparent 60%),
    radial-gradient(50% 40% at 5% 100%, rgba(255,106,0,.07), transparent 60%),
    var(--bg);
}
.bg-grid{
  position:fixed;inset:0;z-index:0;pointer-events:none;opacity:.35;
  background-image:
    linear-gradient(rgba(255,106,0,.05) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,106,0,.05) 1px, transparent 1px);
  background-size:56px 56px;
  mask-image:radial-gradient(70% 60% at 50% 30%, #000 30%, transparent 100%);
}
.scan{
  position:fixed;inset:0;z-index:1;pointer-events:none;opacity:.05;
  background:repeating-linear-gradient(0deg, #fff 0 1px, transparent 1px 3px);
}
main,header,footer{position:relative;z-index:2}

/* ===== шапка ===== */
header{
  position:fixed;top:0;left:0;right:0;z-index:50;
  backdrop-filter:blur(14px);
  background:rgba(7,7,8,.72);
  border-bottom:1px solid rgba(255,106,0,.18);
}
.nav{
  max-width:1280px;margin:0 auto;padding:14px 24px;
  display:flex;align-items:center;gap:28px;
}
.brand{display:flex;align-items:center;gap:12px;text-decoration:none;color:var(--text)}
.brand img{width:44px;height:44px;border-radius:50%;border:2px solid var(--orange);box-shadow:0 0 18px rgba(255,106,0,.55)}
.brand .t1{font-family:'Russo One';font-size:20px;letter-spacing:1px}
.brand .t1 span{color:var(--orange)}
.brand .t2{font-size:10px;letter-spacing:4px;color:var(--muted);text-transform:uppercase}
.nav-links{display:flex;gap:26px;margin-left:auto}
.nav-links a{
  color:var(--muted);text-decoration:none;font-size:14px;letter-spacing:1.5px;
  text-transform:uppercase;font-family:'Oswald';transition:color .25s;position:relative;
}
.nav-links a::after{
  content:'';position:absolute;left:0;bottom:-6px;height:2px;width:0;
  background:var(--orange);box-shadow:0 0 10px var(--orange);transition:width .3s;
}
.nav-links a:hover{color:#fff}
.nav-links a:hover::after{width:100%}
.nav-call{
  display:flex;align-items:center;gap:8px;
  background:linear-gradient(120deg,var(--orange),#ff8a2a);
  color:#0a0a0a;font-family:'Oswald';font-weight:600;letter-spacing:1px;
  padding:10px 20px;border-radius:8px;text-decoration:none;font-size:14px;
  box-shadow:0 0 24px rgba(255,106,0,.45);
  transition:transform .2s, box-shadow .2s;
}
.nav-call:hover{transform:translateY(-2px);box-shadow:0 0 36px rgba(255,106,0,.7)}
.burger{display:none;margin-left:auto;background:none;border:1px solid var(--line);color:var(--orange);border-radius:8px;padding:8px 12px;font-size:18px;cursor:pointer}

/* ===== hero ===== */
.hero{
  min-height:100vh;display:flex;align-items:center;justify-content:center;
  text-align:center;padding:130px 24px 80px;position:relative;
}
.hero-inner{max-width:900px}
.hero .logo-ring{
  width:180px;height:180px;border-radius:50%;margin:0 auto 30px;
  border:2px solid rgba(255,106,0,.4);position:relative;
  box-shadow:0 0 60px rgba(255,106,0,.35), inset 0 0 40px rgba(255,106,0,.15);
  animation:pulse 3.2s ease-in-out infinite;
}
.hero .logo-ring img{width:100%;height:100%;border-radius:50%;object-fit:cover;display:block}
.hero .logo-ring::before{
  content:'';position:absolute;inset:-14px;border-radius:50%;
  border:1px dashed rgba(255,106,0,.35);animation:spin 22s linear infinite;
}
@keyframes spin{to{transform:rotate(360deg)}}
@keyframes pulse{0%,100%{box-shadow:0 0 50px rgba(255,106,0,.3)}50%{box-shadow:0 0 90px rgba(255,106,0,.55)}}
.hero .tag{
  font-family:'Oswald';letter-spacing:6px;text-transform:uppercase;
  color:var(--orange);font-size:14px;margin-bottom:14px;
}
.hero h1{
  font-size:clamp(44px,8vw,96px);line-height:1;
  text-transform:uppercase;
  background:linear-gradient(180deg,#fff 30%,#ffb377 100%);
  -webkit-background-clip:text;background-clip:text;color:transparent;
  filter:drop-shadow(0 0 30px rgba(255,106,0,.35));
}
.hero h1 span{color:var(--orange);-webkit-text-fill-color:var(--orange)}
.hero p.sub{margin:22px auto 8px;max-width:620px;color:var(--muted);font-size:17px;line-height:1.7}
.hero .addr{
  display:inline-flex;align-items:center;gap:10px;margin-top:14px;
  font-family:'Oswald';letter-spacing:1px;color:#d7d7de;font-size:15px;
  border:1px solid var(--line);border-radius:999px;padding:10px 22px;
  background:rgba(255,106,0,.06);
}
.hero .addr svg{width:16px;height:16px;stroke:var(--orange)}
.hero-cta{margin-top:34px;display:flex;gap:16px;justify-content:center;flex-wrap:wrap}
.btn{
  font-family:'Oswald';font-weight:600;letter-spacing:2px;text-transform:uppercase;
  text-decoration:none;padding:16px 38px;border-radius:10px;font-size:16px;
  transition:transform .2s, box-shadow .25s, background .25s;
  display:inline-flex;align-items:center;gap:10px;
}
.btn-call{
  background:linear-gradient(120deg,var(--orange),#ff8a2a);color:#0a0a0a;
  box-shadow:0 0 30px rgba(255,106,0,.5);
}
.btn-call:hover{transform:translateY(-3px) scale(1.02);box-shadow:0 0 50px rgba(255,106,0,.8)}
.btn-ghost{
  color:var(--text);border:1px solid var(--line);background:rgba(255,106,0,.05);
}
.btn-ghost:hover{background:rgba(255,106,0,.14);transform:translateY(-3px)}
.stats{
  margin-top:56px;display:flex;justify-content:center;gap:0;flex-wrap:wrap;
  border:1px solid var(--line);border-radius:16px;overflow:hidden;
  background:rgba(255,106,0,.04);backdrop-filter:blur(6px);
}
.stat{padding:22px 46px;text-align:center;border-right:1px solid rgba(255,106,0,.15)}
.stat:last-child{border-right:none}
.stat b{display:block;font-family:'Russo One';font-size:30px;color:var(--orange)}
.stat span{font-size:12px;letter-spacing:2px;text-transform:uppercase;color:var(--muted)}

/* ===== секции ===== */
section{padding:100px 24px;max-width:1280px;margin:0 auto}
.sec-head{text-align:center;margin-bottom:60px}
.sec-head .kicker{
  font-family:'Oswald';letter-spacing:6px;text-transform:uppercase;
  color:var(--orange);font-size:13px;margin-bottom:12px;
}
.sec-head h2{
  font-size:clamp(30px,5vw,52px);text-transform:uppercase;
  background:linear-gradient(180deg,#fff,#ffb377);
  -webkit-background-clip:text;background-clip:text;color:transparent;
}
.sec-head .line{
  width:90px;height:3px;margin:20px auto 0;
  background:linear-gradient(90deg,transparent,var(--orange),transparent);
  box-shadow:0 0 16px var(--orange);
}

/* карточки прайса */
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(270px,1fr));gap:28px}
.card{
  background:var(--panel);border:1px solid rgba(255,106,0,.18);border-radius:18px;
  overflow:hidden;position:relative;
  transition:transform .3s, box-shadow .3s, border-color .3s;
}
.card:hover{transform:translateY(-8px);border-color:var(--orange);box-shadow:0 20px 60px rgba(255,106,0,.22)}
.card .imgwrap{position:relative;overflow:hidden}
.card img{width:100%;display:block;height:auto;transition:transform .6s}
.card:hover img{transform:scale(1.04)}
.card .body{padding:22px 22px 26px;position:relative;border-top:1px solid rgba(255,106,0,.15)}
.card h3{font-size:24px;text-transform:uppercase;letter-spacing:1px;margin-bottom:6px}
.card h3 span{color:var(--orange)}
.card .sub{font-size:13px;color:var(--muted);margin-bottom:16px;letter-spacing:1px}
.price-list{list-style:none}
.price-list li{
  display:flex;justify-content:space-between;align-items:baseline;gap:12px;
  padding:9px 0;border-bottom:1px dashed rgba(255,255,255,.08);font-size:14px;
}
.price-list li span{color:var(--muted)}
.price-list li b{
  font-family:'Oswald';color:var(--orange);font-size:17px;white-space:nowrap;
  text-shadow:0 0 14px rgba(255,106,0,.5);
}
.card .btn-book{
  display:block;text-align:center;margin-top:20px;
  font-family:'Oswald';font-weight:600;letter-spacing:2px;text-transform:uppercase;
  color:#0a0a0a;background:linear-gradient(120deg,var(--orange),#ff8a2a);
  border-radius:10px;padding:13px;text-decoration:none;font-size:14px;
  box-shadow:0 0 22px rgba(255,106,0,.4);transition:transform .2s, box-shadow .25s;
}
.card .btn-book:hover{transform:translateY(-2px);box-shadow:0 0 38px rgba(255,106,0,.7)}

/* зоны / железо */
.specs{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:28px}
.spec{
  position:relative;border-radius:18px;overflow:hidden;
  border:1px solid rgba(255,106,0,.16);background:var(--panel);
  transition:transform .3s, box-shadow .3s, border-color .3s;
}
.spec:hover{transform:translateY(-8px);border-color:var(--orange);box-shadow:0 20px 60px rgba(255,106,0,.22)}
.spec img{width:100%;display:block;height:auto;transition:transform .6s}
.spec:hover img{transform:scale(1.05)}
.spec .cap{
  padding:16px 22px;border-top:1px solid rgba(255,106,0,.15);background:var(--panel);
}
.spec .cap h3{font-size:22px;text-transform:uppercase}
.spec .cap h3 span{color:var(--orange)}
.spec .cap p{font-size:12px;color:var(--muted);letter-spacing:1.5px;text-transform:uppercase;margin-top:4px}

/* контакты */
.contacts-grid{display:grid;grid-template-columns:1.1fr .9fr;gap:40px;align-items:stretch}
@media(max-width:900px){.contacts-grid{grid-template-columns:1fr}}
.contact-card{
  background:var(--panel);border:1px solid rgba(255,106,0,.18);border-radius:18px;
  padding:38px;position:relative;overflow:hidden;
}
.contact-card::before{
  content:'';position:absolute;top:-60px;right:-60px;width:220px;height:220px;
  border-radius:50%;background:radial-gradient(circle,rgba(255,106,0,.22),transparent 70%);
}
.c-row{display:flex;align-items:flex-start;gap:16px;margin-bottom:26px}
.c-ico{
  width:48px;height:48px;flex:none;border-radius:12px;display:flex;align-items:center;justify-content:center;
  border:1px solid var(--line);background:rgba(255,106,0,.08);
}
.c-ico svg{width:22px;height:22px;stroke:var(--orange);fill:none;stroke-width:1.8}
.c-row h4{font-family:'Oswald';letter-spacing:2px;text-transform:uppercase;font-size:13px;color:var(--muted);margin-bottom:6px}
.c-row p{font-size:17px;line-height:1.5}
.c-row a{color:var(--text);text-decoration:none}
.c-row a:hover{color:var(--orange)}
.big-call{
  display:flex;align-items:center;justify-content:center;gap:14px;
  background:linear-gradient(120deg,var(--orange),#ff8a2a);color:#0a0a0a;
  font-family:'Russo One';font-size:clamp(20px,3vw,28px);letter-spacing:1px;
  border-radius:14px;padding:24px;text-decoration:none;text-align:center;
  box-shadow:0 0 40px rgba(255,106,0,.5);transition:transform .2s, box-shadow .25s;
}
.big-call:hover{transform:translateY(-3px);box-shadow:0 0 70px rgba(255,106,0,.8)}
.profile-shot{
  border-radius:18px;overflow:hidden;border:1px solid rgba(255,106,0,.18);
  position:relative;min-height:100%;
}
.profile-shot img{width:100%;height:100%;object-fit:cover;object-position:top;display:block}
.profile-shot::after{
  content:'@eleven__esportsclub';
  position:absolute;left:0;right:0;bottom:0;padding:36px 24px 18px;
  font-family:'Oswald';letter-spacing:2px;color:#fff;
  background:linear-gradient(180deg,transparent,rgba(7,7,8,.95));
}

/* плавающая кнопка звонка */
.float-call{
  position:fixed;right:22px;bottom:22px;z-index:60;
  display:flex;align-items:center;gap:12px;text-decoration:none;
  background:linear-gradient(120deg,var(--orange),#ff8a2a);color:#0a0a0a;
  font-family:'Oswald';font-weight:700;letter-spacing:1.5px;font-size:15px;
  padding:16px 26px 16px 18px;border-radius:999px;
  box-shadow:0 0 34px rgba(255,106,0,.6);
  transition:transform .2s, box-shadow .25s;
}
.float-call:hover{transform:scale(1.06);box-shadow:0 0 56px rgba(255,106,0,.85)}
.float-call .ring{
  width:22px;height:22px;flex:none;animation:ring 1.6s ease-in-out infinite;
}
@keyframes ring{0%,100%{transform:rotate(0)}10%{transform:rotate(14deg)}20%{transform:rotate(-12deg)}30%{transform:rotate(10deg)}40%{transform:rotate(-8deg)}50%{transform:rotate(0)}}
.float-call .pulse-dot{
  position:absolute;top:2px;left:2px;width:14px;height:14px;border-radius:50%;
  background:#fff;animation:pulse 1.8s infinite;
}

/* footer */
footer{
  border-top:1px solid rgba(255,106,0,.15);
  background:rgba(12,12,15,.8);padding:44px 24px;text-align:center;
}
footer .f-logo{font-family:'Russo One';font-size:22px}
footer .f-logo span{color:var(--orange)}
footer p{color:var(--muted);font-size:13px;margin-top:10px;letter-spacing:1px}
footer a{color:var(--orange);text-decoration:none}

/* reveal анимация */
.reveal{opacity:0;transform:translateY(36px);transition:opacity .8s ease, transform .8s ease}
.reveal.visible{opacity:1;transform:none}

@media(max-width:860px){
  .nav-links,.nav-call{display:none}
  .burger{display:block}
  .nav-links.open{
    display:flex;flex-direction:column;position:absolute;top:100%;left:0;right:0;
    background:rgba(7,7,8,.97);padding:20px 24px;gap:18px;border-bottom:1px solid var(--line);
  }
  .stat{padding:18px 26px}
  section{padding:70px 20px}
  .float-call span.txt{display:none}
  .float-call{padding:16px}
}
</style>
</head>
<body>

<div class="bg-fx"></div>
<div class="bg-grid"></div>
<div class="scan"></div>

<!-- ===== ШАПКА ===== -->
<header>
  <nav class="nav">
    <a class="brand" href="#top">
      <img src="https://placehold.co/100x100/101014/ff6a00?text=E11" alt="E11EVEN">
      <div>
        <div class="t1">E<span>11</span>EVEN</div>
        <div class="t2">Premium Esports Club</div>
      </div>
    </a>
    <div class="nav-links" id="navLinks">
      <a href="#prices">Прайс</a>
      <a href="#zones">Железо</a>
      <a href="#contacts">Контакты</a>
    </div>
    <a class="nav-call" href="tel:+78722561011">
      <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6A19.79 19.79 0 0 1 2.08 4.18 2 2 0 0 1 4.06 2h3a2 2 0 0 1 2 1.72c.13.96.36 1.9.7 2.81a2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45c.91.34 1.85.57 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
      56-10-11
    </a>
    <button class="burger" id="burger" aria-label="Меню">☰</button>
  </nav>
</header>

<main id="top">

  <!-- ===== HERO ===== -->
  <div class="hero">
    <div class="hero-inner">
      <div class="logo-ring reveal"><img src="https://placehold.co/200x200/101014/ff6a00?text=E11EVEN" alt="E11EVEN Premium Esports Club"></div>
      <div class="tag reveal">Компьютерный клуб · PC · Каспийск</div>
      <h1 class="reveal">E<span>11</span>EVEN</h1>
      <p class="sub reveal">E11EVEN | Computer Game Club 🎮<br>Новый уровень гейминга в РД</p>
      <div class="addr reveal">
        <svg viewBox="0 0 24 24" fill="none" stroke-width="2"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/><circle cx="12" cy="10" r="3"/></svg>
        Каспийск, Амет-хана Султана 2/5
      </div>
      <div class="hero-cta reveal">
        <a class="btn btn-call" href="tel:+78722561011">
          <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6A19.79 19.79 0 0 1 2.08 4.18 2 2 0 0 1 4.06 2h3a2 2 0 0 1 2 1.72c.13.96.36 1.9.7 2.81a2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45c.91.34 1.85.57 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
          Забронировать место
        </a>
        <a class="btn btn-ghost" href="#prices">Смотреть прайс</a>
      </div>
    </div>
  </div>

  <!-- ===== ПРАЙС ===== -->
  <section id="prices">
    <div class="sec-head reveal">
      <div class="kicker">Тарифы</div>
      <h2>Прайс</h2>
      <div class="line"></div>
    </div>

    <div class="cards">
      <!-- Общий зал -->
      <div class="card reveal">
        <div class="imgwrap"><img src="https://placehold.co/600x400/101014/ff6a00?text=HALL+ZONE" alt="Прайс — Общий зал" loading="lazy"></div>
        <div class="body">
          <h3>Общий <span>зал</span></h3>
          <div class="sub">RTX 5070 · Ryzen 5 9600X · AOC 260Hz</div>
          <ul class="price-list">
            <li><span>Час (день 8:00–18:00)</span><b>130 ₽</b></li>
            <li><span>Час (вечер 18:00–8:00)</span><b>150 ₽</b></li>
            <li><span>3 часа</span><b>350 ₽</b></li>
            <li><span>5 часов</span><b>590 ₽</b></li>
            <li><span>Ночь (23:00–8:00)</span><b>600 ₽</b></li>
            <li><span>Утро (8:00–13:00)</span><b>399 ₽</b></li>
          </ul>
          <a class="btn-book" href="tel:+78722561011">Забронировать</a>
        </div>
      </div>

      <!-- ВИП -->
      <div class="card reveal">
        <div class="imgwrap"><img src="https://placehold.co/600x400/101014/ff6a00?text=VIP+ZONE" alt="Прайс — ВИП" loading="lazy"></div>
        <div class="body">
          <h3><span>ВИП</span></h3>
          <div class="sub">VIP White · VIP Black · RTX 5070 Ti</div>
          <ul class="price-list">
            <li><span>Час (день 8:00–18:00)</span><b>250 ₽</b></li>
            <li><span>Час (вечер 18:00–8:00)</span><b>280 ₽</b></li>
            <li><span>3 часа</span><b>670 ₽</b></li>
            <li><span>5 часов</span><b>1090 ₽</b></li>
            <li><span>Ночь (23:00–8:00)</span><b>999 ₽</b></li>
            <li><span>Утро (8:00–13:00)</span><b>499 ₽</b></li>
          </ul>
          <a class="btn-book" href="tel:+78722561011">Забронировать</a>
        </div>
      </div>

      <!-- Буткемп -->
      <div class="card reveal">
        <div class="imgwrap"><img src="https://placehold.co/600x400/101014/ff6a00?text=BOOTCAMP" alt="Прайс — Буткемп" loading="lazy"></div>
        <div class="body">
          <h3>Бут<span>кемп</span></h3>
          <div class="sub">Bootcamp 1 · Bootcamp 2 · RTX 5080</div>
          <ul class="price-list">
            <li><span>Час (день 8:00–18:00)</span><b>340 ₽</b></li>
            <li><span>Час (вечер 18:00–8:00)</span><b>380 ₽</b></li>
            <li><span>3 часа</span><b>890 ₽</b></li>
            <li><span>5 часов</span><b>1390 ₽</b></li>
            <li><span>Ночь (23:00–8:00)</span><b>1299 ₽</b></li>
            <li><span>Утро (8:00–13:00)</span><b>699 ₽</b></li>
          </ul>
          <a class="btn-book" href="tel:+78722561011">Забронировать</a>
        </div>
      </div>

      <!-- СуперВИП -->
      <div class="card reveal">
        <div class="imgwrap"><img src="https://placehold.co/600x400/101014/ff6a00?text=SUPER+VIP" alt="Прайс — СуперВИП" loading="lazy"></div>
        <div class="body">
          <h3>Супер<span>ВИП</span></h3>
          <div class="sub">SUPER VIP · RTX 5090 · Ryzen 9 9950X3D</div>
          <ul class="price-list">
            <li><span>Час (день 8:00–18:00)</span><b>480 ₽</b></li>
            <li><span>Час (вечер 18:00–8:00)</span><b>530 ₽</b></li>
            <li><span>3 часа</span><b>1250 ₽</b></li>
            <li><span>5 часов</span><b>1990 ₽</b></li>
            <li><span>Ночь (23:00–8:00)</span><b>1999 ₽</b></li>
            <li><span>Утро (8:00–13:00)</span><b>999 ₽</b></li>
          </ul>
          <a class="btn-book" href="tel:+78722561011">Забронировать</a>
        </div>
      </div>
    </div>
  </section>

  <!-- ===== ЗОНЫ / ЖЕЛЕЗО ===== -->
  <section id="zones">
    <div class="sec-head reveal">
      <div class="kicker">Конфигурации</div>
      <h2>Железо</h2>
      <div class="line"></div>
    </div>

    <div class="specs">
      <div class="spec reveal">
        <img src="https://placehold.co/600x400/101014/ff6a00?text=HALL+SPEC" alt="HALL — характеристики" loading="lazy">
        <div class="cap"><h3>HALL</h3><p>Ryzen 5 9600X · RTX 5070 · AOC 260Hz</p></div>
      </div>
      <div class="spec reveal">
        <img src="https://placehold.co/600x400/101014/ff6a00?text=VIP+BLACK+SPEC" alt="VIP BLACK — характеристики" loading="lazy">
        <div class="cap"><h3>VIP <span>BLACK</span></h3><p>Ryzen 7 7800X3D · RTX 5070 Ti · 2K 300Hz</p></div>
      </div>
      <div class="spec reveal">
        <img src="https://placehold.co/600x400/101014/ff6a00?text=VIP+WHITE+SPEC" alt="VIP WHITE — характеристики" loading="lazy">
        <div class="cap"><h3>VIP <span>WHITE</span></h3><p>Ryzen 7 7800X3D · RTX 5070 Ti · 2K 300Hz</p></div>
      </div>
      <div class="spec reveal">
        <img src="https://placehold.co/600x400/101014/ff6a00?text=BOOTCAMP+1+SPEC" alt="BOOTCAMP 1 — характеристики" loading="lazy">
        <div class="cap"><h3>BOOTCAMP <span>1</span></h3><p>Ryzen 7 7800X3D · RTX 5080 · 2K 320Hz</p></div>
      </div>
      <div class="spec reveal">
        <img src="https://placehold.co/600x400/101014/ff6a00?text=BOOTCAMP+2+SPEC" alt="BOOTCAMP 2 — характеристики" loading="lazy">
        <div class="cap"><h3>BOOTCAMP <span>2</span></h3><p>Ryzen 7 7800X3D · RTX 5080 · 2K 320Hz</p></div>
      </div>
      <div class="spec reveal">
        <img src="https://placehold.co/600x400/101014/ff6a00?text=SUPER+VIP+SPEC" alt="SUPER VIP — характеристики" loading="lazy">
        <div class="cap"><h3>SUPER <span>VIP</span></h3><p>Ryzen 9 9950X3D · RTX 5090 · AORUS 500Hz</p></div>
      </div>
    </div>
  </section>

  <!-- ===== КОНТАКТЫ ===== -->
  <section id="contacts">
    <div class="sec-head reveal">
      <div class="kicker">Мы ждём тебя</div>
      <h2>Контакты</h2>
      <div class="line"></div>
    </div>

    <div class="contacts-grid">
      <div class="contact-card reveal">
        <div class="c-row">
          <div class="c-ico"><svg viewBox="0 0 24 24"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/><circle cx="12" cy="10" r="3"/></svg></div>
          <div>
            <h4>Адрес</h4>
            <p>Каспийск, Амет-хана Султана 2/5</p>
          </div>
        </div>
        <div class="c-row">
          <div class="c-ico"><svg viewBox="0 0 24 24"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6A19.79 19.79 0 0 1 2.08 4.18 2 2 0 0 1 4.06 2h3a2 2 0 0 1 2 1.72c.13.96.36 1.9.7 2.81a2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45c.91.34 1.85.57 2.81.7A2 2 0 0 1 22 16.92z"/></svg></div>
          <div>
            <h4>Телефон</h4>
            <p><a href="tel:+78722561011">56-10-11</a></p>
          </div>
        </div>
        <div class="c-row">
          <div class="c-ico"><svg viewBox="0 0 24 24"><rect x="2" y="2" width="20" height="20" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.5" cy="6.5" r=".8" fill="currentColor"/></svg></div>
          <div>
            <h4>Instagram</h4>
            <p><a href="https://instagram.com/eleven__esportsclub" target="_blank" rel="noopener">@eleven__esportsclub</a></p>
          </div>
        </div>
        <div class="c-row">
          <div class="c-ico"><svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="9"/><path d="M12 7v5l3 3"/></svg></div>
          <div>
            <h4>Режим работы</h4>
            <p>Круглосуточно · день 8:00–18:00 · вечер 18:00–8:00</p>
          </div>
        </div>
        <a class="big-call" href="tel:+78722561011">
          <svg width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6A19.79 19.79 0 0 1 2.08 4.18 2 2 0 0 1 4.06 2h3a2 2 0 0 1 2 1.72c.13.96.36 1.9.7 2.81a2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45c.91.34 1.85.57 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
          ЗАБРОНИРОВАТЬ · 56-10-11
        </a>
      </div>
      <div class="profile-shot reveal">
        <img src="https://placehold.co/600x800/101014/ff6a00?text=CLUB+PROFILE" alt="E11EVEN — профиль клуба">
      </div>
    </div>
  </section>

</main>

<!-- ===== ПЛАВАЮЩАЯ КНОПКА ЗВОНКА ===== -->
<a class="float-call" href="tel:+78722561011" aria-label="Позвонить и забронировать">
  <span class="pulse-dot"></span>
  <svg class="ring" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6A19.79 19.79 0 0 1 2.08 4.18 2 2 0 0 1 4.06 2h3a2 2 0 0 1 2 1.72c.13.96.36 1.9.7 2.81a2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45c.91.34 1.85.57 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
  <span class="txt">Забронировать · 56-10-11</span>
</a>

<!-- ===== ФУТЕР ===== -->
<footer>
  <div class="f-logo">E<span>11</span>EVEN</div>
  <p>Premium Esports Club · Новый уровень гейминга в РД</p>
  <p>Каспийск, Амет-хана Султана 2/5 · Телефон: <a href="tel:+78722561011">56-10-11</a> · <a href="https://instagram.com/eleven__esportsclub" target="_blank" rel="noopener">@eleven__esportsclub</a></p>
  <p style="margin-top:16px;opacity:.6">© 2026 E11EVEN. Все права защищены.</p>
</footer>

<script>
// reveal при скролле
const io = new IntersectionObserver((entries)=>{
  entries.forEach(e=>{ if(e.isIntersecting){ e.target.classList.add('visible'); io.unobserve(e.target);} });
},{threshold:.12});
document.querySelectorAll('.reveal').forEach(el=>io.observe(el));

// мобильное меню
const burger=document.getElementById('burger');
const navLinks=document.getElementById('navLinks');
burger.addEventListener('click',()=>navLinks.classList.toggle('open'));
navLinks.querySelectorAll('a').forEach(a=>a.addEventListener('click',()=>navLinks.classList.remove('open')));
</script>
</body>
</html>
