<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>gmt has</title>

  <!-- SEO (чтобы Google понимал сайт) -->
  <meta name="description" content="gmt has — официальный сайт. Instagram, новости и контакты." />
  <meta name="keywords" content="gmt has, gmthas, gmt, has" />
  <meta name="author" content="gmt has" />

  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, Helvetica, sans-serif; }
    body {
      background: linear-gradient(135deg, #0f172a, #1e293b);
      color: white;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }
    header {
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      font-size: 24px;
      font-weight: 800;
      letter-spacing: 2px;
      text-transform: uppercase;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-weight: 600;
      opacity: 0.85;
      transition: 0.2s;
    }
    nav a:hover { opacity: 1; }

    .hero {
      flex: 1;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 50px 20px;
    }
    .hero h1 {
      font-size: 52px;
      font-weight: 900;
      margin-bottom: 12px;
    }
    .hero p {
      max-width: 650px;
      margin: auto;
      font-size: 18px;
      opacity: 0.85;
      line-height: 1.6;
      margin-bottom: 26px;
    }
    .btns {
      display: flex;
      justify-content: center;
      gap: 15px;
      flex-wrap: wrap;
      margin-bottom: 20px;
    }
    .btn {
      padding: 14px 28px;
      border-radius: 12px;
      border: none;
      font-size: 16px;
      cursor: pointer;
      font-weight: 700;
      transition: 0.2s;
      text-decoration: none;
      display: inline-block;
    }
    .btn-primary {
      background: #3b82f6;
      color: white;
    }
    .btn-primary:hover { transform: translateY(-2px); }
    .btn-outline {
      background: transparent;
      border: 2px solid rgba(255,255,255,0.3);
      color: white;
    }
    .btn-outline:hover { border-color: white; }

    .card-box{
      margin-top: 35px;
      display:flex;
      justify-content:center;
      gap:15px;
      flex-wrap:wrap;
    }
    .card{
      width: 240px;
      padding: 18px;
      border-radius: 16px;
      background: rgba(255,255,255,0.06);
      border: 1px solid rgba(255,255,255,0.12);
      backdrop-filter: blur(10px);
      text-align:left;
    }
    .card h3{ margin-bottom:8px; font-size:18px; }
    .card p{ font-size:14px; opacity:0.8; line-height:1.4; }

    footer {
      text-align: center;
      padding: 20px;
      opacity: 0.6;
      font-size: 14px;
    }

    .insta-box{
      margin-top: 35px;
      display:flex;
      justify-content:center;
    }
    .insta-frame{
      width: 340px;
      max-width: 95%;
      border-radius: 18px;
      overflow: hidden;
      border: 1px solid rgba(255,255,255,0.15);
      background: rgba(255,255,255,0.05);
      padding: 18px;
      text-align: center;
    }
    .insta-frame h2{
      font-size: 20px;
      margin-bottom: 10px;
    }
    .insta-frame p{
      font-size: 14px;
      opacity: 0.8;
      margin-bottom: 12px;
    }
  </style>
</head>
<body>

<header>
  <div class="logo">gmt has</div>
  <nav>
    <a href="#home">Home</a>
    <a href="#instagram">Instagram</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero" id="home">
  <div>
    <h1>gmt has</h1>
    <p>
      Официальный сайт <b>gmt has</b>.  
      Подписывайся на Instagram и следи за новостями.
    </p>

    <!-- ЗАМЕНИ НА СВОЙ ИНСТ -->
    <script>
      const INSTAGRAM_LINK = "https://www.instagram.com/ВАШ_НИК/";
    </script>

    <div class="btns">
      <a class="btn btn-primary" href="#" onclick="window.open(INSTAGRAM_LINK,'_blank')">Instagram</a>
      <a class="btn btn-outline" href="#instagram">Посмотреть ниже</a>
    </div>

    <div class="card-box">
      <div class="card">
        <h3>🔥 Brand</h3>
        <p>gmt has — стиль / богатый вайб / контент.</p>
      </div>
      <div class="card">
        <h3>⚡ Updates</h3>
        <p>Все новые посты и движ — в Instagram.</p>
      </div>
      <div class="card">
        <h3>📱 Contact</h3>
        <p>Связь через Insta Direct.</p>
      </div>
    </div>

    <!-- Instagram блок -->
    <div class="insta-box" id="instagram">
      <div class="insta-frame">
        <h2>Instagram gmt has</h2>
        <p>Нажми на кнопку — откроется профиль</p>
        <a class="btn btn-primary" href="#" onclick="window.open(INSTAGRAM_LINK,'_blank')">Open Instagram</a>
      </div>
    </div>
  </div>
</section>

<footer id="contact">
  © 2026 gmt has — All rights reserved
</footer>

</body>
</html>
