---
layout: page
title: Research
description: "Research projects, Neuroscience, Engineering, Ricardo Martins, CIBIT, ICNAS, UC, University of Coimbra"
navorder: 2
permalink: /research/
---

<h3>Ongoing Research Projects</h3>
<ul class="list-group">
  {% for member in site.data.myResearchOngoing %}
	<div class="col-md-4">
		<!-- Image goes here -->
		<img src="/assets/images/computer-logo.png" class="img-fluid" alt="Image">
	</div>
	<div class="col-md-8">
		<p><strong>{{member.name}}</strong></p>
		<p><strong>Research Field: </strong> {{member.research}}</p>
		<p><strong>Time Span: </strong> {{member.time}}</p>
		<p><strong>Role: </strong> {{member.role}}</p>
		<p><strong>More info: </strong> [<a target="_blank" href="https://{{member.info}}">website</a>]</p>
		<p></p>
	</div>  
  {% endfor %}
</ul>