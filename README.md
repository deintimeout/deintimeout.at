<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Timeout</title>
  <style>
    :root {
      --zeitgrau: #6E6E6E;
      --weiß: #FFFFFF;
      --akzent: #B0B0B0;
    }
    body {
      margin: 0;
      font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
      background: var(--weiß);
      color: var(--zeitgrau);
    }
    header {
      padding: 2rem 0 1rem 0;
      text-align: center;
      background: var(--weiß);
      border-bottom: 1px solid var(--akzent);
    }
    h1 {
      font-size: 2.5rem;
      font-weight: 700;
      margin: 0;
      letter-spacing: 0.1em;
    }
    nav {
      text-align: center;
      margin: 2rem 0 3rem 0;
    }
    nav a {
      color: var(--zeitgrau);
      text-decoration: none;
      margin: 0 1.5rem;
      font-size: 1.2rem;
      padding: 0.5rem 1rem;
      border-radius: 2rem;
      transition: background 0.2s;
    }
    nav a:hover {
      background: var(--akzent);
    }
    .restaurants {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 2rem;
      margin: 3rem 0;
    }
    .restaurant-box {
      background: var(--weiß);
      border: 1px solid var(--akzent);
      border-radius: 1rem;
      padding: 2rem;
      min-width: 260px;
      max-width: 320px;
      box-shadow: 0 2px 12px rgba(110,110,110,0.06);
      text-align: center;
    }
    .restaurant-box h2 {
      margin: 0 0 1rem 0;
      font-size: 1.6rem;
      font-weight: 600;
    }
    .restaurant-box p {
      margin: 0 0 1.2rem 0;
      font-size: 1rem;
      line-height: 1.5;
      color: var(--zeitgrau);
    }
    .restaurant-box a {
      color: var(--weiß);
      background: var(--zeitgrau);
      text-decoration: none;
      padding: 0.6rem 1.5rem;
      border-radius: 2rem;
      font-weight: 500;
      transition: background 0.2s;
    }
    .restaurant-box a:hover {
      background: var(--akzent);
      color: var(--zeitgrau);
    }
    @media (max-width: 700px) {
      .restaurants {
        flex-direction: column;
        align-items: center;
      }
    }
    footer {
      text-align: center;
      font-size: 0.9rem;
      color: var(--akzent);
      padding: 1.5rem 0 1rem 0;
      border-top: 1px solid var(--akzent);
      margin-top: 3rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Timeout</h1>
  </header>
  <nav>
    <a href="#allsportzentrum">Allsportzentrum</a>
    <a href="#technologiezentrum">Technologiezentrum</a>
  </nav>
  <main>
    <section class="restaurants">
      <div class="restaurant-box" id="allsportzentrum">
        <h2>Timeout – Allsportzentrum</h2>
        <p>Sportliche Atmosphäre und frische Küche direkt im Allsportzentrum. Ideal für Sportler und Genießer.</p>
        <a href="allsportzentrum.html">Mehr erfahren</a>
      </div>
      <div class="restaurant-box" id="technologiezentrum">
        <h2>Timeout – Technologiezentrum</h2>
        <p>Modernes Ambiente und innovative Gerichte im Herzen des Technologiezentrums. Perfekt für Business und Lunch.</p>
        <a href="technologiezentrum.html">Mehr erfahren</a>
      </div>
    </section>
  </main>
  <footer>
    &copy; 2025 Timeout – Minimalistisches Restaurant-Erlebnis
  </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Timeout – Allsportzentrum</title>
  <style>
    body { font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; background: #FFFFFF; color: #6E6E6E; margin: 0;}
    a { color: #6E6E6E; text-decoration: none; }
    .container { max-width: 600px; margin: 3rem auto; padding: 2rem; background: #FFFFFF; border-radius: 1rem; border: 1px solid #B0B0B0; }
    h1 { font-size: 2rem; margin-bottom: 1.5rem; }
    p { font-size: 1rem; margin-bottom: 1rem; }
    .back { display: block; margin-bottom: 2rem; font-size: 1rem; }
  </style>
</head>
<body>
  <div class="container">
    <a href="index.html" class="back">&larr; Zurück zur Übersicht</a>
    <h1>Timeout – Allsportzentrum</h1>
    <p>Willkommen im sportlichen Timeout! Genieße frische und gesunde Gerichte in entspannter Atmosphäre mit Blick auf das Allsportzentrum.</p>
    <p>Adresse: Beispielstraße 1, 12345 Musterstadt</p>
    <p>Öffnungszeiten: Mo–Fr 10–22 Uhr, Sa/So 12–20 Uhr</p>
    <p>Kontakt: <a href="mailto:allsportzentrum@timeout.de">allsportzentrum@timeout.de</a></p>
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Timeout – Technologiezentrum</title>
  <style>
    body { font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; background: #FFFFFF; color: #6E6E6E; margin: 0;}
    a { color: #6E6E6E; text-decoration: none; }
    .container { max-width: 600px; margin: 3rem auto; padding: 2rem; background: #FFFFFF; border-radius: 1rem; border: 1px solid #B0B0B0; }
    h1 { font-size: 2rem; margin-bottom: 1.5rem; }
    p { font-size: 1rem; margin-bottom: 1rem; }
    .back { display: block; margin-bottom: 2rem; font-size: 1rem; }
  </style>
</head>
<body>
  <div class="container">
    <a href="index.html" class="back">&larr; Zurück zur Übersicht</a>
    <h1>Timeout – Technologiezentrum</h1>
    <p>Genieße innovative Küche im modernen Timeout des Technologiezentrums. Perfekt für Business-Lunches und Treffen im kreativen Umfeld.</p>
    <p>Adresse: Musterallee 5, 12345 Beispielstadt</p>
    <p>Öffnungszeiten: Mo–Fr 8–18 Uhr</p>
    <p>Kontakt: <a href="mailto:technologiezentrum@timeout.de">technologiezentrum@timeout.de</a></p>
  </div>
</body>
</html>
