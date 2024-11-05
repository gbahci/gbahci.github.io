---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
       
      image:
        filename: logo2.jpg
      text: |
        <br>
        Greater Bay ACM SIGCHI Chapter is an assembly of groups of researchers from universities and institutions across from the Greater Bay Area of China, with the goal to facilitate the sharing of knowledge and synergize efforts to advance the field of Human-Computer Interaction (HCI) research in China and globally. We are united by a common vision wherein HCI research serves as the driving force to connect the intersections of technologies, industries, and humanities. We organize academic events, such as internal workshops, seminars, and forums, for research sharing, and activities to foster connections between academia to the industries and the public. We also host social events on the occasions of HCI conferences (e.g. CHI, UIST, TEI, and DIS).
        
  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text: Greater Bay ACM SIGCHI Chapter is an assembly of groups of researchers from universities and institutions across from the Greater Bay Area of China, with the goal to facilitate the sharing of knowledge and synergize efforts to advance the field of Human-Computer Interaction (HCI) research in China and globally. We are united by a common vision wherein HCI research serves as the driving force to connect the intersections of technologies, industries, and humanities. We organize academic events, such as internal workshops, seminars, and forums, for research sharing, and activities to foster connections between academia to the industries and the public. We also host social events on the occasions of HCI conferences (e.g. CHI, UIST, TEI, and DIS).
    design:
      columns: '1'
      # background:
      #   image: 
      #     filename: coders.jpg
      #     filters:
      #       brightness: 1
      #     parallax: false
      #     position: center
      #     size: cover
      #     text_color_light: true
      spacing:
        padding: ['20px', '20px', '20px', '20px']
        
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Event
      text: ""
      count: 5
      filters:
        folders:
          - talk
        # publication_type: 'Talks/Events'
    design:
      view: showcase
      columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---
