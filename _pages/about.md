---
layout: about
title: About
permalink: /
# subtitle: <em>"An object in motion stays in motion."</em>
subtitle:

profile:
  align: right
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
<summary><h2 class="about-section-title">Publications & Research</h2></summary>

<div class="publications pub-scroll">
{% bibliography %}
</div>

</details>

<details class="about-collapsible" id="entrepreneurship" open>
<summary><h2 class="about-section-title">Entrepreneurship</h2></summary>

<div class="about-leadership-item">
  <div class="item-title"><a href="https://www.illumelabs.ai">Illume</a></div>
  <p class="item-desc">Health tech startup in the Y Combinator S26 batch.</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">EasyComm</div>
  <p class="item-desc">Speech technology app for children with Down Syndrome, funded by MIT Sandbox Innovation Fund. Patent pending.</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">SparkED</div>
  <p class="item-desc">Nonprofit that equipped 2000+ youth across 11 countries with STEM resources.</p>
  <div class="item-links"></div>
</div>

</details>

<details class="about-collapsible" id="projects" open>
<summary><h2 class="about-section-title">Projects</h2></summary>

<div class="about-leadership-item">
  <div class="item-title">Conditional Generation from Few-shot Examples for Protein Design</div>
  <p class="item-note">Oct 2025 – Dec 2025 · MIT 6.S981: AI for Protein Biology · with Zhilei Bei and Weilang Luo</p>
  <p class="item-desc">Few-shot generative framework that conditions a generative multiple sequence alignment (MSA) protein language model on a small set of example sequences to synthesize novel proteins exhibiting desired features.</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">A Pseudo-Time Analysis of Cellular Trajectories in Alzheimer's Disease using scRNA Sequencing</div>
  <p class="item-note">Nov 2024 – Dec 2024 · MIT 6.8701: Machine Learning for Computational Biology · with Jenny Prince and Selina Qian</p>
  <p class="item-desc">Used immune cell-specific single-nucleus RNA-seq data to model temporal gene expression dynamics in Alzheimer's Disease, generating cell- and sample-level pseudotime trajectories correlated with clinical progression and identifying key marker genes and pathways linked to immune activation and AD severity.</p>
  <div class="item-links"><a href="https://drive.google.com/file/d/1X3pht29L8zgKKfiunw0vJPeVYzHPOj_y/view">[Paper]</a> <a href="https://drive.google.com/file/d/1mGeI_zj_tKu50cqAnZWTPlWDQww-YVuv/view">[Poster]</a></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Decoding MIT's Digital Diary: Combining Sentiment, Topic Modeling, and an MIT Confessions-Powered ChatBot</div>
  <p class="item-note">Nov 2024 – Dec 2024 · MIT 6.8611: Quantitative Methods for Natural Language Processing · with Anika Puri and Sejal Rathi</p>
  <p class="item-desc">Analyzed over 61,000 posts from MIT Confessions (2013–2024) with NLP techniques to uncover evolving trends in student sentiment, wellness, and social dynamics, and created a RAG + LLM-based ChatBot that allowed for context-aware engagement with the data to inform institutional support and policy.</p>
  <div class="item-links"><a href="https://drive.google.com/file/d/1NtyZ53-A2qq2I5LxNq1D8CKSerjtKL2z/view">[Paper]</a> <a href="https://drive.google.com/file/d/1jD_h16JYJmXsIfOZk_nu9q2BtidqfMKQ/view">[Poster]</a></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Encoder-Decoder Model for Multimodal SMILES Latent Space Representation Property Prediction</div>
  <p class="item-note">Apr 2024 – May 2024 · MIT 6.8711: Generative AI for Biology (Computational Systems Biology: Deep Learning in the Life Sciences) · with Vincent Lin and Vanessa Xiao</p>
  <p class="item-desc">Proposed a novel multimodal architecture using an autoencoder and fine-tuned ChemBERTa model to generate feature embeddings for SMILES and gene expression datasets to feed into a regressor for IC50 drug viability prediction.</p>
  <div class="item-links"><a href="https://drive.google.com/file/d/19HOK4B6_nfNripPmaZbztrAA7dhcKnQ8/view">[Paper]</a> <a href="https://drive.google.com/file/d/1Bmd_5JG6p5SYAfoY0fz4pPomk4a88Nbd/view">[Slides]</a></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">An Investigation of the Biotechnology and Life Sciences Innovation Ecosystem in Denmark</div>
  <p class="item-note">May 2023 – Sep 2023 · MIT Innovation Diplomats (iDiplomats) Program</p>
  <p class="item-desc">Independent study researching Denmark's biotech innovation ecosystem, interviewing leaders from government, industry, and academia.</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Analysis of the Vaping Pandemic</div>
  <p class="item-note">Jul 2019 – May 2020</p>
  <p class="item-desc">Stemming from round tables on teen health attended by Austin leaders from several school districts, as well as speaking at and attending AISD SHAC meetings, I analyzed survey data on the teen vaping epidemic.</p>
  <div class="item-links"></div>
