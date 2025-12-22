<!-- =========================================================
  SKILL DASHBOARD (clean, extendable, no JS)
  - UX: click a pill -> jump to the selected skill card
  - Edit: add/remove a skill by duplicating ONE <details> block
  - Percent -> BAR width = 720 * (PERCENT/100)
========================================================= -->

<div align="center">

<!-- ======= SECTION HEADER (minimal) ======= -->
<h2 style="margin-bottom: 6px;">▌ Skill Dashboard</h2>
<p style="margin-top: 0; max-width: 820px; color: #8b949e;">
  Tek panel, tek standart: seç → ilgili uzmanlık kartına git.
</p>

<!-- ======= SELECTOR PILLS (click -> anchor) ======= -->
<p>
  <a href="#skill-dotnet"><img alt=".NET / C#" src="https://img.shields.io/badge/.NET%20%2F%20C%23-95%25-7c3aed?style=for-the-badge&labelColor=0d1117" /></a>
  <a href="#skill-arch"><img alt="System Architecture" src="https://img.shields.io/badge/Architecture-90%25-1f6feb?style=for-the-badge&labelColor=0d1117" /></a>
  <a href="#skill-sql"><img alt="SQL / Modeling" src="https://img.shields.io/badge/SQL%20%2F%20Modeling-85%25-d29922?style=for-the-badge&labelColor=0d1117" /></a>
  <a href="#skill-py"><img alt="Python / Automation" src="https://img.shields.io/badge/Python%20Automation-75%25-2ea043?style=for-the-badge&labelColor=0d1117" /></a>
  <a href="#skill-fe"><img alt="Frontend Integration" src="https://img.shields.io/badge/Frontend%20Integration-60%25-e5534b?style=for-the-badge&labelColor=0d1117" /></a>
</p>

</div>

<!-- ======= SKILL CARDS (one per skill) =======
HOW TO EDIT:
- id: skill-xxx (must match pill href)
- PERCENT: change the number in title and aria-label
- BAR WIDTH: 720 * (PERCENT/100)
  Examples:
  95% => 684
  90% => 648
  85% => 612
  75% => 540
  60% => 432
============================================ -->

<!-- .NET -->
<details id="skill-dotnet" open>
  <summary><b>.NET / C# Core — 95%</b> <span style="color:#8b949e;">(backend fundamentals, clean architecture)</span></summary>
  <br/>
  <svg width="920" height="64" viewBox="0 0 920 64" xmlns="http://www.w3.org/2000/svg" role="img" aria-label=".NET / C# Core 95%">
    <defs>
      <linearGradient id="g-dotnet" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0" stop-color="#7c3aed"/>
        <stop offset="1" stop-color="#a371f7"/>
      </linearGradient>
    </defs>

    <!-- Card -->
    <rect x="0" y="0" width="920" height="64" rx="14" fill="#0d1117" stroke="#30363d"/>
    <!-- Title -->
    <text x="22" y="24" fill="#e6edf3" font-size="14" font-family="ui-sans-serif, system-ui" font-weight="700">Scope</text>
    <text x="22" y="44" fill="#8b949e" font-size="12" font-family="ui-sans-serif, system-ui" font-weight="600">
      ASP.NET Core • EF Core • Identity/AuthZ • API Design • Performance & Diagnostics
    </text>

    <!-- Bar -->
    <rect x="650" y="22" width="240" height="20" rx="10" fill="#161b22" stroke="#30363d"/>
    <rect x="650" y="22" width="228" height="20" rx="10" fill="url(#g-dotnet)"/>
    <text x="888" y="36" fill="#c9d1d9" font-size="11" font-family="ui-sans-serif, system-ui" font-weight="800" text-anchor="end">95%</text>
  </svg>
  <br/>
</details>

<!-- Architecture -->
<details id="skill-arch">
  <summary><b>System Architecture — 90%</b> <span style="color:#8b949e;">(design, scalability, operability)</span></summary>
  <br/>
  <svg width="920" height="64" viewBox="0 0 920 64" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="System Architecture 90%">
    <defs>
      <linearGradient id="g-arch" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0" stop-color="#1f6feb"/>
        <stop offset="1" stop-color="#79c0ff"/>
      </linearGradient>
    </defs>

    <rect x="0" y="0" width="920" height="64" rx="14" fill="#0d1117" stroke="#30363d"/>
    <text x="22" y="24" fill="#e6edf3" font-size="14" font-family="ui-sans-serif, system-ui" font-weight="700">Scope</text>
    <text x="22" y="44" fill="#8b949e" font-size="12" font-family="ui-sans-serif, system-ui" font-weight="600">
      Clean Architecture • DDD-ish Boundaries • CQRS (where it pays) • Observability • Failure Modes
    </text>

    <rect x="650" y="22" width="240" height="20" rx="10" fill="#161b22" stroke="#30363d"/>
    <rect x="650" y="22" width="216" height="20" rx="10" fill="url(#g-arch)"/>
    <text x="888" y="36" fill="#c9d1d9" font-size="11" font-family="ui-sans-serif, system-ui" font-weight="800" text-anchor="end">90%</text>
  </svg>
  <br/>
