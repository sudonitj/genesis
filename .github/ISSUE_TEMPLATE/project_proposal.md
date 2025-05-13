name: "Project Proposal"
description: "Propose a new project for SUDO."
title: "Proposal: Your Project Name"
labels: ["proposal", "discussion"] # Simpler labels
assignees: ''

body:
  - type: markdown
    attributes:
      value: |
        Thank you for proposing a new project for SUDO!
        Please provide details below. Focus on clarity and how your idea fits SUDO's goals.

  - type: input
    id: project-name
    attributes:
      label: "Project Name / Tentative Repository Name"
      description: "What do you want to call this project? (e.g., sudo-lib-networking)"
    validations:
      required: true

  - type: textarea
    id: project-goal
    attributes:
      label: "Project Goal & Problem Solved"
      description: "What will this project achieve? What problem does it address?"
    validations:
      required: true

  - type: textarea
    id: sudo-alignment
    attributes:
      label: "Alignment with SUDO Philosophy"
      description: "Explain how this project fits SUDO's approach of building foundational software, learning by doing, and minimizing external dependencies."
    validations:
      required: true

  - type: textarea
    id: core-features
    attributes:
      label: "Core Features (Initial Version)"
      description: "What are the essential features for a first, basic version?"
    validations:
      required: true

  - type: textarea
    id: why-sudo
    attributes:
      label: "Why should SUDO build this?"
      description: "What are the benefits to the SUDO community (e.g., learning opportunities, useful internal tool/library)?"
    validations:
      required: true

  - type: input
    id: your-interest
    attributes:
      label: "Your Interest / Potential Role (GitHub @username)"
      description: "Are you interested in leading or contributing? Let us know! (e.g., @your-username, interested in contributing)"

  - type: markdown
    attributes:
      value: |
        Once submitted, please check back for discussion and feedback in the issue comments.
