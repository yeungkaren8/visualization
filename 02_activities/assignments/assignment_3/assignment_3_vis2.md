**What software did you use to create your data visualization?**
> Python

**Who is your intended audience?**
> General public

**What information or message are you trying to convey with your visualization?**
> Using data from the City of Toronto’s Open Data Portal (https://open.toronto.ca/dataset/toronto-beaches-water-quality/), I wanted to investigate the water quality of Toronto's 2 beaches over time, using E coli levels as a proxy. E coli counts for each beach was plotted as a line graph over the days in July across the years 2020-2024. While there were no clear trends across years, as a whole Sunnyside Beach had lower E coli counts compared to Marie Curtis Park East Beach, particularly from 2021-2023. 

**What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?**
> I tried to make the viz as easily understood as possible, using distinct colours for each line representing each year and showing the changes in E coli counts over time as a connected line graph. I plotted the data from both beaches on the same y-axis scale so that it was easier to compare across sites. I drew in grid lines so that it would be easier to identify x and y values across the graph.
    
**How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?** 
> Ensured reproducibility by writing a Python script on a Jupyter notebook which shows step-by-step how to reproduce the viz from the input data.
    
**How did you ensure that your data visualization is accessible?**
> In terms of data accessibility, I made my data file (.csv) available along with the Jupyter notebook. In terms of visual accessibility, see previous notes.

**Who are the individuals and communities who might be impacted by your visualization?**
> The municipal government of Toronto may look at this visualization and decide that Marie Curtis Park East Beach may require some sort of intervention to improve their water quality and reduce the number of E coli spikes. Citizens viewing this visualization may decide to visit Sunnyside Beach over Marie Curtis for their "cleaner" water.

**How did you choose which features of your chosen dataset to include or exclude from your visualization?** 
> This dataset contained daily data across July-September from 2007-2024. When plotting all of the provided data, it was difficult to view all of the days across this monthly window and so I chose to visualize only July, which would be the first full month of summer break for children K12-grade 12 and likely a popular beach month. I also chose to focus on years 2020-2024 for more current data (focusing on the last 5 years).
    
**What ‘underwater labour’ contributed to your final data visualization product?**
> The people from Toronto Public Health, Toronto Water, the Marine Police Unit, Parks and Recreation Department who sampled both sites daily, measured E coli levels, and collated data, and myself in pre-processing the data.