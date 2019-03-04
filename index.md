---
layout: blocks
title: Homepage
date: 2017-11-22 23:00:00 +0000
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/header_logo.svg"
  navigation:
  - link: "/"
    link_text: Home
  - link: "#features"
    link_text: Features
  - link: "#pricing"
    link_text: Pricing
  cta:
    url: https://github.com/forestryio/ubuild-jekyll/archive/master.zip
    button_text: Download
- template: hero-banner-w-image
  block: hero-2
  headline: <strong>Juice</strong><br>Regain control of your Bluetooth devices
  content: macOS menu & touch bar application you always wanted
  cta:
    enabled: true
    url: https://github.com/forestryio/ubuild-jekyll
    button_text: 'Download Juice <strong>for free</strong>'
  image:
    image: "/uploads/product_face.gif"
    alt_text: Control Center in Dark Mode
  background_image: "/uploads/2018/06/21/hero-2-bg.png"
- template: content-feature
  block: feature-1
  id: "features"
  media_alignment: Left
  headline: <strong>Connect &amp; view<span class="light">&nbsp;</span></strong><span
    class="light">your devices with ease</span>
  content: Use global shortkeys to manage your favorite Bluetooth devices
  media:
    image: "/uploads/2018/06/21/blocks-split.png"
    alt_text: Control Center Gif
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: <strong>Regain control</strong><span class="light">&nbsp;with the global Touch Bar widget</span>
  content: Connect with your devices from anywhere with the global Touch Bar widget.
  media:
    image: "/uploads/touchbar.png"
    alt_text: Touch Bar Widget
- template: 2-column-text
  block: two-column-1
  id: "pricing"
  col_1:
    headline: Free
  col_2:
    headline: Paid

- template: simple-footer
  block: footer-1
  image: "/uploads/bottom_banner.svg"
  alt_text: "Logo"
---
