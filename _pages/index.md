---
title: "Home"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/welcomepic.webp
  actions:
    - label: "Download CV"
      url: "assets/downloads/CharlieMcClaffertyCV.pdf"
      target: "_blank"


excerpt: ""
intro: 
  - excerpt: 'Hello, welcome to my portfolio website!'
feature_row:
  - image_path: /assets/images/P11.png
    alt: "placeholder image 1"
    title: "Project 1"
    excerpt: "Here you can view the very first game I made."
    url: "/projects/project1/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/P21.png
    alt: "placeholder image 2"
    title: "Project 2"
    excerpt: "This is a 3D landscape I created of a Japanese temple."
    url: "/projects/project2/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/skillsicon.jpg
    alt: "placeholder image 4"
    title: "Skills"
    excerpt: "This is a list of my key and soft skills."
    url: "/Skills/"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

