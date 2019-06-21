---
title: Home
sections:
- type: heroblock
  template: heroblock
  section_id: hero
  component: hero_block.html
  content: This Weblog covers stories on my journeys, including, but not limited to,
    Linux, FOSS and web-technologies.
  title: Hi, I'm Ankesh Bharti
  actions: []
- type: contentblock
  template: contentblock
  title: About TLDR
  section_id: about
  actions:
  - label: Read More
    url: about.html
  component: content_block.html
  content: My Name is Ankesh "shermisaurus" Bharti and I'm a junior undergrad student
    living in Delhi-NCR, India.
  image: ''
- type: postsblock
  template: postsblock
  title: Recent Posts
  section_id: recent-posts
  actions:
  - label: View Blog
    url: blog/index.html
  component: posts_block.html
  num_posts_displayed: 4
layout: home
menu:
  main:
    weight: 1

---
