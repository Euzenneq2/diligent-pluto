---
title: Mary-marketing
sections:
  - type: hero_section
    title: Mary Marketing
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: blog_feed_section
    blog_feed_cols: three
    enable_cards: true
    show_recent: false
    author: data/team/mary-marketing.json
    show_date: true
    show_categories: true
    show_author: true
    show_excerpt: true
    show_image: true
    padding_top: small
    padding_bottom: large
    has_border: true
  - type: form_section
    title: Inscription
    title_align: center
    content: |
      Pour ne pas louper un seul article, abonne-toi à ma newsletter !
    content_align: center
    form_position: bottom
    form_layout: inline
    form_id: subscribeForm
    form_action: /thank-you
    form_fields:
      - input_type: email
        name: email
        label: Email
        default_value: Votre adresse mail
        is_required: true
    submit_label: S'abonner
    padding_top: medium
    padding_bottom: medium
    has_border: true
    background_color: secondary
seo:
  title: Blog - Article de Mary Marketing
  description: >-
    Vous trouverez sur cette page tous les articles rédigés par Mary Marketing.
    Les sujets sont divers et variés, n'hésitez pas à tous les consulter.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Blog - Article de Mary Marketing
      keyName: property
    - name: 'og:description'
      value: >-
        Vous trouverez sur cette page tous les articles rédigés par Mary
        Marketing. Les sujets sont divers et variés, n'hésitez pas à tous les
        consulter.
      keyName: property
    - name: 'og:image'
      value: /images/square-coriander.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Posts by Mary-marketing
    - name: 'twitter:description'
      value: This is the author archive page
    - name: 'twitter:image'
      value: /images/square-coriander.png
      relativeUrl: true
layout: advanced
---
