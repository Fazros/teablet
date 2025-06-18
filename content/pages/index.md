---
title: Home
slug: /
sections:
  - type: ImageGallerySection
    subtitle: ''
    images:
      - type: ImageBlock
        altText: Vise logo
        elementId: ''
      - type: ImageBlock
        altText: Telus logo
        elementId: ''
      - type: ImageBlock
        altText: Contentful logo
        elementId: ''
      - type: ImageBlock
        url: /images/image_2025-06-19_023715507.png
        altText: Image alt text placeholder
        elementId: ''
        styles:
          self:
            borderRadius: medium
      - type: ImageBlock
        altText: Sanity logo
        elementId: ''
      - type: ImageBlock
        altText: Rangle logo
        elementId: ''
    elementId: ''
    motion: static
    colors: bg-light-fg-dark
    styles:
      self:
        margin:
          - mt-0
          - ml-0
          - mb-0
          - mr-0
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: ImageGallerySection
    subtitle: Tea like never before
    images:
      - type: ImageBlock
        url: /images/image_2025-06-19_024649920.png
        altText: Empathy logo
        elementId: ''
      - type: ImageBlock
        altText: Wellster logo
        elementId: ''
      - type: ImageBlock
        altText: Vise logo
        elementId: ''
      - type: ImageBlock
        altText: Telus logo
        elementId: ''
      - type: ImageBlock
        altText: Contentful logo
        elementId: ''
      - type: ImageBlock
        url: /images/image_2025-06-19_024726676.png
        altText: Sanity logo
        elementId: ''
      - type: ImageBlock
        altText: Rangle logo
        elementId: ''
    elementId: ''
    motion: move-to-left
    colors: bg-neutral-fg-dark
    styles:
      self:
        margin:
          - mt-0
          - ml-0
          - mb-0
          - mr-0
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
        fontWeight: 700
        fontStyle: italic
  - type: PricingSection
    title:
      type: TitleBlock
      text: Flexible Pricing
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: This is the subtitle for the pricing section
    plans:
      - type: PricingPlan
        title: '"I Just Wanna Try It"'
        price: $20
        details: No Credit Card Required
        description: >
          Not sure if you want to commit? Here's a small trial of our product to
          help you decide!

          For only $20 you can get 2 containers with 10 tablets each, allowing
          you to take Teablet for a test drive before you come back to buy more.

          And you ***will*** come back.
        features: []
        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
          altText: Pricing plan 1
        actions:
          - type: Button
            label: I'll Try
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
      - type: PricingPlan
        title: Professional
        price: $99
        details: Cash On Delivery Works Too
        description: >-
          Sed ut perspiciatis unde omnis, iste natus error sit voluptatem
          accusantium doloremque.
        features:
          - Feature one
          - Feature two
          - Feature three
          - Feature four
        image:
          type: ImageBlock
          url: /images/abstract-feature2.svg
          altText: Pricing plan 2
        actions:
          - type: Button
            label: Try for free
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
      - type: PricingPlan
        title: Enterprise
        price: Custom
        details: We Won't Steal Your Credit Card Info
        description: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam.
        features:
          - Feature one
          - Feature two
          - Feature three
          - Feature four
          - Feature five
        image:
          type: ImageBlock
          url: /images/abstract-feature3.svg
          altText: Pricing plan 3
        actions:
          - type: Button
            label: Contact us
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
