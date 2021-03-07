# web-design-challenge

This challenge creates a website for the analysis done in the Weather API challenge.
There are 7 HTML pages as well as a CSS file.
The Navbar includes a "Latitude" tab that will return the user to the main Landing page from all pages, a drop down for the available plots and links to the Comparison and Data pages.
There is a sidebar that also includes all the plots available. If the user selects a plot from the sidebar, the plot page for that image will open. 
The data page include the cities.csv from the API challenge that saved as HTML using to_html with pandas. 
There is a media condition for screen widths smaller than 1000 px. This will change the color of the navbar and on the Comparisons page, will display the images in a singe column. 
