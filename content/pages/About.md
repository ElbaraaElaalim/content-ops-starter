---
type: PageLayout
title: About Section
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: About Me
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: Special Section
    text: ''
    actions: []
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
  - type: FeaturedPostsSection
    title:
      type: TitleBlock
      text: Featured posts
      color: text-dark
      styles:
        self:
          textAlign: center
    posts:
      - content/pages/blog/life-of-our-development-team.md
      - content/pages/blog/surround-yourself-with-right-people.md
      - content/pages/blog/top-twenty-ways-to-save-time.md
    showThumbnail: true
    showExcerpt: true
    showDate: true
    showAuthor: true
    actions: []
    elementId: ''
    variant: three-col-grid
    colors: bg-light-fg-dark
    hoverEffect: shadow
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
slug: About
seo:
  type: Seo
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify.
  metaTags: []
---
