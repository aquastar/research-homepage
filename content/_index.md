---
# Leave the homepage title empty to use the site title
title: Zhiqian Chen
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: collection
    id: featured
    content:
      title: Pinned Work
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card

---
