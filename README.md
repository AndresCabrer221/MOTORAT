#MOTORAT
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>El Gallo Mas Gallo</title>
  <meta name="description" content="El Gallo Mas Gallo — Productos y marcas. Compare y compruebe." />
  <style>
    /* Reset simple */
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; line-height: 1.4; color:#222; background:#fff; }
    a { color: inherit; text-decoration: none; }

    /* Layout */
    header { background: #fff; border-bottom: 1px solid #eee; position: sticky; top:0; z-index: 60; }
    .container { max-width:1100px; margin:0 auto; padding: 18px; }

    /* Nav */
    .nav { display:flex; align-items:center; justify-content:space-between; gap:12px; }
    .brand { font-weight:700; font-size:1.15rem; }
    nav ul { display:flex; gap:14px; list-style:none; align-items:center; }
    nav li { font-weight:600; font-size:0.95rem; }

    /* Hero */
    .hero { display:flex; gap:30px; align-items:center; padding:48px 18px; background: linear-gradient(180deg, #fff 0%, #fff 100%); }
    .hero-left { flex:1; }
    .logo-big { font-size:2rem; font-weight:800; letter-spacing:0.02em; margin-bottom:8px; }
    .tag { font-size:1.1rem; color:#666; margin-bottom:16px; }
    .ctas { display:flex; gap:12px; flex-wrap:wrap; }
    .btn { padding:10px 16px; border-radius:8px; font-weight:700; cursor:pointer; border: none; }
    .btn-primary { background:#e74c3c; color:#fff; }
    .btn-outline { background:transparent; border:2px solid #e74c3c; color:#e74c3c; }

    .hero-right { width:320px; text-align:center; }
    .hero-right img { max-width:100%; border-radius:12px; box-shadow: 0 6px 18px rgba(0,0,0,0.08); }

    /* Section */
    .section { padding:36px 18px; border-top:1px dashed #eee; }
    .section h2 { font-size:1.25rem; margin-bottom:10px; }
    .muted { color:#666; margin-bottom:12px; }

    /* Products link panel */
    .panel { display:flex; gap:16px; flex-wrap:wrap; }
    .card { flex:1 1 220px; border:1px solid #f0f0f0; padding:16px; border-radius:10px; background:#fff; box-shadow: 0 4px 12px rgba(0,0,0,0.02); }

    /* Footer / cookie */
    footer { padding:20px 18px; background:#fafafa; border-top:1px solid #eee; }
    .copyright { color:#555; font-size:0.95rem; }

    /* Cookie bar */
    .cookie { position:fixed; right:18px; bottom:18px; background:#fff; border:1px solid #ddd; padding:12px 14px; border-radius:10px; box-shadow:0 6px 20px rgba(0,0,0,0.06); display:flex; gap:12px; align-items:center; z-index:999; }
    .cookie button { cursor:pointer; border-radius:8px; padding:8px 10px; border:none; font-weight:700; }

    @media (max-width:800px){
      .hero { flex-direction:column; text-align:center; }
      .hero-right { width:100%; }
      nav ul { display:none; }
    }
  </style>
</head>
<body>

  <header>
    <div class="container nav">
      <div class="brand">El Gallo Mas Gallo</div>
      <nav>
        <ul>
          <li><a href="#inicio">INICIO</a></li>
          <li><a href="#productos">PRODUCTOS</a></li>
          <li><a href="#marcas">MARCAS</a></li>
          <li><a href="#blog">BLOG</a></li>
          <li><a href="#contacto">CONTACTANOS</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main>
    <!-- HERO -->
    <section class="hero container" id="inicio">
      <div class="hero-left">
        <div class="logo-big">El Gallo mas Gallo</div>
        <div class="tag">Agitandolo Todo — <small>-Founded 1971-</small></div>
        <p class="muted">¡Compare y Compruebe! Las mejores ofertas y promociones. Consulta sobre flexi cuotas y obtén los mejores precios.</p>
        <div class="ctas">
          <a class="btn btn-primary" href="#productos">Ir a los Productos</a>
          <a class="btn btn-outline" href="#contacto">Solicita tu Credito</a>
        </div>
      </div>

      <div class="hero-right">
        <!-- Reemplaza el src con la URL real de la imagen del sitio -->
        <img src="https://via.placeholder.com/320x220?text=El+Gallo+Mas+Gallo" alt="El Gallo Mas Gallo — imagen">
        <p style="margin-top:8px;color:#777;font-size:0.9rem;">Derechos Reservado a Anthony Estrada</p>
      </div>
    </section>

    <!-- Flexi cuotas -->
    <section class="section container">
      <h2>Las Flexi Cuotas Llegaron Para Quedarse</h2>
      <p class="muted">Consulta sobre ellas y obten los mejores precios y las mejores promociones. Solicita tu Crédito con Flexi Cuotas.</p>

      <div class="panel" style="margin-top:14px;">
        <div class="card">
          <h3 style="margin-bottom:6px;">Productos</h3>
          <p class="muted">Explora nuestra selección de productos destacados.</p>
          <p><a href="#productos">Ir a los Productos →</a></p>
        </div>

        <div class="card">
          <h3 style="margin-bottom:6px;">Marcas</h3>
          <p class="muted">Las mejores marcas nacionales e internacionales.</p>
          <p><a href="#marcas">Ver Marcas →</a></p>
        </div>

        <div class="card">
          <h3 style="margin-bottom:6px;">Blog</h3>
          <p class="muted">Artículos, novedades y promociones.</p>
          <p><a href="#blog">Leer el Blog →</a></p>
        </div>
      </div>
    </section>

    <!-- Contacto sencillo -->
    <section class="section container" id="contacto">
      <h2>Contáctanos</h2>
      <p class="muted">¿Preguntas sobre precios o financiamiento? Envíanos un mensaje.</p>

      <form style="max-width:640px;margin-top:12px;" onsubmit="event.preventDefault(); alert('Formulario de contacto simulado. Reemplaza con integración real.');">
        <div style="display:flex;gap:8px;flex-wrap:wrap;">
          <input required placeholder="Nombre" style="flex:1;padding:10px;border-radius:8px;border:1px solid #ddd">
          <input required placeholder="Correo" style="flex:1;padding:10px;border-radius:8px;border:1px solid #ddd">
        </div>
        <textarea required placeholder="Mensaje" style="width:100%;margin-top:8px;padding:10px;border-radius:8px;border:1px solid #ddd;min-height:100px"></textarea>
        <div style="margin-top:8px;">
          <button class="btn btn-primary" type="submit">Enviar</button>
        </div>
      </form>
    </section>
  </main>

  <footer>
    <div class="container">
      <div class="copyright">Derechos Reservado a Anthony Estrada — &copy; <span id="year"></span></div>
    </div>
  </footer>

  <!-- Cookie bar -->
  <div class="cookie" id="cookieBar" role="dialog" aria-live="polite">
    <div style="max-width:320px;">
      Utilizamos cookies para garantizar una experiencia de navegación fluida. Al continuar, asumimos que acepta el uso de cookies.
    </div>
    <div style="display:flex;flex-direction:column;gap:6px;">
      <button onclick="acceptCookies()" style="background:#2ecc71;color:white;">Aceptar</button>
      <button onclick="document.getElementById('cookieBar').style.display='none'" style="background:transparent;border:1px solid #ccc;">Saber Más</button>
    </div>
  </div>

  <script>
    // Año dinámico
    document.getElementById('year').textContent = new Date().getFullYear();

    function acceptCookies(){
      localStorage.setItem('gallo_cookies', 'accepted');
      document.getElementById('cookieBar').style.display = 'none';
    }
    // Ocultar cookie si ya aceptó
    if(localStorage.getItem('gallo_cookies') === 'accepted'){
      document.getElementById('cookieBar').style.display = 'none';
    }
  </script>
</body>
</html>
