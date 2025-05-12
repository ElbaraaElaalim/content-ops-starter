---
type: PageLayout
title: Artist Statement
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Artist Statement
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: My Artist Statement
    text: >
      I create art about landscapes, different worlds, and ruins because I love
      how nature and old buildings tell stories. When I see ruins or places that
      have been forgotten, I think about what they used to be like and how time
      or nature has changed them. My artwork focuses on showing the beauty of
      nature mixed with the past, especially through old or broken down
      structures.


      I use different materials to make my art, like paint and textures to show
      how nature takes over old structures and how both are connected. I want my
      art to make people think about how things change over time, and how most
      ruined places can still hold some beauty and meanings in them.
    actions:
      - type: Button
        label: Get started
        altText: ''
        url: /elbaraaportfolio.netlify.app/
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
    colors: bg-neutral-fg-dark
    backgroundImage:
      type: BackgroundImage
      url: /images/abstract-background.svg
      altText: Placeholder image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
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
      text: My Work
      color: text-dark
      styles:
        self:
          textAlign: center
    people:
      - content/data/person1.json
      - content/data/person2.json
      - content/data/person3.json
      - content/data/person4.json
      - content/data/person5.json
      - content/data/person6.json
    actions: []
    variant: three-col-grid
    colors: bg-light-fg-dark
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
slug: careers
seo:
  type: Seo
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify.
  metaTags: []
---
