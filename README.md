<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mi Perfil</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet"/>
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: 'DM Sans', sans-serif;
      background: #0e0e0e;
      color: #f0ece4;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 2rem;
    }

    .card {
      background: #161616;
      border: 1px solid #2a2a2a;
      border-radius: 20px;
      max-width: 480px;
      width: 100%;
      overflow: hidden;
      position: relative;
      animation: fadeUp 0.8s ease both;
    }

    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(30px); }
      to   { opacity: 1; transform: translateY(0); }
    }

    .banner {
      height: 120px;
      background: linear-gradient(135deg, #c8a96e 0%, #8b5e2a 50%, #3d2b10 100%);
      position: relative;
    }

    .banner::after {
      content: '';
      position: absolute;
      inset: 0;
      background: repeating-linear-gradient(
        45deg,
        transparent,
        transparent 10px,
        rgba(255,255,255,0.03) 10px,
        rgba(255,255,255,0.03) 20px
      );
    }

    .avatar-wrap {
      position: absolute;
      bottom: -50px;
      left: 50%;
      transform: translateX(-50%);
      z-index: 2;
    }

    .avatar {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      border: 4px solid #161616;
      background: linear-gradient(135deg, #c8a96e, #8b5e2a);
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Playfair Display', serif;
      font-size: 2.2rem;
      color: #161616;
      font-weight: 700;
      letter-spacing: -1px;
    }

    .body {
      padding: 4rem 2rem 2rem;
      text-align: center;
    }

    .tag {
      display: inline-block;
      font-size: 11px;
      font-weight: 500;
      letter-spacing: 3px;
      text-transform: uppercase;
      color: #c8a96e;
      margin-bottom: 0.75rem;
      opacity: 0;
      animation: fadeUp 0.6s 0.3s ease forwards;
    }

    .name {
      font-family: 'Playfair Display', serif;
      font-size: 2rem;
      font-weight: 700;
      color: #f0ece4;
      line-height: 1.2;
      margin-bottom: 0.5rem;
      opacity: 0;
      animation: fadeUp 0.6s 0.4s ease forwards;
    }

    .role {
      font-size: 0.9rem;
      color: #888;
      font-weight: 300;
      margin-bottom: 1.5rem;
      opacity: 0;
      animation: fadeUp 0.6s 0.5s ease forwards;
    }

    .divider {
      width: 40px;
      height: 2px;
      background: #c8a96e;
      margin: 0 auto 1.5rem;
      opacity: 0;
      animation: fadeUp 0.6s 0.55s ease forwards;
    }

    .bio {
      font-size: 0.95rem;
      line-height: 1.8;
      color: #aaa;
      font-weight: 300;
      margin-bottom: 2rem;
      opacity: 0;
      animation: fadeUp 0.6s 0.6s ease forwards;
    }

    .stats {
      display: flex;
      justify-content: center;
      gap: 2rem;
      margin-bottom: 2rem;
      opacity: 0;
      animation: fadeUp 0.6s 0.7s ease forwards;
    }

    .stat { text-align: center; }

    .stat-num {
      font-family: 'Playfair Display', serif;
      font-size: 1.5rem;
      color: #c8a96e;
      display: block;
    }

    .stat-label {
      font-size: 11px;
      letter-spacing: 2px;
      text-transform: uppercase;
      color: #555;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      justify-content: center;
      margin-bottom: 2rem;
      opacity: 0;
      animation: fadeUp 0.6s 0.75s ease forwards;
    }

    .skill {
      font-size: 12px;
      font-weight: 500;
      padding: 6px 14px;
      border-radius: 100px;
      border: 1px solid #2a2a2a;
      color: #999;
      letter-spacing: 0.5px;
      transition: all 0.2s;
      cursor: default;
    }

    .skill:hover { border-color: #c8a96e; color: #c8a96e; }

    .btn {
      display: inline-block;
      padding: 12px 32px;
      background: #c8a96e;
      color: #0e0e0e;
      font-family: 'DM Sans', sans-serif;
      font-size: 13px;
      font-weight: 500;
      letter-spacing: 1px;
      text-transform: uppercase;
      border-radius: 100px;
      border: none;
      cursor: pointer;
      text-decoration: none;
      transition: opacity 0.2s, transform 0.15s;
      opacity: 0;
      animation: fadeUp 0.6s 0.85s ease forwards;
    }

    .btn:hover { opacity: 0.85; transform: scale(0.98); }
  </style>
</head>
<body>
  <div class="card">
    <div class="banner">
      <div class="avatar-wrap">
        <div class="avatar">MP</div>
      </div>
    </div>
    <div class="body">
      <span class="tag">Bienvenido</span>
      <h1 class="name">Este es mi perfil</h1>
      <p class="role">Diseñador · Desarrollador · Creador</p>
      <div class="divider"></div>
      <p class="bio">
        Hola, soy una persona apasionada por crear cosas únicas y con propósito.
        Me dedico a transformar ideas en experiencias que inspiran y conectan con las personas.
      </p>
      <div class="stats">
        <div class="stat">
          <span class="stat-num">3+</span>
          <span class="stat-label">Años exp.</span>
        </div>
        <div class="stat">
          <span class="stat-num">48</span>
          <span class="stat-label">Proyectos</span>
        </div>
        <div class="stat">
          <span class="stat-num">12</span>
          <span class="stat-label">Clientes</span>
        </div>
      </div>
      <div class="skills">
        <span class="skill">Diseño UI</span>
        <span class="skill">HTML & CSS</span>
        <span class="skill">JavaScript</span>
        <span class="skill">Fotografía</span>
        <span class="skill">Branding</span>
      </div>
      <a href="#" class="btn">Contáctame</a>
    </div>
  </div>
</body>
</html>
