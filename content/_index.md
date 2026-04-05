---
title: ""
date: 2026-04-05
type: landing

design:
  spacing: "5rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: |-
        I am a **Chemistry PhD student** focused on the synthesis, characterization, and molecular-level understanding of semiconductor nanomaterials. My research connects **quantum dot synthesis**, **dopant chemistry**, and **computational modeling** to understand how structure, surface chemistry, and synthetic conditions shape electronic and optical properties.
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: research
    content:
      title: 'Research Vision'
      subtitle: 'Chemistry, nanomaterials, and mechanism-driven design'
      text: |-
        My work is centered on **semiconductor quantum dots and nanoscale materials chemistry**. I am especially interested in how precursor design, ligand environments, cluster-mediated nucleation, and dopant incorporation govern final material performance.

        Current directions include:

        - **Cu-doped CdTe quantum dots** synthesized through low-temperature, cluster-seeded routes.
        - **ZnTe/ZnMnS core-shell nanostructures** engineered to shift core absorption while preserving successful shell growth.
        - **Molecular and theoretical modeling** of chemically complex systems to connect synthesis with microscopic behavior.

        I enjoy building research stories that move from **synthetic strategy** to **spectroscopy, magnetism, and structure-property relationships**.
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'What I Do'
      subtitle: ''
      text: |-
        **Synthesis**  
        Design and optimize low-temperature routes for doped and core-shell semiconductor nanocrystals.

        **Characterization**  
        Use spectroscopy and materials characterization to probe composition, electronic structure, and dopant behavior.

        **Computation**  
        Apply molecular modeling and theoretical tools to understand ligand effects, interfaces, and nanoscale assembly.

        **Communication**  
        Turn complex chemistry into clear scientific narratives for talks, posters, manuscripts, and collaborative research.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Research Highlights
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Selected Publications & Writeups
      text: "A snapshot of current projects, manuscripts, and research summaries."
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: news
    content:
      title: Latest Updates
      subtitle: ''
      text: ''
      page_type: post
      count: 5
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      offset: 0
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]
  - block: markdown
    id: contact
    content:
      title: 'Let’s Connect'
      subtitle: ''
      text: |-
        I am always happy to connect about **nanomaterials chemistry**, **quantum dot synthesis**, **computational chemistry**, and interdisciplinary collaborations.

        Reach me by email at **ikknirmani@gmail.com**, or connect via **LinkedIn**, **GitHub**, and **Google Scholar** from the profile links above.
    design:
      columns: '1'
---