</div>

</details>

<details class="about-collapsible" id="courses" open>
<summary><h2 class="about-section-title">Courses</h2></summary>

<div class="section-scroll">

<h3 class="about-awards-year">Graduate</h3>

<div class="about-courses">
  <span class="course-chip"><span class="course-num">6.8701</span> Machine Learning for Computational Biology</span>
  <span class="course-chip"><span class="course-num">6.8711</span> Generative AI for Biology</span>
  <span class="course-chip"><span class="course-num">6.S981</span> AI for Protein Biology</span>
  <span class="course-chip">AI &amp; Decision Making for Medicine</span>
  <span class="course-chip">Topics in Computational Molecular Biology</span>
</div>

<h3 class="about-awards-year">Undergraduate — CS &amp; Math</h3>

<div class="about-courses">
  <span class="course-chip"><span class="course-num">6.8611</span> Quantitative Methods for Natural Language Processing</span>
  <span class="course-chip">Machine Learning</span>
  <span class="course-chip">Probability &amp; Statistics</span>
  <span class="course-chip">Algorithms</span>
  <span class="course-chip">Linear Algebra</span>
  <span class="course-chip">Programming</span>
  <span class="course-chip">Discrete Math</span>
  <span class="course-chip">Calculus I &amp; II</span>
</div>

<h3 class="about-awards-year">Undergraduate — Biology &amp; Chemistry</h3>

<div class="about-courses">
  <span class="course-chip">Biochemistry</span>
  <span class="course-chip">Cell Biology</span>
  <span class="course-chip">Organic Chemistry</span>
  <span class="course-chip">Thermodynamics</span>
  <span class="course-chip">Genetics</span>
</div>

<h3 class="about-awards-year">Undergraduate — Economics</h3>

<div class="about-courses">
  <span class="course-chip">The Challenge of World Poverty</span>
  <span class="course-chip">Microeconomic Theory and Public Policy</span>
  <span class="course-chip">Psychology and Economics</span>
  <span class="course-chip">Microeconomics</span>
  <span class="course-chip">Macroeconomics</span>
  <span class="course-chip">Innovation Diplomats Independent Study in Management</span>
</div>

</div>

</details>

<details class="about-collapsible" id="education" open>
<summary><h2 class="about-section-title">Education</h2></summary>

<div class="about-leadership-item">
  <div class="item-title">Massachusetts Institute of Technology — M.Eng., Computer Science and Molecular Biology</div>
  <p class="item-note">Jun 2025 – May 2026</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Massachusetts Institute of Technology — B.S., Computer Science & Molecular Biology, Minor in Economics</div>
  <p class="item-note">2022 – 2026</p>
  <p class="item-desc">Activities and societies: MIT UROP, MISTI Denmark, Biotechnology Group, NEET Living Machines Certificate Program, Sandbox Innovation Fund, Undergraduate Association, Laureates and Leaders, Associate Advisor, MIT EECS Committee for Community Engagement, MIT School of Engineering Undergraduate Student Advisory Group, South Asian Association of Students. Teaching Assistant for Introduction to Probability and Statistics.</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Y Combinator</div>
  <p class="item-note">Jun 2026 – Aug 2026</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Liberal Arts & Science Academy — High School Diploma</div>
  <p class="item-note">2018 – 2022</p>
  <p class="item-desc">Activities and societies: LASA Science Fair Club Captain, Mu Alpha Theta Math Honor Society VP, Science Olympiad, Symphony Orchestra.</p>
  <div class="item-links"></div>
</div>

</details>

<details class="about-collapsible" id="awards" open>
<summary><h2 class="about-section-title">Honors & Awards</h2></summary>

<div class="section-scroll">

<h3 class="about-awards-year">2026</h3>

<div class="about-award-item">
  <div class="item-title">NSF Graduate Research Fellowship Program (GRFP)</div>
  <div class="item-links"></div>
</div>

<h3 class="about-awards-year">2024–2025</h3>

<div class="about-award-item">
  <div class="item-title">MIT Eric & Wendy Schmidt Center Research & Innovation Scholar</div>
  <p class="item-desc">1 of 8 computational biology scholars</p>
  <div class="item-links"></div>
</div>

<div class="about-award-item">
  <div class="item-title">HackMIT WisprAI Track, 3rd Place</div>
  <div class="item-links"></div>
</div>

