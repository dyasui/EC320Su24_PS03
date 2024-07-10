# Summer Econometrics Problem Set 3

## Instructions

First, download the repository by downloading the zip file from the green "Code" button. 
Unzip/extract the zip file.
It is a good idea to do this in a directory dedicated to this class.
An example of a file path to save this zip file in would be:
`~/Desktop/classes/EC320/PS03/`.
Once unzipped, open the `EC320Su24_PS03.Rproj` which will open RStudio.

Navigate to the Files tab in the bottom right panel of RStudio. 
You should see the following files:

```
.
├── EC320Su24_PS03.Rproj
├── R
│   └── PS03.Rmd
└── README.md

2 directories, 3 files
```

You will edit the file `PS03.rmd` with `R` code inside of code blocks,
and your explanation of your code and responses to the questions in text.
Once you have satisfactorily completed your answers, 
you will use the 'Knit' button in Rstudio (or the hotkey `Shift Cmd/Ctrl K`)
to compile your work as an html document.
You should find the resulting `PS03.html` document in the same folder 
(assuming you opened the project using the `EC320Su24_PS03.Rproj` file).

Please review the module 'Rmarkdown' on Canvas for an explanation of how to
write and compile R markdown documents.

### Data

We will be using the `HealthInsurance` dataset which is composed of 
cross-sectional survey data from the Medical Expenditure Panel Survey conducted in 1996.

It can be loaded into memory through installing the `AER` package from CRAN
(i.e., `install.packages("AER")`).
Then load the actual dataset with the function: `data("HealthInsurance")`
By default, the Rmd will do this for you. 
After downloading, simply knit the document (cmd/ctrl + shift + k)
and make sure everything looks okay.
