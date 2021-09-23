# Foundations-of-Computer-Science

1. For each university, extract from the times dataset the most recent and the least recent data, obtaining two separate dataframes¶
2. For each university, compute the improvement in income between the least recent and the most recent data points
3. Find the university with the largest increase computed in the previous point
4. For each ranking, consider only the most recent data point. For each university, compute the maximum difference between the rankings (e.g. for Aarhus University the value is 122-73=49). Notice that some rankings are expressed as a range
5. Consider only the most recent data point of the times dataset. Compute the number of male and female students for each country.
6. Find the universities where the ratio between female and male is below the average ratio (computed over all universities)
7. For each country, compute the fraction of the students in the country that are in one of the universities computed in the previous point (that is, the denominator of the ratio is the total number of students over all universities in the country).
8. Read the file educational_attainment_supplementary_data.csv, discarding any row with missing country_name or series_name
9. From attainment build a dataframe with the same data, but with 4 columns: country_name, series_name, year, value
10. For each university, find the number of rankings in which they appear (it suffices to appear in one year for each ranking).
11. In the times ranking, compute the number of times each university appears
12. Find the universities that appear at most twice in the times ranking.
13. The universities that, in any year, have the same position in all three rankings (they must have the same position in a year).
