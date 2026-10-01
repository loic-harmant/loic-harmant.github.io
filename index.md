
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Prénom NOM — Engineer Portfolio</title>
  <link rel="stylesheet" href="css/style.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>
  
  <!-- NAVIGATION FIXÉE EN HAUT -->
  <nav class="navbar">
    <div class="container">
      <ul class="nav-menu">
        <li><a href="#welcome" class="active">Welcome</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#career">Career</a></li>
        <li><a href="#mobility">Mobility</a></li>
        <li><a href="#passions">Passions</a></li>
        <li><a href="#civic">Civic Engagement</a></li>
      </ul>
    </div>
  </nav>

  <!-- 1. WELCOME SECTION -->
  <section id="welcome" class="section section-welcome">
    <div class="container">
      <div class="welcome-content">
        <img src="images/photo-cv.jpg" alt="Photo de profil" class="photo-cv">
        <h1>Loïc HARMANT</h1>
        <p class="uvp">Engineering apprentice in fluide mechanics, erngetics and environment at ENSEEIHT</p>
        <div class="welcome-links">
          <a href="documents/CV_Lea_MARTIN_EN.pdf" class="btn btn-primary" target="_blank">Download CV</a>
          <a href="https://www.linkedin.com/in/loïc-harmant" class="btn btn-secondary">LinkedIn</a>
          <a href="./CV_French_Loïc_Harmant.pdf" class="btn btn-secondary" download>Download CV (French)</a>
        </div>
        <div class="video-container">
          <!-- Remplace le lien YouTube par ta vidéo "Unlisted" -->
          <a href="https://youtube.com/watch?v=votre-video-id" target="_blank" class="video-link">▶ Watch 3-min Pitch (English)</a>
        </div>
      </div>
    </div>
  </section>

  <!-- 2. PROJECTS SECTION -->
  <section id="projects" class="section section-projects">
    <div class="container">
      <h2>Projects</h2>
      <p class="section-subtitle">Engineering projects using the Class 4 method</p>
      
      <div class="project-grid">
        <!-- Projet 1 -->
        <article class="project-card">
          <img src="images/projets/projet1.jpg" alt="Projet 1" class="project-image">
          <div class="project-info">
            <h3>Nom du Projet 1</h3>
            <p class="project-description">Courte description : problème, votre rôle, outils utilisés.</p>
            <div class="project-tags">
              <span>C++</span><span>Embedded</span><span>FPGA</span>
            </div>
            <a href="#" class="project-link">Read Case Study →</a>
          </div>
        </article>
        
        <!-- Projet 2 -->
        <article class="project-card">
          <img src="images/projets/projet2.jpg" alt="Projet 2" class="project-image">
          <div class="project-info">
            <h3>Nom du Projet 2</h3>
            <p class="project-description">Description courte du deuxième projet.</p>
            <div class="project-tags">
              <span>Python</span><span>Data</span><span>ML</span>
            </div>
            <a href="#" class="project-link">Read Case Study →</a>
          </div>
        </article>
        
        <!-- Ajoute autant de cards que nécessaire -->
      </div>
      
      <div class="target-specialty">
        <h3>Target Specialty / Pathway</h3>
        <p>Je vise la spécialité [Nom] chez [Entreprise] car...</p>
      </div>
    </div>
  </section>

  <!-- 3. CAREER SECTION -->
  <section id="career" class="section section-career">
    <div class="container">
      <h2>Career</h2>
      
      <div class="job-target">
        <h3>Target Job Ad</h3>
        <a href="documents/job-ad.pdf" target="_blank" class="doc-link">📄 View Job Advertisement (PDF)</a>
      </div>
      
      <div class="documents-section">
        <a href="documents/CV_Lea_MARTIN_EN.pdf" class="doc-item" target="_blank">
          <span class="doc-icon">📄</span>
          <span class="doc-name">Curriculum Vitae (EN)</span>
        </a>
        <a href="documents/Cover_Letter_Lea_MARTIN_EN.pdf" class="doc-item" target="_blank">
          <span class="doc-icon">📝</span>
          <span class="doc-name">Cover Letter (EN)</span>
        </a>
      </div>
      
      <div class="my-job-glasses">
        <h3>My Job Glasses Interviews</h3>
        <article class="mjg-interview">
          <h4>Interview 1 — Nom & Fonction</h4>
          <p>Pourquoi ? Qu'ai-je appris ? Que vais-je faire ensuite ?</p>
        </article>
        <article class="mjg-interview">
          <h4>Interview 2 — Nom & Fonction</h4>
          <p>Pourquoi ? Qu'ai-je appris ? Que vais-je faire ensuite ?</p>
        </article>
      </div>
      
      <p class="linkedin-link">
        👉 <a href="https://linkedin.com/in/votreprofil" target="_blank">My LinkedIn Profile</a>
      </p>
    </div>
  </section>

  <!-- 4. MOBILITY SECTION -->
  <section id="mobility" class="section section-mobility">
    <div class="container">
      <h2>Mobility</h2>
      <p class="section-subtitle">Three international mobility projects aligned with my apprenticeship</p>
      
      <div class="mobility-list">
        <article class="mobility-item">
          <h3>Mobility 1 — Pays / Université (Dates)</h3>
          <p>Comment cela s'articule avec mon entreprise : timing, étapes à valider...</p>
        </article>
        <article class="mobility-item">
          <h3>Mobility 2 — Pays / Université (Dates)</h3>
          <p>Détails et articulation avec l'apprentissage.</p>
        </article>
        <article class="mobility-item">
          <h3>Mobility 3 — Pays / Université (Dates)</h3>
          <p>Détails et articulation avec l'apprentissage.</p>
        </article>
      </div>
    </div>
  </section>

  <!-- 5. PASSIONS SECTION -->
  <section id="passions" class="section section-passions">
    <div class="container">
      <h2>Passions</h2>
      <p class="section-subtitle">Sport, music, arts, associations — evidencing soft skills</p>
      
      <div class="passions-grid">
        <div class="passion-card">
          <span class="passion-icon">⚽</span>
          <h3>Sport</h3>
          <p>Description courte (équipe, niveau, fréquence).</p>
        </div>
        <div class="passion-card">
          <span class="passion-icon">🎵</span>
          <h3>Music</h3>
          <p>Instrument, années de pratique, concerts.</p>
        </div>
        <div class="passion-card">
          <span class="passion-icon">🎨</span>
          <h3>Arts</h3>
          <p>Activité artistique et engagement.</p>
        </div>
        <div class="passion-card">
          <span class="passion-icon">🤝</span>
          <h3>Associations</h3>
          <p>Rôle dans une asso étudiante ou autre.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- 6. CIVIC ENGAGEMENT SECTION -->
  <section id="civic" class="section section-civic">
    <div class="container">
      <h2>Civic Engagement</h2>
      <p class="section-subtitle">Social, environmental or civic engagement</p>
      
      <div class="engagement-list">
        <article class="engagement-item">
          <h3>Engagement 1 (ex: WomeN7)</h3>
          <p>Que fais-tu ? Pourquoi ? Impact attendu ?</p>
        </article>
        <article class="engagement-item">
          <h3>Engagement 2 (ex: Volontariat)</h3>
          <p>Description de l'action et de sa motivation.</p>
        </article>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="footer">
    <div class="container">
      <p>&copy; 2026 Prénom NOM — Built with GitHub Pages</p>
      <div class="social-links">
        <a href="mailto:votre@email.com">Email</a>
        <a href="https://linkedin.com/in/votreprofil">LinkedIn</a>
        <a href="https://github.com/votre-username">GitHub</a>
      </div>
    </div>
  </footer>

</body>
</html>
