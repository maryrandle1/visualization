
# Data Visualization 2, Written Description
 
    > What software did you use to create your data visualization?
Answer: Microsoft Excel (Pivot Table + Column Chart) 

    > Who is your intended audience? 
Answer: TTC infrastruture Planners, transit advocacy groups, and Toronto city decision-makers. Goal of visualization is to communicate geographic concentration of delays at specific stations across the city, vs. the day of week patterns in visualization 1

    > What information or message are you trying to convey with your visualization? 
Answer: The visualization ranks the top 10 stations by total delay in minutes. It shows that delays are not evenly distributed across the transit network. Certain stations contribute disproportionately to overall system delay, meaning that concentrating on certain infrastructure or operational improvements may be more relavent than full network changes
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
Answer: Intent was to prioritize clarity and being able to comapare and interpret easily;
1.Pivot table: SUM(Min Delay) used to ensure correct total calculation
2.Descending sort: Stations ranked highest to lowest
3.Top 10 filter: Prevents too much in the visualization and improves readability
4.Column chart: Effective for ranked category comparison.
5.Clear axis labels: Units clearly stated
6.Minimal formatting: Avoided excessive colors or 3D effects 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
Answer: Excel is much less reproducible like Python. The following steps were taken;
1.Used a Pivot Table instead of manual calculations
2.Sorted and filtered within the Pivot Table
3.Ensuring the chart updates dynamically when refreshed
    
    > How did you ensure that your data visualization is accessible?  
Answer: 
1.High contrast colors
2.Descriptive title
3.Clear measurement units
4.No reliance on color to understand visualization
5.No decorative chart effects
6.Simple two-axis visualization
    
    > Who are the individuals and communities who might be impacted by your visualization?  
Answer:
1.Students commuting to high delay stations
2.Residents near delay heavy stops
3.Communities who depend on transit
4.Local businesses reliant on consistent transit
5.TTC infrastructure teams
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
Answer: 
Included = Station name, Total delay (sum of minutes)
Excluded = Average delay, Time of day, Vehicle ID, Gap minutes, Direction. These were excluded to remove focus from frequency or timing
    
    > What ‘underwater labour’ contributed to your final data visualization product?
Answer:
1.Verifying aggregation used SUM (not AVERAGE)
2.Sorting and filtering properly
3.Testing layouts
4.Adjusting labels for readability
5.Checking for outliers
6.Ensuring pivot refresh accuracy
