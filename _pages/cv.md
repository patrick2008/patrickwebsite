---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
description: 
---

<div class="text-center mb-3">
  <a
    href="{{ '/assets/rendercv/Resume.pdf' | relative_url }}"
    target="_blank"
    rel="noopener noreferrer"
    class="btn btn-outline-primary btn-sm"
  >
    <i class="fa-solid fa-file-pdf"></i> Download PDF
  </a>
</div>

<div class="embed-responsive" style="height: 100vh;">
  <iframe
    src="{{ '/assets/rendercv/Resume.pdf' | relative_url }}"
    width="100%"
    height="100%"
    style="border: 1px solid var(--global-divider-color, #ddd); border-radius: 4px;"
  >
    Your browser doesn't support embedded PDFs.
    <a href="{{ '/assets/rendercv/Resume.pdf' | relative_url }}">Download the PDF instead.</a>
  </iframe>
</div>
