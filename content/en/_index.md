---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "2rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume-zh.pdf
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
        The deep integration of electrified transportation and energy systems plays an important role in enhancing the operational efficiency of the two systems and realizing the goals of travel convenience, peak shaving and valley filling, energy saving, and emission reduction. Our research is carried out for the coupled transportation, power, and energy system to develop a synergistic operation system that can accurately manage travel demand, station replenishment, and energy supply. Accordingly, at the micro-, meso- and macro-levels, we research synergistic operations, optimal decision-making, and sustainable development of transportation and energy systems with multi-network coupling and multi-agent interaction. We have successively carried out case studies on the Highway charging network with the wind-photovoltaic-energy storage, the Taxi battery swapping network, the Urban V2G (Vehicle-to-grid) response and dispatch system.
        
        Regarding academic achievements, I have published 8 academic papers, participated in 1 international symposium, authorized/publicized 3 national invention patents, and 2 soft writings. Among them, 5 SCI have been published as the first author/corresponding author in CAS Area 1, and 1 SCI in CAS Area 1 and 1 EI has been published as the second author and supervisor's first work. Research results have been published in TOP journals in transportation and energy, including TR-Part A/D, IEEE Transactions on Transportation Electrification, Computer-Aided Civil and Infrastructure Engineering, and Applied Energy. Regarding research projects, I have presided over 2 Fundamental Research Funds for the Central Universities and participated in 2 Key Programs of National Natural Foundation projects, 2 National Natural Foundation projects, and 3 provincial & ministerial projects.        
        
        In the future, we will continue to work deeply in transportation and energy integration. To help the transportation sector achieve the goal of “Double carbon,” we will develop new modes and new business models for transportation and energy integration in the fields of highways, urban roads, and railroads by effectively combining the smart grid and transportation infrastructure network and deeply integrating intelligent transportation and energy management. We sincerely hope to communicate and cooperate with experts and scholars from various disciplines to actively explore and solve complex problems within the cross-field of transportation, electricity, and economy. Let’s promote the development and innovation of transportation and energy integration together!    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Research Highlights
      filters:
        folders:
          - research
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: false
        # featured_only: false
    design:
      view: citation
  - block: markdown
    id: projects
    content:
      title: Projects
      # subtitle: My subtitle
      text: |
        •	Project Chair-Fundamental Research Funds for the Central Universities-Research on cooperative operation and decision-making of highway charging network with multi-network coupling 2023-2025     
        •	Project Chair-Fundamental Research Funds for the Central Universities-Research on optimizing the layout of highway electric vehicle charging station based on multi-user dynamic traffic assignment 2020-2022     
    design:
      columns: '1'
  - block: markdown
    content:
      title: Experience
  - block: resume-experience
    id: experience
    content:
      username: admin
  
  
  
  
  # design:
    #   # Hugo date format
    #   date_format: 'January 2006'
    #   # Education or Experience section first?
    #   is_education_first: false
  # - block: resume-skills
  #   content:
  #     title: Skills & Hobbies
  #     username: admin
  #   design:
  #     show_skill_percentage: false
  # - block: resume-awards
  #   content:
  #     title: Awards
  #     username: admin


      
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  # - block: cta-card
  #   demo: true # Only display this section in the Hugo Blox Builder demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

  #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!
        
  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---
