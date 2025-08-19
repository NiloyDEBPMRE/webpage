---
layout: archive
title: "Resume"
permalink: /cv/
author_profile: true
---

{% include base_path %}

<style>
  :root {
    --body-font-size: 14px;
    --heading-font-size: 16px;
    --muted: #444; /* Darker gray for better contrast */
    --accent: #0b66c3;
    --chip-bg: #f3f6fb;
    --line: #e6e6e6;
    --max-width: 920px;
  }

  .cv {
    max-width: var(--max-width);
    margin: 18px auto;
    font-family: "Helvetica Neue", Arial, sans-serif;
    color: #111;
    font-size: var(--body-font-size);
    line-height: 1.45;
    padding: 18px;
  }

  /* Header */
  .header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 12px;
    margin-bottom: 6px;
  }

  .name {
    font-size: 18px;
    font-weight: 700;
    margin: 0;
    color: #000; /* Ensure name is black for prominence */
  }

  .title {
    font-size: 13px;
    color: var(--muted);
    margin-top: 4px;
    font-style: italic;
  }

  .contact {
    text-align: right;
    font-size: 13px;
    color: var(--muted);
  }

  .contact a {
    color: var(--accent);
    text-decoration: none;
  }

  /* Section */
  .section {
    margin-top: 14px;
    padding-bottom: 12px;
    border-bottom: 1px solid var(--line);
  }

  .section h2 {
    display: flex;
    align-items: center;
    gap: 8px;
    font-size: var(--heading-font-size);
    margin: 0 0 10px 0;
  }

  .section h2 svg {
    width: 18px;
    height: 18px;
    opacity: 0.95;
  }

  /* Left / right entry */
  .entry {
    display: flex;
    justify-content: space-between;
    gap: 12px;
    align-items: flex-start;
    margin: 8px 0;
  }

  .entry-left {
    width: 64%;
  }

  .entry-right {
    width: 34%;
    text-align: right;
    color: var(--muted);
    font-size: 13px;
  }

  .entry-right .location {
    display: block;
    margin-top: 6px;
    font-style: italic;
    font-size: 12.5px;
  }

  .institution {
    display: flex;
    gap: 8px;
    align-items: center;
  }

  .institution-logo {
    height: 28px;
    width: auto;
    display: inline-block;
    vertical-align: middle;
  }

  .institution .inst-name {
    font-weight: 700;
    font-size: 14px;
    color: #000; /* Ensure institution name is black */
  }

  .institution .inst-sub {
    color: var(--accent);
    font-style: italic;
    font-size: 13.2px;
    margin-top: 2px;
  }

  .entry-desc {
    margin-top: 6px;
    font-size: 13.4px;
    color: #111;
  }

  /* chips */
  .chips {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-top: 8px;
  }

  .chip {
    background: var(--chip-bg);
    padding: 6px 10px;
    border-radius: 14px;
    font-size: 13px;
    color: #333; /* Darken chip text for contrast */
  }

  /* inline dot lists */
  .inline-par {
    margin-top: 6px;
    font-size: 13.4px;
    color: #111;
  }

  .inline-par a {
    color: var(--accent);
    text-decoration: none;
  }

  .dot {
    margin: 0 8px;
    color: var(--muted);
  }

  /* compact lists */
  .compact-list {
    margin: 8px 0 0 0;
    padding-left: 14px;
  }

  .compact-list li {
    margin: 6px 0;
    font-size: 13.4px;
  }

  /* responsive */
  @media (max-width: 720px) {
    .entry {
      flex-direction: column;
    }

    .entry-left,
    .entry-right {
      width: 100%;
      text-align: left;
    }

    .entry-right {
      margin-top: 6px;
    }

    .contact {
      text-align: left;
      margin-top: 6px;
    }
  }

  @media print {
    .cv {
      padding: 0;
      margin: 0;
    }
  }

  /* small helper styles */
  .muted {
    color: var(--muted);
    font-size: 13px;
  }
</style>

