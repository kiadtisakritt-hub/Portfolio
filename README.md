# Portfolio
<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>เกียรติศักดิ์ ฤทธิมาร | IT Solution Consultant / IT Manager</title>
<meta name="description" content="พอร์ตโฟลิโอของเกียรติศักดิ์ ฤทธิมาร – IT Solution Consultant / IT Manager">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@300;400;600;700;800&family=Raleway:wght@500;700;800&display=swap" rel="stylesheet">
<style>
  :root{
    --ink:#2b2b2b;
    --side:#2f2f2f;
    --side-text:#f2f2f2;
    --paper:#ffffff;
    --bg:#e4e4e4;
    --muted:#6b6b6b;
    --line:#d9d9d9;
    --accent:#2f2f2f;
  }
  *{box-sizing:border-box;margin:0;padding:0}
  html{scroll-behavior:smooth}
  body{
    font-family:"Noto Sans Thai","Raleway",system-ui,sans-serif;
    background:var(--bg);
    color:var(--ink);
    line-height:1.7;
    padding:32px 16px;
  }
  .page{
    max-width:980px;
    margin:0 auto;
    background:var(--paper);
    display:grid;
    grid-template-columns:300px 1fr;
    box-shadow:0 8px 30px rgba(0,0,0,.15);
    min-height:1100px;
  }

  /* ---------- Sidebar ---------- */
  .side{
    background:var(--side);
    color:var(--side-text);
    margin:0 0 0 28px;
    padding:40px 24px 40px;
    display:flex;
    flex-direction:column;
    gap:28px;
  }
  .photo{
    width:200px;height:200px;
    margin:0 auto;
    border-radius:50%;
    border:8px solid #fff;
    outline:6px solid var(--side);
    overflow:hidden;
    background:#fff;
    box-shadow:0 0 0 14px #fff;
    margin-top:-6px;
  }
  .photo img{width:100%;height:100%;object-fit:cover;object-position:50% 30%;display:block}

  .side h2{
    font-size:1rem;font-weight:700;
    display:flex;align-items:center;gap:10px;
    margin-bottom:10px;
    color:#fff;
  }
  .side h2 .ic{
    width:28px;height:28px;border-radius:50%;
    background:#fff;color:var(--side);
    display:grid;place-items:center;flex:none;
  }
  .side h2 .ic svg{width:15px;height:15px}
  .side ul{list-style:none;font-size:.88rem;display:grid;gap:6px;color:#dcdcdc}
  .side a{color:inherit;text-decoration:none;word-break:break-all}
  .side a:hover,.side a:focus-visible{text-decoration:underline}

  .edu-item{margin-bottom:12px}
  .edu-item strong{display:block;font-size:.92rem;color:#fff;line-height:1.4}
  .edu-item span{font-size:.82rem;color:#cfcfcf}

  /* ---------- Main ---------- */
  .main{padding:48px 44px 48px 40px}
  .name{
    font-size:2.6rem;font-weight:800;line-height:1.15;
    letter-spacing:.01em;
  }
  .title{
    margin-top:6px;
    font-size:1.05rem;font-weight:400;color:var(--muted);
    letter-spacing:.04em;
  }
  .rule{height:2px;background:var(--ink);width:64px;margin:20px 0 8px}

  section{margin-top:30px}
  section h2{
    display:flex;align-items:center;gap:10px;
    font-size:1.1rem;font-weight:700;
    padding-bottom:8px;border-bottom:1px solid var(--line);
    margin-bottom:14px;
  }
  section h2 .ic{
    width:30px;height:30px;border-radius:50%;
    background:var(--ink);color:#fff;
    display:grid;place-items:center;flex:none;
  }
  section h2 .ic svg{width:16px;height:16px}
  section p{font-size:.98rem;color:#444;max-width:60ch}

  .chips{display:flex;flex-wrap:wrap;gap:10px;list-style:none}
  .chips li{
    background:var(--ink);color:#fff;
    padding:6px 16px;border-radius:999px;
    font-size:.9rem;font-weight:600;
  }
  .chips.light li{background:#f0f0f0;color:var(--ink);border:1px solid var(--line);font-weight:400}

  .actions{margin-top:36px;display:flex;flex-wrap:wrap;gap:12px}
  .btn{
    display:inline-block;padding:10px 22px;border-radius:6px;
    background:var(--ink);color:#fff;text-decoration:none;
    font-weight:600;font-size:.95rem;border:2px solid var(--ink);
  }
  .btn.ghost{background:transparent;color:var(--ink)}
  .btn:hover,.btn:focus-visible{opacity:.85}
  :focus-visible{outline:3px solid #0a66c2;outline-offset:2px}

  footer{
    max-width:980px;margin:16px auto 0;text-align:center;
    font-size:.8rem;color:var(--muted);
  }

  /* ---------- Responsive ---------- */
  @media (max-width:760px){
    body{padding:0}
    .page{grid-template-columns:1fr;min-height:0}
    .side{margin:0;padding:32px 24px}
    .photo{box-shadow:none;outline:none;border-width:6px}
    .main{padding:32px 24px}
    .name{font-size:2rem}
  }
  @media print{
    body{background:#fff;padding:0}
    .page{box-shadow:none}
    .actions,footer{display:none}
    *{-webkit-print-color-adjust:exact;print-color-adjust:exact}
  }
</style>
</head>
<body>

<div class="page">

  <!-- ===== Sidebar ===== -->
  <aside class="side">
    <div class="photo">
      <img src="photo.jpg" alt="รูปถ่ายของเกียรติศักดิ์ ฤทธิมาร">
    </div>

    <div>
      <h2>
        <span class="ic" aria-hidden="true"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M12 12a5 5 0 1 0 0-10 5 5 0 0 0 0 10Zm0 2c-4 0-8 2-8 5v3h16v-3c0-3-4-5-8-5Z"/></svg></span>
        ติดต่อ
      </h2>
      <ul>
        <li>📞 <a href="tel:0832104415">083-210-4415</a></li>
        <li>✉️ <a href="mailto:kiadtisak.ritt@bumail.net">kiadtisak.ritt@bumail.net</a></li>
      </ul>
    </div>

    <div>
      <h2>
        <span class="ic" aria-hidden="true"><svg viewBox="0 0 24 24" fill="currentColor"><path d="m12 3 11 5-11 5L1 8l11-5Zm-6 9.5 6 2.7 6-2.7V16c0 1.700-2.700 3-6 3s-6-1.300-6-3v-3.500Z"/></svg></span>
        การศึกษา
      </h2>
      <div class="edu-item">
        <strong>โรงเรียนวัดพุทธบูชา</strong>
        <span>มัธยมศึกษา</span>
      </div>
      <div class="edu-item">
        <strong>โรงเรียนบางมด (ตันเปาว์วิทยาคาร)</strong>
        <span>ประถมศึกษา</span>
      </div>
    </div>
  </aside>

  <!-- ===== Main ===== -->
  <main class="main">
    <header>
      <h1 class="name">เกียรติศักดิ์ ฤทธิมาร</h1>
      <p class="title">IT Solution Consultant / IT Manager</p>
      <div class="rule"></div>
    </header>

    <section id="about">
      <h2>
        <span class="ic" aria-hidden="true"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M12 12a5 5 0 1 0 0-10 5 5 0 0 0 0 10Zm0 2c-4 0-8 2-8 5v3h16v-3c0-3-4-5-8-5Z"/></svg></span>
        เกี่ยวกับฉัน
      </h2>
      <p>ชอบความท้าทาย อยากลองสิ่งที่ไม่เคยทำ</p>
    </section>

    <section id="skills">
      <h2>
        <span class="ic" aria-hidden="true"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M9.400 16.600 4.800 12l4.600-4.600L8 6l-6 6 6 6 1.400-1.400Zm5.200 0L19.200 12l-4.600-4.600L16 6l6 6-6 6-1.400-1.400Z"/></svg></span>
        ทักษะ
      </h2>
      <ul class="chips">
        <li>Power BI</li>
        <li>GitHub</li>
        <li>Microsoft PowerPoint</li>
        <li>Microsoft Word</li>
        <li>Google Colab</li>
      </ul>
    </section>

    <section id="language">
      <h2>
        <span class="ic" aria-hidden="true"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M12 2a10 10 0 1 0 0 20 10 10 0 0 0 0-20Zm6.900 6h-3a15.700 15.700 0 0 0-1.400-3.600A8 8 0 0 1 18.900 8ZM12 4c.800 1.200 1.500 2.500 1.900 4h-3.800c.400-1.500 1.100-2.800 1.900-4ZM4.300 14a8.200 8.200 0 0 1 0-4h3.400a16.600 16.600 0 0 0 0 4H4.300Zm.8 2h3a15.700 15.700 0 0 0 1.400 3.600A8 8 0 0 1 5.100 16Zm3-8h-3a8 8 0 0 1 4.400-3.600C8.900 5.600 8.400 6.800 8.100 8ZM12 20c-.800-1.200-1.500-2.500-1.900-4h3.800c-.400 1.500-1.100 2.800-1.900 4Zm2.300-6H9.700a14.700 14.700 0 0 1 0-4h4.600a14.700 14.700 0 0 1 0 4Zm.2 5.600c.600-1.100 1.100-2.300 1.400-3.600h3a8 8 0 0 1-4.400 3.600ZM16.300 14a16.600 16.600 0 0 0 0-4h3.400a8.200 8.200 0 0 1 0 4h-3.400Z"/></svg></span>
        ภาษา
      </h2>
      <ul class="chips light">
        <li>ไทย</li>
        <li>อังกฤษ</li>
      </ul>
    </section>

    <section id="hobbies">
      <h2>
        <span class="ic" aria-hidden="true"><svg viewBox="0 0 24 24" fill="currentColor"><path d="m12 21-1.500-1.300C5.400 15.100 2 12.100 2 8.500 2 5.500 4.400 3 7.500 3c1.700 0 3.400.8 4.500 2.100C13.100 3.800 14.800 3 16.500 3 19.600 3 22 5.500 22 8.500c0 3.600-3.400 6.600-8.500 11.200L12 21Z"/></svg></span>
        งานอดิเรก
      </h2>
      <ul class="chips light">
        <li>ออกกำลังกาย</li>
        <li>หาความรู้</li>
      </ul>
    </section>

    <div class="actions">
      <a class="btn" href="mailto:kiadtisak.ritt@bumail.net">ส่งอีเมลถึงฉัน</a>
      <a class="btn ghost" href="tel:0832104415">โทร 083-210-4415</a>
    </div>
  </main>

</div>

<footer>© เกียรติศักดิ์ ฤทธิมาร</footer>

</body>
</html>
