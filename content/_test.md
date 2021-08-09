---
layout: blocks
title: Homepage
date: 2021-08-08T23:00:00.000+00:00
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/logo-1.png"
  navigation:
  - link_url: "/"
    link_text: Home
  - link_url: "/test"
    link_text: Test
- template: hero-banner-w-image
  block: hero-2
  headline: Whoo!<br><strong>It works</strong>
  content: This seems to work<br>dunno how to go about it though.
  cta:
    enabled: true
    link_url: https://github.com/forestryio/ubuild-jekyll
    link_text: 'See on GitHub '
  image:
    image: "/uploads/"
    alt_text: Product Shot
  background_image: "/uploads/jay-elephant-logo-small.jpg"
- template: simple-footer
  block: footer-1
  content: Hello test :D

---
