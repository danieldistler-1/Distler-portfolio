
[Return to home](https://danieldistler-1.github.io/Distler-portfolio/)

# Visualization Choice 

I chose to redesign the cumulative data visualization on [Carnegie Mellon University's COVID-19 dashboard](https://www.cmu.edu/coronavirus/health-and-wellness/dashboard.html)<sup>1</sup>.    I chose to redeisgn this visualization because I have used the dashboard throughout this and last semester to monitor COVID-19 on campus. I found that the existing graphs were often hard to intepret and thought there was room for improvement. For example, this is how the graph originally appears on my computer. 


![COVID Graph Zoomed](covid%20zoomed.JPG)

As you can see above, the graph's cuts off, while much of the screen is dominated by four large colored squares that make up the legend. Even when zoomed out, as shown below, I believe that graph could be redesigned to be more aesthetically pleasing, and easier to intepret.

![COVID Graph Zoomed Out](covid%20zoomed%20out.JPG)

# Critique Method 
By completing the critique method, I noticed several aspects of the chart had room for potential improvement. These elements included:

**The Striking Legend:** the four big colored blocks in the graph were the first thing that caught my eye. I wanted to find a different way to label groups in my redesign.

**Four Bright Colors:** I felt the four bright colors used in the graphic were distracting and obfuscated the graph's message. In my final project, I endeavored to be more intentional about color choice. 

**Trends over time:** I felt that by using a stacked bar graph to represent the data, the original chart, didn't allow the reader to assess trends within groups over time. I wanted my redesign to allow for this sort of trend detection. 

# Wireframing - First Iteration 
To make these changes, I sent out to draw a new version of the graph. I decided to group students and faculty by color, students were blue and faculty green, to reduce the brightness of the colors presented to the reader. Then, in my first iteration, I decided to make seperate bar charts for each category and lay them out next to each other. This was to allow the user to make comparisons over time. 

![Line Chart Sketch](unstacked%20bar%20wireframe.jpg)

# User Feedback 
After presenting this wireframe to my users, I recieved some extremely helpful feedback. They felt that having the bars seperately made it more difficult to see comparisions and trends over time. After some brainstorming, we came up with a new form of a line graph. This would allow the user to quickly and easily see comparisons between each group and more readily identify trends over time. They also felt that the colors were distracting and suggested moving to a grouping that had only 2 color. With this advice in hand, I went back to the drawing board and redrew my sketch with the new line graph in mind.  


# Wireframing - Second Iteration
This iteration implemented the changes discussed above. I used only two colors, one for on campus students and staff and one for off campus students and staff. I choose this color scheme because I noticed a large case differential bewteen these two groups and wanted to highlight the differences. As discussed above, I also used a line chart to allow for comparisons over time.  Finally, I moved the labels to the end of the lines themselves. This eliminated the need for an overbearing legend that takes up unnecessary space. 

![Bar Chart Sketch](Line%20Chart%20Wirefarm.jpg)

# User Feedback 
I once again presented my sketch to my users and this time recieved generally positive feedback. They felt that the graph told a clearer story by highlighting the discrepancy between on campus and off campus cases. They also felt that the graph quickly revealed the relatively large volatility in case numbers among students and allowed the user to see trends far more easily than my initial prototype. One point of confusion on this second iteration, was that with the new color scheme, it became difficult to differentiate between students and faculty. One user suggested using a different shape of the line to indicate this difference. I ultimately incorporated this suggestion by using a dashed line to represent the cases of faculty both on and off campus, and a solid line to show the equivalent measurement for students. This allows the user to quickly and easily differentiate between the faculty and student groups. 

# Making the Final Product 
As a result of this wireframing process, I ultimately chose to use [Flourish](https://flourish.studio/) to implement this solution and created a line chart that matched the specifications mentioned above. In making my final product I sought to:

**Tell a clear story:** the redesign highlights the differences between students and faculty on and off campus. This difference emerges as a clear narrative that the original visualization did not identify. 

**Allow for intuitive interpretation:** The dashed lines allow the users to quickly and easily determine which lines represent students and which represent faculty. Additionally, the labels eliminate the need for the large legend included with the original visualization. This allows the reader to quickly and easily interpet each line. 

**Identify trends in the data**: The line chart design allows the user to see trends more clearly than in the original graph. 

**Use color more intentionally:** the colors in this graph are taken directly from CMU's branding guide<sup>2</sup>. These more muted colors are less distracting to the reader and fit cohesively with the rest of the University's dashboard site. 

# The Final Product 

<div class="flourish-embed flourish-chart" data-src="visualisation/5321565"><script src="https://public.flourish.studio/resources/embed.js"></script></div>



References

1.  “CMU Cases Dashboard - COVID-19 Updates - Carnegie Mellon University.” CMU Cases Dashboard , Carnegie Mellon University, [www.cmu.edu/coronavirus/health-and-wellness/dashboard.html](www.cmu.edu/coronavirus/health-and-wellness/dashboard.html).  
2.  "Colors- The CMU Brand." Carnegie Mellon University, [www.cmu.edu/brand/brand-guidelines/visual-identity/colors.html](www.cmu.edu/brand/brand-guidelines/visual-identity/colors.html). 


[Return to home](https://danieldistler-1.github.io/Distler-portfolio/)
