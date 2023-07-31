---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  # old one looks better
  # https://github.com/wowchemy/wowchemy-hugo-themes/blob/main/modules/wowchemy/layouts/partials/blocks/v1/about.html
  - block: v1/about 
    id: about
    Params:
      author: admin
  - block: collection
    id: publications
    content:
      title: Work In Progress
      filters:
         folders:
          - publication
    design:
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Working Papers
      filters:
        folders:
          - project
    design:
      columns: '1'
      view: showcase
---
