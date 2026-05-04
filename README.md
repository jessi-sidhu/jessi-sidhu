<!-- HEADER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=110&color=FFA5D6"/>
</p>

<div align="center">
  <img src="https://i.pinimg.com/originals/5d/6f/2c/5d6f2ce38846c98cd7ebf46374a5ab52.gif" width="200" alt="Peach Goma GIF"/>
</div>

<p align="left">
  <strong>
    <img src="https://readme-typing-svg.herokuapp.com?font=Courier+Prime&pause=100&color=FFA5D6&width=750&lines=Hi,+I'm+Jessi+Sidhu!;+Fullstack+Developer+%7C+Data+Analyst"/>
  </strong>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:FFD6EC,50:FFA5D6,100:CDB4FF" width="100%"/>
</p>

<!-- SOCIAL LINKS -->
<p align="center">
  <a href="https://www.linkedin.com/in/jessisidhu/" target="_blank">
    <img src="https://img.icons8.com/color/48/linkedin.png" width="40" alt="LinkedIn"/>
  </a>
  <a href="mailto:jessisidhu04@gmail.com">
    <img src="https://img.icons8.com/color/48/gmail.png" width="40" alt="Gmail"/>
  </a>
  <a href="https://github.com/jessi-sidhu" target="_blank">
    <img src="https://img.icons8.com/material-outlined/48/github.png" width="40" alt="GitHub"/>
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:FFD6EC,50:FFA5D6,100:CDB4FF" width="100%"/>
</p>

<!-- ABOUT ME -->
<h2>🌟 About Me</h2>

<p>
I'm a <strong>Computer Science &amp; Statistics student at the University of British Columbia</strong> with a strong interest in <strong>full-stack software development, data analytics, and building scalable digital systems</strong>.
</p>

<p>
I enjoy designing applications that combine clean user experiences with strong technical foundations, and I’m especially interested in how software engineering, data-driven decision making, and modern development practices can be applied to solve real-world problems.
</p>

<p>✨ <strong>Interests</strong></p>

<ul>
  <li>Building <strong>modern web applications</strong> using React, TypeScript, and frontend frameworks</li>
  <li>Exploring <strong>data analysis, visualization, and applied machine learning</strong></li>
  <li>Designing <strong>accessible and intuitive digital experiences</strong></li>
  <li>Mentoring students and supporting <strong>technology education initiatives</strong></li>
</ul>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:FFD6EC,50:FFA5D6,100:CDB4FF" width="100%"/>
</p>

<!-- EXPERIENCE -->
<h2>💼 Current Experience</h2>

<h3>Research Data &amp; Communications Assistant — UBC Faculty of Applied Science, Research and Partnerships</h3>
<p><em>May 2026 – Aug 2026 · Vancouver, B.C.</em></p>
<ul>
  <li>Aggregate publication, citation, and grant data across <strong>SciVal, RISE, PAIR, and Workday</strong> to produce performance metrics for the Faculty’s annual research report distributed to senior leadership</li>
  <li>Build <strong>reproducible reporting pipelines</strong> consolidating funding and output data across 8 academic units, replacing manual spreadsheet workflows used in prior cycles</li>
  <li>Design <strong>visualizations of funding and citation trends</strong> to communicate findings to non-technical stakeholders</li>
</ul>

<h3>STEM Facilitator — Steamoji</h3>
<p><em>Jan 2025 – Present · Burnaby, B.C.</em></p>
<ul>
  <li>Lead weekly engineering and programming sessions for <strong>20+ students</strong>, covering physical computing, digital fabrication, and embedded programming on microcontroller platforms</li>
  <li>Coach teams of 4–6 through full <strong>debug cycles on multi-week capstone builds</strong>, raising on-time project completion across cohorts</li>
</ul>

<h3>Workshop Facilitator — UBC GirlsSmart4Tech</h3>
<p><em>Sep 2025 – Present · Vancouver, B.C.</em></p>
<ul>
  <li>Lead hands-on programming workshops for <strong>30+ high school students per session</strong>, teaching control flow, functions, and debugging through guided coding exercises</li>
  <li>Synthesize post-session feedback into recommendations delivered to the <strong>UBC Computer Science department</strong>, directly shaping curriculum revisions for subsequent workshop cycles</li>
