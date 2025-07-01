---
layout: landing
title: CV
permalink: /cv/
nav_order: 2
---

<!-- Page-scoped CSS to blow out the Minima wrapper and let the iframe fill the screen -->
<style>
  /* make the outer wrapper full-bleed */
  .wrapper, 
  .content-wrapper {
    max-width: 100% !important;
    padding: 0 !important;
  }
  /* make the main area fill the viewport minus the header */
  iframe {
    width: 100vw !important;
    height: calc(100vh - 70px) !important;  /* adjust 70px if your header is taller/shorter */
    border: none !important;
    margin: 0 !important;
  }
</style>

<iframe
  src="{{ '/assets/pdf/Pradyot_Sharma_CV.pdf' | relative_url }}"
  allowfullscreen>
  This browser does not support iframes.  
  <a href="{{ '/assets/pdf/Pradyot_Sharma_CV.pdf' | relative_url }}">Download the PDF instead.</a>
</iframe>

