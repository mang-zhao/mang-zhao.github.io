---
title: Papers
summary: My papers
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: markdown
    content:
      title: 'Note on Authorship'
      subtitle: ''
      text: |-
        Authors are listed in alphabetical order by default, following the convention in cryptography worldwide. 
        
        However, authors are listed by contribution in the works that I collaborate with other Chinese authors, following the convention and policy in the Chinese Crypto community.
    design:
      columns: '1'
  - block: collection
    id: teaching
    content:
      title: Teaching
      filters:
        folders:
          - teaching
    design:
      view: article-grid
      columns: 2
---
