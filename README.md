# French-Revolution-site
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>The French Revolution</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Great+Vibes&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: 'Playfair Display', serif;
      background-color: #fef6f0;
      color: #5c3a21;
      margin: 0;
      padding: 0;
      background-image: url('https://upload.wikimedia.org/wikipedia/commons/9/95/Fragonard_-_Blind_Man%27s_Buff.jpg');
      background-size: cover;
      background-attachment: fixed;
      background-position: center;
    }
    header {
      background-color: rgba(255, 245, 235, 0.95);
      padding: 2rem;
      text-align: center;
      border-bottom: 6px double gold;
      background-image: url('https://upload.wikimedia.org/wikipedia/commons/d/d2/Watteau_-_L%27Enseigne_de_Gersaint.jpg');
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;
      color: #fff;
    }
    header h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 3rem;
      color: #ffffff;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.4);
      margin: 0;
    }
    header p.subtitle {
      font-family: 'Great Vibes', cursive;
      font-size: 2.2rem;
      color: #000000; /* changed to black */
      text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
      margin: 0.5rem 0 0 0;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      background-color: #fff5e8;
      padding: 1rem;
      border-bottom: 2px solid gold;
    }
    nav a {
      color: #b8860b;
      text-decoration: none;
      font-weight: bold;
      cursor: pointer;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .page {
      display: none;
    }
    .page.active {
      display: block;
    }
    .content {
      max-width: 960px;
      margin: 2rem auto;
      padding: 2rem;
      background-color: rgba(255, 255, 255, 0.95);
      border: 3px solid gold;
      border-radius: 20px;
      box-shadow: 0 0 30px rgba(218, 165, 32, 0.3);
    }
    h2 {
      color: #a74d3c;
      border-bottom: 2px dashed #d6b19b;
      padding-bottom: 0.5rem;
      margin-top: 2rem;
    }
    p, li {
      line-height: 1.8;
      margin-bottom: 1.2rem;
    }
    .source {
      font-style: italic;
      color: #7a5b4d;
    }
    .art-gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      margin-top: 2rem;
      justify-content: center;
    }
    .art-gallery img {
      width: 220px;
      border: 4px solid gold;
      border-radius: 12px;
      box-shadow: 0 6px 12px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>
  <header>
    <h1>🌸 The French Revolution 🌸</h1>
    <p class="subtitle">Exploring Change, Power & the Voice of the People</p>
  </header>

  <nav>
    <a onclick="showPage('overview')">Overview</a>
    <a onclick="showPage('issues')">Issues</a>
    <a onclick="showPage('questions')">Inquiry</a>
    <a onclick="showPage('sources')">Sources</a>
    <a onclick="showPage('significance')">Legacy</a>
  </nav>

  <div class="content">
    <div id="overview" class="page active">
      <h2>🌿 Narrative Overview</h2>
      <p>
        The French Revolution (1789–1799) was a major turning point in France’s history. The Ancien Régime divided society into three estates: the clergy, the nobility, and the Third Estate (commoners), who made up 98% of the population but carried the tax burden. Financial crises, due to wars and royal spending, combined with Enlightenment ideas about equality and freedom, led to mass dissatisfaction. In 1789, the Estates-General was called, but the Third Estate formed the National Assembly and demanded reforms. The storming of the Bastille became a powerful symbol of change. The monarchy eventually fell, and France became a republic.
      </p>
      <div class="art-gallery">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/03/Fragonard_-_The_Swing.jpg" alt="The Swing by Fragonard" />
        <img src="https://upload.wikimedia.org/wikipedia/commons/e/e9/Boucher_Venus_and_Mercury.jpg" alt="Venus and Mercury by Boucher" />
      </div>
    </div>

    <div id="issues" class="page">
      <h2>🔰 Social & Political Issues</h2>
      <p>
        The Revolution exposed deep inequalities within French society. The Third Estate was burdened by heavy taxation while the clergy and nobility enjoyed privileges. Enlightenment ideals clashed with the realities of an absolute monarchy. Bread shortages, unemployment, and economic mismanagement further fueled public discontent. Protests and pamphlets spread revolutionary ideas, demanding liberty, equality, and fraternity.
      </p>
      <div class="art-gallery">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/02/Watteau_Pilgrimage_to_Cythera.jpg" alt="Pilgrimage to Cythera by Watteau" />
        <img src="https://upload.wikimedia.org/wikipedia/commons/2/26/Boucher-_The_Toilet_of_Venus.jpg" alt="The Toilet of Venus by Boucher" />
      </div>
    </div>

    <div id="questions" class="page">
      <h2>❓ Guiding Questions</h2>
      <ul>
        <li>What were the main causes of the French Revolution?</li>
        <li>How did the Revolution alter the structure of French society?</li>
        <li>What roles did women, peasants, and the bourgeoisie play in the Revolution?</li>
        <li>In what ways did art reflect the political climate of the era?</li>
      </ul>
      <div class="art-gallery">
        <img src="https://upload.wikimedia.org/wikipedia/commons/1/1d/Watteau_Italian_Comedians.jpg" alt="Italian Comedians by Watteau" />
      </div>
    </div>

    <div id="sources" class="page">
      <h2>🔎 Primary Sources</h2>
      <ul>
        <li><span class="source">Declaration of the Rights of Man and of the Citizen (1789)</span></li>
        <li><span class="source">Excerpts from Robespierre's speeches during the Reign of Terror</span></li>
        <li><span class="source">Pamphlets and newspapers from revolutionary Paris</span></li>
      </ul>
    </div>

    <div id="significance" class="page">
      <h2>⚓️ Lasting Legacy</h2>
      <p>
        The French Revolution profoundly changed the course of world history. It inspired movements across Europe and Latin America, emphasized human rights, and laid foundations for modern democracy. Though it descended into violence during the Reign of Terror, the ideals born from the Revolution continue to influence political discourse today.
      </p>
    </div>
  </div>

  <script>
    function showPage(id) {
      document.querySelectorAll('.page').forEach(page => page.classList.remove('active'));
      const page = document.getElementById(id);
      if (page) {
        page.classList.add('active');
      } else {
        console.error(`Page with ID '${id}' not found.`);
      }
    }
  </script>
</body>
</html>
