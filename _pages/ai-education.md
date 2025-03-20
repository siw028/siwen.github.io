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

<div class="presentation-list">
{% for file in site.static_files %}
  {% if file.path contains 'files/AI-Education' %}
    <div class="presentation-item">
      <a href="{{ site.baseurl }}/{{ file.path }}" target="_blank" class="presentation-link">
        {{ file.basename }} 
        <span class="file-type">[{{ file.extname | remove: '.' | upcase }}]</span>
      </a>
    </div>
  {% endif %}
{% endfor %}
</div>

<style>
.presentation-list {
  margin: 20px 0;
}
.presentation-item {
  margin-bottom: 15px;
}
.presentation-link {
  text-decoration: none;
  color: #0366d6;
  display: inline-block;
  padding: 5px 0;
}
.presentation-link:hover {
  text-decoration: underline;
}
.file-type {
  color: #666;
  font-size: 0.9em;
  margin-left: 5px;
}
</style>

Stay tuned for more content! 