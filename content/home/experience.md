---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Graduate Research Assistant 
    company: The University of Texas at Austin 
    company_url: ''
    company_logo: 'ut'
    location: Austin, TX
    date_start: '2023-01-12'
    date_end: ''
    description: |4-
        Developing the first linguistically driven framework for automatic evaluation of QuD (Questions under Discussion) parsers and also exploring QuD ranking. The 
        applications include text simplification and summarization, guided text writing and improving conversational AI
  - title: Software Engineer Intern
    company: Hewlett Packard Enterprise
    company_url: ''
    company_logo: 'hpe'
    location: San Jose, CA
    date_start: '2023-05-22'
    date_end: '2023-08-11'
    description: |4-
        * Automated the workflow of the namespace index module using C++ based customized gRPC services which targeted large workloads, thereby reducing manual testing hours by 60%
        * Integrated a standalone centralized Elastic-search based repository for storing IO workloads with the common feature library for improved search ability while reproducing specific customer use-cases or triaging performance issues
        * Contributed to 4 different code repositories by cross-functionally collaborating with 5 different teams and stakeholders 
        * Received 2 HPE Star Points as a recognition of my work exceeding expectations
  - title: Summer Analyst
    company: Goldman Sachs
    company_url: ''
    company_logo: 'goldman'
    location: Bangalore, India
    date_start: '2021-06-05'
    date_end: '2021-07-12'
    description: |4-
        * Engineered an event creation and management platform, saving 10,000+ man hours for budgeting and approvals
        * Integrated new front-end and middleware with existing legacy backend which was used by 100+ internal departments      
        * Designed test cases for unit testing and exposed to building the CI/CD pipeline for deploying production-level code 
        * Collaborated cross-functionally with UI/UX teams and stakeholders to design a dashboard surfacing business insights
  - title: Undergraduate Research Assistant 
    company: COE-CNDS Lab 
    company_url: ''
    company_logo: 'coe'
    location: Mumbai, India
    date_start: '2019-12-05'
    date_end: '2021-12-12'
    description: |4-
        
        * Developed a novel approach of ‘bot-score’ to detect bots in Twitter with an F1 of 97.3%
        * Performed feature engineering and statistical data analysis to understand the influence of bots in trending a hashtag      
        * Examined the influence of bots by detecting communities with bot representations using the Louvain algorithm
        * Developed a FLASK based web-app to make an easy-go-access interface to ascertain a Twitter user’s bot probability
  - title: Artificial Intelligence Intern
    company: Yozu
    company_url: ''
    company_logo: 'iitb'
    location: IIT Bombay, Mumbai, India
    date_start: '2020-12-05'
    date_end: '2021-01-12'
    description: |2-
        * Developed an AI-based conversational bot using state machine approach with a reduced latency of 13%.
        * Devised an LSTM-based Question Matching algorithm for answering mid-conversation user queries.
  - title: Machine Learning Intern
    company: TechnoPurple Tracking
    company_url: ''
    company_logo: 'technopurple'
    location: Mumbai, India
    date_start: '2020-05-05'
    date_end: '2020-07-12'
    description: |2-
        * Implemented Laplacian filter to separate dark and blur images to examine site cleanliness for Emrill Services LLC(Dubai).
        * Engineered a template matching using OpenCV & OCR-based algorithm to determine success of a rally of Bhartiya Janta Party     (the current ruling party of India), thereby resulting in reduction of false positive and false negative counts by 67%.

design:
  columns: '2'
---
