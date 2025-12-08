1. Add another key card next to Spain named “Total GR Refund (In Euro)” . Add all the refund amount in each market and convert them into EURO and paste the value in this key card. 
2.  For the filter, add another filter = all, so we can see the overall value for all month in each market.
3. Another chart, to highlight missing category in all tickets with status “Closed” and “Multiple”
4. Add Market Filter to Each ChartFor every chart, add a small Market/All filter at the top-right corner of the chart. This filter should allow users to view data for:
* All markets combined
* A single selected market (e.g., Portugal, France, UK, Dubai, Spain)

5. Dynamic Ranking for Single-Market ViewFor the following charts:
* Highest Refund Category (By Amount)
* Highest Refund Subcategory (By Amount)
* Highest Refund Property (By Amount)
* Most Repeated Property ID (3-Month Rolling)
Behavior rules:
* When “All Markets” is selected → keep the current visual layout unchanged.
* When a single market is selected (e.g., Portugal) → automatically re-rank and display only the Top 4 results in descending order:
    * Left = highest value
    * Then second, third, and fourth highest from left to right.
This ensures consistency for global views while improving insight clarity for single-market analysis.