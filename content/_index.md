---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-05-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        In my dissertation, I explore the use of video games as virtual simulations of individual real-world experiences in the experimental social sciences. For this, I design role-playing video games specifically tailored for conducting behavioural experiments within an immersive and coherent virtual world. The goal is to understand how video games can be used for experimental manipulations, online data collections, and educational simulations.
        
        My work as a part of the [POLITSOLID](https://achimgoerres.de/politsolid) research team aims to understand the micro-foundations of political solidarities in modern european democracies. We use survey experiments, a simulated virtual state, an international panel survey, and field experiments to explain why and when citizens are willing to shoulder costs for public redistribution.
        
        Feel free to contact me anytime 😃
    design:
      columns: '1'
#  - block: collection
#    id: papers
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      view: article-grid
#      columns: 2
  - block: collection
    id: talks
    content:
      title: Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      fill_image: false
      columns: 2
  - block: collection
    content:
      title: Current Projects
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 1
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-skills
    content:
      title: Skills & Past Projects
      username: admin
    design:
      show_skill_percentage: false
      show_skill_icons: true
      columns: 2
---
