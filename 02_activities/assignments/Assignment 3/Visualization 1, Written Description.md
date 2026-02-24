
# Data Visualization 1, Written Description
 
    > What software did you use to create your data visualization?
Answer: Python (Pandas + Matplotlib) 

    > Who is your intended audience? 
Answer: TTC labour Planners and Toronto city decision-makers. Goal of visualization is to communicate whether delays are evenly distributed across the week or concentrated on specific days

    > What information or message are you trying to convey with your visualization? 
Answer: The chart shows that average delay time differs by day of the week, with Friday being the highest average delay. This suggests there could be more traffic congestion on Friday, or operational strain such as less labour available on Fridays, or increased rider demand. The visualization supports targeted staffing to account for shape of week to ensure the right amount of labour on the right days
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
Answer: 
1.Chart type = A bar chart was chosen for category comparison
2.Ordering = Days are ordered Monday–Sunday rather than alphabetically to reduce cognitive load
3.Clear labeling = Axes include units (“Minutes”) to avoid ambiguity
4.Minimalism = No colors or visual clutter added, supporting clarity
5.High resolution: Exported at 300 dpi for quality
6.Readable labels: X-axis labels rotated 45° for best readbility 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
Answer:
1.The dataset is loaded for programming 
2.Aggregation is performed using groupby() and mean()
3.The visualization is saved directly through code
4.The full code is included in the appendix
5.Any user running the code with the dataset will produce identical results
    
    > How did you ensure that your data visualization is accessible?  
Answer: 
1.Descriptive title
2.Clear axis labels and units
3.No reliance on color to to explain visualization 
4.High contrast style
5.Simple structure readable by screen readers 
    
    > Who are the individuals and communities who might be impacted by your visualization?  
Answer:
1.Daily riders
2.Shift workers
3.TTC operations staff
4.Any communitites reliant on weekday and/or weekend transit
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
Answer: 
Included = Day of week, Average delay (minutes)
Excluded = Station-level detail, Vehicle ID, Gap minutes, Direction. These were excluded to keep focus on day of week patterns for delays rather than geographic patterns
    
    > What ‘underwater labour’ contributed to your final data visualization product?
Answer:
1.Reviewing data structure
2.Validating delay values
3.Reordering days
4.Checking for missing values
5.Testing export quality
6.Ensuring reproducibility through coding
