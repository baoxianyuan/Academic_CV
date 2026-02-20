---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Hello! I’m Xianyuan👋
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: experience
  #   content:
  #     title: Experience
  #     # Date format for experience
  #     #   Refer to https://docs.hugoblox.com/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many `experience` items below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: Assistant Engineer
  #         company: Guxian Water Conservancy Co.Ltd
  #         company_url: ''
  #         company_logo: org-gx
  #         location: Shanxi Province
  #         date_start: '2026-07-31'
  #         date_end: ''
  #         description: Participated in the construction of Guanxian Hydropower Station
  #   design:
  #     columns: '2'
  - block: collection
    id: projects
    content:
      title: Projects
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - project
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
  - block: collection
    id: publications
    content:
      title: Publications
      text: # |-
        # {{% callout note %}}
        # Quickly discover relevant content by [filtering publications](./publication/).
        # {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
      view: card
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text:
      # Contact (add or remove contact options as necessary)
      email: xybao@stu.nxu.edu.cn
      appointment_url: 'https://cal.com/xybao/get-in-touch-with-xianyuan'
      address:
        street: 450 West Helanshan RD
        city: Yinchuan
        region: Ningxia
        postcode: '750021'
        country: P.R.China
        country_code: CN
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
