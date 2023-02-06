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
    - description: Overleaf
      icon: "overleaf"
      icon_pack: ai
      name: Overleaf      
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
          * I am the current Vice President for the MSU Chess Club
          * Analyzed a SNAP food assistance data set of over 1.5 million observations for anomalies
      location: Starkville, MS
      title: Undergraduate Student
      
    - company: Jackson Academy
      company_logo: JA
      company_url: ""
      date_end: "2019-05-17"
      date_start: "2016-08-01"
      description: Took honors classes and was awarded for academic excellence in the fields of Psychology and Sociology
      location: Jackson, MS
      title: High school Student
    title: Experience
  design:
    columns: "2"
    
  
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
      - blog
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
  

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
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    phone: 601-566-3505
    subtitle: null
    text: 
    title: Contact Me!
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
