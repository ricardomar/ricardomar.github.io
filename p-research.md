---
layout: page
title: Research
description: "Research projects, Neuroscience, Engineering, Ricardo Martins, CIBIT, ICNAS, UC, University of Coimbra"
navorder: 2
permalink: /research/
---

<h2>Ongoing Research Projects</h2>
<ul class="list-group">
  {% for member in site.data.myResearchOngoing %}
  <li class="list-group-item d-md-flex flex-md-row flex-column" style="border: none;">
	<div class="col-md-2">
	  <img src="{{member.logo}}" alt="logo" class="img-fluid"  width="100">
	</div>
	<div class="col-md-10">
	  <p><strong>{{member.name}}</strong></p>
	  <ul>
			<li><strong>Research Field: </strong> {{member.research}}</li>
			<li><strong>Time Span: </strong> {{member.time}}</li>
			<li><strong>Role: </strong> {{member.role}}</li>
			<li><strong>More info: </strong> [<a target="_blank" href="https://{{member.info}}">website</a>]</li>
	  </ul>
	</div>
  </li>
  {% endfor %}
</ul>