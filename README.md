# Custom-Incident-Form

Create a customised form in each incident to perform custom actions per incident in pagerduty e.g. update external tools with custom fields

This currently updates the notes section with the fields within the custom form as an example.

<img src="https://github.com/PD-hliang/Custom-Incident-Form/blob/master/imgs/CustomForm.png" width="600">

# Notes
* This is just a template to get started with so you will need to customise it to your needs.
* An email linked to a pagerduty account is needed for this to update the notes section if you plan to use this specific functionality
* You will need to add your own API key into the code to be able to send data using the PagerDuty API

# Installation

* Download/copy/pull this HTML file 
* Customise the template
* Host the HTML page with your prefered provider (e.g I use Amazon S3 to host this page) 
* Create a new Add-on extension in pagerDuty with the URL with where you host the page as shown below and attach to pagerduty services
<img src="https://github.com/PD-hliang/Custom-Incident-Form/blob/master/imgs/Add%20on%20image.png" width="1200">
* And everything should start working!

