---
layout: archive
title: "Research"
# hide:
#   - title
permalink: /research/
author_profile: true
sitemap: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Working Papers

<p style="margin:0; font-size:1rem;">
  Cohort‑Chained DiD: Long‑Run Effects with Limited Pre‑Treatment Data<br>
  <em style="font-size:.9rem;">with
      <a href="https://www.dballaelliott.com/" target="_blank">Dylan Balla‑Elliott</a>
  </em><br>
  <span style="font-size:.9rem;">
      <a href="#/" onclick="visib('ccdid')">Abstract</a> |
      <a href="/files/pdf/CCDID.pdf">Draft</a>
  </span>
</p>

<div id="ccdid"
     style="display:none; font-size:.9rem; line-height:1.4; text-align:justify">
  Heterogeneity robust difference-in-differences methods typically require control units that remain untreated throughout the entire post-treatment window. This unnecessarily limits the identification of long-run effects when researchers observe fewer pre-treatment periods than post-treatment periods. We show that cohort-stacked estimators identify long-run effects by chaining together successive not-yet-treated controls. This approach uses overlapping cohorts to extend identification under standard common trends assumptions. We demonstrate the approach through an application to earnings effects of parenthood. In a setting where direct methods identify effects only four years post-birth, chaining extends identification to eight years.
</div>


## Work in Progress

<p style="margin:0; font-size:1rem;">
  The Labor Market Returns to Permanent Residency<br>
  <em style="font-size:.9rem;">
    with
    <a href="https://www.korykroft.com/" target="_blank">Kory Kroft</a>,
    <a href="https://users.nber.org/~notom/" target="_blank">Matthew Notowidigdo</a>,
    and
    <a href="https://stephentino.github.io/" target="_blank">Stephen Tino</a>
  </em><br>
  <span style="font-size:.85rem; font-style:italic;">
    Presented (by co‑author) at 2025 NBER Summer Institute Labor Studies
  </span>
</p>

<!-- The Labor Market Returns to Permanent Residency<br> -->
<!-- <span style="font-size:medium;"> *with [Kory Kroft](https://www.korykroft.com/), [Matthew Notowidigdo](https://users.nber.org/~notom/), and [Stephen Tino](https://stephentino.github.io/)*</span> <br> -->
<!-- <span style="font-size:medium; font-style:italic;"> Presented (by co-author) at 2025 NBER Summer -->
<!-- Institute Labor Studies </span> <br> -->


<!-- When you finally have work to add here, put it in the _research folder, one file per paper -->
<!-- Then also remove the sitemap: false from each file -->
<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

[//]: This java script is the button to show abstract
<script>
 function visib(id) {
  var x = document.getElementById(id);
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>

[//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Abstract</button>