---
layout: about
title: About
permalink: /
# subtitle: <em>"An object in motion stays in motion."</em>
subtitle:

profile:
  align: right
  title: MEng & BS @ MIT in<br>Computer Science + Molecular Biology
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

Hi! I recently graduated with my M.Eng. and B.S. in [CS & Molecular Biology](https://catalog.mit.edu/interdisciplinary/undergraduate-programs/degrees/computer-science-molecular-biology/) from [MIT](https://www.mit.edu/), with a minor in [Economics](https://economics.mit.edu/). I am interested in developing algorithms, models, and frameworks to better understand and engineer biological processes to improve human health.

I recently founded [Illume](https://www.illumelabs.ai), a health tech startup in the [YC S26](https://www.ycombinator.com/) batch. I also completed my Master's with [Dr. Feng Zhang](https://zlab.bio) at the [Broad Institute](https://www.broadinstitute.org/), where I used mechanistic interpretability to investigate DNA LLMs for non-coding genome discovery. I have also previously researched with [Dr. Giovanni Traverso](https://www.l4te.org/dipl-team-member/giovanni-traverso/) and [Dr. Robert Langer](https://langerlab.mit.edu/) at the [Koch Institute](https://ki.mit.edu/) on unifying representations in foundation models, quality-aware tokenization, and property-constrained molecular design.

Previously, I have interned in [the AI Division @ Eli Lilly & Company](https://www.lilly.com/), the Genetics Department @ [MD Anderson Cancer Center](https://www.mdanderson.org/), and [Dianox](https://www.dianox.com/) (AI-powered biotech startup in Denmark).

You can email me at [platawa@mit.edu](mailto:platawa@mit.edu)!

---

<details class="about-collapsible" id="publications" open>
<summary><h2 class="about-section-title">Publications</h2></summary>

<div class="section-body">
<div class="publications pub-scroll">
{% bibliography %}
</div>
</div>

</details>

<details class="about-collapsible" id="talks" open>
<summary><h2 class="about-section-title">Symposiums &amp; Presentations</h2></summary>

<div class="section-body">
<div class="about-leadership-item">
  <div class="item-title">In Silico Perturbation Prediction Modeling using Single Cell Foundation Models</div>
  <p class="item-note">2025 · Eli Lilly Advanced Intelligence, Engineering & Biology Research · <strong>Paridhi Latawa</strong></p>
  <div class="item-links"><a href="https://www.linkedin.com/posts/paridhilatawa_this-summer-i-had-the-exciting-opportunity-activity-7366852591655260165-_WiI">[LinkedIn]</a></div>
</div>

<div class="about-leadership-item has-thumb">
  <img class="item-thumb" src="{{ '/assets/img/talks/l7-poster.png' | relative_url }}" alt="Poster on the functional diversity of the L7-like ribosomal protein" loading="lazy">
  <div class="item-body">
  <div class="item-title">Exploring the Functional Diversity of the L7-like Ribosomal Protein</div>
  <p class="item-note">2025 · MIT EECS SuperUROP Poster Symposium · <strong>Paridhi Latawa</strong>, Guilhem Faure, Feng Zhang</p>
  <div class="item-links"><a href="{{ '/assets/pdf/l7-superurop-poster.pdf' | relative_url }}">[Poster]</a> <a href="https://docs.google.com/document/d/1e5llFR3EuPsvmXV9nFav0nsp6yoTWPo9NUa0Zv7M_PE/preview">[Report]</a> <a href="https://superurop.mit.edu/scholars/paridhi-pari-latawa/">[Scholar Page]</a></div>
  </div>
</div>

<div class="about-leadership-item has-thumb">
  <img class="item-thumb" src="{{ '/assets/img/talks/abraxas-poster.png' | relative_url }}" alt="Poster on Abraxas and telomere maintenance" loading="lazy">
  <div class="item-body">
  <div class="item-title">Elucidating the Role of Abraxas on Telomere Maintenance & Alternative Lengthening of Telomeres</div>
  <p class="item-note">2024 · MD Anderson Cancer Center CATALYST Poster Symposium & Division of Radiation Oncology Symposium · <strong>Paridhi Latawa</strong>, Longqiang Wang, Bin Wang</p>
  <div class="item-links"><a href="https://www.linkedin.com/posts/paridhilatawa_this-summer-i-had-the-wonderful-opportunity-activity-7236330775917318144-GsK1">[LinkedIn]</a></div>
  </div>
</div>

<div class="about-leadership-item has-thumb">
  <img class="item-thumb" src="{{ '/assets/img/talks/protein-llm-title-slide.png' | relative_url }}" alt="Title slide for the protein engineering language model talk" loading="lazy">
  <div class="item-body">
  <div class="item-title">Investigating the Capabilities of Large Language Models for Protein Engineering</div>
  <p class="item-note">2024 · MIT Biology Undergraduate Research Symposium · <strong>Paridhi Latawa</strong>, Alvin Chan, Giovanni Traverso, Robert Langer</p>
  <div class="item-links"><a href="https://docs.google.com/presentation/d/11NQkCfbt8IblwI3cw-KK3SW3qXthYzzxdxhZ6YW59Dg/preview">[Slides]</a></div>
  </div>
</div>
</div>

</details>

<details class="about-collapsible" id="projects" open>
<summary><h2 class="about-section-title">Projects</h2></summary>

<div class="section-body">
<div class="about-leadership-item has-thumb">
  <img class="item-thumb" src="{{ '/assets/img/projects/protein-fewshot-cfg.png' | relative_url }}" alt="Training the MSA protein language model and steering generation with classifier-free guidance" loading="lazy">
  <div class="item-body">
  <div class="item-title">Conditional Generation from Few-shot Examples for Protein Design</div>
  <p class="item-note">Oct 2025 – Dec 2025 · MIT 6.S981: AI for Protein Biology · Zhilei Bei, Weiliang Luo, <strong>Paridhi Latawa</strong></p>
  <p class="item-desc">Few-shot generative framework that conditions a generative multiple sequence alignment (MSA) protein language model on a small set of example sequences to synthesize novel proteins exhibiting desired features.</p>
  <div class="item-links"><a href="{{ '/assets/pdf/protein-fewshot-writeup.pdf' | relative_url }}">[Paper]</a> <a href="{{ '/assets/pdf/protein-fewshot-slides.pdf' | relative_url }}">[Slides]</a></div>
  </div>
</div>

<div class="about-leadership-item has-thumb">
  <img class="item-thumb" src="{{ '/assets/img/projects/alzheimers-slides.png' | relative_url }}" alt="Title slide for the Alzheimer's pseudotime analysis project" loading="lazy">
  <div class="item-body">
  <div class="item-title">A Pseudo-Time Analysis of Cellular Trajectories in Alzheimer's Disease using scRNA Sequencing</div>
  <p class="item-note">Nov 2024 – Dec 2024 · MIT 6.8701: Machine Learning for Computational Biology · Jenny Prince, Selina Qian, <strong>Paridhi Latawa</strong></p>
  <p class="item-desc">Used immune cell-specific single-nucleus RNA-seq data to model temporal gene expression dynamics in Alzheimer's Disease, generating cell- and sample-level pseudotime trajectories correlated with clinical progression and identifying key marker genes and pathways linked to immune activation and AD severity.</p>
  <div class="item-links"><a href="https://drive.google.com/file/d/1X3pht29L8zgKKfiunw0vJPeVYzHPOj_y/view">[Paper]</a> <a href="https://drive.google.com/file/d/1mGeI_zj_tKu50cqAnZWTPlWDQww-YVuv/view">[Slides]</a></div>
  </div>
</div>

<div class="about-leadership-item has-thumb">
  <img class="item-thumb" src="{{ '/assets/img/projects/nlp-poster.png' | relative_url }}" alt="Poster for the MIT Confessions sentiment and topic modelling project" loading="lazy">
  <div class="item-body">
  <div class="item-title">Decoding MIT's Digital Diary: Combining Sentiment, Topic Modeling, and an MIT Confessions-Powered ChatBot for Social Data Analysis</div>
  <p class="item-note">Nov 2024 – Dec 2024 · MIT 6.8611: Quantitative Methods for Natural Language Processing · <strong>Paridhi Latawa</strong>, Anika Puri, Sejal Rathi</p>
  <p class="item-desc">Analyzed over 61,000 posts from MIT Confessions (2013–2024) with NLP techniques to uncover evolving trends in student sentiment, wellness, and social dynamics, and created a RAG + LLM-based ChatBot that allowed for context-aware engagement with the data to inform institutional support and policy.</p>
  <div class="item-links"><a href="https://drive.google.com/file/d/1NtyZ53-A2qq2I5LxNq1D8CKSerjtKL2z/view">[Paper]</a> <a href="https://drive.google.com/file/d/1jD_h16JYJmXsIfOZk_nu9q2BtidqfMKQ/view">[Poster]</a></div>
  </div>
</div>

<div class="about-leadership-item has-thumb">
  <img class="item-thumb" src="{{ '/assets/img/projects/smiles-architecture.png' | relative_url }}" alt="Architecture of the multimodal ChemBERTa and autoencoder regression model" loading="lazy">
  <div class="item-body">
  <div class="item-title">Encoder-Decoder Model for Multimodal SMILES Latent Space Representation Property Prediction</div>
  <p class="item-note">Apr 2024 – May 2024 · MIT 6.8711: Generative AI for Biology (Computational Systems Biology: Deep Learning in the Life Sciences) · Vincent Lin, <strong>Paridhi Latawa</strong>, Vanessa Xiao</p>
  <p class="item-desc">Proposed a novel multimodal architecture using an autoencoder and fine-tuned ChemBERTa model to generate feature embeddings for SMILES and gene expression datasets to feed into a regressor for IC50 drug viability prediction.</p>
  <div class="item-links"><a href="https://drive.google.com/file/d/19HOK4B6_nfNripPmaZbztrAA7dhcKnQ8/view">[Paper]</a> <a href="https://drive.google.com/file/d/1Bmd_5JG6p5SYAfoY0fz4pPomk4a88Nbd/view">[Slides]</a></div>
  </div>
</div>

<div class="about-leadership-item has-thumb">
  <img class="item-thumb" src="{{ '/assets/img/projects/denmark-idiplomats.jpg' | relative_url }}" alt="Recap slide from the iDiplomats program on the Copenhagen biotech innovation ecosystem" loading="lazy">
  <div class="item-body">
  <div class="item-title">An Investigation of the Biotechnology and Life Sciences Innovation Ecosystem in Denmark</div>
  <p class="item-note">May 2023 – Sep 2023 · MIT Innovation Diplomats (iDiplomats) Program</p>
  <p class="item-desc">Independent study researching Denmark's biotech innovation ecosystem, interviewing leaders from government, industry, and academia.</p>
  <div class="item-links"><a href="https://docs.google.com/document/d/1V7H3nek8PYpwYNvfNeZWNmJVDtVeHKKsXqaqsVqq9eI/preview">[Paper]</a> <a href="https://docs.google.com/presentation/d/1WyK5nwiMdVmmPPr8Ap_AdZRlNrKvyAhhb0u2F_zXJus/preview">[Recap]</a></div>
  </div>
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
