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
        I am an Applied Statistician with a strong background and experience in Human Genetics and Computational Biology. I am currently doing a Statistical Genetics Postdoc at Harvard T.H. Chan School of Public Health, working on developing methods predicting future risk and finding target genes for complex diseases from multi-omics data (GWAS, Expression, Proteomics, Metabolomics, Methylation, etc.). \
        I completed my Ph.D. in Statistics from the University of Massachusetts Amherst and have a Master's in Bioinformatics. I worked as Application Computational Scientist for 3.5 years at [The Jackson Laboratory](https://www.jax.org/) and did Graduate Biostatistics summer internships at [Roche](https://www.roche.com/) and [Novartis](https://www.novartis.com/us-en/). \
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
      count: 5
      # Filter on criteria
      filters:
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
      columns: '1'
---
