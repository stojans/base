# This Repo contains the code for the following task:


## Task 3: Add "Login As" Button on User List (Advanced)
• Extend the res.users model to add a new button "Login As" in the user list view.
• When clicked, the system should:
  o Authenticate as the selected user.
  o Redirect to the home dashboard as that user.
• Ensure only admin users (with base.group_system) can use this feature.
• Prevent logging in as superuser (ID=2) for security reasons.

## Installation

1. Pull the code to the _server/odoo/addons/base_ folder of your Odoo instalation
2. Restart the Odoo server
3. In Odoo web UI upgrade the "base" module

## Usage

After base module upgrade, in the _Settings > Users & Companies > Users_ tab, each user entry will have a "Login As" button that allows automatic log in to Odoo as that user

NOTE: Only admin users (base.group_system) group) will be able to see this button
NOTE: Logging in as superuser using this button is not allowed, as per the requirements
