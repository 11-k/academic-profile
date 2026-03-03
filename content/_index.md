---
title: ''
summary: ''
date: 2024-01-01
type: landing

design:
  spacing: '3rem'

sections:
  # Bio / About Section
  - block: resume-biography-3
    content:
      username: me
      text: |
        Welcome to my academic homepage. I am a researcher passionate about
        advancing the frontiers of science. Please update this text with your
        own introduction.
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      name:
        size: sm
      avatar:
        size: small
        shape: circle

  # Featured Publications
  - block: collection
    id: publications
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  # Recent Publications
  - block: collection
    content:
      title: Recent Publications
      text: |
        See the full list of [all publications](/publications/).
      filters:
        folders:
          - publications
        exclude_featured: false
      count: 5
    design:
      view: citation

  # Contact
  - block: markdown
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: |
        **Email**: [your.email@example.edu](mailto:your.email@example.edu)

        **Office**: Room XXX, Your Building, Your University

        **Address**:
        Your Department
        Your University
        Your City, Country

        **Office Hours**: By appointment
    design:
      columns: '1'
---
