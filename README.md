[deepseek_html_20261014_f3e99b.html](https://github.com/user-attachments/files/33444055/deepseek_html_20261014_f3e99b.html)
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ремонт стиральных машин на дому — Кисловодск и КМВ</title>
<meta name="description" content="Опытный ремонт стиральных машин всех брендов на дому. Более 30 лет опыта. Выезд по Кисловодску и всему региону КМВ. Самые честные цены.">
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }

  :root {
    --primary: #0a6cff;
    --primary-dark: #004dc2;
    --accent: #00d4a0;
    --dark: #0f172a;
    --gray: #64748b;
    --light: #f1f5f9;
    --white: #ffffff;
  }

  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    color: var(--dark);
    line-height: 1.6;
    overflow-x: hidden;
  }

  .container {
    max-width: 1140px;
    margin: 0 auto;
    padding: 0 20px;
  }

  /* Header */
  header {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    background: rgba(255,255,255,0.95);
    backdrop-filter: blur(10px);
    z-index: 1000;
    box-shadow: 0 2px 20px rgba(0,0,0,0.06);
    transition: all 0.3s;
  }

  nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 16px 0;
  }

  .logo {
    font-size: 22px;
    font-weight: 800;
    color: var(--dark);
    text-decoration: none;
    display: flex;
    align-items: center;
    gap: 8px;
  }

  .logo span { color: var(--primary); }

  .nav-links {
    display: flex;
    gap: 32px;
    list-style: none;
  }

  .nav-links a {
    color: var(--dark);
    text-decoration: none;
    font-weight: 500;
    font-size: 15px;
    transition: color 0.2s;
  }

  .nav-links a:hover { color: var(--primary); }

  .phone-btn {
    background: var(--primary);
    color: white;
    padding: 10px 22px;
    border-radius: 50px;
    text-decoration: none;
    font-weight: 600;
    font-size: 15px;
    transition: all 0.2s;
    display: inline-flex;
    align-items: center;
    gap: 6px;
  }

  .phone-btn:hover {
    background: var(--primary-dark);
    transform: translateY(-1px);
  }

  .burger {
    display: none;
    background: none;
    border: none;
    font-size: 26px;
    cursor: pointer;
    color: var(--dark);
  }

  /* Hero */
  .hero {
    padding: 140px 0 80px;
    background: linear-gradient(135deg, #f0f7ff 0%, #ffffff 100%);
    position: relative;
    overflow: hidden;
  }

  .hero::before {
    content: '';
    position: absolute;
    top: -100px;
    right: -100px;
    width: 500px;
    height: 500px;
    background: radial-gradient(circle, rgba(10,108,255,0.1) 0%, transparent 70%);
    border-radius: 50%;
  }

  .hero-grid {
    display: grid;
    grid-template-columns: 1.1fr 0.9fr;
    gap: 60px;
    align-items: center;
    position: relative;
    z-index: 1;
  }

  .hero-badge {
    display: inline-block;
    background: rgba(10,108,255,0.1);
    color: var(--primary);
    padding: 6px 16px;
    border-radius: 50px;
    font-size: 14px;
    font-weight: 600;
    margin-bottom: 20px;
  }

  .hero h1 {
    font-size: 52px;
    line-height: 1.1;
    font-weight: 800;
    margin-bottom: 24px;
    letter-spacing: -1px;
  }

  .hero h1 span { color: var(--primary); }

  .hero p {
    font-size: 18px;
    color: var(--gray);
    margin-bottom: 32px;
    max-width: 500px;
  }

  .hero-buttons {
    display: flex;
    gap: 16px;
    flex-wrap: wrap;
  }

  .btn {
    padding: 16px 32px;
    border-radius: 50px;
    font-weight: 600;
    font-size: 16px;
    text-decoration: none;
    display: inline-flex;
    align-items: center;
    gap: 10px;
    transition: all 0.25s;
    border: none;
    cursor: pointer;
    font-family: inherit;
  }

  .btn-primary {
    background: var(--primary);
    color: white;
    box-shadow: 0 10px 30px rgba(10,108,255,0.3);
  }

  .btn-primary:hover {
    background: var(--primary-dark);
    transform: translateY(-2px);
    box-shadow: 0 15px 35px rgba(10,108,255,0.4);
  }

  .btn-outline {
    background: white;
    color: var(--dark);
    border: 2px solid #e2e8f0;
  }

  .btn-outline:hover {
    border-color: var(--primary);
    color: var(--primary);
  }

  .hero-stats {
    display: flex;
    gap: 40px;
    margin-top: 48px;
    padding-top: 32px;
    border-top: 1px solid #e2e8f0;
  }

  .stat-number {
    font-size: 32px;
    font-weight: 800;
    color: var(--primary);
    line-height: 1;
  }

  .stat-label {
    font-size: 14px;
    color: var(--gray);
    margin-top: 6px;
  }

  .hero-visual {
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
  }

  .hero-card {
    background: white;
    border-radius: 24px;
    padding: 32px;
    box-shadow: 0 30px 60px rgba(15,23,42,0.15);
    width: 100%;
    max-width: 380px;
  }

  .hero-card-title {
    font-size: 18px;
    font-weight: 700;
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    gap: 10px;
  }

  .machine-icon {
    width: 46px;
    height: 46px;
    background: var(--primary);
    color: white;
    border-radius: 12px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 22px;
  }

  .feature-item {
    display: flex;
    align-items: center;
    gap: 12px;
    padding: 12px 0;
    border-bottom: 1px solid #f1f5f9;
    font-size: 15px;
  }

  .feature-item:last-child { border-bottom: none; }

  .check {
    width: 24px;
    height: 24px;
    background: var(--accent);
    color: white;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 14px;
    font-weight: bold;
    flex-shrink: 0;
  }

  /* Sections */
  section { padding: 90px 0; }

  .section-title {
    text-align: center;
    margin-bottom: 60px;
  }

  .section-title h2 {
    font-size: 40px;
    font-weight: 800;
    margin-bottom: 12px;
    letter-spacing: -0.5px;
  }

  .section-title p {
    color: var(--gray);
    font-size: 17px;
    max-width: 600px;
    margin: 0 auto;
  }

  /* Services */
  .services { background: var(--light); }

  .services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 24px;
  }

  .service-card {
    background: white;
    padding: 32px 28px;
    border-radius: 20px;
    transition: all 0.3s;
    border: 2px solid transparent;
  }

  .service-card:hover {
    transform: translateY(-6px);
    border-color: var(--primary);
    box-shadow: 0 20px 40px rgba(10,108,255,0.1);
  }

  .service-icon {
    width: 56px;
    height: 56px;
    background: linear-gradient(135deg, var(--primary), #4d9bff);
    border-radius: 16px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 26px;
    margin-bottom: 20px;
  }

  .service-card h3 {
    font-size: 19px;
    margin-bottom: 10px;
    font-weight: 700;
  }

  .service-card p {
    color: var(--gray);
    font-size: 15px;
    margin-bottom: 16px;
  }

  .price {
    font-size: 18px;
    font-weight: 800;
    color: var(--primary);
  }

  /* Brands */
  .brands-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
    gap: 16px;
  }

  .brand-item {
    background: white;
    padding: 24px 12px;
    text-align: center;
    border-radius: 14px;
    font-weight: 700;
    color: var(--dark);
    border: 2px solid var(--light);
    transition: all 0.25s;
    font-size: 16px;
  }

  .brand-item:hover {
    border-color: var(--primary);
    color: var(--primary);
    transform: translateY(-3px);
  }

  /* Why us */
  .why { background: var(--dark); color: white; }

  .why .section-title h2 { color: white; }
  .why .section-title p { color: #94a3b8; }

  .why-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 24px;
  }

  .why-card {
    background: rgba(255,255,255,0.05);
    padding: 32px 28px;
    border-radius: 20px;
    border: 1px solid rgba(255,255,255,0.1);
    transition: all 0.3s;
  }

  .why-card:hover {
    background: rgba(255,255,255,0.08);
    border-color: var(--primary);
  }

  .why-number {
    font-size: 36px;
    font-weight: 800;
    color: var(--accent);
    line-height: 1;
    margin-bottom: 16px;
  }

  .why-card h3 {
    font-size: 19px;
    margin-bottom: 10px;
  }

  .why-card p {
    color: #94a3b8;
    font-size: 15px;
  }

  /* Steps */
  .steps-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 24px;
  }

  .step {
    text-align: center;
    position: relative;
  }

  .step-circle {
    width: 70px;
    height: 70px;
    background: white;
    border: 3px solid var(--primary);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 26px;
    font-weight: 800;
    color: var(--primary);
    margin: 0 auto 20px;
  }

  .step h3 {
    font-size: 18px;
    margin-bottom: 8px;
  }

  .step p {
    color: var(--gray);
    font-size: 15px;
  }

  /* Gallery — До и После */
  .gallery { background: var(--light); }

  .gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    gap: 32px;
  }

  .gallery-item {
    background: white;
    border-radius: 20px;
    overflow: hidden;
    box-shadow: 0 10px 30px rgba(15,23,42,0.08);
    transition: transform 0.3s;
  }

  .gallery-item:hover { transform: translateY(-4px); }

  .gallery-pair {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 2px;
    background: #e2e8f0;
  }

  .gallery-photo {
    position: relative;
    aspect-ratio: 4/3;
    overflow: hidden;
  }

  .gallery-photo img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
    transition: transform 0.4s;
  }

  .gallery-photo:hover img { transform: scale(1.05); }

  .gallery-label {
    position: absolute;
    top: 12px;
    left: 12px;
    padding: 4px 12px;
    border-radius: 50px;
    font-size: 12px;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }

  .gallery-label.before {
    background: rgba(239,68,68,0.9);
    color: white;
  }

  .gallery-label.after {
    background: rgba(0,212,160,0.9);
    color: white;
  }

  .gallery-caption {
    padding: 20px 24px;
  }

  .gallery-caption h3 {
    font-size: 17px;
    margin-bottom: 4px;
  }

  .gallery-caption p {
    color: var(--gray);
    font-size: 14px;
  }

  /* CTA */
  .cta {
    background: linear-gradient(135deg, var(--primary) 0%, #4d9bff 100%);
    color: white;
    text-align: center;
    padding: 80px 0;
  }

  .cta h2 {
    font-size: 38px;
    font-weight: 800;
    margin-bottom: 16px;
  }

  .cta p {
    font-size: 18px;
    opacity: 0.9;
    margin-bottom: 32px;
    max-width: 600px;
    margin-left: auto;
    margin-right: auto;
  }

  .cta-buttons {
    display: flex;
    gap: 16px;
    justify-content: center;
    flex-wrap: wrap;
  }

  .btn-white {
    background: white;
    color: var(--primary);
    box-shadow: 0 10px 30px rgba(0,0,0,0.15);
  }

  .btn-white:hover {
    transform: translateY(-2px);
    box-shadow: 0 15px 40px rgba(0,0,0,0.2);
  }

  /* Contact info */
  .contacts-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 24px;
    margin-bottom: 48px;
  }

  .contact-card {
    background: white;
    padding: 32px;
    border-radius: 20px;
    text-align: center;
    border: 1px solid #e2e8f0;
    transition: all 0.25s;
  }

  .contact-card:hover {
    border-color: var(--primary);
    transform: translateY(-4px);
    box-shadow: 0 15px 35px rgba(10,108,255,0.1);
  }

  .contact-icon {
    font-size: 32px;
    margin-bottom: 16px;
  }

  .contact-card h3 {
    font-size: 16px;
    color: var(--gray);
    font-weight: 500;
    margin-bottom: 8px;
  }

  .contact-value {
    font-size: 20px;
    font-weight: 700;
    color: var(--dark);
    text-decoration: none;
    display: block;
    margin-bottom: 4px;
  }

  .contact-value:hover { color: var(--primary); }

  /* Footer */
  footer {
    background: var(--dark);
    color: #94a3b8;
    padding: 40px 0;
    text-align: center;
    font-size: 14px;
  }

  footer a { color: var(--primary); text-decoration: none; }

  /* Floating call button */
  .float-call {
    position: fixed;
    bottom: 24px;
    right: 24px;
    width: 60px;
    height: 60px;
    background: var(--primary);
    color: white;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 26px;
    box-shadow: 0 10px 30px rgba(10,108,255,0.5);
    text-decoration: none;
    z-index: 999;
    animation: pulse 2s infinite;
    transition: transform 0.25s;
  }

  .float-call:hover { transform: scale(1.1); }

  @keyframes pulse {
    0%, 100% { box-shadow: 0 10px 30px rgba(10,108,255,0.5); }
    50% { box-shadow: 0 10px 40px rgba(10,108,255,0.8), 0 0 0 12px rgba(10,108,255,0.1); }
  }

  /* Responsive */
  @media (max-width: 900px) {
    .hero-grid { grid-template-columns: 1fr; gap: 40px; }
    .hero h1 { font-size: 38px; }
    .hero-visual { order: -1; }
    .section-title h2 { font-size: 30px; }
    .cta h2 { font-size: 28px; }
  }

  @media (max-width: 700px) {
    .nav-links { display: none; }
    .burger { display: block; }
    .nav-links.open {
      display: flex;
      flex-direction: column;
      position: absolute;
      top: 100%;
      left: 0;
      right: 0;
      background: white;
      padding: 20px;
      gap: 16px;
      box-shadow: 0 20px 40px rgba(0,0,0,0.1);
    }
    .phone-btn { padding: 8px 16px; font-size: 14px; }
    .hero { padding: 110px 0 60px; }
    .hero h1 { font-size: 30px; }
    .hero p { font-size: 16px; }
    .hero-stats { gap: 24px; }
    .stat-number { font-size: 26px; }
    section { padding: 60px 0; }
    .btn { padding: 14px 24px; font-size: 15px; }
  }
