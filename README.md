# onboarding-theme-boilerplate
Boilerplate theme, template, and modules for Blue Frog's Hubspot theme

## Deploy Theme to a HubSpot Account:


1. Obtain the Portal ID of the HubSpot Account you want to deploy to.
1. Obtain a Personal Access Token from the HubSpot Account you want to deploy to.
   1. Go to <a target="_blank" href="https://app.hubspot.com/portal-recommend/l?slug=personal-access-key" target="_blank">this link</a> to generate this key.
1. In this repository, go to Settings > Secrets and update both the HUBSPOT_PORTAL_ID and HUBSPOT_PERSONAL_ACCESS_KEY secrets with the new Portal ID and Personal Access Token you obtained from steps 1 and 2.
1. Go to Actions then find the workflow named 'Deploy Theme to Hubspot Account' and run the workflow manually by clicking the Run Workflow button.

Once the workflow has finished, the theme should now be deployed to the correct HubSpot account.
