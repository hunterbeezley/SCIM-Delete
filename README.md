# SCIM-Delete
A simple Python script that leverages New Relic's SCIM API to automate SCIM user ID lookup and deletion.

Created by Hunter Beezley using ChatGPT

This script leverages New Relic's SCIM API to (1) ask for a SCIM Bearer Token, (2) ask for a email [string], (3) return the SCIM ID for that user, and (4) ask to delete the user. The app also has logic for invalid user inputs, simple error handling, and asks to run the tool for another user.

