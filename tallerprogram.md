<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>UEFA Champions League</title>
  <link rel="stylesheet" href="./stilos.css" />
</head>
<body>

<header class="site-header">
  <div class="brand">
    <span class="brand-icon">DP</span>
    <div>
      <p class="brand-title">UEFA Champions League</p>
      <p class="brand-subtitle">Informacion reciente sobre UEFA Champions League</p>
    </div>
  </div>

  <form class="search" role="search">
    <input id="search-input" type="text" placeholder="Buscar equipos o estadisticas" />
    <button type="submit">Buscar</button>
  </form>

  <nav class="main-nav">
    <a href="#destacadas">Destacadas</a>
    <a href="#stats">Estadisticas</a>
    <a href="#equipos">Equipos</a>
  </nav>
</header>

<main class="page">

  <!-- IMAGEN PRINCIPAL -->
  <section class="profile">
    <img src="./EXR12nPq2OjngeRJFDNL6axn7VZKNsa7.jpg" alt="Imagen de oficina" class="profile-photo" />

    <div class="profile-info">
      <h1>Encuentra informacion de tus equipos favoritos</h1>

      <div class="profile-actions">
        <button class="badge">36 Equipos</button>
        <button class="badge badge-outline">1 Copa</button>
      </div>
    </div>
  </section>

  <!-- TEXTO -->
  <section class="section" id="destacadas">
    <h2>¿Qué es la Champions League?</h2>
    <p class="text">
      La UEFA Champions League es el torneo de clubes más importante del fútbol europeo.
    </p>
  </section>

  <!-- EQUIPOS -->
  <section class="section" id="stats">
    <h2>EQUIPOS</h2>

    <div class="card-grid">
      <article class="card"></article>

      <article class="card">
        <p>
          La UEFA Champions League reúne a los mejores equipos como Barcelona, Bayern Múnich, Manchester City y PSG.
        </p>
      </article>
    </div>
  </section>

  <!-- PATROCINADORES -->
  <section class="section" id="empresas">
    <h2>PATROCINADORES</h2>

    <div class="card-grid card-grid--photos">

      <article class="photo-card">

        
        <img 
          src="./1686331713715.jpg"
          alt="Patrocinadores Champions League"
          class="photo-card-img"
          width="600"
          height="400"
        />

        <p>
          La UEFA Champions League cuenta con el apoyo de grandes patrocinadores como Mastercard, Heineken, Pepsi y PlayStation.
        </p>

      </article>

    </div>
  </section>

</main>

<footer class="site-footer">
  <p>PWHL</p>
</footer>

</body>
</html>








<!-- Tarjetas de equipos -->
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>PWHL</title>
  <link rel="stylesheet" href="./stiloss.css" />
</head>
<section class="section" id="equipos">
    <header class="section-header">
        <h2>4 EQUIPOS DESTACADOS</h2>
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
            stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <path d="M3 12a9 9 0 1 0 18 0a9 9 0 1 0 -18 0" />
            <path d="M9 10a3 3 0 1 0 6 0a3 3 0 1 0 -6 0" />
            <path d="M6.168 18.849a4 4 0 0 1 3.832 -2.849h4a4 4 0 0 1 3.834 2.855" />
        </svg>
    </header>

    <div class="card-grid">

        <article class="card">
            <h3>FC Barcelona</h3>
            <p>
                Uno de los clubes más importantes de España. Destaca por su estilo de juego ofensivo
                y por haber ganado varias ediciones de la Champions League.
            </p>
        </article>

        <article class="card">
            <h3>Bayern Múnich</h3>
            <p>
                Equipo alemán reconocido por su dominio en la Bundesliga y sus múltiples títulos
                europeos. Es considerado uno de los clubes más fuertes del continente.
            </p>
        </article>

        <article class="card">
            <h3>Manchester City</h3>
            <p>
                Club inglés que se ha convertido en una potencia del fútbol europeo gracias a su
                calidad de plantilla y su estilo de juego moderno.
            </p>
        </article>

        <article class="card">
            <h3>Paris Saint-Germain (PSG)</h3>
            <p>
                Representante destacado de Francia en la Champions League. Es conocido por contar
                con grandes estrellas y competir constantemente al máximo nivel.
            </p>
        </article>

    </div>
