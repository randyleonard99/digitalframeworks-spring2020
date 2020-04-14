# Assignment 2: Tools of the trade: R

As a group, download and install [RStudio](https://www.rstudio.com/)

Follow the [Getting started in R](https://paldhous.github.io/NICAR/2018/r-analysis.html) tutorial by Peter Aldhous using his [data file](https://paldhous.github.io/NICAR/2018/data/r-analysis.zip) which you can unzip and place on your desktop.

Make your way together until you get to:

_**"Create a summary, showing the number of opioid prescriptions written by each doctor, the total cost of the opioids prescribed, and the cost per claim"**_

## Assignment:
For the assignment you will turn in:
1. Change this code to find the doctors outside of California:
`# license revokations for doctors based in California, by year
revoked_ca_year <- ca_discipline %>%
  filter(action_type == "Revoked" 
         & state == "CA") %>%
  group_by(year) %>%
  summarize(revocations = n())`
Take a screen shot of your table and upload that to your GitHub repo and paste the link in Canvas Assignment 2.
