---
title: Home
slug: /
sections:
  - type: GenericSection
    elementId: hero
    colors: bg-light-fg-dark
    badge:
      label: Director & Cinematographer
      color: text-primary
      type: Badge
    title:
      text: Ayberk Aktürk
      color: text-dark
      type: TitleBlock
    subtitle: Films for brands, founders, and artists who care about feeling as much as fidelity.
    text: |-
      I design light, capture motion, and edit with intention. Every project is a one-off crafted end-to-end—from scouting to final color—so the story stays honest and the frames stay calm.
    actions:
      - label: Watch the reel
        altText: Jump to the reel
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
      altText: Ayberk shooting on set
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
          - pl-16
          - pr-16
  - type: FeaturedItemsSection
    elementId: work
    title:
      text: Selected films
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Launch campaigns, short documentaries, and intimate brand stories shot on RED + FX6.
    items:
      - type: FeaturedItem
        title: "Nacre — Product Story"
        subtitle: Tactile macro shots + minimal voiceover
        text: >-
          Directed, lit, and edited a silent film for a design studio. Macro
          glass, soft key, and custom foley build a serene rhythm in 90 seconds.
        image:
          url: /images/abstract-feature1.svg
          altText: Product film frames
          type: ImageBlock
        actions:
          - label: Request private link
            url: mailto:hello@ayberkakturk.com?subject=Nacre%20Film
            style: secondary
            icon: arrowRight
            iconPosition: right
            type: Link
        colors: bg-neutralAlt-fg-dark
      - type: FeaturedItem
        title: "Transit — Short Documentary"
        subtitle: Shot in Lisbon & Istanbul
        text: >-
          Dual-language mini doc following two dancers. Handheld anamorphic,
          available light, and layered field recordings carry the story.
        image:
          url: /images/abstract-feature2.svg
          altText: Documentary frames
          type: ImageBlock
        colors: bg-neutralAlt-fg-dark
      - type: FeaturedItem
        title: "Forma — Launch Film"
        subtitle: Brand anthem for a VC-backed startup
        text: >-
          Built a hybrid set blending practical haze with LED walls. Delivered a
          45 second hero cut plus looping cuts for product screens.
        image:
          url: /images/abstract-feature3.svg
          altText: Launch film frames
          type: ImageBlock
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
    elementId: approach
    colors: bg-light-fg-dark
    badge:
      label: Approach
      color: text-primary
      type: Badge
    title:
      text: Quiet sets, intentional edits
      color: text-dark
      type: TitleBlock
    text: |-
      1. **Listen.** Define mood, pacing, and purpose in one short workshop—no decks, just references.

      2. **Shape.** Scout light, lock movement, and build a micro-crew. Still frames and lighting diagrams keep everyone aligned.

      3. **Polish.** Grade in DaVinci, finish sound in Atmos, and deliver ready-to-share masters plus cutdowns.
    styles:
      self:
        flexDirection: col
        padding:
          - pt-16
          - pb-12
          - pl-12
          - pr-12
  - type: GenericSection
    elementId: reel
    colors: bg-neutral-fg-dark
    badge:
      label: 2025 Reel
      color: text-primary
      type: Badge
    title:
      text: Two minutes of recent frames
      color: text-dark
      type: TitleBlock
    subtitle: Filmed across Vancouver, Istanbul, Lisbon, and remote mountain ranges.
    actions:
      - label: Watch on Vimeo
        url: https://www.youtube.com/
        icon: play
        iconPosition: right
        style: secondary
        type: Link
    media:
      title: Ayberk Aktürk Reel
      url: /images/placeholder-video.mp4
      autoplay: true
      loop: true
      muted: true
      controls: true
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
      type: VideoBlock
    styles:
      self:
        flexDirection: col
        padding:
          - pt-16
          - pb-16
          - pl-16
          - pr-16
  - type: GenericSection
    elementId: contact
    colors: bg-light-fg-dark
    badge:
      label: Booking
      color: text-primary
      type: Badge
    title:
      text: Tell me about the story
      color: text-dark
      type: TitleBlock
    subtitle: I take on one commission at a time to keep the process personal.
    text: |-
      Share a few lines about the mood, location, and timeline. I’ll reply within two business days with availability and a first creative direction.
    media:
      type: FormBlock
      elementId: contact-form
      submitButton:
        type: SubmitButtonFormControl
        label: Send treatment request
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
          placeholder: Contact email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: project
          label: Project type
          hideLabel: true
          placeholder: Shoot details, dates, mood
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
          - pt-16
          - pb-16
          - pl-16
          - pr-16
seo:
  metaTitle: Ayberk Aktürk — Director & Cinematographer
  metaDescription: One-page portfolio for Ayberk Aktürk, a Vancouver-based videographer crafting launch films, short docs, and branded stories with intentional light and sound.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
