---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
#   - block: skills
#     content:
#       title: Skills
#       text: ''
#       # Choose a user to display skills from (a folder name within `content/authors/`)
#       username: admin
#     design:
#       columns: '1'

#   - block: collection
#     id: publications
#     content:
#       title: Publications
#     #   text: |-
#     #     {{% callout note %}}
#     #     Quickly discover relevant content by [filtering publications](./publication/).
#     #     {{% /callout %}}
#     #   # Choose how many pages you would like to display (0 = all pages)
#     #   count: 3
#       filters:
#         folders:
#           - publication
#         exclude_featured: true
#     design:
#       columns: '2'
#       view: compact

  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Data Science, Manager
          company: Lazada, Alibaba
          company_url: 'https://www.lazada.com/en/'
          company_logo: org-lzd
          location: Singapore
          date_start: '2021-06-01'
          date_end: '2024-01-12'
        - title: Data Science, Intern
          company: Lazada, Alibaba
          company_url: 'https://www.lazada.com/en/'
          company_logo: org-lzd
          location: Singapore
          date_start: '2020-06-01'
          date_end: '2021-06-01'
    design:
      columns: '2'

#   - block: collection
#     id: posts
#     content:
#       title: Recent Posts
#       subtitle: ''
#       text: ''
#       # Choose how many pages you would like to display (0 = all pages)
#       count: 3
#       # Filter on criteria
#       filters:
#         folders:
#           - post
#         exclude_featured: false
#         exclude_future: false
#         exclude_past: false
#         publication_type: ""
#       # Choose how many pages you would like to offset by
#       offset: 0
#       # Page order: descending (desc) or ascending (asc) date.
#       order: desc
#     design:
#       # Choose a layout view
#       view: compact
#       columns: '2'

#   - block: collection
#     id: talks
#     content:
#       title: Recent & Upcoming Talks
#       filters:
#         folders:
#           - event
#     design:
#       columns: '2'
#       view: compact
---
