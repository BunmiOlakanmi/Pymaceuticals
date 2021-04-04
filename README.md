# Pharmaceuticals: Comparison of Drug Performance

The purpose of this project was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens, used on 249 mice identified with SCC tumor growth. 

![Laboratory](Images/Laboratory.jpg)

### Tools used in this project
1. Python Libraries:
    - config
    - matplotlib.pyplot
    - pandas
    - numpy
    - scipy.stats
2. Jupyter Notebook

The project requires to clean the data by checking for any mouse ID with duplicate time points in order to remove any data associated with that mouse ID.
The cleaned data were used to do the following:
* Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
* Generate a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows  the number of total mice for each treatment regimen throughout the course of the study.
* Generate a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.
* * * **NOTE:** These plots are identical.
<img width="449" alt="Screen Shot 2021-04-05 at 6 29 25 AM" src="https://user-images.githubusercontent.com/71471355/113508928-fad14980-950f-11eb-8e05-f2ac93aa8914.png">
<img width="444" alt="Screen Shot 2021-04-05 at 6 29 43 AM" src="https://user-images.githubusercontent.com/71471355/113508929-fb69e000-950f-11eb-9ffa-9ba12e0f2002.png">

* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 
* Then, calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
* Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlighted any potential outliers in the plot by changing their color and style.
<img width="497" alt="Screen Shot 2021-04-05 at 6 30 48 AM" src="https://user-images.githubusercontent.com/71471355/113508904-decda800-950f-11eb-849a-fa113dcb0d7a.png">

* Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.
<img width="461" alt="Screen Shot 2021-04-05 at 6 31 13 AM" src="https://user-images.githubusercontent.com/71471355/113508899-d4aba980-950f-11eb-81f9-e17516bc8fa1.png">

* Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. 
* Then, plot the linear regression model on top of the previous scatter plot.
<img width="460" alt="Screen Shot 2021-04-05 at 6 31 44 AM" src="https://user-images.githubusercontent.com/71471355/113508895-cb224180-950f-11eb-97b1-cd018e582970.png">

#### Instruction

* The notebook contains three observations or inferences that can be made from the data.

* My plots include properties such as: plot titles, axis labels, legend labels, _x_-axis and _y_-axis limits, etc.


