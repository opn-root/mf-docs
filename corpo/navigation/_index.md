---
title: навигация
order: 1
---

[view:hierarchy=none::::Table]

[html::780px]

<style>
  html, body {
    background: transparent;
    margin: 0;
    padding: 0;
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 16px;
    font-family: system-ui, -apple-system, "Segoe UI", sans-serif;
  }

  .card {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 16px;
    padding: 24px;
    border: 1px solid rgba(128, 128, 128, 0.35);
    border-radius: 10px;
    text-align: center;
    text-decoration: none;
    color: inherit;
    cursor: pointer;
    transition: border-color 0.15s ease, background-color 0.15s ease, transform 0.15s ease;
  }

  .card:hover {
    border-color: rgba(128, 128, 128, 0.8);
    background: rgba(128, 128, 128, 0.08);
    transform: translateY(-2px);
  }

  .card:active {
    transform: translateY(0);
  }

  .card:focus-visible {
    outline: 2px solid currentColor;
    outline-offset: 3px;
  }

  .card img {
    width: 100%;
    max-width: 120px;
    aspect-ratio: 1 / 1;
    object-fit: contain;
  }

  .card .label {
    font-size: 14px;
    font-weight: 600;
    letter-spacing: 0.04em;
    text-transform: uppercase;
  }
</style>

<div class="grid">
  <a class="card" href="/mf-docs/corpo/navigation/Militech" target="_top">
    <img src="ssilka na fotku" alt="Militech">
    <span class="label">Pidori</span>
  </a>
  <a class="card" href="/mf-docs/corpo/navigation/Arasaka" target="_top">
    <img src="ssilka na fotku" alt="Arasaka">
    <span class="label">Mrazi</span>
  </a>
  <a class="card" href="/mf-docs/corpo/navigation/Dynalar" target="_top">
    <img src="ssilka na fotku" alt="Dynalar">
    <span class="label">Shniri</span>
  </a>
  <a class="card" href="/mf-docs/corpo/navigation/Micro" target="_top">
    <img src="ssilka na fotku" alt="Microtech">
    <span class="label">Microchleniki</span>
  </a>
  <a class="card" href="/mf-docs/corpo/navigation/TT" target="_top">
    <img src="ssilka na fotku" alt="TT">
    <span class="label">TT v karmane</span>
  </a>
  <a class="card" href="/mf-docs/corpo/navigation/KT" target="_top">
    <img src="ssilka na fotku" alt="Kapt">
    <span class="label">Kapt za telku</span>
  </a>
</div>

[/html]