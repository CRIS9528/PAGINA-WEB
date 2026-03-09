<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Grupo Mozu S.A. – Seguridad Privada Costa Rica</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Rajdhani:wght@400;600;700&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,300&display=swap" rel="stylesheet">
<style>
  :root {
    --navy: #0D1B2A;
    --navy-mid: #1B2E45;
    --navy-light: #254060;
    --gold: #E8A020;
    --gold-light: #F5C842;
    --white: #FFFFFF;
    --off-white: #F4F6FA;
    --text-muted: #8A9BB0;
    --border: rgba(232,160,32,0.2);
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    font-family: 'DM Sans', sans-serif;
    background: var(--navy);
    color: var(--white);
    overflow-x: hidden;
  }

  /* ─── NAV ─── */
  nav {
    position: fixed; top: 0; left: 0; right: 0; z-index: 1000;
    display: flex; align-items: center; justify-content: space-between;
    padding: 0 5vw;
    height: 70px;
    background: rgba(13,27,42,0.95);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid var(--border);
    transition: box-shadow 0.3s;
  }
  nav.scrolled { box-shadow: 0 4px 30px rgba(0,0,0,0.4); }

  .nav-logo {
    font-family: 'Rajdhani', sans-serif;
    font-size: 1.5rem; font-weight: 700; letter-spacing: 0.04em;
    color: var(--white); text-decoration: none;
    display: flex; align-items: center; gap: 10px;
  }
  .nav-logo span { color: var(--gold); }
  .logo-icon {
    width: 36px; height: 36px;
    background: var(--gold);
    clip-path: polygon(50% 0%, 100% 25%, 100% 75%, 50% 100%, 0% 75%, 0% 25%);
    display: flex; align-items: center; justify-content: center;
    font-size: 1rem; color: var(--navy); font-weight: 700;
  }

  .nav-links { display: flex; gap: 2rem; list-style: none; }
  .nav-links a {
    color: var(--text-muted); text-decoration: none;
    font-size: 0.9rem; font-weight: 500; letter-spacing: 0.05em;
    transition: color 0.2s;
    text-transform: uppercase;
  }
  .nav-links a:hover, .nav-links a.active { color: var(--gold); }

  .nav-cta {
    background: var(--gold); color: var(--navy);
    padding: 0.5rem 1.4rem; border: none; border-radius: 2px;
    font-family: 'Rajdhani', sans-serif; font-size: 0.9rem; font-weight: 700;
    letter-spacing: 0.08em; text-transform: uppercase; cursor: pointer;
    text-decoration: none;
    transition: background 0.2s, transform 0.2s;
  }
  .nav-cta:hover { background: var(--gold-light); transform: translateY(-1px); }

  /* ─── HERO ─── */
  #home {
    min-height: 100vh;
    display: flex; align-items: center;
    position: relative; overflow: hidden;
    padding-top: 70px;
  }

  .hero-bg {
    position: absolute; inset: 0;
    background: 
      radial-gradient(ellipse 80% 60% at 70% 50%, rgba(37,64,96,0.5) 0%, transparent 70%),
      linear-gradient(135deg, var(--navy) 0%, var(--navy-mid) 50%, var(--navy) 100%);
  }

  .hero-grid {
    position: absolute; inset: 0; opacity: 0.04;
    background-image: linear-gradient(var(--gold) 1px, transparent 1px),
                      linear-gradient(90deg, var(--gold) 1px, transparent 1px);
    background-size: 60px 60px;
  }

  .hero-accent {
    position: absolute; top: 0; right: 0;
    width: 40vw; height: 100%;
    background: linear-gradient(135deg, transparent 40%, rgba(232,160,32,0.06) 100%);
  }

  .hero-line {
    position: absolute; left: 0; top: 0; bottom: 0;
    width: 5px; background: var(--gold);
  }

  .hero-content {
    position: relative; z-index: 2;
    max-width: 1200px; margin: 0 auto; padding: 0 5vw;
    display: grid; grid-template-columns: 1fr 1fr; gap: 4rem; align-items: center;
  }

  .hero-eyebrow {
    display: inline-flex; align-items: center; gap: 8px;
    color: var(--gold); font-size: 0.75rem; font-weight: 500;
    letter-spacing: 0.2em; text-transform: uppercase;
    margin-bottom: 1.2rem;
  }
  .hero-eyebrow::before {
    content: ''; width: 30px; height: 2px; background: var(--gold);
  }

  .hero-title {
    font-family: 'Rajdhani', sans-serif;
    font-size: clamp(2.8rem, 5vw, 4.5rem);
    font-weight: 700; line-height: 1.05;
    letter-spacing: -0.01em;
    margin-bottom: 1.5rem;
  }
  .hero-title .highlight { color: var(--gold); display: block; }

  .hero-desc {
    color: var(--text-muted); font-size: 1.05rem; line-height: 1.7;
    max-width: 480px; margin-bottom: 2.5rem;
    font-weight: 300;
  }

  .hero-actions { display: flex; gap: 1rem; flex-wrap: wrap; }

  .btn-primary {
    background: var(--gold); color: var(--navy);
    padding: 0.85rem 2rem; border: none; border-radius: 2px;
    font-family: 'Rajdhani', sans-serif; font-size: 0.95rem; font-weight: 700;
    letter-spacing: 0.1em; text-transform: uppercase; cursor: pointer;
    text-decoration: none; display: inline-block;
    transition: all 0.2s;
  }
  .btn-primary:hover { background: var(--gold-light); transform: translateY(-2px); box-shadow: 0 8px 25px rgba(232,160,32,0.3); }

  .btn-outline {
    background: transparent; color: var(--white);
    padding: 0.85rem 2rem; border: 1px solid rgba(255,255,255,0.25); border-radius: 2px;
    font-family: 'Rajdhani', sans-serif; font-size: 0.95rem; font-weight: 600;
    letter-spacing: 0.1em; text-transform: uppercase; cursor: pointer;
    text-decoration: none; display: inline-block;
    transition: all 0.2s;
  }
  .btn-outline:hover { border-color: var(--gold); color: var(--gold); }

  /* Hero stats */
  .hero-stats {
    display: flex; gap: 2rem; margin-top: 3rem; padding-top: 2rem;
    border-top: 1px solid var(--border);
  }
  .stat { text-align: left; }
  .stat-num {
    font-family: 'Rajdhani', sans-serif;
    font-size: 2rem; font-weight: 700; color: var(--gold);
    line-height: 1;
  }
  .stat-label { font-size: 0.75rem; color: var(--text-muted); letter-spacing: 0.08em; text-transform: uppercase; margin-top: 4px; }

  /* Hero visual */
  .hero-visual {
    display: flex; align-items: center; justify-content: center;
    position: relative;
  }

  .shield-container {
    position: relative; width: 320px; height: 320px;
    display: flex; align-items: center; justify-content: center;
  }

  .shield-ring {
    position: absolute; border-radius: 50%;
    border: 1px solid rgba(232,160,32,0.2);
    animation: pulse-ring 3s ease-in-out infinite;
  }
  .shield-ring:nth-child(1) { width: 100%; height: 100%; animation-delay: 0s; }
  .shield-ring:nth-child(2) { width: 80%; height: 80%; animation-delay: 0.5s; }
  .shield-ring:nth-child(3) { width: 60%; height: 60%; animation-delay: 1s; }

  @keyframes pulse-ring {
    0%, 100% { opacity: 0.2; transform: scale(1); }
    50% { opacity: 0.5; transform: scale(1.02); }
  }

  .shield-main {
    position: relative; z-index: 2;
    width: 160px; height: 180px;
    background: linear-gradient(160deg, var(--navy-light) 0%, var(--navy-mid) 100%);
    clip-path: polygon(50% 0%, 100% 20%, 100% 65%, 50% 100%, 0% 65%, 0% 20%);
    display: flex; align-items: center; justify-content: center;
    box-shadow: 0 0 60px rgba(232,160,32,0.25);
  }

  .shield-main::before {
    content: '';
    position: absolute; inset: 3px;
    background: linear-gradient(160deg, var(--navy-mid), var(--navy));
    clip-path: polygon(50% 0%, 100% 20%, 100% 65%, 50% 100%, 0% 65%, 0% 20%);
  }

  .shield-letter {
    position: relative; z-index: 1;
    font-family: 'Rajdhani', sans-serif;
    font-size: 4rem; font-weight: 700; color: var(--gold);
    text-shadow: 0 0 30px rgba(232,160,32,0.5);
  }

  /* Service badges floating */
  .badge {
    position: absolute;
    background: var(--navy-mid);
    border: 1px solid var(--border);
    border-radius: 6px;
    padding: 0.6rem 1rem;
    font-size: 0.75rem; font-weight: 500; letter-spacing: 0.05em;
    text-transform: uppercase; color: var(--text-muted);
    display: flex; align-items: center; gap: 6px;
    white-space: nowrap;
  }
  .badge .dot { width: 6px; height: 6px; border-radius: 50%; background: var(--gold); flex-shrink: 0; }
  .badge-1 { top: 15%; left: -10%; animation: float1 4s ease-in-out infinite; }
  .badge-2 { bottom: 25%; left: -15%; animation: float2 5s ease-in-out infinite; }
  .badge-3 { top: 20%; right: -5%; animation: float3 4.5s ease-in-out infinite; }

  @keyframes float1 { 0%,100%{transform:translateY(0)} 50%{transform:translateY(-8px)} }
  @keyframes float2 { 0%,100%{transform:translateY(0)} 50%{transform:translateY(8px)} }
  @keyframes float3 { 0%,100%{transform:translateY(0)} 50%{transform:translateY(-6px)} }

  /* ─── SECTIONS COMMON ─── */
  section { padding: 100px 5vw; }
  .section-inner { max-width: 1200px; margin: 0 auto; }

  .section-eyebrow {
    display: inline-flex; align-items: center; gap: 8px;
    color: var(--gold); font-size: 0.75rem; font-weight: 500;
    letter-spacing: 0.2em; text-transform: uppercase; margin-bottom: 1rem;
  }
  .section-eyebrow::before { content: ''; width: 20px; height: 2px; background: var(--gold); }

  .section-title {
    font-family: 'Rajdhani', sans-serif;
    font-size: clamp(2rem, 3.5vw, 3rem); font-weight: 700;
    line-height: 1.1; margin-bottom: 1rem;
  }

  .section-desc { color: var(--text-muted); font-size: 1rem; line-height: 1.7; max-width: 560px; font-weight: 300; }

  /* ─── SOBRE NOSOTROS ─── */
  #about { background: var(--navy-mid); }

  .about-grid {
    display: grid; grid-template-columns: 1fr 1fr; gap: 5rem; align-items: center;
  }

  .about-values { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; margin-top: 2.5rem; }

  .value-card {
    background: var(--navy);
    border: 1px solid var(--border);
    border-radius: 4px; padding: 1.2rem;
    transition: border-color 0.3s, transform 0.3s;
  }
  .value-card:hover { border-color: var(--gold); transform: translateY(-3px); }

  .value-icon {
    width: 36px; height: 36px; background: rgba(232,160,32,0.12);
    border-radius: 4px; display: flex; align-items: center; justify-content: center;
    font-size: 1.1rem; margin-bottom: 0.7rem;
  }
  .value-card h4 { font-family: 'Rajdhani', sans-serif; font-size: 1rem; font-weight: 700; margin-bottom: 0.3rem; }
  .value-card p { font-size: 0.82rem; color: var(--text-muted); line-height: 1.5; }

  .about-right { position: relative; }

  .iso-badge {
    background: linear-gradient(135deg, var(--gold) 0%, var(--gold-light) 100%);
    color: var(--navy);
    border-radius: 8px; padding: 2rem;
    text-align: center; margin-bottom: 1.5rem;
    position: relative; overflow: hidden;
  }
  .iso-badge::before {
    content: ''; position: absolute;
    top: -30%; right: -20%; width: 150px; height: 150px;
    border-radius: 50%; background: rgba(255,255,255,0.15);
  }
  .iso-badge .iso-num {
    font-family: 'Rajdhani', sans-serif; font-size: 3rem; font-weight: 700; line-height: 1;
  }
  .iso-badge .iso-sub { font-size: 0.85rem; font-weight: 600; margin-top: 0.3rem; opacity: 0.8; }
  .iso-badge .iso-label { font-size: 0.75rem; margin-top: 0.5rem; opacity: 0.7; text-transform: uppercase; letter-spacing: 0.1em; }

  .about-points { display: flex; flex-direction: column; gap: 0.8rem; }
  .about-point {
    display: flex; align-items: flex-start; gap: 0.75rem;
    padding: 0.9rem 1rem;
    background: var(--navy);
    border-left: 3px solid var(--gold);
    border-radius: 0 4px 4px 0;
  }
  .about-point p { font-size: 0.9rem; color: var(--text-muted); line-height: 1.5; }

  /* ─── SERVICIOS ─── */
  #servicios { background: var(--navy); }

  .servicios-header {
    display: flex; justify-content: space-between; align-items: flex-end;
    margin-bottom: 3.5rem; gap: 2rem;
  }

  .services-grid {
    display: grid; grid-template-columns: repeat(3, 1fr); gap: 1.5px;
    background: var(--border);
    border: 1px solid var(--border);
  }

  .service-card {
    background: var(--navy);
    padding: 2.5rem 2rem;
    position: relative; overflow: hidden;
    cursor: default;
    transition: background 0.3s;
  }
  .service-card:hover { background: var(--navy-mid); }

  .service-card::before {
    content: ''; position: absolute; top: 0; left: 0; right: 0;
    height: 3px; background: var(--gold);
    transform: scaleX(0); transform-origin: left;
    transition: transform 0.4s ease;
  }
  .service-card:hover::before { transform: scaleX(1); }

  .service-num {
    font-family: 'Rajdhani', sans-serif;
    font-size: 4rem; font-weight: 700;
    color: rgba(232,160,32,0.08); line-height: 1;
    position: absolute; top: 1rem; right: 1.5rem;
  }

  .service-icon {
    width: 52px; height: 52px;
    background: rgba(232,160,32,0.1); border: 1px solid var(--border);
    border-radius: 4px; display: flex; align-items: center; justify-content: center;
    font-size: 1.5rem; margin-bottom: 1.5rem;
    transition: background 0.3s, border-color 0.3s;
  }
  .service-card:hover .service-icon { background: rgba(232,160,32,0.2); border-color: var(--gold); }

  .service-card h3 {
    font-family: 'Rajdhani', sans-serif; font-size: 1.3rem; font-weight: 700;
    margin-bottom: 0.8rem; letter-spacing: 0.02em;
  }
  .service-card p { font-size: 0.9rem; color: var(--text-muted); line-height: 1.65; margin-bottom: 1.5rem; }

  .service-features { list-style: none; display: flex; flex-direction: column; gap: 0.45rem; }
  .service-features li {
    display: flex; align-items: flex-start; gap: 0.5rem;
    font-size: 0.82rem; color: var(--text-muted);
  }
  .service-features li::before {
    content: '→'; color: var(--gold); font-size: 0.75rem; flex-shrink: 0; margin-top: 1px;
  }

  .service-link {
    display: inline-flex; align-items: center; gap: 6px;
    margin-top: 1.5rem; color: var(--gold); font-size: 0.8rem;
    font-weight: 600; letter-spacing: 0.1em; text-transform: uppercase;
    text-decoration: none; transition: gap 0.2s;
  }
  .service-link:hover { gap: 10px; }

  /* ─── GALERÍA ─── */
  #galeria { background: var(--navy-mid); }

  .gallery-header { text-align: center; margin-bottom: 3rem; }
  .gallery-header .section-desc { margin: 0 auto; }

  .gallery-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: 200px 200px;
    gap: 6px;
  }

  .gallery-item {
    position: relative; overflow: hidden;
    background: var(--navy-light);
    cursor: pointer;
  }
  .gallery-item:first-child { grid-column: span 2; grid-row: span 2; }

  .gallery-placeholder {
    width: 100%; height: 100%;
    display: flex; flex-direction: column;
    align-items: center; justify-content: center; gap: 0.5rem;
    color: var(--text-muted); font-size: 0.8rem; text-align: center;
    padding: 1rem;
    transition: all 0.3s;
  }
  .gallery-placeholder .g-icon { font-size: 2rem; opacity: 0.4; }
  .gallery-item:hover .gallery-placeholder { background: rgba(232,160,32,0.05); }

  .gallery-overlay {
    position: absolute; inset: 0;
    background: linear-gradient(to top, rgba(13,27,42,0.9) 0%, transparent 60%);
    opacity: 0; transition: opacity 0.3s;
    display: flex; align-items: flex-end; padding: 1.5rem;
  }
  .gallery-item:hover .gallery-overlay { opacity: 1; }
  .gallery-overlay span { font-size: 0.85rem; font-weight: 500; }

  .gallery-note {
    text-align: center; margin-top: 1.5rem;
    font-size: 0.8rem; color: var(--text-muted); font-style: italic;
  }

  /* ─── COTIZACIÓN ─── */
  #cotizacion { background: var(--navy); }

  .cot-grid { display: grid; grid-template-columns: 1fr 1.2fr; gap: 4rem; align-items: start; }

  .cot-info h2 { font-family: 'Rajdhani', sans-serif; font-size: 2.2rem; font-weight: 700; margin-bottom: 1rem; }
  .cot-info p { color: var(--text-muted); line-height: 1.7; margin-bottom: 2rem; font-size: 0.95rem; }

  .cot-features { display: flex; flex-direction: column; gap: 1rem; }
  .cot-feature {
    display: flex; align-items: center; gap: 1rem;
    padding: 1rem 1.2rem;
    background: var(--navy-mid); border-left: 3px solid var(--gold);
  }
  .cot-feature .cf-icon { font-size: 1.2rem; }
  .cot-feature h4 { font-family: 'Rajdhani', sans-serif; font-size: 0.95rem; font-weight: 700; }
  .cot-feature p { font-size: 0.8rem; color: var(--text-muted); margin-top: 2px; }

  /* Form */
  .cot-form {
    background: var(--navy-mid);
    border: 1px solid var(--border);
    padding: 2.5rem;
    border-radius: 4px;
  }
  .form-title {
    font-family: 'Rajdhani', sans-serif; font-size: 1.4rem; font-weight: 700;
    margin-bottom: 0.3rem;
  }
  .form-subtitle { font-size: 0.85rem; color: var(--text-muted); margin-bottom: 1.8rem; }

  .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; }
  .form-group { margin-bottom: 1.2rem; }
  .form-group label { display: block; font-size: 0.78rem; font-weight: 600; letter-spacing: 0.1em; text-transform: uppercase; color: var(--text-muted); margin-bottom: 0.4rem; }
  .form-group input, .form-group select, .form-group textarea {
    width: 100%; background: var(--navy);
    border: 1px solid rgba(255,255,255,0.1); border-radius: 2px;
    color: var(--white); font-family: 'DM Sans', sans-serif; font-size: 0.9rem;
    padding: 0.75rem 1rem; outline: none;
    transition: border-color 0.2s;
  }
  .form-group input:focus, .form-group select:focus, .form-group textarea:focus { border-color: var(--gold); }
  .form-group textarea { resize: vertical; min-height: 100px; }
  .form-group select option { background: var(--navy); }

  .form-submit {
    width: 100%; background: var(--gold); color: var(--navy);
    padding: 1rem; border: none; border-radius: 2px;
    font-family: 'Rajdhani', sans-serif; font-size: 1rem; font-weight: 700;
    letter-spacing: 0.1em; text-transform: uppercase; cursor: pointer;
    transition: all 0.2s; margin-top: 0.5rem;
  }
  .form-submit:hover { background: var(--gold-light); transform: translateY(-1px); }

  .form-success {
    display: none; text-align: center; padding: 2rem;
    color: var(--gold); font-family: 'Rajdhani', sans-serif; font-size: 1.2rem;
  }
  .form-success .success-icon { font-size: 3rem; display: block; margin-bottom: 1rem; }

  /* ─── CONTACTO ─── */
  #contacto { background: var(--navy-mid); }

  .contact-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 4rem; }

  .contact-cards { display: flex; flex-direction: column; gap: 1.5rem; }

  .contact-card {
    background: var(--navy);
    border: 1px solid var(--border);
    border-radius: 4px; padding: 1.8rem;
    position: relative; overflow: hidden;
    transition: border-color 0.3s, transform 0.3s;
  }
  .contact-card:hover { border-color: var(--gold); transform: translateY(-3px); }
  .contact-card::before { content: ''; position: absolute; top: 0; left: 0; width: 4px; height: 100%; background: var(--gold); }

  .contact-card .role { font-size: 0.75rem; letter-spacing: 0.15em; text-transform: uppercase; color: var(--gold); margin-bottom: 0.5rem; }
  .contact-card h3 { font-family: 'Rajdhani', sans-serif; font-size: 1.3rem; font-weight: 700; margin-bottom: 1rem; }
  .contact-card .phones { display: flex; flex-direction: column; gap: 0.4rem; }
  .contact-card .phone { display: flex; align-items: center; gap: 0.6rem; font-size: 0.95rem; color: var(--text-muted); }
  .contact-card .phone span { font-size: 0.9rem; }

  .contact-info { display: flex; flex-direction: column; justify-content: center; }
  .contact-info h2 { font-family: 'Rajdhani', sans-serif; font-size: 2.2rem; font-weight: 700; margin-bottom: 1rem; }
  .contact-info p { color: var(--text-muted); line-height: 1.7; margin-bottom: 2rem; font-size: 0.95rem; }

  .contact-form {
    background: var(--navy);
    border: 1px solid var(--border);
    padding: 2rem; border-radius: 4px;
  }

  /* ─── CLIENTES ─── */
  #clientes { background: var(--navy); padding: 60px 5vw; }

  .clientes-inner { max-width: 1200px; margin: 0 auto; }
  .clientes-label {
    text-align: center; font-size: 0.75rem; letter-spacing: 0.2em; text-transform: uppercase;
    color: var(--text-muted); margin-bottom: 2rem;
  }
  .clientes-row {
    display: flex; justify-content: center; flex-wrap: wrap; gap: 1rem;
  }
  .cliente-chip {
    background: var(--navy-mid); border: 1px solid var(--border);
    padding: 0.7rem 1.5rem; border-radius: 2px;
    font-family: 'Rajdhani', sans-serif; font-size: 0.9rem; font-weight: 600;
    color: var(--text-muted); letter-spacing: 0.08em; text-transform: uppercase;
    transition: all 0.2s;
  }
  .cliente-chip:hover { border-color: var(--gold); color: var(--white); }

  /* ─── FOOTER ─── */
  footer {
    background: var(--navy);
    border-top: 1px solid var(--border);
    padding: 3rem 5vw 2rem;
  }
  .footer-inner { max-width: 1200px; margin: 0 auto; }
  .footer-top { display: grid; grid-template-columns: 2fr 1fr 1fr; gap: 3rem; margin-bottom: 2.5rem; }
  .footer-brand p { color: var(--text-muted); font-size: 0.85rem; line-height: 1.7; margin-top: 0.8rem; max-width: 300px; }
  .footer-col h4 { font-family: 'Rajdhani', sans-serif; font-size: 0.85rem; font-weight: 700; letter-spacing: 0.15em; text-transform: uppercase; color: var(--gold); margin-bottom: 1rem; }
  .footer-col ul { list-style: none; display: flex; flex-direction: column; gap: 0.5rem; }
  .footer-col ul li a { color: var(--text-muted); text-decoration: none; font-size: 0.85rem; transition: color 0.2s; }
  .footer-col ul li a:hover { color: var(--white); }
  .footer-bottom { border-top: 1px solid var(--border); padding-top: 1.5rem; display: flex; justify-content: space-between; align-items: center; }
  .footer-bottom p { font-size: 0.78rem; color: var(--text-muted); }

  /* ─── WHATSAPP ─── */
  .wa-float {
    position: fixed; bottom: 2rem; right: 2rem; z-index: 999;
    display: flex; align-items: center; gap: 0;
    filter: drop-shadow(0 4px 20px rgba(37,211,102,0.3));
  }

  .wa-label {
    background: var(--navy-mid); color: var(--white);
    padding: 0.5rem 1rem; border-radius: 30px 0 0 30px;
    font-size: 0.82rem; font-weight: 500;
    opacity: 0; transform: translateX(10px);
    transition: all 0.3s; pointer-events: none;
    border: 1px solid var(--border); border-right: none;
    white-space: nowrap;
  }
  .wa-float:hover .wa-label { opacity: 1; transform: translateX(0); }

  .wa-btn {
    width: 58px; height: 58px;
    background: #25D366; border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    text-decoration: none; font-size: 1.6rem;
    transition: transform 0.3s;
    flex-shrink: 0;
  }
  .wa-btn:hover { transform: scale(1.1); }
  .wa-pulse {
    position: absolute; right: 0; top: 0;
    width: 58px; height: 58px; border-radius: 50%;
    background: #25D366; opacity: 0.4;
    animation: wa-pulse 2s ease-out infinite;
  }
  @keyframes wa-pulse {
    0% { transform: scale(1); opacity: 0.4; }
    100% { transform: scale(1.6); opacity: 0; }
  }

  /* ─── MOBILE ─── */
  .hamburger { display: none; background: none; border: none; color: var(--white); font-size: 1.5rem; cursor: pointer; }

  @media (max-width: 900px) {
    .hamburger { display: block; }
    .nav-links, .nav-cta { display: none; }
    .hero-content { grid-template-columns: 1fr; }
    .hero-visual { display: none; }
    .about-grid, .cot-grid, .contact-grid { grid-template-columns: 1fr; }
    .services-grid { grid-template-columns: 1fr; }
    .footer-top { grid-template-columns: 1fr; }
    .gallery-grid { grid-template-columns: 1fr 1fr; grid-template-rows: auto; }
    .gallery-item:first-child { grid-column: span 2; }
    .form-row { grid-template-columns: 1fr; }
  }

  /* ─── ANIMATIONS ─── */
  .fade-in {
    opacity: 0; transform: translateY(30px);
    transition: opacity 0.7s ease, transform 0.7s ease;
  }
  .fade-in.visible { opacity: 1; transform: translateY(0); }

  .fade-in-delay-1 { transition-delay: 0.1s; }
  .fade-in-delay-2 { transition-delay: 0.2s; }
  .fade-in-delay-3 { transition-delay: 0.3s; }
