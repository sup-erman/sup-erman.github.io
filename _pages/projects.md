---
layout: page
title: team
permalink: /team/
description: PhD students and current supervision topics.
nav: true
nav_order: 2
---

<style>
  .team-page {
    display: grid;
    gap: 1.5rem;
    margin-top: 1.5rem;
  }

  .team-note {
    color: #555;
    font-size: 0.95rem;
    margin-bottom: 0.5rem;
  }

  .team-member {
    display: grid;
    grid-template-columns: 140px minmax(0, 1fr);
    gap: 1.25rem;
    align-items: start;
    padding: 1.25rem;
    border: 1px solid rgba(0, 0, 0, 0.08);
    border-radius: 18px;
    background: rgba(250, 250, 250, 0.85);
  }

  .team-photo,
  .team-placeholder {
    width: 140px;
    height: 140px;
    border-radius: 18px;
    object-fit: cover;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
  }

  .team-placeholder {
    display: flex;
    align-items: center;
    justify-content: center;
    background: linear-gradient(135deg, #dde7f4, #f4efe4);
    color: #334;
    font-size: 2rem;
    font-weight: 700;
    letter-spacing: 0.04em;
  }

  .team-member h3 {
    margin: 0 0 0.35rem;
    font-size: 1.35rem;
  }

  .team-member h3 a {
    color: inherit;
    text-decoration: none;
    border-bottom: 1px solid rgba(0, 0, 0, 0.2);
  }

  .team-member h3 a:hover {
    border-bottom-color: currentColor;
  }

  .team-thesis {
    margin: 0 0 0.5rem;
    font-size: 1.03rem;
    font-weight: 600;
  }

  .team-meta {
    margin: 0;
    color: #444;
    line-height: 1.55;
  }

  .team-meta strong {
    color: #222;
  }

  @media (max-width: 720px) {
    .team-member {
      grid-template-columns: 1fr;
    }

    .team-photo,
    .team-placeholder {
      width: 120px;
      height: 120px;
    }
  }
</style>

<div class="team-note">
  Current PhD students, listed alphabetically by first name. Thesis titles are working titles, estimated from current publications where needed.
</div>

<div class="team-page">
  <section class="team-member">
    <div class="team-placeholder" aria-label="Adia Lumadjeng">AL</div>
    <div>
      <h3><a href="https://www.uva.nl/profiel/l/u/a.c.lumadjeng/a.c.lumadjeng.html">Adia Lumadjeng</a></h3>
      <p class="team-thesis">Explainable Classification via Signomial Equation Learning</p>
      <p class="team-meta"><strong>Co-supervised with:</strong> Ilker Birbil</p>
      <p class="team-meta"><strong>Focus:</strong> interpretable machine learning, symbolic regression, explainable classification</p>
    </div>
  </section>

  <section class="team-member">
    <img class="team-photo" src="/assets/img/andreas.png" alt="Andreas Sauter">
    <div>
      <h3><a href="https://sauter.at/">Andreas Sauter</a></h3>
      <p class="team-thesis">Causal Reinforcement Learning and Discovery</p>
      <p class="team-meta"><strong>Co-supervised with:</strong> Frank van Harmelen, Aske Plaat</p>
      <p class="team-meta"><strong>Focus:</strong> causality, reinforcement learning, neuro-symbolic AI</p>
    </div>
  </section>

  <section class="team-member">
    <img class="team-photo" src="https://www.illc.uva.nl/thumbnails/person/Sprang.jpg.jpg?size=person" alt="Angela van Sprang">
    <div>
      <h3><a href="https://www.illc.uva.nl/People/PhDstudents/person/5626/Angela-van-Sprang">Angela van Sprang</a></h3>
      <p class="team-thesis">Interpretable Time Series Transformers</p>
      <p class="team-meta"><strong>Co-supervised with:</strong> Jelle Zuidema</p>
      <p class="team-meta"><strong>Focus:</strong> concept bottlenecks, transformer interpretability, multimodal consistency</p>
    </div>
  </section>

  <section class="team-member">
    <div class="team-placeholder" aria-label="Arco van Breda">AB</div>
    <div>
      <h3>Arco van Breda</h3>
      <p class="team-thesis">Mechanistic Control for Tabular Transformers</p>
      <p class="team-meta"><strong>Co-supervised with:</strong> Saba Amiri, Ana Oprescu</p>
      <p class="team-meta"><strong>Focus:</strong> symbolic regression, transformers, interpretability</p>
    </div>
  </section>

  <section class="team-member">
    <img class="team-photo" src="https://research.vu.nl/files-asset/436953126/Vrije_stijl_a89aypxk-min.jpg?f=jpg&w=160" alt="Johannes Bendler">
    <div>
      <h3><a href="https://research.vu.nl/en/persons/johannes-bendler/">Johannes Bendler</a></h3>
      <p class="team-thesis">Language Technologies for Conversational Assessment</p>
      <p class="team-meta"><strong>Co-supervised with:</strong> Frank van Harmelen</p>
      <p class="team-meta"><strong>Focus:</strong> large language models, educational assessment, conversational AI</p>
    </div>
  </section>

  <section class="team-member">
    <div class="team-placeholder" aria-label="Mayesha Tasnim">MT</div>
    <div>
      <h3>Mayesha Tasnim</h3>
      <p class="team-thesis">Multi-Agent Learning for Fair and Transparent School Choice</p>
      <p class="team-meta"><strong>Co-supervised with:</strong> Sennay Ghebreab</p>
      <p class="team-meta"><strong>Focus:</strong> civic AI, matching mechanisms, strategic behavior, responsible AI</p>
    </div>
  </section>

  <section class="team-member">
    <img class="team-photo" src="/assets/img/wozny.png" alt="Philip Wozny">
    <div>
      <h3><a href="https://www.tilburguniversity.edu/staff/p-j-wozny?lan=en&amp;x=0">Philip Wozny</a></h3>
      <p class="team-thesis">Multi-Agent Reinforcement Learning for Equitable and Sustainable Tax Policy Design</p>
      <p class="team-meta"><strong>Co-supervised with:</strong> Albert Bomer</p>
      <p class="team-meta"><strong>Focus:</strong> multi-agent systems, reinforcement learning, taxation, climate policy</p>
    </div>
  </section>

  <section class="team-member">
    <div class="team-placeholder" aria-label="Raj Bhalwankar">RB</div>
    <div>
      <h3>Raj Bhalwankar</h3>
      <p class="team-thesis">Reasoning in Tabular Foundation Models</p>
      <p class="team-meta"><strong>Co-supervised with:</strong> Pasquale Minervini (University of Edinburgh)</p>
      <p class="team-meta"><strong>Focus:</strong> tabular foundation models, reasoning, representation learning</p>
    </div>
  </section>

  <section class="team-member">
    <img class="team-photo" src="https://www.hybrid-intelligence-centre.nl/wp-content/uploads/2025/09/satchit_chatterji_profile.png" alt="Satchit Chatterji">
    <div>
      <h3><a href="https://www.hybrid-intelligence-centre.nl/who-is-who/satchit-chatterji/">Satchit Chatterji</a></h3>
      <p class="team-thesis">Neurosymbolic AI for Safety and Norms in Multi-Agent Reinforcement Learning</p>
      <p class="team-meta"><strong>Co-supervised with:</strong> Shihan Wang, Giovanni Sileno</p>
      <p class="team-meta"><strong>Focus:</strong> logic, AI safety, game theory, multi-agent reinforcement learning</p>
    </div>
  </section>
</div>
