---
title: "People"
description: "We are otterstanding!"
hidemeta: true
---

<br><br>

<h2 class="title-accent">We are otterstanding! 💪💪</h2>


<section class="people-group">
  <h3>Alpha Otter ⭐</h3>
  <div class="people-grid">
    <figure class="person">
      <img src="meng.png" alt="Meng">
      <figcaption>Meng</figcaption>
    </figure>
    <figure class="person">
      <img src="travis.png" alt="Travis">
      <figcaption>Travis</figcaption>
    </figure>
  </div>
</section>

<section class="people-group">
  <h3>Sea Otter 🌊</h3>
  <div class="people-grid">
    <figure class="person">
      <img src="steve.png" alt="Steve">
      <figcaption>Steve</figcaption>
    </figure>
  </div>
</section>

<section class="people-group">
  <h3>River Otter 🦦</h3>
  <div class="people-grid">
    <figure class="person">
      <img src="mark.png" alt="Mark">
      <figcaption>Mark</figcaption>
    </figure>
    <figure class="person">
      <img src="wennie.png" alt="Wennie">
      <figcaption>Wennie</figcaption>
    </figure>
    <figure class="person">
      <img src="Wong.png" alt="Wong">
      <figcaption>Wong</figcaption>
    </figure>
  </div>
</section>

<section class="people-group">
  <h3>Pup Otter 🍼</h3>
  <div class="people-grid">
    <figure class="person">
      <img src="Luna.png" alt="Luna">
      <figcaption>Luna</figcaption>
    </figure>
    <figure class="person">
      <img src="Marina.png" alt="Marina">
      <figcaption>Marina</figcaption>
    </figure>
  </div>
</section>

---

<h2 class="title-accent">Waiting for you ✨</h2>

<style>
  .title-accent{
    text-align:center;
    font-size:clamp(1.8rem,5vw,2.6rem);
    font-weight:900;
    letter-spacing:.2px;
    margin:28px 0 18px;
  }
  .title-accent::after{
    content:"";
    display:block;
    width:80px; height:6px;
    margin:10px auto 0;
    border-radius:4px;
    background:var(--darkcolor,#6a7ba2); /* uses your theme color if set */
    opacity:.25;
  }
</style>

<div class="join-wrap">
  <img src="anyone.png" alt="Join Otter Tech Limited">
</div>

<style>
  /* layout */
  .people-group { padding: 1.25rem 0; }
  .people-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
    gap: 1rem;
    align-items: start;
  }

  /* cards */
  .person { margin: 0; text-align: center; }
  .person img {
    width: 140px; height: 140px;
    border-radius: 50%;
    object-fit: cover;
    display: block;
    margin: 0 auto .6rem;
    border: 1px solid #eee;
  }
  .person figcaption { font-weight: 600; }

  /* join banner */
  .join-wrap img {
    width: 100%;
    max-width: 960px;
    border-radius: 14px;
    display: block;
    border: 1px solid #eee;
  }

  /* keep anchors visible below sticky header */
  [id] { scroll-margin-top: 80px; }
</style>
