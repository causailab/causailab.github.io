---
layout: profiles
permalink: /team/
title: Team
description: If you want to go fast, go alone; if you want to go far, go together.
nav: true
nav_order: 3

profiles:
  # if you want to include more than one profile, just replicate the following block
  # and create one content file for each profile inside _pages/
  - align: left
    image: pic_zhangl.png
    content: about_zhangl.md
    image_circular: false # crops the image to make it circular
    more_info: >
    
  - align: left
    image: pic_suns.jpg
    content: about_suns.md
    image_circular: false # crops the image to make it circular
    more_info: >

  - align: left
    image: pic_chenh.jpeg
    content: about_chenh.md
    image_circular: false # crops the image to make it circular
    more_info: >

  - align: left
    image: pic_yous.jpg
    content: about_yous.md
    image_circular: false # crops the image to make it circular
    more_info: >

  - align: left
    image: pic_fanr.jpeg
    content: about_fanr.md
    image_circular: false # crops the image to make it circular
    more_info: >



---

## Alumni

<ul class="alumni-list">
{% for a in site.data.alumni %}
  <li>
    <strong>{{ a.name }}</strong>: {{ a.role }}, {{ a.years }}. Current: {{ a.current }}.
  </li>
{% endfor %}
</ul>