</style>
</head>
<body>

<!-- Header -->
<header>
  <div class="container">
    <nav>
      <a href="#" class="logo">
        <span>⚙</span> РемонтСтир<span>.</span>
      </a>
      <ul class="nav-links" id="navLinks">
        <li><a href="#services">Услуги</a></li>
        <li><a href="#brands">Бренды</a></li>
        <li><a href="#gallery">До / После</a></li>
        <li><a href="#why">Почему я</a></li>
        <li><a href="#contact">Контакты</a></li>
      </ul>
      <a href="tel:+79289707084" class="phone-btn">📞 +7 928 970-70-84</a>
      <button class="burger" id="burger" aria-label="Меню">☰</button>
    </nav>
  </div>
</header>

<!-- Hero -->
<section class="hero">
  <div class="container">
    <div class="hero-grid">
      <div>
        <span class="hero-badge">🚀 Выезд в день обращения</span>
        <h1>Ремонт стиральных машин <span>на дому</span></h1>
        <p>Опыт более 30 лет, свыше тысячи успешных ремонтов. Работаю по Кисловодску и всему региону КМВ. Самые честные цены в регионе.</p>
        <div class="hero-buttons">
          <a href="tel:+79289707084" class="btn btn-primary">📞 Позвонить</a>
          <a href="#services" class="btn btn-outline">Узнать цены</a>
        </div>
        <div class="hero-stats">
          <div>
            <div class="stat-number">30+</div>
            <div class="stat-label">лет опыта</div>
          </div>
          <div>
            <div class="stat-number">1000+</div>
            <div class="stat-label">ремонтов</div>
          </div>
          <div>
            <div class="stat-number">Гарантия</div>
            <div class="stat-label">на объём работ</div>
          </div>
        </div>
      </div>
      <div class="hero-visual">
        <div class="hero-card">
          <div class="hero-card-title">
            <div class="machine-icon">🧺</div>
            <div>Что вы получаете</div>
          </div>
          <div class="feature-item"><div class="check">✓</div> Диагностика бесплатно</div>
          <div class="feature-item"><div class="check">✓</div> Оригинальные запчасти</div>
          <div class="feature-item"><div class="check">✓</div> Ремонт за 1 визит</div>
          <div class="feature-item"><div class="check">✓</div> Гарантия на работы</div>
          <div class="feature-item"><div class="check">✓</div> Оплата после ремонта</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Services -->