</style>
</head>
<body>

<!-- NAV -->
<nav id="navbar">
  <a href="#home" class="nav-logo">
    <div class="logo-icon">M</div>
    GRUPO <span>MOZU</span>
  </a>
  <button class="hamburger">☰</button>
  <ul class="nav-links">
    <li><a href="#home" class="active">Inicio</a></li>
    <li><a href="#about">Nosotros</a></li>
    <li><a href="#servicios">Servicios</a></li>
    <li><a href="#galeria">Galería</a></li>
    <li><a href="#cotizacion">Cotización</a></li>
    <li><a href="#contacto">Contacto</a></li>
  </ul>
  <a href="#cotizacion" class="nav-cta">Cotizar Ahora</a>
</nav>

<!-- HERO -->
<section id="home">
  <div class="hero-bg"></div>
  <div class="hero-grid"></div>
  <div class="hero-accent"></div>
  <div class="hero-line"></div>

  <div class="hero-content">
    <div class="hero-left">
      <div class="hero-eyebrow">Seguridad Privada · Costa Rica</div>
      <h1 class="hero-title">
        Protección Integral
        <span class="highlight">Personas & Activos</span>
      </h1>
      <p class="hero-desc">Soluciones profesionales de seguridad que combinan personal altamente capacitado, tecnología digital avanzada y procesos estandarizados.</p>
      <div class="hero-actions">
        <a href="#servicios" class="btn-primary">Ver Servicios</a>
        <a href="#cotizacion" class="btn-outline">Solicitar Cotización</a>
      </div>
      <div class="hero-stats">
        <div class="stat"><div class="stat-num">24/7</div><div class="stat-label">Monitoreo</div></div>
        <div class="stat"><div class="stat-num">3+</div><div class="stat-label">Servicios</div></div>
        <div class="stat"><div class="stat-num">ISO</div><div class="stat-label">18788 En Proceso</div></div>
      </div>
    </div>

    <div class="hero-visual">
      <div class="shield-container">
        <div class="shield-ring"></div>
        <div class="shield-ring"></div>
        <div class="shield-ring"></div>
        <div class="shield-main"><span class="shield-letter">M</span></div>
        <div class="badge badge-1"><div class="dot"></div> Seguridad Física</div>
        <div class="badge badge-2"><div class="dot"></div> Plataforma MOZUsafe</div>
        <div class="badge badge-3"><div class="dot"></div> CCTV 24/7</div>
      </div>
    </div>
  </div>
