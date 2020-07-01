# TPR COVID-19 Tracker: Instructions and Tips

## Table of Contents
- [Overview](#overview)
- [Data Sources](#data-sources)
- [Access](#access)
- [Update Frequency](#update-frequency)
- [Definitions](#definitions)
- [How to Interpret and Interact with Charts](#how-to-interpret-and-interact-with-charts)
- [Exporting and Saving](#exporting-and-saving)
- [FAQs](#faqs)
---

## Overview
The COVID-19 Tracker integrates publically available health data with internal store information to quickly monitor and identify risk in nearby counties.

The tool is for directional purposes as a supplement to other resources that business partners should be referencing.  All data should be verified against additional external sources before taking action or communicating implications.

## Data Sources
COVID-19 cases by U.S. county and state are sourced from the New York Times, which aggregates the data from local sources.

Re-opening statuses of U.S. states are also sourced from the New York Times.  However, please note that the New York Times publishes the aggregation every evening, so the status in the tracker might not include the most recent announcements if a spike has occurred.

Phase of store's re-opening are from an internal spreadsheet that is distributed weekly.

## Access
Users must be logged into the secure VPN and have license permissions (granted by TPR Analytics team) in order to access the tracker.

Please note that these instructions are publically available, so brands are not mentioned explicitly and screenshots censor any confidential information.

## Update Frequency
The dashboard will be updated by noon everyday.

Data for COVID-19 cases will also be updated by noon everyday.

Data for states' re-opening statuses are published by the New York Times each evening.  While the most recent data will be updated with the tracker by noon everyday, the state's status in the tracker might not include the most recent announcements if a spike has occurred that day.

Data for each store's phase of re-opening is updated weekly on Monday's, or if an important change has occurred.

## Definitions

- **New Cases Yesterday** – New confirmed cases of COVID-19 for the most recent date included in the tracker (listed at the top right corner of the dashboard)
- **Yesterday vs Prior Day** – The increase/decrease that yesterday’s new cases represents in relation to new cases two days ago.  For example, if yesterday was June 15, then this metric would compare to new cases on June 14.
- **7-day Avg** – The average daily new cases for the past 7 days.  For example, if yesterday was June 15, this metric is the daily average for June 9-15.
- **7-day Avg per Capita (M)** – The average daily new cases for the past 7 days, divided by the county’s population in millions.  In other words, the number of new cases for every million people in the county.  This metric is intended to normalize the volume of new cases for population size.  For example, if the 7-day Avg for Neverland County is 100 new cases and its population is 10,000,000 people, then the 7-day Avg per Capita (M) is 10.
- **Prior Week’s 7-day Avg** –  As an example, if yesterday was June 15 and the current 7-day Avg includes June 9-15, then this metric is the daily average for June 2-8.  (Please see above for the definition of 7-day Avg).
- **7-day Avg vs Prior Week** – The increase/decrease that the current 7-day Avg represents in relation to the Prior Week’s 7-day Avg.  (Please see above for definition of Prior Week’s 7-day Avg).

## How to Interpret and Interact with Charts
### Store Locations and County Trends (Map)
- The **shaded areas** are counties.  Hover over any to reveal details about the county, including number of recent cases.  Select a metric in the dropdown menu below the map to change the metric by which the colors scale.

   ![metric dropdown](/assets/images/screenshot-metric-dropdown.png "metric dropdown")

- The **dots** represent zip codes where there are stores.  Hover over any to reveal details about the store(s) in that zip code.
- **Search** for a particular region by clicking into the magnifying glass at the top left of the map.
- **Move** the map by selecting the “pan” tool in the map’s menu.
- **Select** a store to filter the charts specifically for that store.  Select a group of stores by using the lasso, circle or rectangle tools in the map’s menu.

   ![select group](/assets/images/screenshot-select-group.png "select group")

### Store Summaries
- This table lists each store’s respective statistics for counties within a 60 mile radius, including counties in adjacent states.  Please note that an individual county might be associated with multiple stores if it falls within their radii.
- **Select** a metric in the dropdown menu above the table to change the metric by which the colors scale.
- **Sort** according to any metric by hovering over the column name and clicking on the “sort” icon.  Click once to sort descending.  Click again to sort ascending.  Click a third time to return to the original sort order.

   ![sort](/assets/images/screenshot-sort.png "sort")

- **Hover** over the data to reveal more details about the store and its state’s current re-opening status.

   ![store reopening](/assets/images/screenshot-store-reopening.png "store reopening")

- **Select** a store to show it on the map and populate the two charts below, which illustrate trends over time.


### Total Trends for Store
- This chart populates only if a store is selected in the “Store Summaries” table above.
- This chart illustrates total new cases and 7-day Avg over time for counties within a 60 mile radius of the store.

### Total Trends by County for Store
- This chart populates only if a store is selected in the “Store Summaries” table above.
- This chart illustrates new cases and 7-day Avg over time for each county within a 60 mile radius of the store.

### Total Trends by State
- If no store is selected in the “Store Summaries” table, this chart will display new cases and 7-day Avg’s for all states over time.  States are listed in order of most to least cumulative cases.
- If a store is selected in the “Store Summaries” table, this chart will display news cases and 7-day Avg trend for the state where the store is located.  This will include counties that are not within a 60 mile radius.
- **Hover** over the data to reveal more details about the state’s current re-opening status.
- **Click** on the name of the state to open a tooltip with a link to a news article recommended by the New York Times about the states re-opening status.

   ![state trends](/assets/images/screenshot-state-trends.png "state trends")

## Exporting and Saving
### Export to Excel
- Select the “Download” button and choose “Crosstab,” then select the chart you want to export the data from.  “Store Summaries” will probably be the most useful to export in Excel.

   ![export data](/assets/images/screenshot-export-data.png "export data")

- DO NOT choose “Data” because it will download the full backend data and likely won’t be structured the way you want.

### Save as Image or PDF
- Select the “Download” button and choose to save as Image or PDF, which will save the whole dashboard with your current selections/filters.

## FAQs
- ***Will this include Canada and other countries?***

    There are currently no plans to expand outside of the U.S. but we will revisit if the need arises.

- ***Can we filter by brand, district or regional manager?***

   Filters for brand and other internal attributes were omitted to streamline the tracker and avoid potential data conflicts.

- ***If I select stores and filters, will I potentially change the view for other users?***

   No, each user's session with the tracker is isolated and does not affect others.

- ***I'm afraid I might break the tool--is that possible?***

   No, each user's session with the tracker is isolated and all selections or changes are reset to default whenever a user accesses it.

- ***Can I save my selections and filters so that they're there for me the next time I access the tracker?***

   Unfortunately, selections cannot be saved.  However, you can [export and save](#exporting-and-saving) a view for a particular day if needed.

- ***How do I coordinate access for someone else on my team?***

   If they are also a TPR employee, please have them e-mail tlai1@tapestry.com.

- ***Why is a store's re-opening phase either missing or incorrect?***

   The data is sourced directly from an internal spreadsheet managed by cross-functional teams.  If a store's phase details are missing, it is either because it wasn't listed on the spreadsheet or its store number could not be matched as it was listed.

- ***I'm not sure what happened, but I clicked something and the charts disappeared and/or are acting strangely.  What should I do?***

   You can always click the "Revert" button to return the tracker to its default.
---
Still have a question that wasn't addressed here?  E-mail tlai1@tapestry.com.

