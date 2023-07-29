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
      view: citation
      columns: '2'
  # - block: portfolio
  #  id: projects
  #  content:
  #    title: Projects
  #    filters:
  #      folders:
  #        - project
  #    # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #   # default_button_index: 0
  #    # Filter toolbar (optional).
  #    # Add or remove as many filters (`filter_button` instances) as you like.
  #    # To show all items, set `tag` to "*".
  #    # To filter by a specific tag, set `tag` to an existing tag name.
  #    # To remove the toolbar, delete the entire `filter_button` block.
  #    # buttons:
  #    #  - name: All
  #    #    tag: '*'
  #    #  - name: Deep Learning
  #    #    tag: Deep Learning
  #    #  - name: Other
  #    #    tag: Demo
  #  # design:
  #    # Choose how many columns the section has. Valid values: '1' or '2'.
  #   # columns: '1'
  #  #  view: showcase
  #    # For Showcase view, flip alternate rows?
  #  #  flip_alt_rows: false 
---
