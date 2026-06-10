---
layout: page
permalink: /publications/
title: publications
description: Peer-reviewed publications, manuscripts under review, and preregistrations, in reverse chronological order. An asterisk (*) denotes shared first authorship.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography-section-title">Peer-reviewed publications</h2>

{% bibliography %}

<h2 class="bibliography-section-title">Manuscripts under review</h2>

{% bibliography -f under_review %}

<h2 class="bibliography-section-title">Preregistrations</h2>

{% bibliography -f preregistrations %}

</div>
