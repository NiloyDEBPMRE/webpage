---
layout: archive
title: "Resume"
permalink: /cv/
author_profile: true
---

{% include base_path %}

<style>
  .resume-section {
    font-size: 14px;
    line-height: 1.5;
    margin-bottom: 20px;
  }
  .resume-section h2 {
    font-size: 16px;
    font-weight: bold;
    display: flex;
    align-items: center;
    border-bottom: 1px solid #ccc;
    padding-bottom: 3px;
    margin-bottom: 10px;
  }
  .resume-section h2 svg {
    margin-right: 8px;
  }
  .institution-logo {
    height: 16px;
    vertical-align: middle;
    margin-right: 6px;
  }
  .keyword-list {
    font-size: 14px;
    line-height: 1.4;
  }
  .keyword-list span {
    display: inline-block;
    margin-right: 10px;
    margin-bottom: 4px;
  }
  ul {
    margin: 0;
    padding-left: 20px;
  }
  a.btn {
    background-color: #007bff;
    color: #fff;
    padding: 6px 12px;
    text-decoration: none;
    border-radius: 4px;
    font-size: 14px;
  }
  a.btn:hover {
    background-color: #0056b3;
  }
</style>

<section id="basics" class="resume-section">
  <h2>👤 Basics</h2>
  <p><strong>Name:</strong> Niloy Deb<br>
     <strong>Label:</strong> Mechanical Engineering Graduate & Lecturer, Dept. of PMRE, BUET<br>
     <strong>Website:</strong> <a href="https://niloydebpmre.github.io/webpage" target="_blank">niloydebpmre.github.io/webpage</a><br>
     <strong>Summary:</strong> An aspiring individual interested in data-driven science, physics-informed machine learning, computational methods, and applied mathematics. Focused on dynamical systems, turbulence, and transport phenomena at both micro and macro scales.
  </p>
</section>

<section id="download-cv" class="resume-section">
  <a href="link-to-cv.pdf" class="btn">📄 Download PDF CV</a>
</section>

<section id="education" class="resume-section">
  <h2>🎓 Education</h2>
  <ul>
    <li>
      <img src="path-to-buet-logo.png" class="institution-logo" alt="BUET Logo">
      <strong>Bangladesh University of Engineering and Technology (BUET)</strong><br>
      <em style="color:lightskyblue;">B.Sc. in Mechanical Engineering</em><br>
      Dhaka, Bangladesh | Mar 2018 – May 2023<br>
      CGPA: <b>3.94/4.00</b> | Rank: <b>6/188 (Top 3%)</b><br>
      Thesis: Case Study of Natural and Mixed Convection Heat Transfer inside Different Chambers with the Presence of Porous Medium.<br>
      Supervisor: <b>Dr. Sumon Saha</b>
    </li>
    <li>
      <img src="path-to-dhaka-college-logo.png" class="institution-logo" alt="Dhaka College Logo">
      <strong>Dhaka College, Dhaka</strong><br>
      Higher Secondary Certificate in Science
    </li>
  </ul>
</section>

<section id="interests" class="resume-section">
  <h2>💡 Interests</h2>
  <div class="keyword-list">
    <span>Data-Driven Science</span>
    <span>Physics-informed ML</span>
    <span>Mathematical Modeling</span>
    <span>CFD & Heat Transfer</span>
    <span>Turbulence</span>
    <span>Non-linear Dynamics</span>
    <span>Climate Modeling</span>
    <span>Porous Media</span>
    <span>Energy Science</span>
  </div>
</section>

