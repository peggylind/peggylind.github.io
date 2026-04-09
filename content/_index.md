---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Lindner_CV.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: sm # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  
  - block: markdown
    content:
      title: 'My Research'
      subtitle: ''
      text: |-
        My work focuses on using computational methods to make complex systems more interpretable, actionable, and useful for decision-making. I have contributed to research on LLM bias, explainability, text mining, online communication, science-of-science, and digital humanities, with publications in venues including Nature Communications, Nature Human Behaviour, IEEE Transactions on Biomedical Engineering, and Artificial Intelligence in Medicine.

        I am especially interested in translational, cross-disciplinary research that connects technical innovation with real-world application. Across funded projects, industry collaboration, and academic leadership, I work to build data-driven approaches that are rigorous, explainable, and practical for stakeholders.
    design:
      columns: '3'

  - block: collection
    id: papers
    content:
      title: Recent Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  
  - block: resume-experience
    content:
      username: me
    design:
      date_format: 'January 2006'
      is_education_first: true

  
 

  - block: markdown
    content:
      title: Contact
      text: |-
        **Peggy Lindner**  
        Associate Professor | Associate Chair for Graduate Studies  
        Engineering Management and Systems Engineering
        
        Missouri University of Science & Technology

        Engineering Management Building 214  
        Email: [plindner@mst.edu](mailto:plindner@mst.edu)  

        [Book time with me](https://outlook.office.com/bookwithme/user/f25158c06d734f848c3509a2d3624122@mst.edu?anonymous&ismsaljsauthenabled&ep=pcard)
    design:
      columns: '2'
  

---
