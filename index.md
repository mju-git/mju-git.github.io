---
layout: default
title: Portfolio
---

<header class="hero">
  <p class="hero-eyebrow">Data Science &amp; Machine Learning</p>
  <h1>{{ site.title }}</h1>
  <p class="hero-lead">
    Meticulous Computer Science graduate and Data/AI Specialist with practical experience evaluating, ranking, and stress-testing LLM-generated outputs. Proven track record in RLHF annotation, multi-step web-agent evaluation (browser tool-use), and prompt engineering. Brings a technical foundation in Python and SQL to AI training projects, focusing on rubric alignment, fact-checking, safety, and search accuracy against project guidelines.
  </p>
  <div class="hero-actions">
    <a class="btn btn-primary" href="#featured">See featured work</a>
    <a class="btn btn-ghost" href="{{ "/pdf/portfolio.pdf" | relative_url }}" target="_blank" rel="noopener noreferrer">CV (PDF)</a>
    <a class="btn btn-ghost" href="{{ site.github_url }}" target="_blank" rel="noopener noreferrer">GitHub profile</a>
    {% if site.linkedin_url and site.linkedin_url != "" %}
    <a class="btn btn-ghost" href="{{ site.linkedin_url }}" target="_blank" rel="noopener noreferrer">LinkedIn</a>
    {% endif %}
  </div>
</header>

<section class="section" id="featured">
  <div class="section-header">
    <h2>Featured</h2>
    <p>Live apps you can try, plus source code on GitHub.</p>
  </div>
  <div class="project-grid">

    <article class="project-card">
      <div class="project-card-body">
        <h3>CV Builder</h3>
        <p>Interactive CV builder in React, TypeScript, and Vite — create and refine a resume in the browser.</p>
        <div class="tag-row">
          <span class="tag">React</span>
          <span class="tag">TypeScript</span>
          <span class="tag">Vite</span>
          <span class="tag">Vercel</span>
        </div>
        <div class="card-actions">
          <a class="btn btn-primary btn-sm" href="https://makemeacv.vercel.app/" target="_blank" rel="noopener noreferrer">Live</a>
          <a class="btn btn-ghost btn-sm" href="https://github.com/mju-git/cv-builder" target="_blank" rel="noopener noreferrer">Code</a>
        </div>
      </div>
    </article>

    <article class="project-card">
      <div class="project-card-body">
        <h3>Auto Compare</h3>
        <p>End-to-end car listing pipeline: scrape mobile.de, clean to Parquet, explore with filters, charts, and comparison tables in Streamlit.</p>
        <div class="tag-row">
          <span class="tag">Python</span>
          <span class="tag">Scraping</span>
          <span class="tag">Streamlit</span>
          <span class="tag">Plotly</span>
        </div>
        <div class="card-actions">
          <a class="btn btn-primary btn-sm" href="https://auto-compare.streamlit.app/" target="_blank" rel="noopener noreferrer">Live</a>
          <a class="btn btn-ghost btn-sm" href="https://github.com/mju-git/auto-compare" target="_blank" rel="noopener noreferrer">Code</a>
        </div>
      </div>
    </article>

    <article class="project-card">
      <img src="{{ "/images/recommender.png" | relative_url }}" alt="Movie and TV recommender screenshot">
      <div class="project-card-body">
        <h3>Movie &amp; TV Recommender</h3>
        <p>Content-based recommendations with TF-IDF and cosine similarity on curated metadata from IMDb and TMDB, served as a Streamlit app.</p>
        <div class="tag-row">
          <span class="tag">Python</span>
          <span class="tag">TF-IDF</span>
          <span class="tag">Streamlit</span>
          <span class="tag">TMDB</span>
        </div>
        <div class="card-actions">
          <a class="btn btn-ghost btn-sm" href="https://github.com/mju-git/movie-tv-recommender" target="_blank" rel="noopener noreferrer">Code</a>
        </div>
      </div>
    </article>

  </div>
</section>

