---
title: "Talks"
layout: gridlay
sitemap: false
permalink: /talks/
---

### Presentations

<div class="jumbotron">
### *Invited talks*
{% bibliography --query @incollection[keywords ^= invited] %}
</div>

<div class="jumbotron">
### *Conference presentations*
{% bibliography --query @incollection[keywords != invited] %}
</div>

