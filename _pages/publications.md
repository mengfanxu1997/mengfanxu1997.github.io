---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

<h2>Publications</h2>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[keywords~=publication] %}

</div>
