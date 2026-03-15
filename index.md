---
layout: default
title: Home
---

<section class="hero" id="top">
  <div class="hero-inner">
    <div class="hero-text">
      <p class="hero-tag">AI / ML Researcher</p>
      <h1 class="hero-name">Kabir<br/>Potdar</h1>
      <p class="hero-sub">
        Electronics & Telecommunications Engineer working at the intersection of
        <em>large language model efficiency</em> and <em>edge deployment</em>.
        Research focus: quantization, inference-time compute, and post-training optimization.
      </p>
      <div class="hero-cta">
        <a href="#research" class="btn btn-primary">View Research</a>
        <a href="#contact" class="btn btn-secondary">Get in Touch</a>
      </div>
    </div>
    <div class="hero-links-vertical">
      <a href="https://github.com/Kabir08" target="_blank" rel="noopener" title="GitHub">{% include icons/github.html %}</a>
      <a href="https://linkedin.com/in/kabir-potdar" target="_blank" rel="noopener" title="LinkedIn">{% include icons/linkedin.html %}</a>
      <a href="https://scholar.google.com/citations?user=i1GvrigAAAAJ&hl=en" target="_blank" rel="noopener" title="Google Scholar">{% include icons/scholar.html %}</a>
      <a href="https://x.com/potdarkabirr" target="_blank" rel="noopener" title="X">{% include icons/x.html %}</a>
      <span class="side-line"></span>
    </div>
  </div>
</section>

<!-- ═══════════════════════════════════ ABOUT ═══════════════════════════════════ -->
<section class="section" id="about">
  <div class="container">
    <div class="section-label">01 — About</div>
    <div class="about-grid">
      <div class="about-text">
        <h2>Building AI that runs at the edge.</h2>
        <p>
          I'm a researcher and engineer with a background in Electronics & Telecommunications Engineering,
          specialising in making large language models smaller, faster, and deployable on constrained hardware.
          My work sits at the intersection of <strong>cs.LG</strong> and <strong>cs.AR</strong>.
        </p>
        <p>
          I have production experience building RAG systems and quantized LLM pipelines, a preprint on LLM
          quantization, and a Kaggle competition placement. I'm currently pursuing MSc AI/ML programs abroad
          with a focus on efficient inference research.
        </p>
        <p>
          Longer term, I'm interested in founding AI-native tools and contributing to open-source infrastructure
          for efficient ML.
        </p>
      </div>
      <div class="about-sidebar">
        <div class="sidebar-block">
          <h4>Research Interests</h4>
          <ul>
            <li>LLM Quantization & Compression</li>
            <li>Efficient Inference & Edge Deployment</li>
            <li>Inference-time Compute Scaling</li>
            <li>Post-training Optimization</li>
            <li>RAG Systems & Production LLM Pipelines</li>
          </ul>
        </div>
        <div class="sidebar-block">
          <h4>Education</h4>
          <p class="edu-item">
            <strong>B.E. Electronics & Telecommunications</strong><br/>
            <span>Pimpri Chinchwad College of Engineering (PCCOE), Pune · 2023</span><br/>
            <span class="edu-gpa">GPA: 8.08 / 10</span>
          </p>
        </div>
        <div class="sidebar-block">
          <h4>Key Skills</h4>
          <ul>
            <li><strong>Languages:</strong> C++, Python, SQL, Bash/Shell</li>
            <li><strong>AI/ML:</strong> PyTorch, TensorFlow, Llama.cpp, Hugging Face Transformers, Quantization (GGUF, GPTQ), RAG Pipelines, NLP, Computer Vision</li>
            <li><strong>Web/Tools:</strong> React, Node.js, Next.js, Git, Docker, Linux (Fedora/Ubuntu), VS Code, AWS/GCP Basics</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ═══════════════════════════════════ RESEARCH ════════════════════════════════ -->
