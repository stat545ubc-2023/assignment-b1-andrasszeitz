Created October 31, 2023 Last updated October 31, 2023

This is the repository of Andras Szeitz, Ph.D. student in the GSAT program.

Project Title
STAT 545B 102 2023W1 Exploratory Data Analysis - DATA ANALYSIS II

Description
This project describes making a function in R, documenting and testing it.

Location
https://github.com/stat545ubc-2023/assignment-b1-andrasszeitz

Dependencies and Installation
The following OS version, software, libraries, etc., needed to use the cloned version of repository.

Windows 10 Pro or higher
R-4.3.1 or higher (https://posit.co/download/rstudio-desktop/)
RStudio 2023.09.1 Build 494 or higher (https://posit.co/download/rstudio-desktop/)

Anaconda Navigator (https://www.anaconda.com/download/)
Jupyter (Jupyter Notebook) and R Kernel:
In Anaconda prompt, change directory and type
C:\Program Files\R\R-4.3.1\bin\R.exe
in the Anaconda prompt, type
install.packages("IRkernel") and IRkernel::installspec()
in the Anaconda prompt, type
jupyter lab
this will run Jupyter Lab (Pyton and R kernel)

Git and Github
Register an account at github.com
https://happygitwithr.com/github-acct.html
Install Git
https://happygitwithr.com/install-git.html
Configure your Github account
https://happygitwithr.com/hello-git.html
Set up GitHub Personal Access Token (PAT) to sync GitHub (github.com) with files on your computer.
Go to https://github.com/settings/tokens and click “Generate token”. Describe the token’s purpose in the Note field, e.g. “personal-pcbook”. Select “repo”, “user”, and “workflow” for scopes.

Open R,  install the gitcreds package by running install.packages("gitcreds"))
Execute 'gitcreds::gitcreds_set()' and enter the PAT that you previously made when prompted. 

Executing the programs
Configuring R and Git in RStudio
Selecting R
Open RStudio, go to Tools -> Global options -> R General
select R location, for example 'C:\Program Files\R\R-4.3.1'

Selecting Git
Open RStudio, go to Tools -> Global options -> Git/SVN ->
select Git location, for example 'C:/Program Files/Git/bin/git.exe'

This repository contains the following folders and files.

Folders:
assignment-b1-andrasszeitz_files

Files:
README.md
assignment-b1-andrasszeitz.Rmd
assignment-b1-andrasszeitz.md

File ‘assignment-b1-andrasszeitz.Rmd’ contains the 'STAT 545B 102 2023W1 Exploratory Data Analysis - DATA ANALYSIS II' data before knitting to a md file.

File ‘assignment-b1-andrasszeitz.md’ contains the tag release version of 'STAT 545B 102 2023W1 Exploratory Data Analysis - DATA ANALYSIS II' document.

Authors
Andras Szeitz, Ph.D. student, UBC, GSAT program

Cloning this repository:
• Using HTTPS: https://github.com/stat545ubc-2023/assignment-b1-andrasszeitz.git
• Using SSH: git@github.com:stat545ubc-2023/assignment-b1-andrasszeitz.git
• Using GitHub CLI: gh repo clone stat545ubc-2023/assignment-b1-andrasszeitz
• Open Git Bash.
• Change the current working directory to the location where you want the cloned directory.
• Type git clone, and then paste the (HTTPS) URL you copied earlier
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
• Press Enter to create your local clone as follows

$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY

Cloning into Spoon-Knife...
remote: Counting objects: 10, done.
remote: Compressing objects: 100% (8/8), done.
remove: Total 10 (delta 1), reused 10 (delta 1)
Unpacking objects: 100% (10/10), done.

Version History
0.2 Various bug fixes and optimization
See commit change or See release history
0.1 Initial Releas

Acknowledgments
Instructor
Dr. Lucy Gao
Assistant Professor 
Department of Statistics
The University of British Columbia

Teaching Assistants
Asfar Lathif
Emily Brown
Erick Isaac Navarro Delgado

