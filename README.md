<p align="center">
  <img
    alt="Arsalan — animated header"
    src='data:image/svg+xml;utf8,
    <svg xmlns="http://www.w3.org/2000/svg" width="960" height="220" viewBox="0 0 960 220">
      <defs>
        <linearGradient id="g1" x1="0" x2="1" y1="0" y2="1">
          <stop offset="0" stop-color="%23007cf0"/>
          <stop offset="0.5" stop-color="%23914ffe"/>
          <stop offset="1" stop-color="%23ff7eb6"/>
        </linearGradient>
        <filter id="blur">
          <feGaussianBlur stdDeviation="30" />
        </filter>
      </defs>

      <!-- background blobs -->
      <rect width="100%" height="100%" fill="transparent"/>
      <g opacity="0.45" filter="url(%23blur)">
        <ellipse cx="160" cy="40" rx="140" ry="60" fill="url(%23g1)"/>
        <ellipse cx="820" cy="120" rx="180" ry="80" fill="%23007cf0"/>
      </g>

      <!-- main text -->
      <text x="50%" y="70" text-anchor="middle" font-family="Inter, Roboto, Arial" font-weight="700"
            font-size="34" fill="white" style="letter-spacing:0.6px">
        Hi 👋, I'm Mohammad Arsalan
      </text>

      <!-- subtitle boxed -->
      <rect x="220" y="88" rx="12" ry="12" width="520" height="48" fill="rgba(255,255,255,0.06)"/>
      <text id="subtitle" x="50%" y="120" text-anchor="middle" font-family="Inter, Roboto, Arial"
            font-size="16" fill="white" style="letter-spacing:0.4px">

        <!-- We'll animate several phrases (fade in/out) to mimic a typing/rotate effect -->
        <tspan id="s1" opacity="1">🚀 Mobile App Developer • Flutter &amp; React Native • AI/ML</tspan>
        <tspan id="s2" opacity="0" dy="0"> • GenAI &amp; AgenticAI • Insightify (Scam Detection)</tspan>
        <tspan id="s3" opacity="0" dy="0"> • Hackathon Gold Honours • 100+ LeetCode Problems</tspan>

        <!-- animation controllers -->
        <animate xlink:href="%23s1" attributeName="opacity" values="1;0" dur="5s" begin="1s" repeatCount="indefinite" />
        <animate xlink:href="%23s2" attributeName="opacity" values="0;1;0" dur="5s" begin="1s" repeatCount="indefinite" />
        <animate xlink:href="%23s3" attributeName="opacity" values="0;1;0" dur="5s" begin="1s" repeatCount="indefinite" />
      </text>

      <!-- subtle underline -->
      <rect x="160" y="150" width="640" height="2" rx="1" fill="rgba(255,255,255,0.12)"/>
      <!-- corner tag: currently building -->
      <g transform="translate(720,18)">
        <rect width="200" height="28" rx="8" fill="white" opacity="0.06"/>
        <text x="100" y="19" font-family="Inter, Roboto, Arial" font-size="12" text-anchor="middle" fill="white">
          ⚙️ Currently building: Insightify
        </text>
        <!-- small pulse -->
        <circle cx="15" cy="14" r="5" fill="%23ff7eb6">
          <animate attributeName="r" values="5;9;5" dur="2s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="1;0.4;1" dur="2s" repeatCount="indefinite" />
        </circle>
      </g>
    </svg>'
    style="max-width:100%; border-radius:12px; box-shadow: 0 8px 30px rgba(16,24,40,0.25);"
  />
</p>

<!-- Quick top info as centered badges to make the top "dashboard" feel full-width -->
<p align="center">
  <img alt="Profile Views" src="https://komarev.com/ghpvc/?username=arsalanthecoder&label=Profile%20Views&color=0e75b6&style=flat" />
  &nbsp;&nbsp;
  <img alt="Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=arsalanthecoder&layout=compact" />
  &nbsp;&nbsp;
  <img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=arsalanthecoder&show_icons=true" />
</p>

---

<!-- ABOUT / SUMMARY — centered and full-width -->
<p align="center">
  <strong>Mohammad Arsalan</strong> — Mobile App Developer &amp; AI/ML practitioner building production mobile experiences.
  I lead engineering on <em>Insightify</em> (Scam Detection), ship Flutter &amp; React Native apps, prototype GenAI agents, and compete in hackathons.
</p>

