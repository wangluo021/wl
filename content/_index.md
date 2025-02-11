---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Engineering
          description: 100%
          icon: r-project
          icon_pack: fab
        - name: Science
          description: 70%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 80%
          icon: camera-retro
          icon_pack: fas
  - block: experience
    id: Exp
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Assistant
          company: University of Michigan, Ann Arbor
          company_url: ''
          company_logo: UM
          location: Ann Arbor
          date_start: '2024-07-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Simulation
              * Experiment
              * Machine Learning
        - title: Research Assistant
          company: University of Washington, Seattle
          company_url: ''
          company_logo: UW
          location: Seattle
          date_start: '2023-06-01'
          date_end: '2024-06-15'
          description: Recycling of carbon fiber prepreg was studied with discontinuous fiber compound method (DFC) and bulk molding compound (BMC) methods. The material's parameters were optimized by Gaussian process regression (GPR) machine learning model.
        - title: Research Assistant
          company: University of Nottingham, Ningbo China
          company_url: ''
          company_logo: UNNC
          location: Ningbo
          date_start: '2020-06-01'
          date_end: '2022-06-15'
          description: High performance of recycled carbon fiber was investigated during the undergraduate period with fire retardant application on recycled carbon fiber mat.
    design:
      columns: '2'
  - block: accomplishments
    id: Ac
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: uploads/MSE.pdf
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: University of Washington, Seattle
          organization_url: https://uw.edu
          title: Master of Science
          url: ''
    design:
      columns: '2'
  - block: markdown
    id: gallery
    content:
      title: Photo Gallery
      text: |
        A collection of my recent photography.

        ![Image 1](/lw/uploads/2024.jpg)

  - block: collection
    id: featured
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: lhrwang@umich.edu
      phone: (206)-730-2784
      appointment_url: 'https://calendly.com'
      address:
        street: 2350 Hayward St
        city: Ann Arbor
        region: MI
        postcode: '48109'
        country: United States
        country_code: US
      directions: EECS 3001D
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: DM Me
          link: 'https://www.linkedin.com/in/luohaoran-wang-3a181420b/'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://umich.zoom.us/j/9718275299'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
