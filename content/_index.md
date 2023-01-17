---
date: "2022-10-24"
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  id: about
  
- block: features
  content:
    items:
    - description: 100%
      icon: r-project
      icon_pack: fab
      name: R
    - description: 100%
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: 10%
      icon: camera-retro
      icon_pack: fas
      name: Photography
    title: Skills

- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: Mississippi State University
      company_logo: MSSTATE
      company_url: "https://www.msstate.edu/"
      date_end: ""
      date_start: "2021-01-01"
      description: |2-
        Majored in Psychology and minored in Statistics and Cognitive Science.
          * Collected data using the Five Factor model form an pool of 43 undergraduates.
          * Analyzed a SNAP food assistance data set of over 1.5 million observations for anomalies
      location: Starkville, MS
      title: Undergraduate Student
      
    - company: Jackson Academy
      company_logo: JA
      company_url: ""
      date_end: "2019-05-17"
      date_start: "2016-08-01"
      description: Took honors classes and was given an award for academic excelence in the fields of Psychology
      location: Jackson, MS
      title: High school Student
    title: Experience
  design:
    columns: "2"
    
- block: accomplishments
  content:
    date_format: Jan 2006
    items:
    - certificate_url: https://www.coursera.org
      date_end: ""
      date_start: "2021-01-25"
      description: ""
      organization: Coursera
      organization_url: https://www.coursera.org
      title: Neural Networks and Deep Learning
      url: ""
    - certificate_url: https://www.edx.org
      date_end: ""
      date_start: "2021-01-01"
      description: Formulated informed blockchain models, hypotheses, and use cases.
      organization: edX
      organization_url: https://www.edx.org
      title: Blockchain Fundamentals
      url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    - certificate_url: https://www.datacamp.com
      date_end: "2020-12-21"
      date_start: "2020-07-01"
      description: ""
      organization: DataCamp
      organization_url: https://www.datacamp.com
      title: Object-Oriented Programming in R
      url: ""
    subtitle: null
    title: Accomplish&shy;ments
  design:
    columns: "2"
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="demo" >}}'
    title: Gallery
  design:
    columns: "1"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
- block: collection
  content:
    filters:
      folders:
      - event
    title: Recent & Upcoming Talks
  design:
    columns: "2"
    view: compact
  id: talks
- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"
- block: contact
  content:
    address:
      city: Jackson
      country: United States
      country_code: US
      postcode: "39216"
      region: MS
      street: 
    appointment_url: https://calendly.com/charles-b-williams
    autolink: true
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/Chwill713
      name: DM Me
    - icon: video
      icon_pack: fas
      link: https://zoom.com
      name: Zoom Me
    directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    email: test@example.org
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    phone: 601-566-3505
    subtitle: null
    text: If you ever feel like contacting me, here are some ways that you can do so!
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
