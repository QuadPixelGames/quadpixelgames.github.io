---
title: "Meet the Team"
permalink: /team/
layout: archive
author_profile: false
---

<style>
  .qpg-team-header {
    text-align: center;
    margin-bottom: 2.5rem;
  }
  .qpg-team-header h1 {
    font-size: 2.6rem !important;
    font-weight: 800 !important;
    background: linear-gradient(135deg, #fff 30%, #a0f0c0 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin: 0 0 0.6rem 0 !important;
    letter-spacing: -0.04em;
  }
  .qpg-team-header p {
    color: rgba(255,255,255,0.5);
    font-size: 0.95rem;
    margin: 0;
  }
  .qpg-team-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
    gap: 1.4rem;
  }
  .qpg-member {
    background: rgba(255,255,255,0.025);
    border: 1px solid rgba(255,255,255,0.07);
    border-radius: 20px;
    padding: 1.6rem 1.4rem;
    transition: all 0.25s cubic-bezier(0.16,1,0.3,1);
    position: relative;
    overflow: hidden;
  }
  .qpg-member::before {
    content: "";
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 3px;
    border-radius: 20px 20px 0 0;
    background: linear-gradient(90deg, #00ff88, #7c4dff);
    opacity: 0;
    transition: opacity 0.25s;
  }
  .qpg-member:hover {
    background: rgba(255,255,255,0.045);
    border-color: rgba(255,255,255,0.13);
    transform: translateY(-4px);
  }
  .qpg-member:hover::before {
    opacity: 1;
  }
  .qpg-member-icon {
    font-size: 2.4rem;
    margin-bottom: 0.8rem;
  }
  .qpg-member-name {
    font-size: 1.15rem;
    font-weight: 800;
    color: #fff;
    margin: 0 0 0.25rem 0;
    font-family: 'Outfit', sans-serif;
  }
  .qpg-member-role {
    display: inline-block;
    font-size: 0.68rem;
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: #00ff88;
    background: rgba(0,255,136,0.08);
    border: 1px solid rgba(0,255,136,0.2);
    border-radius: 100px;
    padding: 2px 10px;
    margin-bottom: 0.75rem;
  }
  .qpg-member-bio {
    font-size: 0.85rem;
    color: rgba(255,255,255,0.55);
    line-height: 1.55;
    margin: 0;
  }
  @media (max-width: 600px) {
    .qpg-team-grid { grid-template-columns: 1fr; }
  }
</style>

<div class="qpg-team-header">
  <h1>🎮 The QuadPixel Squad</h1>
  <p>We make chaotic games, semi-functioning features, and the occasional masterpiece.</p>
</div>

<div class="qpg-team-grid">

  <div class="qpg-member">
    <div class="qpg-member-icon">👑</div>
    <div class="qpg-member-name">Aatiksh</div>
    <span class="qpg-member-role">Founder · Developer · Editor</span>
    <p class="qpg-member-bio">Writes the code, edits the videos, manages the chaos, and still finds time to sweat in Genshin. Deadline enforcer by necessity.</p>
  </div>

  <div class="qpg-member">
    <div class="qpg-member-icon">🧪</div>
    <div class="qpg-member-name">Sarthak</div>
    <span class="qpg-member-role">Playtester · QA</span>
    <p class="qpg-member-bio">Our quality control guy. He plays, tests, and actually gives useful feedback — without breaking anything. Ever.</p>
  </div>

  <div class="qpg-member">
    <div class="qpg-member-icon">🎥</div>
    <div class="qpg-member-name">Kartik</div>
    <span class="qpg-member-role">Gamer Trio Content</span>
    <p class="qpg-member-bio">Helps power the Gamer Trio with gameplay, commentary, and general chaos. Also the star of Flappy Kartik. He didn't ask for this.</p>
  </div>

  <div class="qpg-member">
    <div class="qpg-member-icon">🎮</div>
    <div class="qpg-member-name">Shankh</div>
    <span class="qpg-member-role">Gamer Trio Content</span>
    <p class="qpg-member-bio">Part of the Gamer Trio content crew. Keeps the energy unhinged and the videos rolling. Essential chaos ingredient.</p>
  </div>

</div>
