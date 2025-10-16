<html lang="fr">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Omar KASSI — Chercheur</title>
  <style>
    :root{--maxw:900px;--accent:#0b63ce}
    body{font-family:system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;line-height:1.45;margin:0;padding:0;color:#111}
    .wrap{max-width:var(--maxw);margin:30px auto;padding:20px}
    header{display:flex;gap:20px;align-items:center}
    .avatar{width:88px;height:88px;border-radius:8px;background:#ddd;display:inline-block}
    h1{margin:0;font-size:1.6rem}
    p.lead{margin:6px 0;color:#333}
    nav{margin-top:14px}
    nav a{margin-right:12px;text-decoration:none;color:var(--accent)}
    section{margin-top:22px}
    .grid{display:grid;grid-template-columns:1fr;gap:18px}
    .card{padding:14px;border:1px solid #eee;border-radius:8px;background:#fff}
    footer{margin-top:30px;padding-top:12px;border-top:1px solid #f0f0f0;color:#666}
    ul.simple{padding-left:1.15rem}
    @media(min-width:800px){.grid{grid-template-columns:2fr 1fr}}
    .muted{color:#666;font-size:0.95rem}
    .btn{display:inline-block;padding:6px 10px;border-radius:6px;text-decoration:none;border:1px solid #ddd}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="avatar" aria-hidden="true"></div>
      <div>
        <h1>Omar KASSI</h1>
        <div class="muted">Research assistant at CREST-ENSAI</div>
        <p class="lead">I am currently a research assistant at CREST-ENSAI working with Valentin Patilea.</p>
        <nav>
          <a href="#recherche">Recherche</a>
          <a href="#publications">Publications</a>
          <a href="#conferences">Conférences</a>
          <a href="#enseignement">Enseignement</a>
          <a href="#contact">Contact</a>
        </nav>
      </div>
    </header>

    <main class="grid">
      <div>
        <section id="recherche" class="card">
          <h2>Recherche</h2>
          <p>My research focuses on developing methods that are both theoretically sound and practically effective in functional data analysis and nonparametric statistics, with an emphasis on the non-asymptotic properties of statistical procedures.</p>
          <h3>Thèmes</h3>
          <ul class="simple">
            <li>Thème 1 : functional data analysis</li>
            <li>Thème 2 : nonparametric statistics</li>
          </ul>
        </section>

        <section id="publications" class="card">
          <h2>Publications choisies</h2>
          <ol>
            <li>O. Kassi, N. Klutchnikoff, V. Patilea. "Learning the regularity of multivariate functional data". <em>Electronic Journal of Statistics. DOI: 10.1214/25-EJS2433</em>, 9(2): 4174-4229 (2025). <a href="https://projecteuclid.org/journals/electronic-journal-of-statistics/volume-19/issue-2/Learning-the-regularity-of-multivariate-functional-data/10.1214/25-EJS2433.full">PDF</a></li>
            <li>O. Kassi, SGW. Wang. "Structural adaptation via directional regularity: rate accelerated estimation in multivariate functional data".Bernoulli (major revision requested). <a href="https://arxiv.org/abs/2409.00817">PDF</a> </li>
            <li>O. Kassi, V. Patilea. " Optimal inference for the mean of random  functions"</li>
          </ol>
          <p class="muted">Pour une liste complète : <a href="#">Google Scholar</a> • <a href="#">ORCID</a> • <a href="#">BibTeX</a></p>
        </section>

        <section id="conferences" class="card">
          <h2>Conférences & Présentations récentes</h2>
          <ul class="simple">
            <li>2025 — Titre de la présentation, Conférence (Ville) — <a href="#">slides</a></li>
            <li>2024 — ...</li>
          </ul>
        </section>

        <section id="enseignement" class="card">
          <h2>Enseignement & Cours</h2>
          <p class="muted">Semestre actuel : cours que tu donnes, niveau, lien vers les notes ou la page du cours.</p>
          <ul class="simple">
            <li>Master 1 — Statistiques nonparamétriques — <a href="#">Syllabus</a></li>
          </ul>
        </section>
      </div>

      <aside>
        <section class="card">
          <h3>CV & Contact</h3>
          <p class="muted">Télécharger : <a class="btn" href="#">CV (PDF)</a></p>
          <p>Email : <a href="mailto:email@exemple.com">omar.kassi@ensai.fr</a></p>
          <p class="muted">Liens : <a href="#">GitHub</a> • <a href="https://scholar.google.com/citations?user=FNVKxr8AAAAJ&hl=fr">Google Scholar</a></p>
        </section>

        <section class="card">
          <h3>À propos</h3>
          <p class="muted">Quelques lignes bio : parcours, thèse, encadrants, contact pro.</p>
        </section>

        <section class="card">
          <h3>Fichiers utiles</h3>
          <ul class="simple">
            <li><a href="/courses/">Cours & supports</a></li>
            <li><a href="/talks/">Présentations</a></li>
            <li><a href="/publications/bibtex.bib">BibTeX</a></li>
          </ul>
        </section>
      </aside>
    </main>

    
  </div>
</body>
</html>