</section>



























/* 1) Reset y box sizing (evita margenes raros del navegador) */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* 2) Variables de color */
:root {
  --bg: #0f043f;
  --text: #064df3;
  --muted: #64748b;
  --primary: #0e0007;
  --card: #000000;
  --border: #2c73cf;
  --shadow: 0 12px 24px rgba(1, 69, 228, 0.08);
}

/* 3) Estilos globales */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: var(--bg);
  color: var(--text);
  line-height: 1.5;
}

a {
  color: inherit;
  text-decoration: none;
}

/* HEADER */
.site-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 16px;
  padding: 16px;
  background: rgb(0, 0, 0);
  border-bottom: 5px solid var(--border);
  margin-bottom: 12px;
}

.site-header strong {
  color: wheat;
}

.brand {
  display: flex;
  align-items: center;
  gap: 15px;
}

.brand-icon {
  width: 40px;
  height: 40px;
  background: var(--primary);
  border-radius: 50%;
  color: white;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  font-weight: 700;
}

.brand-title,
.brand-tittle {
  font-weight: 700;
}

.brand-subtitle {
  color: var(--muted);
  font-size: 0.9rem;
}

/* SEARCH */
.search {
  display: flex;
  gap: 8px;
  background: rgb(138, 153, 241);
  padding: 8px;
  border-radius: 999px;
  flex: 1;
  max-width: 400px;
}

.search input {
  border: none;
  background: transparent;
  outline: none;
  flex: 1;
}

.search button {
  border: none;
  background: var(--primary);
  color: white;
  padding: 6px 12px;
  border-radius: 999px;
  cursor: pointer;
}

/* NAV */
.main-nav {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
}

.main-nav a {
  padding: 6px 10px;
  border-radius: 999px;
}

.main-nav a:hover {
  background: var(--primary);
}

/* LAYOUT */
.page {
  max-width: 1100px;
  margin: 0 auto;
  padding: 24px;
}

.section {
  margin-top: 28px;
}

/* PROFILE */
.profile {
  display: grid;
  grid-template-columns: 260px 1fr;
  gap: 32px;
  background: var(--card);
  border-radius: 14px;
  padding: 45px 24px 24px 24px;
  box-shadow: var(--shadow);
}

/* BOTONES */
.badge {
  border: none;
  background: #1f1d1d;
  color: #064df3;
  padding: 8px 14px;
  border-radius: 999px;
  font-weight: 600;
}

.badge-outline {
  border: 1px solid #064df3;
  background: transparent;
  color: #064df3;
}

/* ========================= */
/* TARJETAS (AQUÍ ESTÁ EL CAMBIO IMPORTANTE)
/* ========================= */

/* 4 columnas en desktop */
.card-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 12px;
}

/* cada card */
.card {
  background: var(--card);
  padding: 14px;
  border-radius: 14px;
  border: 1px solid var(--border);
  box-shadow: var(--shadow);
}

/* responsive (móvil) */
@media (max-width: 900px) {
  .card-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 500px) {
  .card-grid {
    grid-template-columns: 1fr;
  }
}

/* errores corregidos */
.card-title {
  color: var(--muted);
  font-size: 0.9rem;
}

.card-value {
  font-size: 1.2rem;
  font-weight: 700;
}

/* photos grid corregido */
.card-grid--photos {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
  gap: 12px;
}

/* photo cards */
.photo-card {
  background: rgb(0, 0, 0);
  border-radius: 16px;
  padding: 12px;
  border: 1px solid var(--border);
  box-shadow: var(--shadow);
}

.photo-placeholder {
  height: 120px;
  border-radius: 12px;
  background: #004285;
  margin-bottom: 8px;
}

.card-subtitle {
  color: var(--muted);
  font-size: 0.85rem;
}

/* FOOTER */
.site-footer {
  text-align: center;
  padding: 24px;
  color: var(--muted);
}
.photo-img {
  width: 100%;
  height: 120px;
  object-fit: cover;
  border-radius: 12px;
  margin-bottom: 8px;
}

