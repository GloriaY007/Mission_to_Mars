# Mission to Mars

This project is for Robin, who loves astronomy, and wants to work for NASA one day. She has decided to use a specific method of gathering the latest data: web scraping. Using this technique, she has the ability to pull data from multiple websites, store it in a database, then present the collected data in a central location: a webpage.

## Scrapping

### 1. NASA Mars News
We start with importing dependency in Jupiter notebook and write a script to collect the latest News Title and Paragraph Text.

### 2. JPL Mars Space Images - Featured Image
We write a sript to find the image url for the current Featured Mars Image and assigns the url string of the full size image.

### 3. Mars Facts
We write a script to visit the Mars Facts webpage and uses Pandas to scrape the table containing facts about the planet including Diameter, Mass, etc.

### Mars Hemispheres
We write a script that visits the USGS Astrogeology site and obtains the full resolution images for each of Mar's hemispheres.

### MongoDB and Flask Application
Finally, we use MongoDB and Flask to display the results. First, install MongoDB. Once MongoDB is installed run the command mondgod on bash. 
