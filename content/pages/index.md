---
type: PageLayout
title: Home
colors: colors-e
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: ''
    subtitle: '$ awk ''/ Justin McKay / {f=1} f'' /dev/portfolio'
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
        borderRadius: none
        borderStyle: none
        borderColor: border-dark
        borderWidth: 0
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
    text: >
      ##### Welcome to my portfolio and blog!


      Dive into my personal coding projects and experiments. From AI innovations
      to classic games like Tetris, my code portfolio showcases a diverse range
      of projects.


      Explore my blog for insights and perspectives as I navigate the world of
      science, tech, AI, and beyond. You'll find articles, reviews, editorials,
      and thought pieces on a variety of topics.


      Interested in collaborating? Check out my resume and contact information.
      Let's connect and start working together today!
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projects
    title: ''
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-b
    subtitle: Featured Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: ''
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
    text: |
      HIRING? Need IT work by the hour? Want to collaborate on something cool?

      Get in touch now!
---
