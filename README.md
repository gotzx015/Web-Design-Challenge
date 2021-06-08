# Web-Design-Challenge

The WebVisualizations directory contains these files:

	* 7 html files	
	* assets directory which contains the images and css styling used in the html files
	* resources directory which contains csv file and jupyter notebook file

The website contains 7 pages total, including:

* A landing page (index.html) containing:
	* An explanation of the project
	* Links to each visualizations page. There is also a container containing preview images of each plot, and clicking an image should take the user to that visualization.
	
* Four visualization pages (cloudiness.html, humidity.html, max_temp.html, wind_speed.html), each with:
	* A descriptive title and heading tag.
	* The plot/visualization itself for the selected comparison.
	* A paragraph describing the plot and its significance.
	
* A comparisons page (comparison.html) that:
	* Contains all of the visualizations on the same page so we can easily visually compare them.
	* Uses a Bootstrap grid for the visualizations.
	* The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
	
* A data page (data.html) that:
	* Displays a responsive table containing the data used in the visualizations.
	* The table is a bootstrap table component
	* The table code comes from the jupyter notebook code that turns a dataframe into an html table 

* The website, at the top of every page, have a navigation menu that:
	* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
	* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
	* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
	* Is responsive (using media queries). The nav must have similar behavior as the screenshots.
