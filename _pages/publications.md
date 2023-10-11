---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 1
---
## **Journal Articles**
<div class="publications">
{% bibliography --file journals %}
</div>
---
## **Peer-Reviewed CS Conferences**
<div class="publications">
{% bibliography -f {{ site.scholar.bibliography }} %}
</div>
---
## **Reviews**
<div class="publications">
{% bibliography --file reviews %}
</div>
---
## **Preprints**
<div class="publications">
{% bibliography --file preprints %}
</div>