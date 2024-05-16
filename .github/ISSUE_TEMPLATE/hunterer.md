name: Hunterer/Companion bug
about: Submit a bug with the Hunterer database or Companion app that you've reported to WotC
labels: hunterer/companion
body:
- type: textarea
  id: problem
  attributes:
    label: Describe the problem
    description: "Include screenshots and directions to the problematic page(s) if applicable"
  validations:
    required: true
- type: input
  id: platform
  attributes:
    label: Which platform did this occur on?
    description: Did this occur on an Android device, iOS device, or some other way?
    placeholder: Android / iOS / Other
  validations:
    required: true
- type: input
  id: reference
  attributes:
    label: WotC report reference (optional)
    description: If you reported this to WotC already and received a report link or reference number, please include it here.
