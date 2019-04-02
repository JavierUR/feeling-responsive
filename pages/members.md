---
layout: page
title: "Miembros"
subheadline: ""
teaser: ""
header:
   image_fullwidth: "header.svg"
permalink: "/members/"
---

<link href="{{ site.url }}{{ site.baseurl }}/assets/css/members.css" rel="stylesheet">


<div class="row t60">
    {%for person in site.data.members %}
        {% assign member = person[0] %}
        <div class="medium-6 columns b30">
            {% include member-by-name memberName=member %}

        </div>
    {%endfor%}

	



</div>