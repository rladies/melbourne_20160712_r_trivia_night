# r-trivia-night-melbourne2016
The draft of questions used in  R Trivia Night by R-Ladies Melbourne team


Potential questions for Trivia Night


1. Name two Australian women in Women in R Taskforce - Di Cook and Alicia Oshlack
2. What is the markup language of R Sweave documents?  - latex
3. What does Literate Programming mean? - having code & text in one document
4. How to change the layout of console, source, view and environment panels in R Studio? - tools > Global options > pane layout
5. What is the expression that signals skipping the current iteration and going to the next iteration in a loop? - next
6. What argument preserves the structure of a matrix, if the result of subsetting is a vector?  - m[ , 1, drop = FALSE]
7. The command to check if all rows in a matrix/data frame have non-NA values? - complete.cases()
8. What is the act of estimating a missing value from a neighbourhood group of values called? imputation
9. Shortcut to comment/uncomment a block of code - command/ctrl + shift + c
10. Shortcut for command execution in Windows -  ctrl + enter
11. An Rstudio Service that facilitates interactive data analysis:  a) Rstudio Server b) Shiny c) RMarkdown
12. The most popular CRAN package for data visualisation based on grammar of graphics - ggplot2
13. A R package for interactive data visualisation -plotly
14. R base package for faceted plots - lattice
15. What is the R package that provides an API for codes written in C/C++ programming languages? Rccp
16. What is the command set before generating random numbers that ensures reproducibility  -set.seed()
17. This markup enables users to embed code in the textual analysis/reports - Rmarkdown
18. The function used to extract code from Rmarkdown documents - purl()
19. A R package that is used for writing books and other publications - pandoc
20. What is a makefile? 
21. This package is used to predict gender based on the first names - genderizer
22. A package that is rapidly becoming popular for working with data frames - dplyr
23. What is %>% notation called in dplyr terminology? - pipe
24. Which code is more efficient ( m is a matrix)?
    for (i in 1:ncol(m)) { sum(m[ ,i]) }
    apply(m, 2, sum)
    colSums(m) - because of vectorisation
      
25.  Who is the author of Advanced R  & R Packages books? Hadley
26. Where the next UseR (UseR2017) conference is going to be held? Brussels, Belgium
27. When a library is loaded, it is added to the … search path
28. Sd in base R calculates the Standard Deviation. If a function with the similar name ‘sd’ is defined in the working directory, which of these two is evaluated when sd() is called?
    sd() in base R
    sd() defined in Working Directory 
29. Name one R package for Parallel programming/parallelization - snow, parallel
30. Name a function that lists files in a directory based on a pattern or a suffix list.files()
31. What is the the function that writes console output to a file sink()
32. Default delimiter in read.table() - tab
33. This character invokes help page for a function -?
34. Write down all possible package names that you can guess using any letters from the pool ( a pool of letters from which the names of up to 4 packages could be recovered - to be made)
35. What is the function used to execute command-line/shell commands from within R? - system() or system2()
36. What does CRAN stands for? The Comprehensive R Archive Network
37. What is a (CRAN) Task View? Each Task View is a category of R packages developed for similar purposes
38. How to install packages from CRAN and GitHub? install.packages() install_github()
39. What is git? A version control system
40. How many CRAN mirrors are there for Australia? 2- CRAN minors are country-specific repositories to download R
41. What does the following commands do?
    grep(pattern, x)   - returns index
    grep(pattern, x, value = TRUE) -returns the grepped value
    grep(pattern, x, invert = TRUE)  - returns everything but the one with matches to the pattern specified
    gsub()  - pattern replacement
    paste() vs paste0()  -  string concatenation 
42. Name all the apply family-functions apply, vapply, lapply, sapply
43. What is the difference between grep() and grepl()? Answer needed
44. Who invented the S programming language the predecessor of R? John Chambers
45. What is global environment? Same as the current working directory
46. A function that reads the lines of a file with unknown delimiter. - readLines()
47. How do you out of a get out of a misspelled command in the R console? Press esc


## Graphical round


Give a set of pictures from different ggplot geoms and they need to detect which geom has been used! 




