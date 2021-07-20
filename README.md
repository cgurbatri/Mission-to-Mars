# Mission to Mars

### Project Overview

The purpose of this project is to build a web application to scrape recent article headlines about Mars and images of Mars' hemispheres from multiple websites and display our findings in a HTML page. 

### Method
1. To obtain the latest news title and description, scrape the NASA Mars News Site (https://redplanetscience.com/).
2. To obtain the JPL Mars Space Image (Featured Image), use Splinter to navigate through https://spaceimages-mars.com/ and get the image URL.
3. To obtain Mars Facts, scrape from https://galaxyfacts-mars.com/, and store the data in an HTML table.
4. To obtain full-resolution images of Mars' hemispheres, scrape https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars, and save both the image URL and the title into a Python dictionary.
5. MongoDB and Flask was used to store the data and ultimately create an HTML page to display the above findings. 
6. Bootstrapping was used to make stylistic changes -- including decreasing button 'scrape new data' button size, adding borders to the table, making the hemisphere imaes thumbnails, and making the webpage responsive for multiple mobile devices. 

Below is an image of the final HTML page (Fig.1)
