# NETFLIX-Pymaceuticals-Continued-Making-Matplotlib-Magic
## Instructions:

**Part 1:** Regenerate Data and Create Detailed Subplot

1. Using the supplied starter code, re-import, clean and visualize the drug regimen data from the previous skill-drill. 

2. Use `plt.subplot()` to create a figure with a 2x2 subplot layout, where the first plot is our original boxplot from the previous skill drill.

   * **Note:** All four subplots should share the same axes and labels. In doing so, each plot brings more context to the next. 

3. For the second plot within the subplot, create a horizontal bar chart showing the largest final tumor volume for each drug regimen.

   * **Hint:** You can use the `tumor_vol_list` from the starter code to retrieve final tumor volume for your calculations.

4. For the third plot within the subplot, create a scatter plot that shows final tumor volume by drug regimen and colored by the mouse `Sex`. 

   * **Hint:** The most straightforward way to plot multiple categories (such as the mice's `Sex`) is to plot multiple scatter plots, one for each category, using a loop.  

5. For the fourth plot within the subplot, create a scatter plot that shows final tumor volume by drug regimen and colored by mouse `Age_months` using a colorbar. 

   * **Hint:** Check out [this article](https://jakevdp.github.io/PythonDataScienceHandbook/04.07-customizing-colorbars.html) on how to add and customize a colorbar for your plot. Also check out the [colorbar documentation](https://matplotlib.org/3.3.3/api/_as_gen/matplotlib.pyplot.colorbar.html?highlight=colorbar#matplotlib.pyplot.colorbar) to see how to add a label to your colorbar.

   * **Note:** If your plots are crowded or overlapping on your screen, you can adjust the layout of your subplot using `plt.subplots_adjust()`. For most people, `plt.subplots_adjust(top=2.5,right=2.5)` should be sufficient.

**Part 2:** Critical Thinking

1. Now that you have created your subplot looking at final tumor volume versus drug regimen, it is time to analyze your visualizations. Think about the following questions while you review your subplot. (Note: no need to write and submit your answers. In upcoming skill drills, we will begin to document our observations more thoroughly.)

   * Take a look at the original boxplot. Do you notice any datapoints that stand out from the box and whiskers? These are known as *outliers*. We will learn more about them in the next unit.

   * Take a look at the horizontal bar plot. Are there any drug regimen with substantially smaller maximum final tumor volume? How are they related to the drug regimens that stand out in the boxplot?

   * Look at the scatter plot colored by `Sex`. Across all of the drug regimen, does the distribution of mouse `Sex` look different in any regimen? Why or why not?

   * Lastly, look at the scatter plot colored by `Age_months`. Across all of the drug regimen, does the distribution of mouse `Age_months` look different in any regimen? Why or why not?
