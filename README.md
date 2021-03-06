# 02-DataVis-5ways

Assignment 2 - Data Visualization, 5 Ways  
===

# R + ggplot2

R is a language primarily focused on statistical computing.
ggplot2 is a popular library for charting in R, having never used R before, I was a bit apprehensive, however, it turned out to be relatively
straightforward to use. The nicest part of R in my opinion is the ease at which it converts the csv file, as in the user does not need to
remove incomplete rows. The built in ggplot features were used to create the different sizes, the colors were selected using a color picker on the 
original graph given in the assignment in an attempt to create an image as close to the original as possible.

For R I used information from this webpage: https://statisticsglobe.com/plot-in-r-example as well as the R documentaion on import and graphing: http://lib.stat.cmu.edu/R/CRAN/manuals.html

![RStudioImage](img/Assignment2Rplot.png)

# Excel

Excel is a very easy to use program that I am very familiar with, however, its usefullness peters out as you get into more complicated situations.
I imported the csv file, removed all of the columns that I was not using, and ordered the data by manufacturer, I used the excel scatterplot with 3
data inputs to assign the weight/25 to be the size of the width of the dots scaled to 25, this allowed me to make the graph increase the size of the dots as the
weight increased.

![ExcelImage](img/Assignment2Excel.png)

# Python + matplot

Python is a versitile language that is very intuitive and has a lot of great addons, such as matplot. 
I used matplot to make a plot, it is very simple to use matplot, and nothing was needed to take care
of the rows with missing variables. I created a color set and mapped the classes to the colors, I also
used viridis in the cmap to automatically change the intensity of the color.

For matplot I used information from: https://kanoki.org/2020/08/30/matplotlib-scatter-plot-color-by-category-in-python/

![PythonImage](img/PythonAssignment2Image.png)

# Tableau

Tableau is a highly intuitive data analysis program, it is probably the single most user friendly
interface that I have ever laid my hands on. I downloaded the csv, tableau automatically converted 
it to a table, and I dragged and dropped the columns I would like to use for the x and y axis,
tableau also makes it so you can drag and drop columns to use as data markers, which I did for both
size and car company, making the dot size increase with weight and color coding the dots by company.

![TableauImage](img/TableauImage.png)

# d3

d3 proved very challenging for me, the whole process of making the scales of the graph as global functions
because the file has not made that section yet is very confusing to me. Additionally, the process of 
inverting axes was hard. I ended up making the graph by taking the csv file and extracting only the
rows which had an MPG, the categories from each row were put in variables and the graph was made of the variables.
I was not able to change the color or increase the size of the dots based on the weight, but I beleive that I will
be able to do so going forward.

Information for making the graph was taking from Learn d3.js by Helder da Rocha 
(It is a physical book)

![d3Image](img/d3Image.png)

## Technical Achievements
- Used the three input excel scatterplot to make the size of the dots increase with vehicle weight.
- Created the color set and mapped the colors to it in python.
- Used viridis for the cmap.
- flip the axes of the d3 graph
- create a grid in the d3 graph
- make the scales of the d3 graph global functions

### Design Achievements
- Downloaded the given graph and used a color picker to select colors for the Rplot graph
