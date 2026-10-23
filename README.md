# SQL-and-Power-BI-analysis-of-Latin-American-series-Top-10-presence-across-ten-selected-markets.
Comparative analysis of Latin American series’ Netflix Top 10 presence across 10 selected markets using SQL and Power BI.

## Research question
In which markets did selected Latin American series stand out through their duration and ranking in Netflix’s Top 10 during selected 12-week observation windows?
This project focuses on the first instalment of One Hundred Years of Solitude, compared with Season 1 of The Eternaut and Who Killed Sara?.

## Objective
Explore differences in the geographical reach, persistence and peak ranking of these series across ten selected markets, using Colombia as a reference.

## Data and scope
Source: Netflix’s public weekly Top 10 dataset (https://www.netflix.com/tudum/top10/)
Markets: Canada, Colombia, France, Germany, Italy, Japan, the Philippines, Spain, the United Kingdom and the United States.
Each series is analysed over a 12-week window
The Queen of Flow was explored during preparation but is not included in the final dashboard.

## Tools and workflow
- SQL: select series and markets, define observation windows and calculate indicators.
- Power Query: prepare the exported CSV, correct data types and convert text “null” values into missing values.
- Power BI: build comparative visualisations of geographical reach, weeks in the Top 10 and best ranking.

## Indicators
- Markets reached: number of selected countries with at least one Top 10 appearance.
- Weeks in the Top 10: number of weeks with a recorded appearance within each 12-week window.
- Best position:highest ranking achieved in each country. A lower number represents a better ranking.
A zero for weeks in the Top 10 means no appearance was recorded during the selected window. It does not mean zero viewers.

## Key findings

### The Eternaut had the broadest observed reach
The Eternaut appeared in the Top 10 in 9 of the 10 selected markets, compared with 3 for One Hundred Years of Solitude and 2 for Who Killed Sara?.
Within these observation windows, The Eternaut therefore showed the widest geographical reach.

### One Hundred Years of Solitude had stronger persistence in Colombia
One Hundred Years of Solitude remained in Colombia’s Top 10 for 6 weeks, compared with 4 weeks for The Eternaut.
Both series reached the number-one position in Colombia. However, One Hundred Years of Solitude maintained a Top 10 presence for longer.

### International reach and local persistence tell different stories
In Italy and Spain, One Hundred Years of Solitude appeared in the Top 10 for 3 weeks, compared with 4 weeks for The Eternaut.
Its observed presence was concentrated in Colombia, Italy and Spain, while The Eternaut reached a broader selection of markets.

## Conclusion
One Hundred Years of Solitude stood out for its persistence in Colombia, but did not achieve the broadest international Top 10 presence among the series and windows examined. The Eternaut combined wider geographical reach with longer Top 10 presence in Italy and Spain.
These results highlight the importance of examining both reach and persistence, entering more markets and remaining visible within a particular market are different dimensions of performance.
The findings for Who Killed Sara? describe a later period in its lifecycle and should not be interpreted as evidence of a weaker original launch.

## Limitations
- The observation windows cover different stages of the series’ lifecycles. This is a descriptive comparison, not a controlled comparison of launches.
- Country rankings do not provide country-level viewer counts. The same ranking in two countries does not imply the same audience size.
- Only Top 10 appearances are observed. Activity outside the rankings is not measured.
- Weeks in the Top 10 are not necessarily consecutive.
- The selected countries and series are a limited sample; findings cannot be generalised to all markets or Latin American productions.
- The dataset does not measure campaign spending, advertising effectiveness, completion rates or subscriber acquisition.
