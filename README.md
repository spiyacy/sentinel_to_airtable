# Sentinel to Airtable
This repository contains a Sentinel Policy to be used alongside a Terraform Cloud/Enterprise workspace to POST the Success and Failures via API.
<br><br>

**An Example Airtable base with this information can be found at [here](https://airtable.com/shrTh7TP7Y1twy56M)**


## Sentinel Parameters



|Parameter                    | Value           |
| :---                        |    :----:       |
| total_cost             | numerical value of max workspace spent per month          |
| api_key | airtable api key for account to update the base        | 
| url_path         | the full path to the airtable base and table           |
-------------------------------------------------------------
<br><br>
# Updating the POST body

Be sure to check and update the body of the POST call to match the element column names in the airtable


