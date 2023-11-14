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
        - name: Python
          description: 60%
          icon: python
          icon_pack: fab
        - name: Statistics
          description: 50%
          icon: chart-line
          icon_pack: fas
        - name: Soft Skills
          description: 80%
          icon: users
          icon_pack: fas
        - name: Illustration
          description: 60%
          icon: paint-brush
          icon_pack: fas
  - block: experience
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
        - title: Teacher assistant
          company: Math center
          company_url: ''
          company_logo: org-gc
          location: Moscow
          date_start: '2022-09-29'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Designing study materials
              * Organising lesson
        - title: Student
          company: RUDN
          company_url: ''
          company_logo: org-x
          location: Moscow
          date_start: '2019-09-01'
          date_end: ''
          description: Studying applied mathematics and informatics.
    design:
      columns: '2'
  - block: accomplishments
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
        - certificate_url: 
          date_end: ''
          date_start: '2023-06-15'
          description: BS diploma with honours in Applied Mathematics and Informatics
          organization: RUDN
          organization_url: ''
          title: Applied Mathematics and Informatics
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2023-06-15'
          description: Translators diploma in mathematics
          organization: RUDN
          organization_url: ''
          title: English - Russian transtalion 
          url: ''
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
---
