# Web-Design-Challenge
Assignment # 10: Web Design / Web Visualization Dashboard

This is my overall 10th, first ‘Web’ (HTML, CSS) challenge. For this assignment / challenge, I created a visualization dashboard website using visualizations that I created in a past assignment (Python API: WeatherPy). Using ‘WeatherPy’ data and images, I plotted weather data.
In building this dashboard, I created individual pages for each plot and a means by which I can navigate between them. These pages contained the visualizations and their corresponding explanations. I also created a landing page – a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.
As a part of this assignment / challenge, there were the following website requirements that I met:
The website must consist of 7 pages total, including:
* A landing page containing:
	- An explanation of the project.
	- Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four visualization pages, each with:
	- A descriptive title and heading tag.
	- The plot/visualization itself for the selected comparison.
	- A paragraph describing the plot and its significance.
* A "Comparisons" page that:
	- Contains all of the visualizations on the same page so we can easily visually compare them.
	- Uses a Bootstrap grid for the visualizations.
		o The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A "Data" page that:
	- Displays a responsive table containing the data used in the visualizations.
		o The table must be a bootstrap table component.
		o The data must come from exporting the .csv file as HTML, or converting it to HTML.

The website must, at the top of every page, have a navigation menu that:
* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive and the navigation bar must have similar behavior as the screenshots "Navigation Menu".

As a part of assignment / challenge consideration, I did the following tasks:
* I used the weather data.
* I used Bootstrap. This included using the Bootstrap navbar component for the header on every page, the bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.
* I used a CSS media query for the navigation menu.
* I made sure that the website works at all window widths / sizes.

As extra / bonus challenge, I performed the following tasks:
* Used a Bootstrap theme to customize your website.
* Used meaningful glyphicons / material-icons next to links in the header.
* Added extra visualizations
* Created visualization navigation on every visualizations page with an active state.