<section class="services" id="services">
  <div class="container">
    <div class="section-title">
      <h2>Услуги и цены</h2>
      <p>Точная стоимость известна после бесплатной диагностики. Работаю без скрытых доплат. Самые честные цены в регионе КМВ.</p>
    </div>
    <div class="services-grid">
      <div class="service-card">
        <div class="service-icon">💧</div>
        <h3>Не сливает воду</h3>
        <p>Чистка и замена сливного насоса, устранение засоров в патрубках.</p>
        <div class="price">Цена по диагностике</div>
      </div>
      <div class="service-card">
        <div class="service-icon">🔄</div>
        <h3>Не отжимает</h3>
        <p>Замена ремня, подшипников, ремонт двигателя и электроники.</p>
        <div class="price">Цена по диагностике</div>
      </div>
      <div class="service-card">
        <div class="service-icon">🚪</div>
        <h3>Не открывается дверца</h3>
        <p>Ремонт замка блокировки люка (УБЛ), замена ручки.</p>
        <div class="price">Цена по диагностике</div>
      </div>
      <div class="service-card">
        <div class="service-icon">⚡</div>
        <h3>Не включается</h3>
        <p>Ремонт платы управления, замена сетевого фильтра, проводки.</p>
        <div class="price">Цена по диагностике</div>
      </div>
      <div class="service-card">
        <div class="service-icon">💦</div>
        <h3>Протекает вода</h3>
        <p>Замена манжеты люка, уплотнителей, шлангов, устранение течей.</p>
        <div class="price">Цена по диагностике</div>
      </div>
      <div class="service-card">
        <div class="service-icon">🔊</div>
        <h3>Шумит при отжиме</h3>
        <p>Замена подшипников, балансировка барабана, ремонт бака.</p>
        <div class="price">Цена по диагностике</div>
      </div>
    </div>
  </div>
