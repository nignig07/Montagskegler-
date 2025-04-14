<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Montagskegler</title>
  <link href="https://fonts.googleapis.com/css2?family=Rubik:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Rubik', sans-serif;
      background: linear-gradient(120deg, #e0f7fa, #ffffff);
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background-image: url('https://upload.wikimedia.org/wikipedia/commons/5/5f/Kegelbahn.jpg');
      background-size: cover;
      background-position: center;
      color: white;
      padding: 100px 0;
      text-align: center;
      text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.7);
    }
    header h1 {
      font-size: 5rem;
      margin-bottom: 30px;
    }
    header p {
      font-size: 2rem;
    }
    nav {
      background-color: #00695c;
      padding: 20px;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 30px;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #b2dfdb;
    }
    .container {
      padding: 40px 30px;
      max-width: 1300px;
      margin: auto;
    }
    h2 {
      color: #00695c;
      font-size: 2.5rem;
      margin-bottom: 20px;
    }
    img {
      width: 100%;
      border-radius: 12px;
      margin-top: 20px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
    }
    .tipps {
      background-color: #b2dfdb;
      padding: 25px;
      border-radius: 15px;
      margin-top: 40px;
    }
    .tipps ul {
      padding-left: 20px;
      list-style-type: none;
    }
    .tipps ul li {
      font-size: 1.3rem;
      margin-bottom: 12px;
    }
    footer {
      background-color: #004d40;
      color: white;
      text-align: center;
      padding: 25px 0;
      margin-top: 50px;
    }
    .bilder-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
      gap: 25px;
    }
    .cta-button {
      background-color: #00796b;
      color: white;
      padding: 18px 40px;
      font-size: 1.4rem;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      margin-top: 25px;
      transition: background-color 0.3s;
    }
    .cta-button:hover {
      background-color: #004d40;
    }
    .cta-button:active {
      transform: scale(0.98);
    }
    .fade-in {
      animation: fadeIn 2s ease-out;
    }
    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }
  </style>
</head>
<body>
  <header class="fade-in">
    <h1>Montagskegler</h1>
    <p>Dein Freizeitspaß am Wochenanfang!</p>
  </header>
  
  <nav>
    <a href="#warum">Warum Kegeln?</a>
    <a href="#bilder">Bilder</a>
    <a href="#tipps">Tipps</a>
    <a href="#kontakt">Kontakt</a>
  </nav>

  <div class="container">
    <section id="warum" class="fade-in">
      <h2>Warum Kegeln?</h2>
      <p>Kegeln ist der perfekte Ausgleich zum Alltag! Ob mit Freunden, Familie oder Kollegen – beim Kegeln kommt jeder in Bewegung und der Spaß steht im Mittelpunkt. Werde Teil unserer Montagsrunde und starte die Woche sportlich und gut gelaunt!</p>
      <button class="cta-button">Jetzt Mitmachen!</button>
    </section>

    <section id="bilder" class="fade-in">
      <h2>Bilder vom Kegeln</h2>
      <div class="bilder-grid">
        <img src="https://upload.wikimedia.org/wikipedia/commons/5/5f/Kegelbahn.jpg" alt="Kegelbahn">
        <img src="https://upload.wikimedia.org/wikipedia/commons/7/7d/Kegeln_2008.jpg" alt="Leute beim Kegeln">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/Kegeln_bei_Bayern.jpg/800px-Kegeln_bei_Bayern.jpg" alt="Kegler in Aktion">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/Kegelspiel_-_Abger%C3%A4umte_Kegel.jpg/800px-Kegelspiel_-_Abger%C3%A4umte_Kegel.jpg" alt="Abgeräumte Kegel">
      </div>
    </section>

    <section id="tipps" class="tipps fade-in">
      <h2>Tipps zum Kegeln</h2>
      <ul>
        <li><strong>Haltung zählt:</strong> Bleib locker, aber stabil – nicht verkrampfen!</li>
        <li><strong>Übung macht den Meister:</strong> Versuche verschiedene Techniken und finde deinen Stil.</li>
        <li><strong>Ziele bewusst:</strong> Nicht einfach drauf los – peile dein Ziel genau an.</li>
        <li><strong>Der richtige Schwung:</strong> Nicht zu stark, nicht zu schwach – finde dein perfektes Tempo.</li>
        <li><strong>Schuhe & Ball:</strong> Passendes Schuhwerk und der richtige Ball helfen enorm!</li>
      </ul>
    </section>

    <section id="kontakt" class="fade-in">
      <h2>Kontakt</h2>
      <p>Du willst mitkegeln oder hast Fragen? Schreib uns einfach eine Mail an <a href="mailto:montagskegler@example.com">montagskegler@example.com</a> oder komm montags ab 18 Uhr in unsere Kegelbahn in Gernsbach!</p>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 Montagskegler. Alle Rechte vorbehalten.</p>
  </footer>
</body>
</html>
