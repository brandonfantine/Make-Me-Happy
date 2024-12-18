# Make-Me-Happy
More detalied instructions are on the .rmd.

1. Within R, import all libraries.

2. Importing Keras, TensorFlow, and Reticulate will create a Python environment in R

3. Run py_config() to verify both NumPy and TensorFlow are dowloaded

4. If not, identify the location of the python virtual environmnet (pythonhome:... in py_config()) and manually set that as the virtual environment

5. Similarly, find the path to the environment's version of Python (python:... in py_config()) and manually set that as well

6. Install numpy and tensorflow from within R

7. Verify the environment is operating as intended

8. Set the woring directory to the location of "GSS2022.dta" on your PC

9. Run lines 99 - 276

10. The ANN and Spectral Clustering algorithms should be good to go!

11. classification_report() runs the ANN

12. get_metrics() runs the Spectral Clustering algorithm

13. When merging any of the categories, add the name of the grouping to the list() in each Reduce function

14. To create your own data set, call clean_data() with an input vector detailing the names of all the columns of interest. Do not forget to use a dplyr pipe to deslect the ID column (%>% select(-id))