<!-- Two-column "dashboard-like" layout using a table so content uses full page width on GitHub -->
<table width="100%" cellpadding="12">
  <tr>

    <!-- LEFT: Main profile / projects / activity (wider) -->
    <td valign="top" width="62%" style="padding-right:16px;">

      <!-- Current focus (live) -->
      <h3>🔧 Currently Building (Live)</h3>
      <p>
        <strong>Insightify — Scam Detection</strong><br/>
        Real-time detection across text, image & audio using hybrid on-device + server models. Flutter &amp; React Native clients,
        Node.js backend, PostgreSQL, and TFLite models for privacy-first inference.
      </p>

      <!-- Pinned / Featured project card (visual) -->
      <p>
        <a href="https://github.com/ArsalanTheCoder/Insightify" target="_blank" rel="noreferrer">
          <img alt="Insightify — featured" src="https://img.shields.io/badge/Featured-Insightify-7b61ff?style=for-the-badge&logo=appveyor" />
        </a>
        &nbsp;
        <a href="https://github.com/ArsalanTheCoder" target="_blank" rel="noreferrer">
          <img alt="Open Repos" src="https://img.shields.io/badge/Repos-Explore-0ea5e9?style=for-the-badge&logo=github" />
        </a>
      </p>

      <!-- Achievements / Hackathons -->
      <h3>🏆 Achievements & Hackathons</h3>
      <ul>
        <li><strong>ICSC 2025</strong> — Gold Honour (Top 1% worldwide)</li>
        <li>AgentPay — Team Lead for AI Agent Arc (lablab.ai)</li>
        <li>100+ LeetCode problems solved — Strong DSA foundation</li>
        <li>Participated &amp; placed in multiple hackathons (team lead & contributor)</li>
      </ul>

      <!-- GitHub activity graph (makes the page look like a live dashboard) -->
      <h3>📈 GitHub Activity</h3>
      <p>
        <img alt="Arsalan's GitHub activity graph" src="https://ghchart.rshah.org/arsalanthecoder" style="max-width:100%; border-radius:8px; box-shadow: 0 8px 24px rgba(2,6,23,0.12);" />
      </p>

      <!-- Contribution / Stats widgets -->
      <p>
        <img alt="GitHub commits & contributions" src="https://github-readme-streak-stats.herokuapp.com/?user=arsalanthecoder&theme=default" />
      </p>

    </td>

    <!-- RIGHT: Skills, Tools, Contact (narrower, but full height) -->
    <td valign="top" width="38%" style="padding-left:16px; border-left:1px solid rgba(0,0,0,0.06);">

      <!-- Skills block centered to make UI symmetric -->
      <h3 align="center">🛠 Skills & Tools</h3>
      <p align="center" style="line-height:1.8">
        <!-- Mobile -->
        <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" width="36" title="Flutter" />&nbsp;
        <img src="https://reactnative.dev/img/header_logo.svg" width="36" title="React Native" />&nbsp;
        <img src="https://www.vectorlogo.zone/logos/dartlang/dartlang-icon.svg" width="36" title="Dart" />&nbsp;
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="36" title="JavaScript" />&nbsp;

        <!-- Backend / Data -->
        <br/>
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="36" title="Node.js" />&nbsp;
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="36" title="Python" />&nbsp;
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" width="36" title="PostgreSQL" />&nbsp;
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" width="36" title="MySQL" />&nbsp;

        <!-- ML -->
        <br/>
        <img src="https://raw.githubusercontent.com/google-coral/edgetpu-api/master/images/tflite.png" width="36" title="TensorFlow Lite" />&nbsp;
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" width="36" title="scikit-learn" />&nbsp;
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" width="36" title="Pandas" />&nbsp;

        <!-- Tools -->
        <br/>
        <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" width="36" title="Git" />&nbsp;
        <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" width="36" title="Firebase" />&nbsp;
        <img src="https://www.vectorlogo.zone/logos/visualstudio_code/visualstudio_code-icon.svg" width="36" title="VSCode" />
      </p>

      <!-- Quick contact and profile links -->
      <h3 align="center">📫 Contact & Links</h3>
      <p align="center">
        ✉️ <a href="mailto:mohammad.arsalan.dev@gmail.com">mohammad.arsalan.dev@gmail.com</a><br/>
        📍 Mirpurkhas, Sindh, Pakistan<br/>
        <a href="https://github.com/ArsalanTheCoder">GitHub</a> • <a href="https://www.linkedin.com/in/mohammad-arsalan-83631b2aa">LinkedIn</a> • <a href="https://kaggle.com/arsalansahab7866">Kaggle</a>
      </p>

      <!-- Short "profile metrics" using badges to show contributions & achievements at-a-glance -->
      <h3 align="center">📊 Quick Metrics</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/LeetCode-100%2B-ff8c00?style=for-the-badge&logo=leetcode" alt="LeetCode" /><br/>
        <img src="https://img.shields.io/badge/ICSC-2025%20Gold-ffd700?style=for-the-badge" alt="ICSC Gold" />
      </p>

    </td>
  </tr>
</table>

---

<!-- footer -->
<p align="center" style="margin-top:18px; color:rgba(0,0,0,0.6)">
  Built with ❤️ • Fluent in Flutter & React Native • AI/ML for mobile • Want a custom variant? Ask me — I'll generate a tailored header or SVG.
</p>
