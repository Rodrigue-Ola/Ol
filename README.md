<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>CV – Rodrigue Olalekan Assogba</title>
  <meta name="description" content="CV professionnel et dynamique de Rodrigue Olalekan Assogba" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #3b82f6;
      --secondary: #0f172a;
      --accent: #facc15;
      --light: #f8fafc;
      --muted: #94a3b8;
      --font: 'Inter', sans-serif;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: var(--font);
      background: var(--secondary);
      color: var(--light);
      line-height: 1.6;
      overflow-x: hidden;
    }

    header {
      background: rgba(15, 23, 42, 0.95);
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
      position: sticky;
      top: 0;
      z-index: 999;
    }

    header img {
      width: 50px;
      height: 50px;
      border-radius: 50%;
    }

    nav ul {
      display: flex;
      gap: 1.5rem;
      list-style: none;
    }

    nav a {
      color: var(--light);
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s;
    }

    nav a:hover {
      color: var(--accent);
    }

    .hero {
      text-align: center;
      padding: 5rem 1rem 3rem;
      background: linear-gradient(to bottom, #1e293b, #0f172a);
      animation: fadeIn 1.5s ease-in;
    }

    .hero h1 {
      font-size: 2.5rem;
      font-weight: 800;
    }

    .typewriter {
      display: inline-block;
      border-right: 2px solid var(--accent);
      white-space: nowrap;
      overflow: hidden;
      animation: typing 3s steps(30), blink 0.75s step-end infinite;
    }

    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }

    @keyframes blink {
      50% { border-color: transparent; }
    }

    .btn {
      display: inline-block;
      margin-top: 2rem;
      padding: 0.75rem 1.5rem;
      background: var(--primary);
      color: #fff;
      border-radius: 30px;
      text-decoration: none;
      font-weight: 600;
      transition: all 0.3s ease-in-out;
    }

    .btn:hover {
      background: var(--accent);
      color: var(--secondary);
    }

    .container {
      max-width: 900px;
      margin: 3rem auto;
      padding: 0 1rem;
    }

    h2 {
      font-size: 1.8rem;
      color: var(--accent);
      margin-bottom: 1rem;
      border-bottom: 2px solid var(--accent);
      padding-bottom: 0.3rem;
      animation: fadeIn 1s ease-in;
    }

    .section {
      margin-bottom: 3rem;
      animation: fadeInUp 1s ease forwards;
      opacity: 0;
    }

    .skills-list, .timeline, ul {
      list-style: none;
      padding: 0;
    }

    .skills-list li, .timeline .entry {
      background: #1e293b;
      padding: 0.75rem 1rem;
      margin-bottom: 0.75rem;
      border-radius: 8px;
    }

    .timeline .entry {
      border-left: 4px solid var(--primary);
    }

    footer {
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
      color: var(--muted);
      background-color: #0f172a;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="logo_ra.png" alt="Logo RA">
    <nav>
      <ul>
        <li><a href="#home">Accueil</a></li>
        <li><a href="#about">Profil</a></li>
        <li><a href="#experience">Expériences</a></li>
        <li><a href="#skills">Compétences</a></li>
        <li><a href="#projects">Projets</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="hero">
    <h1 class="typewriter">Rodrigue Olalekan Assogba</h1>
    <p>Étudiant en Technique Actuarielle | Analyste Financier Junior</p>
    <a href="CV_Rodrigue_Assogba.pdf" class="btn" download>📄 Télécharger le CV</a>
  </section>

  <section id="about" class="container section">
    <h2>À propos</h2>
    <p>Je suis un jeune étudiant passionné de finance, technologie et innovation, actuellement en deuxième année de gestion à l'UAC. Je travaille sur des projets concrets comme la conception d'une voiture électrique et la création de solutions comptables adaptées à l’Afrique francophone.</p>
  </section>

  <section id="experience" class="container section">
    <h2>Expériences professionnelles</h2>
    <div class="timeline">
      <div class="entry">
        <strong>Stagiaire Analyste Financier</strong><br>
        <em>Bank Bénin – Juin–Août 2024</em>
        <ul>
          <li>Analyse des portefeuilles SME</li>
          <li>Rapports Excel et recommandations stratégiques</li>
        </ul>
      </div>
      <div class="entry">
        <strong>Assistant Comptable</strong><br>
        <em>Cabinet OHADA+ – Juillet–Sept 2023</em>
        <ul>
          <li>Saisie comptable selon normes OHADA</li>
          <li>Participation aux audits internes</li>
        </ul>
      </div>
    </div>
  </section>

  <section id="skills" class="container section">
    <h2>Compétences</h2>
    <ul class="skills-list">
      <li>Python, C++, Excel avancé</li>
      <li>Sage 100, Comptabilité OHADA</li>
      <li>Canva, PowerPoint, InShot</li>
    </ul>
    <h3>Langues</h3>
    <ul class="skills-list">
      <li>Français (natif)</li>
      <li>Anglais (B2 CECRL)</li>
    </ul>
  </section>

  <section id="projects" class="container section">
    <h2>Projets</h2>
    <div>
      <strong>Quincaillerie moderne</strong> – +15 % d’efficacité<br>
      <a href="https://github.com/rod-assogba/quincaillerie" target="_blank">Voir sur GitHub</a>
    </div>
  </section>

  <section id="contact" class="container section">
    <h2>Contact</h2>
    <p>📧 <a href="mailto:rodrigueassogba963@gmail.com">rodrigueassogba963@gmail.com</a></p>
    <p>📞 +229 0161643404 / +229 0145895013</p>
    <p>
      <a href="https://www.linkedin.com/in/rodrigue-assogba" target="_blank">LinkedIn</a> |
      <a href="https://github.com/rod-assogba" target="_blank">GitHub</a>
    </p>
  </section>

  <footer>
    &copy; 2025 Rodrigue Olalekan Assogba – Tous droits réservés
  </footer>

</body>
</html>
