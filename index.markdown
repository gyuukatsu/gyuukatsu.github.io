---
layout: page
title: Seungkyu Lee
---

<div class="about-section" id="about">
<h1>About</h1>

<p>Hi, I'm <strong>Seungkyu Lee</strong>, a senior undergraduate in Industrial Engineering at Seoul National University passionate about advancing the capabilities of Large Language Models and their real-world applications.</p>

<p>My research interests focus on <strong>building more intelligent and capable AI systems</strong>, with a particular emphasis on LLM-powered Tool Agents. At SNU's HOLI (Human-Oriented Language Intelligence) Lab, I've developed graph-based architectures that enhance how agents plan and execute complex tasks through structured reasoning and API interactions. This work has led to a first-author paper on API graph datasets and their applications.</p>

<p>Through my experience as a Machine Learning Engineer at Liner, I've implemented these concepts by developing <strong>autonomous agents that effectively handle complex user queries</strong> using various external APIs. I'm passionate about combining theoretical research with practical applications to build more reliable and capable AI assistants that truly understand user intentions.</p>


</div>

<div class="education-section" id="education">
<h1>Education</h1>

<h3><strong>Seoul National University</strong> <span class="date">Mar. 2019 - Feb. 2026</span></h3>
<p><em>B.S. in Industrial Engineering</em></p>

<h3><strong>State University of New York at Stony Brook</strong> <span class="date">Jan. 2024 - May 2024</span></h3>
<p><em>Exchange Student in Computer Science</em></p>
</div>

<div class="publications-section" id="publications">
<h1>Publications</h1>

<h3>2025</h3>
<ol>
<li><strong>In-N-Out: A Parameter-Level API Graph Dataset for Tool Agents</strong><br>
   <em><u>Seungkyu Lee</u>, Nalim Kim, Yohan Jo</em><br>
   <i>arXiv Preprint</i> <a href="#">[PDF]</a> <a href="#">[Code]</a><br></li>
<li><strong>Summarizing Large-scale Reviews with LLM-based Aspect Term Extraction</strong><br>
   <em><u>Seungkyu Lee</u>, Sungzoon Cho</em><br>
   <i>arXiv Preprint</i> <a href="#">[PDF]</a><br></li>
</ol>

</div>

<div class="experience-section" id="experience">
<h1>Experience</h1>

<h3><strong>Undergraduate Researcher</strong> @ HOLI Lab., SNU | Advisor: <a href="https://yohanjo.github.io/" style="text-decoration: underline; color: #006400;"> Yohan Jo</a> <span class="date">Aug. 2024 - Present</span></h3>

<h3><strong>Software Engineer Intern</strong> @ SAP Labs Korea <span class="date">Jul. 2025 - Present</span></h3>

<h3><strong>Machine Learning Engineer</strong> @ Liner <span class="date">Nov. 2022 - Jan. 2024</span></h3>

<h3><strong>Data Analyst</strong> @ Nudge Healthcare <span class="date">Jan. 2022 - Nov. 2022</span></h3>

</div>


<div class="awards-section" id="awards">
<h1>Awards</h1>

<h3><strong>The 13th Lee Joonghan Award</strong> <span class="date">Dec. 2021</span></h3>
<p><em>Undergraduate Leadership Award, Department of Industrial Engineering, SNU</em></p>

<h3><strong>HopperHackers 2024 - Best Beginner Hack (1st Place)</strong> <span class="date">Feb. 2024</span></h3>
<p><em>SUNY Stony Brook Hackathon</em></p>

</div>

<hr>
<p><em>"The best way to predict the future is to invent it."</em> - Alan Kay</p>
<p><em>Last updated: Aug. 2025</em></p>

<style>
div[class$="-section"] {
  margin-bottom: 2.5rem;
  scroll-margin-top: 2rem;
  padding: 1.5rem 0;
}

/* First section (About) gets more top padding */
.about-section {
  padding-top: 0.5rem;
}

html {
  scroll-behavior: smooth;
}

/* Content styling for better readability - Light Mode */
body:not(.dark) em {
  color: #444;
  font-style: normal;
  font-weight: 400;
  line-height: 1.7;
}

/* Dark Mode content styling */
body.dark em {
  color: #d1d1d1;
  font-style: normal;
  font-weight: 400;
  line-height: 1.7;
}

/* Special styling for experience/education descriptions - Light Mode */
body:not(.dark) .experience-section li em,
body:not(.dark) .education-section li em,
body:not(.dark) .publications-section em,
body:not(.dark) .awards-section em {
  color: #2c3e50;
  font-style: normal;
  font-weight: 400;
}

/* Special styling for experience/education descriptions - Dark Mode */
body.dark .experience-section li em,
body.dark .education-section li em,
body.dark .publications-section em,
body.dark .awards-section em {
  color: #e8e8e8;
  font-style: normal;
  font-weight: 400;
}

/* Styling for dates - Light Mode */
body:not(.dark) .experience-section .date,
body:not(.dark) .education-section .date,
body:not(.dark) .awards-section .date {
  color: #666;
  font-style: normal;
  font-weight: 300;
  font-size: 0.9em;
  float: right;
}

/* Styling for dates - Dark Mode */
body.dark .experience-section .date,
body.dark .education-section .date,
body.dark .awards-section .date {
  color: #aaa;
  font-style: normal;
  font-weight: 300;
  font-size: 0.9em;
  float: right;
}

