---
name: Weekly Meeting Notes
about: Used for taking notes in our daily standups, with a new issue every week.
title: "Weekly Meeting Notes: {{ date | date('MMMM Do') }} - {{ date | date('add', 5, 'days') | date('Do') }}"
labels:
  - "Meeting 💬"
---
### Monday, {{ date | date('MMM Do') }}
# Matches @-mentions in an issue comment
mention:
  - user: JasonEtco
  - team: github/

# Matches slash commands, like `/deploy` in an issue comment
command: deploy