---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: As a researcher
      content: Explore my currrent and previous research projects
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: coders.jpg
      link: 
          icon: graduation-cap
          icon_pack: fas
          text: "Access my porfolio"
          url: ../guides/
    - title: As an educator
      content: 'Presentations, lectures or other educational materials'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: contact.jpg
    - title: As a community citizen
      content: 'Support local projects, or helping you age better.
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