</section>

<!-- CLIENTES STRIP -->
<section id="clientes" style="padding: 50px 5vw;">
  <div class="clientes-inner">
    <div class="clientes-label">Empresas que confían en nosotros</div>
    <div class="clientes-row">
      <div class="cliente-chip">AVIN Nutrición Animal</div>
      <div class="cliente-chip">Pollos Pako</div>
      <div class="cliente-chip">ADIFORT La Fortuna</div>
      <div class="cliente-chip">Místico Park</div>
    </div>
  </div>
</section>

<!-- SOBRE NOSOTROS -->
<section id="about">
  <div class="section-inner">
    <div class="about-grid">
      <div>
        <div class="section-eyebrow fade-in">Nuestra Empresa</div>
        <h2 class="section-title fade-in fade-in-delay-1">Construyendo entornos más seguros en Costa Rica</h2>
        <p class="section-desc fade-in fade-in-delay-2">Somos una empresa costarricense especializada en seguridad privada. Nuestro enfoque integra personal capacitado, tecnología de control y procesos estandarizados para ofrecer un servicio confiable y eficiente.</p>
        <div class="about-values fade-in fade-in-delay-3">
          <div class="value-card">
            <div class="value-icon">🤝</div>
            <h4>Confianza</h4>
            <p>Relaciones basadas en transparencia y cumplimiento de compromisos.</p>
          </div>
          <div class="value-card">
            <div class="value-icon">⚡</div>
            <h4>Tecnología</h4>
            <p>Innovación constante para maximizar la eficiencia operativa.</p>
          </div>
          <div class="value-card">
            <div class="value-icon">🛡️</div>
            <h4>Protección</h4>
            <p>Nuestra misión: resguardar personas, activos e infraestructura.</p>
          </div>
          <div class="value-card">
            <div class="value-icon">📋</div>
            <h4>Excelencia</h4>
            <p>Procesos estandarizados y mejora continua en cada operación.</p>
          </div>
        </div>
      </div>
      <div class="about-right fade-in fade-in-delay-2">
        <div class="iso-badge">
          <div class="iso-num">ISO 18788</div>
          <div class="iso-sub">:2015</div>
          <div class="iso-label">En proceso de certificación</div>
        </div>
        <div class="about-points">
          <div class="about-point">
            <p>Sistema de gestión con enfoque en riesgos, legalidad y derechos humanos.</p>
          </div>
          <div class="about-point">
            <p>Garantizamos la competencia ética y profesional del personal operativo.</p>
          </div>
          <div class="about-point">
            <p>Transparencia, responsabilidad social y confianza con nuestros clientes.</p>
          </div>
          <div class="about-point">
            <p>Mejora continua en planificación, operación y control de servicios.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- SERVICIOS -->
