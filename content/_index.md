---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Matt and Emaly Vatne
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Hi! We are Matt and Emaly Vatne and we work across the entire data lifecycle for Ohio State Athletics and also lead the contextualization of data and translation to action that helps put athletes in the best position to perform. The purpose of this site is to serve as a portfolio of our work and demonstrate our growth over time.
  
  - block: collection
    content:
      title: Latest Projects
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: citation
      columns: '1'

  - block: collection
    content:
      title: Latest Publications and Presentations
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
