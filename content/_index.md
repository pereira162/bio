---
title: ''
date: 2024-11-16
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/CV Lucas Campos_2024.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: daniel-mccullough--FPFq_trr2Y-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em; margin-right: 5px; margin-left: 5px;'
  - block: experience
    content:
      title: Experiência Profissional
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
  - block: skills
    content:
      title: Habilidades
      username: admin
  - block: awards
    content:
      title: Certificados
      username: admin
---
