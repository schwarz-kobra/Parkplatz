<!DOCTYPE html>

<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>🔒 Arduino Parkplatz</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      color: #222;
    }
    header {
      background-color: black;
      color: white;
      padding: 0.3rem 1rem;
      font-size: 1.1rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav {
      background-color: black;
      padding: 0.5rem 2rem;
    }
    nav a {
      color: white;
      margin-right: 1.5rem;
      text-decoration: none;
      font-weight: bold;
    }
    nav a[href="#kontakt"] {
      background-color: white;
      color: black;
      padding: 0.2rem 0.6rem;
      border-radius: 4px;
    }
    .hero {
      background-color: #0e76a8;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    main {
      max-width: 800px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    h2 {
      color: #0e76a8;
      border-bottom: 2px solid #0e76a8;
      padding-bottom: 0.3rem;
    }
    .warn-hinweis {
      background-color: #ffdf91;
      padding: 1rem;
      margin-bottom: 1rem;
      border-left: 6px solid darkorange;
      border-radius: 4px;
      color: #222;
    }
    .component-list {
      background-color: #fff;
      border-left: 6px solid #0e76a8;
      padding: 1rem;
      margin-bottom: 2rem;
    }
    footer {
      background-color: black;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
    }
    .video-container {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      margin-top: 1rem;
    }
    iframe {
      width: 100%;
      height: 400px;
      border: none;
    }
    .kontakt-info {
      text-align: right;
    }
  </style>
</head>
<body>

<header>
  🔒 Arduino Parkplatz
  <div class="kontakt-info">
    <a href="#kontakt" style="color: white; text-decoration: none;">📬 Kontakt</a>
  </div>
</header>
<nav>
  <a href="#start">Start</a>
  <a href="#anleitung">Anleitung</a>
  <a href="#bauteile">Bauteile</a>
  <a href="#kontakt">Kontakt</a>
</nav>

<div class="hero">
  <h1>Arduino Parkplatz mit Lasersensoren</h1>
  <p>Automatisierter Zugang mit Servo, IR-Sensor und LCD – Schulprojekt 2025</p>
</div>

<main>
  <section id="start">
    <h2>📖 Projektbeschreibung</h2>
    <p>Eine automatische Schrankenanlage mit Lasersensor. Erkennt ein Fahrzeug und öffnet per Servoarm für 5 Sekunden. LCD zeigt Status, Bewegungssensor optional.</p>
    <p><em>🔄 Update kommt demnächst...</em></p>
  </section>

  <section id="warnhinweise">
    <h2>⚠️ Warn- und Sicherheitshinweise</h2>

```
<div class="warn-hinweis">
  <strong>🔌 Elektrische Sicherheit</strong>
  <ul>
    <li>Nur 5 V vom Arduino oder geregeltem Netzteil verwenden.</li>
    <li>Polung (GND und VCC) beachten.</li>
    <li>Keine Kabel bei Betrieb umstecken.</li>
  </ul>
</div>

<div class="warn-hinweis">
  <strong>🔋 Stromquelle</strong>
  <ul>
    <li>Separate 5 V-Stromquelle mit mindestens 1 A empfohlen.</li>
  </ul>
</div>

<div class="warn-hinweis">
  <strong>🔥 Laser- und Brandschutz</strong>
  <ul>
    <li>Laser nie auf Augen richten.</li>
    <li>Nur Klasse-1 oder Klasse-2 Laser einsetzen.</li>
    <li>Keine Bauteile abdecken oder überhitzen lassen.</li>
  </ul>
</div>

<div class="warn-hinweis">
  <strong>🧠 Allgemein</strong>
  <ul>
    <li>Kurze, stabile Leitungen verwenden.</li>
    <li>Keine wackelnden Steckverbindungen.</li>
    <li>Servo darf sich frei bewegen können.</li>
  </ul>
</div>

<div class="warn-hinweis">
  <strong>🛑 Notabschaltung</strong>
  <ul>
    <li>Ein Schalter zur Notabschaltung wird empfohlen.</li>
  </ul>
</div>
```

  </section>

  <section id="bauteile">
    <h2>📦 Komponentenliste</h2>
    <div class="component-list">
      <ul>
        <li>Arduino Uno</li>
        <li>LCD 16x2 mit I2C</li>
        <li>2x Laser-Sensor</li>
        <li>IR Sensor</li>
        <li>Servo SG90</li>
        <li>Piezo-Buzzer</li>
        <li>Stromversorgung 5V 1A</li>
      </ul>
    </div>
  </section>

  <section id="kontakt">
    <h2>📬 Kontakt</h2>
    <div class="kontakt-info">
      <p>Email: <a href="mailto:felixepic91@gmail.com">felixepic91@gmail.com</a></p>
      <p>Website: <a href="https://parkplatz.vercel.app/" target="_blank">https://parkplatz.vercel.app</a></p>
      <p>Schule: <a href="https://www.holzmsgraz.at/" target="_blank">holzmsgraz.at</a></p>
      <p>TikTok: <a href="https://www.tiktok.com/@blackcobra.officialx" target="_blank">@blackcobra.officialx</a></p>
    </div>

```
<h3>🎥 Videos</h3>
<div class="video-container">
  <iframe src="https://www.tiktok.com/embed/v2/7498327481569660190"></iframe>
  <iframe src="https://www.tiktok.com/embed/v2/7493832615292865838"></iframe>
</div>
```

  </section>
</main>

<footer>
  <p>📄 Impressum & Datenschutz</p>
  <p>Diese Website ist ein Schulprojekt und enthält keine kommerziellen Inhalte.</p>
  <p>Verantwortlich laut § 5 TMG: Felix E. (Kontakt per E-Mail)</p>
  <p>Alle Marken und Inhalte gehören den jeweiligen Eigentümern.</p>
  <p>Keine Speicherung personenbezogener Daten, keine Cookies.</p>
  <p>Letzte Änderung: Juli 2025 | Version: 1.1</p>
  <p>© 2025 Felix & Thomas – Schulprojekt Mittelschule Graz Straßgang</p>
</footer>

</body>
</html>
