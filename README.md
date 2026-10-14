# Blesswin-2k10.github.io
Personal Record

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport"
        content="width=device-width, initial-scale=1.0">
  <title>Personal Record</title>

  <style>
    :root {
      --bg: #101110;
      --panel: #191a17;
      --ivory: #eee8da;
      --muted: #aaa89f;
      --gold: #b89a60;
      --line: #34332c;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      background: var(--bg);
      color: var(--ivory);
      font-family: Georgia, "Times New Roman", serif;
      line-height: 1.7;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    .container {
      width: min(100% - 36px, 1000px);
      margin: auto;
    }

    header {
      border-bottom: 1px solid var(--line);
      padding: 20px 0;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 16px;
    }

    .logo {
      color: var(--gold);
      font-size: 19px;
      letter-spacing: 3px;
      font-weight: bold;
    }

    .nav-links {
      display: flex;
      gap: 18px;
      font-size: 12px;
      color: var(--muted);
    }

    .hero {
      padding: 85px 0 75px;
      border-bottom: 1px solid var(--line);
    }

    .eyebrow {
      color: var(--gold);
      text-transform: uppercase;
      letter-spacing: 4px;
      font: 11px Arial, sans-serif;
      margin-bottom: 24px;
    }

    h1 {
      font-size: clamp(43px, 10vw, 76px);
      line-height: 1.08;
      font-weight: normal;
      letter-spacing: -2px;
      margin-bottom: 24px;
    }

    h1 span {
      color: var(--gold);
      font-style: italic;
    }

    .intro {
      color: var(--muted);
      font: 15px/1.9 Arial, sans-serif;
      max-width: 480px;
      margin-bottom: 30px;
    }

    .button {
      display: inline-block;
      border: 1px solid var(--gold);
      color: var(--ivory);
      padding: 11px 20px;
      font: 12px Arial, sans-serif;
      letter-spacing: 1px;
    }

    .button:hover {
      background: var(--gold);
      color: var(--bg);
    }

    section {
      padding: 55px 0;
      border-bottom: 1px solid var(--line);
    }

    .section-label {
      color: var(--gold);
      font: 11px Arial, sans-serif;
      letter-spacing: 3px;
      text-transform: uppercase;
      margin-bottom: 12px;
    }

    h2 {
      font-size: 31px;
      font-weight: normal;
      margin-bottom: 20px;
    }

    .body-text {
      color: var(--muted);
      font: 14px/1.9 Arial, sans-serif;
      max-width: 650px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 15px;
      margin-top: 25px;
    }

    .card {
      background: var(--panel);
      border: 1px solid var(--line);
      padding: 22px;
    }

    .card-number {
      color: var(--gold);
      font: 11px Arial, sans-serif;
      letter-spacing: 2px;
    }

    h3 {
      font-size: 21px;
      font-weight: normal;
      margin: 12px 0;
    }

    .card p {
      color: var(--muted);
      font: 13px/1.8 Arial, sans-serif;
    }

    .quote {
      color: var(--ivory);
      font-size: 25px;
      font-style: italic;
      max-width: 600px;
    }

    .quote span {
      color: var(--gold);
    }

    footer {
      padding: 25px 0;
      color: var(--muted);
      font: 11px Arial, sans-serif;
      letter-spacing: 1px;
    }

    footer .container {
      display: flex;
      justify-content: space-between;
      gap: 12px;
      flex-wrap: wrap;
    }

    @media (max-width: 480px) {
      .container {
        width: calc(100% - 30px);
      }

      .nav-links {
        gap: 10px;
        font-size: 11px;
      }

      .hero {
        padding: 65px 0 55px;
      }

      .grid {
        grid-template-columns: 1fr;
      }

      h2 {
        font-size: 27px;
      }
    }
  </style>
</head>

<body>

  <header>
    <nav class="container">
      <a class="logo" href="#home">PR.</a>

      <div class="nav-links">
        <a href="#about">About</a>
        <a href="#journey">Journey</a>
        <a href="#projects">Projects</a>
      </div>
    </nav>
  </header>

  <main>
    <div class="container">
      <section class="hero" id="home">
        <p class="eyebrow">Personal archive · Est. 2026</p>

        <h1>PERSONAL<br><span>RECORD.</span></h1>

        <p class="intro">
          A record of the work, lessons and ambitions
          that shape who I am becoming. Quiet progress.
          Real skills. My own path.
        </p>

        <a class="button" href="#about">
          ENTER MY WORLD &rarr;
        </a>
      </section>

      <section id="about">
        <p class="section-label">01 / The person</p>
        <h2>More than a name.</h2>

        <p class="body-text">
          I'm someone who believes in improving through
          practice, learning from mistakes and building
          things that matter. This website is my space
          to document that journey — one step at a time.
        </p>
      </section>

      <section id="journey">
        <p class="section-label">02 / The journey</p>
        <h2>Work in progress.</h2>

        <div class="grid">
          <article class="card">
            <span class="card-number">01 — FOOTBALL</span>
            <h3>The Game</h3>
            <p>
              Training, teamwork, decision-making and
              the pursuit of becoming a better player.
            </p>
          </article>

          <article class="card">
            <span class="card-number">02 — LEARNING</span>
            <h3>The Craft</h3>
            <p>
              Learning web development and turning
              ideas into working projects.
            </p>
          </article>

          <article class="card">
            <span class="card-number">03 — DISCIPLINE</span>
            <h3>The Process</h3>
            <p>
              Building good habits, keeping promises
              and making consistent progress.
            </p>
          </article>

          <article class="card">
            <span class="card-number">04 — THE FUTURE</span>
            <h3>What's Next</h3>
            <p>
              New skills, new projects and goals
              worth working towards.
            </p>
          </article>
        </div>
      </section>

      <section id="projects">
        <p class="section-label">03 / The archive</p>
        <h2>Things I build.</h2>

        <p class="body-text">
          Every project begins as an idea. This section
          will grow as I learn, experiment and create
          things of my own.
        </p>

        <div class="grid">
          <article class="card">
            <span class="card-number">PROJECT 001</span>
            <h3>Personal Record</h3>
            <p>
              My first website. A starting point for
              learning design and development.
            </p>
          </article>

          <article class="card">
            <span class="card-number">PROJECT 002</span>
            <h3>Coming Soon</h3>
            <p>
              The next idea is waiting to be built.
            </p>
          </article>
        </div>
      </section>

      <section>
        <p class="section-label">04 / The principle</p>
        <p class="quote">
          "Less noise.<br>
          More <span>substance.</span><br>
          Progress over performance."
        </p>
      </section>
    </div>
  </main>

  <footer>
    <div class="container">
      <span>PERSONAL RECORD © 2026</span>
      <span>BUILT FROM ZERO.</span>
    </div>
  </footer>

</body>
</html>
