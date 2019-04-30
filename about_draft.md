---
layout: page
title: 070116-1 AR Methodological Workshop (2019S)
subtitle: DH Methods — Historical Inquiries with R
---

# 070116-1 AR Methodological Workshop - DH Methods: Historical Inquiries with R (2019S)

* Instructor: Dr. Maxim Romanov, [maxim.romanov@univie.ac.at](maxim.romanov@univie.ac.at)
* Office hours: We 2–3pm (or by appointment)
* Office: Hauptgebäude, Room O2.121 (2.Stock, Stiege 9)

# Course

* u:find Link: <https://ufind.univie.ac.at/en/course.html?lv=070116&semester=2019S>
* Meeting time: Tu 15:00-16:30
* Meeting place: Hörsaal 30 Hauptgebäude, 1.Stock, Stiege 7

# Aims, contents and method of the course

The course will offer a practical introduction into R programming language, which is currently one of the most popular choices of humanists interested in investigating humanities problems with computational methods. Following the general introduction, the course will cover a series of cases of how one can analyze textual, historical and spatial data with statistics-based and visual methods.

# Course Evaluation 

Assessment will be based on class participation, homework assignments, and a final project.

# Class Participation

Each class session will consist in large part of practical hands-on exercises led by the instructor. BRING YOUR LAPTOP! We will accommodate whatever operating system you use, but it should be a laptop rather than a tablet. Don’t forget that asking for help counts as participation!

# Homework

* For each class you will be creating reports, which can be then submitted as PDFs (email or Moodle), or published as your own Shiny web application.
* DH is a collaborative field, so you are most welcome to work on your homework assignments in groups, however, you must still submit them individually. That is, if a groups of three works on one assignment, there must be three separate submissions by each member of the group. 

# Final Project

* The final project is a portfolio of detailed reports for each class. You are highly encouraged to use your own dataset for the final project and your weekly assignments.

# Study Materials

* Jockers, Matthew L. *Text Analysis with R for Students of Literature.* New York: Springer, 2014. (*Moodle*)
* Arnold, Taylor, and Lauren Tilton. *Humanities Data in R.* New York, NY: Springer Science+Business Media, 2015.
* Healy, Kieran *Data Visualization: A Practical Guide*, <http://socviz.co/>
* Check <https://bookdown.org/> for more books on R

# Software, Tools, Technologies

* R <https://www.r-project.org/>
* R Studio <https://www.rstudio.com/>
* Different packages for R:
	* swirl <https://swirlstats.com/>
	* knitr <https://yihui.name/knitr/> 
	* R markdown <https://rmarkdown.rstudio.com/>, <https://bookdown.org/yihui/rmarkdown/>
		* Additionally, bookdown <https://bookdown.org/>, <https://bookdown.org/yihui/bookdown/>
	* tidyverse <https://www.tidyverse.org/>
	* ggplot2 <https://ggplot2.tidyverse.org/>
		* Tutorial: <http://r-statistics.co/ggplot2-Tutorial-With-R.html>
		* Useful cookbook: <http://r-statistics.co/Top50-Ggplot2-Visualizations-MasterList-R-Code.html>
	* ggvis <https://ggvis.rstudio.com/>, <https://ggvis.rstudio.com/ggvis-basics.html>
	* shiny <https://shiny.rstudio.com/>
	* stylo <https://computationalstylistics.github.io/>, <https://sites.google.com/site/computationalstylistics/stylo>


# Schedule for the R Course

## Brief Schedule

- `[#01]` Basics: Introduction --- *Making sure everything works*
- `[#02]` Basics: Worksheets --- Getting Familiar with R, Data Structures and Subsetting (WS1 and WS2)
- `[#03]` Basics: Data manipulation
	- WS3 and WS4
	- HW: EDA from swirl() 
- `[#04]` Basics: Visualizing Data
	- Basic Principles and Practice (WS5)
	- HW: Functions WS6 can be given as homework
