# Spatiotemporal Data Analysis

## Overview
This is a graduate course taught as GEOG696c (the physical geography seminar) at the University of Arizona.  The class was last taught in Fall 2023.  The full syllabus is available [here](https://github.com/kanchukaitis/spatiotemporal_data_analysis/blob/c70773af70425a7ffa5c0f13320f57c5dafd5565/geog696c_syllabus.pdf).

This course is designed as a graduate level class in a workshop format to give students a theoretical framework, practical experience, expert knowledge, and statistical tools for analyzing spatiotemporal datasets. Topics include basic matrix algebra and statistics, exploratory data analysis, field correlation and regression analysis, autocorrelation and its statistical consequences in time and space, parametric and non-parametric significance testing and error analysis, empirical orthogonal functions including rotation, singular spectrum analysis, maximum covariance and canonical correspondence analysis, and traditional and multitaper spectral analysis.  The course encompasses instruction and training in Python and in the use and manipulation of large multi-dimensional datasets.

The major outcome for the class for each student will be a new and independent analysis of a substantial space-time dataset, a formal manuscript describing the motivation, methods, and results of this analysis, and a professional oral presentation.  Students are encouraged to bring with them or seek out data relevant to their research to use for their final project.  Ideally, students' final projects will provide the material for a thesis chapter and/or peer-reviewed article. 

The course was inspired by and initially based on an objective analysis/spatiotemporal data analysis class taught by [Mike Evans](https://www.geol.umd.edu/~mnevans/).
 
## General Schedule

August 23 to August 31 - [Introduction to Python](https://github.com/kanchukaitis/spatiotemporal_data_analysis/tree/819d6db721c34aa39680e7ff4f72a57fe6611cb9/01_introduction_to_python), [NumPy](https://github.com/kanchukaitis/spatiotemporal_data_analysis/blob/main/01_introduction_to_python/introduction_to_numpy.ipynb), [Pandas](https://github.com/kanchukaitis/spatiotemporal_data_analysis/blob/main/01_introduction_to_python/introduction_to_pandas_part_1.ipynb), Matplotlib ([Part 1](https://github.com/kanchukaitis/spatiotemporal_data_analysis/blob/main/01_introduction_to_python/introduction_to_matplotlib_part_1.ipynb) and [Part2])(https://github.com/kanchukaitis/spatiotemporal_data_analysis/blob/main/01_introduction_to_python/introduction_to_matplotlib_part_2.ipynb) and [Linear Algebra](https://github.com/kanchukaitis/spatiotemporal_data_analysis/tree/main/02_linear_algebra)

August 31 to September 12 - Variance, covariance, and correlation -- [Part 1](https://github.com/kanchukaitis/spatiotemporal_data_analysis/blob/main/03_covariance/covariance_correlation.ipynb) and [Part 2](https://github.com/kanchukaitis/spatiotemporal_data_analysis/blob/main/03_covariance/covariance_correlation_part2.ipynb) -- plus an [introduction to `xarray`](https://github.com/kanchukaitis/spatiotemporal_data_analysis/blob/main/01_introduction_to_python/introduction_to_xarray.ipynb)

September 14 to September 21 - Introduction to Empirical Orthogonal Functions -- Part 1 and Part 2 -- plus mapping with Matplotlib and Cartopy

September 21 to September 28 - EOF significance, meaningfulness, and interpretation

September 28 to October 10 - EOF interpretation and orthogonal rotation

October 17 to October 19 - Analysis of coupled fields

October 19 to October 26 - Field correlation, compositing, field significance, and false discovery

October 31 to November 7 - Spectral analysis 

November 9 to November 14 - Frameworks for spatiotemporal data analysis

November 14 to December 5 - Student project work and presentations

## Recommended Software Installation 

[This Youtube video](https://www.youtube.com/watch?v=h1sAzPojKMg&ab_channel=VisualStudioCode) from Visual Studio Code (the integrated coding environment we'll use in this class) can get you up and running pretty quickly . They show installation in Windows, so macOs will be slightly different.  We'll also go this **live** in class on August 24th. 

Here are the basic steps:
* Install Python using Miniconda (recommended for this class: https://docs.conda.io/en/main/miniconda.html) or the full individual Anaconda distribution (https://www.anaconda.com/download) for your operating system.  Both are free.  **Note that if you have an older operating system, the current versions of Miniconda might not work on your system.** 
* From the newly installed Conda prompt, from within Python, or from your terminal, [install iPython](https://ipython.readthedocs.io/en/stable/install/install.html#quick-install).
* Install Juypter Notebooks: https://jupyter.org/install
* Install Visual Studio Code itself (https://code.visualstudio.com/download) for your system
* Within Visual Studio Code, install the Python extensions (from Microsoft)
* Test your system 

## License

This work is licensed under a <a rel="license" href="https://creativecommons.org/licenses/by-nc/3.0/us/">Creative Commons Attribution-NonCommercial 3.0 License (CC BY-NC 3.0 US)</a>. 

You are welcome to use any of this material, so long as it is for non-commercial purposes.
