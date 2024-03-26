---
# Leave the homepage title empty to use the site title
title:
date: 2023-04-25
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: accomplishments
    content:
      title: Accomplishments
      items:
        - title: Burp Suite Certified Practitioner
          organization: Portswigger
          organization_url: https://portswigger.net/
          certificate_url: https://portswigger.net/web-security/e/c/f4c96eac5722a99f
          date_start: '2024-01-16'
          date_end: '2029-01-16'
          description: Detect and prove the full business impact of a wide range of common web vulnerabilities
  - block: experience
    content:
      title: Professional Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Technical Advisor
          company: Free Software Foundation Europe
          company_url: 'https://fsfe.org/about/people/index'
          location: Berlin
          date_start: '2022-10-01'
          date_end: '2023-03-31'
          description: |2-
            Organized and led workshops for the [Upcycling Android](https://fsfe.org/activities/upcyclingandroid/) campaign, as well as creating new materials.
            
            Developed a frontend prototype for [TEDective](https://tedective.org/) using Next.js.

        - title: Research Assistant
          company: University of Potsdam
          company_url: 'https://www.uni-potsdam.de/'
          location: Potsdam
          date_start: '2017-04-01'
          date_end: '2021-10-01'
          description: |2-
            Worked as a research assistant at the chair of Prof. Christian Hammer on security analyses for JavaScript.
            
            Developed a static analysis using the SAFE framework that can handle JavaScript Promises in an efficient and sound manner.
            
            Served as a teaching assistant for various lectures\: Software Engineering I/II for 4 semesters and Static Program Analysis for 1 semester.
        - title: Research Intern
          company: Oracle Labs
          company_url: 'https://labs.oracle.com/'
          location: Brisbane
          date_start: '2018-09-01'
          date_end: '2019-03-01'
          description: |2-
            Worked as a research intern at Oracle Labs on test-case generation of Node.js web applications.
            
            Developed a static analysis that generates REST specifications from the source code of an Express-based web application
            
            A grammar-based Fuzzer uncovered seven 0-days in five large Node.js applications using generated specifications.
        - title: Research Assistant
          company: Saarland University
          company_url: 'https://www.uni-saarland.de'
          location: Saarbrücken
          date_start: '2016-07-01'
          date_end: '2017-09-01'
          description: |2-
            Worked as a research assistant at the chair of Prof. Christian Hammer on the [SimoBA](http://www.forschung-it-sicherheit-kommunikationssysteme.de/projekte/simoba) project.
            
            Performed static information flow control using the WALA framework for an Android hybrid app to detect possible security vulnerabilities within the app.
        #- title: Student Tutor
        #  company: Saarland University
        #  company_url: 'https://www.uni-saarland.de'
        #  location: Saarbrücken
        #  date_start: '2015-04-01'
        #  date_end: '2015-10-01'
        #  description: |2-
        #    Served as a tutor for Secure Software Engineering for 1 semester
    design:
      columns: '2'
---
