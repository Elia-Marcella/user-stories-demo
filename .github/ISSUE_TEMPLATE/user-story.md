name: User Story
description: Create a new user story
title: "[User Story]: "
labels: ["new"]
assignees: ''

body:
  - type: input
    id: role
    attributes:
      label: As a...
      placeholder: "e.g., customer, admin, visitor"
    validations:
      required: true
  - type: input
    id: goal
    attributes:
      label: I want to...
      placeholder: "e.g., create an account, reset password"
    validations:
      required: true
  - type: input
    id: reason
    attributes:
      label: So that...
      placeholder: "e.g., I can access my dashboard"
    validations:
      required: true