- `[#05]` Basics: simple cartograms (mapping)
	- workbook with Pleiades data
	- HW: data from `europop` and *boskers* dataset
- `[#06]` Data: preparing, collecting, organizing
- `[#07]` Data: modeling
- `[#08]` Texts: micro, meso, macro
- `[#09]` Texts: topic modeling
- `[#10]` Texts: stylometry
- `[#11]` SNA: basics & practice
- `[#12]` SNA: modeling & challenge
- `[#13]` SNA and Maps: ?
- `[#14]` Project Presentations

* Units:
	- basics
	- data
	- texts
	- mapping data
	- social network analysis

## Notes:

* Tilton's book has 100 programming exercises -> I am sure they can be worked into workbooks (for the next time > prep workbooks for each class);
	- these are to serve as foundation for my Islamic World Analysis class/book.
* Healy's book has lots of materials that can be worked into the my course materials.

## Detailed Schedule

### `[#01]` Introduction --- *Making Sure Everything Works*

- Installing `R`: <https://cloud.r-project.org/>
- Installing `RStudio`: <https://www.rstudio.com/products/rstudio/download/>
- Basic commands in `R`
- Writing `R markdown` documents

### `[#02]` NO CLASS

- Homework (for 19.03):
	- `swirl` tutorials
		- > reports in `R markdown`
	- Jockers's book: Part I --- Micro Analysis
		- > reports in `R markdown`

### ` Tu 19.03 [#02]` Data

- Creating, Collection and Organinzing Data
	- **READING**: Broman, Karl W., and Kara H. Woo. “Data Organization in Spreadsheets.” *The American Statistician* 72, no. 1 (January 2, 2018): 2–10. <https://doi.org/10.1080/00031305.2017.1375989>.


### ` Tu 26.03 [#03]` 

### ` Tu 02.04 [#04]` 

### ` Tu 09.04 [#05]` 

### ` Tu 30.04 [#06]` 

### ` Tu 07.05 [#07]` 

### ` Tu 14.05 [#08]` 

### ` Tu 21.05 [#09]` 

### ` Tu 28.05 [#10]` 

### ` Tu 04.06 [#11]` 

### ` Tu 18.06 [#12]` 

### ` Tu 25.06 [#13]` 



# Working Notes

## Topics to cover:

1. R basics:
	- Basic intro;
		- Interactive tutorial:
			- Swirl, <https://swirlstats.com/>
			- learnr, <https://rstudio.github.io/learnr/examples.html>
	- Specific tools in R:
		- RMarkdown <https://bookdown.org/yihui/rmarkdown/>
		- Shiny
		- ggplot2 and ggvis
		- tidyverse

- topic modeling
- stylometry

## Practice Datasets

- from Mullen:
	- `historydata` package include a number of datasets suitable for practice
- via Mullen:
	- `europop` package:
		- `europop` table with the historical population of European cities
		- `city_coords` table with coordinates of those cities
- via MGR:
	- "digital" datasets:
		- `bosker` dataset (available online with the publication)
	- "paper" datasets:
		- pages from Ian Morris
	- text/corpus datasets:
		- The Richmond Dispatch
		- rStylo collection of texts for stylometric experiments
		- Gutenberg texts (Jockers)
		- Tilton and Arnold?
	- network datasets:



- Library of Congress:
	- [**DATA**] 25 mln book records: <http://www.loc.gov/cds/products/MDSConnect-books_all.html>
- Miriam Posner (UCLA):
	- [**DATA**] collection of datasets: <http://miriamposner.com/classes/dh201w19/final-project/datasets/>
	- class materials: <http://miriamposner.com/classes/dh201w19/>
- Lincoln Mullen (Geprge Mason U):
	- [**DATA**] `historydata` R-package: <https://lincolnmullen.com/software/historydata/>
	- *Computational Historical Thinking*, <https://dh-r.lincolnmullen.com/>