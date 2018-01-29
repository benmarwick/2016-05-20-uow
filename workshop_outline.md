2:00 - 2:15 Interacting with R & RStudio
2:15 - 2:30 Importing data
2:30 - 2:45 Inspecting data
2:45 - 3:00 Plotting data
3:00 - 3:15 Preparing to test
3:15 - 3:30 Testing for the difference in measurements of two samples
3:30 - 3:45 Testing for the difference in measurements of three or more samples
3:45 - 4:00 Testing for difference in counts
4:00 - 4:15 Fitting models


Interacting with R & RStudio BM
- console, script editor, plots, environment
- assigning values to objects, using objects
- commenting code
- using functions
- packages
- getting help: SO, swirl, https://www.rstudio.com/resources/cheatsheets/

Importing data BM
- working directory
- read.csv() & readxl::read_excel()
- str(), head(), tail(), names(), summary(), View()
- reshaping data with tidyr

Inspecting data SL
- indexing with [ , ] and $
- data structures: data frames, vectors
- vector types: numeric, character

Plotting data SL, BM
- base plot: scatter, boxplot, histogram
- ggplot2 geoms: bar, point, boxplot, density
- ggplot2 aesthetics: colour, size
- ggplot2 transformations and stats
- faceting

Preparing to test SL
- probability
- population
- sample
- p-values

Testing for the difference in measurements of two samples SL
- normality check:  shapiro.test() & qqnorm()
- parametric: t-test
- non-parametric: Wilcoxon test

Testing for the difference in measurements of three or more samples BM
- normality check: http://www.statmethods.net/stats/anovaAssumptions.html
- parametric: ANOVA & TukeyHSD
- non-parametric: Kruskal–Wallis test (post-hoc: http://rcompanion.org/rcompanion/d_06.html)

Testing for difference in counts BM
- rearranging data to get counts with dplyr
- chi-square

Fitting models
- lm() & interpreting summary() output (slope, residual, p, r^2)
- visual diagnostics of assumptions with ggfortify::autoplot 
