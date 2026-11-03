+++
title = "Mentions légales • CGV • Confidentialité"
description = "Mentions légales, Conditions générales de vente et Politique de confidentialité"
template = "page.html"
+++

<details class="accordion">
  <summary><h2 id="legal">Mentions légales</h2><span class="accordion-button">+</span></summary>
  <div class="accordion-content">
    {% include "partials/legal-mentions.md" %}
  </div>
</details>

<details class="accordion">
  <summary><h2 id="cgv">Conditions générales de vente</h2><span class="accordion-button">+</span></summary>
  <div class="accordion-content">
    {% include "partials/legal-cgv.md" %}
  </div>
</details>

<details class="accordion">
  <summary><h2 id="confidentialite">Politique de confidentialité</h2><span class="accordion-button">+</span></summary>
  <div class="accordion-content">
    {% include "partials/legal-confidentialité.md" %}
  </div>
</details>