<section id="coursework" class="resume-section">
  <h2>📚 Relevant Coursework</h2>
  <h4>Advanced Graduate Level & Self-Learning</h4>
  <ul>
    <li>Advanced Numerical Analysis</li>
    <li>Advanced Thermodynamics</li>
    <li>Boiling and Condensation</li>
    <li>Non-linear Dynamics and Chaos (S. Strogatz)</li>
    <li>Global Warming: Science & Modeling (D. Archer)</li>
    <li>Understanding Rheology (F. Morrison)</li>
    <li>Flow in Porous Media (M. Blunt)</li>
    <li>AI Principles & Techniques (Stanford Online)</li>
    <li>Deep Learning in Scientific Computing (ETH Zurich)</li>
    <li>Non-linear Systems (J. Slotine, MOCW)</li>
  </ul>
  <h4>Undergraduate/Basic Courses</h4>
  <ul>
    <li>Noise and Vibration</li>
    <li>System Dynamics and Control</li>
    <li>Thermodynamics</li>
    <li>Fluid Mechanics</li>
    <li>Heat Transfer</li>
    <li>Combustion</li>
    <li>Composite Materials</li>
    <li>Numerical Analysis & Programming</li>
  </ul>
</section>

<section id="research" class="resume-section">
  <h2>🔬 Research Experience</h2>
  <ul>
    <li>
      <strong>Robustness of Linear Controllers (P, PI, PID) in Convection Modeling</strong><br>
      Supervisor: Dr. Sumon Saha | June 2023
    </li>
    <li>
      <strong>A Generalized Formulation for Nusselt Number Irrespective of Thermal Boundary Conditions</strong><br>
      Supervisor: Dr. Sumon Saha | August 2023
    </li>
    <li>
      <strong>A Study of Reservoir Fluid Properties and Phase Behavior of Titas Gas Field</strong><br>
      Hydrocarbon Unit Research Program 2023-24<br>
      Supervisor: Dr. Mohammed Mahbubur Rahman | May 2024
    </li>
  </ul>
</section>

<section id="publications" class="resume-section">
  <h2>📄 Publications</h2>
  <ul>
    {% for post in site.publications reversed %}
      {% include archive-single-cv.html %}
    {% endfor %}
  </ul>
</section>

<section id="professional-experience" class="resume-section">
  <h2>💼 Professional Experience</h2>
  <ul>
    <li>
      <strong>Bangladesh University of Engineering and Technology</strong><br>
      <em style="color: lightskyblue;">Lecturer, Dept. of Petroleum and Mineral Resources Engineering</em><br>
      Dhaka, Bangladesh | Dec 2023 - Present<br>
      Academic research in Energy Resources Engineering (Hydrocarbon Reservoir Engineering, Drilling, Well Logging, Production).<br>
      <b>Taught Undergraduate Courses:</b><br>
      PMRE 411 - Petroleum Reservoir Engineering (50 students)<br>
      PMRE 413 - Natural Gas Engineering (50 students)
    </li>
    <li>
      <strong>Research Assistant, CFDHT Research Group, Dept. of ME</strong><br>
      Dhaka, Bangladesh | June 2023 - Dec 2023<br>
      * Numerical Modeling & Simulation of Thermo-Fluidic Problems<br>
      * Computational Fluid Dynamics & Heat Transfer Research<br>
      * Mentored undergraduate students
    </li>
    <li>
      <strong>Co-instructor, Directorate of Continuing Education, BUET</strong><br>
      Dhaka, Bangladesh | Dec 2023 (2-Day Workshop)<br>
      Short course: COMSOL Multiphysics Simulation of Thermo-fluidic Problems (Basic Level)<br>
      Resource Person: Dr. Sumon Saha
    </li>
    <li>
      <strong>Haripur 360 MW Combined Cycle Power Plant</strong><br>
      <em style="color: lightskyblue;">Industrial Trainee</em><br>
      Dhaka, Bangladesh | April 2022 (3 Weeks)<br>
      First-hand experience in Power Generation, Unit operations (FGC, HRSG, ST, GT, WT), Maintenance, Control
    </li>
  </ul>
</section>

<section id="academic-projects" class="resume-section">
  <h2>📐 Academic Projects</h2>
  <ul>
    <li>
      <strong>Design of a Counter-Flow Shell and Helical Coil Tube Heat Exchanger (SHCTHX)</strong><br>
      <em style="color:lightskyblue;">ME-310: Thermo-fluid System Design & Practice | Feb 2022</em><br>
      * CAD of mechanical components and systems<br>
      * Thermo-hydraulic calculations & performance evaluation<br>
      * Prototype design and CFD simulation
    </li>
    <li>
      <strong>Self-Stabilizing, Computer-Controlled Laser Turret</strong><br>
      <em style="color:lightskyblue;">ME-366: Electromechanical System Design & Practice | July 2021</em><br>
      * CAD design, Arduino programming, sensor integration<br>
      * Feedback control, system tuning for external disturbances<br>
      * Hardware-software integration for stabilization and precision
    </li>
  </ul>