<section id="servicios">
  <div class="section-inner">
    <div class="servicios-header">
      <div>
        <div class="section-eyebrow">Lo que ofrecemos</div>
        <h2 class="section-title">Nuestros Servicios</h2>
      </div>
      <p class="section-desc" style="max-width:380px">Tres ejes fundamentales diseñados para ofrecer protección integral, eficiente y tecnológicamente avanzada.</p>
    </div>

    <div class="services-grid">
      <div class="service-card fade-in">
        <div class="service-num">01</div>
        <div class="service-icon">🛡️</div>
        <h3>Seguridad Física Presencial</h3>
        <p>Oficiales de seguridad altamente capacitados para la protección activa de instalaciones, personas y bienes con protocolos estrictos.</p>
        <ul class="service-features">
          <li>Control de accesos peatonales y vehiculares</li>
          <li>Rondas de vigilancia y supervisión perimetral</li>
          <li>Inspección de bultos, paquetes y vehículos</li>
          <li>Control de visitantes y proveedores</li>
          <li>Atención de emergencias y evacuaciones</li>
          <li>Reporte inmediato de incidencias</li>
        </ul>
        <a href="#cotizacion" class="service-link">Solicitar servicio →</a>
      </div>

      <div class="service-card fade-in fade-in-delay-1">
        <div class="service-num">02</div>
        <div class="service-icon">📱</div>
        <h3>Plataforma MOZUsafe</h3>
        <p>Nuestra app digital para gestión y trazabilidad de operaciones de vigilancia en tiempo real con panel de indicadores clave.</p>
        <ul class="service-features">
          <li>Registro de ingreso y salida de camiones</li>
          <li>Escaneo de códigos QR y tecnología NFC</li>
          <li>Alertas automáticas por tiempos excesivos</li>
          <li>Bitácora digital tipo chat con historial</li>
          <li>Panel KPI con indicadores de rendimiento</li>
          <li>Exportación de datos en PDF y Excel</li>
        </ul>
        <a href="#cotizacion" class="service-link">Solicitar servicio →</a>
      </div>

      <div class="service-card fade-in fade-in-delay-2">
        <div class="service-num">03</div>
        <div class="service-icon">📹</div>
        <h3>Sistemas de Videovigilancia</h3>
        <p>Diseño, instalación y mantenimiento de sistemas CCTV con tecnología de última generación adaptados a cada cliente.</p>
        <ul class="service-features">
          <li>Cámaras analógicas, IP y térmicas</li>
          <li>Diseño de circuitos CCTV a medida</li>
          <li>Monitoreo remoto 24/7</li>
          <li>Integración con alarmas y sensores</li>
          <li>Mantenimiento preventivo y correctivo</li>
        </ul>
        <a href="#cotizacion" class="service-link">Solicitar servicio →</a>
      </div>
    </div>
  </div>
