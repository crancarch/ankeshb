---
title: Home
sections:
- type: heroblock
  template: heroblock
  section_id: hero
  component: hero_block.html
  content: This section can contain a subtitle or tagline. The recommended length
    is one to three sentences, but can be changed as you prefer.
  title: ''
  actions: []
- type: contentblock
  template: contentblock
  title: About
  section_id: about
  actions:
  - label: Contact Me
    url: contact.html
  component: content_block.html
  content: 'Fine, I’ll admit it: I’m Ankesh Bharti. I identify myself as one heck
    of a tech nerd who absolutely loves web-technologies, FOSS among many other _cool_  things.
    **_:x_**'
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
