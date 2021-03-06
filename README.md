# D3 DataJournalism

Tasked with analyzing the current trends shaping people's lives, as well as creating charts, graphs, and interactive elements to help readers understand your findings for a major metro paper.

The editor wants to run a series of feature stories about the health risks facing particular demographics. Sifted through information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

### Step 1
- Create a scatter plot between two of the data variables such as Healthcare vs. Poverty or Smokers vs. Age.
  - Create a scatter plot that represents each state with circle elements. Code the graphic in the app.js file of your directory—make sure you pull in the data from data.csv by using the d3.csv function.
  - Include state abbreviations in the circles.
  - Create and situate your axes and labels to the left and bottom of the chart.
  - Note: You'll need to use python -m http.server to run the visualization. This will host the page at localhost:8000 in your web browser.
  
### Step 2
- You're going to include more demographics and more risk factors. Place additional labels in your scatter plot and give them click events so that your users can decide which data to display. Animate the transitions for your circles' locations as well as the range of your axes. Do this for two risk factors for each axis.
- While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. Enter tooltips: developers can implement these in their D3 graphics to reveal a specific element's data when the user hovers their cursor over the element. Add tooltips to your circles and display each tooltip with the data that the user has selected.
