---
title: "AI+Education"
permalink: /ai-education/
layout: single
classes: wide
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

{% for file in site.static_files %}
  {% if file.path contains 'files/AI-Education' %}
    - [{{ file.name }}]({{ file.path | relative_url }})
  {% endif %}
{% endfor %}

Stay tuned for more content! 