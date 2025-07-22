# Data Visualization

## Assignment 3: Final Project


- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    I used Python in a Jupyter Notebook, specifically with Pandas, Matplotlib, and Seaborn libraries for plotting.

    > Who is your intended audience? 
    Urban planners, policy researchers, government analysts, or anyone interested in Toronto’s urban development trends.
    
    > What information or message are you trying to convey with your visualization? 
    I wanted to show 
    1. How overall construction activity in Toronto has changed from 2000 to 2024, 
    2. What types of construction work permits —such as new builds, renovations, or demolitions—have driven those trends over time.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    I used color palettes like tab10 and Set2 for contrast and clarity. I added gridlines for readability, labeled axes clearly, rotated year labels for better fit, and placed legends outside the plot to prevent overlap. All elements support quick visual interpretation.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    I ensured reproducibility by using code-based tools (Python/Jupyter) with well-documented steps. Anyone with the dataset can re-run the notebook and get identical results. 
    
    > How did you ensure that your data visualization is accessible?  
    I used high-contrast color palettes, labeled axes and legends for clarity, and avoided clutter. I also kept visual elements simple and avoided reliance on color alone to convey meaning.
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    Residents, developers, community organizations, city officials, and researchers might use these insights to understand construction patterns, identify development hotspots, or influence policy decisions.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    I focused on the most relevant columns for trend analysis: COMPLETED_DATE, PERMIT_TYPE. I excluded technical metadata and geographical fields since the goal was high-level temporal patterns, not spatial ones (for now).
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    This includes downloading and merging datasets, cleaning date formats, handling missing values, converting column names, aggregating yearly totals, selecting meaningful categories, and fine-tuning design choices—all of which happen behind the scenes before a single chart appears.
