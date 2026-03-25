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
        Avez Shaikh is a PhD Candidate in the Department of Mechanical Engineering at the Pennsylvania State University. He currently works as a research assistant at the Systems for Hybrid-Additive Process Engineering Laboratory (SHAPE), under the advisement of Dr. Guha Manogharan. His research focuses on designing metamaterials using additive manufacturing (AM) and inverse computational design to achieve targeted flow and mechanical properties.

        Additive manufacturing enables geometric complexity, but complexity without engineering precision is ineffective. His work incorporates process-specific constraints across AM methods, including Vat Photopolymerization, Laser Powder Bed Fusion (LPBF), and Binder Jetting, into inverse design frameworks for metamaterials employed in applications such as acoustic absorbers, battery electrodes, and bone scaffolds. To achieve this, he uses different generative AI techniques such as Conditional Variational Graph Autoencoders (CVGAEs), diffusion models, and Generative Adversarial Networks (GANs).

        Prior to joining Penn State, he earned his Bachelor of Technology (B. Tech) in Mechanical Engineering from Vishwakarma Institute of Information Technology, India. He has previously worked at Tata Technologies, Jaguar Land Rover department as a Product Lifecycle Management (PLM) consultant and has experience as a Founder for an early-stage startup, Invenzee Technologies. Avez holds four patents and his research has been published in Journal of Materials Engineering and Performance, Materials Science in Additive Manufacturing, Advances in Materials and Processing Technologies, Manufacturing Letters and many other journal and conference venues. He also serves as a peer reviewer for several prominent journals, including Progress in Additive Manufacturing, Discover Sustainability and Nature Scientific Reports.
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