<div class="cv">

  <div class="header">
    <div style="width:68%;">
      <p class="name">Niloy Deb</p>
      <p class="title">Mechanical Engineering Graduate</p>
      <p class="entry-desc" style="margin-top:8px;">
        <strong>Summary:</strong> An aspiring mechanical engineering graduate focused on data-driven science, differentiable physics extended scientific machine learning, statistical inference, computational methods, and applied mathematics. Research interests include chaotic dynamical systems, turbulence, fluid flow through porous and subsuface media, fluid under multiphysics environment, and so on.
      </p>
    </div>
    <div class="contact" style="width:32%;">
      <div style="font-weight:600;margin-bottom:6px;">Contact</div>
      <div>niloydeb@pmre.buet.ac.bd</div>
      <div style="margin-top:6px;">
        <a href="LINKEDIN_URL" target="_blank">LinkedIn</a> · <a href="#" target="_blank">ORCID</a>
      </div>
      <div style="margin-top:8px;">
        <a class="btn" href="link-to-cv.pdf" style="background:var(--accent); color:#fff; padding:6px 10px; border-radius:6px; text-decoration:none; font-size:13px;">📄 Download PDF</a>
      </div>
    </div>
  </div>

  <section class="section" id="education">
    <h2>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
        <path d="M3 7l9-4 9 4-9 4-9-4z"></path>
        <path d="M3 7v7a9 9 0 0 0 9 5 9 9 0 0 0 9-5V7"></path>
      </svg>
      Education
    </h2>
    <div class="entry">
      <div class="entry-left">
        <div class="institution">
          <img src="{{ site.baseurl }}/images/buet.png" alt="BUET logo" class="institution-logo">
          <div>
            <div class="inst-name">Bangladesh University of Engineering and Technology (BUET)</div>
            <div class="inst-sub">Bachelor of Science in Mechanical Engineering</div>
          </div>
        </div>
        <p class="entry-desc">
          <strong>CGPA:</strong> 3.94 / 4.00 · <strong>Class Rank:</strong> 6 / 188 (Top 3%)<br>
          <strong>Thesis:</strong> <em>Case Study of Natural and Mixed Convection Heat Transfer inside Different Chambers with the Presence of Porous Medium</em><br>
          <strong>Supervisor:</strong> Dr. Sumon Saha
        </p>
      </div>
      <div class="entry-right">
        March 2018 – May 2023
        <span class="location">Dhaka, Bangladesh</span>
      </div>
    </div>
    <div class="entry" style="margin-top:6px;">
      <div class="entry-left">
        <div class="institution">
          <img src="{{ site.baseurl }}/images/dhakacollege.png" alt="Dhaka College logo" class="institution-logo">
          <div>
            <div class="inst-name">Dhaka College, Dhaka</div>
            <div class="inst-sub">Higher Secondary Certificate (Science)</div>
          </div>
        </div>
        <p class="entry-desc">
          <strong>GPA:</strong> 5:00 / 5.00 
        </p>
      </div>
      <div class="entry-right">
        June 2015 - August 2017
        <span class="location">Dhaka, Bangladesh</span>
      </div>
    </div>
  </section>

  <section class="section" id="interests">
    <h2>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round">
        <circle cx="12" cy="12" r="10"></circle>
        <path d="M12 6v6l4 2"></path>
      </svg>
      Interests
    </h2>
    <div class="chips" role="list">
      <span class="chip">Data-Driven Science</span>
      <span class="chip">Statistical Modeling</span>
      <span class="chip">Scientific Machine Learing</span>
      <span class="chip">Differentiable Physics</span>
      <span class="chip">Mathematical & Computational Modeling</span>
      <span class="chip">Numerical Methods - FEM, FDM, FVM, SEM, etc.</span>
      <span class="chip">Computational Fluid Dynamics & Heat Transfer</span>
      <span class="chip">Advanced Thermodynamics Applications & Optimization</span>
      <span class="chip">Physics of Turbulence</span>
      <span class="chip">Chaotic Dynamical System and Control</span>
      <span class="chip">Fluid under Multiphysics Environments</span>
      <span class="chip">Fluid Flow Through Porous & Subsurface Media</span>
      <span class="chip">Physics of Convection</span>
    </div>
  </section>

  <section class="section" id="coursework">
    <h2>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
        <rect x="3" y="4" width="18" height="6" rx="2"></rect>
        <path d="M7 20h10"></path>
      </svg>
      Relevant Coursework
    </h2>
    <div class="inline-par">
      <strong>Advanced / Graduate & Self-Learning:</strong> (listed partially)
      Advanced Numerical Analysis (Dept. of ME, BUET)· Advanced Thermodynamics (classical and statistical) (Dept. of ME, BUET)· Boiling & Condensation Heat Transfer (Dept. of ME, BUET) · Reservoir Engineering (Dept. of PMRE, BUET) · Non-linear Dynamics & Chaos (S. Strogatz, Online) · Non-linear Systems (J. Slotine, MOCW) · Control Bootcamp (S. L. Brunton, Online)· Global Warming - Science & Modeling (D. Archer, edX) · Understanding Rheology (F. Morrison, Online) · Flow in Porous Media (M. Blunt, Online) · Physics of Turbulence (M. K. Verma, IITK-NPTEL) · Advanced Fluid Mechanics (S. Chakraborty, IITKGP-NPTEL) · AI Principles & Techniques (Stanford Online) · Deep Learning in Scientific Computing (ETH Zurich) · Data Analytics and Geostatistics (M. J. Pyrcz, Online) · Matrix Calculus for Machine Learning and Beyond (A. Edelman & S. G. Johnson, MOCW) ·  Matrix, Numerical and Optimization Methods in Science and Engineering (K. Cassel, Online) · Applied Time Series Analysis (A. K. Tangirala, IITM-NPTEL) · Probabilistic System Analysis and Applied Probability (J. Tsitsiklis, MOCW)· Data-Driven Science and Engineering (S. L. Brunton, Online) · Random Physics Lectures (classical, Statistical, Quantum Mechanics, Modern Physics - Special and General Relativity by L. Susskind, Online )- did just for fun. 
    </div>
    <div class="inline-par" style="margin-top:8px;">
      <strong>Undergraduate / Core:</strong>
      Instrumentation and Measurement· Electro-Mechanical System Design (Project) · Noise & Vibration · Control Engineering · Engineering Mechanics (I & II) · Mechanics of Solids · Thermodynamics (Basic)· Advanced Thermodynamics (Classical and Statistical) · Fluid Mechanics (I & II) · Heat Transfer · Heat Transfer Equipment Design · Thermo Fluid System Design (Project)· Combustion · Refrigeration and Building Mechanical System · Numerical Analysis · Computer Programming 
    </div>
  </section>

  <section class="section" id="research">
    <h2>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
        <path d="M3 7h18"></path>
        <path d="M12 3v18"></path>
      </svg>
      Research Experience
    </h2>
    <div class="entry" style="margin-top:6px;">
      <div class="entry-left">
        <div class="inst-name">Thermal Management and Robustness of Linear Controllers (P, PI, PID) in Mixed Convection Modeling - A CFD Approach</div>
        <div class="entry-desc">Supervisor: Dr. Sumon Saha</div>
      </div>
      <div class="entry-right">June 2023</div>
    </div>
    <div class="entry" style="margin-top:6px;">
      <div class="entry-left">
        <div class="inst-name">Revisiting the Numerical Calculation of Nusselt Number (Nu) for Different Thermal Boundary Conditions</div>
        <div class="entry-desc">Supervisor: Dr. Sumon Saha</div>
      </div>
      <div class="entry-right">Aug 2023</div>
    </div>
    <div class="entry" style="margin-top:6px;">
      <div class="entry-left">
        <div class="inst-name">Natural and Mixed Convection Heat Transfer in the Presence of Porous Medium with Magnetohydrodynamics, Joule Heating, and Internal Heat Generation</div>
        <div class="entry-desc">Supervisor: Dr. Sumon Saha</div>
      </div>
      <div class="entry-right">Aug 2023</div>
    </div>
    <div class="entry" style="margin-top:6px;">
      <div class="entry-left">
        <div class="inst-name">Subsurface Fluid Properties and Phase Behavior — A Case Study of the Titas Gas Field in Bangladesh: Changes in Natural Gas Phase Behavior Across Spatial and Temporal Dimensions. </div>
        <div class="entry-desc">Funded Project by 'Hydrocarbon Unit Research Program 2023–24' · Supervisor / PI: Dr. Mohammed Mahbubur Rahman</div>
      </div>
      <div class="entry-right">May 2024</div>
    </div>
    <div class="entry" style="margin-top:6px;">
      <div class="entry-left">
        <div class="inst-name"> Thermodynamic Optimization of a Novel Three-Stage Direct Expansion Cycle for LNG Cold Energy Recovery</div>
        <div class="entry-desc"> PI: Shaumik Rahman Ayon</div>
      </div>
      <div class="entry-right">May 2024</div>
    </div>
  </section>

  <section class="section" id="publications">
    <h2>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round">
        <path d="M19 21H5a2 2 0 0 1-2-2V7"></path>
        <path d="M17 3H7a2 2 0 0 0-2 2v12"></path>
      </svg>
      Publications
    </h2>

    <ul style="margin:6px 0 0 14px;">
      {% for post in site.publications reversed %}
      {% include archive-single-cv.html %}
      {% endfor %}
    </ul>
  </section>

