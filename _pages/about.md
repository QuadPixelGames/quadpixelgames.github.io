---
permalink: /about/
title: "About QuadPixel"
author_profile: false
---

<style>
  .qpg-about-hero {
    position: relative;
    background: radial-gradient(circle at 70% 30%, rgba(0,255,136,0.07), transparent 60%),
                radial-gradient(circle at 20% 80%, rgba(124,77,255,0.05), transparent 60%),
                #0e1017;
    border: 1px solid rgba(255,255,255,0.06);
    border-radius: 24px;
    padding: 3rem 2rem;
    margin-bottom: 2.5rem;
    overflow: hidden;
  }
  .qpg-about-hero::before {
    content: "";
    position: absolute;
    inset: 0;
    background-image:
      linear-gradient(rgba(255,255,255,0.012) 1px, transparent 1px),
      linear-gradient(90deg, rgba(255,255,255,0.012) 1px, transparent 1px);
    background-size: 40px 40px;
    mask-image: radial-gradient(ellipse 80% 80% at 50% 50%, white, transparent);
    pointer-events: none;
  }
  .qpg-about-hero h1 {
    font-size: 3rem !important;
    font-weight: 800 !important;
    margin: 0 0 1rem 0 !important;
    background: linear-gradient(135deg, #fff 30%, #a0f0c0 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    letter-spacing: -0.04em;
    line-height: 1.1;
  }
  .qpg-about-hero p {
    font-size: 1.05rem;
    color: rgba(255,255,255,0.72);
    line-height: 1.7;
    max-width: 640px;
    margin: 0;
  }
  .qpg-badge-row {
    display: flex;
    gap: 0.6rem;
    flex-wrap: wrap;
    margin-bottom: 1.5rem;
  }
  .qpg-badge {
    display: inline-block;
    font-size: 0.7rem;
    font-weight: 700;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    padding: 4px 12px;
    border-radius: 100px;
    border: 1px solid rgba(0,255,136,0.25);
    background: rgba(0,255,136,0.08);
    color: #00ff88;
  }
  .qpg-about-cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 1.5rem;
    margin-bottom: 2.5rem;
  }
  .qpg-about-card {
    background: rgba(255,255,255,0.02);
    border: 1px solid rgba(255,255,255,0.06);
    border-radius: 18px;
    padding: 1.6rem;
    transition: all 0.25s ease;
  }
  .qpg-about-card:hover {
    background: rgba(255,255,255,0.04);
    border-color: rgba(255,255,255,0.12);
    transform: translateY(-3px);
  }
  .qpg-about-card-icon {
    font-size: 2rem;
    margin-bottom: 0.75rem;
  }
  .qpg-about-card h3 {
    margin: 0 0 0.5rem 0 !important;
    font-size: 1rem !important;
    color: #fff;
    font-weight: 700;
  }
  .qpg-about-card p {
    margin: 0 !important;
    font-size: 0.875rem;
    color: rgba(255,255,255,0.58);
    line-height: 1.6;
  }
  .qpg-joke-block {
    border-left: 3px solid #00ff88;
    background: rgba(0,255,136,0.05);
    border-radius: 0 14px 14px 0;
    padding: 1.2rem 1.6rem;
    margin: 2rem 0;
    font-size: 0.95rem;
    color: rgba(255,255,255,0.8);
    line-height: 1.6;
  }
  .qpg-joke-block strong {
    color: #00ff88;
    font-size: 1.3rem;
    letter-spacing: 0.1em;
  }
  .qpg-joke-block .qpg-joke-note {
    font-size: 0.8rem;
    color: rgba(255,255,255,0.4);
    margin-top: 0.4rem;
    font-style: italic;
  }
</style>

<div class="qpg-about-hero">
  <div class="qpg-badge-row">
    <span class="qpg-badge">👾 Indie Studio</span>
    <span class="qpg-badge">🎮 Est. 2024</span>
    <span class="qpg-badge">✨ Zero Chill</span>
  </div>
  <h1>About QuadPixel</h1>
  <p>
    QuadPixel is a tiny but mighty indie game studio focused on making chaotic, weird, and wildly fun games that don't take themselves too seriously — and neither do we.
    We're all about ideas that make people go <em>"wait, what?"</em> and then <em>"okay that was actually fun."</em>
    Whether it's a gun that shoots beach balls, faceless blobs jumping through portals, or Kartik flapping through pipes —
    if it makes us laugh or rage-quit, it probably belongs in a QuadPixel game.
  </p>
</div>

<div class="qpg-about-cards">
  <div class="qpg-about-card">
    <div class="qpg-about-card-icon">🔥</div>
    <h3>What we make</h3>
    <p>Chaotic, weird, wildly fun games. No GOTY ambitions. Just dumb fun — and maybe a few broken rules.</p>
  </div>
  <div class="qpg-about-card">
    <div class="qpg-about-card-icon">🛠️</div>
    <h3>How we build</h3>
    <p>Small team, big ideas, questionable deadlines. Unity for the heavy lifting, pure chaos for everything else.</p>
  </div>
  <div class="qpg-about-card">
    <div class="qpg-about-card-icon">🎯</div>
    <h3>Why we exist</h3>
    <p>Because making dumb fun is a valid life choice. If it makes us rage-quit, it's ready to ship.</p>
  </div>
</div>

<div class="qpg-joke-block">
  <strong>6️⃣7️⃣</strong>
  <p style="margin:0.4rem 0 0 0;">Our secret stat. Not a score, not a level — just the vibe. If you know, you know. If you don't, it doesn't mean anything. That's literally the whole bit.</p>
  <div class="qpg-joke-note">Powered by peak brainrot™ and LaMelo Ball's height.</div>
</div>

We're not here to win GOTY. We're here to make dumb fun — and maybe break a few rules while we're at it.

**Come play.** 🕹️
