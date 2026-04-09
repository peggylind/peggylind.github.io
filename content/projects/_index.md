---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  spacing: '5rem'

sections:
  - block: markdown
    content:
      title: 'Research Projects'
      text: |-
        <div class="project-filter-bar">
          <a class="project-filter-button active" href="/projects/">All</a>
          <a class="project-filter-button" href="/projects-digital-humanities/">Digital Humanities</a>
          <a class="project-filter-button" href="/projects-social-computing/">Social Computing</a>
          <a class="project-filter-button" href="/projects-other/">Other</a>
        </div>

  - block: collection
    content:
      title:
      text: ''
      count: 0
      filters:
        folders:
          - projects
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false
---
