# Creating a Shiny Web Application for global MPI

INTRODUCTION and MOTIVATION
---------------------------------------

This repository is to record the process to attempt to create a shiny web application for Multidimensional Poverty Index by using the data released by OPHI.

This is not about creating a Multidimensional Poverty Index. The idea is to create visualizations using the data (https://ophi.org.uk/multidimensional-poverty-index/mpi-resources/) that the OPHI (https://ophi.org.uk/) releases. In addition to creating interactive visualizations that I am familiar with, I will also try to incorporate techniques that are new to me (hopefully this will go well).


The following tables are available on the website. These tables down load as excel files. Each of these excel workbooks have multiple worksheet.

Table 1	National Results MPI 2019. 
Table 2	Other k Values MPI 2019. 
Table 3	Age Results MPI 2019.
Table 4	Rural/Urban Area Results MPI 2019.
Table 5	Subnational Results MPI 2019. 
Table 6	Changes over Time.
Table 7	All MPI Data Since 2010 December.

While making this web application I hope to utilize as much data as possible. 

I would like to mention that if anyone notices a mistake in the code or my understanding, please free to open an issue. All such mistakes will remain mine. Moreover, if there are any more efficient techniques that can be used instead of those I have employed here kindly let me know.


PROCESS (This section will be updated as I go)
--------------------------

I will start with data cleaning scripts, will probably make these as Rmd notebooks so the code is as explainable as possible. We will start work with Table1.

As on 3rd May 2020, cleaning of the table 1.1 of TABLE1 has been completed. I will proceed to create visualizations from this data (table1.1). Once that is done I will return to cleaning table 1.2 of TABLE1.... and so forth and so on. 

The URL for the uploaded interactive document (a Rmd file with shiny widget) is [this](http://ayush-patel.shinyapps.io/Interactive_Documnet_MPI?_ga=2.267160393.698749113.1588778285-1890707637.1585288669)

I have, at this point, encountered a problem. A interactive ggplot is not rendered in the markdown document as desired. I have posted a question on https://community.rstudio.com/, the link for the question is [here](https://community.rstudio.com/t/error-in-rendering-ggplot-with-shiny-components-widget-i-rmarkdown-file/64847)

The above mentioned problem is solved. The above link has the solution. Moving onnn. 
