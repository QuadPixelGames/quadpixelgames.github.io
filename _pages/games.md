---
layout: single
title: "🎮 Games"
permalink: /games/
author_profile: false
classes: wide
---

<style>
  .qpg-games-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 1.5rem;
    margin-top: 1.5rem;
  }

  .qpg-card {
    border: 1px solid rgba(255,255,255,0.1);
    border-radius: 14px;
    overflow: hidden;
    background: rgba(255,255,255,0.04);
    display: flex;
    flex-direction: column;
    transition: transform 0.2s, box-shadow 0.2s;
  }
  .qpg-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 8px 30px rgba(0,0,0,0.4);
  }

  .qpg-card__banner {
    height: 130px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 3.5rem;
    position: relative;
    overflow: hidden;
  }
  .qpg-card__banner--flappy  { background: linear-gradient(135deg, #1a1a2e 0%, #16213e 50%, #0f3460 100%); }
  .qpg-card__banner--blaster { background: linear-gradient(135deg, #1a0a2e 0%, #2d1b4e 50%, #4a1080 100%); }
  .qpg-card__banner--smoorpples { background: linear-gradient(135deg, #0a1f1a 0%, #0d3320 50%, #0f5030 100%); }

  .qpg-card__badge {
    position: absolute;
    top: 10px;
    right: 10px;
    font-size: 0.65rem;
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    padding: 3px 8px;
    border-radius: 20px;
  }
  .qpg-card__badge--live {
    background: rgba(0, 200, 120, 0.2);
    border: 1px solid #00c878;
    color: #a0f0c0;
  }
  .qpg-card__badge--soon {
    background: rgba(255, 200, 50, 0.15);
    border: 1px solid rgba(255, 200, 50, 0.5);
    color: #ffd970;
  }

  .qpg-card__body {
    padding: 1.1rem 1.2rem 1.3rem;
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
    flex: 1;
  }

  .qpg-card__title {
    font-size: 1.1rem;
    font-weight: 700;
    margin: 0;
  }

  .qpg-card__desc {
    font-size: 0.85rem;
    opacity: 0.7;
    line-height: 1.5;
    margin: 0;
    flex: 1;
  }

  .qpg-card__footer {
    margin-top: 0.9rem;
  }

  .qpg-card__btn {
    display: inline-flex;
    align-items: center;
    gap: 0.4rem;
    padding: 0.4rem 1rem;
    border-radius: 8px;
    font-size: 0.82rem;
    font-weight: 700;
    text-decoration: none !important;
    transition: opacity 0.15s, transform 0.15s;
  }
  .qpg-card__btn:hover { opacity: 0.85; transform: translateY(-1px); }

  .qpg-card__btn--itch {
    background: linear-gradient(135deg, #fa5c5c, #e84848);
    color: #fff !important;
  }
  .qpg-card__btn--disabled {
    background: rgba(255,255,255,0.08);
    border: 1px solid rgba(255,255,255,0.15);
    color: rgba(255,255,255,0.4) !important;
    cursor: not-allowed;
    pointer-events: none;
  }
</style>

<div class="qpg-games-grid">

  <!-- Flappy Kartik -->
  <div class="qpg-card">
    <div class="qpg-card__banner qpg-card__banner--flappy">
      🐦
      <span class="qpg-card__badge qpg-card__badge--live">● Live on itch.io</span>
    </div>
    <div class="qpg-card__body">
      <div class="qpg-card__title">Flappy Kartik</div>
      <p class="qpg-card__desc">He didn't ask for this. A Flappy Bird tribute starring our very own Kartik — dodge the pipes, question your life choices.</p>
      <div class="qpg-card__footer">
        <a href="https://aatiksh.itch.io/flappy-kartik" target="_blank" rel="noopener" class="qpg-card__btn qpg-card__btn--itch">
          <svg width="13" height="13" viewBox="0 0 245.9 220.2" fill="white" xmlns="http://www.w3.org/2000/svg"><path d="M31.1 0C19.8 6.9 0 29.6 0 34.5v9.7c0 12.2 11.4 22.9 21.7 22.9 12.4 0 22.8-10.2 22.8-22.4 0 12.2 10 22.4 22.4 22.4s22-10.2 22-22.4c0 12.2 10.4 22.4 22.8 22.4 12.4 0 22.1-10.2 22.1-22.4 0 12.2 10.4 22.4 22.8 22.4 12.4 0 22.1-10.2 22.1-22.4 0 12.2 10.4 22.4 22.8 22.4 12.4 0 22.8-10.8 22.8-22.9v-9.7C223.3 29.6 204 6.9 192.5 0H31.1zm-4.8 79.3c-4.1 0-8 .5-11.6 1.4C6 83.9 0 95.5 0 107.1V192c0 15.5 25.8 28.2 57.6 28.2h108.4c31.8 0 57.6-12.6 57.6-28.2v-84.9c0-11.6-6-23.2-14.7-26.4-3.6-.9-7.5-1.4-11.6-1.4-8.1 0-15.4 2.5-20.9 6.5v-.1c0 12.4-10.3 22.4-22.7 22.4-12.4 0-22.1-10-22.1-22.4-.1 12.4-10.4 22.4-22.8 22.4-12.4 0-22.7-10-22.7-22.4 0 12.4-10.4 22.4-22.8 22.4S43.3 98.1 43.3 85.8l-.1.1c-5.4-4.1-12.7-6.6-20.9-6.6zm40.4 48.3h83.3c8.7 0 14.5 7.8 14.5 17.4v29.1c0 8.4-5.8 17.4-14.5 17.4H66.7c-8.7 0-14.5-9-14.5-17.4V145c0-9.6 5.8-17.4 14.5-17.4z"/></svg>
          Play on itch.io
        </a>
      </div>
    </div>
  </div>

  <!-- Blaster Balls -->
  <div class="qpg-card">
    <div class="qpg-card__banner qpg-card__banner--blaster">
      🎯
      <span class="qpg-card__badge qpg-card__badge--soon">⏳ Upcoming</span>
    </div>
    <div class="qpg-card__body">
      <div class="qpg-card__title">Blaster Balls</div>
      <p class="qpg-card__desc">A Unity FPS built around one idea: shoot beach balls. Chaotic. Unfinished. Absolutely ours.</p>
      <div class="qpg-card__footer">
        <span class="qpg-card__btn qpg-card__btn--disabled">Coming Soon</span>
      </div>
    </div>
  </div>

  <!-- Smoorpples -->
  <div class="qpg-card">
    <div class="qpg-card__banner qpg-card__banner--smoorpples">
      🫧
      <span class="qpg-card__badge qpg-card__badge--soon">⏳ Upcoming</span>
    </div>
    <div class="qpg-card__body">
      <div class="qpg-card__title">Smoorpples</div>
      <p class="qpg-card__desc">Faceless blobs. Portals. No reason. We're not sure what this is yet either, but it's going to be weird.</p>
      <div class="qpg-card__footer">
        <span class="qpg-card__btn qpg-card__btn--disabled">Coming Soon</span>
      </div>
    </div>
  </div>

</div>