</section>

<!-- GALERÍA -->
<section id="galeria">
  <div class="section-inner">
    <div class="gallery-header">
      <div class="section-eyebrow" style="justify-content:center">Nuestro Trabajo</div>
      <h2 class="section-title">Galería</h2>
      <p class="section-desc">Instalaciones, equipos y operaciones de nuestros proyectos en todo Costa Rica.</p>
    </div>
    <div class="gallery-grid">
      <div class="gallery-item">
        <div class="gallery-placeholder">
          <span class="g-icon">📷</span>
          <strong>Foto Principal</strong>
          <span>Control de acceso – instalación destacada</span>
        </div>
        <div class="gallery-overlay"><span>Control de Acceso</span></div>
      </div>
      <div class="gallery-item">
        <div class="gallery-placeholder"><span class="g-icon">🎥</span><span>Cámaras IP instaladas</span></div>
        <div class="gallery-overlay"><span>Sistema CCTV</span></div>
      </div>
      <div class="gallery-item">
        <div class="gallery-placeholder"><span class="g-icon">👮</span><span>Personal en operación</span></div>
        <div class="gallery-overlay"><span>Equipo de Seguridad</span></div>
      </div>
      <div class="gallery-item">
        <div class="gallery-placeholder"><span class="g-icon">📱</span><span>App MOZUsafe en uso</span></div>
        <div class="gallery-overlay"><span>Plataforma MOZUsafe</span></div>
      </div>
      <div class="gallery-item">
        <div class="gallery-placeholder"><span class="g-icon">🏭</span><span>Instalación industrial</span></div>
        <div class="gallery-overlay"><span>Protección Industrial</span></div>
      </div>
    </div>
    <p class="gallery-note">Reemplace los marcadores con fotografías reales de sus instalaciones y operaciones.</p>
  </div>
