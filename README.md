# Amazon Vine Analysis
## Summary
The purpose of this analysis is to compare the reviews of Amazon products listed in the Baby department based on if the members are part of the paid Amazon Vine program. We would like to see if there is or is not bias. For our baseline we filtered the products to those that had over 20 votes, then took the top 50 percent of that result. We called tallied these as our total votes data point.

### Tools
PySpark
Pandas
Postgres

## Results
We can see our summary table below which shows a similar percentage of a 5 star rating between the Vine campaign and the non Vine campaign.
<img src="Resources/SummaryTable.png width=300">

## Summary


### Postgres Table
<img src="Resources/vineTable_SQL.png width=300">
<img src="Resources/productsTable_SQL.png width=300">
<img src="Resources/customerTable_SQL.png width=300">
<img src="Resources/reviewIDTable_SQL.png width=300">
