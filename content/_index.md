---
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: |
        PhD candidate at Penn State building computational and AI-driven methods for additive manufacturing, inverse design, and manufacturable metamaterials.
      button:
        text: Download CV
        url: /uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    id: research
    content:
      title: Research Summary
      subtitle: ''
      text: |-
        My work focuses on computational design for additive manufacturing, inverse design, and physics-aware AI systems for engineering.

        Current directions include process-constrained generative design, acoustic and electrochemical metamaterials, CAD automation, manufacturability-aware data generation, and simulation workflows spanning FEA, CFD, and geometry processing.

        I am especially interested in building tools that connect generative AI with real manufacturing constraints so designs are both novel and buildable.
    design:
      columns: '1'
  - block: markdown
    id: publications
    content:
      title: Selected Publications
      subtitle: ''
      text: |-
        Google Scholar: [Profile](https://scholar.google.com/citations?user=9gPZgy4AAAAJ&hl=en&oi=ao)

        - [Functionally graded TPMS gyroid structures for additive manufacturing of non-pneumatic tires](https://pure.psu.edu/en/publications/functionally-graded-tpms-gyroid-structures-for-additive-manufactu/)
        - [Towards gradient design of TPMS lattices and laser powder bed fusion processing: Role of laser strategies and lattice thickness](https://pure.psu.edu/en/publications/towards-gradient-design-of-tpms-lattices-and-laser-powder-bed-fus/)
        - [ANN modelling of surface roughness of FDM parts considering the effect of hidden layers, neurons, and process parameters](https://www.tandfonline.com/doi/full/10.1080/2374068X.2022.2091085)
        - [A review on machine learning, big data analytics, and design for additive manufacturing for aerospace applications](https://link.springer.com/article/10.1007/s11665-022-07125-4)
    design:
      columns: '1'
  - block: collection
    id: projects
    content:
      title: Featured Projects
      text: Selected projects pulled from my Penn State research portfolio.
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 2
      fill_image: true
      show_date: false
      show_read_time: false
      show_read_more: true
  - block: markdown
    id: contact
    content:
      title: Contact
      text: |-
        Email: [aas6636@psu.edu](mailto:aas6636@psu.edu)

        Phone: [+1 (814) 280-7238](tel:+18142807238)

        Current address: State College, PA 16803

        Permanent address: Pune, Maharashtra 411014, India
    design:
      columns: '1'
---