</section>

<!-- COTIZACIÓN -->
<section id="cotizacion">
  <div class="section-inner">
    <div class="cot-grid">
      <div class="cot-info fade-in">
        <div class="section-eyebrow">Sin costo</div>
        <h2>Solicite su Cotización</h2>
        <p>Evaluamos sus necesidades de seguridad de manera gratuita y le presentamos una propuesta personalizada, sin compromisos.</p>
        <div class="cot-features">
          <div class="cot-feature">
            <span class="cf-icon">⚡</span>
            <div><h4>Respuesta Rápida</h4><p>Le contactamos en menos de 24 horas.</p></div>
          </div>
          <div class="cot-feature">
            <span class="cf-icon">🎯</span>
            <div><h4>Propuesta Personalizada</h4><p>Adaptada exactamente a sus instalaciones y presupuesto.</p></div>
          </div>
          <div class="cot-feature">
            <span class="cf-icon">🔒</span>
            <div><h4>Sin Compromiso</h4><p>Evaluación gratuita, sin presión de contratación.</p></div>
          </div>
        </div>
      </div>

      <div class="cot-form fade-in fade-in-delay-1">
        <h3 class="form-title">Formulario de Cotización</h3>
        <p class="form-subtitle">Complete los datos y nos comunicamos a la brevedad.</p>
        <form id="cotForm">
          <div class="form-row">
            <div class="form-group">
              <label>Nombre *</label>
              <input type="text" placeholder="Su nombre completo" required>
            </div>
            <div class="form-group">
              <label>Empresa</label>
              <input type="text" placeholder="Nombre de la empresa">
            </div>
          </div>
          <div class="form-row">
            <div class="form-group">
              <label>Teléfono *</label>
              <input type="tel" placeholder="8888-0000" required>
            </div>
            <div class="form-group">
              <label>Correo electrónico</label>
              <input type="email" placeholder="correo@empresa.com">
            </div>
          </div>
          <div class="form-group">
            <label>Servicio de interés *</label>
            <select required>
              <option value="">Seleccione un servicio...</option>
              <option>Seguridad Física Presencial</option>
              <option>Plataforma MOZUsafe</option>
              <option>Sistemas de Videovigilancia CCTV</option>
              <option>Paquete integral (todos los servicios)</option>
            </select>
          </div>
          <div class="form-group">
            <label>Ubicación / Descripción</label>
            <textarea placeholder="Describa brevemente sus instalaciones, cantidad de accesos, área a cubrir, horarios, etc."></textarea>
          </div>
          <button type="submit" class="form-submit">Solicitar Cotización Gratuita</button>
        </form>
        <div class="form-success" id="formSuccess">
          <span class="success-icon">✅</span>
          ¡Mensaje recibido!<br>
          <span style="font-size:0.9rem;color:var(--text-muted);font-family:'DM Sans',sans-serif">Le contactaremos en menos de 24 horas.</span>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACTO -->
