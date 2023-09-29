# Social Vulnerability Index (SOVI) Map
## This repository maps social vulnerability, as an index, for regions overlapping the Sacramento-San Joaquin Delta and Suisun Marsh. 

#### The code was developed as part of the Delta Stewardship Council's [Delta Adapts climate change initiative](https://deltacouncil.ca.gov/delta-plan/climate-change). For more information on the methdology and appropriate use of the data, please see the *Methodology and Resources* tab on the [app](https://deltascience.shinyapps.io/Delta_vulnerability_map/).

#### Updates
##### 2023-09-28
Recommended steps for updating app updates to shinyapps.io, for an existing app:
- Before starting, login to shinyapps.io and download bundle backup to your computer.
- Open code in R/R Studio, confirm using lastest updates to code. Within "Delta_vulnerability_map.dcf", confirm that the name, URL, and index number match the existing app. (You can confirm these variables on shinyapps.io). Save.
- Open, save, and run "server.R.
- Click "Publish the application or document" button and the Publish to Server" menu box will open.
- If "Publish" button is greyed out, click "Add New Account" and enter your token and secret (available under your account on ShinyApps.io).
- Under the Update section in the lower right of the box, ensure that it is pointing to the correct, existing app. Click publish.