<section class="section section-alt" id="research">
  <div class="container">
    <div class="section-label">02 — Research & Publications</div>
    <h2>Publications</h2>

    <!-- ── PUBLICATION 1 — edit fields below ── -->
    <article class="pub-card">
      <div class="pub-meta">
        <span class="pub-badge pub-badge--preprint">Preprint</span>
        <span class="pub-year">2024</span>
      </div>
      <h3 class="pub-title">
        Defying the Precision Tax: Scalable Sequential Editing in 4-bit Quantized LLMs
      </h3>
      <p class="pub-authors">
        <strong>Kabir Potdar</strong>, Co-author Name, Co-author Name
      </p>
      <p class="pub-venue">arXiv preprint</p>
      <p class="pub-abstract">
        Research on scalable methods for editing knowledge in 4-bit quantized large language models,
        addressing the precision-accuracy tradeoffs in efficient LLM deployment.
      </p>
      <div class="pub-links">
        <a href="#" class="pub-link">arXiv</a>
        <a href="#" class="pub-link">PDF</a>
        <a href="#" class="pub-link">Code</a>
      </div>
    </article>

    <!-- ── PUBLICATION 2 — Current Research -->
    <article class="pub-card">
      <div class="pub-meta">
        <span class="pub-badge">Current Research</span>
        <span class="pub-year">2024</span>
      </div>
      <h3 class="pub-title">
        The Efficiency-Accuracy Pareto Frontier: Evaluating 1-bit Quantization Viability in Sub-3B Parameter Models on Mobile Edge Devices
      </h3>
      <p class="pub-authors">
        <strong>Kabir Potdar</strong>
      </p>
      <p class="pub-venue">In Progress</p>
      <p class="pub-abstract">
        Benchmarking Llama-3.2 and SmolLM2 on ARM architectures to evaluate the viability of
        1-bit quantization for mobile edge deployment, exploring the efficiency-accuracy tradeoff.
      </p>
    </article>

    <!-- ── PUBLICATION 3 — Journal Paper -->
    <article class="pub-card">
      <div class="pub-meta">
        <span class="pub-badge pub-badge--journal">Journal</span>
        <span class="pub-year">2024</span>
      </div>
      <h3 class="pub-title">
        Evaluating the Impact of Precipitation, Temperature, and Topological Factors on Flood Severity in Myanmar
      </h3>
      <p class="pub-authors">
        <strong>Kabir Potdar</strong>, Co-author Name
      </p>
      <p class="pub-venue">IJRASET, DOI: 10.22214/ijraset.2024.64932</p>
      <p class="pub-abstract">
        Analyzing the correlation between meteorological and geographical factors and flood severity
        in Myanmar using machine learning approaches.
      </p>
      <div class="pub-links">
        <a href="https://doi.org/10.22214/ijraset.2024.64932" target="_blank" rel="noopener" class="pub-link">DOI</a>
      </div>
    </article>

    <div class="scholar-link-wrap">
      <a href="https://scholar.google.com/citations?user=i1GvrigAAAAJ&hl=en" target="_blank" rel="noopener" class="btn btn-secondary">
        View all on Google Scholar →
      </a>
    </div>
  </div>
</section>

<!-- ═══════════════════════════════════ PROJECTS ════════════════════════════════ -->
<section class="section" id="projects">
  <div class="container">
    <div class="section-label">03 — Projects</div>
    <h2>Selected Projects</h2>
    <p class="section-intro">
      A selection of research prototypes, open-source tools, and engineering projects.
    </p>
    <div class="projects-grid">

      <!-- ── PROJECT CARD — duplicate this block to add more ── -->
      <div class="project-card">
        <div class="project-header">
          <span class="project-tag">Algorithm Optimization</span>
          <div class="project-icon-links">
            <a href="https://github.com/Kabir08" target="_blank" rel="noopener" aria-label="GitHub repo">{% include icons/github.html %}</a>
          </div>
        </div>
        <h3>Google Code Golf (Kaggle)</h3>
        <p>
          Achieved a top 17% global ranking (194/1142) by optimizing Python/C++ code for extreme
          brevity and algorithmic efficiency. Solved complex algorithmic challenges under strict
          character-count constraints, demonstrating mastery of low-level optimization.
        </p>
        <div class="project-tech">
          <span>Python</span>
          <span>C++</span>
          <span>Algorithms</span>
          <span>Optimization</span>
        </div>
      </div>
      <!-- ── end project card ── -->

      <!-- ── PROJECT CARD 2 — NLP Project -->
      <div class="project-card">
        <div class="project-header">
          <span class="project-tag">NLP & Deep Learning</span>
          <div class="project-icon-links">
            <a href="https://github.com/Kabir08" target="_blank" rel="noopener" aria-label="GitHub repo">{% include icons/github.html %}</a>
          </div>
        </div>
        <h3>Quora Insincere Questions Classification</h3>
        <p>
          Developed a text classification model to detect toxic content on Quora, handling a dataset
          of 1.3M+ questions. Implemented GloVe embeddings and LSTM networks, achieving an F1-score
          of 0.68 on a highly imbalanced dataset.
        </p>
        <div class="project-tech">
          <span>Python</span>
          <span>PyTorch</span>
          <span>NLP</span>
          <span>LSTM</span>
          <span>GloVe</span>
        </div>
      </div>

      <!-- ── PROJECT CARD 3 — RAG System -->
      <div class="project-card">
        <div class="project-header">
          <span class="project-tag">LLM Engineering</span>
          <div class="project-icon-links">
            <a href="https://github.com/Kabir08" target="_blank" rel="noopener" aria-label="GitHub repo">{% include icons/github.html %}</a>
          </div>
        </div>
        <h3>RAG Pipeline for HR Automation</h3>
        <p>
          Architected a Retrieval-Augmented Generation pipeline for HR automation at Asanify Technologies.
          Reduced query response latency by 35% and automated 80% of Level-1 employee support tickets
          using quantized LLMs.
        </p>
        <div class="project-tech">
          <span>Python</span>
          <span>LangChain</span>
          <span>Hugging Face</span>
          <span>Quantized LLMs</span>
          <span>RAG</span>
        </div>
      </div>

      <!-- ── PROJECT CARD 4 -->
      <div class="project-card">
        <div class="project-header">
          <span class="project-tag">MLOps</span>
          <div class="project-icon-links">
            <a href="https://github.com/Kabir08" target="_blank" rel="noopener" aria-label="GitHub repo">{% include icons/github.html %}</a>
          </div>
        </div>
        <h3>Predictive Model Deployment</h3>
        <p>
          Built and deployed predictive models processing 50,000+ records at Source Code Technologies,
          improving data classification accuracy by 15%. Containerized ML models using Docker for
          cloud deployment, ensuring 99.9% system uptime.
        </p>
        <div class="project-tech">
          <span>Python</span>
          <span>TensorFlow</span>
          <span>Docker</span>
          <span>AWS</span>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- ═══════════════════════════════════ EXPERIENCE ══════════════════════════════════ -->
