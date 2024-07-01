---
type: PageLayout
title: Home
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Unblock your team boost your time to production
      color: text-neutral
    subtitle: Subtitle goes here
    text: >
      A Netlify website is a git repo that you own. Every code commit is
      instantly reflected in the visual editor and since every visual edit is a
      git commit, git workflows and collaboration just work.
    actions:
      - type: Button
        label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
      - type: Link
        label: See Tutorials
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
    media:
      type: ImageBlock
      url: /images/main-hero.svg
      altText: Unblock your team boost your time to production preview
      elementId: ''
    badge:
      type: Badge
      label: This is a badge
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
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Key Benefits
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: Subtitle goes here
    items:
      - type: FeaturedItem
        title: 500k
        subtitle: Numbers Done
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/icon1.svg
          altText: Placeholder image
          elementId: ''
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
      - type: FeaturedItem
        title: 20x
        subtitle: The Job Stuff
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/icon2.svg
          altText: Placeholder image
          elementId: ''
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
      - type: FeaturedItem
        title: 200%
        subtitle: Faster
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/icon3.svg
          altText: Placeholder image
          elementId: ''
        actions: []
        colors: bg-neutralAlt-fg-dark
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
        label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    badge:
      type: Badge
      label: This is a badge
      color: text-primary
      styles:
        self:
          textAlign: center
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: ImageGallerySection
    subtitle: Award winning enterprises trust us
    images:
      - type: ImageBlock
        url: /images/empathy-logo.svg
        altText: Empathy logo
      - type: ImageBlock
        url: /images/wellster-logo.svg
        altText: Wellster logo
      - type: ImageBlock
        url: /images/vise-logo.svg
        altText: Vise logo
      - type: ImageBlock
        url: /images/telus-logo.svg
        altText: Telus logo
      - type: ImageBlock
        url: /images/contenful-logo.svg
        altText: Contentful logo
      - type: ImageBlock
        url: /images/sanity-logo.svg
        altText: Sanity logo
      - type: ImageBlock
        url: /images/rangle-logo.svg
        altText: Rangle logo
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
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
  - type: GenericSection
    title:
      type: TitleBlock
      text: Grow your business 10x faster
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: This is a subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
    media:
      type: VideoBlock
      title: Title of the video
      url: /images/placeholder-video.mp4
      autoplay: true
      loop: true
      muted: true
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    badge:
      type: Badge
      label: Key Benefits
      color: text-primary
      styles:
        self:
          textAlign: center
    colors: bg-light-fg-dark
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
