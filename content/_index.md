---
# Homepage configuration
title: 'Sonan Memon'
date: 2025-01-04
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  # Biography Section
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/CV-SMEMON-Dec-2025.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  # Optional Markdown Section
  - block: markdown
    content:
      title: 'Welcome'
      text: |-
        Here you can find my publications and other academic work.
    design:
      columns: '1'

  # Job Market Papers Collection
  - block: collection
    id: papers
    content:
      title: Job Market Papers
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  # Published Papers Collection
  - block: collection
    content:
      title: Other Research Work
      filters:
        folders:
          - publications
    design:
      view: citation
      columns: 1
---
