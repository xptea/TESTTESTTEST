---
type: PageLayout
title: Careers
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: A team that works closely together
      color: text-neutral
      styles:
        self:
          textAlign: center
    subtitle: Collaboration at Its Best
    text: >
      Our team is dedicated to working together to bring you the best gaming
      experience. We believe in strong collaboration and open communication to
      achieve our goals.
    actions:
      - type: Button
        label: See open positions
        url: '#positions'
        icon: arrowRight
        iconPosition: right
        style: primary
    colors: bg-dark-fg-light
    styles:
      self:
        padding:
          - pt-40
          - pl-4
          - pb-40
          - pr-4
        alignItems: center
        flexDirection: row-reverse
        justifyContent: center
      text:
        textAlign: center
      subtitle:
        textAlign: center
  - type: FeaturedPeopleSection
    title:
      type: TitleBlock
      text: Meet the team
      color: text-neutral
      styles:
        self:
          textAlign: center
    people:
      - content/data/web.json
    actions: []
    variant: three-col-grid
    colors: bg-dark-fg-light
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Positions
      color: text-neutral
      styles:
        self:
          textAlign: center
    subtitle: careers
    items:
      - type: FeaturedItem
        title: Lua-U Engineer
        subtitle: 'Engineering '
        text: |+
          Contact for more info

        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
        tagline: 'Engineering '
      - type: FeaturedItem
        title: Open Source Engineer
        subtitle: 'Engineering '
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
        tagline: 'Engineering '
      - type: FeaturedItem
        title: Senior Software Engineer
        subtitle: Engineering
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
    actions:
      - type: Button
        label: Apply now
        url: /contact
        icon: arrowRight
        iconPosition: right
        style: primary
    variant: toggle-list
    colors: bg-dark-fg-light
    styles:
      self:
        padding:
          - pb-40
          - pt-16
          - pl-3
          - pr-3
        justifyContent: center
      subtitle:
        textAlign: center
    elementId: positions
slug: careers
seo:
  type: Seo
  metaTitle: Careers - Only Three Team Games
  metaDescription: Careers Page - Only Three Team Games
  metaTags: []
  socialImage: /images/ONLYTHREETEAM.png
---