</section>

<!-- Brands -->
<section id="brands">
  <div class="container">
    <div class="section-title">
      <h2>Ремонтирую все марки</h2>
      <p>Работаю с популярными брендами и редкими моделями</p>
    </div>
    <div class="brands-grid">
      <div class="brand-item">Samsung</div>
      <div class="brand-item">LG</div>
      <div class="brand-item">Bosch</div>
      <div class="brand-item">Indesit</div>
      <div class="brand-item">Ariston</div>
      <div class="brand-item">Electrolux</div>
      <div class="brand-item">Whirlpool</div>
      <div class="brand-item">Candy</div>
      <div class="brand-item">Siemens</div>
      <div class="brand-item">Beko</div>
      <div class="brand-item">Haier</div>
      <div class="brand-item">Atlant</div>
    </div>
  </div>
</section>

<!-- Gallery — До и После -->
<section class="gallery" id="gallery">
  <div class="container">
    <div class="section-title">
      <h2>Фото до и после ремонта</h2>
      <p>Реальные примеры выполненных работ</p>
    </div>
    <div class="gallery-grid">
      <div class="gallery-item">
        <div class="gallery-pair">
          <div class="gallery-photo">
            <span class="gallery-label before">До</span>
            <img src="https://elektroniker.help/wp-content/uploads/2025/10/beko-wml61433nps1-plata-upravleniya-do-remonta.jpg" alt="Плата управления до ремонта" loading="lazy">
          </div>
          <div class="gallery-photo">
            <span class="gallery-label after">После</span>
            <img src="https://elektroniker.help/wp-content/uploads/2025/10/beko-wml61433nps1-plata-upravleniya-posle-remonta.jpg" alt="Плата управления после ремонта" loading="lazy">
          </div>
        </div>
        <div class="gallery-caption">
          <h3>Замена платы управления</h3>
          <p>BEKO WML61433NPS1 — восстановление работоспособности</p>
        </div>
      </div>

      <div class="gallery-item">
        <div class="gallery-pair">
          <div class="gallery-photo">
            <span class="gallery-label before">До</span>
            <img src="https://pro100del.ru/upload/iblock/ten-bosch-do.jpg" alt="ТЭН до замены" loading="lazy">
          </div>
          <div class="gallery-photo">
            <span class="gallery-label after">После</span>
            <img src="https://pro100del.ru/upload/iblock/ten-bosch-posle.jpg" alt="ТЭН после замены" loading="lazy">
          </div>
        </div>
        <div class="gallery-caption">
          <h3>Замена ТЭНа</h3>
          <p>Bosch — устранение протечки и замена нагревательного элемента</p>
        </div>
      </div>

      <div class="gallery-item">
        <div class="gallery-pair">
          <div class="gallery-photo">
            <span class="gallery-label before">До</span>
            <img src="https://peling.ru/wp-content/uploads/2026/05/atlant-do-remonta.jpg" alt="Стиральная машина Атлант до ремонта" loading="lazy">
          </div>
          <div class="gallery-photo">
            <span class="gallery-label after">После</span>
            <img src="https://peling.ru/wp-content/uploads/2026/05/atlant-posle-remonta.jpg" alt="Стиральная машина Атлант после ремонта" loading="lazy">
          </div>
        </div>
        <div class="gallery-caption">
          <h3>Ремонт двигателя и насоса</h3>
          <p>Атлант — восстановление после заклинивания мотора</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Why us -->
