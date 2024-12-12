# Analysis-of-mercury-levels-in-fish


We will be exploring the relationship of water characteristics of the lake and the mercury level in fish from data set collected in Florida.

## Methodology: 

Largemouth bass were studied in 53 different Florida lakes to examine the factors that influence the level of mercury contamination. Water samples were collected from the surface of the middle of each lake in August 1990 and then again in March 1991. The pH level, the amount of chlorophyll, calcium, and alkalinity were measured in each sample. The average of the August and March values were used in the analysis. Next, a sample of fish was taken from each lake with sample sizes ranging from 4 to 44 fish (note: this adds a level of complexity that we will choose to ignore for this project). The mercury concentration in the muscle tissue was measured and averaged for each lake. Florida has set a standard of 1/2 part per million as the unsafe level of mercury concentration in edible foods. 45.3% of the lakes exceed this level.

## Reference: 

Lange, Royals, & Connor. (1993). Transactions of the American Fisheries Society .

## There are 3 major components in this analysis.
1) Determine if the average mercury is different for fish in lakes with acidic water compared to fish in lakes with basic water.
2) Determine if there is a relationship between the calcium categories and whether or not the mercury level in the fish is acceptable.
3) Explore the impact of chlorophyll, Calcium, and pH on mercury in fish using a regression
## Data description:
 Variables
   * ID: ID number
   * Lake: Name of the lake
  * Alkalinity: Alkalinity (mg/L as Calcium Carbonate)
   * pH: pH
   * pH_cat: pH categorized as "acid" for pH<7 and "base" for pH>=7
   * Calcium: Calcium (mg/l)
   * Calcium_cat: Calcium categorized as "low" for Calcium<5, "medium" for 5<Calcium<30, and "high" for Calcium>30
   * Chlorophyll: Chlorophyll (mg/l)
   * Avg_Mercury: Average mercury concentration (parts per million) in the muscle tissue of the fish sampled from that lake
   * Mercury_cat: Avg_Mercury categorized as "acceptable" for Avg_Mercury<0.5 and "unsafe" for Avg_Mercury>=0.5
