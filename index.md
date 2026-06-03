<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>

<title>Política de Privacidad | Album Panini 2026</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

:root{
  --primary:#0F172A;
  --secondary:#475569;
  --gold:#F4B400;
  --blue:#2563EB;
  --bg:#F8FAFC;
  --white:#FFFFFF;
  --border:#E2E8F0;
  --success:#10B981;
  --shadow:0 10px 30px rgba(15,23,42,.08);
}

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}

body{
  font-family:'Inter', sans-serif;
  background:var(--bg);
  color:var(--primary);
  line-height:1.7;
}

/* Background decoration */
.bg-decoration{
  position:fixed;
  width:100%;
  height:100%;
  top:0;
  left:0;
  overflow:hidden;
  z-index:-1;
}

.circle{
  position:absolute;
  border-radius:50%;
  filter: blur(80px);
  opacity:.12;
}

.circle.one{
  width:300px;
  height:300px;
  background:#2563EB;
  top:-80px;
  left:-100px;
}

.circle.two{
  width:300px;
  height:300px;
  background:#F4B400;
  right:-100px;
  top:150px;
}

/* Header */
.hero{
  position:relative;
  overflow:hidden;
  background:
  linear-gradient(
  135deg,
  #0F172A,
  #1E293B
  );
  color:white;
  text-align:center;
  padding:90px 20px 70px;
  border-bottom-left-radius:40px;
  border-bottom-right-radius:40px;
}

.badge{
  display:inline-flex;
  align-items:center;
  gap:8px;
  background:rgba(255,255,255,.1);
  border:1px solid rgba(255,255,255,.15);
  padding:10px 18px;
  border-radius:999px;
  font-size:13px;
  font-weight:600;
  backdrop-filter: blur(10px);
  margin-bottom:25px;
}

.hero-icon{
  font-size:70px;
  margin-bottom:20px;
}

.hero h1{
  font-size:clamp(38px,6vw,70px);
  font-weight:800;
  line-height:1.1;
}

.hero h1 span{
  color:var(--gold);
}

.subtitle{
  margin-top:15px;
  color:#CBD5E1;
  font-size:15px;
}

.container{
  max-width:900px;
  margin:auto;
  padding:50px 20px 90px;
}

/* Update */
.update-card{
  background:white;
  border-radius:20px;
  padding:18px;
  text-align:center;
  margin-top:-45px;
  position:relative;
  z-index:10;
  box-shadow:var(--shadow);
  border:1px solid var(--border);
  font-size:14px;
  color:var(--secondary);
}

.update-card strong{
  color:var(--blue);
}

/* Sections */
.section{
  background:var(--white);
  border-radius:24px;
  padding:35px;
  margin-top:25px;
  box-shadow:var(--shadow);
  border:1px solid rgba(226,232,240,.7);
  transition:.3s ease;
}

.section:hover{
  transform:translateY(-3px);
}

.section-header{
  display:flex;
  align-items:center;
  gap:14px;
  margin-bottom:20px;
}

.icon-box{
  width:60px;
  height:60px;
  background:linear-gradient(
  135deg,
  #2563EB,
  #1D4ED8
  );
  border-radius:18px;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:28px;
  color:white;
  flex-shrink:0;
}

.section h2{
  font-size:24px;
  font-weight:700;
}

.section p{
  color:var(--secondary);
  font-size:15px;
}

ul{
  list-style:none;
  margin-top:15px;
}

ul li{
  position:relative;
  padding:14px 0 14px 32px;
  color:var(--secondary);
  border-bottom:1px solid #F1F5F9;
}

ul li:last-child{
  border-bottom:none;
}

ul li::before{
  content:'✓';
  position:absolute;
  left:0;
  color:var(--success);
  font-weight:bold;
}

/* Chips */
.chips{
  display:flex;
  flex-wrap:wrap;
  gap:12px;
  margin-top:20px;
}

.chip{
  background:#F8FAFC;
  border:1px solid var(--border);
  border-radius:14px;
  padding:12px 18px;
  font-weight:600;
  color:var(--primary);
}

