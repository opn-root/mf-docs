---
title: Навигация
order: 1
aliases:
  - path: corpo/navigation
    moved: "2026-08-27T14:28:59Z"
---

[html::839px]

<style>
  html, body {
    background: #111 !important;
    color: #e8e8e8;
    margin: 0;
    padding: 0;
  }

  @media (prefers-color-scheme: light) {
    html, body { background: #fff !important; color: #1a1a1a; }
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
    gap: 14px;
    min-height: 150px;
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
    background: rgba(128, 128, 128, 0.10);
    transform: translateY(-2px);
  }

  .card:active { transform: translateY(0); }

  .card:focus-visible {
    outline: 2px solid currentColor;
    outline-offset: 3px;
  }

  .card img {
    max-width: 110px;
    max-height: 110px;
    object-fit: contain;
  }

  .card .label {
    font-size: 13px;
    font-weight: 600;
    letter-spacing: 0.05em;
    text-transform: uppercase;
  }
</style>

<div class="grid">
  <a class="card" href="https://gramax.mainframenetwork.com/mf-docs/corpo/navigation/Militech" target="_blank" rel="noopener noreferrer">
    <img src="ssilka na fotku" alt="">
    <span class="label">Pidori</span>
  </a>
  <a class="card" href="https://gramax.mainframenetwork.com/mf-docs/corpo/navigation/Arasaka" target="_blank" rel="noopener noreferrer">
    <img src="ssilka na fotku" alt="">
    <span class="label">Mrazi</span>
  </a>
  <a class="card" href="https://gramax.mainframenetwork.com/mf-docs/corpo/navigation/Dynalar" target="_blank" rel="noopener noreferrer">
    <img src="ssilka na fotku" alt="">
    <span class="label">Shniri</span>
  </a>
  <a class="card" href="https://gramax.mainframenetwork.com/mf-docs/corpo/navigation/Micro" target="_blank" rel="noopener noreferrer">
    <img src="ssilka na fotku" alt="">
    <span class="label">Microchleniki</span>
  </a>
  <a class="card" href="https://gramax.mainframenetwork.com/mf-docs/corpo/navigation/TT" target="_blank" rel="noopener noreferrer">
    <img src="ssilka na fotku" alt="">
    <span class="label">TT v karmane</span>
  </a>
  <a class="card" href="https://gramax.mainframenetwork.com/mf-docs/corpo/navigation/KT" target="_blank" rel="noopener noreferrer">
    <img src="ssilka na fotku" alt="">
    <span class="label">Kapt za telku</span>
  </a>
</div>

[/html]