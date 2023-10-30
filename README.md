# ascpt-ml-webinar-2023

This repository contains material for the 2023 ASCPT AI/ML Webinar hands-on section

## Instructions to ASCPT AI tutorial hands session

### Overview 

The code within this tutorial is using a machine learning method called xgboost, which will classify a set of patients into recurrence vs. non-recurrence for a breast cancer treatment. The data and code will be available publicly (i.e. this repository). 

### Requirements

Participants will need R(preferably the latest version) running in Rstudio with Rtools installed.  If you are new to R, or do not have a local copy on your computer, you can download them from the links below. If you are using a cloud platform, such as Metworx, you can skip all the installation requirements. If you need administrative permissions, please contact your IT group.  

R - https://cran.r-project.org/bin/windows/base/

Once R is downloaded and installed, you’ll need Rtools (needed for using certain Rpackages).  Follow the link below to download and install rtools.  You’ll need to match the version of R you have or just downloaded with the same version of Rtools. 
https://cran.r-project.org/bin/windows/Rtools/ 

Lastly, if you don’t have Rstudio (the most popular integrated development environment for R), download it here.  
https://posit.co/download/rstudio-desktop/

### Git hub account:
Github is a platform and cloud-based service for software development and version control using Git, allowing developers to store and manage their code. The R code, underlying data, and package versions are contained on a shared git repository for this tutorial. 

The file containing all the materials is publicly available on github so you should not need to create a github account in order to access it.  However, if you’d like to have an account, feel free to register (it’s free) by going to https://github.com/ and click sign-up in the upper right hand corner of the screen.

### Accessing the repository: 

To access the AI tutorial repository, use the link below.  Again, you should not need to a github account.    
https://github.com/metrumresearchgroup/ascpt-ml-webinar-2023

On this screen, there will be a green button called ‘Code’. Click on that and select ‘Download Zip’.  Place the zip file in a location of your choice, and unzip the project folder.

 
### Setting up the project:
In Rstudio, go to the folder containing the unzipped project folder (this example has Home > ASCPT ).  In that folder, click on the `ascpt-ml-webinar.Rproj` file.  
 
Once clicked, you will see the name of the project in the upper right hand corner of Rstudio

To open the script, locate the script folder from the file window in the lower right hand portion of the screen, click on it, and click on the file called `test-script.R`.  This is a test code that will diagnose if the main code will run.   Attempt to run all of this code.  If it runs fine, then all packages are set up.  If not, you will likely need to install some required packages.  The packages used are:

`knitr`, `tidyverse`, `tidymodels`, `xgboost`, and `here`

To install a package, type in the following code into the console and hit enter:

`Install.packages('insert_package_name_here')`

Once this is complete you should be able to begin run the code without error.

_Please note that each person’s computer, R version, and overall setup can be different.  Hence it is expected that there will be some issues in setting things up.  As communicated via ASCPT, please reach out to the coaches from the ASCPT email to help troubleshoot the set up portion.  It will be important to have your code fully set up at the start of the hands-on portion._

With the required packages installed, and test-code running, open the .Rmd file called workbook.Rmd.  The workbook.Rmd file contains nearly all the code to fit and evaluate the xgboost model fits on the dataset.  However certain portions of code are omitted as hands-on exercises during the hands-on session.  

Given that this is an Rmarkdown file, it has helpful functions to run the code more efficiently.  Code blocks are contained within the syntax of ```{r} and another ``` (see below).  The green arrow circled in red when clicked with execute all code in this chunk.  
 
Any line beginning with a ‘#’ is a comment, and is not considered code.  It can be used to write notes and help explain the code.  This has been done in this file to help participants understand what each piece of doing.  It is encouraged to look through each line carefully to best learn how the code is using the data and executing the various functions.  

Begin running the code by clicking on the green arrows.  Each code block that is run should result in no errors.  

The .Rmd rile called answer-script.Rmd has all of the code including the fill in portions completed.  Feel free to refer to this any time to see what the correct code is.   

For participants, please note that the final presentation during the webinar which contained several links to useful resources is located in the download project folder.

 








 