/* Contact */
.contact-card{
  background:
  linear-gradient(
  135deg,
  #EFF6FF,
  #F8FAFC
  );

  border-radius:24px;
  padding:25px;
  display:flex;
  align-items:center;
  gap:20px;
  margin-top:20px;
  border:1px solid #DBEAFE;
}

.contact-icon{
  width:65px;
  height:65px;
  border-radius:18px;
  background:var(--blue);
  color:white;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:30px;
}

.contact-card a{
  text-decoration:none;
  color:var(--blue);
  font-weight:700;
  font-size:18px;
}

.contact-card small{
  display:block;
  color:var(--secondary);
  margin-top:5px;
}

/* Footer */
footer{
  text-align:center;
  padding:35px 20px;
  color:#64748B;
  font-size:14px;
}

footer strong{
  color:var(--primary);
}

@media(max-width:768px){

.hero{
  padding:70px 20px 60px;
}

.section{
  padding:25px;
}

.section-header{
  align-items:flex-start;
}

.contact-card{
  flex-direction:column;
  text-align:center;
}

}

</style>
</head>

<body>

<div class="bg-decoration">
  <div class="circle one"></div>
  <div class="circle two"></div>
</div>

<header class="hero">

  <div class="badge">
    🔒 Política de Privacidad
  </div>

  <div class="hero-icon">
    🏆
  </div>

  <h1>Album Panini <span>2026</span></h1>

  <p class="subtitle">
    Mundial de Fútbol · Aplicación de Colección
  </p>

</header>

<div class="container">

  <div class="update-card">
    Última actualización:
    <strong>Junio 2026</strong>
    · Versión 1.0
  </div>

  <!-- Introducción -->
  <div class="section">

    <div class="section-header">
      <div class="icon-box">📋</div>
      <h2>Introducción</h2>
    </div>

    <p>
      Album Panini 2026 ("la App") es una aplicación móvil para coleccionar
      y gestionar figuritas del Mundial de Fútbol 2026.
      Esta política explica qué información recopilamos,
      cómo la usamos y cómo la protegemos.
    </p>

    <p style="margin-top:10px;">
      Al usar la App, aceptas los términos descritos en esta política.
    </p>

  </div>

  <!-- Información -->
  <div class="section">

    <div class="section-header">
      <div class="icon-box">🗂️</div>
      <h2>Información que recopilamos</h2>
    </div>

    <ul>
      <li>Datos de uso y navegación dentro de la App</li>
      <li>Información de suscripción gestionada por Google Play</li>
      <li>Imágenes capturadas con la cámara</li>
      <li>Imágenes seleccionadas desde la galería</li>
      <li>Identificadores para personalización de anuncios</li>
    </ul>

  </div>

  <!-- Uso -->
  <div class="section">

    <div class="section-header">
      <div class="icon-box">⚙️</div>
      <h2>Uso de la información</h2>
    </div>

    <ul>
      <li>Sincronizar tu colección</li>
      <li>Gestionar suscripciones Premium</li>
      <li>Mostrar anuncios relevantes</li>
      <li>Mejorar el rendimiento de la App</li>
    </ul>

  </div>

  <!-- Terceros -->
  <div class="section">

    <div class="section-header">
      <div class="icon-box">🤝</div>
      <h2>Servicios de terceros</h2>
    </div>

    <p>
      La App integra servicios externos con sus propias políticas de privacidad:
    </p>

    <div class="chips">
      <div class="chip">Google AdMob</div>
      <div class="chip">RevenueCat</div>
      <div class="chip">Google Play</div>
    </div>

  </div>

  <!-- Contacto -->
  <div class="section">

    <div class="section-header">
      <div class="icon-box">📬</div>
      <h2>Contacto</h2>
    </div>

    <p>
      Si tienes preguntas sobre privacidad puedes contactarnos:
    </p>

    <div class="contact-card">

      <div class="contact-icon">
        ✉️
      </div>

      <div>
        <a href="mailto:smican97@gmail.com">
          smican97@gmail.com
        </a>

        <small>
          Respuesta aproximada: 48 horas hábiles
        </small>
      </div>

    </div>

  </div>

</div>

<footer>
  <strong>Album Panini 2026</strong>
  · Todos los derechos reservados · Colombia 🇨🇴
</footer>

</body>
</html>
