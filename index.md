---
title: "Daniel Liu Consulting"
layout: splash
author_profile: false
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/national-cancer-institute-zQkoVCTyaHI-unsplash.jpg
  actions:
    - label: "Get in touch!"
      url: "mailto:consulting@liudaniel.com"
excerpt: "Performance-focused bioinformatics software consultancy"

intro:
  - excerpt: |
      We specialize in software and algorithms development.
      We will work with you to tackle your challenging bioinformatics problems.

feature_row:
  - image_path: "data:,"
    title: "We focus on DNA/RNA sequence analysis software"
    excerpt: "Sequencing experiments are widely used to understand biological systems. We may take on other projects on a case-by-case basis."
  - image_path: "data:,"
    title: "We care about efficiency and reliability"
    excerpt: "Typical sequencing experiments generate millions or billions of reads. We strive to build software that easy scales to these large experiments."
  - image_path: "data:,"
    title: "We use the Rust programming language"
    excerpt: "Rust makes it easy to write reliable, efficient code. Depending on the requirements of a project, we may use other languages like Java, Python, C, etc."

services:
  - excerpt: |
      ## Our Services

feature_row2:
  - image_path: "data:,"
    title: "Algorithms and software development"
    excerpt: "We develop, document, and test software that addresses a client's needs."
  - image_path: "data:,"
    title: "Optimizing software bottlenecks"
    excerpt: "We help optimize software pipelines by carefully benchmarking and using tools like SIMD, multi-threading, etc."
  - image_path: "data:,"
    title: "Contributing to open source"
    excerpt: "We maintain or add new features to open source projects."

testimonials:
  - excerpt: |
      ## Testimonials
      "Such cool much wow" *- First Last*
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="services" type="center" %}

{% include feature_row id="feature_row2" %}

{% include feature_row id="testimonials" type="center" %}
