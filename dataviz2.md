[Return to Portfolio Home](https://danieldistler-1.github.io/Distler-portfolio/)


# Visualizing Government Debt

The visualizations below, utilize data from the Organisation for Economic Co-operation and Development (OECD) on the Debt-to-GDP ratio for member countries. [OECD notes](https://data.oecd.org/gga/general-government-debt.htm) that Debt-to-GDP ratio is a "a key indicator for the sustainability of government finance". The quantity can be simply calculated as a nation's debt / the nation's GDP.  

## 2009 Government Debt in the European Union 

The graph below shows the Government Debt-to-GDP ratio for EU member countries in 2009. Taken from the [OECD site](https://data.oecd.org/gga/general-government-debt.htm), the graph effectively communicates the relative Debt-to-GDP ratios for each member nation. The graph is free of any extraneous information, and deisgned to limit the cognitive load of the reader. Each country is well labled and arranged in ascending order by Debt-to-GDP ratio. The reader can quickly and easily focus on a country's by mousing over, on clicking on the nation.  

<iframe src="https://data.oecd.org/chart/6gGc" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6gGc" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2009</a></iframe>

## Tracking Debt Over Time

This grid of line charts provides a more comprehensive view of how Debt-to-GDP ratio has changed in OECD member nations over time. Each box shows this key indicator for a member nation from 1995-2018. Mouse over any point, in any chart to see specific ratio measurements. I experimented with changing the size of the points, order of the variables and position of the axes, but ultimately thought the preset setttings displayed the data optimally. In an effort to fine tune the graphic, I eliminated the preset legednd and opted to instead include a detailed subtitle. To avoid clutter, I tried to use this title to both identify the main variable in the chart (Debt-to-GDP ratio) and provide context for the visualization.  

<div class="flourish-embed flourish-chart" data-src="visualisation/5272840"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## OECD's Biggest Economies 

For my original visualization, I wanted to create something that both captured the benefits of interactive graphics and satsified the more established guidelines of effective visualization. While the first two visualizations allow the reader to compare countries staticly, in the bar chart from 2009, and against themselves over time, in the grid fo line charts above, I wanted to find a visualization that would allow the reader to compare country's against one another over time. To reach this goal, I ultimately opted to generate a Flourish Bar Chart Race. To get the data into a form that would work with this visualization in Flourish I undertook a few steps. 

### Creating the Graphic 
- First, I **transformed the original CSV file**, using a pivot table, so that the columns, would be years and the rows were individual countries. This did not transform the GDP-to-Debt ratios themselves, but organized them in a way that allowed me to feed the data into the Flourish bar chart race visualization tool. 
- I also needed to add an **image for each nation**. The preset, Flourish bar chart race, included the flags of many nations (including all of OECD). I used these publicly available links from Flourish as the Icons for each OECD country. These are linked as a source in the footer of the image. 
- I wanted to **choose a focus** for this visualization, since without one the shear amount of data would be overwhelming. I chose to focus on the OECD's two biggest economies Japan and the United States. I originally began with the idea on focusing on all of the G7 member nations, but determined this would be too much information for the reader to take in at once. 

### Model Techniques Used
- **Grey as a friend:** when I first put my data into this visualization I noticed that it was immeadiately overwhelming. To try and make this more manageable I used gray to represent all the countries that were not my focus. 
- **Constrainting Colors:** I chose the colors for USA and Japan using [ColorBrewer](https://colorbrewer2.org/#type=qualitative&scheme=Dark2&n=3) to find optimal qualitative color codes. This allowed for quick and accesssible recognition. 
- **Bars for comparision and simplicity:** I chose to use horizontal ordered bars for comparison. Since the data is dynamic and there are many countries, this format allows for quick and easy comparision. 
- **Left aligned:** I tried to follow the best practice of aligning all elements of my graph by aligning the title, on the left, with the labels for my graphic. 
- **Temporal Change:** While the changing time period of this graphic adds information, and can reasonably be viewed as complicating the messsage, I decided this trade off was worth it in exchange for the ability to see countries change over time, and the engagement that would come from the graph's interactive features. 
- **Title and Legend:** I chose to eliminate the preset legend and instead include it as part of my descriptive title by highlighting the acronyms for the U.S. and Japan (JPN). The flags, included for each country, also allow the reader to quickly and easily identify any nation in the plot. 

### The Visualization 

The final result, produced as described above, tries tells a particular story. The title and subtitle, put an immediate focus on the USA and Japan. From the graphic we can quikcly and easily see the Debt-to-GDP ratio for these nations. We notice, that over time, not only does Debt-to-GDP seem to rise on pverall average, but the increase is  particularly obvious for these two major economies. They ultimately, end up in the top 5 with oft-economically embattled nations such as Portugal, Greece and Italy.  

<div class="flourish-embed flourish-bar-chart-race" data-src="visualisation/5278262"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

[Return to Portfolio Home](https://danieldistler-1.github.io/Distler-portfolio/)