/* Clear float for proper layout */
.experience-section h3,
.education-section h3,
.awards-section h3 {
  overflow: hidden;
}



/* Experience section font styling - use Merriweather for content, not title */
.experience-section h3,
.experience-section p,
.experience-section em,
.experience-section strong,
.experience-section a,
.experience-section .date {
  font-family: "Merriweather", serif !important;
}

/* Education section font styling - same as Experience */
.education-section h3,
.education-section p,
.education-section em,
.education-section strong,
.education-section a,
.education-section .date {
  font-family: "Merriweather", serif !important;
}

/* Awards section font styling - same as Experience and Education */
.awards-section h3,
.awards-section p,
.awards-section em,
.awards-section strong,
.awards-section a,
.awards-section .date {
  font-family: "Merriweather", serif !important;
}

/* Publications section dark mode improvements */
body.dark .publications-section ol {
  color: #fff;
}

body.dark .publications-section li {
  color: #fff;
}

body.dark .publications-section li strong {
  color: #fff;
}

body.dark .publications-section i {
  color: #f0f0f0;
  font-style: italic;
}

body.dark .publications-section em {
  color: #e8e8e8;
}

/* Specific styling for arXiv Preprint in dark mode */
body.dark .publications-section ol li::marker {
  color: #fff;
  font-weight: bold;
}

/* Experience section advisor link styling in light mode */
body:not(.dark) .experience-section a {
  color: #000 !important;
  text-decoration: underline;
}

/* Experience section advisor link styling in dark mode */
body.dark .experience-section a {
  color: #fff !important;
  text-decoration: underline;
}

/* Experience section font size and readability matching Publications */
.experience-section {
  font-size: 16px;
  line-height: 1.7;
}

.experience-section h3 {
  font-size: 16px;
  line-height: 1.6;
  font-weight: 400;
  margin-bottom: 0.8rem;
}

.experience-section h3 strong {
  font-weight: 600;
  color: inherit;
}

.experience-section p {
  font-size: 16px;
  line-height: 1.6;
  margin-top: 0.5rem;
  margin-bottom: 1.5rem;
}

/* Education section font size and styling - same as Experience */
.education-section {
  font-size: 16px;
  line-height: 1.7;
}

.education-section h3 {
  font-size: 16px;
  line-height: 1.6;
  font-weight: 400;
  margin-bottom: 0.8rem;
}

.education-section h3 strong {
  font-weight: 600;
  color: inherit;
}

.education-section p {
  font-size: 16px;
  line-height: 1.6;
  margin-top: 0.5rem;
  margin-bottom: 1.5rem;
}

/* Awards section font size and styling - same as Experience and Education */
.awards-section {
  font-size: 16px;
  line-height: 1.7;
}

.awards-section h3 {
  font-size: 16px;
  line-height: 1.6;
  font-weight: 400;
  margin-bottom: 0.8rem;
}

.awards-section h3 strong {
  font-weight: 600;
  color: inherit;
}

.awards-section p {
  font-size: 16px;
  line-height: 1.6;
  margin-top: 0.5rem;
  margin-bottom: 1.5rem;
}

/* Styling for job titles/majors/organizations under institution names - Light Mode */
body:not(.dark) .experience-section p em,
body:not(.dark) .education-section p em,
body:not(.dark) .awards-section p em {
  color: #777;
  font-style: normal;
  font-weight: 400;
  font-size: 0.95em;
}

/* Styling for job titles/majors/organizations under institution names - Dark Mode */
body.dark .experience-section p em,
body.dark .education-section p em,
body.dark .awards-section p em {
  color: #bbb;
  font-style: normal;
  font-weight: 400;
  font-size: 0.95em;
}

/* Section specific styling - Light Mode */
body:not(.dark) h1 {
  border-bottom: 2px solid #333;
  padding-bottom: 0.5rem;
  margin-bottom: 1.5rem;
}

body:not(.dark) h2 {
  color: #555;
  margin-top: 2rem;
  margin-bottom: 1rem;
}

body:not(.dark) h3 {
  color: #666;
  margin-bottom: 0.5rem;
  margin-top: 1.5rem;
}

/* Section specific styling - Dark Mode */
body.dark h1 {
  border-bottom: 2px solid #ccc;
  padding-bottom: 0.5rem;
  margin-bottom: 1.5rem;
}

body.dark h2 {
  color: #fff;
  margin-top: 2rem;
  margin-bottom: 1rem;
}

body.dark h3 {
  color: #ddd;
  margin-bottom: 0.5rem;
  margin-top: 1.5rem;
}

/* Links styling - Light Mode */
body:not(.dark) a {
  color: #333;
  text-decoration: none;
}

body:not(.dark) a:hover {
  color: #000;
  text-decoration: underline;
}

/* Links styling - Dark Mode */
body.dark a {
  color: #ddd;
  text-decoration: none;
}

body.dark a:hover {
  color: #fff;
  text-decoration: underline;
}

/* Lists styling */
ul, ol {
  margin-bottom: 1rem;
}

li {
  margin-bottom: 0.3rem;
}

/* Emphasis styling for template fields - Light Mode */
body:not(.dark) strong {
  color: #333;
}

/* Emphasis styling for template fields - Dark Mode */
body.dark strong {
  color: #f0f0f0;
}

/* Spacing */
p {
  margin-bottom: 1rem;
  line-height: 1.6;
}
</style>
