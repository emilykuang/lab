---
# Leave the homepage title empty to use the site title
title:
date: 2025-08-20
type: landing

sections:
  - block: hero
    content:
      title: |
        COCOA
        Research Lab
      image:
        filename: COCOA-lab.png
      text: |
        <br>
        
        <small>The <b>COCOA (CO-designing COllaborations with AI)</b> Lab explores how humans and AI can collaborate effectively, designing intelligent interactive systems that enhance human productivity and empower diverse users. 
        We combine Human-Computer Interaction, AI, and accessibility research to create  collaborative tools and adaptive interfaces that support real-world tasks and emerging virtual experiences.</small>

        <br>

        <small>We are part of the <a href="https://gamay-hub.github.io/">Graphics and Media at York (GaMaY) Hub</a>.</small>
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 1
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
      view: card
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 3
      filters:
        folders:
          - publication
        # publication_type: 'paper-conference'
    design:
      view: citation
      columns: '1'
---
