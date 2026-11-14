---
permalink: /research/
title: "Research"
excerpt: "Research interests and projects"
author_profile: true
---

<div class="st-research-intro">
  <p class="st-eyebrow">RESEARCH OVERVIEW</p>
  <h2>Connecting stellar systems to black hole growth</h2>
  <p>My research explores <strong>how black holes form and grow</strong>, and what their properties reveal about the star clusters and galaxies in which they originate. I combine dynamical simulations, semi-analytic models, and population synthesis with electromagnetic and gravitational-wave observations.</p>
</div>

<div class="st-science-flow" aria-label="Research themes connecting star clusters, black holes, and galaxies">
  <div class="st-science-flow__step">
    <span class="st-science-flow__icon" aria-hidden="true">✦</span>
    <strong>Star clusters</strong>
    <span>Formation &amp; dynamics</span>
  </div>
  <div class="st-science-flow__step">
    <span class="st-science-flow__icon" aria-hidden="true">◎</span>
    <strong>Black holes</strong>
    <span>Growth &amp; mergers</span>
  </div>
  <div class="st-science-flow__step">
    <span class="st-science-flow__icon" aria-hidden="true">◌</span>
    <strong>Galaxies</strong>
    <span>Nuclear assembly</span>
  </div>
</div>

<div class="st-research-section">
  <div class="st-research-label">01 / STELLAR SYSTEMS</div>
  <h2 id="star-cluster-dynamics">Star cluster dynamics</h2>
  <p>The birth properties and dynamical evolution of star clusters strongly influence their stellar and black hole populations. I study how stellar evolution, binary interactions, and the initial structure of clusters shape their long-term evolution and observable properties.</p>
</div>

<div class="st-research-section">
  <div class="st-research-label">02 / COMPACT OBJECTS</div>
  <h2 id="black-holes-and-gravitational-waves">Black holes and gravitational waves</h2>
  <p>Dense stellar environments can produce and transform binary black holes through dynamical interactions and hierarchical mergers. I investigate their masses, spins, and merger rates, and their connection to gravitational-wave observations.</p>
</div>

<div class="st-research-section">
  <div class="st-research-label">03 / BLACK HOLE SEEDS</div>
  <h2 id="intermediate-mass-black-holes">Intermediate-mass black holes</h2>
  <p>I study whether dense stellar clusters can form intermediate-mass black holes through stellar collisions, hierarchical black hole mergers, and other growth pathways. A central question is whether these objects can contribute to massive black hole seeding.</p>
</div>

<div class="st-research-section">
  <div class="st-research-label">04 / GALAXY EVOLUTION</div>
  <h2 id="galactic-nuclei">Galactic nuclei</h2>
  <p>Star clusters can migrate toward galactic centers and contribute to the assembly of nuclear star clusters. I investigate how this migration transports black holes into galactic nuclei and influences their subsequent growth.</p>
</div>

<div class="st-feature st-research-feature" id="inspyral">
  <p class="st-eyebrow">RESEARCH SOFTWARE</p>
  <h2>inSpyral</h2>
  <p>I developed <strong>inSpyral</strong>, a population-synthesis framework coupling star cluster formation, orbital migration, and black hole evolution within galaxies. It enables population-level studies of these connected processes across cosmic time.</p>
</div>


<section class="st-research-video" aria-labelledby="galaxy-video-heading">
  <p class="st-eyebrow">MODEL VISUALIZATION</p>
  <h2 id="galaxy-video-heading">Star cluster migration to galactic nuclei</h2>
  <p>A visualization of the evolution of star clusters and black holes in a growing galaxy, produced with my dynamical and population-synthesis models.</p>
  {% assign galaxy_video = site.static_files | where: "path", "/assets/video/galaxy_evolution_web.mp4" | first %}
  {% if galaxy_video %}
  <video class="st-galaxy-video" controls preload="metadata" playsinline poster="{{ '/assets/video/galaxy_evolution_poster.jpg' | relative_url }}">
    <source src="{{ '/assets/video/galaxy_evolution_web.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support embedded videos.
  </video>
  {% else %}
  <div class="st-video-awaiting">Animation coming soon.</div>
  {% endif %}
  <p class="st-video-caption">Galaxy evolution and star cluster dynamics. Select play to watch the animation.</p>
</section>
