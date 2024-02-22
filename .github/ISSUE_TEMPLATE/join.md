name: Join the EIC organization
description: Provide the required information to join.
body:
  - type: markdown
    attributes:
      value: Thank you for your interest in joining the EIC organization on GitHub. Please provide the information below so we can assess your request.
  - type: input
    id: username
    attributes:
      label: GitHub username
    validations:
      required: true
  - type: input
    id: affiliation
    attributes:
      label: Affiliation (university, laboratory)
    validations:
      required: true
  - type: checkboxes
    id: eicug-membership
    attributes:
      label: Check duplicate issues.
      description: Membership in the EIC organization is limited to persons affiliated with an insitution in the EIC User Group (EICUG). Membership are listed at https://phonebook.sdcc.bnl.gov/eic/client/.
      options:
        - label: I am a member or my supervisor is a member of the EICUG.
    validations:
      required: true
  - type: textarea
    id: additional-information
    attributes:
      label: Additional information
    validations:
      required: false
