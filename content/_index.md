---
title: ""
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: "欢迎来到落木庭"
      subtitle: "拾起旧时的落叶，记录其中的岁月。"
    design:
      spacing:
        padding: [0, 0, 0, 0]
         margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
       color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  - block: collection
    id:
    content:
      title: Recent Posts
      subtitle: 
      text:
      page_type: post
      count: 0
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: ['3rem', 0, '6rem', 0]
---
