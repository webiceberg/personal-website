---
title: Home
slug: /
sections:
  - type: GenericSection
    elementId: hero
    colors: bg-dark-fg-light
    badge:
      label: Ayberk Aktürk
      color: text-primary
      type: Badge
    title:
      text: Cinematic videographer for thoughtful brands
      color: text-light
      type: TitleBlock
    subtitle: Director of Photography · Vancouver / Worldwide
    text: |-
      I craft restrained, human films for founders, fashion houses, and cultural
      institutions. Minimal crews, cinematic light, story-first delivery.
    actions:
      - label: Play showreel
        altText: Jump to the showreel
        url: /#reel
        showIcon: true
        icon: play
        iconPosition: right
        style: primary
        type: Button
      - label: Book a shoot
        altText: Jump to contact
        url: /#contact
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Link
    media:
      url: /images/main-hero.jpg
      altText: Cinematic still of Ayberk filming on set
      type: ImageBlock
      styles:
        self:
          borderRadius: x-large
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-24
          - pb-24
          - pl-12
          - pr-12
  - type: FeaturedItemsSection
    elementId: scenes
    title:
      text: Recent scenes
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Lean shoots, crafted in-camera, color-finished in-house.
    items:
      - type: FeaturedItem
        title: 47
        subtitle: films delivered in 2024
        text: From teaser loops to 12-minute documentaries.
        colors: bg-light-fg-dark
      - type: FeaturedItem
        title: 14
        subtitle: cities filmed
        text: Vancouver, Lisbon, Istanbul, Seoul, and more.
        colors: bg-light-fg-dark
      - type: FeaturedItem
        title: 6
        subtitle: international awards
        text: Honored by ADC, Applied Arts, and Motion Awards.
        colors: bg-light-fg-dark
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-12
          - pb-12
          - pl-10
          - pr-10
  - type: GenericSection
    elementId: reel
    colors: bg-light-fg-dark
    badge:
      label: Showreel
      color: text-primary
      type: Badge
    title:
      text: 90 seconds of light & motion
      color: text-dark
      type: TitleBlock
    text: Filmed on FX6 + RED Komodo with Zeiss glass. Graded in DaVinci.
    media:
      title: Ayberk Aktürk Reel 2025
      url: /images/placeholder-video.mp4
      autoplay: false
      loop: false
      muted: false
      controls: true
      aspectRatio: '16:9'
      styles:
        self:
          borderRadius: large
      type: VideoBlock
    actions:
      - label: Watch on Vimeo
        url: https://www.vimeo.com/
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Link
    styles:
      self:
        flexDirection: col
        padding:
          - pt-16
          - pb-16
          - pl-12
          - pr-12
  - type: FeaturedItemsSection
    elementId: services
    title:
      text: Services
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Full-stack video production, sized for modern launches.
    items:
      - type: FeaturedItem
        title: Brand Films
        text: Concept, direction, and on-set leadership for campaigns and launches.
        image:
          url: /images/icon1.svg
          altText: Brand film icon
          type: ImageBlock
        colors: bg-light-fg-dark
      - type: FeaturedItem
        title: Documentary Portraits
        text: Intimate interviews + vérité coverage for founders and artists.
        image:
          url: /images/icon2.svg
          altText: Documentary icon
          type: ImageBlock
        colors: bg-light-fg-dark
      - type: FeaturedItem
        title: Post & Color
        text: Editing, grade, sound mix, and delivery in every requested format.
        image:
          url: /images/icon3.svg
          altText: Post production icon
          type: ImageBlock
        colors: bg-light-fg-dark
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-18
          - pb-18
          - pl-10
          - pr-10
  - type: GenericSection
    elementId: approach
    colors: bg-neutral-fg-dark
    badge:
      label: Approach
      color: text-primary
      type: Badge
    title:
      text: Quiet, precise, collaborative
      color: text-dark
      type: TitleBlock
    text: |-
      1. **Treatment & schedule.** We define tone, shot list, and logistics in a
      90-minute working session.

      2. **Shoot.** Lean crew, natural light first, then add shape with practical
      rigs. Daily stills for feedback.

      3. **Finish.** Edit, color, mix, mastering, and multi-format delivery with a
      detailed usage guide.
    styles:
      self:
        flexDirection: col
        padding:
          - pt-16
          - pb-16
          - pl-12
          - pr-12
  - type: FeaturedItemsSection
    elementId: work
    title:
      text: Spotlight work
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Selected collaborations from the past year.
    items:
      - type: FeaturedItem
        title: Lumière Atelier
        subtitle: Resort launch film
        text: Shot in Provence at sunrise + dusk; tactile macro shots paired with whispered VO.
        image:
          url: /images/abstract-feature1.svg
          altText: Lumière still
          type: ImageBlock
        actions:
          - label: View stills
            url: /blog/case-study-1
            style: secondary
            icon: arrowRight
            iconPosition: right
            type: Link
        colors: bg-light-fg-dark
      - type: FeaturedItem
        title: Meridian Instruments
        subtitle: Founder profile short
        text: Industrial textures meet delicate portraiture inside a working lab.
        image:
          url: /images/abstract-feature2.svg
          altText: Meridian still
          type: ImageBlock
        actions:
          - label: Watch excerpt
            url: /#reel
            style: secondary
            icon: play
            iconPosition: right
            type: Link
        colors: bg-light-fg-dark
    variant: two-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pb-16
          - pl-10
          - pr-10
  - type: GenericSection
    elementId: contact
    colors: bg-neutral-fg-dark
    badge:
      label: Contact
      color: text-primary
      type: Badge
    title:
      text: Tell me about the film you need
      color: text-dark
      type: TitleBlock
    text: |-
      Share a brief, deck, or even a single reference clip. I respond within two
      business days with a schedule and budget range.
    actions:
      - label: Email hello@ayberkakturk.com
        url: mailto:hello@ayberkakturk.com
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: Download rate sheet
        url: /pricing
        icon: arrowRight
        iconPosition: right
        style: link
        type: Link
    media:
      type: FormBlock
      elementId: contact-form
      submitButton:
        type: SubmitButtonFormControl
        label: Send request
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
          label: Project
          hideLabel: true
          placeholder: Launch, campaign, or story
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
          - pt-18
          - pb-18
          - pl-12
          - pr-12
seo:
  metaTitle: Ayberk Aktürk — Cinematic Videographer
  metaDescription: One-page portfolio for Ayberk Aktürk, a Vancouver-based cinematographer creating refined brand films, documentaries, and showreels.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
