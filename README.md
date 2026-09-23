# T01_104395111
# Appliance Energy Consumption Website
Prepared by: Filicia Jing Xuan WONG (Student ID: 104395111)

Overview of the Website:
This website is an educational website that showcases household appliance energy consumption in the Australian market, with a focus in television energy data.

How to Run:
Open the index.html through the link provided in a browser.

Data Story:
- Audience: Everyday Australian consumers researching TVs before purchase.
- Audience Interest: Budget-conscious and want to minimise long-term electricity costs. The charts help them see which technologies, sizes and brands use the least power.
- The story: Question 1 to question 3 show what is on the market mainly stating LCD (LED) is 83.02% of models whereas 55, 65 and 75 inch are the most common sizes. Question 4 to question 5 show what it costs in power with LCD being of the least usage, OLED the most, and power is seen to rise with size. In addition, question 6 to  question 7 show that size does not detremine efficiency and that brands may differ, so buyers should compare star ratings and figures of power.

About the Data
- Data source: The data source is publicly available “Energy Rating Data for household appliances – Labelled Products" at http://data.gov.au/ with the category television. 
- Data processing: The data was cleaned and analysed in Knime. Models were counted by technology, size and brand, and median or average power was calculated. Finally, charts were exported as PNG.
- Privacy: The data describe TV models and not individuals. Thus, the site collects no user data.
- Accuracy and limitations: The values are reported by manufacturers through cover models, not sales. Moreover, the real power used depends on the settings and viewing habits of consumers. Lastly, snother limitation is that larger screens have few models.
- Ethics: The data are public and credited on the About Us page. Explanations describe patterns without endorsing any brand, and GenAI usage is disclosed below.

Usage of GenAI:
- GenAI was used during the debugging of the CSS codes, especially at the @media rules for 768px and 500. It was used to properly code the website's responsiveness to achieve the proper collapsiing of the information cards at homepage and also the navigation bar as the screen size decrease or is minimized.
- GenAI was also used for the "click-to-navigate" handler in script.js
- GenAI was used to set the overall theme and colour scheme of the website design to ensure that the colour matches the logo

Written by Filicia:
- The HTML structure along with its content across the pages index.html, televisions.html and aboutus.html was written by me.
- Base CSS layout and design was coded by me. For instance, spacing, information card structure and setup of responsive breakpoints. 
- Added the images and its explanation into HTML files.

Reflection:
Throughout this assignment, GitHub copilot was the most useful. It is especially useful for CSS debugging when achieving correct responsive breakpoints. For instance, the wrapping of the navigation bar and collapsing of information card into a single column when screen size is minimised. Many trial and errors of adjusting the dimensions between px and % values were done before the screen responsiveness was acceptable for both 768px and 500px breakpoints. In addition, the "click-to-navigate" handle was more streaightforward. In conclusion, I have written the HTML and the core of CSS with the usage of GenAI mainly to debug the code in which I have understood and adjusted the generated content instead of acccepting the answer without further analysis.

Credits
Created by: Filicia Jing Xuan WONG. GenAI tools were used to help draft starter code and placeholder text. 