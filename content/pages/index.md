---
type: PageLayout
title: Home
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Only Three Team Games
      color: text-neutral
    subtitle: Game Updates every weekend
    text: ''
    actions:
      - type: Button
        label: Discord
        altText: ''
        url: 'https://discord.gg/QgKHvt76Kb'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
      - type: Link
        label: Careers
        altText: ''
        url: /careers
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
    media:
      type: ImageBlock
      url: /images/ONLYTHREETEAM.png
      altText: icon
      elementId: ''
      styles:
        self:
          borderRadius: large
          padding:
            - pr-0
            - pl-0
            - pt-0
            - pb-0
          margin:
            - mr-0
            - ml-64
    badge:
      type: Badge
      label: EST 2024
      color: text-neutral
    elementId: ''
    colors: bg-dark-fg-light
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - type: DividerSection
    title: Divider
    colors: bg-dark-fg-light
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
  - type: GenericSection
    title:
      type: TitleBlock
      text: Punching Simulator
      color: text-neutral
      styles:
        self:
          textAlign: center
    subtitle: Updates every weekend
    text: "Step into the ring and unleash your fury in Punching Simulator! \U0001F94A\U0001F4A5 Train your fists of steel, get stronger, and rise through the ranks to dominate other players! Smash through walls, take down opponents, and hone your skills in intense training sessions. Customize your fighter, earn epic rewards, and climb the leaderboards! \U0001F31F\n"
    actions: []
    badge:
      type: Badge
      label: Only Three Team Games
      color: text-neutral
      styles:
        self:
          textAlign: center
    colors: bg-dark-fg-light
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
  - type: DividerSection
    title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: List of features here
      color: text-primary
      styles:
        self:
          textAlign: center
    subtitle: Featured items section subtitle
    items:
      - type: FeaturedItem
        title: Feature Item One
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first Netlify site.
        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
          altText: Placholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
      - type: FeaturedItem
        title: Feature Item Two
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first awesome Netlify site.
        image:
          type: ImageBlock
          url: /images/abstract-feature2.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
      - type: FeaturedItem
        title: Feature Item Three
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Learn from the tutorial and build your first awesome Netlify site.
        image:
          type: ImageBlock
          url: /images/abstract-feature3.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
    actions: []
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
slug: /
seo:
  type: Seo
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create
  socialImage: /images/main-hero.jpg
  metaTags: []
---
