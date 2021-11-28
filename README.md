# UFOs
## Project Overview
This project focuses on building a dynamic webpage of UFO sightings that accepts user inputs and adjusts the display and information for these inputs. The webpage is setup in a table format so users can filter UFO sightings based on different or multiple criteria such as event date, city, and shape.
## Resources
- Data Source: [UFO Data](https://github.com/weise142/UFOs/blob/main/static/js/data.js)
- Software: HTML, CSS, JavaScript, BootStrap, VS Code
## Results
### Link to the UFO Sightings Webpage
The deployed webpage is accessible at: https://weise142.github.io/UFOs/
### Index Page
This is the page that is initialized when you access the webpage from the above link or by clicking on the top of the navbar:
![This is an image](https://github.com/weise142/UFOs/blob/main/Top%20of%20site.PNG)
### Filters
There are multiple options for filters on the site; event date, city, state, country, and shape of the UFO sighted. These filters can be enter individually, using multiple options or using all filters at once:
![This is an image](https://github.com/weise142/UFOs/blob/main/Filtes%20x3.PNG)
![This is an image](https://github.com/weise142/UFOs/blob/main/Filters%20x5.PNG)
![This is an image](https://github.com/weise142/UFOs/blob/main/filtered%20data.PNG)
## Summary
- One of the drawbacks of this design is the difficulty for the user to know what to enter for filter parameters in order to get results. The user would need to go through the data to find the cities or data they want to find and then use that data parameter to filter so it requires the user to look over all of the data.
- A good way to address this problem would be to add drop down menus within the filter options to show what data is in the table and allow the user to more easliy choose how they would like to filter the information. This would allow the user to look over the information in a more high level way instead of having to look over all of the data to determine the best filter options for them.
- Another drawback that could be addressed is having a clickable button to both filter the data and to clear the data. The webpage is currently setup to understand the changes as you type them in and although this is a fine option, I find it(and believe most people do) find the user experience more pleasurable to click a button to get results. This would also help the user experience to clear filter data when there are multiple filter options.