<section class="section" id="projects">
  <div class="section-header">
    <h2>Older projects</h2>
    <p>Earlier portfolio work — notebooks and analyses on GitHub.</p>
  </div>
  <div class="project-grid">

    <article class="project-card">
      <img src="{{ "/images/audio_classifier.png" | relative_url }}" alt="Music genre classification visualization">
      <div class="project-card-body">
        <h3>Music genre classification</h3>
        <p>Classifying GTZAN audio into 10 genres. Best result: 91% accuracy with CatBoostClassifier; audio features and visuals for further deep learning.</p>
        <div class="tag-row">
          <span class="tag">Classification</span>
          <span class="tag">CatBoost</span>
          <span class="tag">Audio</span>
        </div>
        <div class="card-actions">
          <a class="btn btn-ghost btn-sm" href="https://github.com/mju-git/music-genre-classification" target="_blank" rel="noopener noreferrer">Code</a>
        </div>
      </div>
    </article>

    <article class="project-card">
      <img src="{{ "/images/digits.png" | relative_url }}" alt="MNIST handwritten digits">
      <div class="project-card-body">
        <h3>MNIST digits</h3>
        <p>Classification of 70,000 handwritten digits. Achieved 97% accuracy with KNN; next steps toward neural network models.</p>
        <div class="tag-row">
          <span class="tag">Classification</span>
          <span class="tag">KNN</span>
          <span class="tag">MNIST</span>
        </div>
        <div class="card-actions">
          <a class="btn btn-ghost btn-sm" href="https://github.com/mju-git/MNIST" target="_blank" rel="noopener noreferrer">Code</a>
        </div>
      </div>
    </article>

    <article class="project-card">
      <img src="{{ "/images/california_housing.png" | relative_url }}" alt="California housing regression chart">
      <div class="project-card-body">
        <h3>California housing prices</h3>
        <p>Random forest regressor for median house price. Lowest RMSE 46,910 with 95% CI [44,945, 48,797].</p>
        <div class="tag-row">
          <span class="tag">Regression</span>
          <span class="tag">Random Forest</span>
        </div>
        <div class="card-actions">
          <a class="btn btn-ghost btn-sm" href="https://github.com/mju-git/housing-prices" target="_blank" rel="noopener noreferrer">Code</a>
        </div>
      </div>
    </article>

    <article class="project-card">
      <img src="{{ "/images/word_cloud.png" | relative_url }}" alt="Telegram chat word cloud">
      <div class="project-card-body">
        <h3>Telegram chat analysis</h3>
        <p>EDA and visualization of a private Telegram chat with ~700,000 messages.</p>
        <div class="tag-row">
          <span class="tag">NLP</span>
          <span class="tag">EDA</span>
          <span class="tag">Visualization</span>
        </div>
        <div class="card-actions">
          <a class="btn btn-ghost btn-sm" href="https://github.com/mju-git/chat-analysis" target="_blank" rel="noopener noreferrer">Code</a>
        </div>
      </div>
    </article>

    <article class="project-card">
      <div class="project-card-body">
        <h3>Image caption generator</h3>
        <p>Generating textual descriptions of images using computer vision and NLP.</p>
        <div class="tag-row">
          <span class="tag">Deep Learning</span>
          <span class="tag">CV</span>
          <span class="tag">NLP</span>
        </div>
        <div class="card-actions">
          <a class="btn btn-ghost btn-sm" href="https://github.com/mju-git/image-caption-generator" target="_blank" rel="noopener noreferrer">Code</a>
        </div>
      </div>
    </article>

  </div>
</section>

<section class="section" id="skills">
  <div class="section-header">
    <h2>Skills</h2>
    <p>Tools used across these projects.</p>
  </div>
  <div class="skills">
    <span class="skill">Python</span>
    <span class="skill">pandas / NumPy</span>
    <span class="skill">scikit-learn</span>
    <span class="skill">Streamlit</span>
    <span class="skill">SQL</span>
    <span class="skill">R</span>
    <span class="skill">Plotly</span>
    <span class="skill">React / TypeScript</span>
    <span class="skill">Web scraping</span>
    <span class="skill">TF-IDF / NLP</span>
    <span class="skill">Git / GitHub</span>
  </div>
</section>

<section class="section" id="contact">
  <div class="section-header">
    <h2>Contact</h2>
    <p>Reach out about roles, collaborations, or questions about the projects.</p>
  </div>
  <div class="contact-panel">
    <div class="contact-meta">
      <p>Prefer email? Use the link below.</p>
      <div class="contact-links">
        <a href="{{ site.github_url }}" target="_blank" rel="noopener noreferrer">GitHub — @{{ site.github_username }}</a>
        {% if site.linkedin_url and site.linkedin_url != "" %}
        <a href="{{ site.linkedin_url }}" target="_blank" rel="noopener noreferrer">LinkedIn</a>
        {% endif %}
        {% if site.email and site.email != "" %}
        <a href="mailto:{{ site.email }}">{{ site.email }}</a>
        {% endif %}
      </div>
    </div>

    {% if site.web3forms_access_key and site.web3forms_access_key != "" %}
    <form class="contact-form" id="contact-form">
      <input type="hidden" name="access_key" value="{{ site.web3forms_access_key }}">
      <input type="hidden" name="subject" value="Portfolio contact — {{ site.title }}">
      <input type="checkbox" name="botcheck" class="honeypot" tabindex="-1" autocomplete="off">
      <label>
        Name
        <input type="text" name="name" required autocomplete="name">
      </label>
      <label>
        Email
        <input type="email" name="email" required autocomplete="email">
      </label>
      <label>
        Message
        <textarea name="message" required></textarea>
      </label>
      <button class="btn btn-primary" type="submit">Send message</button>
      <p class="form-status" id="form-status" role="status" aria-live="polite"></p>
    </form>
    {% else %}
    <p class="form-disabled-note">
      Contact form is ready once you add a free
      <a href="https://web3forms.com" target="_blank" rel="noopener noreferrer">Web3Forms</a>
      access key to <code>web3forms_access_key</code> in <code>_config.yml</code>.
      Until then, use GitHub{% if site.linkedin_url and site.linkedin_url != "" %} or LinkedIn{% endif %}{% if site.email and site.email != "" %} or email{% endif %}.
    </p>
    {% endif %}
  </div>
</section>
