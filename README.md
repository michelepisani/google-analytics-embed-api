# google-analytics-embed-api
Google Analytics Embed API

Google Analytics Embed API documentation:
https://developers.google.com/analytics/devguides/reporting/embed/v1/getting-started

How to adapt it in Google Apps Script:

1) Create a standalone Google Apps Script;

2) Convert project from default to standard in GCP:
https://developers.google.com/apps-script/guides/cloud-platform-projects#switching_to_a_different_standard_gcp_project

3) Create an ID Client in GCP;

4) Replace in index.html file the placeholder *REPLACE_WITH_YOUR_CLIENT_ID* with the ID Client;

5) Enable Google Analytics API in script editor and GCP;

6) Deploy script as web application:

![alt text](<google-analytics-embed-api.png>)
