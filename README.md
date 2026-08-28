# TEAM-HAWK
<!DOCTYPE html>
<html lang="ms">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TEAM HAWK | Official Esports</title>

<style>
*{margin:0; padding:0; box-sizing:border-box; scroll-behavior:smooth;}
body{font-family:Arial,Helvetica,sans-serif; background:#050505; color:#fff;}
:root{--red:#e50925;}

/* NAVBAR MOBILE */
nav{position:fixed; width:100%; top:0; z-index:999; background:rgba(0,0,0,.95); border-bottom:1px solid #292929;}
.navbar{max-width:1200px; margin:auto; padding:16px 20px; display:flex; justify-content:space-between; align-items:center;}
.brand{font-size:22px; font-weight:1000; letter-spacing:2px;}
.brand span{color:var(--red);}
.menu-toggle{display:block; font-size:28px; color:white; cursor:pointer; background:none; border:none;}
.nav-links{display:none; position:absolute; top:60px; left:0; width:100%; background:#0a0a0a; flex-direction:column;}
.nav-links.active{display:flex;}
.nav-links a{color:white; text-decoration:none; font-size:14px; font-weight:bold; padding:15px 20px; border-bottom:1px solid #222;}
.nav-links a:hover{background:var(--red);}

/* HERO */
.hero{min-height:100vh; display:flex; align-items:center; background:linear-gradient(120deg,#030303,#111,#26070b);}
.hero-content{max-width:1200px; width:100%; margin:auto; padding:130px 20px 80px; text-align:center;}
.tag{color:var(--red); font-size:12px; letter-spacing:4px; font-weight:900;}
.hero h1{font-size:clamp(50px,15vw,130px); line-height:.9; margin-top:15px; font-weight:1000; letter-spacing:-3px;}
.hero h1 span{color:var(--red);}
.slogan{margin-top:20px; font-size:18px; font-weight:900;}
.hero p{color:#aaa; line-height:1.7; margin:12px auto 0; max-width:600px;}
.btn{display:inline-block; margin-top:30px; padding:14px 24px; background:var(--red); color:white; text-decoration:none; font-weight:900; border-radius:5px;}

section{padding:70px 20px;}
.container{max-width:1200px; margin:auto;}
.section-title{font-size:32px; font-weight:1000; text-transform:uppercase; margin-bottom:10px; text-align:center;}
.section-title span{color:var(--red);}
.section-desc{color:#888; margin-bottom:35px; text-align:center;}

/* SEMUA GRID JADI 1 KOLUM UNTUK MOBILE */
.story-box{border-left:4px solid var(--red); background:#121212; padding:25px; border-radius:10px;}
.story-box p{color:#ccc; line-height:1.9;}
.stats, .teams, .roster, .achievement-gallery, .matches{display:grid; grid-template-columns:1fr; gap:18px;}
.stat, .team-card, .generation, .achievement-card, .match{background:#111; border:1px solid #292929; padding:25px; border-radius:10px;}
.stat strong{display:block; color:var(--red); font-size:35px;}

/* LOGO */
.logo-timeline{display:grid; grid-template-columns:1fr; gap:20px;}
.logo-card{background:#111; border:1px solid #292929; padding:20px; text-align:center; border-radius:10px;}
.logo-placeholder{height:200px; background:#181818; border:2px dashed #444; display:flex; justify-content:center; align-items:center; margin-bottom:15px; border-radius:10px;}
.logo-placeholder img{width:100%; height:100%; object-fit:contain;}
.logo-card h3{color:var(--red);}
.arrow{text-align:center; color:var(--red); font-size:35px; transform:rotate(90deg);}

/* ROSTER */
.generation{position:relative;}
.generation:before{content:""; position:absolute; top:0; left:0; width:100%; height:3px; background:var(--red);}
.generation small{color:var(--red); font-weight:bold;}
.generation h3{margin:10px 0 18px;}
.generation ol{margin-left:20px; color:#ddd;}

/* ACHIEVEMENT */
.achievement-card img{width:100%; height:200px; object-fit:cover; background:#1a1a1a; border-radius:10px 10px 0 0;}
.caption{padding:15px 0 0;}
.caption h3{color:var(--red);}
.caption p{color:#aaa; margin-top:8px; font-size:14px;}

/* JOURNEY */
.journey-card{background:#111; border-left:4px solid var(--red); padding:20px; margin-bottom:20px; border-radius:10px;}
.journey-card h3{color:var(--red); font-size:20px;}

footer{text-align:center; padding:25px; color:#666; border-top:1px solid #222;}

/* DESKTOP 900px KE ATAS */
@media(min-width:900px){
    .menu-toggle{display:none;}
    .nav-links{display:flex; position:static; flex-direction:row; width:auto; background:none;}
    .nav-links a{border:none; padding:0 15px;}
    .hero-content{text-align:left;}
    .logo-timeline{grid-template-columns:1fr auto 1fr auto 1fr;}
    .arrow{transform:rotate(0deg);}
    .stats{grid-template-columns:repeat(3,1fr);}
    .teams, .matches{grid-template-columns:1fr 1fr;}
    .roster{grid-template-columns:repeat(4,1fr);}
    .achievement-gallery{grid-template-columns:repeat(4,1fr);}
    section{padding:90px 25px;}
}
</style>
</head>
<body>

<nav>
<div class="navbar">
<div class="brand">TEAM <span>HAWK</span></div>
<button class="menu-toggle" onclick="document.querySelector('.nav-links').classList.toggle('active')">☰</button>
<div class="nav-links">
<a href="#home">HOME</a><a href="#story">STORY</a><a href="#roster">ROSTER</a><a href="#achievement">ACHIEVEMENTS</a><a href="#journey">JOURNEY</a>
</div>
</div>
</nav>

<header class="hero" id="home">
<div class="hero-content">
<div class="tag">OFFICIAL ESPORTS TEAM</div>
<h1>TEAM <span>HAWK</span></h1>
<div class="slogan">HAWK NEVER BACKS DOWN.</div>
<p>Selamat datang ke laman rasmi TEAM HAWK. Kenali sejarah pasukan, generasi roster, pencapaian dan perjalanan TEAM HAWK.</p>
<a href="#story" class="btn">OUR STORY</a>
</div>
</header>

<section id="story" class="story">
<div class="container">
<div class="section-title">OUR <span>STORY</span></div>
<div class="story-box">
<p>TEAM HAWK telah dibentuk oleh <strong>MUHAMMAD ADAM AMMAR BIN RUSMAINI</strong> pada tahun <strong>2023</strong> bersama <strong>4 orang rakan penolong</strong>.</p><br>
<p>Daripada sebuah pasukan yang bermula secara kecil, TEAM HAWK terus berkembang melalui pengalaman, persahabatan dan semangat untuk bersaing dalam dunia esports.</p><br>
<p>Kini organisasi ini mempunyai dua pasukan, iaitu <strong>HAWK</strong> dan <strong>ORCA</strong>, dengan keseluruhan <strong>12 pemain</strong>.</p>
</div>
<div class="stats">
<div class="stat"><strong>2023</strong>Tahun Ditubuhkan</div>
<div class="stat"><strong>2</strong>Pasukan</div>
<div class="stat"><strong>12</strong>Pemain</div>
</div>
</div>
</section>

<section>
<div class="container">
<div class="logo-timeline">
<div class="logo-card"><div class="logo-placeholder"><img src="eagle.jpg" alt="Logo NADI 2023"></div><h3>LOGO 01</h3><p>Logo pertama / 2023</p></div>
<div class="arrow">→</div>
<div class="logo-card"><div class="logo-placeholder"><img src="nevros.jpg" alt="Logo Nadi 2025"></div><h3>LOGO 02</h3><p>Logo S2 dan S3</p></div>
<div class="arrow">→</div>
<div class="logo-card"><div class="logo-placeholder"><img src="hawk.jpg" alt="Logo Nadi 2026"></div><h3>LOGO TERKINI</h3><p>Identiti TEAM HAWK sekarang</p></div>
</div>
<section>
<div class="container">
<div class="section-title">OUR <span>TEAMS</span></div>
<div class="teams">
<div class="team-card"><h3>HAWK</h3><p>Pasukan utama yang membawa nama TEAM HAWK dalam pertandingan esports.</p></div>
<div class="team-card"><h3>ORCA</h3><p>Pasukan kedua di bawah organisasi yang sama, terus berkembang bersama keluarga TEAM HAWK.</p></div>
</div>
</div>
</section>

<section id="roster">
<div class="container">
<div class="section-title">TEAM <span>ROSTER</span></div>
<div class="roster">
<div class="generation"><small>GENERATION 01</small><h3>GENERASI PERTAMA</h3><ol><li>Kanzoro</li><li>Adibrembo</li><li>umarhangsamu</li><li>uping</li><li>dragon</li><li>todak fc</li></ol></div>
<div class="generation"><small>GENERATION 02</small><h3>GENERASI KEDUA</h3><ol><li>Obama</li><li>Adibrembo</li><li>pewira windara</li><li>todak fc</li><li>aqil</li></ol></div>
<div class="generation"><small>GENERATION 03</small><h3>GENERASI KETIGA</h3><ol><li>Obama</li><li>Jewjewchan</li><li>ambatukam</li><li>faris shazalan</li><li>only</li></ol></div>
<div class="generation"><small>GENERATION 04</small><h3>GENERASI KEEMPAT</h3><ol><li>OWZYE</li><li>KRZYE</li><li>ACHAALUV</li><li>XYPHOR</li><li>HAYASAKA</li><li>SKYWALKER</li></ol></div>
</div>
</div>
</section>

<section id="achievement">
<div class="container">
<div class="section-title">OUR <span>ACHIEVEMENTS</span></div>
<div class="achievement-gallery">
<div class="achievement-card"><img src="nadi aci s1.jpg" alt="Pencapaian 1"><div class="caption"><h3>NADI S1</h3><p>TEAM HAWK berjaya muncul sebagai <strong>JOHAN</strong>.</p></div></div>
<div class="achievement-card"><img src="nadi aci s2.jpg" alt="Pencapaian 2"><div class="caption"><h3>NADI S2</h3><p>TEAM HAWK berjaya menamatkan kejohanan sebagai <strong>NAIB JOHAN</strong>.</p></div></div>
<div class="achievement-card"><img src="Aci s3.jpg" alt="Pencapaian 3"><div class="caption"><h3>NADI S3</h3><p>TEAM HAWK berjaya mendapat <strong>TEMPAT KE-3</strong>.</p></div></div>
<div class="achievement-card"><img src="Aci s4.jpg" alt="Pencapaian 4"><div class="caption"><h3>NADI S4</h3><p>TEAM HAWK berjaya merangkul gelaran <strong>JOHAN</strong>.</p></div></div>
<div class="achievement-card"><img src="Highlight s1.jpg" alt="Pencapaian 5"><div class="caption"><h3>HIGHLIGHT GAME S1</h3><p>.</p></div></div>
<div class="achievement-card"><img src="Highlight s2.jpg" alt="Pencapaian 6"><div class="caption"><h3>HIGHLIGHT GAME S2</h3><p> .</p></div></div>
<div class="achievement-card"><img src="Highlight s3.jpg" alt="Pencapaian 7"><div class="caption"><h3>HIGHLIGHT GAME S3</h3><p>.</p></div></div>
<div class="achievement-card"><img src="Highlight s4.jpg" alt="Pencapaian 8"><div class="caption"><h3>HIGHLIGHT GAME S4</h3><p> </p></div></div>
</div>
</div>
</section>

<section id="journey" class="journey">
<div class="container">
<div class="section-title">THE <span>JOURNEY</span></div>
<div class="timeline">
<div class="journey-card"><h3>NADI S1 — THE BEGINNING</h3><p>Inilah permulaan perjalanan TEAM HAWK. TEAM HAWK berjaya muncul sebagai <strong>JOHAN NADI S1</strong>.</p></div>
<div class="journey-card"><h3>NADI S2 — KEEP MOVING</h3><p>Pasukan terus berjuang sehingga berjaya menduduki tempat sebagai <strong>NAIB JOHAN</strong>.</p></div>
<div class="journey-card"><h3>NADI S3 — NEVER GIVE UP</h3><p>TEAM HAWK mendapat <strong>TEMPAT KE-3</strong>. Pengalaman ini menjadi motivasi untuk bangkit.</p></div>
<div class="journey-card"><h3>NADI S4 — BACK TO THE TOP</h3><p>TEAM HAWK berjaya menjadi <strong>JOHAN NADI S4</strong>.</p></div>
</div>
</div>
</section>

<footer>© 2026 TEAM HAWK — OFFICIAL ESPORTS TEAM</footer>
</body>
</html>