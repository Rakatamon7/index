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

