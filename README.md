# priasit.github.io
URL: https://priasit.github.io/

Title: Car Mileage Analysis

Caption: This narrative visualization provides Car Mileage Analysis to show the mileages of different car brands based on fuel types (2017 data).

Essay

1. Messaging:

A key element in assessing the EPA rating for a vehicle's average fuel economy (EPA combined) is the split between highway and city driving. Almost all cars and trucks deliver better fuel economy while cruising at 55 mph on the open highway than they do while stopping and starting at low speed on city streets. (Research: https://www.edmunds.com/fuel-economy/heres-why-real-world-mpg-doesnt-match-epa-ratings.html)

This narrative visualization plots the Average City Mileage and Average Highway Mileage of several brands of cars with different engine cylinder configurations to help viewers visualize comparative performances, filterable by fuel type.

2. Narrative Structure:

This narrative visualization follows an interactive slide show structure. Here the narrative follows a directed path through a slideshow metaphor. The slideshow is progressed with the capability of clickable buttons.

3. Visual Structure:

This narrative combines a linearly ordered (fuel type buttons) scatter plot of mileage data for several brands of cars, with color coded cylinder classification (legends) and an annotation to provide key reference point to performance. The X-axis of the scatter plot, represents the “Average City MPG” (MilesPerGallon) and the Y-axis represents the “Average Highway MPG”. Both the axes use a logarithmic scale set to base 10 over a domain set from 10 to 150. Each axis is set to four tick values at 10, 20, 50 and 100. The charts on all the scenes follow the same format as mentioned in the previous lines thereby helps in the smooth transition between scenes for the viewer. Viewers can get additional information using tool-tips. They will be pointed to tool-tip information based on cursor hover transformation to a pointer on information regions. They can traverse the scenes via clickable buttons.

4. Scenes:

This narrative visualization brings together four scenes to provide an analysis of average city and highway mileages for several car brands and cylinder configurations, based on fuel type. Each of these scenes are delivered as separate web pages following a consistent visualization scheme of scatter plot, legend, buttons, annotation, and tool-tips.

5. Annotations:

This narrative visualization establishes the most efficient car based on its city and highway mileages as an annotation in each scene. This annotation is established via a key reference message related to the most efficient car in that scene with a dashed line connector. These annotations provide static information.

6. Parameters:

This narrative visualization leverages fuel types as parameters to create the scenes

and for navigation. Within each scene cylinder configurations are used as parameters to classify car brands. Average city and highway mileages are used as parameters to plot performances of car brands based on fuel types and cylinder configuration.

7. Triggers:

This narrative visualization leverages onclick events on buttons for scene creation and navigation, and mouseover and mouseout events to provide specific information to viewers via tool tips. D3 callback functions are used to establish a custom color scheme for the scatter plot and the legends. D3 cursor property is used to change the cursor to a pointer to indicate clickable information availability on the scatter plot data. The clickable buttons change color to indicate selection.