<section class="section" id="professional">
  <h2>
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
      <rect x="2" y="7" width="20" height="14" rx="2"></rect>
      <path d="M16 3h0a2 2 0 0 1 2 2v2H6V5a2 2 0 0 1 2-2h0"></path>
    </svg>
    Professional Experience
  </h2>

  <div class="entry">
    <div class="entry-left">
      <div class="institution">
        <img src="{{ site.baseurl }}/images/buet.png" alt="BUET logo" class="institution-logo">
        <div>
          <div class="inst-name">Bangladesh University of Engineering and Technology (BUET)</div>
          <div class="inst-sub">Lecturer, Dept. of Petroleum & Mineral Resources Engineering</div>
        </div>
      </div>
      <p class="entry-desc">
        <strong> Academic research </strong> on · Energy Resources Engineering · Hydrocarbon Reservoir Engineering · Advanced Well Testing and Interpretation · Advanced Reservoir Simulation .<br>
        <strong> Taught (Undergraduate Courses):</strong> PMRE 411 · Reservoir Engineering · PMRE 413 · Natural Gas Engineering (≈50 students each)
      </p>
    </div>
    <div class="entry-right">
      Dec 2023 – Present
      <span class="location">Dhaka, Bangladesh</span>
    </div>
  </div>

  <div class="entry" style="margin-top:8px;">
    <div class="entry-left">
      <div class="institution">
        <img src="{{ site.baseurl }}/images/buet.png" alt="BUET logo" class="institution-logo">
        <div>
          <div class="inst-name">Computational Fluid Dynamics and Heat Transfer (CFDHT) Research Group, Dept. of Mechanical Engineering, BUET</div>
          <div class="inst-sub">Research Assistant</div>
        </div>
      </div>
      <div class="entry-desc">Numerical modeling & simulation of thermo-fluid problems · CFD & Heat Transfer research · Mentored undergraduate students</div>
    </div>
    <div class="entry-right">Jun 2023 – Dec 2023 <span class="location">Dhaka, Bangladesh</span></div>
  </div>

  <div class="entry" style="margin-top:8px;">
    <div class="entry-left">
      <div class="institution">
        <img src="{{ site.baseurl }}/images/buet.png" alt="BUET logo" class="institution-logo">
        <div>
          <div class="inst-name">Directorate of Continuing Education, BUET</div>
          <div class="inst-sub">Co-instructor</div>
        </div>
      </div>
      <div class="entry-desc">Short course: COMSOL Multiphysics Simulation of Thermo-fluidic Problems (Basic Level) · 2-day workshop · Resource person: Dr. Sumon Saha</div>
    </div>
    <div class="entry-right">Dec 2023 <span class="location">Dhaka, Bangladesh</span></div>
  </div>

  <div class="entry" style="margin-top:8px;">
    <div class="entry-left">
      <div class="institution">
        <img src="{{ site.baseurl }}/images/powertek.jpeg" alt="Powertek logo" class="institution-logo">
        <div>
          <div class="inst-name">Haripur 360 MW Combined Cycle Power Plant</div>
          <div class="inst-sub">Industrial Trainee </div>
        </div>
      </div>
      <div class="entry-desc">An internship program organized by the dept. of Mechanical Engineering, BUET <br>
      Hands-on exposure to power generation, Plant unit operations (FGC, HRSG, ST, GT, WT), maintenance, and process control.</div>
    </div>
    <div class="entry-right">Apr 2022 (3 weeks) <span class="location">Dhaka, Bangladesh</span></div>
  </div>
