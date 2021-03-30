---
title: Blog
sections:
  - type: hero_section
    template: hero_section
    title: Blog rédactrice web SEO
    subtitle: >-
      Chaque semaine, retrouvez mes conseils et stratégies qui fonctionnent pour
      bâtir et optimiser votre contenu sur le web.
    align: center
    padding_top: medium
    padding_bottom: none
    background_color: none
    actions:
      - label: S'abonner
        style: primary
        has_icon: false
        icon: arrow-left
        icon_position: right
        new_window: false
        no_follow: false
        type: action
    image: /images/blog-redac-web.png
    media_position: right
    media_width: fifty
    image_alt: blog-redac-web
  - type: blog_feed_section
    template: blog_feed_section
    blog_feed_cols: three
    enable_cards: true
    show_recent: false
    show_date: true
    show_categories: true
    show_author: true
    show_excerpt: true
    show_image: true
    padding_top: small
    padding_bottom: large
    has_border: true
  - type: form_section
    template: form_section
    title: Inscrivez-vous
    title_align: center
    content: |
      Pour ne pas louper un seul article, abonne-toi à ma newsletter !
    content_align: center
    form_position: bottom
    form_layout: inline
    form_id: subscribeForm
    form_action: /thank-you
    form_fields:
      - type: form_field
        template: form_field
        input_type: email
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
  type: stackbit_page_meta
  template: stackbit_page_meta
  title: Blog rédactrice web SEO - Mary Marketing
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Blog rédactrice web SEO - Mary Marketing
      keyName: property
    - name: 'og:description'
      value: >-
        Grâce au blog Mary marketing, restez à l'écoutes des dernières nouvelle
        dans le domaine du marketing, de la rédaction web ou plus généralement,
        du digital ! 
      keyName: property
    - name: 'og:image'
      value: /images/square-coriander.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Blog rédactrice web SEO - Mary Marketing
    - name: 'twitter:description'
      value: >-
        Grâce au blog Mary marketing, restez à l'écoutes des dernières nouvelle
        dans le domaine du marketing, de la rédaction web ou plus généralement,
        du digital ! 
    - name: 'twitter:image'
      value: /images/square-coriander.png
      relativeUrl: true
  description: >-
    Grâce au blog Mary marketing, restez à l'écoutes des dernières nouvelle dans
    le domaine du marketing, de la rédaction web ou plus généralement, du
    digital ! 
layout: advanced
---
