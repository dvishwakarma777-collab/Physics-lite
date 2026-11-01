# Physics-lite
A portal to help the Physics aspirants
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="theme-color" content="#f6f7f2" />
    <meta name="description" content="A focused physics study space for JEE and NEET aspirants." />
    <title>Fieldnotes — Physics prep, made clearer</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link href="https://fonts.googleapis.com/css2?family=DM+Mono:wght@400;500&family=DM+Sans:wght@400;500;600;700&family=Newsreader:opsz,wght@6..72,500;6..72,600&display=swap" rel="stylesheet" />
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="app-shell">
      <aside class="sidebar" aria-label="Main navigation">
        <a class="brand" href="#home" aria-label="Fieldnotes home">
          <span class="brand-mark" aria-hidden="true">f.</span>
          <span>fieldnotes<span class="brand-period">.</span></span>
        </a>

        <p class="nav-caption">YOUR SPACE</p>
        <nav class="primary-nav">
          <a class="nav-link is-active" href="#home" data-view="home"><span class="nav-index">01</span>Overview</a>
          <a class="nav-link" href="#syllabus" data-view="syllabus"><span class="nav-index">02</span>Syllabus</a>
          <a class="nav-link" href="#practice" data-view="practice"><span class="nav-index">03</span>Practice</a>
          <a class="nav-link" href="#formulas" data-view="formulas"><span class="nav-index">04</span>Formula book</a>
        </nav>

        <div class="sidebar-note">
          <span class="note-label">A SMALL REMINDER</span>
          <p>One good problem at a time. That's how the big ones get easier.</p>
          <span class="note-mark" aria-hidden="true">∴</span>
        </div>

        <div class="profile-row">
          <div class="avatar" aria-hidden="true">A</div>
          <div><strong>My study space</strong><span>Keep showing up.</span></div>
          <button class="profile-menu" aria-label="Profile options" title="Profile options">···</button>
        </div>
      </aside>

      <main class="main-content" id="home">
        <header class="topbar">
          <div class="breadcrumbs"><span>MY DESK</span><span class="crumb-slash">/</span><span id="current-section">OVERVIEW</span></div>
          <div class="topbar-actions">
            <span class="exam-label">PREPARING FOR</span>
            <div class="exam-switch" role="group" aria-label="Choose your exam">
              <button class="exam-option is-selected" data-exam="JEE" aria-pressed="true">JEE</button>
              <button class="exam-option" data-exam="NEET" aria-pressed="false">NEET</button>
            </div>
            <span class="today-date" id="today-date"></span>
          </div>
        </header>

        <section class="welcome-section" aria-labelledby="welcome-title">
          <div class="welcome-copy">
            <p class="eyebrow"><span class="eyebrow-dot"></span> YOUR PHYSICS STUDY SPACE</p>
            <h1 id="welcome-title">Make sense<br />of <em>the universe.</em></h1>
            <p class="welcome-description">A little more understanding today. A lot more confidence on exam day.</p>
          </div>
          <div class="welcome-side">
            <p class="welcome-side-label">YOUR STREAK</p>
            <div class="streak-count"><span id="streak-count">4</span><span class="streak-unit">days<br />in a row</span></div>
            <div class="streak-dots" aria-label="4 day study streak">
              <span class="streak-day done">M</span><span class="streak-day done">T</span><span class="streak-day done">W</span><span class="streak-day today">T</span><span class="streak-day">F</span><span class="streak-day">S</span><span class="streak-day">S</span>
            </div>
            <span class="streak-caption">Keep the rhythm going.</span>
          </div>
        </section>

        <section class="daily-row" aria-label="Daily study progress">
          <div class="daily-intro"><span class="section-kicker">TODAY, AT A GLANCE</span><p>A focused session beats a perfect plan.</p></div>
          <div class="daily-stat"><span class="stat-label">STUDY TIME</span><strong><span id="study-minutes">35</span><small> / 90 min</small></strong><div class="progress-track"><span id="time-progress" style="width:39%"></span></div></div>
          <div class="daily-stat"><span class="stat-label">QUESTIONS</span><strong><span id="question-count">8</span><small> / 20 done</small></strong><div class="progress-track"><span id="question-progress" style="width:40%"></span></div></div>
          <button class="goal-button" id="start-session"><span>Continue your session</span><span aria-hidden="true">↗</span></button>
        </section>

        <section class="study-section" aria-label="Continue studying">
          <div class="section-heading"><div><span class="section-kicker">PICK UP WHERE YOU LEFT OFF</span><h2>Your next <em>good question.</em></h2></div><a class="text-link" href="#syllabus">All chapters <span aria-hidden="true">→</span></a></div>
          <article class="chapter-feature" id="syllabus">
            <div class="chapter-copy">
              <div class="chapter-meta"><span class="chapter-number">CHAPTER 04</span><span class="meta-divider"></span><span>MECHANICS</span></div>
              <h3>Work, energy<br />&amp; power</h3>
              <p>Build your intuition for how forces transfer energy, and when they don't.</p>
              <div class="chapter-progress-label"><span>CHAPTER PROGRESS</span><strong>3 of 8 concepts</strong></div>
              <div class="chapter-progress"><span></span></div>
              <button class="chapter-button" id="continue-chapter">Continue learning <span aria-hidden="true">↗</span></button>
            </div>
            <div class="chapter-image" role="img" aria-label="A view of Earth from space">
              <div class="image-caption"><span>ENERGY IS NEVER LOST.</span><span>IT JUST CHANGES FORM.</span></div>
              <span class="image-coordinate">φ = 0.618</span>
            </div>
          </article>
        </section>

        <section class="lower-grid">
          <div class="practice-panel" id="practice-panel">
            <div class="section-heading compact-heading"><div><span class="section-kicker">A QUICK ONE</span><h2>Think it through.</h2></div><span class="question-tag">01 / 01</span></div>
            <p class="question-text">A body is thrown vertically upward. At its highest point, which statement is true?</p>
            <div class="answer-list" role="group" aria-label="Choose an answer">
              <button class="answer-option" data-answer="A"><span>A</span>Both velocity and acceleration are zero</button>
              <button class="answer-option" data-answer="B"><span>B</span>Velocity is zero, acceleration is g downward</button>
              <button class="answer-option" data-answer="C"><span>C</span>Velocity is g upward, acceleration is zero</button>
            </div>
            <p class="answer-feedback" id="answer-feedback" aria-live="polite"></p>
          </div>

          <div class="formula-panel" id="formula-panel">
            <div class="section-heading compact-heading"><div><span class="section-kicker">KEEP IT CLOSE</span><h2>On the tip of your tongue.</h2></div><button class="formula-search" id="formula-search" aria-label="Search formulas" title="Search formulas">⌕</button></div>
            <div class="formula-feature">
              <span class="formula-subject">KINEMATICS · 1D MOTION</span>
              <p class="formula-equation">v² = u² + 2as</p>
              <p class="formula-caption">The one that leaves time out of the picture.</p>
            </div>
            <button class="formula-link" id="browse-formulas">Browse formula book <span aria-hidden="true">→</span></button>
          </div>
        </section>
        <footer class="page-footer"><span>PHYSICS, ONE IDEA AT A TIME.</span><span>MADE FOR THE CURIOUS.</span></footer>
      </main>
    </div>
    <dialog class="formula-dialog" id="formula-dialog" aria-labelledby="dialog-title">
      <div class="dialog-header"><div><span class="section-kicker">YOUR QUICK REFERENCE</span><h2 id="dialog-title">Formula book</h2></div><button class="dialog-close" id="close-dialog" aria-label="Close formula book">×</button></div>
      <label class="formula-input-label" for="formula-filter">Search by topic or formula</label>
      <input id="formula-filter" class="formula-input" type="search" placeholder="Try 'motion' or 'F = ma'" />
      <div class="formula-list" id="formula-list"></div>
    </dialog>
    <script src="app.js"></script>
  </body>
</html>
