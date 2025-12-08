---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/images/front_page_banner.png
excerpt: "North Wales Slate & Pebble Jewellery."
intro: 
  - excerpt: 'Welcome to Pebblau Mon. I make jewellery using pebbles from North Wales beaches and slate from old roofs. Each piece is shaped, engraved with a fibre laser, and coloured by hand, creating something unique from natural materials.'
feature_row:
  - image_path: assets/images/designs/Iron_Age_Cat.png
    image_caption: "Image courtesy of [Amgueddfa Cymru]([https://unsplash.com/](https://museum.wales/collections/online/object/92350620-6033-3a2c-b424-f546991e4094/Iron-Age-copper-alloy-bowl/?field0=string&value0=coast&field1=with_images&value1=on&page=141&index=1681))"
    alt: "Historical Designs"
    title: "Designs"
    excerpt: "My designs are inspired by Welsh symbols and archaeological finds, including Roman and early medieval tiles. You can see more of these designs here."
    url: "designs"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/images/selfie.jpg
    alt: "Megan Round"
    title: "About Me"
    excerpt: "I enjoy exploring materials, trying new techniques, and making things with my hands. You can find out more about me on the About Me page."
    url: "about"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/images/process/cutting_slate_front_page.png
    title: "The Process"
    excerpt: "The pieces take time and careful work, from shaping the stone to enamel firing and finishing. You can read about the full process here."
    url: "process"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