<section id="contacto">
  <div class="section-inner">
    <div class="contact-grid">
      <div class="contact-cards fade-in">
        <div class="section-eyebrow">Hable con nosotros</div>
        <h2 class="section-title" style="margin-bottom:1.5rem">Contacto Directo</h2>
        <div class="contact-card">
          <div class="role">Administrador de Proyectos</div>
          <h3>Cristopher Morales Zúñiga</h3>
          <div class="phones">
            <div class="phone">📞 <span>6232-7333</span></div>
            <div class="phone">📞 <span>6410-1209</span></div>
          </div>
        </div>
        <div class="contact-card">
          <div class="role">Jefe de Operaciones</div>
          <h3>Marcos Morales Garbanzo</h3>
          <div class="phones">
            <div class="phone">📞 <span>6469-5098</span></div>
          </div>
        </div>
        <div style="margin-top:1rem;padding:1.2rem;background:rgba(37,211,102,0.08);border:1px solid rgba(37,211,102,0.2);border-radius:4px;display:flex;align-items:center;gap:0.8rem">
          <span style="font-size:1.4rem">💬</span>
          <div>
            <div style="font-family:'Rajdhani',sans-serif;font-weight:700;font-size:0.95rem">WhatsApp Disponible</div>
            <div style="font-size:0.8rem;color:var(--text-muted)">Respuesta rápida por mensaje directo</div>
          </div>
        </div>
      </div>

      <div class="contact-info fade-in fade-in-delay-1">
        <div class="contact-form">
          <h3 class="form-title" style="margin-bottom:0.3rem">Envíenos un Mensaje</h3>
          <p class="form-subtitle">Para consultas generales o información adicional.</p>
          <form id="contactForm">
            <div class="form-group">
              <label>Nombre *</label>
              <input type="text" placeholder="Su nombre" required>
            </div>
            <div class="form-group">
              <label>Teléfono / Correo *</label>
              <input type="text" placeholder="Cómo podemos contactarle" required>
            </div>
            <div class="form-group">
              <label>Mensaje *</label>
              <textarea placeholder="¿En qué podemos ayudarle?" required></textarea>
            </div>
            <button type="submit" class="form-submit">Enviar Mensaje</button>
          </form>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-inner">
    <div class="footer-top">
      <div class="footer-brand">
        <a href="#home" class="nav-logo" style="font-size:1.3rem">
          <div class="logo-icon" style="width:30px;height:30px;font-size:0.85rem">M</div>
          GRUPO <span>MOZU</span> S.A.
        </a>
        <p>Soluciones integrales en seguridad privada. Protegemos personas, activos e infraestructura empresarial en todo Costa Rica.</p>
      </div>
      <div class="footer-col">
        <h4>Servicios</h4>
        <ul>
          <li><a href="#servicios">Seguridad Física</a></li>
          <li><a href="#servicios">Plataforma MOZUsafe</a></li>
          <li><a href="#servicios">Videovigilancia CCTV</a></li>
        </ul>
      </div>
      <div class="footer-col">
        <h4>Empresa</h4>
        <ul>
          <li><a href="#about">Quiénes Somos</a></li>
          <li><a href="#galeria">Galería</a></li>
          <li><a href="#cotizacion">Cotización</a></li>
          <li><a href="#contacto">Contacto</a></li>
        </ul>
      </div>
    </div>
    <div class="footer-bottom">
      <p>© 2025 Grupo Mozu S.A. · Costa Rica · Todos los derechos reservados.</p>
      <p style="color:var(--gold);font-family:'Rajdhani',sans-serif;font-size:0.8rem;letter-spacing:0.1em">PROTECCIÓN · TECNOLOGÍA · CONFIANZA</p>
    </div>
  </div>
