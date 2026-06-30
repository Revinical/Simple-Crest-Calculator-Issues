name: Bug Report
description: Something isn't working as expected
labels: ["bug"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to report a bug! Please fill out the sections below to help get it resolved quickly.
        Before submitting, check that you're on the **latest version** and that no [existing issue](../../issues) already covers this.

  - type: dropdown
    id: wow-version
    attributes:
      label: WoW Version
      description: Which version of WoW are you playing?
      options:
        - Retail (The War Within)
        - Classic Era
        - Cataclysm Classic
        - Season of Discovery
    validations:
      required: true

  - type: input
    id: addon-version
    attributes:
      label: Addon Version
      description: Found in the addon list in-game (bottom-left of the addon entry).
      placeholder: e.g. 1.2.0
    validations:
      required: true

  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      description: A clear description of the bug you encountered.
      placeholder: Tell us what you saw...
    validations:
      required: true

  - type: textarea
    id: expected
    attributes:
      label: What did you expect to happen?
      placeholder: Tell us what you expected...
    validations:
      required: true

  - type: textarea
    id: steps
    attributes:
      label: Steps to Reproduce
      description: How can we trigger this bug?
      placeholder: |
        1. Open the addon panel
        2. Click on ...
        3. See error
    validations:
      required: true

  - type: textarea
    id: error-message
    attributes:
      label: Error Message (if any)
      description: Paste the full text of any Lua error or addon error here. Use the BugSack or !BugGrabber addon to capture the full error if possible.
      render: text

  - type: checkboxes
    id: conflict-check
    attributes:
      label: Conflict Check
      description: Please confirm the following before submitting.
      options:
        - label: I tested with other addons disabled and the issue still occurs
          required: false
        - label: I have checked for duplicate issues and found none
          required: true