<section class="why" id="why">
  <div class="container">
    <div class="section-title">
      <h2>Почему выбирают меня</h2>
      <p>Более тысячи довольных клиентов за 30 лет работы</p>
    </div>
    <div class="why-grid">
      <div class="why-card">
        <div class="why-number">01</div>
        <h3>Опыт более 30 лет</h3>
        <p>Знаю устройство любой стиральной машины и быстро нахожу причину поломки.</p>
      </div>
      <div class="why-card">
        <div class="why-number">02</div>
        <h3>Ремонт на дому</h3>
        <p>Приезжаю со всем необходимым. Большинство ремонтов делаю за один визит.</p>
      </div>
      <div class="why-card">
        <div class="why-number">03</div>
        <h3>Гарантия на работы</h3>
        <p>Даю гарантию на проделанный объём работ. Если что-то пойдёт не так — приеду бесплатно.</p>
      </div>
      <div class="why-card">
        <div class="why-number">04</div>
        <h3>Честные цены</h3>
        <p>Самые честные цены в регионе КМВ. Называю стоимость до ремонта, без накруток.</p>
      </div>
    </div>
  </div>
</section>

<!-- Steps -->
<section>
  <div class="container">
    <div class="section-title">
      <h2>Как я работаю</h2>
      <p>Простой процесс от звонка до готовой машины</p>
    </div>
    <div class="steps-grid">
      <div class="step">
        <div class="step-circle">1</div>
        <h3>Звонок</h3>
        <p>Опишите проблему, согласуем время визита</p>
      </div>
      <div class="step">
        <div class="step-circle">2</div>
        <h3>Диагностика</h3>
        <p>Приезжаю и бесплатно определяю причину</p>
      </div>
      <div class="step">
        <div class="step-circle">3</div>
        <h3>Ремонт</h3>
        <p>Чиню на месте, называю точную цену заранее</p>
      </div>
      <div class="step">
        <div class="step-circle">4</div>
        <h3>Гарантия</h3>
        <p>Выдаю гарантийный талон, оплата после ремонта</p>
      </div>
    </div>
  </div>
