---
title: Home
slug: /
sections:
  - type: GenericSection
    elementId: hero
    colors: bg-light-fg-dark
    badge:
      label: Portfolio 2025
      color: text-primary
      type: Badge
    title:
      text: Ayberk Aktürk
      color: text-dark
      type: TitleBlock
    subtitle: Software Engineer · Videographer
    text: |-
      I build calm, useful tools and cinematic films for founders who value
      restraint. Clean UI, honest lighting, and measurable outcomes—nothing
      bloated.
    actions:
      - label: View my work
        altText: Jump to selected work
        url: /#work
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
      - label: Watch the reel
        altText: Jump to film section
        url: /#films
        showIcon: true
        icon: play
        iconPosition: right
        style: secondary
        type: Link
    media:
      url: /images/main-hero.jpg
      altText: Minimal workspace with camera and laptop
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
  - type: GenericSection
    elementId: studio
    colors: bg-neutral-fg-dark
    badge:
      label: Studio snapshot
      color: text-primary
      type: Badge
    title:
      text: Calm tools, cinematic taste
      color: text-dark
      type: TitleBlock
    text: |-
      Eight years across startups and film sets taught me to keep briefs short,
      teams aligned, and deliveries obsessively polished. I take on one build or
      film suite at a time so every detail feels intentional.
    media:
      url: /images/hero2.svg
      altText: Abstract portfolio illustration
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
      text: What I deliver
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Product, design, and film support without the agency noise.
    items:
      - type: FeaturedItem
        title: Product Engineering
        text: >-
          Technical direction and native-feeling web apps using Next.js,
          TypeScript, and thoughtful systems.
        image:
          url: /images/icon1.svg
          altText: Icon representing engineering
          type: ImageBlock
        colors: bg-light-fg-dark
      - type: FeaturedItem
        title: Experience Design
        text: >-
          Minimal UI, motion, and copy that feel like Apple—not enterprise UX debt.
        image:
          url: /images/icon2.svg
          altText: Icon representing design
          type: ImageBlock
        colors: bg-light-fg-dark
      - type: FeaturedItem
        title: Film Direction
        text: >-
          Narrative spots, product films, and BTS cuts with soft light and tactile sound.
        image:
          url: /images/icon3.svg
          altText: Icon representing cinematography
          type: ImageBlock
        colors: bg-light-fg-dark
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pb-16
          - pl-10
          - pr-10
  - type: FeaturedItemsSection
    elementId: work
    title:
      text: Selected work
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Partnerships across health, fintech, and storytelling.
    items:
      - type: FeaturedItem
        title: Atlas OS
        subtitle: Systems dashboard for a biomedical startup
        text: >-
          Led product engineering and visual direction; designed a modular UI
          kit, delivered 40% faster load times, and produced a launch film for investors.
        image:
          url: /images/abstract-feature1.svg
          altText: Atlas OS preview
          type: ImageBlock
        actions:
          - label: Request a walkthrough
            url: mailto:hello@ayberkakturk.com?subject=Atlas%20OS
            style: secondary
            icon: arrowRight
            iconPosition: right
            type: Link
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pb-8
              - pl-8
              - pr-8
            borderRadius: x-large
      - type: FeaturedItem
        title: Vise Markets
        subtitle: Trading intelligence platform
        text: >-
          Architected a multi-tenant Next.js app with live market video
          explainers; directed product film shot on FX6 with custom lighting rig.
        image:
          url: /images/abstract-feature2.svg
          altText: Vise app preview
          type: ImageBlock
        actions:
          - label: Explore the case study
            url: /blog/case-study-1
            style: secondary
            icon: arrowRight
            iconPosition: right
            type: Link
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pb-8
              - pl-8
              - pr-8
            borderRadius: x-large
      - type: FeaturedItem
        title: Telus Health Films
        subtitle: Cinematic stories for clinical teams
        text: >-
          Suite of tactile 4K films pairing gimbal motion with macro optics.
        image:
          url: /images/abstract-feature3.svg
          altText: Telus Health still frame
          type: ImageBlock
        actions:
          - label: Watch a teaser
            url: /#films
            style: secondary
            icon: play
            iconPosition: right
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
    elementId: films
    colors: bg-light-fg-dark
    badge:
      label: Film & motion
      color: text-primary
      type: Badge
    title:
      text: 2025 showreel
      color: text-dark
      type: TitleBlock
    subtitle: Hybrid of RED + Sony FX6 footage, practical lighting, and tactile sound design.
    text: |-
      Shot across Vancouver, Istanbul, and Lisbon. Intimate product shots,
      docu-style interviews, and atmospheric cityscapes. Audio mixed in Dolby Atmos.
    actions:
      - label: Open on YouTube
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
      label: Collaborate
      color: text-primary
      type: Badge
    title:
      text: Tell me about your next launch
      color: text-dark
      type: TitleBlock
    subtitle: I take on one product build or film suite at a time to stay sharp.
    text: |-
      Send a quick brief, mood board, or even a voice note. I’ll reply within
      two business days with availability and a POV on how we can make it
      memorable.
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
          label: Project type
          hideLabel: true
          placeholder: What are we building or filming?
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
  metaTitle: Ayberk Aktürk — Software Engineer & Videographer
  metaDescription: Portfolio for Ayberk Aktürk, a Vancouver-based software engineer and videographer crafting serene digital products and cinematic films.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
