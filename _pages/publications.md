---
layout: page
permalink: /publications/
title: Publications
description: (* co-first author; underlined names are my students)
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<div class="publications">

<h3 class="pub-section">Preprints</h3>
{% bibliography --query @*[abbr~=^Pre] %}

<h3 class="pub-section">Highlighted Publications</h3>
{% bibliography --query @*[abbr!~^Pre] %}

</div>
