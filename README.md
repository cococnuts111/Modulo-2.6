z;
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
