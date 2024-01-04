---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: About
    username: admin
  id: about
- block: collection
  content:
    count: 3
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Posts
  design:
    columns: "2"
    view: compact
  id: posts

  
- block: collection
  content:
    title: Recent Publications
    filters:
      folders:
        - publication
  design:
    columns: '2'
    view: compact
  id: publications

title: ""
type: landing
---
