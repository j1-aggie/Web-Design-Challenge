![image](https://user-images.githubusercontent.com/66078772/96190609-20d64380-0f08-11eb-9863-cf48b2df682b.png)


## Power Lifting Visualization Dashboard
* [Background](#background)
* [Link to Data Analysis Project](#analysis_project)
* [Visualization Dashboard Website](#website)
* [Requirements](#requirements)

## <a name="background"></a>Background

Data is more powerful when we share it with others. This Site is a dashboard website using visualizations I created using the most recent data from the power lifting orginization website to uncover patterns, observations, and insights about power lifting meets from years past.  The overall dataset was very large, so in order to work with managable data, I narrowed my focus on data for meets that happened in 2019 to October 2020 timeframe.   

## <a name="analysis_project"></a>Link to Data Analysis Project

For more information about the data analysis and visualization project I completed, you can go [here](https://github.com/j1-aggie/Web-Design-Challenge), which will take you to the github repository for the project.  Inside the repo you will find all the visuals and working files associated with this project. 

## <a name="website"></a>Visualization Dashboard Website

To create the visualization dashboard website, I used HTML, CSS, and Bootstrap. The website is currently deployed to GitHub Pages. The website works on a variety of screen sizes, from mobile to desktop. To check out the visualization dashboard website (it's gray theme), you can go [here](https://j1-aggie.github.io/Web_Design_Challenge/).

## <a name="requirements"></a>Requirements

The website consists of the following:

* A [landing page] containing:
  * An explanation/summary of the project.
  * Links to each visualization page.
* A [page]for each visualization containing:
  * A descriptive title and heading.
  * The plot/visualization.
  * A paragraph describing the plot and its significance.
* A [comparison] page that:
  * Contains all of the visualizations on the same page so you can easily visually compare them.
  * Uses a bootstrap grid to make the page responsive on a variety of screen sizes.
    * The grid is 2 visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A [data] page that:
  * Displays a responsive table containing the data used in the visualizations.
  * The data table on this page came from exporting the [.csv file] as HTML using the pandas ```to_html``` method, which generates a HTML table from a pandas dataframe. The code for this conversion is in a jupyter notebook file located in the repo.
  * The table is a bootstrap responsive table component.
* A navigation menu that:
  * Has the name of the site on the left of the nav, which allows users to return to the landing page from any page.
  * Contains a dropdown on the right of the navbar named "Plots", which provides links to each individual visualization page.
  * Provides two more links on the right: "Comparisons", which links to the comparisons page, and "Data", which links to the data page.
  * Background color changes going from a large to a small screen size.
  * Is responsive (uses media queries).