</ul>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:FFD6EC,50:FFA5D6,100:CDB4FF" width="100%"/>
</p>

<!-- PROJECTS -->
<h2>🚀 Featured Projects</h2>

<h3>Plume</h3>
<p><strong>Tech:</strong> Rust • Apache Arrow • Parquet • DuckDB • Rayon</p>
<ul>
  <li>Built a <strong>Rust query engine</strong> over CSV and Parquet using Arrow RecordBatch pipelines; structured as a 5-crate workspace with <strong>168 tests, zero warnings</strong>, and a typed DataFrame builder API</li>
  <li>Implemented a <strong>5-rule logical-plan optimizer</strong> (constant folding, dead-projection elimination, predicate pushdown, column pruning, limit pushdown) wired to Parquet row-group statistics, cutting scanned rows from <strong>1M to 125K (8x reduction)</strong> on benchmark queries</li>
  <li>Designed a <strong>differential test harness</strong> comparing canonicalized engine output against embedded DuckDB across hundreds of generated queries</li>
  <li>Added opt-in <strong>Rayon parallel Parquet scan</strong> streaming row-group results via mpsc channels</li>
</ul>

<h3>FailureForge</h3>
<p><strong>Tech:</strong> Python • Docker • SQLite • Typer • Pumba</p>
<ul>
  <li>Built a <strong>chaos engineering CLI</strong> that injects network latency, packet loss, and container kills into Docker Compose stacks to surface resilience gaps in multi-service applications</li>
  <li>Designed a <strong>YAML-driven experiment runner</strong> that orchestrates fault injection, polls service health endpoints in real time, and persists run history to SQLite for cross-experiment comparison</li>
  <li>Implemented a <strong>reporting engine</strong> computing p95 latency, availability, and recovery time per fault scenario, surfacing measurable degradation thresholds across reproducible test runs</li>
</ul>

<h3>TA Pro <em>(Hackathon, Feb 2025)</em></h3>
<p><strong>Tech:</strong> React • TypeScript • Supabase • Node.js • OpenAI API • Tailwind CSS</p>
<ul>
  <li>Built an <strong>AI teaching assistant</strong> that ingests course materials and answers student questions in real time, shipped end-to-end in <strong>24 hours with a 3-person team</strong></li>
  <li>Designed the <strong>React/TypeScript student interface</strong> and Node.js backend handling Supabase persistence and streaming OpenAI responses, supporting concurrent question submissions during live demo</li>
</ul>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:FFD6EC,50:FFA5D6,100:CDB4FF" width="100%"/>
</p>

<!-- TECH STACK -->
<h2>🛠 Tech Stack</h2>

<p><strong>Programming Languages</strong><br/>
Rust | Python | Java | C++ | TypeScript | JavaScript | R | SQL
</p>

<p><strong>Frameworks &amp; Tools</strong><br/>
React | Node.js | Tailwind CSS | Pandas | Apache Arrow | Parquet | Rayon | Docker | Git | jUnit | Vite | Figma
</p>

<p><strong>Databases</strong><br/>
PostgreSQL | MongoDB | DuckDB | SQLite
</p>

<p><strong>Other</strong><br/>
REST APIs | Responsive Design | JSON | Object-Oriented Programming | GitHub | UI/UX Prototyping
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:FFD6EC,50:FFA5D6,100:CDB4FF" width="100%"/>
</p>

<!-- CONNECT -->
<h2>📌 Let's Connect</h2>

<p>
📩 <strong>Email:</strong> <a href="mailto:jessisidhu04@gmail.com">jessisidhu04@gmail.com</a><br/>
🐙 <strong>GitHub:</strong> <a href="https://github.com/jessi-sidhu">github.com/jessi-sidhu</a><br/>
💼 <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/jessisidhu/">linkedin.com/in/jessisidhu</a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=FFA5D6&height=90&section=footer"/>
</p>

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
