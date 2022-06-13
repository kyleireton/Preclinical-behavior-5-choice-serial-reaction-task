# Preclinical_neuroscience
RMarkdown pipelines for end-to-end wrangling, visualization, and analysis of preclinical data

## Before analysis, we need to read in and wrangle raw behavior data from our animal studies
# Use the "read in and wrangle" .RMd script

We can pull data from any number of downstream directories, if we specify a parent folder. Be sure to update the directory to list file names in the .RMd script. 
The latest files for the day will be added to previous day's cumulative data frame of all days. Update the filenames with today's date to stay current.

Once the script has finished, the output will be saved as a .csv for visualization and analysis. 

## Once read-in and wrangled, we can use our tidy data for visualization and analysis
# use the "visualize and analyze" .RMd script

The current data with all training sessions in a single tidy dataframe will be specified at the top of the script. Be sure the date in the name is current.
