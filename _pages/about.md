---
layout: about
title: About
permalink: /
# subtitle: <em>"An object in motion stays in motion."</em>
subtitle:

profile:
  align: right
  title: M.Eng. & B.S., CS + Molecular Biology, MIT
  image: pari_headshot.jpg
  image_circular: true # crops the image to make it circular

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons under profile picture

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Hi! I recently graduated with my M.Eng. and B.S. in [CS & Molecular Biology](https://catalog.mit.edu/interdisciplinary/undergraduate-programs/degrees/computer-science-molecular-biology/) from [MIT](https://www.mit.edu/), with a minor in Economics. I am interested in developing algorithms, models, and frameworks to better understand and engineer biological processes to improve human health.

I recently founded [Illume](https://www.illumelabs.ai), a health tech startup in the YC S26 batch. I also completed my Master's with [Dr. Feng Zhang](https://zlab.bio) at the [Broad Institute](https://www.broadinstitute.org/), where I used mechanistic interpretability to investigate DNA LLMs for non-coding genome discovery. I have also previously researched with [Dr. Giovanni Traverso](https://www.l4te.org/dipl-team-member/giovanni-traverso/) and [Dr. Robert Langer](https://langerlab.mit.edu/) at the [Koch Institute](https://ki.mit.edu/) on unifying representations in foundation models, quality-aware tokenization, and property-constrained molecular design.

Previously, I have interned in [the AI Division @ Eli Lilly & Company](https://www.lilly.com/), the Genetics Department @ [MD Anderson Cancer Center](https://www.mdanderson.org/), and [Dianox](https://www.dianox.com/) (AI-powered biotech startup in Denmark).

You can email me at [platawa@mit.edu](mailto:platawa@mit.edu)!

---

<details class="about-collapsible" id="publications" open>
<summary><h2 class="about-section-title">Publications &amp; Research</h2></summary>

<div class="section-body">
<div class="publications pub-scroll">
{% bibliography %}
</div>
</div>

</details>

<details class="about-collapsible" id="talks" open>
<summary><h2 class="about-section-title">Symposiums &amp; Presentations</h2></summary>

<div class="section-body">
<div class="about-leadership-item has-thumb">
  <img class="item-thumb" src="{{ '/assets/img/talks/lilly-perturbation-talk.jpg' | relative_url }}" alt="Presenting the in silico perturbation prediction work at Eli Lilly" loading="lazy">
  <div class="item-body">
  <div class="item-title">In Silico Perturbation Prediction Modeling using Single Cell Foundation Models</div>
  <p class="item-note">2025 · Eli Lilly Advanced Intelligence, Engineering & Biology Research · Paridhi Latawa</p>
  <div class="item-links"><a href="https://www.linkedin.com/posts/paridhilatawa_this-summer-i-had-the-exciting-opportunity-activity-7366852591655260165-_WiI">[Reflection]</a></div>
  </div>
</div>

<div class="about-leadership-item has-thumb">
  <img class="item-thumb" src="{{ '/assets/img/talks/l7-poster.png' | relative_url }}" alt="Poster on the functional diversity of the L7-like ribosomal protein" loading="lazy">
  <div class="item-body">
  <div class="item-title">Exploring the Functional Diversity of the L7-like Ribosomal Protein</div>
  <p class="item-note">2025 · MIT EECS SuperUROP Poster Symposium · Paridhi Latawa, Guilhem Faure, Feng Zhang</p>
  <div class="item-links"><a href="{{ '/assets/pdf/l7-superurop-poster.pdf' | relative_url }}">[Poster]</a> <a href="https://docs.google.com/document/d/1e5llFR3EuPsvmXV9nFav0nsp6yoTWPo9NUa0Zv7M_PE/preview">[Report]</a> <a href="https://superurop.mit.edu/scholars/paridhi-pari-latawa/">[Scholar Page]</a></div>
  </div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Elucidating the Role of Abraxas on Telomere Maintenance & Alternative Lengthening of Telomeres</div>
  <p class="item-note">2024 · MD Anderson Cancer Center CATALYST Poster Symposium & Division of Radiation Oncology Symposium · Paridhi Latawa, Longqiang Wang, Bin Wang</p>
  <div class="item-links"><a href="https://www.linkedin.com/posts/paridhilatawa_this-summer-i-had-the-wonderful-opportunity-activity-7236330775917318144-GsK1">[Reflection]</a></div>
</div>

<div class="about-leadership-item has-thumb">
  <img class="item-thumb" src="{{ '/assets/img/talks/protein-llm-title-slide.png' | relative_url }}" alt="Title slide for the protein engineering language model talk" loading="lazy">
  <div class="item-body">
  <div class="item-title">Investigating the Capabilities of Large Language Models for Protein Engineering</div>
  <p class="item-note">2024 · MIT Biology Undergraduate Research Symposium · Paridhi Latawa, Alvin Chan, Giovanni Traverso, Robert Langer</p>
  <div class="item-links"><a href="https://docs.google.com/presentation/d/11NQkCfbt8IblwI3cw-KK3SW3qXthYzzxdxhZ6YW59Dg/preview">[Slides]</a></div>
  </div>
</div>
</div>

</details>

<details class="about-collapsible" id="projects" open>
<summary><h2 class="about-section-title">Projects</h2></summary>

<div class="section-body">
<div class="about-leadership-item">
  <div class="item-title">Conditional Generation from Few-shot Examples for Protein Design</div>
  <p class="item-note">Oct 2025 – Dec 2025 · MIT 6.S981: AI for Protein Biology · with Zhilei Bei and Weilang Luo</p>
  <p class="item-desc">Few-shot generative framework that conditions a generative multiple sequence alignment (MSA) protein language model on a small set of example sequences to synthesize novel proteins exhibiting desired features.</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item has-thumb">
  <img class="item-thumb" src="{{ '/assets/img/projects/alzheimers-slides.png' | relative_url }}" alt="Title slide for the Alzheimer's pseudotime analysis project" loading="lazy">
  <div class="item-body">
  <div class="item-title">A Pseudo-Time Analysis of Cellular Trajectories in Alzheimer's Disease using scRNA Sequencing</div>
  <p class="item-note">Nov 2024 – Dec 2024 · MIT 6.8701: Machine Learning for Computational Biology · with Jenny Prince and Selina Qian</p>
  <p class="item-desc">Used immune cell-specific single-nucleus RNA-seq data to model temporal gene expression dynamics in Alzheimer's Disease, generating cell- and sample-level pseudotime trajectories correlated with clinical progression and identifying key marker genes and pathways linked to immune activation and AD severity.</p>
  <div class="item-links"><a href="https://drive.google.com/file/d/1X3pht29L8zgKKfiunw0vJPeVYzHPOj_y/view">[Paper]</a> <a href="https://drive.google.com/file/d/1mGeI_zj_tKu50cqAnZWTPlWDQww-YVuv/view">[Slides]</a></div>
  </div>
</div>

<div class="about-leadership-item has-thumb">
  <img class="item-thumb" src="{{ '/assets/img/projects/nlp-poster.png' | relative_url }}" alt="Poster for the MIT Confessions sentiment and topic modelling project" loading="lazy">
  <div class="item-body">
  <div class="item-title">Decoding MIT's Digital Diary: Combining Sentiment, Topic Modeling, and an MIT Confessions-Powered ChatBot for Social Data Analysis</div>
  <p class="item-note">Nov 2024 – Dec 2024 · MIT 6.8611: Quantitative Methods for Natural Language Processing · with Anika Puri and Sejal Rathi</p>
  <p class="item-desc">Analyzed over 61,000 posts from MIT Confessions (2013–2024) with NLP techniques to uncover evolving trends in student sentiment, wellness, and social dynamics, and created a RAG + LLM-based ChatBot that allowed for context-aware engagement with the data to inform institutional support and policy.</p>
  <div class="item-links"><a href="https://drive.google.com/file/d/1NtyZ53-A2qq2I5LxNq1D8CKSerjtKL2z/view">[Paper]</a> <a href="https://drive.google.com/file/d/1jD_h16JYJmXsIfOZk_nu9q2BtidqfMKQ/view">[Poster]</a></div>
  </div>
</div>

<div class="about-leadership-item has-thumb">
  <img class="item-thumb" src="{{ '/assets/img/projects/smiles-slides.png' | relative_url }}" alt="Title slide for the multimodal SMILES property prediction project" loading="lazy">
  <div class="item-body">
  <div class="item-title">Encoder-Decoder Model for Multimodal SMILES Latent Space Representation Property Prediction</div>
  <p class="item-note">Apr 2024 – May 2024 · MIT 6.8711: Generative AI for Biology (Computational Systems Biology: Deep Learning in the Life Sciences) · with Vincent Lin and Vanessa Xiao</p>
  <p class="item-desc">Proposed a novel multimodal architecture using an autoencoder and fine-tuned ChemBERTa model to generate feature embeddings for SMILES and gene expression datasets to feed into a regressor for IC50 drug viability prediction.</p>
  <div class="item-links"><a href="https://drive.google.com/file/d/19HOK4B6_nfNripPmaZbztrAA7dhcKnQ8/view">[Paper]</a> <a href="https://drive.google.com/file/d/1Bmd_5JG6p5SYAfoY0fz4pPomk4a88Nbd/view">[Slides]</a></div>
  </div>
</div>

<div class="about-leadership-item">
  <div class="item-title">An Investigation of the Biotechnology and Life Sciences Innovation Ecosystem in Denmark</div>
  <p class="item-note">May 2023 – Sep 2023 · MIT Innovation Diplomats (iDiplomats) Program</p>
  <p class="item-desc">Independent study researching Denmark's biotech innovation ecosystem, interviewing leaders from government, industry, and academia.</p>
  <div class="item-links"><a href="https://docs.google.com/document/d/1V7H3nek8PYpwYNvfNeZWNmJVDtVeHKKsXqaqsVqq9eI/preview">[Paper]</a> <a href="https://docs.google.com/presentation/d/1WyK5nwiMdVmmPPr8Ap_AdZRlNrKvyAhhb0u2F_zXJus/preview">[Recap]</a></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Analysis of the Vaping Pandemic</div>
  <p class="item-note">Jul 2019 – May 2020</p>
  <ul class="item-bullets">
    <li>Stemming from round tables on teen health attended by Austin leaders from several school districts as well as speaking and attending AISD SHAC meetings, I analyzed survey data and experimented with nicotine and plant cells.</li>
    <li>This data will allow for an informed approach to teen vaping prevention campaigns and serve as a focus for anti-addiction support.</li>
    <li>This project won the Superintendent Award at the AERSF.</li>
  </ul>
  <div class="item-links"></div>
</div>
</div>

</details>

<details class="about-collapsible" id="awards" open>
<summary><h2 class="about-section-title">Honors &amp; Awards</h2></summary>

<div class="section-body">
<div class="section-scroll">

<h3 class="about-awards-year">2026</h3>

<ul class="about-awards-bullets">
<li>
  <span class="award-title">NSF Graduate Research Fellowship Program (GRFP)</span>
  <span class="award-note">May 2026</span>
</li>

</ul>

<h3 class="about-awards-year">2024–2025</h3>

<ul class="about-awards-bullets">
<li>
  <span class="award-title">MIT Eric & Wendy Schmidt Center Funded Research & Innovation Scholar</span>
  <span class="award-note">Oct 2024</span>
  <span class="award-desc">MIT EECS SuperUROP Scholar, selected as 1 of 8 computational biology scholars (Feng Zhang Lab).</span>
</li>

<li>
  <span class="award-title">HackMIT WisprAI Track, 3rd Place</span>
</li>

<li>
  <span class="award-title">AnitaB.org Grace Hopper Conference & SWE WE24 Conference Grant Awardee & Ambassador</span>
  <span class="award-note">Jan 2024</span>
</li>

</ul>

<h3 class="about-awards-year">2018–Present</h3>

<ul class="about-awards-bullets">
<li>
  <span class="award-title">NCWIT Award for Aspirations in Computing: 3x National Awardee (top 9.5% in US), Impact Award</span>
  <span class="award-note">Jan 2023</span>
  <ul class="award-sub">
    <li>MIT Campus Representative: led 4+ colleges to organize NCWIT AiC Boston-area receptions with 100+ attendees from 9 colleges & 11 high schools.</li>
    <li>Recognized with the Impact Award for leadership in expanding access to computing.</li>
  </ul>
</li>

</ul>

<h3 class="about-awards-year">2022</h3>

<ul class="about-awards-bullets">
<li>
  <span class="award-title">Apple Scholar</span>
  <span class="award-note">Mar 2022</span>
</li>

<li>
  <span class="award-title">Regeneron Science Talent Search (STS) Scholar</span>
  <span class="award-note">Jan 2022</span>
  <span class="award-desc">Top 300 in the nation's oldest and most prestigious science and math competition for high school seniors.</span>
</li>

<li>
  <span class="award-title">Regeneron International Science & Engineering Fair (ISEF) Finalist</span>
  <span class="award-note">2022</span>
  <span class="award-desc">Finalist in the Computational Biology & Bioinformatics category.</span>
</li>

<li>
  <span class="award-title">Texas Science & Engineering Fair (TXSEF): Regeneron Biomedical Science Award</span>
  <span class="award-note">2022</span>
</li>

<li>
  <span class="award-title">Austin Energy Regional Science Fair (AERSF): 1st in Cellular & Molecular Biology, Best of Fair</span>
  <span class="award-note">2022</span>
  <span class="award-desc">Ranked 1st in the Cellular & Molecular Biology category (advancing to TXSEF), selected as a Best of Fair project (advancing to ISEF 2022), and received the Austin Energy STEM scholarship.</span>
</li>

<li>
  <span class="award-title">National Honor Society Scholarship + Finalist</span>
  <span class="award-note">Jan 2022</span>
</li>

<li>
  <span class="award-title">Schlumberger Founders Scholarship</span>
  <span class="award-note">Jan 2022</span>
</li>

<li>
  <span class="award-title">Bank of America Student Leader</span>
  <span class="award-note">Jan 2022</span>
</li>

<li>
  <span class="award-title">Coca-Cola Scholar</span>
  <span class="award-note">Jan 2022</span>
</li>

</ul>

<h3 class="about-awards-year">2021</h3>

<ul class="about-awards-bullets">
<li>
  <span class="award-title">World Science Scholar</span>
  <span class="award-note">Jun 2021</span>
  <span class="award-desc">World Science Festival.</span>
</li>

<li>
  <span class="award-title">Texas Education Agency Student Hero</span>
  <span class="award-note">Jan 2021</span>
</li>

<li>
  <span class="award-title">AERSF & TXSEF: 2nd in Cellular & Molecular Biology</span>
  <span class="award-note">2021</span>
  <span class="award-desc">Ranked 2nd in the Cellular & Molecular Biology category at both fairs; received a $2k research grant and an invitation to the Texas Governor's Science & Engineering Champions Academy to research solid-state nanopore sequencing at the SMU BAST Lab.</span>
</li>

<li>
  <span class="award-title">Sigma Xi Scientific Research Honor Society</span>
  <span class="award-note">2021</span>
  <span class="award-desc">Abstract accepted for the International Student Research Showcase Competition.</span>
</li>

</ul>

<h3 class="about-awards-year">2020</h3>

<ul class="about-awards-bullets">
<li>
  <span class="award-title">AERSF Superintendent Award: Best Project in District</span>
  <span class="award-note">2020</span>
  <span class="award-desc">For "Analysis of the Vaping Pandemic," focusing on schools in Austin, Texas.</span>
</li>

</ul>

</div>
</div>

</details>

<details class="about-collapsible" id="education" open>
<summary><h2 class="about-section-title">Education</h2></summary>

<div class="section-body">
<div class="about-leadership-item has-logo">
  <img class="item-logo" src="{{ '/assets/img/logos/mit.svg' | relative_url }}" alt="MIT logo" loading="lazy">
  <div class="item-body">
  <div class="item-title">Massachusetts Institute of Technology, M.Eng. in Computer Science and Molecular Biology</div>
  <p class="item-note">Jun 2025 – May 2026</p>
  <div class="item-links"></div>
  </div>
</div>

<div class="about-leadership-item has-logo">
  <img class="item-logo" src="{{ '/assets/img/logos/mit.svg' | relative_url }}" alt="MIT logo" loading="lazy">
  <div class="item-body">
  <div class="item-title">Massachusetts Institute of Technology, B.S. in Computer Science & Molecular Biology, Minor in Economics</div>
  <p class="item-note">2022 – 2026</p>
  <ul class="item-bullets">
    <li>Activities and societies:
      <ul class="item-subbullets">
        <li><a href="https://urop.mit.edu/" target="_blank" rel="noopener noreferrer">MIT UROP</a></li>
        <li><a href="https://misti.mit.edu/denmark" target="_blank" rel="noopener noreferrer">MISTI Denmark</a></li>
        <li><a href="https://biotech.mit.edu/" target="_blank" rel="noopener noreferrer">Biotechnology Group</a></li>
        <li><a href="https://neet.mit.edu/threads/lm" target="_blank" rel="noopener noreferrer">NEET Living Machines Certificate Program</a></li>
        <li><a href="https://sandbox.mit.edu/" target="_blank" rel="noopener noreferrer">Sandbox Innovation Fund</a></li>
        <li><a href="https://ua.mit.edu/" target="_blank" rel="noopener noreferrer">Undergraduate Association</a></li>
        <li><a href="https://ome.mit.edu/laureates-and-leaders" target="_blank" rel="noopener noreferrer">Laureates and Leaders</a></li>
        <li><a href="https://advising.mit.edu/advising-resources/for-associate-advisors" target="_blank" rel="noopener noreferrer">Associate Advisor</a></li>
        <li>MIT EECS Committee for Community Engagement</li>
        <li><a href="https://engineering.mit.edu/about/leadership/sage" target="_blank" rel="noopener noreferrer">MIT School of Engineering Undergraduate Student Advisory Group</a></li>
        <li>South Asian Association of Students</li>
      </ul>
    </li>
    <li>Teaching Assistant for Introduction to Probability and Statistics.</li>
  </ul>
  <div class="item-links"></div>
  </div>
</div>

<div class="about-leadership-item has-logo">
  <img class="item-logo" src="{{ '/assets/img/logos/ycombinator.svg' | relative_url }}" alt="Y Combinator logo" loading="lazy">
  <div class="item-body">
  <div class="item-title">Y Combinator</div>
  <p class="item-note">Jun 2026 – Aug 2026</p>
  <div class="item-links"></div>
  </div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Liberal Arts & Science Academy, High School Diploma</div>
  <p class="item-note">2018 – 2022</p>
  <p class="item-desc">Activities and societies: LASA Science Fair Club Captain, Mu Alpha Theta Math Honor Society VP, Science Olympiad, Symphony Orchestra.</p>
  <div class="item-links"></div>
</div>

<h3 class="about-awards-year">Coursework</h3>

<p class="course-legend"><em>* indicates graduate coursework.</em></p>

<h4 class="about-course-group">Computer Science</h4>

<ul class="about-course-list">
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=6.8701">6.8701</a><span class="course-grad">*</span> <span class="course-name">Machine Learning for Computational Biology</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=6.8711">6.8711</a><span class="course-grad">*</span> <span class="course-name">Generative AI for Biology</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=6.S981">6.S981</a><span class="course-grad">*</span> <span class="course-name">AI for Protein Biology</span></li>
  <li><span class="course-name">AI &amp; Decision Making for Medicine</span><span class="course-grad">*</span></li>
  <li><span class="course-name">Topics in Computational Molecular Biology</span><span class="course-grad">*</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=6.8611">6.8611</a> <span class="course-name">Quantitative Methods for Natural Language Processing</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=6.3900">6.3900</a> <span class="course-name">Introduction to Machine Learning</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=6.1210">6.1210</a> <span class="course-name">Introduction to Algorithms</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=6.1010">6.1010</a> <span class="course-name">Fundamentals of Programming</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=6.1200">6.1200</a> <span class="course-name">Mathematics for Computer Science (Discrete Math)</span></li>
</ul>

<h4 class="about-course-group">Mathematics</h4>

<ul class="about-course-list">
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=18.05">18.05</a> <span class="course-name">Introduction to Probability &amp; Statistics</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=18.06">18.06</a> <span class="course-name">Linear Algebra</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=18.01">18.01</a> <span class="course-name">Calculus I</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=18.02">18.02</a> <span class="course-name">Calculus II</span></li>
</ul>

<h4 class="about-course-group">Biology &amp; Chemistry</h4>

<ul class="about-course-list">
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=7.05">7.05</a> <span class="course-name">General Biochemistry</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=7.06">7.06</a> <span class="course-name">Cell Biology</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=5.12">5.12</a> <span class="course-name">Organic Chemistry</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=20.110">20.110</a> <span class="course-name">Thermodynamics of Biomolecular Systems</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=7.03">7.03</a> <span class="course-name">Genetics</span></li>
</ul>

<h4 class="about-course-group">Economics</h4>

<ul class="about-course-list">
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=14.73">14.73</a> <span class="course-name">The Challenge of World Poverty</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=14.03">14.03</a> <span class="course-name">Microeconomic Theory and Public Policy</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=14.13">14.13</a> <span class="course-name">Psychology and Economics</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=14.01">14.01</a> <span class="course-name">Principles of Microeconomics</span></li>
  <li><a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=14.02">14.02</a> <span class="course-name">Principles of Macroeconomics</span></li>
  <li><span class="course-name">Innovation Diplomats Independent Study in Management</span></li>
</ul>
</div>

</details>

<details class="about-collapsible" id="teaching" open>
<summary><h2 class="about-section-title">Teaching &amp; Mentorship</h2></summary>

<div class="section-body">
<div class="about-teaching-item">
  <div class="item-title">Teaching Assistant, <a class="course-num-link" href="http://student.mit.edu/catalog/search.cgi?search=18.05">18.05</a> Introduction to Probability &amp; Statistics (MIT)</div>
  <p class="item-note">Feb 2025 – May 2025</p>
  <ul class="item-bullets">
    <li>Led weekly in-class problem-solving sessions, office hours, and coding lessons for 140+ students.</li>
    <li>Graded homework assignments and provided detailed feedback.</li>
  </ul>
  <div class="item-links"><a href="http://student.mit.edu/catalog/search.cgi?search=18.05">[Course]</a></div>
</div>

<div class="about-teaching-item">
  <div class="item-title">Associate Advisor (MIT)</div>
  <p class="item-note">Aug 2025 – Present</p>
  <ul class="item-bullets">
    <li>Advised students on academic planning, course selection, and research involvement.</li>
    <li>Collaborated with Professor Collin Stultz to improve advisee support and registration processes.</li>
  </ul>
  <div class="item-links"><a href="https://firstyear.mit.edu/first-year-advising/your-advising-network-advising-roles">[Program]</a></div>
</div>
</div>

</details>

<details class="about-collapsible" id="entrepreneurship" open>
<summary><h2 class="about-section-title">Entrepreneurship</h2></summary>

<div class="section-body">
<div class="about-leadership-item">
  <div class="item-title"><a href="https://www.illumelabs.ai">Illume</a></div>
  <p class="item-note">2026 – Present</p>
  <ul class="item-bullets">
    <li>Founded a health tech startup in the Y Combinator S26 batch.</li>
  </ul>
  <div class="item-links"><a href="https://www.illumelabs.ai">[Website]</a></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Co-Founder, EasyComm</div>
  <p class="item-note">Jun 2022 – Present</p>
  <ul class="item-bullets">
    <li>Developing a speech technology app for children with Down Syndrome (patent pending).</li>
    <li>Funded by the <a href="https://sandbox.mit.edu/">MIT Sandbox Innovation Fund</a>.</li>
    <li>Selected for the Harvard Law Entrepreneurship Project / Cooley LLP program and the Takeda Biopharma Internship.</li>
  </ul>
  <div class="item-links"><a href="https://sandbox.mit.edu/">[MIT Sandbox]</a></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Founder and Executive Director, SparkED</div>
  <p class="item-note">Apr 2019 – May 2024</p>
  <ul class="item-bullets">
    <li>Equipped 2000+ youth across 11 countries with STEM resources.</li>
    <li>Led a 20+ volunteer team and launched chapters beyond the founding city.</li>
  </ul>
  <div class="item-links"><a href="https://www.pointsoflight.org/daily-point-of-light/texas-teen-sparked-success-through-service-for-next-generation-of-empowered-youth/">[Press]</a></div>
</div>
</div>

</details>

<details class="about-collapsible" id="leadership" open>
<summary><h2 class="about-section-title">Service &amp; Community</h2></summary>

<div class="section-body">
<div class="section-scroll">
<div class="about-leadership-item">
  <div class="item-title">MIT School of Engineering Student Advisory Group & EECS Community Engagement Committee</div>
  <ul class="item-bullets">
    <li>Connect with Dean and faculty on education, engagement, research, and student life.</li>
    <li>Created proposals for alumni funding requests for national conferences.</li>
  </ul>
  <div class="item-links"><a href="https://engineering.mit.edu/">[Website]</a></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Lead Communications Ambassador, MIT PKG Center for Public Service</div>
  <p class="item-desc">Facilitate connection between PKG and students, lead interns, and organize outreach and media presence.</p>
  <div class="item-links"><a href="https://pkgcenter.mit.edu/">[Website]</a></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Board Member, MIT South Asian Association of Students</div>
  <p class="item-desc">Organized the largest cultural events at MIT, including Garba, Holi, and South Asian Formal.</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">MIT Innovation Diplomats (iDiplomats) Program</div>
  <p class="item-note">May 2023 – Sep 2023</p>
  <ul class="item-bullets">
    <li>Researched Denmark's biotech innovation ecosystem.</li>
    <li>Interviewed 11 leaders from government, industry, and academia.</li>
  </ul>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Developmental and Behavioral Pediatrics, Boston Medical Center</div>
  <p class="item-note">Dec 2022 – Feb 2023</p>
  <p class="item-desc">Autism Resources Program intern supporting 8+ low-socioeconomic families and patient cases with Autism Spectrum Disorder.</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Weekend Pre-Med Academy, Harvard Student Agencies</div>
  <p class="item-note">Jul 2019 – Jun 2020</p>
  <p class="item-desc">Brought the Pre-Med Academy I had attended to my own high school in Austin, recruiting 100+ Texas students and inviting practicing physicians to speak.</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Social Chair, MIT Laureates and Leaders Program</div>
  <p class="item-desc">Office of Minority Education leadership and community programming.</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Recruitment Director & Panhellenic Delegate, MIT Panhellenic Council</div>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">MIT Undergraduate Association</div>
  <p class="item-desc">Education Committee and Community Service Committee.</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">MIT Campus Ambassador, NCWIT</div>
  <p class="item-note">Aug 2022 – Present</p>
  <div class="item-links"><a href="https://www.aspirations.org/">[Website]</a></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Events Lead, Science Olympiad</div>
  <p class="item-note">Aug 2016 – May 2022</p>
  <ul class="item-bullets">
    <li>Competed in various events focusing around life sciences, including going to National competitions twice as well as competing with the LASA A team at out-of-state tournaments at UPenn, MIT, Rice, and UT.</li>
    <li>Ranked 7th in Ecology & 6th in Roller Coaster (Engineering) at Nationals.</li>
  </ul>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Citywide Leader, Health Through Science (HTS)</div>
  <p class="item-note">Jul 2018 – 2020</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">District Advisory Council Member; Student Health Advisory Board, Austin Independent School District</div>
  <div class="item-links"></div>
</div>
</div>
</div>

</details>

<details class="about-collapsible" id="personal" open>
<summary><h2 class="about-section-title">Personal Interests &amp; Hobbies</h2></summary>

<div class="section-body">
<div class="about-hobbies">
  <p>I enjoy pursuing adventures, from visiting new places to hiking and biking locally in Cambridge and Austin. I played the viola for 8 years, painted for 5 years, previously tried rowing, and am currently really interested in photography and videography.</p>
  <p>I am passionate about science communication and blogging. Here is my <a href="https://paridhi-latawa.medium.com/">Medium Blog</a>. In my free time, you'll find me solving puzzles or traveling!</p>
  <p>Languages: advanced in English, Hindi, & Punjabi; beginner in Spanish.</p>
</div>

<h3 class="about-awards-year">Computational Skills</h3>

<ul class="skills-list">
  <li>Machine Learning</li>
  <li>LLMs</li>
  <li>Python</li>
  <li>PyTorch</li>
  <li>Pandas</li>
  <li>Biopython</li>
  <li>R Studio</li>
  <li>Linux</li>
  <li>HPC</li>
  <li>ImageJ/Fiji</li>
  <li>Imaging</li>
</ul>

<h3 class="about-awards-year">Wet Lab Skills</h3>

<ul class="skills-list">
  <li>PCR</li>
  <li>Gel Electrophoresis</li>
  <li>Western Blot</li>
  <li>IF</li>
  <li>FISH</li>
  <li>Protein Purification</li>
  <li>Transformation</li>
  <li>Gibson Assembly</li>
  <li>Fluorescence Anisotropy/Polarization</li>
  <li>Fluorescence Microscopy</li>
  <li>Biotech Lab Technician Certificate (ACC)</li>
</ul>
</div>

</details>
