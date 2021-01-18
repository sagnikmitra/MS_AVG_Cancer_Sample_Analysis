### BC_MS_AVG_Cancer_Sample_Analysis
This is an Intensity based analysis for Boston College Mass Spectometry Average Cancer Sample having M/Z Ratio and Absolute Intensity as their primary attributes.

The Analysis includes the following parts:
1. Fetching any random Peak.
2. Creating a Closed Interval surrounding the Peak
3. Accessing all the M/Z Ratios within that particular range considering the lower range and upper range from the said closed interval.
4. Getting the Maximum Absolute Density for the corresponding M/Z Ratios.
5. Repeating the same for all the M/Z Ratio - Absolute Intensity Column pairs.
6. Getting all the Max Value and creating a 2D where where each element is Max_Intensity, Corresponding M/Z Ratio
7. Plotting M/Z Ratio with max_intensity values.
8. Repeating the same process for all the Sheets available (having simialr stat shape).

### About the Data:
The First two row of the data are its attributes. First row consists of 21 pairs of M/Z Ratio & corresponding Absolute Intensity value. The secodn row refersto a particular Disjoint Ordered Discontinuous BC Values. The reason of discontinuity is the fact that any inaapropiate datas were dropped beforehand and the data which was provided had only remaining BC values. The Data is not well rounded as the length of each column is different. So, first we had to fill in the blank spots with NaN and then proceed with analyzing the datset.
