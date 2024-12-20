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
      background: stacked-peaks.svg
      spacing: ['2rem', '2rem', '4rem', '2rem']
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
