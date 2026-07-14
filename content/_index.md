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
        - name: Multiphysics Simulation
          description: COMSOL, ABAQUS, and LS-DYNA modeling
          icon: cogs
          icon_pack: fas
        - name: Machine Learning & Data Analysis
          description: Python, MATLAB, and data-driven manufacturing models
          icon: chart-line
          icon_pack: fas
        - name: Composite Manufacturing
          description: Pultrusion, BMC, hot pressing, hand layup, and vacuum infusion
          icon: industry
          icon_pack: fas
        - name: Materials Characterization
          description: DMA, DSC, DIC, SEM, and laser profilometry
          icon: microscope
          icon_pack: fas
        - name: Sustainable Materials
          description: Recycled carbon fiber composites and functional coatings
          icon: recycle
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
          date_start: '2024-09-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Developing COMSOL multiphysics models of spray deposition to improve coating uniformity in scalable solid-state battery processing
              * Designing dry processing workflows for solid-state battery components and fabricating cells with 93% Coulombic efficiency
              * Building LS-DYNA crash simulations for pultruded carbon fiber composite battery separators in electric-vehicle structures
              * Applying machine-learning methods to optimize fiber distribution, composite architecture, and manufacturing parameters
        - title: Research Assistant
          company: University of Washington, Seattle
          company_url: ''
          company_logo: UW
          location: Seattle
          date_start: '2023-06-01'
          date_end: '2024-06-15'
          description: |2-
              Responsibilities included:

              * Fabricated recycled carbon fiber composites through bulk molding compound (BMC) processing and evaluated laminate quality
              * Used digital image correlation and convolutional neural networks to analyze and predict composite failure behavior
              * Built Python-based machine-learning models on approximately 100 experimental samples to connect processing conditions with performance
              * Characterized thermoplastic prepregs through DMA stress relaxation, thermal ramp, and four-point bending tests
        - title: Research Assistant
          company: University of Nottingham, Ningbo China
          company_url: ''
          company_logo: UNNC
          location: Ningbo
          date_start: '2020-06-01'
          date_end: '2022-06-15'
          description: |2-
              Responsibilities included:

              * Designed recycled and hybrid fiber composites for sustainable structural applications
              * Integrated natural fibers, fire-retardant systems, and functional coatings to tune mechanical, thermal, and electrical properties
              * Developed ABAQUS finite element models of wing-structured flexible sensors and refined model accuracy through boundary-condition validation
    design:
      columns: '2'
  - block: accomplishments
    id: Ac
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: Accomplishments
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
        - certificate_url: ''
          date_end: ''
          date_start: ''
          description: Outstanding Participant in FoSE Elite Project; First Prize in Online Yangming Cultural Study and Knowledge Contest; Communication and Marketing Campaign Volunteer; AIESEC Volunteer.
          organization: Selected Honors and Service
          organization_url: ''
          title: Honors and Volunteer Service
          url: ''
    design:
      columns: '2'
  - block: markdown
    id: gallery
    content:
      title: Photo Gallery
      text: |
        A collection of my recent photography.

        ![Image 1](/wl/uploads/2024.jpg)

  - block: collection
    id: featured
    content:
      title: Recent Publications & Presentations
      text: |-
        Selected publications, presentations, and current manuscripts.
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
        Feel free to contact me if you have any questions.
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