</details>

<!-- SQL -->
<details id="skill-sql">
  <summary><b>SQL / Data Modeling — 85%</b> <span style="color:#8b949e;">(integrity, constraints, migrations)</span></summary>
  <br/>
  <svg width="920" height="64" viewBox="0 0 920 64" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="SQL / Data Modeling 85%">
    <defs>
      <linearGradient id="g-sql" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0" stop-color="#d29922"/>
        <stop offset="1" stop-color="#f2cc60"/>
      </linearGradient>
    </defs>

    <rect x="0" y="0" width="920" height="64" rx="14" fill="#0d1117" stroke="#30363d"/>
    <text x="22" y="24" fill="#e6edf3" font-size="14" font-family="ui-sans-serif, system-ui" font-weight="700">Scope</text>
    <text x="22" y="44" fill="#8b949e" font-size="12" font-family="ui-sans-serif, system-ui" font-weight="600">
      Relational Modeling • Index Strategy • Constraints • Query Tuning • EF Core Migrations
    </text>

    <rect x="650" y="22" width="240" height="20" rx="10" fill="#161b22" stroke="#30363d"/>
    <rect x="650" y="22" width="204" height="20" rx="10" fill="url(#g-sql)"/>
    <text x="888" y="36" fill="#c9d1d9" font-size="11" font-family="ui-sans-serif, system-ui" font-weight="800" text-anchor="end">85%</text>
  </svg>
  <br/>
</details>

<!-- Python -->
<details id="skill-py">
  <summary><b>Python / Automation — 75%</b> <span style="color:#8b949e;">(tooling, scripts, pipelines)</span></summary>
  <br/>
  <svg width="920" height="64" viewBox="0 0 920 64" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Python / Automation 75%">
    <defs>
      <linearGradient id="g-py" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0" stop-color="#2ea043"/>
        <stop offset="1" stop-color="#7ee787"/>
      </linearGradient>
    </defs>

    <rect x="0" y="0" width="920" height="64" rx="14" fill="#0d1117" stroke="#30363d"/>
    <text x="22" y="24" fill="#e6edf3" font-size="14" font-family="ui-sans-serif, system-ui" font-weight="700">Scope</text>
    <text x="22" y="44" fill="#8b949e" font-size="12" font-family="ui-sans-serif, system-ui" font-weight="600">
      Scripting • Automation • CLI Tooling • Data Ops Helpers • System Glue
    </text>

    <rect x="650" y="22" width="240" height="20" rx="10" fill="#161b22" stroke="#30363d"/>
    <rect x="650" y="22" width="180" height="20" rx="10" fill="url(#g-py)"/>
    <text x="888" y="36" fill="#c9d1d9" font-size="11" font-family="ui-sans-serif, system-ui" font-weight="800" text-anchor="end">75%</text>
  </svg>
  <br/>
</details>

<!-- Frontend -->
<details id="skill-fe">
  <summary><b>Frontend Integration — 60%</b> <span style="color:#8b949e;">(integration, not “UI artist”)</span></summary>
  <br/>
  <svg width="920" height="64" viewBox="0 0 920 64" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Frontend Integration 60%">
    <defs>
      <linearGradient id="g-fe" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0" stop-color="#e5534b"/>
        <stop offset="1" stop-color="#ffa198"/>
      </linearGradient>
    </defs>

    <rect x="0" y="0" width="920" height="64" rx="14" fill="#0d1117" stroke="#30363d"/>
    <text x="22" y="24" fill="#e6edf3" font-size="14" font-family="ui-sans-serif, system-ui" font-weight="700">Scope</text>
    <text x="22" y="44" fill="#8b949e" font-size="12" font-family="ui-sans-serif, system-ui" font-weight="600">
      API Integration • Auth Flows • Minimal UI • Tooling Pages • Dashboard Wiring
    </text>

    <rect x="650" y="22" width="240" height="20" rx="10" fill="#161b22" stroke="#30363d"/>
    <rect x="650" y="22" width="144" height="20" rx="10" fill="url(#g-fe)"/>
    <text x="888" y="36" fill="#c9d1d9" font-size="11" font-family="ui-sans-serif, system-ui" font-weight="800" text-anchor="end">60%</text>
  </svg>
  <br/>
</details>

<!-- Optional: back-to-selector -->
<div align="center">
  <a href="#skill-dashboard-top"></a>
  <p style="margin-top: 10px;">
    <a href="#skill-dotnet">↑ Back to Skills</a>
  </p>
</div>