<section class="section" id="experience">
  <div class="container">
    <div class="section-label">04 — Experience</div>
    <h2>Work Experience</h2>
    <div class="timeline">

      <!-- ── EXPERIENCE 1 -->
      <div class="timeline-item">
        <div class="timeline-date">Jan 2025 – Aug 2025</div>
        <div class="timeline-content">
          <h3>AI Engineering Intern</h3>
          <p class="timeline-company">Asanify Technologies, Pune, India</p>
          <ul>
            <li>Architected a RAG (Retrieval-Augmented Generation) pipeline for HR automation, reducing query response latency by 35%</li>
            <li>Automated 80% of Level-1 employee support tickets using quantized LLMs</li>
            <li>Optimized inference costs by implementing token-caching strategies, resulting in 20% reduction in API usage overhead</li>
          </ul>
        </div>
      </div>

      <!-- ── EXPERIENCE 2 -->
      <div class="timeline-item">
        <div class="timeline-date">Aug 2023 – July 2024</div>
        <div class="timeline-content">
          <h3>Machine Learning Intern</h3>
          <p class="timeline-company">Source Code Technologies Pvt Ltd, Pune, India</p>
          <ul>
            <li>Built and deployed predictive models processing 50,000+ records, improving data classification accuracy by 15%</li>
            <li>Automated data preprocessing pipelines using Python (Pandas/NumPy), reducing manual data cleaning time by 10+ hours per week</li>
            <li>Containerized ML models using Docker for cloud deployment, ensuring 99.9% system uptime during client demos</li>
          </ul>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- ═══════════════════════════════════ CERTIFICATIONS & ACHIEVEMENTS ══════════════════════════════════ -->
<section class="section section-alt" id="certifications">
  <div class="container">
    <div class="section-label">05 — Certifications & Achievements</div>
    <h2>Certifications</h2>
    <div class="cert-grid">
      <div class="cert-card">
        <h3>Walmart Global Tech</h3>
        <p>Advanced Software Engineering Job Simulation</p>
        <span class="cert-date">Jan 2024 – June 2024</span>
      </div>
      <div class="cert-card">
        <h3>J.P. Morgan</h3>
        <p>Software Engineering Job Simulation</p>
        <span class="cert-date">June 2024</span>
      </div>
      <div class="cert-card">
        <h3>Kaggle</h3>
        <p>Intro to AI Ethics</p>
        <span class="cert-date">July 2024 – Aug 2024</span>
      </div>
    </div>

    <h2>Competitive Programming Achievements</h2>
    <div class="achievements-list">
      <div class="achievement-item">
        <span class="achievement-icon">🏆</span>
        <div>
          <strong>LeetCode</strong>
          <p>Rating: 1568 (Top 28.89% worldwide)</p>
        </div>
      </div>
      <div class="achievement-item">
        <span class="achievement-icon">🏆</span>
        <div>
          <strong>Meta Hacker Cup</strong>
          <p>Ranked 6976th among 20k+ participants</p>
        </div>
      </div>
      <div class="achievement-item">
        <span class="achievement-icon">🏆</span>
        <div>
          <strong>Google Code Golf</strong>
          <p>Ranked 194 out of 1142 participants (Top 17%)</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ═══════════════════════════════════ CONTACT ═════════════════════════════════ -->
<section class="section section-alt" id="contact">
  <div class="container contact-container">
    <div class="section-label">06 — Contact</div>
    <h2>Let's talk.</h2>
    <p class="contact-intro">
      I'm open to research collaborations, PhD discussions, industry roles in AI/ML,
      and conversations about efficient inference. Reach out via email or any of the links below.
    </p>
    <a href="mailto:kabirpotdar7@gmail.com" class="contact-email">kabirpotdar7@gmail.com</a>
    <div class="contact-socials">
      <a href="https://github.com/Kabir08" target="_blank" rel="noopener">
        {% include icons/github.html %} GitHub
      </a>
      <a href="https://linkedin.com/in/kabir-potdar" target="_blank" rel="noopener">
        {% include icons/linkedin.html %} LinkedIn
      </a>
      <a href="https://scholar.google.com/citations?user=i1GvrigAAAAJ&hl=en" target="_blank" rel="noopener">
        {% include icons/scholar.html %} Google Scholar
      </a>
      <a href="https://x.com/potdarkabirr" target="_blank" rel="noopener">
        {% include icons/x.html %} @potdarkabirr
      </a>
    </div>
  </div>
</section>
