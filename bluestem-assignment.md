# Bluestem Assignment

In this assignment, you will create a document containing the following:

- A histogram of plant heights
- A bar chart of plant heights
- A histogram of rame lengths
- A bar chart of rame lengths
- Four figure legends, one for each of the figures listed above.
- A section titled **RESULTS** which includes:
    - A paragraph describing the difference in plant heights between lowland and upland areas, citing the first two figures and giving the results of the plant height *t*-test.
    - A paragraph describing the difference in rame lengths between lowland and upland areas, citing the last two figures and giving the results of the rame length *t*-test.

When you're done, submit the document to your instructor.

## Create Project

In RStudio Cloud, go back to the **Class Workspace** and click **Start** next to the project named **Bluestem Variation Project**.

Your assignment involves plotting and analyzing the data on intraspecific variation in big bluestem (*Andropogon gerardii*) plants that you collected during a field trip to the Regional Science Center. All the data were entered onto a single Excel spreadsheet.

Each row in the dataset represents an individual plant.

The variables in the dataset are:

- **location** ("lowland" vs. "upland")
- **plant_height** (plant height measured in cm)
- **rame_length** (rame length measured in mm)

## Create script

For this assignment, you can use the script you just created to analyze **beak length** as a starting point.

That script is available here: [Beak Length Script](beak-length-script.html)

1. Create a new R script, save it as `plant_height.R`
2. It's always easier to modify existing code than to create new code from scratch. To make sure you start off with a nice clean copy of the beak length code, follow [this link  &rarr;](lab1_beak_length_script.html) to copy the code for the beak length script
3. Use "find and replace" (the magnifying glass on the Source tab toolbar) to modify the script.
    - replace `finches` with `bluestem`
    - replace `beak_length` with `plant_height`
    - replace `outcome` with `location`
    - replace `died` with `lowland` and replace `survived` with `upland`
    - change the x- and y-axis labels on the histogram
    - change the x- and y-axis labels on the bar chart
    - change the name of the file you save the histogram as
    - change the name of the file you save the bar chart as
4. Save the `plant_height.R` script
5. Run the `plant_height.R` script, one line at a time, watching for errors. If you performed step 3 correctly, you shouldn't get any errors.
6. Insert the figures into your word document
    - Open your project folder in the Finder. 
    - Open your Word document.
    - Drag the figures from the Finder into your open Word document.


## Repeat for rame length

Now you can repeat the same process for rame length.

1. With your plant height script `plant_height.R` open go to **File > Save As** and save the new script as `rame_length.R`
4. Use Find and Replace to change `plant_height` to `rame_length` throughout.
4. Change the axis labels
3. Change the file names for saving
4. Change the figure titles (e.g. **Figure 1** becomes **Figure 3**, and **2** becomes **4**)


## Write figure legends

Write figure legends for each figure in your Word document.

For reference, here are the figure legends for the finch beak length analysis again:

<blockquote class="text-info">Figure 1. <strong>Distribution of beak lengths among medium ground finches (<i>Geospiza fortis</i>) grouped by outcome during the 1977 drought on Daphne Major, Galapagos archipelago.</strong> Each sample consisted of 50 individuals. Birds were banded and measured during 1975-1977 and resighted in 1978.</blockquote>

<blockquote class="text-info">Figure 2. <strong>Mean beak length varied between medium ground finches (<i>Geospiza fortis</i>) that survived or died during the 1977 drought on Daphne Major, Galapagos archipelago.</strong> Each sample consisted of 50 individuals. Birds were banded and measured during 1975-1977 and resighted in 1978. Error bars represent 95% confidence intervals.</blockquote>

For tips on how to write a good figure legend, see [Writing an Effective Figure Legend](https://www.aje.com/en/arc/writing-effective-figure-legend/). In general, a figure legend should provide the following parts:

- Title: A brief title that applies to the entire figure, including all panels.
- Materials and methods: A description of the techniques used.
- Results: A statement of the results that can be gleaned from the particular figure.
- Definitions: An explanation of features in the figure.

## Write a RESULTS section

Write a RESULTS section as you might for a report or peer-reviewed article. This section should include:

- A paragraph describing the difference in plant heights between lowland and upland areas, citing the first two figures and giving the results of the plant height *t*-test.
- A paragraph describing the difference in rame lengths between lowland and upland areas, citing the last two figures and giving the results of the rame length *t*-test.

For reference, here is the paragraph we wrote for the beak length analysis:

<blockquote class="text-info">Birds that survived the 1977 drought generally had longer beaks than those that died (Fig. 1). Mean beak lengths were 11.1 mm in survivors and 10.5 mm in non-survivors (Fig. 2).  This difference was stastistically significant according to a Welch's two-sample t-test assuming unequal variances (*t*=3.6335, *df*=94.807, *p*=0.0004539).</blockquote>


## Submit your assignment

Once you have all the components in your Word document, save it and submit it to your instructor.


## Saving your work

All of your files, including R scripts and image files, will be saved on RStudio Cloud. You can return any time to rerun your code, edit a script, or download a file.