</section>

  <section class="section" id="projects">
    <h2>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round">
        <path d="M3 7h18"></path>
        <path d="M3 11h18"></path>
        <path d="M3 15h18"></path>
      </svg>
      Academic Projects
    </h2>

    <div class="entry" style="margin-top:6px;">
      <div class="entry-left">
        <div class="inst-name">Design of a Counter-Flow Shell & Helical Coil Tube Heat Exchanger (SHCTHX)</div>
        <div class="inst-sub">ME-310: Thermo-fluid System Design & Practice</div>
        <div class="entry-desc">CAD design · Thermo-hydraulic calculations · Prototype design and CFD simulation for flow & thermal visualization.</div>
      </div>
      <div class="entry-right">Feb 2022</div>
    </div>

    <div class="entry" style="margin-top:6px;">
      <div class="entry-left">
        <div class="inst-name">Self-Stabilizing, Computer-Controlled Laser Turret</div>
        <div class="inst-sub">ME-366: Electromechanical System Design & Practice</div>
        <div class="entry-desc">CAD · Arduino programming · sensor integration & feedback control · hardware-software integration for stabilization and precision.</div>
      </div>
      <div class="entry-right">Jul 2021</div>
    </div>
  </section>

  <section class="section" id="training">
    <h2>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round">
        <path d="M21 8V7a2 2 0 0 0-2-2h-3"></path>
        <path d="M3 8v9a2 2 0 0 0 2 2h3"></path>
      </svg>
      Training & MOOC Completion
    </h2>

    <p class="inline-par">
      Research Skill Development · DCE, BUET · <a href="https://buetedu-my.sharepoint.com/:b:/g/personal/niloydeb_pmre_buet_ac_bd/EXOfHmAlqktAtOIqCe3qqqwBMHvi-7VKch1JsfkeN4RUmw?e=1pHMCX">Certificate</a>
      <span class="dot">·</span>
      Quantitative Method · Coursera · <a href="https://www.coursera.org/account/accomplishments/verify/KUNNEK67EW6E">Certificate</a>
      <span class="dot">·</span>
      Evaluating Problems · Coursera · <a href="https://www.coursera.org/account/accomplishments/verify/QWF5B9NVSPDD">Certificate</a>
      <span class="dot">·</span>
      Welcome to Game Theory · Coursera · <a href="https://www.coursera.org/account/accomplishments/verify/3V72R3HBVLJS">Certificate</a>
      <span class="dot">·</span>
      Intro to Data Analysis using Excel · Coursera · <a href="https://www.coursera.org/account/accomplishments/verify/8SC5YX5ZGN9K">Certificate</a>
      <span class="dot">·</span>
      Introduction to Programming with MATLAB · Coursera · <a href="https://www.coursera.org/account/accomplishments/verify/TCQNM5G5Y7FP">Certificate</a>
      <span class="dot">·</span>
      Python for Everybody (Specialization) · Coursera · <a href="https://www.coursera.org/account/accomplishments/specialization/VPRVZ5MZ43HX">Certificate</a>
      <span class="dot">·</span>
      ELEN7070x: Research Methods · EdX · <a href="https://courses.edx.org/certificates/9abb933553e644ed9f41ff096fc60a72">Certificate</a>
      <span class="dot">·</span>
      16.00x: Introduction to Aerospace Engineering · EdX · <a href="https://courses.edx.org/certificates/ec2238cfcac64bbebddb7263c82ce30c">Certificate</a>
      <span class="dot">·</span>
      Image Processing Onramp · MathWorks · <a href="https://matlabacademy.mathworks.com/progress/share/certificate.html?id=6c90b29d-19c4-4b51-9069-fa743ed4b1f7&">Certificate</a>
      <span class="dot">·</span>
      Solving ODEs with MATLAB · MathWorks · <a href="https://matlabacademy.mathworks.com/progress/share/certificate.html?id=c390f6ca-c82a-4189-83ef-c67ccb7cc0dc&">Certificate</a>
    </p>
  </section>

  <section class="section" id="skills">
    <h2>
       <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" style="width:24px; height:24px; opacity:.95;">
        <path stroke-linecap="round" stroke-linejoin="round" d="M9.594 3.94c.09-.542.56-.94 1.11-.94h2.514c.55 0 1.02.398 1.11.94l.213 1.28c.554.113 1.074.453 1.503.94l1.28.213c.542.09.94.56.94 1.11v2.514c0 .55-.398 1.02-.94 1.11l-1.28.213a6.72 6.72 0 0 1-.94 1.503l-.213 1.28c-.09.542-.56.94-1.11.94h-2.514c-.55 0-1.02-.398-1.11-.94l-.213-1.28a6.72 6.72 0 0 1-1.503-.94l-1.28-.213c-.542-.09-.94-.56-.94-1.11v-2.514c0-.55.398-1.02.94-1.11l1.28-.213a6.72 6.72 0 0 1 .94-1.503l.213-1.28Z" />
        <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z" />
      </svg>
      Technical Skills
    </h2>
    <p class="entry-desc">
      <strong>Highlights:</strong> Scientific Writing · Exploratory Data Analysis · Quantitative Research
    </p>
    <ul class="compact-list">
      <li><strong>Programming Language:</strong> Python, MATLAB, C</li>
      <li><strong>Documentation/Scripting:</strong> LaTeX, MS Office, Jupyter Notebook Markdown Text</li>
      <li><strong>Visualization:</strong> Tecplot 360, WebPlotDigitizer, Desmos graphing calculator, Python - Matplotlib, Plotly, Seaborn</li>
      <li><strong>Design, CAD, & Drawing:</strong> AutoCAD, SolidWorks, Proteus, Draw.io, Canva, Illustrator, Photoshop, LaTeX - TikZ, Python - OpenCV, Pillow, scikit-image </li>
      <li><strong>FEM Modeling:</strong> COMSOL Multiphysics</li>
      <li><strong> Reservoir Simulation:</strong> Kappa Workstation (Rubis - Full Reservoir Numerical Modeling, Saphir - Pressure Transient Analysis).</li>
      <li><strong> ML/DL/Stats:</strong> Python - scikit-learn, TensorFlow, PyTorch, JAX, SciPY, PyMC/3/4, etc. </li>
      <li><strong>Exploratory Data Analysis:</strong> Python - Pandas, NumPy, SciPy, Matplotlib, Plotly, Seaborn</li>
    </ul>
  </section>

  <section class="section" id="awards">
    <h2>
       <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" style="width:24px; height:24px; opacity:.95;">
        <path stroke-linecap="round" stroke-linejoin="round" d="M4.26 10.147a60.438 60.438 0 0 0-.491 6.347A48.62 48.62 0 0 1 12 20.915c3.593 0 7.172-.647 10.42-1.921-.191-2.924-.715-5.83-1.89-8.568M4.26 10.147c6.182-5.744 12.827-6.023 16.326-2.197M4.26 10.147a60.462 60.462 0 0 1 1.042-4.148m-.576-.445C7.942 2.064 12.38 2.064 15.65 3.32a8.716 8.716 0 0 0 1.524 1.05M20.326 7.95c.531.636 1.058 1.236 1.574 1.838m-1.574-1.838a60.462 60.462 0 0 1-.576-.445m0 0a24.115 24.115 0 0 1-5.76-1.458" />
      </svg>
      Awards & Achievements
    </h2>
    <ul class="compact-list">
      <li><strong>Dr. Muhammad Harunur Rashid Award (ICME 2023):</strong> Best paper — 14th International Conference on Mechanical Engineering, Dept. of Mechanical Engineering, BUET</li>
      <li><strong>University Merit Scholarship (2018–2023):</strong> Awarded for consecutive terms, BUET</li>
      <li><strong>Dean’s List Award (2018–2023):</strong> Awarded for consecutive terms, Dept. of ME, BUET</li>
    </ul>
  </section>

</div>