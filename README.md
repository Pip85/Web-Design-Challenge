# **Web-Design-Challenge**

Student project - create website to showcase weather data visualizations created in practice-api exercise<br>
https://github.com/Pip85/practice-api<br>

## **software/tools used**

* pandas:  https://pandas.pydata.org/<br>
* Jupyter Notebook:  https://jupyter.org/<br>
* HTML 5<br>
* Bootstrap 5<br>
* CSS

## **resources**
* Background and datasets provided as part of Georgia Tech Data Analytics Boot Camp:<br>
* © 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.<br>
* csv file created during practice-api exercise (https://github.com/Pip85/practice-api):<br>
* https://github.com/Pip85/Web-Design-Challenge/blob/main/resources/cities.csv
  
## **project background**

### **Latitude - Latitude Analysis Dashboard with Attitude**

* For this homework we'll be creating a visualization dashboard website using visualizations we've created in a past assignment. 

* In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### **Website Requirements**

The website must consist of 7 pages total, including:

* A landing page containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four visualizations, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A comparisons that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A data page that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component. 
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. 

* The website must, at the top of every page, have a navigation menu that:
* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots 

* Finally, the website must be deployed to GitHub pages.

## **acknowledgement**

* Background and datasets provided as part of Georgia Tech Data Analytics Boot Camp:<br>
* OpenWeatherMap.org. (2012). Сurrent weather and forecast. Retrieved from [https://openweathermap.org/](https://openweathermap.org/)
<br>
* © 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.

* Project Author:  Valerie Pippenger - https://github.com/Pip85

## **process**
* Read cities.csv into pandas and created a data frame. 
* Exported data frame to an HTML table.
* Created landing page with summary of analysis and 4 visualizations of humidity, wind speed, cloudiness and maximum temperature derived from previous practice-api exercise (https://github.com/Pip85/practice-api)
* Website was created using HTML, Bootstrap & CSS.
* The website includes a navbar created with Bootstrap & CSS for navigating the visualizations.

![landing]()

* A series of 4 plot pages was created to show each visualization along with a short summary.  Each plot page also includes a small inset of all 4 plot pages to use as navigation between the 4 plots.  Navigation to the plots can also be found under the Plot dropdown in the navigation bar.


![max_temp]()

![humidity]()

![cloudiness]()

![wind_speed]()

* Created Comparison page of all 4 visualizations together

![comparison]()

* Created Data page with table of cities.csv content.

![data]()

* The site was deployed using github pages.

