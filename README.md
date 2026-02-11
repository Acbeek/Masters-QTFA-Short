# My Project For Setting Up Your Cleaned Survey Database 

This project is designd for a specific database (rows and colluns), but might still be of use for quick cleaning and setting up. 
It is also aimed to help with a with a optimal research workflow.

## Usage

Click "Use this template" at the top of this page to create a new repository with the same folder structure.
***Also make a new R- workspace and save it in the main folder (the folder above docs, data, results.....etc***)


## Project Structure

The project structure distinguishes three kinds of folders:
- read-only (RO): not edited by either code or researcher
- human-writeable (HW): edited by the researcher only.
- project-generated (PG): folders generated when running the code; these folders can be deleted or emptied and will be completely reconstituted as the project is run.


```
.
├── .gitignore
├── CITATION.cff
├── LICENSE
├── README.md
├── requirements.txt
├── data               <- All project data, ignored by git
│   ├── cleandata      <- The final, canonical data sets for analysis (PG)
│   ├── raw 
|   |    |_________synthetic   <- synthethic made data for test purposes (RO) 
|   |                              consists of 3 smaller portion survey and 
|   |                              assessment datatbases.  
│   └── processed           <- Intermediate data that has been transformed. (PG)
├── docs               <- Documentation notebook for users (HW)
│   ├── manuscript     <- Here you can put your Manuscript source, e.g., 
|   |                     LaTeX, Markdown, etc. (HW)   
│   └── reports        <- Other project reports and notebooks (e.g. Jupyter, .Rmd) (HW)
├── results
│   ├── figures        <- Figures for the manuscript or reports (PG)
│   └── output         <- Other output for the manuscript or reports (PG)
└── R                  <- Source code for this project (HW)
    |____scr.          <- Scripts here you find the R test script

```

## License

This project is licensed under the terms of the [MIT License](/LICENSE).
