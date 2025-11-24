---
title: Home
slug: /
sections:
  - type: GenericSection
    elementId: hero
    colors: bg-light-fg-dark
    badge:
      label: Videographer · Director
      color: text-primary
      type: Badge
    title:
      text: Ayberk Aktürk
      color: text-dark
      type: TitleBlock
    subtitle: Narrative films for brands who value craft.
    text: |-
      Vancouver-based videographer blending natural light with precise direction to deliver cinematic brand films, founder portraits, and product launches.
    actions:
      - label: Watch the reel
        altText: Jump to 2025 reel
        url: /#reel
        showIcon: true
        icon: play
        iconPosition: right
        style: primary
        type: Button
      - label: Book a shoot
        altText: Jump to contact form
        url: /#contact
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Link
    media:
      url: /images/main-hero.jpg
      altText: Ayberk working on set
      type: ImageBlock
      styles:
        self:
          borderRadius: x-large
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-20
          - pb-20
          - pl-12
          - pr-12
  - type: GenericSection
    elementId: about
    colors: bg-neutral-fg-dark
    badge:
      label: About the studio
      color: text-primary
      type: Badge
    title:
      text: Quiet sets, bold stories
      color: text-dark
      type: TitleBlock
    text: |-
      Every project runs through a lean cadence: discover the story, craft the look, shoot with intention, and deliver polished masters fit for launch. I work with a small network of sound, color, and animation partners so you get senior hands on every frame.

      **What clients say:** reliable communication, calm direction, and footage that feels expensive without the bloated crew.
    media:
      url: /images/hero2.svg
      altText: Minimal studio illustration
      type: ImageBlock
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-14
          - pb-14
          - pl-14
          - pr-14
  - type: FeaturedItemsSection
    elementId: services
    title:
      text: Services at a glance
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: From 30-second launch spots to documentary series.
    items:
      - type: FeaturedItem
        title: Brand films
        text: >-
          Direction, cinematography, and edit for narrative commercials and
          flagship campaigns.
        image:
          url: /images/icon1.svg
          altText: Spotlight icon
          type: ImageBlock
        colors: bg-light-fg-dark
      - type: FeaturedItem
        title: Founder portraits
        text: >-
          Intimate interviews and docu-style pieces that show the people behind
          the product.
        image:
          url: /images/icon2.svg
          altText: Interview icon
          type: ImageBlock
        colors: bg-light-fg-dark
      - type: FeaturedItem
        title: Event & launch coverage
        text: >-
          Multi-camera coverage, social cuts, and motion graphics ready within
          days of your moment.
        image:
          url: /images/icon3.svg
          altText: Event icon
          type: ImageBlock
        colors: bg-light-fg-dark
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-14
          - pb-14
          - pl-8
          - pr-8
  - type: FeaturedItemsSection
    elementId: work
    title:
      text: Selected work
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Recent collaborations shipped in 2024–2025.
    items:
      - type: FeaturedItem
        title: Edge of Light
        subtitle: Lifestyle brand film
        text: >-
          Shot on FX6 + Zeiss primes in Lisbon, blending handheld movement with
          moody interiors. Delivered hero film plus 8 social cutdowns.
        image:
          url: /images/abstract-feature1.svg
          altText: Edge of Light frame
          type: ImageBlock
        actions:
          - label: View breakdown
            url: /blog/case-study-1
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Link
        colors: bg-neutralAlt-fg-dark
      - type: FeaturedItem
        title: Founders in Focus
        subtitle: Documentary mini-series
        text: >-
          Three-part founder story for a fintech startup. Hybrid of Sit-Down
          interviews, macro product shots, and archival overlays.
        image:
          url: /images/abstract-feature2.svg
          altText: Founders in Focus frame
          type: ImageBlock
        actions:
          - label: Watch episode
            url: /blog/case-study-2
            icon: play
            iconPosition: right
            style: secondary
            type: Link
        colors: bg-neutralAlt-fg-dark
      - type: FeaturedItem
        title: City Pulse
        subtitle: Event recap
        text: >-
          48-hour turnaround recap for a downtown summit. Delivered vertical
          reels, hero film, and a library of color-graded stills.
        image:
          url: /images/abstract-feature3.svg
          altText: City Pulse frame
          type: ImageBlock
        actions:
          - label: See deliverables
            url: /blog/case-study-3
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Link
        colors: bg-neutralAlt-fg-dark
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pb-16
          - pl-10
          - pr-10
  - type: GenericSection
    elementId: reel
    colors: bg-light-fg-dark
    badge:
      label: Reel 2025
      color: text-primary
      type: Badge
    title:
      text: 90 seconds, multiple continents
      color: text-dark
      type: TitleBlock
    subtitle: Shot on RED Komodo + Sony FX6 · graded in DaVinci
    text: |-
      A mix of commercial, lifestyle, and documentary footage captured in Vancouver, Istanbul, and Lisbon. Includes handheld, gimbal, and drone work with bespoke Foley.
    actions:
      - label: Open on YouTube
        url: https://www.youtube.com/
        icon: play
        iconPosition: right
        style: secondary
        type: Link
    media:
      title: Ayberk Aktürk Reel 2025
      url: /images/placeholder-video.mp4
      autoplay: true
      loop: true
      muted: true
      controls: true
      aspectRatio: '16:9'
      type: VideoBlock
    styles:
      self:
        flexDirection: col
        padding:
          - pt-14
          - pb-14
          - pl-14
          - pr-14
  - type: GenericSection
    elementId: contact
    colors: bg-light-fg-dark
    badge:
      label: Contact
      color: text-primary
      type: Badge
    title:
      text: Tell me about your shoot
      color: text-dark
      type: TitleBlock
    subtitle: I book one production window per month—reach out early.
    text: |-
      Share the location, timeline, and vibe. I’ll follow up within two business days with a treatment outline, crew size, and estimate.
    media:
      type: FormBlock
      elementId: contact-form
      submitButton:
        type: SubmitButtonFormControl
        label: Send message
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: project
          label: Project details
          hideLabel: true
          placeholder: Location, timeline, deliverables
          width: full
          type: TextareaFormControl
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    styles:
      self:
        flexDirection: row
        alignItems: center
        padding:
          - pt-14
          - pb-14
          - pl-14
          - pr-14
seo:
  metaTitle: Ayberk Aktürk — Videographer Portfolio
  metaDescription: One-page videographer portfolio for Ayberk Aktürk featuring services, selected films, reel, and contact.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
