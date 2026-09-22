<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="educad - Sistema de Gestión Educativa. Digitaliza, organiza y simplifica la gestión de tu institución educativa.">
  <meta name="theme-color" content="#173b68">
  <title>educad | Sistema de Gestión Educativa</title>

  <!-- Fuente moderna. Si quieres 100% offline, puedes quitar esta línea. -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Nunito:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">

  <style>
    :root{
      --navy:#173b68;
      --navy-2:#234b7b;
      --teal:#16b8b1;
      --teal-2:#45c9c1;
      --orange:#f47b45;
      --orange-2:#ff9a5c;
      --blue:#277bdc;
      --purple:#7650c8;
      --ink:#18375f;
      --muted:#64748b;
      --bg:#f7fbfc;
      --white:#ffffff;
      --line:#e5eef3;
      --shadow:0 18px 50px rgba(23,59,104,.12);
      --radius:24px;
    }

    *{box-sizing:border-box;margin:0;padding:0}
    html{scroll-behavior:smooth}
    body{
      font-family:"Nunito",system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif;
      color:var(--ink);
      background:var(--bg);
      overflow-x:hidden;
    }
    body.menu-open{overflow:hidden}
    a{text-decoration:none;color:inherit}
    button,input{font:inherit}

    /* ---------- UTILIDADES ---------- */
    .container{width:min(1180px,92%);margin:auto}
    .section{padding:100px 0;position:relative}
    .eyebrow{
      display:inline-flex;align-items:center;gap:8px;
      padding:8px 14px;border-radius:999px;
      background:#e9fbfa;color:#087e7b;font-size:.82rem;font-weight:900;
      letter-spacing:.5px;text-transform:uppercase;
    }
    .section-title{
      font-size:clamp(2rem,4vw,3.2rem);
      line-height:1.05;margin:16px 0 14px;font-weight:900;
    }
    .section-title span{color:var(--teal)}
    .section-lead{
      max-width:680px;color:var(--muted);font-size:1.08rem;line-height:1.7;
    }

    /* ---------- NAV ---------- */
    .nav{
      position:fixed;top:0;left:0;width:100%;z-index:1000;
      background:rgba(255,255,255,.82);
      backdrop-filter:blur(18px);
      border-bottom:1px solid rgba(229,238,243,.8);
      transition:.3s ease;
    }
    .nav.scrolled{box-shadow:0 10px 30px rgba(23,59,104,.08)}
    .nav-inner{
      min-height:76px;display:flex;align-items:center;justify-content:space-between;
      gap:25px;
    }
    .brand{display:flex;align-items:center;gap:10px}
    .brand-mark{
      width:42px;height:42px;border-radius:13px;
      display:grid;place-items:center;color:white;font-weight:900;font-size:1.25rem;
      background:linear-gradient(135deg,var(--navy),var(--teal));
      box-shadow:0 8px 20px rgba(22,184,177,.22);
    }
    .brand-text{font-size:1.65rem;font-weight:900;letter-spacing:-1.5px;color:var(--navy)}
    .brand-text i{font-style:normal;color:var(--teal)}
    .nav-links{display:flex;align-items:center;gap:28px;font-weight:800;color:#48617f;font-size:.95rem}
    .nav-links a{position:relative;padding:28px 0}
    .nav-links a:after{
      content:"";position:absolute;left:0;right:100%;bottom:20px;height:3px;
      background:var(--teal);border-radius:99px;transition:.25s;
    }
    .nav-links a:hover:after{right:0}
    .nav-cta{
      padding:11px 18px!important;border-radius:999px;background:var(--navy);color:white!important;
      box-shadow:0 8px 18px rgba(23,59,104,.2);
    }
    .nav-cta:after{display:none}
    .menu-btn{display:none;border:0;background:transparent;font-size:1.7rem;color:var(--navy);cursor:pointer}

    /* ---------- HERO ---------- */
    .hero{
      min-height:850px;padding:145px 0 80px;
      position:relative;overflow:hidden;
      background:
        radial-gradient(circle at 10% 15%,rgba(22,184,177,.12),transparent 22%),
        radial-gradient(circle at 92% 20%,rgba(244,123,69,.12),transparent 22%),
        linear-gradient(180deg,#fff 0%,#f5fbfc 100%);
    }
    .blob{
      position:absolute;border-radius:50%;filter:blur(1px);pointer-events:none;
    }
    .blob.one{width:300px;height:300px;background:#dff7f5;left:-150px;top:230px}
    .blob.two{width:210px;height:210px;background:#fff0e9;right:-80px;bottom:130px}
    .hero-grid{
      display:grid;grid-template-columns:1.03fr .97fr;align-items:center;gap:60px;position:relative;z-index:2;
    }
    .hero h1{
      font-size:clamp(3.2rem,7vw,5.8rem);line-height:.94;letter-spacing:-4px;font-weight:900;
      margin:22px 0;
    }
    .hero h1 span{display:block;color:var(--teal)}
    .hero-copy{font-size:1.2rem;line-height:1.7;color:var(--muted);max-width:600px}
    .hero-actions{display:flex;gap:14px;flex-wrap:wrap;margin:32px 0 26px}
    .btn{
      display:inline-flex;align-items:center;justify-content:center;gap:10px;
      border:0;border-radius:14px;padding:14px 22px;font-weight:900;cursor:pointer;
      transition:.25s ease;
    }
    .btn-primary{
      color:#fff;background:linear-gradient(135deg,var(--navy),var(--navy-2));
      box-shadow:0 12px 25px rgba(23,59,104,.2);
    }
    .btn-primary:hover{transform:translateY(-3px);box-shadow:0 17px 30px rgba(23,59,104,.27)}
    .btn-secondary{background:white;color:var(--navy);border:1px solid var(--line)}
    .btn-secondary:hover{transform:translateY(-3px);border-color:#bfe6e3}
    .mini-proof{display:flex;gap:20px;flex-wrap:wrap;color:#5f7188;font-weight:700;font-size:.9rem}
    .mini-proof span{display:flex;align-items:center;gap:7px}
    .check{color:var(--teal);font-weight:900}

    .hero-art{position:relative;min-height:510px;display:grid;place-items:center}
    .art-glow{
      position:absolute;width:470px;height:470px;border-radius:50%;
      background:radial-gradient(circle,#dff7f5 0%,rgba(223,247,245,.35) 55%,transparent 70%);
    }
    .screen{
      position:relative;width:min(520px,95%);height:330px;border:13px solid var(--navy);
      border-radius:30px;background:white;box-shadow:0 28px 55px rgba(23,59,104,.2);
      transform:perspective(900px) rotateY(-5deg) rotateX(2deg);
      overflow:hidden;
    }
    .screen-top{height:42px;background:#f2f8fa;border-bottom:1px solid #e2edf1;display:flex;align-items:center;padding:0 14px;gap:6px}
    .dot{width:9px;height:9px;border-radius:50%}
    .dot.teal{background:var(--teal)}.dot.orange{background:var(--orange)}.dot.blue{background:var(--blue)}
    .dashboard{display:grid;grid-template-columns:105px 1fr;height:calc(100% - 42px)}
    .side{background:#eef9f8;padding:18px 12px}
    .side-logo{height:32px;border-radius:9px;background:var(--teal);margin-bottom:20px}
    .side-line{height:10px;background:#cde9e7;border-radius:9px;margin:12px 0}
    .dash-main{padding:20px}
    .dash-title{width:55%;height:17px;background:#dce9f3;border-radius:9px;margin-bottom:18px}
    .dash-cards{display:grid;grid-template-columns:repeat(3,1fr);gap:12px}
    .dash-card{height:75px;border-radius:16px;padding:12px}
    .dash-card.a{background:#e5f9f7}.dash-card.b{background:#fff0e9}.dash-card.c{background:#eaf3ff}
    .dash-icon{width:27px;height:27px;border-radius:8px;margin-bottom:9px}
    .dash-card.a .dash-icon{background:var(--teal)}.dash-card.b .dash-icon{background:var(--orange)}.dash-card.c .dash-icon{background:var(--blue)}
    .dash-bar{height:7px;background:rgba(23,59,104,.12);border-radius:99px;margin:5px 0}
    .book-stack{position:absolute;left:0;bottom:20px;width:190px;transform:rotate(-6deg)}
    .book{height:38px;border-radius:9px 13px 13px 9px;margin-top:7px;box-shadow:0 8px 15px rgba(23,59,104,.14)}
    .book.one{background:#f47b45;width:155px}.book.two{background:#1bbab2;width:180px}.book.three{background:#173b68;width:135px}
    .pencil{position:absolute;right:8px;bottom:15px;width:23px;height:180px;background:var(--orange);border-radius:15px;transform:rotate(32deg);box-shadow:0 12px 25px rgba(244,123,69,.25)}
    .pencil:before{content:"";position:absolute;top:-22px;left:0;border-left:11px solid transparent;border-right:11px solid transparent;border-bottom:24px solid #e9c8a7}
    .cap{position:absolute;right:15px;top:35px;font-size:4.6rem;filter:drop-shadow(0 10px 10px rgba(23,59,104,.15))}

    /* ---------- STATS ---------- */
    .stats{margin-top:-40px;position:relative;z-index:5}
    .stats-box{
      background:white;border:1px solid var(--line);box-shadow:var(--shadow);
      border-radius:25px;padding:25px;display:grid;grid-template-columns:repeat(4,1fr);gap:10px;
    }
    .stat{text-align:center;padding:12px;border-right:1px solid var(--line)}
    .stat:last-child{border-right:0}
    .stat strong{display:block;font-size:1.8rem;color:var(--navy);font-weight:900}
    .stat span{color:var(--muted);font-size:.9rem}

    /* ---------- FEATURES ---------- */
    .features{background:white}
    .section-head{display:flex;align-items:end;justify-content:space-between;gap:30px;margin-bottom:45px}
    .feature-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
    .feature{
      background:white;border:1px solid var(--line);border-radius:24px;padding:28px;
      min-height:255px;position:relative;overflow:hidden;
      box-shadow:0 12px 35px rgba(23,59,104,.06);transition:.3s;
    }
    .feature:hover{transform:translateY(-8px);box-shadow:0 22px 45px rgba(23,59,104,.12)}
    .feature:before{content:"";position:absolute;left:0;bottom:0;width:100%;height:5px;background:var(--teal)}
    .feature.orange:before{background:var(--orange)}
    .feature.blue:before{background:var(--blue)}
    .feature.purple:before{background:var(--purple)}
    .feature-icon{
      width:58px;height:58px;border-radius:18px;display:grid;place-items:center;
      font-size:1.7rem;background:#e7faf8;margin-bottom:20px;
    }
    .feature.orange .feature-icon{background:#fff0e9}.feature.blue .feature-icon{background:#eaf3ff}.feature.purple .feature-icon{background:#f0eaff}
    .feature h3{font-size:1.2rem;margin-bottom:8px}
    .feature p{color:var(--muted);line-height:1.6}

    /* ---------- SHOWCASE ---------- */
    .showcase{background:#f4fafb;overflow:hidden}
    .show-grid{display:grid;grid-template-columns:.9fr 1.1fr;gap:70px;align-items:center}
    .benefits{display:grid;gap:16px;margin-top:28px}
    .benefit{display:flex;gap:15px;align-items:flex-start;padding:16px;background:white;border:1px solid var(--line);border-radius:18px}
    .benefit-icon{width:44px;height:44px;flex:0 0 44px;border-radius:14px;display:grid;place-items:center;background:#e6faf8}
    .benefit h4{margin-bottom:3px}.benefit p{color:var(--muted);font-size:.9rem;line-height:1.5}
    .showcase-card{
      background:linear-gradient(145deg,var(--navy),#245484);border-radius:35px;padding:35px;
      min-height:470px;color:white;position:relative;overflow:hidden;box-shadow:0 30px 60px rgba(23,59,104,.22)
    }
    .showcase-card:before{content:"";position:absolute;width:260px;height:260px;border-radius:50%;background:rgba(22,184,177,.18);right:-80px;top:-80px}
    .showcase-card h3{font-size:2rem;max-width:420px;position:relative}
    .showcase-card p{color:#cbd9e7;line-height:1.7;max-width:500px;margin:12px 0 25px;position:relative}
    .mock-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:14px;position:relative}
    .mock{background:rgba(255,255,255,.1);border:1px solid rgba(255,255,255,.15);border-radius:18px;padding:18px;backdrop-filter:blur(8px)}
    .mock strong{display:block;font-size:1.05rem;margin-top:8px}.mock small{color:#cbd9e7}
    .mock-icon{font-size:1.7rem}

    /* ---------- PROCESS ---------- */
    .process{background:white}
    .steps{display:grid;grid-template-columns:repeat(4,1fr);gap:20px;margin-top:45px}
    .step{position:relative;padding:30px;border-radius:24px;background:#f7fbfc;border:1px solid var(--line)}
    .step-number{width:48px;height:48px;border-radius:15px;background:var(--navy);color:white;display:grid;place-items:center;font-weight:900;font-size:1.2rem;margin-bottom:18px}
    .step:nth-child(2) .step-number{background:var(--teal)}.step:nth-child(3) .step-number{background:var(--orange)}.step:nth-child(4) .step-number{background:var(--blue)}
    .step h3{margin-bottom:8px}.step p{color:var(--muted);line-height:1.55}

    /* ---------- CTA ---------- */
    .cta-section{padding:90px 0;background:var(--navy);position:relative;overflow:hidden;color:white}
    .cta-section:before,.cta-section:after{content:"";position:absolute;border-radius:50%;pointer-events:none}
    .cta-section:before{width:360px;height:360px;background:rgba(22,184,177,.15);right:-130px;top:-130px}
    .cta-section:after{width:250px;height:250px;background:rgba(244,123,69,.13);left:-110px;bottom:-110px}
    .cta-inner{position:relative;z-index:2;display:flex;justify-content:space-between;align-items:center;gap:40px}
    .cta-inner h2{font-size:clamp(2rem,4vw,3.2rem);line-height:1.05;margin:15px 0}
    .cta-inner p{color:#cad8e8;max-width:650px;line-height:1.7}
    .cta-contact{display:grid;gap:10px;margin-top:20px;color:#e6eff7;font-weight:700}
    .cta-contact span{display:flex;align-items:center;gap:10px}
    .cta-contact b{color:#5de0d7}

    /* ---------- FOOTER ---------- */
    footer{background:#102f54;color:#aec0d4;padding:28px 0}
    .footer-inner{display:flex;justify-content:space-between;align-items:center;gap:20px}
    .footer-brand{color:white;font-weight:900;font-size:1.25rem}.footer-brand i{font-style:normal;color:var(--teal)}
    footer small{font-size:.82rem}

    /* ---------- FLOATING BUTTONS ---------- */
    .top-btn{
      position:fixed;right:22px;bottom:22px;width:46px;height:46px;border:0;border-radius:15px;
      background:var(--navy);color:white;cursor:pointer;display:grid;place-items:center;
      opacity:0;pointer-events:none;transform:translateY(10px);transition:.25s;z-index:900;
      box-shadow:0 12px 25px rgba(23,59,104,.25)
    }
    .top-btn.show{opacity:1;pointer-events:auto;transform:none}
    .whatsapp{
      position:fixed;left:22px;bottom:22px;width:54px;height:54px;border-radius:50%;
      display:grid;place-items:center;background:#20c997;color:white;font-size:1.5rem;
      box-shadow:0 14px 30px rgba(32,201,151,.3);z-index:900;transition:.25s
    }
    .whatsapp:hover{transform:scale(1.08)}

    /* ---------- MODAL ---------- */
    .modal{
      position:fixed;inset:0;background:rgba(10,30,52,.65);backdrop-filter:blur(7px);
      display:grid;place-items:center;padding:20px;opacity:0;pointer-events:none;transition:.25s;z-index:2000
    }
    .modal.open{opacity:1;pointer-events:auto}
    .modal-box{
      width:min(650px,100%);background:white;border-radius:28px;padding:34px;position:relative;
      box-shadow:0 30px 90px rgba(0,0,0,.25);transform:translateY(20px) scale(.98);transition:.25s
    }
    .modal.open .modal-box{transform:none}
    .close{position:absolute;right:18px;top:15px;border:0;background:#eef5f7;width:38px;height:38px;border-radius:50%;cursor:pointer;color:var(--navy);font-size:1.2rem}
    .modal-box h3{font-size:2rem;margin-bottom:8px}.modal-box p{color:var(--muted);line-height:1.6;margin-bottom:22px}
    .contact-options{display:grid;grid-template-columns:1fr 1fr;gap:14px}
    .contact-card{padding:18px;border-radius:18px;background:#f6fbfc;border:1px solid var(--line)}
    .contact-card strong{display:block;margin-bottom:5px}.contact-card span{color:var(--muted);font-size:.9rem}

    /* ---------- EASTER EGG ---------- */
    .egg-overlay{
      position:fixed;inset:0;background:rgba(10,25,45,.86);backdrop-filter:blur(12px);
      z-index:3000;display:grid;place-items:center;padding:20px;opacity:0;pointer-events:none;transition:.3s
    }
    .egg-overlay.open{opacity:1;pointer-events:auto}
    .egg{
      width:min(620px,100%);background:linear-gradient(145deg,#fff,#eefcfb);border-radius:30px;
      padding:35px;text-align:center;box-shadow:0 35px 100px rgba(0,0,0,.35);position:relative;overflow:hidden
    }
    .egg h2{font-size:2.4rem;color:var(--navy);margin:10px 0}
    .egg p{color:var(--muted);margin-bottom:20px}
    .game-area{
      width:100%;height:240px;border-radius:22px;background:#173b68;position:relative;overflow:hidden;
      border:5px solid #dff7f5;cursor:crosshair
    }
    .game-target{
      position:absolute;width:42px;height:42px;border-radius:50%;display:grid;place-items:center;
      background:var(--orange);box-shadow:0 0 0 7px rgba(244,123,69,.18);
      user-select:none;transition:.08s;cursor:pointer
    }
    .game-info{display:flex;justify-content:space-between;gap:10px;margin:14px 0;font-weight:900;color:var(--navy)}
    .egg-close{margin-top:12px}
    .hint{font-size:.82rem;color:#7a8b9f}

    /* ---------- REVEAL ---------- */
    .reveal{opacity:0;transform:translateY(25px);transition:.7s ease}
    .reveal.visible{opacity:1;transform:none}

    /* ---------- RESPONSIVE ---------- */
    @media(max-width:950px){
      .nav-links{
        position:fixed;top:76px;right:0;width:min(330px,85%);
        height:calc(100vh - 76px);background:white;padding:25px;
        flex-direction:column;align-items:stretch;gap:5px;
        transform:translateX(105%);transition:.3s;box-shadow:-15px 0 40px rgba(23,59,104,.12)
      }
      .nav-links.open{transform:none}
      .nav-links a{padding:15px;border-radius:12px}.nav-links a:hover{background:#f3f9fa}
      .nav-links a:after{display:none}
      .nav-cta{text-align:center}
      .menu-btn{display:block}
      .hero-grid,.show-grid{grid-template-columns:1fr}
      .hero{min-height:auto;padding-bottom:70px}
      .hero-art{min-height:430px}
      .section-head{display:block}
      .feature-grid{grid-template-columns:repeat(2,1fr)}
      .steps{grid-template-columns:repeat(2,1fr)}
      .cta-inner{display:block}
      .cta-inner .btn{margin-top:28px}
    }
    @media(max-width:620px){
      .section{padding:75px 0}
      .hero{padding-top:125px}
      .hero h1{font-size:3.2rem;letter-spacing:-2.5px}
      .hero-copy{font-size:1.05rem}
      .hero-art{min-height:340px}
      .screen{height:235px;border-width:9px;border-radius:22px}
      .dashboard{grid-template-columns:70px 1fr}
      .dash-cards{gap:6px}.dash-card{height:60px;padding:8px}
      .side{padding:10px 8px}
      .book-stack{width:125px;bottom:0}.pencil{height:125px}.cap{font-size:3rem}
      .stats-box{grid-template-columns:1fr 1fr}.stat{border-right:0;border-bottom:1px solid var(--line)}
      .feature-grid,.steps{grid-template-columns:1fr}
      .mock-grid{grid-template-columns:1fr}
      .showcase-card{padding:25px;min-height:auto}
      .contact-options{grid-template-columns:1fr}
      .footer-inner{display:block;text-align:center}.footer-inner small{display:block;margin-top:8px}
      .whatsapp{left:15px;bottom:15px}.top-btn{right:15px;bottom:15px}
    }
  </style>
</head>

<body>

  <!-- NAV -->
  <header class="nav" id="navbar">
    <div class="container nav-inner">
      <a class="brand" href="#inicio" aria-label="educad inicio">
        <div class="brand-mark">e</div>
        <div class="brand-text">educad<span>.</span></div>
      </a>

      <nav class="nav-links" id="navLinks">
        <a href="#inicio">Inicio</a>
        <a href="#herramientas">Herramientas</a>
        <a href="#beneficios">Beneficios</a>
        <a href="#como-funciona">Cómo funciona</a>
        <a href="#contacto" class="nav-cta">Contáctanos</a>
      </nav>

      <button class="menu-btn" id="menuBtn" aria-label="Abrir menú">☰</button>
    </div>
  </header>

  <main>

    <!-- HERO -->
    <section class="hero" id="inicio">
      <div class="blob one"></div>
      <div class="blob two"></div>

      <div class="container hero-grid">
        <div class="reveal">
          <span class="eyebrow">✦ Sistema de Gestión Educativa</span>

          <h1>
            Todo tu centro
            <span>educativo,</span>
            en un solo lugar.
          </h1>

          <p class="hero-copy">
            Digitaliza, organiza y simplifica la gestión de tu institución
            con herramientas pensadas para docentes, administración y familias.
          </p>

          <div class="hero-actions">
            <a class="btn btn-primary" href="#herramientas">Explorar herramientas →</a>
            <button class="btn btn-secondary" id="openContact">Solicitar información</button>
          </div>

          <div class="mini-proof">
            <span><b class="check">✓</b> Menos papeleo</span>
            <span><b class="check">✓</b> Más organización</span>
            <span><b class="check">✓</b> Mejor comunicación</span>
          </div>
        </div>

        <div class="hero-art reveal">
          <div class="art-glow"></div>
          <div class="cap">🎓</div>

          <div class="screen">
            <div class="screen-top">
              <span class="dot orange"></span>
              <span class="dot teal"></span>
              <span class="dot blue"></span>
            </div>
            <div class="dashboard">
              <aside class="side">
                <div class="side-logo"></div>
                <div class="side-line"></div>
                <div class="side-line"></div>
                <div class="side-line"></div>
                <div class="side-line"></div>
              </aside>
              <div class="dash-main">
                <div class="dash-title"></div>
                <div class="dash-cards">
                  <div class="dash-card a"><div class="dash-icon"></div><div class="dash-bar"></div><div class="dash-bar"></div></div>
                  <div class="dash-card b"><div class="dash-icon"></div><div class="dash-bar"></div><div class="dash-bar"></div></div>
                  <div class="dash-card c"><div class="dash-icon"></div><div class="dash-bar"></div><div class="dash-bar"></div></div>
                </div>
                <div style="height:15px"></div>
                <div class="dash-bar" style="height:12px;width:90%"></div>
                <div class="dash-bar" style="height:12px;width:72%"></div>
                <div class="dash-bar" style="height:12px;width:82%"></div>
              </div>
            </div>
          </div>

          <div class="book-stack">
            <div class="book one"></div>
            <div class="book two"></div>
            <div class="book three"></div>
          </div>
          <div class="pencil"></div>
        </div>
      </div>
    </section>

    <!-- STATS -->
    <section class="stats">
      <div class="container">
        <div class="stats-box reveal">
          <div class="stat"><strong>QR</strong><span>Asistencia rápida</span></div>
          <div class="stat"><strong>Auto</strong><span>Libretas automáticas</span></div>
          <div class="stat"><strong>360°</strong><span>Gestión institucional</span></div>
          <div class="stat"><strong>1 lugar</strong><span>Información organizada</span></div>
        </div>
      </div>
    </section>

    <!-- FEATURES -->
    <section class="section features" id="herramientas">
      <div class="container">
        <div class="section-head reveal">
          <div>
            <span class="eyebrow">Nuestras herramientas</span>
            <h2 class="section-title">Todo lo que necesitas para una gestión <span>más fácil.</span></h2>
          </div>
          <p class="section-lead">
            Una propuesta de herramientas para centralizar procesos académicos,
            administrativos y de comunicación.
          </p>
        </div>

        <div class="feature-grid">

          <article class="feature reveal">
            <div class="feature-icon">▦</div>
            <h3>Asistencia con QR</h3>
            <p>Registra la asistencia de estudiantes de forma rápida y organizada mediante códigos QR.</p>
          </article>

          <article class="feature orange reveal">
            <div class="feature-icon">▤</div>
            <h3>Libretas automáticas</h3>
            <p>Facilita la generación e impresión de libretas y calificaciones por bloque o sección.</p>
          </article>

          <article class="feature blue reveal">
            <div class="feature-icon">◉</div>
            <h3>Gestión de cobros</h3>
            <p>Da seguimiento a pagos, colegiaturas y saldos de los estudiantes.</p>
          </article>

          <article class="feature purple reveal">
            <div class="feature-icon">♧</div>
            <h3>Portal para padres</h3>
            <p>Facilita la consulta de notas, asistencia y actividades para las familias.</p>
          </article>

          <article class="feature reveal">
            <div class="feature-icon">✓</div>
            <h3>Control de conducta</h3>
            <p>Registra y consulta incidencias para llevar un seguimiento organizado.</p>
          </article>

          <article class="feature blue reveal">
            <div class="feature-icon">▦</div>
            <h3>Agenda y actividades</h3>
            <p>Organiza tareas, actividades, circulares y comunicación escolar.</p>
          </article>

          <article class="feature orange reveal">
            <div class="feature-icon">↗</div>
            <h3>Reportes y estadísticas</h3>
            <p>Presenta información organizada para apoyar la gestión de la institución.</p>
          </article>

          <article class="feature purple reveal">
            <div class="feature-icon">▣</div>
            <h3>Gestión administrativa</h3>
            <p>Centraliza diferentes procesos en una experiencia clara y sencilla.</p>
          </article>

          <article class="feature reveal">
            <div class="feature-icon">☁</div>
            <h3>Información organizada</h3>
            <p>Consulta la información que necesitas desde una interfaz moderna y ordenada.</p>
          </article>

        </div>
      </div>
    </section>

    <!-- BENEFITS -->
    <section class="section showcase" id="beneficios">
      <div class="container show-grid">
        <div class="reveal">
          <span class="eyebrow">¿Por qué educad?</span>
          <h2 class="section-title">Tecnología que <span>simplifica</span> la educación.</h2>
          <p class="section-lead">
            La idea es reducir tareas repetitivas y ayudarte a concentrarte en
            lo más importante: la comunidad educativa.
          </p>

          <div class="benefits">
            <div class="benefit">
              <div class="benefit-icon">⚡</div>
              <div><h4>Ahorra tiempo</h4><p>Automatiza procesos y reduce trabajo manual.</p></div>
            </div>
            <div class="benefit">
              <div class="benefit-icon">🛡</div>
              <div><h4>Información organizada</h4><p>Encuentra la información de manera más clara y ordenada.</p></div>
            </div>
            <div class="benefit">
              <div class="benefit-icon">✨</div>
              <div><h4>Experiencia moderna</h4><p>Una interfaz pensada para facilitar el uso diario.</p></div>
            </div>
            <div class="benefit">
              <div class="benefit-icon">🤝</div>
              <div><h4>Comunicación</h4><p>Acerca a la institución, docentes y familias.</p></div>
            </div>
          </div>
        </div>

        <div class="showcase-card reveal">
          <h3>Una plataforma pensada para la comunidad educativa.</h3>
          <p>
            Desde la asistencia hasta las libretas, cobros, agendas y comunicación,
            educad reúne diferentes herramientas en una experiencia sencilla.
          </p>

          <div class="mock-grid">
            <div class="mock"><div class="mock-icon">▦</div><strong>Asistencia QR</strong><small>Registro rápido</small></div>
            <div class="mock"><div class="mock-icon">▤</div><strong>Libretas</strong><small>Generación automática</small></div>
            <div class="mock"><div class="mock-icon">◉</div><strong>Cobros</strong><small>Seguimiento de pagos</small></div>
            <div class="mock"><div class="mock-icon">♧</div><strong>Padres</strong><small>Consulta de información</small></div>
          </div>
        </div>
      </div>
    </section>

    <!-- HOW IT WORKS -->
    <section class="section process" id="como-funciona">
      <div class="container">
        <div class="reveal">
          <span class="eyebrow">Así de sencillo</span>
          <h2 class="section-title">Una experiencia <span>simple.</span></h2>
          <p class="section-lead">Una presentación clara para que cada institución pueda conocer las posibilidades de educad.</p>
        </div>

        <div class="steps">
          <div class="step reveal">
            <div class="step-number">01</div>
            <h3>Conoce</h3>
            <p>Explora las herramientas y descubre cuáles pueden adaptarse a tu institución.</p>
          </div>
          <div class="step reveal">
            <div class="step-number">02</div>
            <h3>Organiza</h3>
            <p>Centraliza los procesos que quieres gestionar de una forma más ordenada.</p>
          </div>
          <div class="step reveal">
            <div class="step-number">03</div>
            <h3>Digitaliza</h3>
            <p>Reduce procesos manuales y aprovecha herramientas digitales.</p>
          </div>
          <div class="step reveal">
            <div class="step-number">04</div>
            <h3>Avanza</h3>
            <p>Dedica más tiempo a la comunidad educativa y menos al papeleo.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- CTA -->
    <section class="cta-section" id="contacto">
      <div class="container cta-inner">
        <div class="reveal">
          <span class="eyebrow" style="background:rgba(255,255,255,.12);color:#8ff2ec">¿Hablamos?</span>
          <h2>Moderniza la gestión<br>de tu institución.</h2>
          <p>
            Conoce educad y descubre cómo una plataforma digital puede ayudarte
            a organizar mejor tus procesos educativos.
          </p>

          <div class="cta-contact">
            <span><b>✉</b> vegoescolar@gmail.com</span>
            <span><b>☎</b> 3877-7262</span>
          </div>
        </div>

        <div class="reveal">
          <button class="btn btn-secondary" id="openContact2">Quiero conocer educad →</button>
        </div>
      </div>
    </section>

  </main>

  <footer>
    <div class="container footer-inner">
      <div class="footer-brand">educad<span>.</span></div>
      <small>© <span id="year"></span> educad · Sistema de Gestión Educativa</small>
      <small>Organiza · Controla · Avanza</small>
    </div>
  </footer>

  <!-- BOTÓN WHATSAPP -->
  <a
    class="whatsapp"
    href="https://wa.me/50238777262?text=Hola%20educad,%20quiero%20conocer%20la%20plataforma."
    target="_blank"
    rel="noopener"
    aria-label="Contactar por WhatsApp"
    title="Escribir por WhatsApp">☎</a>

  <button class="top-btn" id="topBtn" aria-label="Volver arriba">↑</button>

  <!-- MODAL CONTACTO -->
  <div class="modal" id="contactModal" aria-hidden="true">
    <div class="modal-box">
      <button class="close" id="closeContact" aria-label="Cerrar">×</button>
      <span class="eyebrow">Contacto</span>
      <h3>Hablemos de educad.</h3>
      <p>Elige la forma que prefieras para solicitar información.</p>

      <div class="contact-options">
        <a class="contact-card" href="mailto:vegoescolar@gmail.com?subject=Información%20sobre%20educad">
          <strong>✉ Correo electrónico</strong>
          <span>vegoescolar@gmail.com</span>
        </a>
        <a class="contact-card" href="https://wa.me/50238777262?text=Hola%20educad,%20quiero%20solicitar%20información." target="_blank" rel="noopener">
          <strong>☎ WhatsApp</strong>
          <span>3877-7262</span>
        </a>
      </div>
    </div>
  </div>

  <!-- EASTER EGG -->
  <div class="egg-overlay" id="eggOverlay">
    <div class="egg">
      <button class="close" id="closeEgg" aria-label="Cerrar">×</button>
      <span class="eyebrow">✦ Easter Egg encontrado</span>
      <h2>¡Modo director activado! 🎓</h2>
      <p>Haz clic en el objetivo tantas veces como puedas antes de que termine el tiempo.</p>

      <div class="game-info">
        <span>Puntos: <b id="score">0</b></span>
        <span>Tiempo: <b id="time">15</b>s</span>
        <span>Récord: <b id="record">0</b></span>
      </div>

      <div class="game-area" id="gameArea">
        <div class="game-target" id="target">★</div>
      </div>

      <p class="hint">Pista: el secreto se activa con una combinación de teclas 😉</p>
      <button class="btn btn-primary egg-close" id="restartGame">Jugar de nuevo</button>
    </div>
  </div>

  <script>
    // ==========================================================
    // educad - JavaScript de la página promocional
    // ==========================================================

    const navbar = document.getElementById("navbar");
    const navLinks = document.getElementById("navLinks");
    const menuBtn = document.getElementById("menuBtn");
    const topBtn = document.getElementById("topBtn");

    // Menú móvil
    menuBtn.addEventListener("click", () => {
      navLinks.classList.toggle("open");
      document.body.classList.toggle("menu-open");
      menuBtn.textContent = navLinks.classList.contains("open") ? "×" : "☰";
    });

    document.querySelectorAll(".nav-links a").forEach(link => {
      link.addEventListener("click", () => {
        navLinks.classList.remove("open");
        document.body.classList.remove("menu-open");
        menuBtn.textContent = "☰";
      });
    });

    // Navbar + botón volver arriba
    window.addEventListener("scroll", () => {
      navbar.classList.toggle("scrolled", window.scrollY > 20);
      topBtn.classList.toggle("show", window.scrollY > 500);
    });

    topBtn.addEventListener("click", () => {
      window.scrollTo({top:0, behavior:"smooth"});
    });

    // Animaciones al entrar en pantalla
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if(entry.isIntersecting){
          entry.target.classList.add("visible");
          observer.unobserve(entry.target);
        }
      });
    }, {threshold:.12});

    document.querySelectorAll(".reveal").forEach(el => observer.observe(el));

    // Año automático
    document.getElementById("year").textContent = new Date().getFullYear();

    // Modal de contacto
    const modal = document.getElementById("contactModal");
    const openContact = document.getElementById("openContact");
    const openContact2 = document.getElementById("openContact2");
    const closeContact = document.getElementById("closeContact");

    function openModal(){
      modal.classList.add("open");
      modal.setAttribute("aria-hidden","false");
    }

    function closeModal(){
      modal.classList.remove("open");
      modal.setAttribute("aria-hidden","true");
    }

    openContact.addEventListener("click", openModal);
    openContact2.addEventListener("click", openModal);
    closeContact.addEventListener("click", closeModal);

    modal.addEventListener("click", e => {
      if(e.target === modal) closeModal();
    });

    // ==========================================================
    // EASTER EGG
    // Código secreto: escribe EDUCAD
    // ==========================================================

    const secret = ["e","d","u","c","a","d"];
    let typed = [];

    const eggOverlay = document.getElementById("eggOverlay");
    const closeEgg = document.getElementById("closeEgg");
    const restartGame = document.getElementById("restartGame");
    const gameArea = document.getElementById("gameArea");
    const target = document.getElementById("target");
    const scoreEl = document.getElementById("score");
    const timeEl = document.getElementById("time");
    const recordEl = document.getElementById("record");

    let score = 0;
    let timeLeft = 15;
    let timer = null;
    let gameActive = false;
    let record = Number(localStorage.getItem("educadRecord") || 0);

    recordEl.textContent = record;

    document.addEventListener("keydown", e => {
      if(["INPUT","TEXTAREA"].includes(document.activeElement.tagName)) return;

      typed.push(e.key.toLowerCase());
      typed = typed.slice(-secret.length);

      if(secret.every((key, i) => typed[i] === key)){
        openEgg();
        typed = [];
      }

      // Escape cierra modales
      if(e.key === "Escape"){
        closeModal();
        closeEggGame();
      }
    });

    function openEgg(){
      eggOverlay.classList.add("open");
      startGame();
    }

    function closeEggGame(){
      eggOverlay.classList.remove("open");
      stopGame();
    }

    closeEgg.addEventListener("click", closeEggGame);

    eggOverlay.addEventListener("click", e => {
      if(e.target === eggOverlay) closeEggGame();
    });

    function startGame(){
      stopGame();
      score = 0;
      timeLeft = 15;
      gameActive = true;
      scoreEl.textContent = score;
      timeEl.textContent = timeLeft;
      moveTarget();

      timer = setInterval(() => {
        timeLeft--;
        timeEl.textContent = timeLeft;

        if(timeLeft <= 0){
          gameActive = false;
          clearInterval(timer);
          if(score > record){
            record = score;
            localStorage.setItem("educadRecord", record);
            recordEl.textContent = record;
          }
          target.textContent = "✓";
          target.style.background = "#16b8b1";
        }
      },1000);
    }

    function stopGame(){
      if(timer) clearInterval(timer);
      timer = null;
      gameActive = false;
    }

    function moveTarget(){
      const maxX = gameArea.clientWidth - target.offsetWidth - 8;
      const maxY = gameArea.clientHeight - target.offsetHeight - 8;
      target.style.left = Math.max(5, Math.random() * maxX) + "px";
      target.style.top = Math.max(5, Math.random() * maxY) + "px";
    }

    target.addEventListener("click", e => {
      e.stopPropagation();
      if(!gameActive) return;
      score++;
      scoreEl.textContent = score;
      moveTarget();
    });

    restartGame.addEventListener("click", startGame);

    // Pequeña animación al pasar por encima de las tarjetas
    document.querySelectorAll(".feature").forEach(card => {
      card.addEventListener("mousemove", e => {
        const r = card.getBoundingClientRect();
        const x = ((e.clientX-r.left)/r.width-.5)*4;
        const y = ((e.clientY-r.top)/r.height-.5)*-4;
        card.style.transform = `translateY(-8px) rotateX(${y}deg) rotateY(${x}deg)`;
      });
      card.addEventListener("mouseleave", () => {
        card.style.transform = "";
      });
    });
  </script>
</body>
</html>