</section>

<!-- CTA -->
<section class="cta">
  <div class="container">
    <h2>Машинка сломалась прямо сейчас?</h2>
    <p>Позвоните — отвечу сразу и приеду в удобное время. Работаю ежедневно с 8:00 до 22:00.</p>
    <div class="cta-buttons">
      <a href="tel:+79289707084" class="btn btn-white">📞 +7 928 970-70-84</a>
      <a href="tel:+79289824492" class="btn btn-outline" style="border-color:white;color:white;background:transparent;">📞 +7 928 982-44-92</a>
    </div>
  </div>
</section>

<!-- Contacts -->
<section id="contact">
  <div class="container">
    <div class="section-title">
      <h2>Свяжитесь со мной</h2>
      <p>Позвоните — отвечу сразу и приеду в удобное время</p>
    </div>

    <div class="contacts-grid">
      <div class="contact-card">
        <div class="contact-icon">📞</div>
        <h3>Телефон 1</h3>
        <a href="tel:+79289707084" class="contact-value">+7 928 970-70-84</a>
      </div>
      <div class="contact-card">
        <div class="contact-icon">📞</div>
        <h3>Телефон 2</h3>
        <a href="tel:+79289824492" class="contact-value">+7 928 982-44-92</a>
      </div>
      <div class="contact-card">
        <div class="contact-icon">🕐</div>
        <h3>Работаю</h3>
        <div class="contact-value" style="font-size:16px;">Ежедневно 8:00 – 22:00</div>
      </div>
      <div class="contact-card">
        <div class="contact-icon">📍</div>
        <h3>Выезд</h3>
        <div class="contact-value" style="font-size:16px;">Кисловодск и весь регион КМВ</div>
      </div>
    </div>
  </div>
</section>

<!-- Footer -->
<footer>
  <div class="container">
    <p>© 2025 Ремонт стиральных машин — Кисловодск и КМВ. Все права защищены.</p>
    <p style="margin-top:8px;">📞 <a href="tel:+79289707084">+7 928 970-70-84</a> · <a href="tel:+79289824492">+7 928 982-44-92</a></p>
  </div>
</footer>

<!-- Floating call button -->
<a href="tel:+79289707084" class="float-call" aria-label="Позвонить">📞</a>

<script>
  // Burger menu
  const burger = document.getElementById('burger');
  const navLinks = document.getElementById('navLinks');
  burger.addEventListener('click', () => {
    navLinks.classList.toggle('open');
  });

  // Smooth scroll + close menu
  document.querySelectorAll('a[href^="#"]').forEach(link => {
    link.addEventListener('click', e => {
      const target = document.querySelector(link.getAttribute('href'));
      if (target) {
        e.preventDefault();
        navLinks.classList.remove('open');
        window.scrollTo({ top: target.offsetTop - 80, behavior: 'smooth' });
      }
    });
  });
</script>

</body>
</html>