</footer>

<!-- WHATSAPP FLOAT -->
<div class="wa-float">
  <div class="wa-pulse"></div>
  <div class="wa-label">¿Necesita seguridad?</div>
  <a href="https://wa.me/50662327333?text=Hola%2C%20me%20interesa%20información%20sobre%20sus%20servicios%20de%20seguridad." class="wa-btn" target="_blank" title="Contactar por WhatsApp">💬</a>
</div>

<script>
  // Nav scroll effect
  const navbar = document.getElementById('navbar');
  window.addEventListener('scroll', () => {
    navbar.classList.toggle('scrolled', window.scrollY > 50);
    // Active link
    const sections = document.querySelectorAll('section[id]');
    const links = document.querySelectorAll('.nav-links a');
    let current = '';
    sections.forEach(s => { if (window.scrollY >= s.offsetTop - 100) current = s.id; });
    links.forEach(l => { l.classList.toggle('active', l.getAttribute('href') === '#' + current); });
  });

  // Intersection observer for fade-in
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(e => { if (e.isIntersecting) { e.target.classList.add('visible'); } });
  }, { threshold: 0.15 });
  document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));

  // Form submissions
  document.getElementById('cotForm').addEventListener('submit', function(e) {
    e.preventDefault();
    this.style.display = 'none';
    document.getElementById('formSuccess').style.display = 'block';
  });

  document.getElementById('contactForm').addEventListener('submit', function(e) {
    e.preventDefault();
    this.innerHTML = '<div style="text-align:center;padding:2rem;color:var(--gold);font-family:Rajdhani,sans-serif;font-size:1.1rem">✅ Mensaje enviado.<br><span style="font-size:0.85rem;color:var(--text-muted);font-family:DM Sans,sans-serif">Nos comunicaremos pronto.</span></div>';
  });
</script>
</body>
</html>
