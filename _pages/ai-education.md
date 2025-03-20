---
title: "AI+Education"
permalink: /ai-education/
layout: single
classes: wide
nav: true
nav_order: 3
---

Welcome to the AI+Education section! This page will showcase my work and insights in the intersection of artificial intelligence and education.

## Overview

This section will be updated with content about:
- AI applications in education
- Educational technology innovations
- Teaching and learning with AI
- Research and projects in AI education

## Presentations and Slides

You can find my presentations and slides related to AI in Education below:

<ul class="presentation-list">
{% for file in site.static_files %}
  {% if file.path contains 'files/AI-Education' %}
    <li>
      <a href="{{ site.baseurl }}{{ file.path }}" target="_blank">
        {{ file.basename }} 
        <small>[{{ file.extname | remove: '.' | upcase }}]</small>
      </a>
    </li>
  {% endif %}
{% endfor %}
</ul>

<style>
.presentation-list {
  list-style: none;
  padding-left: 0;
}
.presentation-list li {
  margin-bottom: 10px;
}
.presentation-list small {
  color: #666;
}
</style>

Stay tuned for more content! 