---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  # =========================
  # BIO / HERO SECTION
  # =========================
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  # =========================
  # MY WORK SECTION
  # =========================
  - block: markdown
    content:
      title: "💼 My Work"
      subtitle: ""
      text: |-
        I work in the field of data analytics and data engineering, with experience in transforming raw data into meaningful insights for business decision-making. My background includes building data pipelines, analyzing time-series data, and developing interactive dashboards to monitor performance and trends.

        I have industry experience working with technologies such as SQL, Python, Power BI, Microsoft Azure, Databricks, and Apache Spark. My work focuses on data analysis, forecasting, and creating clear, actionable insights for stakeholders.

        I am interested in analytics-driven problem solving, business intelligence, and using data to support strategic decisions. Feel free to reach out if you would like to collaborate or discuss data-driven projects 😊
---
