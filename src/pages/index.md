---
title: Home
white_header: true
sections:
  - type: hero_section
    section_id: hero_section
    background_image: images/photo-1590540179852-2110a54f813a.jpg
    background_image_opacity: 65
    content: >-
      # Real, beautiful plants right to your door

      Don't forget to add your Snipcart API key to the site's configuration to
      enable Cart actions.
    actions:
      - title: Ver catalogo
        url: /store
        arrow: true
        style: primary
  - type: featured_products_section
    section_id: best_sellers_section
    title: Tendencias
    icon: true
    light_title: true
    featured_products:
      - src/pages/products/plant1.md
      - src/pages/products/plant3.md
      - src/pages/products/plant5.md
      - src/pages/products/plant7.md
  - type: featured_categories_section
    section_id: featured_categories_section
    featured_categories:
      - src/pages/category/bigplants.md
      - src/pages/category/cactuses.md
  - type: testimonials_section
    section_id: testimonials_section
    title: Opiniones
    testimonials:
      - author:
          name: Mariel avila
        text: Son unos genios.. me encanta como cortan
      - author:
          name: Héctor Jesús Gutiérrez
        text: son unos capos. Buena atención
  - type: promotion_section
    section_id: promotion_section
    title: Saca tu turno ahora
    subtitle: from $149.99
    image: images/103415204_3058766594203155_3155016059337296175_n.jpg
    background_image: images/Logo-light.jpg
    cta:
      title: Quiero mi turno
      url: /store
      style: secondary
      arrow: true
seo:
  title: Planty Theme
  description: The preview of the Planty theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Planty Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Planty theme
      keyName: property
    - name: 'og:image'
      value: images/header.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Planty Theme
    - name: 'twitter:description'
      value: The preview of the Planty theme
    - name: 'twitter:image'
      value: images/header.jpg
      relativeUrl: true
template: home
---
