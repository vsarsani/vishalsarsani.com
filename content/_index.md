---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: 
    design:
      background:
        color: black
        text_color_light: true
       
  - block: markdown
    content:
      subtitle: ''
      text: |-
        I am an applied statistician interested in translational genetics. My primary research focus is developing methods to systematically prioritize drug targets and predict disease risk by leveraging large-scale biobanks and multi-omics data (GWAS, expression, proteomics, metabolomics, methylation, etc.)\
 \
        I'm a postdoc at Harvard T.H. Chan School of Public Health. I obtained my Ph.D. in statistics from the University of Massachusetts Amherst. During my Ph.D., I interned in the industry at [Roche](https://www.roche.com/) and [Novartis](https://www.novartis.com/us-en/). Prior to that, I was a computational scientist for 3.5 years at [The Jackson Laboratory](https://www.jax.org/) and obtained MS in Bioinformatics.\
        \
        **Specialties:** Statistical Genetics, Biostatistics, and Computational Biology
    design:
      columns: '1'
  - block: collection
    content:
      title: Updates
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        author: ""
        category: "talk"
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
      columns: '1'
---
