<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Historia del Internet</title>
  <!-- Tipografía -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --sky: #87CEEB; 
      --dark: #0f1724;
      --muted: #6b7280;
      --bg: #ffffff;
      --card: #f8fbff;
      --accent: #0366d6;
      font-family: 'Poppins', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing: border-box}
    body{
      margin:0;
      background:var(--bg);
      color:var(--dark);
      line-height:1.6;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
    }
    header{
      background: linear-gradient(135deg, rgba(135,206,235,0.18), rgba(3,102,214,0.06));
      padding:48px 20px;
      text-align:center;
      border-bottom:1px solid rgba(3,102,214,0.06);
    }
    .container{max-width:1000px;margin:0 auto;padding:24px}
    h1{font-size:2.4rem;margin:0 0 8px;color:var(--dark)}
    .subtitle{color:var(--muted);margin-bottom:18px}

    .hero-row{display:flex;gap:24px;align-items:center;justify-content:center;flex-wrap:wrap}
    .hero-card{background:var(--card);padding:16px;border-radius:14px;box-shadow:0 6px 20px rgba(3,102,214,0.06);max-width:540px}
    .hero-card img{width:100%;height:220px;object-fit:cover;border-radius:10px}

    nav{display:flex;gap:8px;justify-content:center;flex-wrap:wrap;margin-top:18px}
    nav a{padding:8px 14px;border-radius:999px;text-decoration:none;color:var(--accent);border:1px solid rgba(3,102,214,0.1);font-weight:600}

    /* Timeline */
    .timeline{margin-top:36px}
    .timeline-item{display:grid;grid-template-columns:120px 1fr;gap:16px;padding:18px 12px;border-radius:12px;background:#fff;margin-bottom:12px;border:1px solid rgba(0,0,0,0.04)}
    .timeline-year{font-weight:700;color:var(--accent);font-size:1.05rem}
    .timeline-content h3{margin:0 0 6px}
    .timeline-content p{margin:0;color:var(--muted)}

    /* grid for sections */
    .grid{display:grid;grid-template-columns:repeat(2,1fr);gap:20px;margin-top:28px}
    .card{background:#fff;padding:18px;border-radius:12px;border:1px solid rgba(0,0,0,0.04)}
    .figure{display:flex;gap:12px;align-items:center}
    .figure img{width:84px;height:84px;object-fit:cover;border-radius:8px}

    footer{margin-top:25px;padding:15px 0;text-align:center;color:var(--muted);font-size:0.9rem}

    /* Responsive */
    @media (max-width:800px){
      .grid{grid-template-columns:1fr}
      .timeline-item{grid-template-columns:1fr}
      .timeline-year{order:-1}
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <h1>La historia del Internet</h1>
      <p class="subtitle">Como bien sabemos el internet a lo largo de los años ha tenido una evolucion impresionante; y haz llegado al lugar correcto para llenarte de informacion.</p>

      <div class="hero-row">
        <div class="hero-card">
          <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Red de computadoras">
          <p style="margin-top:8px">¿Que es el ineternet?</p> 
          <p style="margin-top:10px">Internet es la red que conecta e interrelaciona dispositivos electrónicos y redes de computadoras entre sí, de todo el mundo. Su nombre proviene del inglés International Network que significa “Red Internacional” y el acrónimo de esas palabras dio origen al nombre internet.</p>

        </div>
      </div>

      <nav aria-label="Navegación principal">
        <a href="#timeline">Línea del tiempo</a>
        <a href="#personajes">Personas destacadas</a>
        <a href="#impacto">Impacto</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section id="timeline" class="timeline">
      <h2>Evolucion del Internet</h2>

      <article class="timeline-item">
        <div class="timeline-year">1960</div>
        <div class="timeline-content">
          <h3>Proyecto DARPA</h3>
          <p>El Departemento de Defensa de los Estados Unidos diseño este proyecto para evitar fallas en las redes de comunicacion. Conectaban varias computadoras y si alguna fallaba hacer que las otras siguieran funcionando.</p>
        </div>
      </article>

      <article class="timeline-item">
        <div class="timeline-year">1965</div>
        <div class="timeline-content">
          <h3>Primeros Enlaces de Datos</h3>
          <p>Realizan los primeros enlaces de datos entre redes de varias universidades y laboratorios de Estados Unidos por medio de las lienas telefonicas el proyecto DARPA se denomino ARPANET tambien se creo el protocolo TCP/IP.</p>
        </div>
      </article>

 <article class="timeline-item">
        <div class="timeline-year">1971</div>
        <div class="timeline-content">
          <h3>Se mando el primer Email</h3>
          <p>Se invento y se envio el primer Email o cooreo electronico que decia algo asi como QWERTYIOP.</p>
        </div>
      </article>

      <article class="timeline-item">
        <div class="timeline-year">1988</div>
        <div class="timeline-content">
          <h3>Se crearon las primeras APPS que usaron Internet.</h3>
          <p>Usaban el internet para comjunicarse, asi msimo aparecio el primer chat llamado "MIR", se creo el primer virus de la historia llamado "GUSANO MORRIS" y ademas se desarrollo el primer buscador llamado "ARCHIE FINDER".</p>
        </div>
      </article>

      <article class="timeline-item">
        <div class="timeline-year">1989–1991</div>
        <div class="timeline-content">
          <h3>La World Wide Web</h3>
          <p>Tim Berners-Lee inventa la World Wide Web (WWW) y el primer navegador/servidor web en el CERN, lo que facilita el acceso a información mediante hipervínculos.</p>
        </div>
      </article>

      <article class="timeline-item">
        <div class="timeline-year">1993–2000</div>
        <div class="timeline-content">
          <h3>Expansión comercial y navegadores</h3>
          <p>Los navegadores gráficos (por ejemplo, Mosaic y luego Netscape) y el acceso comercial popularizan Internet para el público general.</p>
        </div>
      </article>

      <article class="timeline-item">
        <div class="timeline-year">2000–presente</div>
        <div class="timeline-content">
          <h3>Web 2.0 y más allá</h3>
          <p>Surge la web interactiva, redes sociales, streaming y grandes plataformas que transforman la comunicación, la economía y la cultura global.</p>
        </div>
      </article>
    </section>

    <section id="personas destacadas" class="grid">
      <div class="card">
        <h2>Personas destacadas</h2>
        <div class="figure" style="margin-top:12px">
          <img src=1.jpeg>
          <div>
            <h3>Tim Berners-Lee</h3>
            <p class="muted">Inventor de la World Wide Web; propuso HTTP, HTML y los primeros servidores y navegadores.</p>
          </div>
        </div>

        <div class="figure" style="margin-top:12px">
          <img src=2.jpg>
          <div>
            <h3>Vinton Cerf</h3>
            <p class="muted">Conocido como uno de los "padres del Internet" por su trabajo en el diseño del TCP/IP.</p>
          </div>
        </div>
      </div>

      <div class="card">
        <h2>Impacto y transformaciones</h2>
        <p>Internet cambió cómo compartimos información, cómo hacemos negocios, enseñamos y nos relacionamos. Entre los efectos claves están:</p>
        <ul>
          <li>Globalización de la comunicación</li>
          <li>Economía digital y nuevas industrias</li>
          <li>Acceso masivo a la información</li>
          <li>Retos: privacidad, desinformación y brecha digital</li>
        </ul>
      </div>
    </section>

    <footer>
      <p>Diseñado para fines educativos (Atziri Paola & Edgar Humberto). &copy; <span id="year"></span> Historia del Internet</p>
    </footer>
  </main>

  <script>
    // Añade el año actual al pie
    document.getElementById('year').textContent = new Date().getFullYear();

    // Scroll suave para navegación interna
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click', e=>{
        e.preventDefault();
        const id = a.getAttribute('href').slice(1);
        const el = document.getElementById(id);
        if(el) el.scrollIntoView({behavior:'smooth', block:'start'});
      })
    })
  </script>
</body>
</html>
