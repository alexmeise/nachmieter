---
layout: page
title: Galerie
---

Lege deine Fotos im Ordner `assets/images/` ab und ergänze sie unten.
Dateinamen können beliebig sein — passe die `src`-Pfade entsprechend an.

<div class="galerie">
  {% comment %} Ersetze die PLATZHALTER-Dateinamen durch deine echten Bilder. {% endcomment %}
  <figure>
    <img src="{{ '/assets/images/foto-1.jpg' | relative_url }}" alt="PLATZHALTER Beschreibung Foto 1">
    <figcaption>PLATZHALTER: z. B. Wohnzimmer</figcaption>
  </figure>
  <figure>
    <img src="{{ '/assets/images/foto-2.jpg' | relative_url }}" alt="PLATZHALTER Beschreibung Foto 2">
    <figcaption>PLATZHALTER: z. B. Küche</figcaption>
  </figure>
  <figure>
    <img src="{{ '/assets/images/foto-3.jpg' | relative_url }}" alt="PLATZHALTER Beschreibung Foto 3">
    <figcaption>PLATZHALTER: z. B. Schlafzimmer</figcaption>
  </figure>
  <figure>
    <img src="{{ '/assets/images/foto-4.jpg' | relative_url }}" alt="PLATZHALTER Beschreibung Foto 4">
    <figcaption>PLATZHALTER: z. B. Bad</figcaption>
  </figure>
</div>