</section>

<section id="training-mooc" class="resume-section">
  <h2>🎓 Training & MOOC Completion</h2>
  <ul>
    <li>Research Skill Development | DCE, BUET | <a href="https://buetedu-my.sharepoint.com/:b:/g/personal/niloydeb_pmre_buet_ac_bd/EXOfHmAlqktAtOIqCe3qqqwBMHvi-7VKch1JsfkeN4RUmw?e=1pHMCX">Certificate</a></li>
    <li>Quantitative Method | Coursera | <a href="https://www.coursera.org/account/accomplishments/verify/KUNNEK67EW6E">Certificate</a></li>
    <li>Evaluating Problems | Coursera | <a href="https://www.coursera.org/account/accomplishments/verify/QWF5B9NVSPDD">Certificate</a></li>
    <li>Welcome to Game Theory | Coursera | <a href="https://www.coursera.org/account/accomplishments/verify/3V72R3HBVLJS">Certificate</a></li>
    <li>Intro to Data Analysis using Excel | Coursera | <a href="https://www.coursera.org/account/accomplishments/verify/8SC5YX5ZGN9K">Certificate</a></li>
    <li>Intro to MATLAB Programming | Coursera | <a href="https://www.coursera.org/account/accomplishments/verify/TCQNM5G5Y7FP">Certificate</a></li>
    <li>Python for Everybody (Specialization) | Coursera | <a href="https://www.coursera.org/account/accomplishments/specialization/VPRVZ5MZ43HX">Certificate</a></li>
    <li>ELEN7070x: Research Methods (EdX) | <a href="https://courses.edx.org/certificates/9abb933553e644ed9f41ff096fc60a72">Certificate</a></li>
    <li>16.00x: Aerospace Engineering (EdX) | <a href="https://courses.edx.org/certificates/ec2238cfcac64bbebddb7263c82ce30c">Certificate</a></li>
    <li>Image Processing Onramp | MathWorks | <a href="https://matlabacademy.mathworks.com/progress/share/certificate.html?id=6c90b29d-19c4-4b51-9069-fa743ed4b1f7&">Certificate</a></li>
    <li>Solving ODEs with MATLAB | MathWorks | <a href="https://matlabacademy.mathworks.com/progress/share/certificate.html?id=c390f6ca-c82a-4189-83ef-c67ccb7cc0dc&">Certificate</a></li>
  </ul>
</section>

<section id="technical-skills" class="resume-section">
  <h2>🛠 Technical Skills</h2>
  <p><strong>Highlights:</strong> Scientific Writing | Exploratory Data Analysis | Quantitative Research</p>
  <ul>
    <li><strong>Programming:</strong> Python, MATLAB, C</li>
    <li><strong>Documentation:</strong> LaTeX, MS Office</li>
    <li><strong>Visualization:</strong> Tecplot 360, WebplotDigitizer, Desmos</li>
    <li><strong>Design Tools:</strong> AutoCAD, SolidWorks, Proteus, Draw.io, Canva, Illustrator, Photoshop</li>
    <li><strong>FEM Modeling:</strong> COMSOL Multiphysics</li>
    <li><strong>Developer Tools:</strong> Simulink</li>
  </ul>
</section>

<section id="awards" class="resume-section">
  <h2>🏆 Awards & Achievements</h2>
  <ul>
    <li><strong>Dr. Muhammad Harunur Rashid Award ICME 2023:</strong> Best paper, 14th Int. Conf. on Mech. Engg., Dept. of ME, BUET</li>
    <li><strong>University Merit Scholarship 2018-2023:</strong> Consecutive terms from Level 1 to 4, BUET</li>
    <li><strong>Dean’s List Award 2018-2023:</strong> Consecutive terms from Level 1 to 4, Dept. of ME, BUET</li>
  </ul>
</section>









  
