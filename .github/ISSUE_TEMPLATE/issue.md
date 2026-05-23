name: APH Issue Form
description: Create a structured issue with required fields


body:
  - type: textarea
    id: description
    attributes:
      label: Description
      description: Provide a clear and concise description of the issue/problem/request
      placeholder: Describe the issue...
    validations:
      required: true

  - type: textarea
    id: adarsh_statement
    attributes:
      label: Adarsh Statement
      description: Add Adarsh's statement, context, or perspective
      placeholder: Enter Adarsh statement...
    validations:
      required: true

  - type: textarea
    id: owners_stance
    attributes:
      label: Owners Stance
      description: Describe the owner's position, decision, or response
      placeholder: Enter owner's stance...
    validations:
      required: true

  - type: textarea
    id: representatives
    attributes:
      label: Representatives
      description: List representatives, stakeholders, or involved parties
      placeholder: |
        - Name:
        - Role:
        - Contact/Reference:
    validations:
      required: true

  - type: textarea
    id: evidences
    attributes:
      label: Evidences
      description: Attach or reference supporting evidence
      placeholder: |
        - Screenshots:
        - Documents:
        - Logs/Links:
        - Additional Notes:
    validations:
      required: true
