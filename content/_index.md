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
    - description: R is the language that I'm most familiar with since I've been using it for the past 4 years. It is also what I used to make this website using the blogdown and markdown packages! 
      icon: r-project
      icon_pack: fab
      name: R
    - description: As a social scientist I of course have lots of experience working with SPSS and IBM's internal language "Syntax" Specifically I have used its AMOS software to perform Structural Eqaution Modeling
      icon: SPSS
      icon_pack: custom
      name: SPSS
    - description: It wasn't until I took experimental psychology in my sophomore year that I became obsessed with statistical methods. 
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: I was first introduced to LaTeX by the math department here at Mississippi State but I have been using it for all my academic writing since.
      icon: "overleaf"
      icon_pack: ai
      name: Overleaf  
    - description: I am the vice president of MSU's chess club. I've been in charge of promoting the club, securing funding, and organizing events. Since starting, we've managed to increase attendance from ~8 per meeting to over 30.
      icon: chess
      icon_pack: custom
      name: Chess
    title: Skills
    
   
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: Mississippi State University
      company_logo: MSSTATE
      company_url: "https://www.msstate.edu/"
      date_end: ""
      date_start: "2019-08-21"
      description: |2-
        Majored in Psychology with two minors in Statistics and Cognitive Science.
          * Collected data using the IPIP-NEO form an pool of 43 undergraduate students.
          * Analyzed a SNAP food assistance data set of over 1.5 million observations for anomalies
          * Worked as a research assistant for a NIH funded R15 Grant (Emotion Regulation Study) in a Clinical personality research lab
          * Programmed and launched Alcohol and Impulsivity study using E-Prime and Amazon Turk for researchers
          * Assisted with SPSS syntax for a peer's project on the Antagonistic Triad and Risky Sexual Behaviors 
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
    - name: Blog
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - blog
    title: Portfolio
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