<div class="about-award-item">
  <div class="item-title">AnitaB.org Grace Hopper Conference & SWE WE24 Grant Awardee & Ambassador</div>
  <div class="item-links"></div>
</div>

<h3 class="about-awards-year">2022</h3>

<div class="about-award-item">
  <div class="item-title">Regeneron International Science & Engineering Fair Finalist</div>
  <div class="item-links"></div>
</div>

<div class="about-award-item">
  <div class="item-title">Austin Regional Science Fair — Best of Fair Award</div>
  <div class="item-links"></div>
</div>

<div class="about-award-item">
  <div class="item-title">Regeneron STS Scholar</div>
  <div class="item-links"></div>
</div>

<div class="about-award-item">
  <div class="item-title">Coca-Cola Scholar</div>
  <div class="item-links"></div>
</div>

<div class="about-award-item">
  <div class="item-title">Apple Scholar</div>
  <div class="item-links"></div>
</div>

<h3 class="about-awards-year">2021</h3>

<div class="about-award-item">
  <div class="item-title">Austin Regional Science Fair — Superintendent's Award</div>
  <div class="item-links"></div>
</div>

<h3 class="about-awards-year">2018–Present</h3>

<div class="about-award-item">
  <div class="item-title">NCWIT Award for Aspirations in Computing — 3x National Awardee, Impact Award</div>
  <div class="item-links"></div>
</div>

<h3 class="about-awards-year">Other</h3>

<div class="about-award-item">
  <div class="item-title">World Science Scholar</div>
  <div class="item-links"></div>
</div>

<div class="about-award-item">
  <div class="item-title">Bank of America Student Leader</div>
  <div class="item-links"></div>
</div>

<div class="about-award-item">
  <div class="item-title">Texas Education Agency Student Hero</div>
  <div class="item-links"></div>
</div>

</div>

</details>

<details class="about-collapsible" id="teaching" open>
<summary><h2 class="about-section-title">Teaching & Mentorship</h2></summary>

<div class="about-teaching-item">
  <div class="item-title">Teaching Assistant, Intro to Probability & Statistics (MIT)</div>
  <p class="item-desc">Led weekly in-class problem-solving sessions, office hours, and coding lessons for 140+ students.</p>
  <div class="item-links"></div>
</div>

<div class="about-teaching-item">
  <div class="item-title">Associate Advisor (MIT)</div>
  <p class="item-desc">Advised students on academic planning, course selection, and research involvement. Collaborated with Professor Collin Stultz to improve advisee support.</p>
  <div class="item-links"></div>
</div>

</details>

<details class="about-collapsible" id="leadership" open>
<summary><h2 class="about-section-title">Leadership & Community Service</h2></summary>

<div class="section-scroll">
<div class="about-leadership-item">
  <div class="item-title">Co-Founder, EasyComm</div>
  <p class="item-desc">Speech technology app for children with Down Syndrome, funded by MIT Sandbox Innovation Fund. Patent pending.</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">MIT School of Engineering Student Advisory Group</div>
  <p class="item-desc">Connect with Dean and faculty on education, engagement, research, and student life.</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Lead Communications Ambassador, MIT PKG Center for Public Service</div>
  <p class="item-desc">Facilitate connection between PKG and students, lead interns, and organize outreach and media presence.</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Board Member, MIT South Asian Association of Students</div>
  <p class="item-desc">Organized the largest cultural events at MIT, including Garba, Holi, and South Asian Formal.</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">MIT Innovation Diplomats (iDiplomats) Program</div>
  <p class="item-desc">Researched Denmark's biotech innovation ecosystem. Interviewed 11 leaders from government, industry, and academia.</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Developmental and Behavioral Pediatrics, Boston Medical Center</div>
  <p class="item-desc">Supported low-socioeconomic families and patient cases with Autism Spectrum Disorder.</p>
  <div class="item-links"></div>
</div>

<div class="about-leadership-item">
  <div class="item-title">Founder and Executive Director, SparkED</div>
  <p class="item-desc">Equipped 2000+ youth across 11 countries with STEM resources. Led a 20+ volunteer team.</p>
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
</div>

</details>

<details class="about-collapsible" id="personal" open>
<summary><h2 class="about-section-title">Personal Interests & Hobbies</h2></summary>

<div class="about-hobbies">
  <p>I enjoy pursuing adventures, from visiting new places to hiking and biking locally in Cambridge and Austin. I played the viola for 8 years, painted for 5 years, previously tried rowing, and am currently really interested in photography and videography.</p>
  <p>I am passionate about science communication and blogging — here is my <a href="https://paridhi-latawa.medium.com/">Medium Blog</a>. In my free time, you'll find me solving puzzles or traveling!</p>
</div>

</details>
