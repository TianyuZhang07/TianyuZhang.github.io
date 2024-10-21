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
      title: '📚 研究简介'
      subtitle: ''
      text: |-
        电气化交通与能源系统深度融合，对提升两大系统运营效率，实现出行便利、削峰填谷、节能减排目标具有重要作用。我们研究旨在针对交通、电力和能源耦合系统开展，构建能够准确管理出行需求、站点补给和能源供应的协同运作体系。为此，我们立足微观、中观和宏观层面，开展多网络耦合和多主体互动的交通和能源系统协同运作、优化决策和可持续发展研究。目前已陆续开展了有关高速公路“风-光-储-充”网络、出租车换电网络和城市V2G响应与调度系统的交能融合案例研究。
        
        学术成果方面，已公开发表论文8篇，参与国际研讨会1次，授权/公开国家发明专利3项，软著2项。其中，以第一作者/通讯作者发表中科院1区SCI论文5篇，以第二作者发表中科院1区SCI论文1篇，EI论文1篇。研究成果发表在交通和能源领域的TOP期刊上，包括TR-Part A/D，IEEE Transactions on Transportation Electrification，Computer-Aided Civil and Infrastructure Engineering，Applied Energy。科研项目方面，主持中央高校基本科研业务2项，参与国家重点研发计划2项，国家自然基金项目2项，其余省部级或横向项目3项。        
        
        未来，我们将继续在交通与能源融合领域进行深耕，将智能电网和交通基础设施网有效结合，智慧交通和能源管理深度融合，开拓高速公路、城市道路和铁路等领域的交能融合新模式和新业态，助力交通领域实现“双碳”目标。我们衷心希望与各学科专家、学者的交流与合作，积极探索和解决交通、电力与经济交叉领域内的复杂问题。让我们共同推动交能融合的发展和创新!
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: 研究方向
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
      title: 研究成果
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
      title: 科研项目
      subtitle: My subtitle
      text: |
        •	主持-中央高校基本科研业务-多网络耦合的高速公路充电网络协同运作与优化决策研究 2023-2025     
        •	主持-中央高校基本科研业务-基于多用户动态交通分配的高速公路电动汽车充电站布局优化研究 2020-2022     
    design:
      columns: '1'
  - block: markdown
    content:
      title: 工作/学习经历
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
