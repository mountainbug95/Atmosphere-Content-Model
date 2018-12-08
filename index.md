---
title: Home
banner:
  section_id: banner
  title: Magna sed consequat
  subtitle: Ipsum dolor sit amet
  actions:
    - label: Get Started
      url: '#spotlight'
      is_primary: true
      is_scrolly: true
sections:
  - section_id: spotlight
    background_style: style2
    component: spotlight.html
    type: spotlight
  - section_id: features
    background_style: style1
    features:
      - title: Placerat
        text: Lorem ipsum dolor sit amet nullam et consequat.
        icon: fa-bar-chart
      - title: Libero
        text: Lorem ipsum dolor sit amet nullam et consequat.
        icon: fa-paper-plane-o
      - title: Solicitu
        text: Lorem ipsum dolor sit amet nullam et consequat.
        icon: fa-area-chart
      - title: Tempor
        text: Lorem ipsum dolor sit amet nullam et consequat.
        icon: fa-file-image-o
    component: features.html
    type: features
  - section_id: featured-page
    component: featured_page.html
    type: featured_page
  - title: Aliquam tincidunt mauris eu risus
    subtitle: Malesuada
    background_style: style2
    section_id: posts
    num_posts_displayed: 3
    component: posts.html
    type: posts
menus:
  main:
    title: Home
    weight: 1
layout: home
---
