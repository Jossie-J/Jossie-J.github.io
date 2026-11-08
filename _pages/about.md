---
permalink: /
homepage: true
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<section id="about" class="homepage-intro" aria-labelledby="about-title">
  <h1 id="about-title">About Me</h1>
  <p>Hi, thanks for stopping by! I’m <strong>Jiaxun (Jossie) Jiang (蒋佳迅)</strong>.</p>
  <p>I am an MSc student in <strong>Geoinformatics Engineering at Politecnico di Milano</strong> and a visiting student in <a href="https://mc2.hkust-gz.edu.cn/people">Prof. Pan Hui’s MC² Lab</a> at <strong>The Hong Kong University of Science and Technology (Guangzhou)</strong>. I received my bachelor’s degree in Computer Science and Technology from Nanning Normal University.</p>
  <p>My research brings together <strong>GeoAI, spatial data science, social computing, and urban analytics</strong>. Using spatial and social data, I study wildfire impacts, the early administrative stages of rebuilding, and the concerns people express online about environmental policies.</p>
  <p>I have finalized my master’s thesis on the 2025 Los Angeles wildfires, supervised by <a href="https://www.dica.polimi.it/en/il-dipartimento/persone/docenti/daniele.oxoli/">Prof. Daniele Oxoli</a> and co-supervised by <a href="https://panhui.people.ust.hk/">Prof. Pan Hui</a>, and plan to defend it in <strong>December 2026</strong>.</p>
</section>

<section id="research" class="homepage-section" aria-labelledby="research-title">
  <h2 id="research-title">Research &amp; Projects</h2>

  <article id="la-wildfires" class="homepage-project" aria-labelledby="la-wildfires-title">
    <figure class="homepage-project__figure">
      <a class="homepage-project__image homepage-project__image--cover" href="{{ '/images/projects/la-wildfires-nasa.jpg' | relative_url }}">
        <img src="{{ '/images/projects/la-wildfires-nasa.jpg' | relative_url }}" width="960" height="639" loading="lazy" decoding="async" alt="View the satellite image of smoke plumes from the Palisades and Eaton fires near Los Angeles">
      </a>
      <figcaption>Palisades and Eaton fires, 10 Jan 2025. <a href="https://science.nasa.gov/earth/earth-observatory/smoke-streams-from-palisades-and-eaton-fires-153813/">NASA Earth Observatory</a> image by Wanmei Liang, using MODIS data from NASA EOSDIS LANCE and GIBS/Worldview.</figcaption>
    </figure>
    <div>
      <span class="homepage-project__status homepage-project__status--ongoing">Ongoing</span>
      <h3 id="la-wildfires-title">Spatial Damage and Early Rebuilding after the 2025 Los Angeles Wildfires</h3>
      <p class="homepage-project__meta">MSc thesis finalized · Journal manuscript in preparation</p>
      <p>My MSc thesis examines residential destruction across the Eaton and Palisades fires and the timing of first recorded permit applications after the Eaton Fire. I am now aligning city and county records to identify comparable application milestones and, where the data support it, test whether models transfer between fires and help identify areas for follow-up.</p>
      <details class="homepage-project__reference">
        <summary>Full thesis title</summary>
        <p><cite>From Structure Loss to Early Rebuilding: Spatial Damage Disparities in the 2025 Los Angeles Fires and Permit Entry after the Eaton Fire</cite></p>
      </details>
    </div>
  </article>

  <article id="crop-residue-policy" class="homepage-project" aria-labelledby="crop-residue-policy-title">
    <figure class="homepage-project__figure">
      <a class="homepage-project__image" href="{{ '/images/projects/crop-residue-policy-equity.png' | relative_url }}">
        <img src="{{ '/images/projects/crop-residue-policy-equity.png' | relative_url }}" width="1200" height="1000" loading="lazy" decoding="async" alt="View the provincial map of policy equity concerns about crop-residue burning restrictions in China">
      </a>
      <figcaption>Spatial variation in policy equity concerns. Figure from the accepted manuscript.</figcaption>
    </figure>
    <div>
      <span class="homepage-project__status homepage-project__status--accepted">Accepted</span>
      <h3 id="crop-residue-policy-title">Public Concerns about Crop-Residue Burning Restrictions in China</h3>
      <p class="homepage-project__meta"><cite>Environmental Impact Assessment Review</cite> · 2026 · Second author</p>
      <p>This study examines how concerns about crop-residue burning restrictions in China vary across places. We use text and spatial analysis to study how people discuss agro-ecological risks, governance conflicts, and policy equity on online platforms.</p>
      <details class="homepage-project__reference">
        <summary>Full paper title</summary>
        <p><cite>Spatial Heterogeneity of Platform-Expressed Concerns about Environmental Policy Implementation: Evidence from China’s Crop-Residue Burning Restrictions</cite></p>
      </details>
    </div>
  </article>

  <article id="land-cover-toolbox" class="homepage-project" aria-labelledby="land-cover-toolbox-title">
    <figure class="homepage-project__figure">
      <a class="homepage-project__image" href="{{ '/images/projects/land-cover-forest-fraction.png' | relative_url }}">
        <img src="{{ '/images/projects/land-cover-forest-fraction.png' | relative_url }}" width="2424" height="1403" loading="lazy" decoding="async" alt="View the toolbox output map of mean CCI forest cover fraction around the Mediterranean from 1992 to 2022">
      </a>
      <figcaption>Mean CCI forest fraction around the Mediterranean, 1992–2022. Toolbox output.</figcaption>
    </figure>
    <div>
      <span class="homepage-project__status">Completed</span>
      <h3 id="land-cover-toolbox-title">Python Toolbox for Land-Cover Fractions and Forest Dynamics</h3>
      <p class="homepage-project__meta">With Xinchen Yu · Supervised by Daniele Oxoli</p>
      <p>We developed a Python toolbox to analyze land-cover fractions over time using CCI and GLC datasets. Its reusable modules and demonstration notebooks cover data loading, quality control, forest cover change, comparisons across datasets, regional summaries, and reproducible figures.</p>
    </div>
  </article>
</section>

<section id="news" class="homepage-section" aria-labelledby="news-title">
  <h2 id="news-title">News</h2>
  <ul class="homepage-news">
    <li>
      <span class="homepage-news__date">Upcoming · <time datetime="2026-12">Dec 2026</time></span>
      <span>MSc thesis defense planned at Politecnico di Milano.</span>
    </li>
    <li>
      <time class="homepage-news__date" datetime="2026">2026</time>
      <span>Our <a href="#crop-residue-policy">paper on platform-expressed concerns about crop-residue burning restrictions</a> was accepted by <cite>Environmental Impact Assessment Review</cite>.</span>
    </li>
  </ul>
</section>
