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
        price: $19.99
        details: We Won't Steal
        description: >
          Not sure if you want to commit? Here's a small trial of our product to
          help you decide!

          For only ***`$20`*** you can get ***2 containers*** with ***10 tablets
          each***, allowing you to take Teablet for a test drive before you come
          back to buy more.

          And you ***will*** come back.
        features: []
        image:
          type: ImageBlock
          url: /images/image_2025-06-19_033903595.png
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
        title: '"Okay, I Kinda Like It"'
        price: $99.99
        details: Your Credit Card Information
        description: >
          Getting a little greedy now, are we? No worries. Teablet's got you
          covered regardless of how bad your tea cravings and caffeine addiction
          gets. Get your hands on ***10 WHOLE containers*** with ***10 Teablets
          each***, for a grand total of ***100 Teablets*** just for
          ***`$99.99`***. ***Ready to step it up a notch? ;)***
        features: []
        image:
          type: ImageBlock
          url: /images/image_2025-06-19_033808445.png
          altText: Pricing plan 2
        actions:
          - type: Button
            label: GIMME
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
        title: '"I NEED IT TO LIVE"'
        price: Custom
        details: (Trust)
        description: >
          Now that you've come to terms with your love for Teablet, ***YOU***
          get to decide exactly how much you want from us. Any quantity can be
          ordered at your discretion, pricing will scale according to quantity
          with a starting price of ***$9*** per container of ***10 Teablets***.
        features: []
        image:
          type: ImageBlock
          url: /images/image_2025-06-19_034139252.png
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
  - type: CarouselSection
    subtitle: This is a subtitle
    items:
      - type: FeaturedItem
        title: >-
          “Teablet changed my life, I've never been able to humour my caffeine
          addiction this easily before! Now I can be an addict anywhere and
          everywhere!”
        tagline: We don't glaze our own product. Listen to our customers instead;
        subtitle: 'Maria Hossain, Cox''s Bazar'
        text: >
          Sheesh man, love the product glaze but you might wanna get that
          caffeine addiction in check, Maria. We're rooting for you!
        image:
          type: ImageBlock
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: >-
          “Quote from some important person goes right here. I love using
          Netlify.”
        tagline: We don't glaze our own product. Listen to our customers instead;
        subtitle: 'Zulfikar Ali Bhutto, Karachi'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/img-placeholder-dark.png
          altText: Jane Doe
          styles:
            self:
              borderRadius: full
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
    variant: next-prev-nav
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
isDraft: false
---
