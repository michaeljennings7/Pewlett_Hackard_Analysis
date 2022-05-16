# Pewlett Hackard Analysis

## Overview
The purpose of this analysis was to help a fictional character to determine certain characteristics of employees at the large corporation called Pewlett Hackard. We were tasked with determining which employees were eligible for retirement based on their employee number, title, and birth and hire date data. Practically speaking we practiced SQL to slice and segment a large data set into a meaningful subset that could be used to help a corporation plan for a retirement wave and set them up to determine who might be good candidates for a mentorship program.

## Results
The output of this module challenge was a set of csv files that contain the information requested by Pewlett Hackard. The files listed below:

* Retirement eligible employees and their titles
[retirement_titles.csv](https://github.com/michaeljennings7/Pewlett_Hackard_Analysis/files/8696616/retirement_titles.csv)

* A subset of the file above that finds just the unique employees eligible for retirement and their titles
[unique_titles.csv](https://github.com/michaeljennings7/Pewlett_Hackard_Analysis/files/8696625/unique_titles.csv)

* The number of employees retiring sorted by their titles
[retiring_titles.csv](https://github.com/michaeljennings7/Pewlett_Hackard_Analysis/files/8696628/retiring_titles.csv)

* The employees eligible for the Mentorship Program
[mentorship_eligibility.csv](https://github.com/michaeljennings7/Pewlett_Hackard_Analysis/files/8696634/mentorship_eligibility.csv)

## Summary
With the above analysis finished we learned that there were quite a few people about to retire in general, but the bulk of those retiring were senior staff and senior engineers. Understandably, the "senior" tier of employees in the hierarchy are experiencing the largest exodus with far fewer leaving from the lower levels via retirement. However, one way to get more insight on this data set would be to parse the mentorship eligibility dataset further. The outcome of this could be to identify particular employees who have a significant amount experience to then fill the roles vacated by those retiring rather than relying solely on hiring replacements from outside the organization. This approach could be applied in a sort of "organizational pipeline" that can be used to forecast new hires out of university, through to retirement. Using this approach Pewlett Hackard would have good insight into where the greatest amount of turnover is happening within the organization and possibly plan for rention at the same time.
