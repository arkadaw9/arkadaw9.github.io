---
layout: page
permalink: /publications/
title: Publications
description: For an updated list please visit <a href='https://scholar.google.com/citations?user=pz2Nm8AAAAAJ&hl=en'>Google Scholar</a>. * denotes equal contribution.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h4><b>Conference and Journal Publications</b></h4>
{% bibliography -f papers -q @*[category=Conference Publications] %}



<h4><b>Preprints</b></h4>
{% bibliography -f papers -q @*[category=Preprints] %}



<h4><b>Workshop Papers</b></h4>
{% bibliography -f papers -q @*[category=Workshop Papers] %}

</div>
