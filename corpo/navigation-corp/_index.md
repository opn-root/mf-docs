---
title: Навигация
order: 6
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
    <img src="https://r2.fivemanage.com/4yZaDFaKDWfxxYbNh9G4n/militechlogo.png" alt="">
    <span class="label">Militech</span>
  </a>
  <a class="card" href="https://gramax.mainframenetwork.com/mf-docs/corpo/navigation/Arasaka" target="_blank" rel="noopener noreferrer">
    <img src="https://r2.fivemanage.com/4yZaDFaKDWfxxYbNh9G4n/arasakalogo.png" alt="">
    <span class="label">Arasaka</span>
  </a>
  <a class="card" href="https://gramax.mainframenetwork.com/mf-docs/corpo/navigation/Dynalar" target="_blank" rel="noopener noreferrer">
    <img src="https://r2.fivemanage.com/4yZaDFaKDWfxxYbNh9G4n/dynalarlogo.png" alt="">
    <span class="label">Dynalar</span>
  </a>
  <a class="card" href="https://gramax.mainframenetwork.com/mf-docs/corpo/navigation/Microtech" target="_blank" rel="noopener noreferrer">
    <img src="https://r2.fivemanage.com/4yZaDFaKDWfxxYbNh9G4n/microtechlogo.png" alt="">
    <span class="label">Microtech</span>
  </a>
  <a class="card" href="https://gramax.mainframenetwork.com/mf-docs/corpo/navigation/Trauma-Team" target="_blank" rel="noopener noreferrer">
    <img src="https://r2.fivemanage.com/4yZaDFaKDWfxxYbNh9G4n/traumalogo.png" alt="">
    <span class="label">Trauma Team</span>
  </a>
  <a class="card" href="https://gramax.mainframenetwork.com/mf-docs/corpo/navigation/Kang-Tao" target="_blank" rel="noopener noreferrer">
    <img src="https://r2.fivemanage.com/4yZaDFaKDWfxxYbNh9G4n/kang-taologo.png" alt="">
    <span class="label">Kang Tao</span>
  </a>
</div>

[/html]