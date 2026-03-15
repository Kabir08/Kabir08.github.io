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
            <span>India · 2024</span>
          </p>
          <!-- Add MSc once confirmed: -->
          <!-- <p class="edu-item">
            <strong>MSc Artificial Intelligence</strong><br/>
            <span>University · Year</span>
          </p> -->
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
        <span class="pub-year">2024</span>  <!-- ← change year -->
      </div>
      <h3 class="pub-title">
        <!-- ← paste your paper title here -->
        Your Paper Title Here
      </h3>
      <p class="pub-authors">
        <!-- ← list authors, bold your name -->
        <strong>Kabir Potdar</strong>, Co-author Name, Co-author Name
      </p>
      <p class="pub-venue">arXiv preprint</p>  <!-- ← venue / conference -->
      <p class="pub-abstract">
        <!-- ← one or two sentences describing the paper -->
        Brief abstract or summary of the paper's contribution and key findings.
        Replace this with your actual abstract excerpt.
      </p>
      <div class="pub-links">
        <a href="#" class="pub-link">arXiv</a>  <!-- ← replace # with arXiv URL -->
        <a href="#" class="pub-link">PDF</a>
        <!-- <a href="#" class="pub-link">Code</a> -->
        <!-- <a href="#" class="pub-link">Cite</a> -->
      </div>
    </article>

    <!-- ── Add more publications by duplicating the block above ── -->

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
          <span class="project-tag"><!-- e.g. LLM Efficiency --></span>
          <div class="project-icon-links">
            <a href="#" target="_blank" rel="noopener" aria-label="GitHub repo">{% include icons/github.html %}</a>
            <!-- <a href="#" target="_blank" rel="noopener" aria-label="Demo">↗</a> -->
          </div>
        </div>
        <h3>Project Name</h3>  <!-- ← project title -->
        <p>
          <!-- ← short description (2-3 sentences) -->
          Brief description of what this project does, the problem it solves,
          and any key results or impact.
        </p>
        <div class="project-tech">
          <span>Python</span>  <!-- ← tech tags -->
          <span>PyTorch</span>
          <span><!-- add more --></span>
        </div>
      </div>
      <!-- ── end project card ── -->

      <!-- ── PROJECT CARD 2 ── -->
      <div class="project-card">
        <div class="project-header">
          <span class="project-tag"></span>
          <div class="project-icon-links">
            <a href="#" target="_blank" rel="noopener" aria-label="GitHub repo">{% include icons/github.html %}</a>
          </div>
        </div>
        <h3>Project Name</h3>
        <p>Brief description of this project.</p>
        <div class="project-tech">
          <span>Python</span>
          <span></span>
        </div>
      </div>

      <!-- ── PROJECT CARD 3 ── -->
      <div class="project-card">
        <div class="project-header">
          <span class="project-tag"></span>
          <div class="project-icon-links">
            <a href="#" target="_blank" rel="noopener" aria-label="GitHub repo">{% include icons/github.html %}</a>
          </div>
        </div>
        <h3>Project Name</h3>
        <p>Brief description of this project.</p>
        <div class="project-tech">
          <span></span>
        </div>
      </div>

      <!-- ── PROJECT CARD 4 ── -->
      <div class="project-card">
        <div class="project-header">
          <span class="project-tag"></span>
          <div class="project-icon-links">
            <a href="#" target="_blank" rel="noopener" aria-label="GitHub repo">{% include icons/github.html %}</a>
          </div>
        </div>
        <h3>Project Name</h3>
        <p>Brief description of this project.</p>
        <div class="project-tech">
          <span></span>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- ═══════════════════════════════════ CONTACT ═════════════════════════════════ -->
<section class="section section-alt" id="contact">
  <div class="container contact-container">
    <div class="section-label">04 — Contact</div>
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
