<!DOCTYPE html>
<meta http-equiv="Content-Security-Policy" content="default-src *; img-src * data: blob:;">
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Real Estate - Esteban Tena</title>
  <meta name="description" content="Servicios inmobiliarios en New Jersey. Encuentra tu vivienda ideal con Esteban Tena, asesor experto.">
  <meta name="keywords" content="inmobiliaria, real estate, casas, apartamentos, New Jersey, Esteban Tena">
  <!-- Favicon con tu logo -->
  <link rel="icon" href="logo1.png" type="image/png">
  <link href="https://fonts.googleapis.com/css?family=Poppins:400,600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
  <style>
    /* ... Todo tu CSS optimizado actual ... */
    .navbar-space { height: 64px; }
    nav .logo img { height: 38px; width: 38px; border-radius: 7px; object-fit: cover; }
    header img.foto-personal { max-width: 140px; border-radius: 10px; margin-right: 32px; box-shadow: 0 3px 12px rgba(0,0,0,0.11); }
    .banner-flyer { display: flex; justify-content: center; align-items: center; background: #fffbe6; padding: 18px 0 15px 0; }
    .banner-flyer img { max-width: 350px; width: 100%; border-radius: 13px; box-shadow: 0 2px 10px rgba(0,0,0,0.12);}
    @media (max-width: 600px) {
      header img.foto-personal { margin-right: 0; margin-bottom: 15px; max-width: 80vw;}
      .banner-flyer img { max-width: 98vw; }
    }
    /* ... Resto del CSS optimizado ... */
  </style>
</head>
<body>
  <!-- NAVBAR -->
  <nav class="navbar" role="navigation" aria-label="Menú principal">
    <a class="logo" href="#top">
      <img src="logo1.png" alt="Logo Realty One Group Portfolio">
      Esteban Tena
    </a>
    <div class="links">
      <a href="#propiedades" class="active" aria-current="page">Propiedades</a>
      <a href="#testimonios">Testimonios</a>
      <a href="#contacto">Contacto</a>
    </div>
    <div class="socials">
      <a href="https://wa.me/18624065471" target="_blank" aria-label="Contactar por WhatsApp"><i class="fab fa-whatsapp"></i></a>
      <a href="https://instagram.com/esteban_njrealtor" target="_blank" aria-label="Instagram de Esteban Tena"><i class="fab fa-instagram"></i></a>
    </div>
  </nav>
  <div class="navbar-space"></div>
  <!-- PORTADA PRINCIPAL CON FOTO PERSONAL -->
  <header id="top" role="banner">
    <img src="foto3.png" class="foto-personal" alt="Esteban Tena - Asesor inmobiliario">
    <div class="info">
      <h1>Dedica menos tiempo buscando vivienda,<br>permíteme hacerlo por ti.</h1>
      <p><strong>Real Estate:</strong> Esteban Tena</p>
      <p><strong>📞 862-406-5471</strong></p>
      <div class="contacto">
        <a href="tel:8624065471" aria-label="Llamar ahora por teléfono"><i class="fa fa-phone"></i> LLAMA AHORA</a>
        <a href="https://wa.me/18624065471" target="_blank" aria-label="Contactar por WhatsApp"><i class="fab fa-whatsapp"></i> WHATSAPP</a>
        <button class="toggle-darkmode" id="darkmodeBtn" aria-label="Cambiar entre modo oscuro y claro">🌙 Modo oscuro</button>
      </div>
    </div>
  </header>
  <!-- FLYER INFORMATIVO DESTACADO -->
  <div class="banner-flyer" role="region" aria-label="Información de contacto y servicios">
    <img src="flyer2.png" alt="Flyer con información de contacto y servicios de Esteban Tena" loading="lazy">
  </div>
  <!-- ... Resto del contenido de tu web ... -->
</body>
</html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Real Estate - Esteban Tena</title>
  <meta name="description" content="Servicios inmobiliarios en New Jersey. Encuentra tu vivienda ideal con Esteban Tena, asesor experto.">
  <meta name="keywords" content="inmobiliaria, real estate, casas, apartamentos, New Jersey, Esteban Tena">
  <link rel="icon" href="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/72x72/1f3e0.png" type="image/png">
  <link href="https://fonts.googleapis.com/css?family=Poppins:400,600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
  <style>
    :root {
      --color-bg: #f9f9f9;
      --color-text: #333;
      --color-header: #0d1b2a;
      --color-accent: #d97a3a;
      --color-accent-hover: #b55e29;
      --color-card-bg: #fff;
      --color-footer: #0d1b2a;
      --color-navbar: #fff;
      --color-navbar-bg: rgba(13, 27, 42, 0.96);
      --color-navbar-link: #fff;
      --color-navbar-link-active: #d97a3a;
    }
    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      margin: 0;
      font-family: 'Poppins', Arial, sans-serif;
      color: var(--color-text);
      background-color: var(--color-bg);
      transition: background 0.3s, color 0.3s;
    }
    nav.navbar {
      position: fixed;
      top: 0;
      width: 100vw;
      background: var(--color-navbar-bg);
      color: var(--color-navbar-link);
      z-index: 999;
      box-shadow: 0 2px 10px rgba(0,0,0,0.08);
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 0 40px;
      height: 64px;
      transition: background 0.3s;
    }
    nav .logo {
      display: flex;
      align-items: center;
      gap: 10px;
      font-weight: 600;
      font-size: 1.2rem;
      letter-spacing: 1px;
    }
    nav .logo img {
      height: 38px;
      width: 38px;
      border-radius: 7px;
      object-fit: cover;
    }
    nav .links {
      display: flex;
      gap: 26px;
    }
    nav .links a {
      color: var(--color-navbar-link);
      text-decoration: none;
      font-weight: 500;
      padding: 7px 10px;
      border-radius: 4px;
      transition: background 0.25s, color 0.25s;
    }
    nav .links a.active,
    nav .links a:hover {
      color: var(--color-navbar-link-active);
      background: rgba(255,255,255,0.10);
    }
    nav .socials {
      display: flex;
      gap: 14px;
    }
    nav .socials a {
      color: var(--color-navbar-link);
      font-size: 1.18em;
      transition: color 0.25s;
    }
    nav .socials a:hover {
      color: var(--color-navbar-link-active);
    }
    @media (max-width: 800px) {
      nav.navbar { flex-direction: column; align-items: flex-start; height: auto; padding: 10px 16px;}
      nav .links { flex-direction: column; gap: 10px; margin-top: 7px;}
      nav .socials { margin-top: 8px;}
    }
    .navbar-space { height: 64px; }
    header {
      background-color: var(--color-header);
      color: white;
      padding: 50px 20px 30px 20px;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-wrap: wrap;
      gap: 32px;
      min-height: 260px;
      margin-bottom: 0px;
      box-shadow: 0 2px 18px rgba(0,0,0,0.07);
    }
    header img {
      max-width: 180px;
      border-radius: 10px;
      margin-right: 0;
      box-shadow: 0 3px 12px rgba(0,0,0,0.11);
    }
    header .info {
      max-width: 600px;
    }
    header h1 {
      font-size: 2.2rem;
      margin-bottom: 10px;
      color: #fff;
      letter-spacing: 1.2px;
      line-height: 1.25;
      text-shadow: 0 1px 3px rgba(0,0,0,0.08);
      animation: fadeInDown 1.2s;
    }
    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-30px);}
      to { opacity: 1; transform: translateY(0);}
    }
    header p {
      font-size: 1.1rem;
      margin-bottom: 18px;
      line-height: 1.5;
    }
    .contacto {
      margin-top: 18px;
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
    }
    .contacto a, .toggle-darkmode {
      display: inline-block;
      background-color: var(--color-accent);
      color: white;
      padding: 10px 18px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 6px;
      border: none;
      transition: background 0.3s, color 0.3s, box-shadow 0.3s;
      font-size: 1rem;
      cursor: pointer;
      box-shadow: 0 2px 8px rgba(0,0,0,0.07);
    }
    .contacto a:hover, .toggle-darkmode:hover {
      background-color: var(--color-accent-hover);
      color: #fff;
      box-shadow: 0 3px 14px rgba(0,0,0,0.09);
    }
    .toggle-darkmode { margin-left: 0; background: none; border: 2px solid #fff; color: #fff;}
    .toggle-darkmode:hover { background: #fff; color: #0d1b2a; border-color: #d97a3a; }
    /* SECCIÓN ACCIONES LINKTREE */
    #acciones {
      background: linear-gradient(90deg,#f9f9f9 65%,#f3f6fa 100%);
      padding: 45px 10px 30px 10px;
      text-align: center;
    }
    #acciones h2 {
      color: #0d1b2a;
      font-size: 2rem;
      margin-bottom: 34px;
      letter-spacing: 1px;
    }
    .acciones-cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 32px;
      max-width: 900px;
      margin: 0 auto;
    }
    .acciones-cards a {
      flex: 1 1 220px;
      max-width: 270px;
      background: #fff;
      border-radius: 13px;
      box-shadow: 0 4px 16px rgba(0,0,0,0.09);
      padding: 30px 18px 25px 18px;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-decoration: none;
      color: #222;
      transition: transform 0.18s, box-shadow 0.18s;
      font-size: 1.01em;
    }
    .acciones-cards a:hover {
      transform: translateY(-8px) scale(1.04);
      box-shadow: 0 8px 28px rgba(0,0,0,0.13);
      color: #d97a3a;
    }
    .acciones-cards i {
      margin-bottom: 17px;
    }
    .acciones-cards span {
      text-align: center;
    }
    .acciones-cards .acciones-title {
      font-size: 1.18em;
      font-weight: 600;
      margin-bottom: 7px;
      color: #0d1b2a;
    }
    .acciones-cards .acciones-desc {
      font-size: 0.98em;
      color: #777;
    }
    @media (max-width: 900px) {
      .acciones-cards { gap: 18px; }
      .acciones-cards a { max-width: 95vw; }
    }
    @media (max-width: 700px) {
      .acciones-cards { flex-direction: column; gap: 18px;}
      .acciones-cards a { max-width: 100%; }
    }
    section#propiedades {
      padding: 60px 20px 40px 20px;
      text-align: center;
      background: linear-gradient(180deg, #f9f9f9 75%, #fff 100%);
    }
    section#propiedades h2 {
      font-size: 2.1rem;
      margin-bottom: 30px;
      color: var(--color-header);
      letter-spacing: 1px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 28px;
      margin-bottom: 12px;
    }
    .card {
      background: var(--color-card-bg);
      border-radius: 10px;
      box-shadow: 0 4px 14px rgba(0,0,0,0.12);
      overflow: hidden;
      text-align: left;
      transition: transform 0.22s, box-shadow 0.22s, background 0.3s, color 0.3s;
      cursor: pointer;
      position: relative;
    }
    .card:hover {
      transform: translateY(-7px) scale(1.03);
      box-shadow: 0 8px 24px rgba(0,0,0,0.17);
    }
    .card img {
      width: 100%;
      height: 210px;
      object-fit: cover;
      transition: filter 0.20s;
    }
    .card:hover img {
      filter: brightness(90%) saturate(1.13);
    }
    .card h3 {
      margin: 18px 15px 10px 15px;
      font-size: 1.15rem;
      color: var(--color-header);
      font-weight: 600;
      letter-spacing: 1px;
    }
    .card p {
      margin: 0 15px 15px;
      font-size: 0.99rem;
      color: #555;
      line-height: 1.35;
    }
    #testimonios {
      background: #f3f6fa;
      padding: 50px 20px 35px 20px;
      text-align: center;
    }
    #testimonios h2 {
      font-size: 2rem;
      color: var(--color-header);
      margin-bottom: 30px;
    }
    .testimonios-lista {
      display: flex;
      flex-wrap: wrap;
      gap: 30px;
      justify-content: center;
      align-items: stretch;
    }
    .testimonio {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 14px rgba(0,0,0,0.13);
      padding: 26px 20px 19px 20px;
      max-width: 340px;
      min-width: 220px;
      flex: 1 1 240px;
      display: flex;
      flex-direction: column;
      align-items: center;
      transition: background 0.3s, box-shadow 0.3s;
    }
    .testimonio .avatar {
      width: 56px;
      height: 56px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 13px;
      box-shadow: 0 1px 6px rgba(0,0,0,0.09);
    }
    .testimonio .nombre {
      font-weight: 600;
      margin-bottom: 6px;
      color: #0d1b2a;
    }
    .testimonio .texto {
      font-style: italic;
      font-size: 0.99rem;
      color: #444;
      margin-bottom: 4px;
    }
    .testimonio .estrella {
      color: #d97a3a;
      font-size: 1.1em;
      margin: 0 1.5px;
    }
    #contacto {
      background: linear-gradient(180deg, #fff 70%, #f9f9f9 100%);
      padding: 52px 20px 40px 20px;
      text-align: center;
    }
    #contacto h2 {
      font-size: 2rem;
      color: var(--color-header);
      margin-bottom: 25px;
    }
    .contact-form {
      max-width: 430px;
      margin: 0 auto;
      background: #fff;
      border-radius: 13px;
      box-shadow: 0 4px 14px rgba(0,0,0,0.10);
      padding: 36px 22px 24px 22px;
      display: flex;
      flex-direction: column;
      gap: 16px;
    }
    .contact-form input, .contact-form textarea {
      padding: 10px 11px;
      border: 1.5px solid #ced4da;
      border-radius: 6px;
      font-size: 1rem;
      font-family: inherit;
      resize: none;
      transition: border 0.16s;
    }
    .contact-form input:focus, .contact-form textarea:focus {
      border-color: var(--color-accent);
      outline: none;
    }
    .contact-form button {
      background: var(--color-accent);
      color: #fff;
      border: none;
      border-radius: 6px;
      font-weight: bold;
      padding: 11px 0;
      cursor: pointer;
      font-size: 1.05em;
      transition: background 0.24s, box-shadow 0.24s;
      box-shadow: 0 2px 8px rgba(0,0,0,0.07);
    }
    .contact-form button:hover {
      background: var(--color-accent-hover);
      box-shadow: 0 3px 14px rgba(0,0,0,0.10);
    }
    .form-success {
      color: #2ecc40;
      font-weight: 600;
      margin-top: 12px;
    }
    footer {
      background-color: var(--color-footer);
      color: white;
      text-align: center;
      padding: 28px 14px 15px 14px;
      margin-top: 40px;
      font-size: 1rem;
      border-top-left-radius: 13px;
      border-top-right-radius: 13px;
      box-shadow: 0 -2px 12px rgba(0,0,0,0.08);
    }
    footer .footer-links {
      margin-top: 8px;
      display: flex;
      justify-content: center;
      gap: 18px;
      flex-wrap: wrap;
    }
    footer .footer-links a {
      color: #fff;
      text-decoration: none;
      font-size: 1.12em;
      transition: color 0.3s;
    }
    footer .footer-links a:hover { color: #d97a3a; }
    footer .footer-socials {
      margin-top: 8px;
      display: flex;
      justify-content: center;
      gap: 18px;
      font-size: 1.3em;
    }
    footer .footer-socials a { color: #fff; transition: color 0.3s;}
    footer .footer-socials a:hover { color: #d97a3a; }
    @media (max-width: 750px) {
      header { flex-direction: column; text-align:center; gap:18px;}
      header img { margin-bottom: 14px; }
      .card img { height: 160px; }
      .contact-form { padding: 22px 7px 16px 7px;}
    }
    @media (max-width: 530px) {
      nav.navbar { padding: 4px 7px;}
      .navbar-space { height: 82px;}
      header { padding: 40px 8px 20px 8px;}
      section#propiedades { padding: 44px 7px 30px 7px;}
      #testimonios, #contacto { padding: 40px 7px 20px 7px;}
      .testimonio, .card { min-width: 120px;}
    }
    body.darkmode {
      --color-bg: #181c24;
      --color-text: #f2f2f2;
      --color-header: #101522;
      --color-accent: #d97a3a;
      --color-accent-hover: #b55e29;
      --color-card-bg: #232a36;
      --color-footer: #101522;
      --color-navbar-bg: rgba(16,21,34,0.97);
      --color-navbar-link: #f2f2f2;
      --color-navbar-link-active: #d97a3a;
    }
    body.darkmode .card p { color: #ddd; }
    body.darkmode .testimonio { background: #232a36; color: #e6e6e6;}
    body.darkmode .contact-form, body.darkmode .card { background: #232a36; color: #e6e6e6;}
    body.darkmode footer { background: #101522; color: #fff; }
    body.darkmode #testimonios { background: #212735; }
    body.darkmode #contacto { background: linear-gradient(180deg, #181c24 75%, #22293c 100%);}
    body.darkmode section#propiedades { background: linear-gradient(180deg,#181c24 80%,#232a36 100%);}
    body.darkmode #acciones { background: linear-gradient(90deg,#232a36 65%,#22293c 100%);}
    body.darkmode .acciones-cards a { background: #232a36; color: #e6e6e6;}
    body.darkmode .acciones-cards .acciones-title { color: #d97a3a;}
    body.darkmode .acciones-cards .acciones-desc { color: #bbb;}
  </style>
</head>
<body>
  <!-- NAVBAR -->
  <nav class="navbar">
    <a class="logo" href="#top">
      <img src="66F7FC11-4332-4082-B4B0-7BA4D9B0A790.png" alt="Esteban Tena Logo">
      Esteban Tena
    </a>
    <div class="links">
      <a href="#propiedades" class="active">Propiedades</a>
      <a href="#testimonios">Testimonios</a>
      <a href="#contacto">Contacto</a>
    </div>
    <div class="socials">
      <a href="https://wa.me/18624065471" target="_blank" title="WhatsApp"><i class="fab fa-whatsapp"></i></a>
      <a href="https://instagram.com/esteban_njrealtor" target="_blank" title="Instagram"><i class="fab fa-instagram"></i></a>
    </div>
  </nav>
  <div class="navbar-space"></div>
  <!-- PORTADA PRINCIPAL -->
  <header id="top">
    <img src="66F7FC11-4332-4082-B4B0-7BA4D9B0A790.png" alt="Esteban Tena - Real Estate">
    <div class="info">
      <h1>Dedica menos tiempo buscando vivienda,<br>permíteme hacerlo por ti.</h1>
      <p><strong>Real Estate:</strong> Esteban Tena</p>
      <p><strong>📞 862-406-5471</strong></p>
      <div class="contacto">
        <a href="tel:8624065471"><i class="fa fa-phone"></i> LLAMA AHORA</a>
        <a href="https://wa.me/18624065471" target="_blank"><i class="fab fa-whatsapp"></i> WHATSAPP</a>
        <button class="toggle-darkmode" id="darkmodeBtn" aria-label="Cambiar modo oscuro/claro">🌙 Modo oscuro</button>
      </div>
    </div>
  </header>
  <!-- SECCIÓN ACCIONES LINKTREE -->
  <section id="acciones">
    <h2>¿Qué deseas hacer hoy?</h2>
    <div class="acciones-cards">
      <a href="https://docs.google.com/forms/d/e/1FAIpQLSfJgtDvH2iMZOMzC_VZkMArCCcyO3G-9x20Rlr7PL4Z7qNbrg/viewform?usp=dialog" target="_blank">
        <i class="fas fa-key" style="color:#d97a3a;font-size:2.3em;"></i>
        <span class="acciones-title">Estoy listo para rentar</span>
        <span class="acciones-desc">Encuentra la mejor opción de alquiler para ti.</span>
      </a>
      <a href="https://docs.google.com/forms/d/e/1FAIpQLSfxB7cAL_wfomvANx-4XsSljw-XUZNAwiqGdK30aBNHWBnruA/viewform?usp=header" target="_blank">
        <i class="fas fa-home" style="color:#0d1b2a;font-size:2.3em;"></i>
        <span class="acciones-title">Estoy listo para vender</span>
        <span class="acciones-desc">Vende tu propiedad rápido y al mejor precio.</span>
      </a>
      <a href="https://docs.google.com/forms/d/e/1FAIpQLSftXbe7R_jKmQlVy_4KHcoC4U6iiGkXxZ_NAgJUrc_TPquznw/viewform?usp=header" target="_blank">
        <i class="fas fa-dollar-sign" style="color:#d97a3a;font-size:2.3em;"></i>
        <span class="acciones-title">Estoy listo para comprar</span>
        <span class="acciones-desc">Te ayudo a encontrar tu nuevo hogar.</span>
      </a>
    </div>
  </section>
  <!-- SECCIÓN PROPIEDADES -->
  <section id="propiedades">
    <h2>Propiedades Destacadas en New Jersey</h2>
    <div class="grid">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1600607687486-6cc36d7e5f2f" alt="Casa de lujo en Bergen">
        <h3>Casa de lujo en Bergen County</h3>
        <p>Moderna y amplia, ubicada en uno de los vecindarios más exclusivos.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1564013799919-ab600027ffc6" alt="Apartamento en Jersey City">
        <h3>Apartamento en Jersey City</h3>
        <p>Hermosas vistas al río Hudson, ideal para quienes trabajan en NYC.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1599423300746-b62533397364" alt="Suburbio familiar">
        <h3>Casa en Montclair</h3>
        <p>Perfecta para familias, cerca de colegios y parques.</p>
      </div>
    </div>
  </section>
  <!-- TESTIMONIOS -->
  <section id="testimonios">
    <h2>Testimonios de Clientes</h2>
    <div class="testimonios-lista">
      <div class="testimonio">
        <img class="avatar" src="https://randomuser.me/api/portraits/men/32.jpg" alt="Avatar">
        <div class="nombre">Carlos M.</div>
        <div class="texto">"¡Excelente atención y rapidez! Encontré mi casa ideal en menos de una semana."</div>
        <div>
          <i class="fa fa-star estrella"></i><i class="fa fa-star estrella"></i><i class="fa fa-star estrella"></i><i class="fa fa-star estrella"></i><i class="fa fa-star estrella"></i>
        </div>
      </div>
      <div class="testimonio">
        <img class="avatar" src="https://randomuser.me/api/portraits/women/68.jpg" alt="Avatar">
        <div class="nombre">Ana T.</div>
        <div class="texto">"Esteban me ayudó en cada paso del proceso, ¡muy recomendado!"</div>
        <div>
          <i class="fa fa-star estrella"></i><i class="fa fa-star estrella"></i><i class="fa fa-star estrella"></i><i class="fa fa-star estrella"></i><i class="fa fa-star estrella"></i>
        </div>
      </div>
      <div class="testimonio">
        <img class="avatar" src="https://randomuser.me/api/portraits/men/65.jpg" alt="Avatar">
        <div class="nombre">Luis V.</div>
        <div class="texto">"Profesional, confiable y atento. Sin duda volvería a contratarlo."</div>
        <div>
          <i class="fa fa-star estrella"></i><i class="fa fa-star estrella"></i><i class="fa fa-star estrella"></i><i class="fa fa-star estrella"></i><i class="fa fa-star estrella"></i>
        </div>
      </div>
    </div>
  </section>
  <!-- FORMULARIO DE CONTACTO -->
  <section id="contacto">
    <h2>Contáctame</h2>
    <form class="contact-form" id="contactForm" autocomplete="off">
      <input type="text" id="nombre" name="nombre" placeholder="Tu nombre" required>
      <input type="email" id="email" name="email" placeholder="Tu correo electrónico" required>
      <textarea id="mensaje" name="mensaje" rows="4" placeholder="¿Cómo puedo ayudarte?" required></textarea>
      <button type="submit">Enviar mensaje</button>
      <div class="form-success" id="formSuccess" style="display:none;">
        ¡Gracias por tu mensaje! Te responderé pronto.
      </div>
    </form>
  </section>
  <footer>
    <div>
      <strong>© 2025 Real Estate Esteban Tena</strong> | Todos los derechos reservados
    </div>
    <div class="footer-links">
      <a href="#propiedades">Propiedades</a>
      <a href="#testimonios">Testimonios</a>
      <a href="#contacto">Contacto</a>
    </div>
    <div class="footer-socials">
      <a href="https://instagram.com/esteban_njrealtor" target="_blank" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
      <a href="https://wa.me/18624065471" target="_blank" aria-label="WhatsApp"><i class="fab fa-whatsapp"></i></a>
    </div>
    <div style="margin-top:10px;font-size:0.95em;">
      Sígueme en <strong>@esteban_njrealtor</strong>
    </div>
  </footer>
  <script>
    // DARK MODE
    const darkmodeBtn = document.getElementById('darkmodeBtn');
    function updateBtn() {
      if (document.body.classList.contains('darkmode')) {
        darkmodeBtn.textContent = '☀️ Modo claro';
      } else {
        darkmodeBtn.textContent = '🌙 Modo oscuro';
      }
    }
    darkmodeBtn.addEventListener('click', () => {
      document.body.classList.toggle('darkmode');
      updateBtn();
      if(document.body.classList.contains('darkmode')){
        localStorage.setItem('darkmode','1');
      } else {
        localStorage.removeItem('darkmode');
      }
    });
    if(localStorage.getItem('darkmode')){
      document.body.classList.add('darkmode');
    }
    updateBtn();
    // NAVBAR active links
    document.querySelectorAll('.navbar .links a').forEach(link => {
      link.addEventListener('click', function(){
        document.querySelectorAll('.navbar .links a').forEach(l => l.classList.remove('active'));
        this.classList.add('active');
      });
    });
    // CONTACT FORM - Simulación de envío (sin backend)
    document.getElementById('contactForm').addEventListener('submit', function(e){
      e.preventDefault();
      document.getElementById('formSuccess').style.display = 'block';
      setTimeout(()=>{ document.getElementById('formSuccess').style.display = 'none'; }, 3500);
      this.reset();
    });
  </script>
</body>
</html>
