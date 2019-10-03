
<p style="color: red; font-weight: bold">>>>>>  gd2md-html alert:  ERRORs: 1; WARNINGs: 0; ALERTS: 18.</p>
<ul style="color: red; font-weight: bold"><li>See top comment block for details on ERRORs and WARNINGs. <li>In the converted Markdown or HTML, search for inline alerts that start with >>>>>  gd2md-html alert:  for specific instances that need correction.</ul>

<p style="color: red; font-weight: bold">Links to alert messages:</p><a href="#gdcalert1">alert1</a>
<a href="#gdcalert2">alert2</a>
<a href="#gdcalert3">alert3</a>
<a href="#gdcalert4">alert4</a>
<a href="#gdcalert5">alert5</a>
<a href="#gdcalert6">alert6</a>
<a href="#gdcalert7">alert7</a>
<a href="#gdcalert8">alert8</a>
<a href="#gdcalert9">alert9</a>
<a href="#gdcalert10">alert10</a>
<a href="#gdcalert11">alert11</a>
<a href="#gdcalert12">alert12</a>
<a href="#gdcalert13">alert13</a>
<a href="#gdcalert14">alert14</a>
<a href="#gdcalert15">alert15</a>
<a href="#gdcalert16">alert16</a>
<a href="#gdcalert17">alert17</a>
<a href="#gdcalert18">alert18</a>

<p style="color: red; font-weight: bold">>>>>> PLEASE check and correct alert issues and delete this message and the inline alerts.<hr></p>



## A collection of links to WWW resources on R \
1. Basic/intermediate stuff

Other R link collections:

[2. Statistical methods](https://drive.google.com/open?id=1AaKlgACkanDEqeFkL1EdS81eQdXHhgLTUmj9_PLcmM8)

[3. Miscellaneous (some of it advanced, some not)](https://drive.google.com/open?id=1z2IW4-0E8_WLxG80zzvS9xT1rA3yeMzSVxAyRstETXU)

[4. Web and interactive](https://drive.google.com/open?id=1PByB6pJydkomfaafqSTbpIgbtyY-Uw_YWOWzUK30jLI)

[5. Teaching](https://docs.google.com/document/d/1454EQiCUQ1EwGzigOKRvcBZj7W7G7hiqlXvb75QuOvc) 

Plus 

[Tips on Windows, Office or general computer stuff](https://drive.google.com/open?id=1TCY52Lk4zzdPpSX70p2qQ8wBHjlnE1drrPdDXmHKWkY)

[Github notes](https://docs.google.com/document/d/1ZoahGYbF4r2m4fvWiYdX04EomNi28Smdamr-rYsSnC4/edit#)


## Contents


[TOC]



## General {#general}

======================================================

**Another list like this :-)**

[http://www.computerworld.com/article/2497464/business-intelligence/business-intelligence-60-r-resources-to-improve-your-data-skills.html](http://www.computerworld.com/article/2497464/business-intelligence/business-intelligence-60-r-resources-to-improve-your-data-skills.html)

**Why R (or why Python)**

[R vs. Python](https://github.com/matloff/R-vs.-Python-for-Data-Science) by Norm Matloff - one of the better comparsions

**Introductions**

[http://rforcats.net/](http://rforcats.net/)

[http://www.burns-stat.com/documents/tutorials/impatient-r/](http://www.burns-stat.com/documents/tutorials/impatient-r/)

[https://togaware.com/onepager/](https://togaware.com/onepager/) 

**Official manual (latest stable release)** - note: much of this is too complex for beginners

[http://stat.ethz.ch/R-manual/R-patched/library/](http://stat.ethz.ch/R-manual/R-patched/library/)

**R blogs/news collections**

[https://www.r-bloggers.com/](https://www.r-bloggers.com/) Blog aggregator for ca. 750 R blogs

[https://rweekly.org/](https://rweekly.org/) Hand-selected weekly updates from the entire R community

**A beginner's guide to sharing and collaboration with R**

[http://www.noamross.net/blog/2013/1/7/collaborating-with-r.html](http://www.noamross.net/blog/2013/1/7/collaborating-with-r.html)

[A note on the R community spirit](https://drmowinckels.io/blog/why-rstudio-conf-is-the-best-conference-experience-i-have-had/) 

**Good R references:**

[http://wiki.stdout.org/rcookbook/](http://www.cookbook-r.com/) (good on data manipulation, ggplot2 etc.)

[http://www.statmethods.net/](http://www.statmethods.net/) (good on classic statistics etc.)

[https://info201-s17.github.io/book/](https://info201-s17.github.io/book/) (full intro, good on dplyr, ggplot2, git etc.)

[http://rtutorialseries.blogspot.no/](http://rtutorialseries.blogspot.no/)

[https://www.zoology.ubc.ca/~schluter/R/fit-model/](https://www.zoology.ubc.ca/~schluter/R/fit-model/) (intro to common models, mixed models, model selection and GAM)

[Mastering Software Development in R](https://bookdown.org/rdpeng/RProgDA/) - advanced introduction including e.g. package development

**Huge list of R github packages **

[http://rpkg.gepuro.net/](http://rpkg.gepuro.net/)

Also see [trending R depositories](https://github.com/trending/r)

**Debugging functions - see ?browser**


```
debug(name_of_function)
debugonce(name_of_function)
browser() - put this inside the function itself
```


Inside debugging:

  q = exit debugging, quit execution of function

  c = exit debugging, continue execution at the next statement

  f = finish execution of the current loop or function

**The single most useful R trick?**

[http://stackoverflow.com/questions/1295955/what-is-the-most-useful-r-trick](http://stackoverflow.com/questions/1295955/what-is-the-most-useful-r-trick)

**Learning functions**



name_of_function


<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: Definition term(s) &uarr;&uarr; missing definition? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>






example(name_of_function) - runs the examples in the help page! E.g.,


```
example(image)
```


**The “statistical learning” course by Hastie & Tibshirani**

[https://class.stanford.edu/courses/HumanitiesandScience/StatLearning/Winter2015/about](https://class.stanford.edu/courses/HumanitiesandScience/StatLearning/Winter2015/about)

**R _language _introduction (programming-oriented)**

Advanced programming in R (Hadley):

[http://adv-r.had.co.nz/](http://adv-r.had.co.nz/)

**Lists of R references**

[http://schamberlain.github.com/R-esources.html](http://schamberlain.github.com/R-esources.html)

[http://statmethods.wordpress.com/2012/01/14/staying-up-with-r/](http://statmethods.wordpress.com/2012/01/14/staying-up-with-r/)

**List of R books:**

[http://www.r-project.org/doc/bib/R-books.html](http://www.r-project.org/doc/bib/R-books.html)

**For in-depth knowledge: environments**

[https://www.r-bloggers.com/environments-in-r/](https://www.r-bloggers.com/environments-in-r/)

**Save typing: attach() and the (better) alternatives**

[https://www.r-bloggers.com/to-attach-or-not-attach-that-is-the-question/](https://www.r-bloggers.com/to-attach-or-not-attach-that-is-the-question/)


```
Based on variables a, b and c, compute a vector d:
d <- with(my_data, a*b +c)
Based on variables a, b and c, make a new variable d:
my_data <- within(my_data, d <- a*b +c)
...or 
my_data <- within(my_data, d <- a*b +c)
```


**R quirks and pitfalls**

[http://r4stats.com/articles/why-r-is-hard-to-learn/](http://r4stats.com/articles/why-r-is-hard-to-learn/)

[http://www.burns-stat.com/pages/Tutor/R_inferno.pdf](http://www.burns-stat.com/pages/Tutor/R_inferno.pdf)

[http://www.r-bloggers.com/7-r-quirks-that-will-drive-you-nutty/](http://www.r-bloggers.com/7-r-quirks-that-will-drive-you-nutty/)

**.rProfile examples**

[http://www.r-bloggers.com/fun-with-rprofile-and-customizing-r-startup/](http://www.r-bloggers.com/fun-with-rprofile-and-customizing-r-startup/)

[http://stackoverflow.com/questions/1189759/expert-r-users-whats-in-your-rprofile/](http://stackoverflow.com/questions/1189759/expert-r-users-whats-in-your-rprofile/)

[http://www.r-bloggers.com/customize-your-r-session-with-rprofile/](http://www.r-bloggers.com/customize-your-r-session-with-rprofile/)

[http://gettinggeneticsdone.blogspot.com.es/2013/07/customize-rprofile.html](http://gettinggeneticsdone.blogspot.com.es/2013/07/customize-rprofile.html)

Sys.getenv("R_LIBS_USER")

[1] "//niva-of5/osl-userdata$/dhj/Documents/R/win-library/3.2"

Control panel > User accounts > User accounts

“Change my environment variables”

**All kinds of questions about statistics and R:**

<span style="text-decoration:underline;">Focus on statistics (but often applied in R):</span>

[http://stats.stackexchange.com/](http://stats.stackexchange.com/)

<span style="text-decoration:underline;">Focus on programming (in all languages including R):</span>

[http://stackoverflow.com/](http://stackoverflow.com/)

[http://www.theanalysisfactor.com/](http://www.theanalysisfactor.com/)

**R blogs:**

[http://www.r-statistics.com/](http://www.r-statistics.com/)

[http://anythingbutrbitrary.blogspot.no/](http://anythingbutrbitrary.blogspot.no/)

[http://flowingdata.com/](http://flowingdata.com/)

[http://www.statisticsblog.com/](http://www.statisticsblog.com/)

[http://is-r.tumblr.com/](http://is-r.tumblr.com/)

[http://dmbates.blogspot.no/](http://dmbates.blogspot.no/) (Douglas Bates, lme4)

**A brief guide to using R in collaborative, social ways:**

**[http://www.noamross.net/blog/2013/1/7/collaborating-with-r.html](http://www.noamross.net/blog/2013/1/7/collaborating-with-r.html)**

**R graphs in media:**

[http://www.r-bloggers.com/amanda-cox-on-how-the-new-york-times-graphics-department-uses-r/](http://www.r-bloggers.com/amanda-cox-on-how-the-new-york-times-graphics-department-uses-r/)

[http://www.r-bloggers.com/nyt-charts-the-facebook-ipo-with-r/](http://www.r-bloggers.com/nyt-charts-the-facebook-ipo-with-r/)

[http://www.r-bloggers.com/r-chart-featured-in-facebook-ipo/](http://www.r-bloggers.com/r-chart-featured-in-facebook-ipo/)

**About R:**

[http://www.nytimes.com/2009/01/07/technology/business-computing/07program.html?_r=0](http://www.nytimes.com/2009/01/07/technology/business-computing/07program.html?_r=0)

[http://homes.msi.ucsb.edu/~byrnes/rtutorial.html](http://homes.msi.ucsb.edu/%7Ebyrnes/rtutorial.html)

[http://stackoverflow.com/questions/1738087/what-can-matlab-do-that-r-cannot-do](http://stackoverflow.com/questions/1738087/what-can-matlab-do-that-r-cannot-do)

[http://www.r-bloggers.com/will-2015-be-the-beginning-of-the-end-for-sas-and-spss/](http://www.r-bloggers.com/will-2015-be-the-beginning-of-the-end-for-sas-and-spss/)

[http://www.johnmyleswhite.com/notebook/2012/08/12/the-social-dynamics-of-the-r-core-team/](http://www.johnmyleswhite.com/notebook/2012/08/12/the-social-dynamics-of-the-r-core-team/)

**R guides:**

[http://pairach.com/2012/02/26/r-tutorials-from-universities-around-the-world/](http://pairach.com/2012/02/26/r-tutorials-from-universities-around-the-world/)

[http://flowingdata.com/2012/12/17/getting-started-with-charts-in-r/](http://flowingdata.com/2012/12/17/getting-started-with-charts-in-r/)

[http://www.johndcook.com/R_language_for_programmers.html](http://www.johndcook.com/R_language_for_programmers.html)

[http://www.sr.bham.ac.uk/~ajrs/R/index.html](http://www.sr.bham.ac.uk/%7Eajrs/R/index.html)

[http://www.openair-project.org/PDF/OpenAir_Manual.pdf](http://www.openair-project.org/PDF/OpenAir_Manual.pdf)

**Guide on R, Python etc.:**

A Gentle Introduction to Effective Computing in Quantitative Research: What ...

Harry J. Paarsch,Konstantin Golyaev

**R workflow / good practice tips**

[http://stackoverflow.com/questions/1429907/workflow-for-statistical-analysis-and-report-writing](http://stackoverflow.com/questions/1429907/workflow-for-statistical-analysis-and-report-writing)

[http://files.meetup.com/1685538/Rmeetup_Workflow_fullscreen.pdf](http://files.meetup.com/1685538/Rmeetup_Workflow_fullscreen.pdf)

[http://www.r-statistics.com/2010/09/dumping-functions-from-the-global-environment-into-an-r-script-file/](http://www.r-statistics.com/2010/09/dumping-functions-from-the-global-environment-into-an-r-script-file/)

[http://inundata.org/R_talks/meetup/](http://inundata.org/R_talks/meetup/)

[http://www.r-bloggers.com/10-top-tips-for-becoming-a-better-coder/](http://www.r-bloggers.com/10-top-tips-for-becoming-a-better-coder/)

[The Joel Test](https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/)

Python style logging in R (for scripts that are run periodically): futile.logger package

[https://www.r-bloggers.com/python-style-logging-in-r/](https://www.r-bloggers.com/python-style-logging-in-r/)

**Unit testing and data validation**

_<span style="text-decoration:underline;">testthat </span>_from Hadley, for unit testing of <span style="text-decoration:underline;">functions</span>

[http://www.brodrigues.co/blog/2016-03-31-unit-testing-with-r/](http://www.brodrigues.co/blog/2016-03-31-unit-testing-with-r/) (small intro)

[https://github.com/hadley/testthat](https://github.com/hadley/testthat)

[http://r-pkgs.had.co.nz/tests.html](http://r-pkgs.had.co.nz/tests.html)

<span style="text-decoration:underline;">ensurer</span>, a package for pipe-style validation:

[http://www.r-statistics.com/2014/11/the-ensurer-package-validation-inside-pipes/](http://www.r-statistics.com/2014/11/the-ensurer-package-validation-inside-pipes/)

<span style="text-decoration:underline;">ruler</span>, a package for validating <span style="text-decoration:underline;">data</span> (rather than functions)

[http://www.questionflow.org/2017/11/28/rule-your-data-with-tidy-validation-reports-design/](http://www.questionflow.org/2017/11/28/rule-your-data-with-tidy-validation-reports-design/)

Naniar, a package for visualising/handling NAs

[https://github.com/njtierney/naniar](https://github.com/njtierney/naniar) 

For more packages, see [here](https://echasnovski.github.io/ruler/#other-packages-for-validation-and-assertions)

**R workflow with Git**

[http://nicercode.github.io/git/rstudio.html](http://nicercode.github.io/git/rstudio.html)

[http://www.r-bloggers.com/r-studio-and-presentations-and-git-oh-my/](http://www.r-bloggers.com/r-studio-and-presentations-and-git-oh-my/)

**Some things R can do that you might not be aware of**

[http://simplystatistics.org/2013/12/30/some-things-r-can-do-you-might-not-be-aware-of/](http://simplystatistics.org/2013/12/30/some-things-r-can-do-you-might-not-be-aware-of/)

**R code school:**

[http://tryr.codeschool.com/](http://tryr.codeschool.com/)

**R "how-to" 2-minute videos:**

[http://www.twotorials.com/](http://www.twotorials.com/)

**R guide - functions:**

[https://github.com/hadley/devtools/wiki/Functions](https://github.com/hadley/devtools/wiki/Functions)

**R guide - error messages:**

[http://rforpublichealth.blogspot.no/2013/01/translating-weird-r-errors.html](http://rforpublichealth.blogspot.no/2013/01/translating-weird-r-errors.html)

**R and Norwegian/foreign characters (encodings)**

[Why you should use UTF-8 (Yihui)](https://yihui.name/en/2018/11/biggest-regret-knitr/) 

In RStudio, make sure that default encoding are set to “UTF-8”:

In menu Tools:Global Options, “Code” in the menu on the left, tab “Saving”. 

(_Needless to say, if you haven’t set this option on Windows, I won’t be your friend. [Yihui](https://yihui.name/en/2018/11/biggest-regret-knitr/))_

System default in RStudio is [ISO-8859-1 (Latin-1)](https://no.wikipedia.org/wiki/ISO_8859-1), which _does _include Norwegian letters, but in practice there often some trouble anyway. More on ANSI, UTF-8 and Unicode here and here.

In base R, the program will use ISO-8859-1 by default (IFAIK), but note that it can read [scripts ](https://stackoverflow.com/a/5588488/1734247)and csv files (see below) with UTF encoding.



<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/R-tips0.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/R-tips0.png "image_tooltip")


<span style="text-decoration:underline;">If Norwegian letters are “destroyed”</span>: try to open the file in Notepad++ and try out the “Encoding” menu. From this menu one can also convert e.g. an ANSI file to UTF-8.

Also see:

[http://quantifyingmemory.blogspot.no/2013/01/r-and-foreign-characters.html](http://quantifyingmemory.blogspot.no/2013/01/r-and-foreign-characters.html)

**Improvements to the R language**

[http://www.sumsar.net/blog/2013/12/three-syntax-addtions-that-would-make-r/](http://www.sumsar.net/blog/2013/12/three-syntax-addtions-that-would-make-r/)

Addition 1 & 2 is implemented here:

[https://github.com/crowding/vadr](https://github.com/crowding/vadr)

**Other/alternative R implementations (faster)**

[http://dynamicecology.wordpress.com/2014/01/14/r-isnt-just-r-anymore/](http://dynamicecology.wordpress.com/2014/01/14/r-isnt-just-r-anymore/)

**validR: Validated (certificated) R from Mango for commercial purposes**

[http://www.r-bloggers.com/validation-why-bother/](http://www.r-bloggers.com/validation-why-bother/)


## Packages {#packages}

For _making_ packages, see [R tips and tricks 3](https://docs.google.com/document/d/1z2IW4-0E8_WLxG80zzvS9xT1rA3yeMzSVxAyRstETXU/edit#heading=h.q44k29pgzc4u) 

===================================================

**Installing packages**

Use menu (in R or RStudio) or


```
install.packages("ggplot2")
```


**Where are/should packages be stored?**

[http://stackoverflow.com/questions/2615128/where-does-r-store-packages](http://stackoverflow.com/questions/2615128/where-does-r-store-packages)

[http://www.stat.osu.edu/computer-support/mathstatistics-packages/installing-r-libraries-locally-your-home-directory](http://www.stat.osu.edu/computer-support/mathstatistics-packages/installing-r-libraries-locally-your-home-directory)

[http://www.r-bloggers.com/installing-r-packages/](http://www.r-bloggers.com/installing-r-packages/)

<span style="text-decoration:underline;">Problem: RStudio tries to open some packages by default, before you have the chance to set libPath(). Solution:</span>

Add (or change) the user variable R_LIBS_USER in Windows: \
In Windows 7: Control panel > User accounts > User accounts > “Change my environment variables”

In Windows 10: Right-click Start > System > Type “Environment” in the Search box > Select “Edit environment variables for your account” \
Select “new variable”

set name to be: R_LIBS_USER

set value to be (for instance): “C:/Data/R/Library” (not including the quotation marks)

See answer from _gorkypl _with comment from _davidmoye _here: [http://stackoverflow.com/questions/15170399/changing-r-default-library-path-using-libpaths-in-rprofile-site-fails-to-work](http://stackoverflow.com/questions/15170399/changing-r-default-library-path-using-libpaths-in-rprofile-site-fails-to-work)

**If packages don’t install:**

[https://stackoverflow.com/questions/20587440/some-r-packages-do-not-update-with-update-packages](https://stackoverflow.com/questions/20587440/some-r-packages-do-not-update-with-update-packages)

**Installing github packages**


```
library(devtools)
install_github("DeveloperName/PackageName")
# example
install_github("metno/esd")
```


**library() vs require()**

If loading fails, library() causes the script to fail, require() just returns FALSE

[http://yihui.name/en/2014/07/library-vs-require/](http://yihui.name/en/2014/07/library-vs-require/)

**Update all packages (may take some time…)**


```
update.packages(ask = FALSE, checkBuilt = TRUE)
```


**Use a function from a package without loading the entire package**

Example: _lsos_ (_ls_ including object size) from package `multilevelPSA`:

`multilevelPSA::lsos(...)` 

For more info, see [here](https://stackoverflow.com/questions/35240971/what-are-the-double-colons-in-r/35241015), [here](https://stackoverflow.com/questions/23232791/is-it-a-good-practice-to-call-functions-in-a-package-via) and [here](http://blog.obeautifulcode.com/R/How-R-Searches-And-Finds-Stuff/)

Alternatively, use **[package import](https://cran.r-project.org/web/packages/import/vignettes/import.html) **to import (and optionally, rename) specific functions, Python-style:

import::from(dplyr, mutate, keep_when = filter)

**The cranky guide to trying R packages**

[http://www.win-vector.com/blog/2011/02/the-cranky-guide-to-trying-r-packages/](http://www.win-vector.com/blog/2011/02/the-cranky-guide-to-trying-r-packages/)

**Unload package**


```
detach("package:vegan", unload=TRUE)
```


**Uninstall package (doesn’t work if package is loaded)**


```
remove.packages("vegan") 
```


**Uninstall package (also works when package is loaded)**


```
library(installr)
uninstall.packages("vegan")
```


**Overview of the ‘tidyverse’ (at some stage called ‘Hadleyverse’, i.e. the collection of Hadley’s packages: dplyr, ggplot etc)**

[http://barryrowlingson.github.io/hadleyverse/](http://barryrowlingson.github.io/hadleyverse/)

[http://adolfoalvarez.cl/the-hitchhikers-guide-to-the-hadleyverse/](http://adolfoalvarez.cl/the-hitchhikers-guide-to-the-hadleyverse/)

Load the entire Hadleyverse

[https://github.com/imanuelcostigan/hadleyverse](https://github.com/imanuelcostigan/hadleyverse)

Hadley’s own version:

[https://cran.r-project.org/web/packages/tidyverse/index.html](https://cran.r-project.org/web/packages/tidyverse/index.html)

**Handling package dependencies**

[Good intro on Packrat, Checkpoint and Docker from RStudio](https://rviews.rstudio.com/2018/01/18/package-management-for-reproducible-r-code/)

[Another intro (see slides)](https://github.com/dougmet/repEnvDemo)

_<span style="text-decoration:underline;">Packrat</span> _- built into RStudio, but bulky in repo and needs foresight:

[http://rstudio.github.io/packrat/](http://rstudio.github.io/packrat/)

[http://www.r-bloggers.com/announcing-packrat/](http://www.r-bloggers.com/announcing-packrat/)

[http://www.r-bloggers.com/packrat-presentation-at-user-2014/](http://www.r-bloggers.com/packrat-presentation-at-user-2014/)

_<span style="text-decoration:underline;">Checkpoint</span> - _rescues old scripts using snapshots of CRAN on Microsoft R’s [time machine](https://mran.microsoft.com/timemachine)

[http://blog.revolutionanalytics.com/2014/10/introducing-rrt.html](http://blog.revolutionanalytics.com/2014/10/introducing-rrt.html)

_<span style="text-decoration:underline;">Gran</span> and <span style="text-decoration:underline;">switchr</span>_ - Repo friendly (not huge) but a not so easy

[http://blog.revolutionanalytics.com/2014/08/gran-and-switchr-cant-send-you-back-in-time-but-they-can-send-r-sort-of.html](http://blog.revolutionanalytics.com/2014/08/gran-and-switchr-cant-send-you-back-in-time-but-they-can-send-r-sort-of.html)

_Docker_ (also treating Packrat)

[http://www.r-bloggers.com/how-i-use-vagrant-and-docker-in-consultancy-projects/](http://www.r-bloggers.com/how-i-use-vagrant-and-docker-in-consultancy-projects/)

_Rocker_ 

[http://www.mango-solutions.com/wp/2015/01/docker-and-enabling-analytic-workflows/](http://www.mango-solutions.com/wp/2015/01/docker-and-enabling-analytic-workflows/)

**Rtools**

Rtools is not an R package but a “standalone” collection of files (DLLs for C, etc) for WIndows. It is needed for <span style="text-decoration:underline;">building</span> packages from C files._ _I have Rtools installed as a folder directly under C:/

[https://cran.r-project.org/bin/windows/Rtools/](https://cran.r-project.org/bin/windows/Rtools/)

**R packages compared with SAS/SPSS products**

[http://r4stats.com/articles/add-ons/](http://r4stats.com/articles/add-ons/)

**[Awesome-R](https://awesome-r.com/) - a curated list of awesome R packages**

**More lists of general-purpose packages**

10 R packages I wish I knew about earlier

[http://blog.yhathq.com/posts/10-R-packages-I-wish-I-knew-about-earlier.html](http://blog.yhathq.com/posts/10-R-packages-I-wish-I-knew-about-earlier.html)

Computerworld list of packages

[http://www.computerworld.com/article/2921176/business-intelligence/great-r-packages-for-data-import-wrangling-visualization.html](http://www.computerworld.com/article/2921176/business-intelligence/great-r-packages-for-data-import-wrangling-visualization.html)


## Some common problems {#some-common-problems}

======================================================

**Read txt or csv file without making factor variables from character variables**


```
mydf <- read.csv('my_data_file.csv',  stringsAsFactors = FALSE)
mydf <- read.csv('my_data_file.csv',  as.is = TRUE)
```


**Drop unused factor levels**


```
mydf <- droplevels(mydf)
```


[https://stat.ethz.ch/R-manual/R-devel/library/base/html/droplevels.html](https://stat.ethz.ch/R-manual/R-devel/library/base/html/droplevels.html)

[http://stackoverflow.com/questions/1195826/drop-factor-levels-in-a-subsetted-data-frame](http://stackoverflow.com/questions/1195826/drop-factor-levels-in-a-subsetted-data-frame)

**Change factor variable to character variable or numeric variables**


```
myDataframe$a <- as.character(myDataframe$a)
# Or:
# fact2char <- function(x) levels(x)[as.numeric(x)]
fact2num <- function(x) as.numeric(fact2char(x))
```


**Change <span style="text-decoration:underline;">all</span> factor variables to character variables**


```
library(dplyr)
myDataframe <- myDataframe %>%
  mutate_if(is.factor, as.character)  # (from here)
```


**Forcats package - consists of a handful of missing tools for dealing with factors**

fct_recode() - use together with mutate()

fct_lump()  - lumps the rarest levels into a new “others” level

fct_relevel() is similar to stats::relevel() but allows you to move any number of levels to the front.

fct_inorder() orders according to the first appearance of each level.

fct_infreq() orders from most common to rarest.

fct_rev() reverses the order of levels.

[https://www.r-bloggers.com/forcats-0-1-0-%f0%9f%90%88%f0%9f%90%88%f0%9f%90%88%f0%9f%90%88/](https://www.r-bloggers.com/forcats-0-1-0-%f0%9f%90%88%f0%9f%90%88%f0%9f%90%88%f0%9f%90%88/)

**Avoid that unused factor levels/combinations are dropped by dplyr::summarise**

[http://stackoverflow.com/questions/22523131/dplyr-summarise-equivalent-of-drop-false-to-keep-groups-with-zero-length-in](http://stackoverflow.com/questions/22523131/dplyr-summarise-equivalent-of-drop-false-to-keep-groups-with-zero-length-in)

Use <span style="text-decoration:underline;">complete()</span>. And your variables must be factors.


```
df2$datatype <- factor(df2$datatype)
df2$Par_unit <- factor(df2$Par_unit)
df3 <- df2 %>%
  group_by(datatype, Par_unit) %>%
  summarise(N_files = sum(!is.na(not_na)),
            N_data = sum(not_na, na.rm = TRUE)) %>%
  complete(datatype, Par_unit, fill = list(N_files = 0, N_data = 0))
```


 

**Using Norwegian characters in R GUI script files**

`Sys.getlocale(category = "LC_ALL")` should return


```
"LC_COLLATE=Norwegian (Bokmål)_Norway.1252;LC_CTYPE=Norwegian (Bokmål)_Norway.1252;LC_MONETARY=Norwegian (Bokmål)_Norway.1252;LC_NUMERIC=C;LC_TIME=Norwegian (Bokmål)_Norway.1252"
```


[http://stackoverflow.com/questions/10955582/displaying-utf-8-encoded-chinese-characters-in-r](http://stackoverflow.com/questions/10955582/displaying-utf-8-encoded-chinese-characters-in-r)

[http://stackoverflow.com/questions/5031630/how-to-source-r-file-saved-using-utf-8-encoding](http://stackoverflow.com/questions/5031630/how-to-source-r-file-saved-using-utf-8-encoding)

[https://stat.ethz.ch/R-manual/R-devel/library/base/html/locales.html](https://stat.ethz.ch/R-manual/R-devel/library/base/html/locales.html)

**Read data files with Norwegian (or other non-ASCII) characters**

Important point: the data may be ok even if the print() method for data.table doesn’t show characters correctly (it has a bug)

[http://people.fas.harvard.edu/~izahn/posts/reading-data-with-non-native-encoding-in-r/](http://people.fas.harvard.edu/~izahn/posts/reading-data-with-non-native-encoding-in-r/)

**Passing columns of a dataframe to a function without quotes**

[https://www.r-bloggers.com/passing-columns-of-a-dataframe-to-a-function-without-quotes/](https://www.r-bloggers.com/passing-columns-of-a-dataframe-to-a-function-without-quotes/)

**Concatenate a list of vectors to a single vector**


```
x <- list(1:5, 10:11, 15:19)
do.call(c, x)
```



## Get overview/summary of data {#get-overview-summary-of-data}

======================================================

**Basic functions**

str(my_data_frame)

head(my_data_frame)

summary(my_data_frame)

**Packages**

**[skimr](https://github.com/ropensci/skimr)** - which also handles grouped data

skim(iris)

iris %>% dplyr::group_by(Species) %>% skim()   



<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/R-tips1.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/R-tips1.png "image_tooltip")


[inspectdf](https://github.com/alastairrushworth/inspectdf) - collection of utilities for columnwise summary, comparison and visualisation of data frames. Especially nice for comparing two data frames.


## Import/export {#import-export}

======================================================

**Moving data to and from Excel using copy/paste**

[http://www.johndcook.com/r_excel_clipboard.html](http://www.johndcook.com/r_excel_clipboard.html)

**From Excel **- to read data copied from Excel:


```
newdata <- read.table("clipboard", sep="\t", dec=",")
```


- if you also copied the row with variable names:


```
newdata <- read.table("clipboard", header =TRUE, sep="\t", dec=",")
```


**To Excel**: to write data to Clipboard (can be pasted into Excel sheet):


```
write.table(x, "clipboard", dec=',', sep="\t", row.names=TRUE)
```


If you get error message that “clipboard buffer is full”, increase limit (given in KB, default 32 K):


```
write.table(outtake, "clipboard-1024", sep=";", dec=",", quote=FALSE, row.names = FALSE)
```


**Packages**

**readxl** from Hadley - no dependencies (function: <span style="text-decoration:underline;">read_excel()</span>)

[https://github.com/hadley/readxl](https://github.com/hadley/readxl)

**XLConnect** -depends on updated Java (see below!)

[http://cran.r-project.org/web/packages/XLConnect/index.html](http://cran.r-project.org/web/packages/XLConnect/index.html)

(works also on mac according to[ http://lamages.blogspot.no/2012/06/uk-house-prices-visualised-with.html](http://lamages.blogspot.no/2012/06/uk-house-prices-visualised-with.html))

**xlsx** - Another Java-dependent package - can write a lot of formats and even change column widths etc. (see below). Appears to not be maintained anymore (but still works)

**openxlsx** - Java-independent (uses Rcpp instead)

[https://CRAN.R-project.org/package=openxlsx](https://cran.r-project.org/package=openxlsx) (see [this](https://rpubs.com/RomanL/16180) for formatted characters)


```
write.xlsx(my_data_frame, file = "test1.xlsx")          # writes 1 data set
write.xlsx(my_list_of_data_frames, file = "test1.xlsx") # list of data sets
```


**Connecting R and Excel**

[Connecting R and Excel in a million ways (old but still good?)](https://www.r-bloggers.com/a-million-ways-to-connect-r-and-excel/)

[Excelsi-R - Excel interface to R](https://sourceforge.net/p/excelsir/wiki/User%20Documentation/)

[RExcel](http://rcom.univie.ac.at/download.html) 

[Rpart package](https://journal.r-project.org/archive/2011-2/RJournal_2011-2_Baier~et~al.pdf) (maintained?)

[Microsoft R](https://mran.microsoft.com)

[R tools for Visual Studio](https://visualstudio.microsoft.com/vs/features/rtvs/)

**Installing/maintaining Java**

[https://chocolatey.org/](https://chocolatey.org/) (recommended by [this](https://github.com/ropensci/tabulizer) package maintainer) 

**Reading Excel files**

[http://www.r-bloggers.com/read-excel-files-from-r/](http://www.r-bloggers.com/read-excel-files-from-r/)

**Reading _messy_ Excel files**

[https://www.r-bloggers.com/extract-tables-from-messy-spreadsheets-with-jailbreakr/](https://www.r-bloggers.com/extract-tables-from-messy-spreadsheets-with-jailbreakr/)

**Write CSV **- use fwrite() from package data.table for large files

[https://rpubs.com/demydd/207377](https://rpubs.com/demydd/207377)

[https://www.r-bloggers.com/fast-csv-writing-for-r/](https://www.r-bloggers.com/fast-csv-writing-for-r/)

**Write _formatted_ data to Excel (colors, bold, italics etc.)**

[https://CRAN.R-project.org/package=xlsx](https://CRAN.R-project.org/package=xlsx)

**Reading data pasted into the code** - use <span style="text-decoration:underline;">textConnection(txt)</span>


```
Example 1
df <- read.table(textConnection("
Year Month  Salt     Flu
2005  1.00  32.0  0.525 
2005  2.00  32.1  0.0286
2006  1.00  32.3  0.197 
2006  2.00  32.3  0.107 
2007  2.00  33.1  0.412
"), header = TRUE)

Example 2 - using read.csv
my_data <- read.csv(textConnection("
Vegetasjonsdekke,ARVEGET
Impediment,51
Skrint usammenhengende,52
Lavdekke,53
Skrint til godt,54
Frodig usammenhengende,55
Ikke relevant,98
Ikke registrert,99 
"), stringsAsFactors = FALSE)
```


**Line endings in Mac Excel** (here, in connection with Git)

[http://nicercode.github.io/blog/2013-04-30-excel-and-line-endings/](http://nicercode.github.io/blog/2013-04-30-excel-and-line-endings/)

**R guide - importing data:**

[http://statistical-research.com/importing-data-into-r-from-different-sources](http://statistical-research.com/importing-data-into-r-from-different-sources)

**Read data from tables in a Word document**

[http://www.r-bloggers.com/using-r-to-get-data-out-of-word-docs/](http://www.r-bloggers.com/using-r-to-get-data-out-of-word-docs/)

**Read data from pdf**

**Package [tabulizer](https://github.com/ropensci/tabulizer)**: dedicated to extracting tables from text-based PDF, but depends on java. Wrapper of Tabula (see below). Best for extracting entire pdf files? [Intro](https://ropensci.org/tutorials/tabulizer_tutorial/) 

**Package [pdftools](https://github.com/ropensci/pdftools)**: blog [1](https://www.r-bloggers.com/taming-exam-results-in-pdf-with-pdftools/), [2](https://www.r-bloggers.com/extracting-pdf-text-with-r-and-creating-tidy-data/), [3 (including tidytext)](https://www.r-bloggers.com/how-to-extract-data-from-a-pdf-file-with-r/) - [not good for extract table data](https://github.com/ropensci/pdftools)

**Program [Tabula](https://tabula.technology/)** (screenshot below) - not an R program, depends on Java. For text-based PDFs. Opens up in your web-browser where you can select the table area. <span style="text-decoration:underline;">Tip 1</span>: Can extract multi-page tables, just mark it as several areas (however, you probably have to do some corrections in Excel afterwards). <span style="text-decoration:underline;">Tip 2</span>: if you have chemical names involved (e.g. Indeno(1,2,3cd)pyren) ,export tables as TSV (not CSV). Installed on my laptop in folder ‘C:\Data\tabula-win-1.2.1\tabula’.



<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/R-tips2.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/R-tips2.png "image_tooltip")


**R zip and unzip**

[http://www.r-bloggers.com/make-your-date-folder-clean-with-function-unzip-unz/](http://www.r-bloggers.com/make-your-date-folder-clean-with-function-unzip-unz/)

If you have your files compressed with bzip2, xvz, or gzip they can be read into R as if they are plain text files:

[http://blog.revolutionanalytics.com/2009/12/r-tip-save-time-and-space-by-compressing-data-files.html](http://blog.revolutionanalytics.com/2009/12/r-tip-save-time-and-space-by-compressing-data-files.html)

Comparison of compression formats:

[http://www.r-bloggers.com/comparison-of-compression/](http://www.r-bloggers.com/comparison-of-compression/)

**Determine number of lines in a large text file**

[http://www.r-bloggers.com/easy-way-of-determining-number-of-linesrecords-in-a-given-large-file-using-r-2/](http://www.r-bloggers.com/easy-way-of-determining-number-of-linesrecords-in-a-given-large-file-using-r-2/)

**Download all files in folder - DOS script (can be written and called from R, see “send email” solution below)**

[http://stackoverflow.com/questions/5230966/python-ftp-download-all-files-in-directory/](http://stackoverflow.com/questions/5230966/python-ftp-download-all-files-in-directory/)

**Fix ‘unsupported URL scheme’ when using https: use ‘setInternet2()’**

[http://stackoverflow.com/questions/21857264/error-in-download-file-unsupported-url-scheme](http://stackoverflow.com/questions/21857264/error-in-download-file-unsupported-url-scheme)

**Download from internet text file in packages (1) rCurl and (2) httr**


```
(1) getURL()
(2) r <- GET("http://httpbin.org/get")
    content(r, "text")
```


**Download zipped text file in packages (1) rCurl and (2) httr**


```
(1) 
  bin <- getBinaryURL(ftptxt, ssl.verifypeer=FALSE, 
           userpwd = userpwd.string, verbose = TRUE)
(2)
  r <- GET("http://httpbin.org/get")
  bin <- content(r, "raw")
# For both (1) and (2):
  fn <- tempfile()
  con <- file(fn, open = "wb")
  writeBin(bin, con)
  close(con)
  data <- read.table(fn, stringsAsFactors=FALSE)
```


**How to close the curl connection (httr)**

[https://github.com/hadley/httr/issues/122](https://github.com/hadley/httr/issues/122)

<span style="text-decoration:underline;">Example:</span>


```
my_handle <- handle("http://h-web01.nve.no/")
page <- try(GET(handle = my_handle, path = urlstring, url = NULL))
rm(my_handle)
```


<span style="text-decoration:underline;">See files</span>


```
H:\Documents\seksjon 214\MyOcean\2015_Insitu\2015_09_Analyse\30B_read_NetCDF.R
K:\Avdeling\214-Oseanografi\DHJ\Data\Riverflow\01_Rscripts\Read_NVE_data.R
```


**Download files from Google Drive**

[http://architects.dzone.com/articles/download-files-google](http://architects.dzone.com/articles/download-files-google)

[http://blog.revolutionanalytics.com/2009/09/how-to-use-a-google-spreadsheet-as-data-in-r.html](http://blog.revolutionanalytics.com/2009/09/how-to-use-a-google-spreadsheet-as-data-in-r.html)

**Download files from Dropbox**

[http://thebiobucket.blogspot.co.at/2013/04/download-files-from-dropbox.html](http://thebiobucket.blogspot.co.at/2013/04/download-files-from-dropbox.html)

**NetCDF files**

[Package ncdf4 vs. RNetCDF](http://r.789695.n4.nabble.com/big-difference-between-ncdf-and-RNetCDF-td4676332.html) 

[ncdf4 cheatsheet](https://www.r-bloggers.com/a-netcdf-4-in-r-cheatsheet/) 

**Reading files in JSON format**

General introduction to JSON

[http://www.copterlabs.com/blog/json-what-it-is-how-it-works-how-to-use-it/](http://www.copterlabs.com/blog/json-what-it-is-how-it-works-how-to-use-it/)

Reading JSON files in R

[http://rud.is/b/2013/09/28/obamacare-jobs-r-d3/](http://rud.is/b/2013/09/28/obamacare-jobs-r-d3/)

[http://lamages.blogspot.no/2011/09/accessing-and-plotting-world-bank-data.html](http://lamages.blogspot.no/2011/09/accessing-and-plotting-world-bank-data.html)

[http://www.r-bloggers.com/the-deutsche-bahn-german-railway-corp-is-always-late-or-is-it-and-if-why/](http://www.r-bloggers.com/the-deutsche-bahn-german-railway-corp-is-always-late-or-is-it-and-if-why/)

For use in a rCharts application (also see below)

[http://ramnathv.github.io/bikeshare/](http://ramnathv.github.io/bikeshare/)

Newest package: jsonlite:

[http://www.r-bloggers.com/new-package-jsonlite-a-smarter-json-encoderdecoder/](http://www.r-bloggers.com/new-package-jsonlite-a-smarter-json-encoderdecoder/)

Examples:

[http://cran.r-project.org/web/packages/jsonlite/vignettes/json-apis.html](http://cran.r-project.org/web/packages/jsonlite/vignettes/json-apis.html)

Also see application to forecast.io data using Rforecastio, see below

**For GeoJSON/TopoJSON, see “Maps” section**



<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "Maps"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[Maps](#heading=h.sqoho6vh0kn3)

**Reading files in XML format**

[https://www.r-bloggers.com/r-and-the-web-for-beginners-part-ii-xml-in-r/](https://www.r-bloggers.com/r-and-the-web-for-beginners-part-ii-xml-in-r/)

**For connecting to databases, see the “Big data” section in the “[Advanced](https://drive.google.com/open?id=1z2IW4-0E8_WLxG80zzvS9xT1rA3yeMzSVxAyRstETXU)” document**

**Why using saveRDS() and readRDS() instead of save() and load()**

[http://www.r-bloggers.com/a-better-way-of-saving-and-loading-objects-in-r/](http://www.r-bloggers.com/a-better-way-of-saving-and-loading-objects-in-r/)

**Feather - fast format for data tables, compatible with Python**

[http://www.r-bloggers.com/feather-a-fast-on-disk-format-for-data-frames-for-r-and-python-powered-by-apache-arrow/](http://www.r-bloggers.com/feather-a-fast-on-disk-format-for-data-frames-for-r-and-python-powered-by-apache-arrow/)

**Temporary files and temporary folder**

tempfile(), tempdir()


## Send/read email from R {#send-read-email-from-r}

======================================================

**gmailr - allows access to your Gmail messages, threads, drafts and labels.**

[https://cran.r-project.org/web/packages/gmailr/](https://cran.r-project.org/web/packages/gmailr/)

Old solution: make VB script in R and call it via shell (see response from [marvin_dpr](http://stackoverflow.com/users/1144966/marvin-dpr), one of the last responses)

[http://stackoverflow.com/questions/2885660/how-to-send-email-with-attachment-from-r-in-windows](http://stackoverflow.com/questions/2885660/how-to-send-email-with-attachment-from-r-in-windows)


## String (text) handling {#string-text-handling}

(String = [a sequence of characters](https://en.wikipedia.org/wiki/String_(computer_science)) which may include spaces, symbols etc. E.g. “a red fox.” )

======================================================

**Guide to working with strings in R (book)**

[Handling Strings with R](http://www.gastonsanchez.com/r4strings/)

 

**The basics: paste, paste0 and sprintf**

[http://www.r-bloggers.com/paste-paste0-and-sprintf/](http://www.r-bloggers.com/paste-paste0-and-sprintf/)

**Convert numbers to characters with leading zeros, and add e.g. “.png”:**


```
sprintf("%02i.png", 1:30)    # Makes 01.png, 02.png, 03.png, …, 30.png
sprintf("The number 3 with 3 decimals: %.3f", 3)
sprintf("%02i_%s.png", 1:3, c("Anna","Bjorn","Chris"))  # "01_Anna.png" etc.
sprintf("%2s_%1s.png", c("Anna","Bjorn"), c("Bergen","Oslo"))
# "Anna_Bergen.png" "Bjorn_Oslo.png" 
```


[http://stackoverflow.com/questions/33601673/create-character-vector-of-filenames-in-numeric-sequence-with-leading-zeroes](http://stackoverflow.com/questions/33601673/create-character-vector-of-filenames-in-numeric-sequence-with-leading-zeroes)

**Find and replace in R (pattern matching and replacement)**

_grep(pattern, x)_ returns an <span style="text-decoration:underline;">integer</span> vector of elements of _x_ that match _pattern_

_grep(pattern, x, value = TRUE)_ returns a <span style="text-decoration:underline;">text</span> vector of elements of _x_ that match _pattern_

_grepl(pattern, x)_ returns a <span style="text-decoration:underline;">boolean</span> vector of elements of _x_ that match _pattern_

_sub(pattern, replacement, x)_ replaces the <span style="text-decoration:underline;">first</span> match in each element of _x_

_gsub(pattern, replacement, x)_ replaces <span style="text-decoration:underline;">all</span> matches in each element of _x_

_regexpr(pattern, x)_ returns an <span style="text-decoration:underline;">integer vector</span> of the starting position of the <span style="text-decoration:underline;">first</span> match

_gregexpr(pattern, x)_ returns a <span style="text-decoration:underline;">list</span> of the starting position of <span style="text-decoration:underline;">all</span> matches

**Plus**

_strsplit(x, pattern)_ splits the string where there is a match to _pattern_

**From the <span style="text-decoration:underline;">stringr</span> package:**

_str_extract(x, pattern)_ returns a <span style="text-decoration:underline;">character</span> vector of <span style="text-decoration:underline;">first</span> match in each element of _x_

_str_extract_all(x, pattern)_ returns a <span style="text-decoration:underline;">list</span> of character vectors of all matches

Default behaviour (**fixed = FALSE**) is to use regular expressions. Set **fixed = FALSE** to search for the exact character(s):


```
strsplit("abcd.efgh", ".")              # doesn't work
strsplit("abcd.efgh", ".", fixed=TRUE)  # does work
```


The functions are <span style="text-decoration:underline;">case-sensitive </span>by default (`ignore.case = FALSE`), set `ignore.case = TRUE` to change that

[http://www.endmemo.com/program/R/grep.php](http://www.endmemo.com/program/R/grep.php)

[https://stat.ethz.ch/R-manual/R-devel/library/base/html/grep.html](https://stat.ethz.ch/R-manual/R-devel/library/base/html/grep.html)

**<span style="text-decoration:underline;">Regular expressions</span>**


```
?regex
```


[https://en.wikipedia.org/wiki/Regular_expression](https://en.wikipedia.org/wiki/Regular_expression)

[http://www.cheatography.com/davechild/cheat-sheets/regular-expressions/](http://www.cheatography.com/davechild/cheat-sheets/regular-expressions/)

[http://regexone.com/](http://regexone.com/) Online short course

[https://regex101.com/](https://regex101.com/) Regex tester (and explainer!)

[Regex crossword…!](https://blog.revolutionanalytics.com/2018/04/because-its-friday-regex-games.html) 

**<span style="text-decoration:underline;">Regular expressions</span> - micro cheat sheet<span style="text-decoration:underline;"> </span>**


```
. Any single character
[0-9] Match any digit
[abc] Match any of the characters a-c
[^abc] Match any character except a-c
? The preceding item is optional and will be matched at most once
* The preceding item will be matched zero or more times
+ The preceding item will be matched one or more times
^ Start of line
$ End of line
```


**<span style="text-decoration:underline;">Regular expressions, some examples</span>**

**Matching a single/specific number of whitespace**


```
sub("[[:blank:]]", "d", "abc e") 
[1] "abcde"
sub("\\s", "d", "abc e") 
[1] "abcde"
```


**Matching any length of whitespace**


```
sub("\\s+", "d", "abc    e") 
[1] "abcde"
sub("[[:blank:]]+", "d", "abc     e")
[1] "abcde"
```


**Remove trailing whitespace (at end of string)**


```
cemp_pos$jmpst <- gsub("[:blank:]$", "", cemp_pos$jmpst) 
OR (better?):
cemp_pos$jmpst <- sub(" +$", "", cemp_pos$jmpst)
```


**Remove hyphen at the start (1st line) or end (2nd line)**


```
gsub("^-", "", c("-bcd", "ab-d", "abc-"))
gsub("-$", "", c("-bcd", "ab-d", "abc-"))
```


**Replace repeated hyphens with a single hyphen**


```
gsub("-+", "-", c("-bcd", "ab-d", "ab---"))
```


**Remove start of word up to and including ‘full stop’ sign**


```
sub("^.+\\.", "", c('sensor.temp', 'sensor2.salt'))
Explanation:
^    start of string
.+   any character (.), one or more of them (+)
\\.  full stop (the two slashes are 'escape signs')
```


**Make logic vector which is TRUE for all strings ending in 7 **


```
strings <- c('714', '56', '57', '170')
grepl('7$', strings)
Explanation:
$    end of string
```


**Extract all characters to the left of the first underscore** ([ref](https://stackoverflow.com/questions/5985494/regex-match-everything-before-first-underscore-and-everything-in-between-after))


```
x <- c("31F_Solbergstrand", "41G1_Feneset", "97A2_Bodø havn")
stringr::str_extract(x, "[^_]+")
# if you like it complicated: stringr::str_extract(x, "^[^_]+(?=_)")
```


**Extract all characters between underscore 1 and 2** ([ref](https://stackoverflow.com/questions/5985494/regex-match-everything-before-first-underscore-and-everything-in-between-after))


```
x <- c("31F_Solbergstrand_nord", "41G1_Feneset_vest", "97A2_Bodø havn_vest")
stringr::str_extract(x, "(?<=_)[^_]+(?=_)")
```


**Extract all characters to the left or to the right of the first space**


```
x <- c("31F Solbergstrand", "41G1 Feneset", "97A2 Bodø havn")
stringr::str_extract(x, "([^[[:blank:]]]+)")  
stringr::str_extract(x, "(?<=[[:blank:]]).*")
# OR
stringr::str_extract(x, "([^\\s]+)")
stringr::str_extract(x, "(?<=\\s).*")
(reference 1, reference 2; except that R needs double backslashes)
```


**Extract characters between ‘(‘ and ‘,’ but don’t include the delimiters (‘(‘ and ‘,’) in the output**


```
x <- "(180,210)"
stringr::str_match(x, "^\\((.+)\\,")[2]   # result: "180"
Explanation:
^      start of string
\\(    '(' (double backslashes = escape sign in R)
(      start of group (we want the thing inside the parentheses
.+     any character, one or more times
)      end of group
\\,    ',' (again, using escape sign)
[2]    the result is a group where [1] is "(180," and [2] is "180" 
```


**Extract numbers**


```
# Extract first integer number
stringr::str_extract(c("bcd123", "b4d5ff", "< 3.4"), "[0-9]+")
# Extract first integer or decimal number
stringr::str_extract(c("bcd123", "b4d5ff", "< 3.4"), "[0-9,.]+")
```


**Detect less-than sign**


```
grepl("<", c("12.5", "<8.5", " < 3.4"))               # base R
stringr::str_detect(c("12.5", "<8.5", " < 3.4"), "<") # library stringr
```


**Extract function name** (not solved)


```
^([^ ]+) *<- *function
```


Check it in [https://regex101.com/](https://regex101.com/) 

The following should have returned `'find_tissue' `but apparently doesn’t work in R:


```
grep("^([^ ]+) *<- *function", 'find_tissue <- function(', value = TRUE)
```


**Some other commands**


```
Number of characters in a string:  
      nchar(string)  
      # but note that NA is counted as 2 characters!
Extract characters from a string:  
      substr(string, start_position, stop_position)
```



## Time/date handling {#time-date-handling}

======================================================

R has two systems (‘lubridate’ uses the first one)

**POSIXct** = number of seconds since 1.1.1970 (UTC), equals UNIX time (a.k.a. epoch time)

**POSIXlt** = a list of vectors for year, month, date, hour etc. Note that numbering starts at zero, so January = month 0!

- POSIXlt also includes wday (day of week) and yday (day of the year)

**General**

[http://stat.ethz.ch/R-manual/R-devel/library/base/html/DateTimeClasses.html](http://stat.ethz.ch/R-manual/R-devel/library/base/html/DateTimeClasses.html)

[http://www.ats.ucla.edu/stat/r/faq/dates.htm](http://www.ats.ucla.edu/stat/r/faq/dates.htm)

**Lubridate**

[https://www.r-bloggers.com/do-more-with-dates-and-times-in-r-with-lubridate-1-1-0/](https://www.r-bloggers.com/do-more-with-dates-and-times-in-r-with-lubridate-1-1-0/)

<span style="text-decoration:underline;">Interval</span> = specific start and end time. Can also be created by <span style="text-decoration:underline;">int_diff()</span>


```
int <- interval(ymd(20110720, ymd(20110831))
int <- int_diff(dmy("01.01.2015") + seq(0,12)*months(1))
```


<span style="text-decoration:underline;">int_shift</span> = shifts an interval a period or duration


```
new_interval1 <- int_shift(my_intervals, years(10))
new_interval2 <- int_shift(my_intervals, years(10))
```


<span style="text-decoration:underline;">Interval</span> overlaps, intersections, union


```
int1 <- interval(ymd(20160101),ymd(20160115)) # 1st to 15th
int2 <- interval(ymd(20160110),ymd(20160120)) # 10th to 20th
int_overlaps(int1, int2)
intersect(int1, int2)
union(int1, int2)
```


<span style="text-decoration:underline;">Durations</span> (start with d) and <span style="text-decoration:underline;">periods</span>: dyears(1) is always 365 days, years(1) is 365 or 366

leap_year(2012) \
## TRUE \
ymd(20120101) + dyears(1) \
## "2012-12-31 UTC" \
ymd(20120101) + years(1) \
## "2013-01-01 UTC"

<span style="text-decoration:underline;">difftime</span> = one time minus another (Core R class)


```
mydates <- dmy("01.01.2015") + 1:12*months(1)
dt <- mydates - dmy("01.01.2015")
```


difftime arithmetic:


```
as.duration(dt) / dseconds(1)     = exact number of seconds
as.duration(dt) / ddays(1)        = exact number of days
as.period(dt) / months(1)         = number of "mean months"
#  [1]  1.019178  1.939726  2.958904  3.945205  4.964384  5.950685  6.969863
#  [8]  7.989041  8.975342  9.994521 10.980822 12.000000
round(as.period(dt) / months(1))  = number of months
dt <- mydates - dmy("01.01.2015")
```


**Week numbers**

[https://cran.r-project.org/package=ISOweek](https://cran.r-project.org/package=ISOweek)

**Anytime** - simple conversion of time integer/string to Unix time (also covering DST)

[http://dirk.eddelbuettel.com/code/anytime.html](http://dirk.eddelbuettel.com/code/anytime.html)

**From Windows-Excel, Mac-Excel or Matlab to R**

[http://stat.ethz.ch/R-manual/R-devel/library/base/html/as.Date.html](http://stat.ethz.ch/R-manual/R-devel/library/base/html/as.Date.html)

<span style="text-decoration:underline;">Matlab to R (UTC time):</span>


```
as.POSIXct((data$TIME-719529)*86400, origin = "1970-01-01", tz = "GMT")
```


<span style="text-decoration:underline;">Windows Excel to R, whole dates only:</span>


```
as.Date(35981, origin = "1899-12-30") # 1998-07-05
```


<span style="text-decoration:underline;">Mac Excel to R, whole dates only:</span>


```
as.Date(34519, origin = "1904-01-01") # 1998-07-05
```


<span style="text-decoration:underline;">Windows Excel to R, fractional date (i.e. date and time)</span>


```
as.POSIXct((excel_date - 25569)*24*3600, origin = "1970-01-01")
# ...or with package anytime:
anytime((excel_date - 25569)*24*3600)
```


<span style="text-decoration:underline;">Windows Excel to R, time given as local time (should handle Daylight Saving Time as well)</span>


```
anytime((df2$Dato - dt2)*24*3600, tz="Europe/Oslo")
```


(also see link below:)

[http://www.r-bloggers.com/converting-matlab-and-r-date-and-time-values/](http://www.r-bloggers.com/converting-matlab-and-r-date-and-time-values/)

**For timezone trouble**

[http://stackoverflow.com/questions/4047188/unknown-timezone-name-in-r-strptime-as-posixct](http://stackoverflow.com/questions/4047188/unknown-timezone-name-in-r-strptime-as-posixct)

**Plot weekly or monthly totals**

[http://www.mollietaylor.com/2013/08/plot-weekly-or-monthly-totals-in-r.html](http://www.mollietaylor.com/2013/08/plot-weekly-or-monthly-totals-in-r.html)

**Dates to/from Excel**

[http://stackoverflow.com/questions/15686451/dates-from-excel-to-r-platform-dependency](http://stackoverflow.com/questions/15686451/dates-from-excel-to-r-platform-dependency)

**How to set all dates to the same year**

[http://stackoverflow.com/questions/9500114/find-which-season-a-particular-date-belongs-to?rq=1](http://stackoverflow.com/questions/9500114/find-which-season-a-particular-date-belongs-to?rq=1)

**Dates/times in ggplot2 - only POSIXct format is accepted**

[http://learnr.wordpress.com/2010/02/25/ggplot2-plotting-dates-hours-and-minutes/](http://learnr.wordpress.com/2010/02/25/ggplot2-plotting-dates-hours-and-minutes/)

**The cut() function can be used to cut times according to day **- but beware that it will follow global (Greenwich) time, not the daylight saving time (see comments in the following link)

[http://paleocave.sciencesortof.com/2014/08/strange-behavior-from-the-cut-function-with-dates-in-r/](http://paleocave.sciencesortof.com/2014/08/strange-behavior-from-the-cut-function-with-dates-in-r/)

**Preserve time format when writing to CSV**


```
dat <- data.frame(time=as.POSIXlt("2013-04-25 09:00 BST"), quantity=1)
dat2 <- dat
dat2$time <- format(dat2$time, usetz=TRUE)
write.csv(dat2, "time.csv", row.names=FALSE)
```



## Tables {#tables}

======================================================

**Overview**

[http://www.statmethods.net/stats/frequencies.html](http://www.statmethods.net/stats/frequencies.html)

**xtabs()**


```
xtabs(formula = ~., data = parent.frame(), subset, sparse = FALSE,
      na.action, exclude = c(NA, NaN), drop.unused.levels = FALSE)
```


**Include NAs in xtabs**

Use <span style="text-decoration:underline;">addNA</span>...


```
xtabs(~myear + addNA(inorb), cemp_be)
```


or add “<span style="text-decoration:underline;">exclude=NULL, na.action=na.pass</span>”:


```
xtabs(~myear + inorb, cemp_be, exclude=NULL, na.action=na.pass)
```


**table()**

table(..., exclude = if (useNA == "no") c(NA, NaN), useNA = c("no", \
    "ifany", "always"), dnn = list.names(...), deparse.level = 1)

**[tabyl()](https://cran.r-project.org/web/packages/janitor/vignettes/tabyls.html) in the janitor package** 

Outputs tables formatted as data.frames

A lot easier to add sums, percentages etc.

Example of two-way-table:


```
humans %>% tabyl(gender, eye_color)
```


Example of two-way-table + sums:


```
humans %>% tabyl(gender, eye_color) %>% adorn_totals()
```


**ftable(): for ‘flat’ cross-tables** (note: often **dplyr::group_by() %>% dplyr::count()** is easier)

Input = output from xtabs or table


```
ftable(..., exclude = c(NA, NaN), row.vars = NULL, col.vars = NULL)
```


Example:


```
ftable(Titanic, row.vars = 1:2, col.vars = "Survived")
```


Also **CrossTable( ) **function in the **gmodels **package

**Interactive pivot tables in R**

[http://www.magesblog.com/2015/03/pivot-tables-with-r.html](http://www.magesblog.com/2015/03/pivot-tables-with-r.html)

[https://cran.r-project.org/web/packages/rpivotTable/vignettes/rpivotTableIntroduction.html](https://cran.r-project.org/web/packages/rpivotTable/vignettes/rpivotTableIntroduction.html)

**[Package forcats](https://forcats.tidyverse.org/)** - for instance, **fct_lump() **keeps only a top N number of the categories and moves everything else into an ‘Other’ bucket. Also see [here](https://blog.exploratory.io/why-factor-is-one-of-the-most-amazing-things-in-r-e967fe27d292) 


## Making (printing) tables {#making-printing-tables}

======================================================

**Basic HTML tables: [knitr::kable and kableExtra](https://cran.r-project.org/web/packages/kableExtra/vignettes/awesome_table_in_html.html) (update)**

**Making HTML tables using htmlTables**

Very simple yet quite flexible. Can be copied to Word

[http://cran.r-project.org/web/packages/htmlTable/vignettes/general.html](http://cran.r-project.org/web/packages/htmlTable/vignettes/general.html)

**Justification **example: First column left-justified, second columo right-justified:


```
htmlTable(df, align='lr')
```


For Norwegian letters, use **norwegianHTML() **or **toHTMLcode() **function, see my own “R selfmade functions.R”


```
df[,1] <- norwegianHTML(df[,1])
```


**addTable() **in the **rft** package: perhaps also able to add bold/italics of cell components (which I think htmlTables can’t)

[https://cran.r-project.org/web/packages/rtf/vignettes/rtf.pdf](https://cran.r-project.org/web/packages/rtf/vignettes/rtf.pdf)

**Package gt - Grammar of Tables**

[https://github.com/rstudio/gt](https://github.com/rstudio/gt) 

Preview using gt_preview() or output using as_raw_html() or as_rtf()  

**[huxtable](https://hughjonesd.github.io/huxtable/huxtable.html) **

- simple formatting, but also an intuitive interface for fine-grained control

- can do [conditional formatting](https://hughjonesd.github.io/huxtable/huxtable.html#conditional-formatting) 

- can do [multiple regression models  -> single regression table](https://hughjonesd.github.io/huxtable/huxtable.html#creating-a-regression-table)

- export to HTML and Markdown, export to Powerpoint and Word via [flextable](https://cran.r-project.org/package=flextable)

**Other packages for outputting HTML tables**

**xtable **- HTML or LaTEx

[https://cran.r-project.org/web/packages/xtable/vignettes/xtableGallery.pdf](https://cran.r-project.org/web/packages/xtable/vignettes/xtableGallery.pdf)

**[sjplot](https://strengejacke.wordpress.com/sjplot-r-package/) - **a bit less general. Nice for output of e.g. [regression models](http://strengejacke.de/sjPlot/sjt.lm/).

Best results if data first are _labelled_ using [set_labels](http://strengejacke.de/sjPlot/datainit/).

[http://www.r-bloggers.com/beautiful-table-outputs-in-r-part-2-rstats-sjplot/](http://www.r-bloggers.com/beautiful-table-outputs-in-r-part-2-rstats-sjplot/)

**[ggeffects](https://github.com/strengejacke/ggeffects)** - Create Tidy Data Frames of Marginal Effects for 'ggplot' from Model Outputs

**formattable **- stylish and can include horiz. barplots, check out examples! 

[http://www.magesblog.com/2016/01/formatting-table-output-in-r.html](http://www.magesblog.com/2016/01/formatting-table-output-in-r.html)

[https://github.com/renkun-ken/formattable](https://github.com/renkun-ken/formattable)

**rhandsontable**  - allows sparklines and images in table

[https://github.com/jrowen/rhandsontable](https://github.com/jrowen/rhandsontable)

**condformat - conditional formatting of tables**

[Example](https://www.r-bloggers.com/conditional-formatting-of-a-table-in-r/) (about ⅔ down on page)

**Finalfit - for regression tables**

[Example with workflow to Word](https://www.r-bloggers.com/finalfit-knitr-and-r-markdown-for-quick-results/) 

**Exporting HTML tables**

[http://stackoverflow.com/questions/3438226/exporting-r-tables-to-html](http://stackoverflow.com/questions/3438226/exporting-r-tables-to-html)

**Interactive (sortable) tables in markdown documents**

[Library DT](https://rstudio.github.io/DT/) ([simple example](https://holtzy.github.io/Pimp-my-rmd/#DT))

**Creating tables with basic statistics (means, percentages, etc. per group): Gmisc**

Made to work together with _htmlTables_, se above.

Also see _sjt.df()_ in _sjplot _above

[http://cran.r-project.org/web/packages/Gmisc/vignettes/Descriptives.html](http://cran.r-project.org/web/packages/Gmisc/vignettes/Descriptives.html)

Tables for lm model summaries: _sjt.lm()_ 

[http://www.r-bloggers.com/beautiful-tables-for-linear-model-summaries-rstats/](http://www.r-bloggers.com/beautiful-tables-for-linear-model-summaries-rstats/)

**ReporteR: Manager-friendly Word or Powerpoint documents created with R**

“One of the most useful features is to be able to insert R output (numbers, tables, and charts) into an existing document”. Can also merge/color table cells.

[http://blog.revolutionanalytics.com/2016/10/reporters.html](http://blog.revolutionanalytics.com/2016/10/reporters.html)

[http://davidgohel.github.io/ReporteRs/](http://davidgohel.github.io/ReporteRs/)

[https://davidgohel.github.io/ReporteRs/articles/flextable_examples.html](https://davidgohel.github.io/ReporteRs/articles/flextable_examples.html)

(If problems with Java, then [try this](https://www.r-statistics.com/2012/08/how-to-load-the-rjava-package-after-the-error-java_home-cannot-be-determined-from-the-registry/))

**Officer - allows you to create Word and Powerpoint docs**

[Crafting a PowerPoint Presentation with R](http://lenkiefer.com/2017/09/23/crafting-a-powerpoint-presentation-with-r/) and [package purrr](http://lenkiefer.com/2017/09/27/use-purrr/) 

**WordR – Package for Rendering Documents in MS Word Format**

Mashup of officer and ReporteRs

[https://www.r-bloggers.com/wordr-a-new-r-package-for-rendering-documents-in-ms-word-format/](https://www.r-bloggers.com/wordr-a-new-r-package-for-rendering-documents-in-ms-word-format/)


## Plotting {#plotting}

======================================================

R basically has 3 “generations” of plotting tools (see comparison [here](https://stackoverflow.com/questions/2759556/r-what-are-the-pros-and-cons-of-using-lattice-versus-ggplot2)):



1. “base” plot ([tutorial](https://blog.revolutionanalytics.com/2015/01/some-basics-for-base-graphics.html)) - the functions built into the R program (no packages needs to be loaded). Functions: plot(), lines(), points() etc. If you want to make something really custom-made, this is the one you need.
2. Package [lattice](http://lattice.r-forge.r-project.org) ([tutorial](http://lattice.r-forge.r-project.org/Vignettes/src/lattice-intro/lattice-intro.pdf)) - developed in the early 2000s, makes it much easier to plot data that varies in more than 2 dimensions (i.e. adding different colors and subplots). Less happening than Still under active development.
3. Package [ggplot2](https://ggplot2.tidyverse.org) ([tutorial](http://r-statistics.co/Complete-Ggplot2-Tutorial-Part1-With-R-Code.html)) -  developed in the 2010s, has same goal as _lattice_ but currently more popular and lots of active development and “side-projects”. For comparison of the default visual design see [here](https://learnr.wordpress.com/2009/06/28/ggplot2-version-of-figures-in-lattice-multivariate-data-visualization-with-r-part-1/). 

- All of these exist side by side, but cannot be combined in the same plot

- Each have different “logic” of the syntax

- Plotting complicated data (several colors of points, data split into subplots) needs a lot of code, which was the motivation for _lattice _and _ggplot_. The two latter have many of the same capabilites and you probably need only to learn one of them. 

- _lattice_ and _ggplot2 _have a different “look and feel” if you just make a plot without changing the default options. For a side-by-side comparison of lattice and ggplot2, see the series starting [here](https://learnr.wordpress.com/2009/06/28/ggplot2-version-of-figures-in-lattice-multivariate-data-visualization-with-r-part-1/) and summarized [here](https://learnr.wordpress.com/2009/08/26/ggplot2-version-of-figures-in-lattice-multivariate-data-visualization-with-r-final-part/).

**[R graphics book](http://www.e-reading.club/bookreader.php/137370/C486x_APPb.pdf)** (a bit old, contains base and lattice, but no ggplot)

[Base graphics cheat sheet](http://www.joyce-robbins.com/wp-content/uploads/2016/04/BaseGraphicsCheatsheet.pdf)

**Frequently asked questions about plotting (recommended!)**

[http://www.r-bloggers.com/15-questions-all-r-users-have-about-plots/](http://www.r-bloggers.com/15-questions-all-r-users-have-about-plots/)

**High resolution TIFF / EPS figures (for publication)**

[http://blog.revolutionanalytics.com/2009/01/10-tips-for-making-your-r-graphics-look-their-best.html](http://blog.revolutionanalytics.com/2009/01/10-tips-for-making-your-r-graphics-look-their-best.html)

[http://danieljhocking.wordpress.com/2013/03/12/high-resolution-figures-in-r/](http://danieljhocking.wordpress.com/2013/03/12/high-resolution-figures-in-r/)

_Note that the links above doesn’t treat cairographics and anti-aliasing (see links below). For best results, use:_


```
tiff("my_graph.tiff", height = 8, width = 17, units = 'cm', 
     compression = "lzw", res = 300, type="cairo", antialias="default")
```


_or_


```
png("my_graph.png", height = 8, width = 17, units = 'cm', 
     res = 300, type="cairo", antialias="default")
```


...and always remember **dev.off() **after plotting (saves the file)

**Sizing png graphs: a scale of 1.8 gives about the same proportions as windows()**

  so 


```
windows(18, 14)
```


  is equivalent to


```
scale <- 1.8
png("my_graph.png", height = 14*scale, width = 18*scale, units = 'cm',  
  res = 300, type="cairo", antialias="default")
```


**More on publication quality figures (anti-aliasing etc.)**

[http://www.r-bloggers.com/fast-track-publishing-using-knitr-exporting-images-for-sharing-and-press-part-iii/](http://www.r-bloggers.com/fast-track-publishing-using-knitr-exporting-images-for-sharing-and-press-part-iii/)

[http://is-r.tumblr.com/post/33421588764/using-cairographics-with-ggsave](http://is-r.tumblr.com/post/33421588764/using-cairographics-with-ggsave)

<span style="text-decoration:underline;">Arial font and EPS</span>

[http://www.fromthebottomoftheheap.net/2013/09/09/preparing-figures-for-plos-one-with-r/](http://www.fromthebottomoftheheap.net/2013/09/09/preparing-figures-for-plos-one-with-r/)

Solving 

[https://www.stat.auckland.ac.nz/~paul/R/PDF/pdfEncoding.html](https://www.stat.auckland.ac.nz/~paul/R/PDF/pdfEncoding.html)

**Plot layout and subplots (with base plot)**

[http://www.statmethods.net/advgraphs/layout.html](http://www.statmethods.net/advgraphs/layout.html)

**Color guides**

Jen Bryan’s guide:

[http://www.stat.ubc.ca/~jenny/STAT545A/block14_colors.html](http://www.stat.ubc.ca/~jenny/STAT545A/block14_colors.html)

colors in base R:

[http://www.stat.tamu.edu/~jkim/Rcolorstyle.pdf](http://www.stat.tamu.edu/~jkim/Rcolorstyle.pdf)

ggplot2 colour guides:

[http://www.cookbook-r.com/Graphs/Colors_(ggplot2)/](http://www.cookbook-r.com/Graphs/Colors_(ggplot2)/) (R Cookbook)

[http://learnr.wordpress.com/2009/04/15/ggplot2-qualitative-colour-palettes/](http://learnr.wordpress.com/2009/04/15/ggplot2-qualitative-colour-palettes/) (Learning R)

ggplot2 and base plot:

[http://blog.ggplot2.org/post/23995319650/choosing-colour-palettes-part-i-introduction](http://blog.ggplot2.org/post/23995319650/choosing-colour-palettes-part-i-introduction) (ggplot2)

Web-safe colours:

[http://cloford.com/resources/colours/websafe1.htm](http://cloford.com/resources/colours/websafe1.htm)

Matlab’s Jet colour scale: _tim.colors_ in package _fields_:

[http://svitsrv25.epfl.ch/R-doc/library/fields/html/tim.colors.html](http://svitsrv25.epfl.ch/R-doc/library/fields/html/tim.colors.html)

Explanation of Matlab’s “Jet” color scale

[http://stackoverflow.com/questions/7706339/grayscale-to-red-green-blue-matlab-jet-color-scale](http://stackoverflow.com/questions/7706339/grayscale-to-red-green-blue-matlab-jet-color-scale)

Turbo: An improved version of the Jet scale

[Mikhailov: Turbo, An Improved Rainbow Colormap for Visualization](https://ai.googleblog.com/2019/08/turbo-improved-rainbow-colormap-for.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+blogspot%2FgJZg+%28Google+AI+Blog%29) ([Python code](https://gist.github.com/mikhailov-work/ee72ba4191942acecc03fe6da94fc73f))

**Choosing colours in R:**

virid[://www.nceas.ucsb.edu/~frazier/RSpatialGuides/colorPaletteCheatsheet.pdf](https://www.nceas.ucsb.edu/~frazier/RSpatialGuides/colorPaletteCheatsheet.pdf)

[http://menugget.blogspot.no/2013/01/choosing-colors-visually-with-getcolors.html](http://menugget.blogspot.no/2013/01/choosing-colors-visually-with-getcolors.html)

**Test how you plot looks for the red-green colorblind (8% of men, 0.4% of women):**


```
install.packages("dichromat")
library(dichromat)
pie(rep(1,6), col = class_colors)             # original plot (example)
pie(rep(1,6), col = dichromat(class_colors))  # as seen by colorblind 
```


**The viridis colour scale - perceptually uniform and works in greyscale  **

[https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html](https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html)

**Color scales: Paul Tol’s page**

[https://personal.sron.nl/~pault/](https://personal.sron.nl/~pault/) (R code [here](https://tradeblotter.wordpress.com/2013/02/28/the-paul-tol-21-color-salute/))

**Color scales: RColorBrewer**

The colors from [http://colorbrewer2.org/](http://colorbrewer2.org/)

Syntax: 


```
brewer.pal(n, name) 
display.brewer.pal(n, name)
display.brewer.all()
```


**Interactive color space explorer**

[http://colorizer.org/](http://colorizer.org/)

**Colorspace package**

Palettes, mapping among assorted color spaces, interactive palette picker (with either a Tcl/Tk or a shiny GUI) [https://CRAN.R-project.org/package=colorspace](https://cran.r-project.org/package=colorspace)

**Easily make your own color scale functions **using leaflet functions _colorNumeric, colorBin, _

_colorQuantile, colorFactor_

These are functions that return functions. Made for leaflet, but can be generally useful.  

[https://rstudio.github.io/leaflet/colors.html](https://rstudio.github.io/leaflet/colors.html) 

**Using symbols/expressions in labels: expression()**



plotmath in R


<p id="gdcalert6" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: Definition term(s) &uarr;&uarr; missing definition? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert7">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>






**Examples of expression()**

<span style="text-decoration:underline;">Putting “Temperature (°C)” (also note the “~” for space between characters):</span>


```
plot(1:2, 1:2, pch = "") 
text(1.5, 1.5, expression(February~temperature~(degree*C))) 
```


<span style="text-decoration:underline;">Inserting percentage symbol, add subscript to T: </span>


```
text(1.5, 1.5, expression(Growth~(plain("%")~of~T[0])))
```


<span style="text-decoration:underline;">Greek letters, here mu: </span>


```
expression(DCB~(mu*g/kg~våtvekt))
expression(Kornstørrelse>63~mu*m)
```


<span style="text-decoration:underline;">Subscript with comma in it (both should work): </span>


```
plot(1, main=expression(Coeff['x,y']))
plot(1, main=expression(Coeff[list(x,y)]))
```


<span style="text-decoration:underline;">Other strings with comma in it </span>- replace comma with `*","*`:<span style="text-decoration:underline;"> </span>


```
expression(Chl~a~(median~per~passage*","*~mu*g/l))
```


<span style="text-decoration:underline;">Multiply sign</span>


```
plot(1,1,main=expression(A%.%B))
```


<span style="text-decoration:underline;">Superscript in front of letter (for isotopes, e.g. 13C)</span>


```
expression(" "^13 * C)
```


<span style="text-decoration:underline;">When you want **both** superscript and line feeds</span> (line feeds [doesn’t work](https://stackoverflow.com/a/27741196/1734247) inside expressions), use Unicode code starting with “\u”, e.g. \u00B2 for “superscript 2” (code from [here](https://en.wikipedia.org/wiki/List_of_Unicode_characters#Latin-1_Supplement)) or \u03BC for greek mu (code from [here](https://en.wikipedia.org/wiki/List_of_Unicode_characters#Greek_and_Coptic))


```
plot(1, 1, main="Deposisjon av nitrogen\n(mg/m\u00B2/år)")
```


**Some problems solved**

<span style="text-decoration:underline;">Axis labels in image() and image.plot()</span>

[http://stackoverflow.com/questions/17569218/r-image-function-of-graphics-package-add-axis-labels](http://stackoverflow.com/questions/17569218/r-image-function-of-graphics-package-add-axis-labels)

<span style="text-decoration:underline;">Mtext doesn’t work in image.plot()</span>

Put 


```
  title("")
```


on the line before mtext.

(http://stackoverflow.com/questions/12895783/r-language-mtext-not-working-with-image-plot-array)

<span style="text-decoration:underline;">mfg option of doesn’t seem to work the first time you use it. </span>

Solution: before first usage, run `par(mfg=c(1,1)); plot.new()`

[http://r.789695.n4.nabble.com/problem-with-mfg-argument-of-par-td820865.html](http://r.789695.n4.nabble.com/problem-with-mfg-argument-of-par-td820865.html)

<span style="text-decoration:underline;">mfg _can _be used together with layout() (in spite of the warnings in ?layout). </span>

[http://www.r-bloggers.com/mfg-mfcol-mfrow-and-layout-secret-friends/](http://www.r-bloggers.com/mfg-mfcol-mfrow-and-layout-secret-friends/)

<span style="text-decoration:underline;">Plotting point densities as colours:</span>

[http://stackoverflow.com/questions/17093935/r-scatter-plot-symbol-color-represents-number-of-overlapping-points](http://stackoverflow.com/questions/17093935/r-scatter-plot-symbol-color-represents-number-of-overlapping-points)

**Choosing optimal span parameter for loess()**

[http://www.fromthebottomoftheheap.net/2012/07/24/whats-wrong-with-loess-for-palaeo-data/](http://www.fromthebottomoftheheap.net/2012/07/24/whats-wrong-with-loess-for-palaeo-data/)


## Plotting using ggplot2 {#plotting-using-ggplot2}

[The official documentation](http://ggplot2.tidyverse.org)

[ggplot cheatsheet with many good tips](http://zevross.com/blog/2014/08/04/beautiful-plotting-in-r-a-ggplot2-cheatsheet-3/#move-the-labels-away-from-the-plot-and-add-color-theme-axis.title.x) 

[List of cheat sheets](http://stackoverflow.com/questions/3446495/ggplot2-cheat-sheet)

Introductions/tutorials:

[http://blog.revolutionanalytics.com/2009/09/ggplot2-and-the-grammar-of-graphics.html](http://blog.revolutionanalytics.com/2009/09/ggplot2-and-the-grammar-of-graphics.html)

[http://www.aridhia.com/technical-tutorials/the-fundamentals-of-ggplot-explained/](http://www.aridhia.com/technical-tutorials/the-fundamentals-of-ggplot-explained/)

[http://www.ling.upenn.edu/~joseff/rstudy/summer2010_ggplot2_intro.html](http://www.ling.upenn.edu/%7Ejoseff/rstudy/summer2010_ggplot2_intro.html)

[http://sape.inf.usi.ch/quick-reference/ggplot2](http://www.r-bloggers.com/visualising-f1-telemetry-data-and-plotting-latitude-and-longitude-with-ggplot-map-projections-in-r/)

[http://www.r-bloggers.com/visualising-f1-telemetry-data-and-plotting-latitude-and-longitude-with-ggplot-map-projections-in-r/](http://www.r-bloggers.com/visualising-f1-telemetry-data-and-plotting-latitude-and-longitude-with-ggplot-map-projections-in-r/)

[http://www.r-bloggers.com/nice-ggplot-intro-tutorial-just-run-the-commands-about-6-pages/](http://www.r-bloggers.com/nice-ggplot-intro-tutorial-just-run-the-commands-about-6-pages/)

Some other ggplot adjustments

[http://www.r-bloggers.com/how-to-customize-ggplot2-graphics/](http://www.r-bloggers.com/how-to-customize-ggplot2-graphics/)

[http://www.r-bloggers.com/how-i-build-up-a-ggplot2-figure/](http://www.r-bloggers.com/how-i-build-up-a-ggplot2-figure/)

Locator in ggplot?

[http://stackoverflow.com/questions/9450873/locator-equivalent-in-ggplot2-for-maps](http://stackoverflow.com/questions/9450873/locator-equivalent-in-ggplot2-for-maps)

Change defaults (e.g. font size, distance between axes axis label ) ggplot2:

[http://stackoverflow.com/questions/11955229/how-to-change-the-default-font-size-in-ggplot2](http://stackoverflow.com/questions/11955229/how-to-change-the-default-font-size-in-ggplot2)

Remove some data series from the legend:

[https://jdegen.wordpress.com/2012/05/03/how-to-get-ride-of-the-diagonal-line-in-ggplot-legends/](https://jdegen.wordpress.com/2012/05/03/how-to-get-ride-of-the-diagonal-line-in-ggplot-legends/)

Hide unwanted legend in ggplot (here: size)

ggplot(dat, aes(x=x, y=y, color=datatype, size=1)) + geom_point() + guides(size=FALSE)

[https://docs.google.com/document/d/19Vz5iC0n968CPYvlEJi_Jz0J8XGWE-3Zjm5N800GEN4/edit#](http://#)

Combine two legends into one:

[http://stackoverflow.com/questions/33236495/combine-legend-in-ggplot2](http://stackoverflow.com/questions/33236495/combine-legend-in-ggplot2)

Arranging ggplots using grid.arrange() and arrangeGrob() in package **gridExtra**, or alternatively layOut() in package **wq**

[http://stackoverflow.com/questions/8112208/how-can-i-obtain-an-unbalanced-grid-of-ggplots/8127096#8127096](http://stackoverflow.com/questions/8112208/how-can-i-obtain-an-unbalanced-grid-of-ggplots/8127096#8127096)

[http://is-r.tumblr.com/post/34628702940/ggtutorial-day-2-grid-arrange](http://is-r.tumblr.com/post/34628702940/ggtutorial-day-2-grid-arrange)

Also see “Dates/times in ggplot2” above

Different colours under/over zero:

[http://stackoverflow.com/questions/17959817/filling-area-under-curve-based-on-value-in-ggplot2](http://stackoverflow.com/questions/17959817/filling-area-under-curve-based-on-value-in-ggplot2)

Pass string as variable to ggplot, e.g. for functions or loops

[http://stackoverflow.com/questions/31864618/pass-string-as-variable-to-log-function-in-r](http://stackoverflow.com/questions/31864618/pass-string-as-variable-to-log-function-in-r)

<span style="text-decoration:underline;">geom_contour</span> with labels (using <span style="text-decoration:underline;">directlabels</span> package)

[https://stackoverflow.com/questions/38154679/r-adding-legend-and-directlabels-to-ggplot2-contour-plot](https://stackoverflow.com/questions/38154679/r-adding-legend-and-directlabels-to-ggplot2-contour-plot)

Position text in corner(s):

[https://stackoverflow.com/a/32124365/1734247](https://stackoverflow.com/a/32124365/1734247) 

**Great list of plot types**

[http://r-statistics.co/Top50-Ggplot2-Visualizations-MasterList-R-Code.html#Slope%20Chart](http://r-statistics.co/Top50-Ggplot2-Visualizations-MasterList-R-Code.html#Slope%20Chart) 

**ggplot (and dplyr) as a creativity engine**

[https://www.r-bloggers.com/the-financial-times-uses-r-for-quantitative-journalism/https://www.r-bloggers.com/the-financial-times-uses-r-for-quantitative-journalism/](https://www.r-bloggers.com/the-financial-times-uses-r-for-quantitative-journalism/) (sell links to presentation and code)

**ggplot2 extensions**

[http://www.ggplot2-exts.org/gallery/](http://www.ggplot2-exts.org/gallery/)

geofacet - [https://hafen.github.io/geofacet/](https://hafen.github.io/geofacet/) 

ggimage - [https://cran.r-project.org/web/packages/ggimage/vignettes/ggimage.html](https://cran.r-project.org/web/packages/ggimage/vignettes/ggimage.html) including _geom_subview_ to plot a scatter plot of plots (e.g. scatter plot of pie plots)

[scatter_pie](https://cran.r-project.org/web/packages/scatterpie/vignettes/scatterpie.html) - specifically made for adding scatter plot of pie plots \
    (Note: only useful when colors (categories) are constant and pie slice sizes change, not vice versa)

gghighlight - [https://yutani.rbind.io/post/2018-06-16-re-intro-to-gghighlight/](https://yutani.rbind.io/post/2018-06-16-re-intro-to-gghighlight/) 

**Add p-values and pairwise comparisons to boxplots using <span style="text-decoration:underline;">ggpubr</span>**

[https://www.r-bloggers.com/add-p-values-and-significance-levels-to-ggplots/](https://www.r-bloggers.com/add-p-values-and-significance-levels-to-ggplots/) 

**plotluck() - “I’m feeling lucky” for ggplot (for quick exploration)**

[https://cran.r-project.org/web/packages/plotluck/vignettes/plotluck.html](https://cran.r-project.org/web/packages/plotluck/vignettes/plotluck.html)

**Bugs** - If there seems to be a bug in ggplot, check

[https://github.com/hadley/ggplot2/issues](https://github.com/hadley/ggplot2/issues)

**Cowplot: Custom arrangement of several ggplots in a single graph file**

...and add labels like (a), (b) as well


```
gg1 <- … 
gg2 <- … 
library(cowplot)
ggg <- plot_grid(gg1, gg2, labels = c('(a)', '(b)'), ncol = 2)
# For better results, increase margin on left side of plot  
…  + theme(plot.margin = margin(12, 6, 6, 32))
```


Can also make small subplots/pictures in plot. See [here](https://cran.r-project.org/web/packages/cowplot/vignettes/introduction.html)

Alternative packages are [patchwork ](https://www.r-exercises.com/2018/05/25/how-to-plot-with-patchwork/) and [gridExtra](http://lightonphiri.org/blog/ggplot2-multiple-plots-in-one-graph-using-gridextra) (but alignment is difficult with the latter)

<span style="text-decoration:underline;">Manipulating grobs (older , pre cowplot, stuff) </span>

[http://stackoverflow.com/questions/23746718/separate-y-axis-labels-by-facet-or-remove-legend-but-keep-the-space](http://stackoverflow.com/questions/23746718/separate-y-axis-labels-by-facet-or-remove-legend-but-keep-the-space)

[http://stackoverflow.com/questions/12041042/how-to-plot-just-the-legends-in-ggplot2](http://stackoverflow.com/questions/12041042/how-to-plot-just-the-legends-in-ggplot2)

[http://blog.mckuhn.de/2013/04/2d-plot-with-histograms-for-each.html](http://blog.mckuhn.de/2013/04/2d-plot-with-histograms-for-each.html)

**ggpubr: ‘ggplot2’ Based Publication Ready Plots**

[Vignette](http://www.sthda.com/english/rpkgs/ggpubr/index.html)

**Change axis labels depending on data, e.g. entries with P < 0.05 in bold **

Use e.g. `face = c("plain", "bold")[change$signif2]`

See “broom” part below

**Fonts and special characters in ggplot**



par (see “family”)


<p id="gdcalert7" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: Definition term(s) &uarr;&uarr; missing definition? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert8">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>






windowsFonts() gives you the available fonts

Adding annotation in different font:


```
ggplot() + annotate(
  "text", x = 5, y = 22, label = "h/i", adj = 1, size = 8, 
  family = "Wingdings 3")
```


<span style="text-decoration:underline;">Using extrafont package for e.g., “Humor” font: </span>

[http://aschinchon.wordpress.com/2014/03/09/doras-choice/](http://aschinchon.wordpress.com/2014/03/09/doras-choice/)

[http://blog.revolutionanalytics.com/2012/09/how-to-use-your-favorite-fonts-in-r-charts.html](http://blog.revolutionanalytics.com/2012/09/how-to-use-your-favorite-fonts-in-r-charts.html)

[http://www.fromthebottomoftheheap.net/2013/09/09/preparing-figures-for-plos-one-with-r/](http://www.fromthebottomoftheheap.net/2013/09/09/preparing-figures-for-plos-one-with-r/)



*   For special characters such as subscript/superscript, greek letters etc., , there is the possibility for using either [expression()](https://stat.ethz.ch/R-manual/R-devel/library/grDevices/html/plotmath.html) (also [here](https://quantpalaeo.wordpress.com/2015/04/20/expressions-in-r/)), [bquote()](https://stackoverflow.com/questions/36420367/difference-between-using-bquote-and-expressionpaste-for-labels-in-ggplot2) or [Unicode](https://stackoverflow.com/questions/27690729/greek-letters-symbols-and-line-breaks-inside-a-ggplot-legend-label/27741196#27741196) (e.g., “m\u00B2” for “m<sup>2</sup>”):

However,



*   Unlike expression(), bquote() can [show the value of a variable](http://www.endmemo.com/program/R/bquote.php)
*   expression() cannot include “line break” (written as [“\n”](https://stackoverflow.com/a/1761086/1734247) in R), then you have to show your special characters using Unicode , which should suffice in [many cases](https://en.wikipedia.org/wiki/List_of_Unicode_characters#Latin-1_Supplement)

**A couple of ggplot themes**

**1. For a single plot**


```
theme_custom <- theme(legend.text=element_text(size=18, colour="black"),
        	legend.title=element_text(size=18, colour="black"),
        	axis.title=element_text(size=20, colour="black"),
        	axis.title.x=element_text(vjust=-0.2),
        	axis.title.y=element_text(vjust=1.7),
        	axis.text=element_text(size=15, colour="black"),
        	panel.background=element_rect(fill="white"), panel.grid=element_blank(),
        	axis.line=element_line(colour="black"),
        	plot.margin = unit(c(0.3,0.3,0.8,0.8), "cm"))
```


**2. For a plot with 2 x 3 subplots** (height = 7.5, width = 10.5)


```
theme_custom <-   theme_bw() + 
  theme(panel.border = element_rect(color=NA), axis.line = element_line(color="black"),
        axis.text = element_text(color = "black", size = 12),
        axis.title = element_text(color = "black", size = 16),
        strip.text = element_text(color = "black", size = 14),
        strip.background = element_rect(fill = NA, color = NA),
        axis.title.y = element_text(margin = margin(r = 20)),
        panel.spacing.x = unit(0.5, "lines"), panel.spacing.y = unit(2, "lines"),
        legend.title=element_text(size=14),
        legend.text=element_text(size=13)
        )
```


**Other themes**

[https://cran.r-project.org/web/packages/hrbrthemes/index.html](https://cran.r-project.org/web/packages/hrbrthemes/index.html)

[https://cran.r-project.org/web/packages/ggthemes/vignettes/ggthemes.html](https://cran.r-project.org/web/packages/ggthemes/vignettes/ggthemes.html)

[http://sape.inf.usi.ch/quick-reference/ggplot2/themes](http://sape.inf.usi.ch/quick-reference/ggplot2/themes)

**Ggplot completely remade in D3.js (!) - in plotly**

[http://www.r-bloggers.com/ggplot2-docs-completely-remade-in-d3-js/](http://www.r-bloggers.com/ggplot2-docs-completely-remade-in-d3-js/)

[http://ropensci.github.io/plotly/ggplot2/](http://ropensci.github.io/plotly/ggplot2/)

**GGally - “matrix” version of ggplot2**

_<span style="text-decoration:underline;">Scatterplot matrix</span>_

[http://stackoverflow.com/questions/20079977/ggally-unexpected-behavior-with-ggpairs-diag-list-continuous-densit](http://stackoverflow.com/questions/20079977/ggally-unexpected-behavior-with-ggpairs-diag-list-continuous-densit)

_<span style="text-decoration:underline;">Visual correlation matrices for large number of variables</span>_ (also see [corrr](https://drsimonj.svbtle.com/explore-correlations-in-r-with-corrr))

[https://github.com/briatte/ggcorr](https://github.com/briatte/ggcorr)

_<span style="text-decoration:underline;">Fluctuation plots - visual representation of contingency tables</span>_

[http://stackoverflow.com/questions/17114209/ggfluctuation-in-different-color](http://stackoverflow.com/questions/17114209/ggfluctuation-in-different-color)

_<span style="text-decoration:underline;">Network plots</span>_

[https://github.com/briatte/ggnet](https://github.com/briatte/ggnet)

_<span style="text-decoration:underline;">Parallell coordinate plots</span>_

[http://stackoverflow.com/questions/12793717/how-to-plot-non-standardized-data-with-ggplot2](http://stackoverflow.com/questions/12793717/how-to-plot-non-standardized-data-with-ggplot2)

**Cleveland dot plots**

[Code recipe](http://www.joyce-robbins.com/blog/2016/06/02/datavis-with-rdrawing-a-cleveland-dot-plot-with-ggplot2/) (plot below)

[Another](https://uc-r.github.io/cleveland-dot-plots) 



<p id="gdcalert8" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/R-tips3.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert9">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/R-tips3.png "image_tooltip")


**GGalt - interpolating splines, improved map projection, improved density plots, [encircling points automagically](https://github.com/hrbrmstr/ggalt#encircling-points-automagically)**

**[lollipop charts](https://github.com/hrbrmstr/ggalt#lollipop-charts)**



<p id="gdcalert9" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/R-tips4.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert10">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/R-tips4.png "image_tooltip")


[https://github.com/hrbrmstr/ggalt](https://github.com/hrbrmstr/ggalt)

**WVPlots, a selection of “pre-made” ggplots**

[http://rpubs.com/jmount/WVPlots](http://rpubs.com/jmount/WVPlots)

**Visreg - package for visualization of regression models (including ANOVA, ANCOVA,**

**and non-linear regression)**

Includes nice vignette:

[http://cran.r-project.org/web/packages/visreg/index.html](http://cran.r-project.org/web/packages/visreg/index.html)

**Not to show a regression line in visreg:**

use linetype = none (lty=0) inside line.par()

See "\\niva-of5\osl-userdata$\DHJ\Documents\Hjelp\Camilla H\lm-analyse (jan2014 - 2).R"

**How to plot gamm() models using visreg:**


```
mod <- gamm(y ~ s(x1) + s(x2), my_dataset, correlation=corARMA(p=1, q=0))
# This is the crucial part:
mod$data <- my_dataset
# Continue as usual (using the $gam part of the object)
visreg(mod$gam)
```


**3D model plot for glm using glmModelPlot.R (made by mages)**

[https://gist.github.com/mages/dedfb0d97082f0f0e0ab](https://gist.github.com/mages/dedfb0d97082f0f0e0ab)

Example:

[www.r-bloggers.com/visualising-the-predictive-distribution-of-a-log-transformed-linear-model/](http://www.r-bloggers.com/visualising-the-predictive-distribution-of-a-log-transformed-linear-model/)

**The plot3D package by Karline Soetaert (check vignette!)**

[https://cran.r-project.org/web/packages/plot3D/vignettes/volcano.pdf](https://cran.r-project.org/web/packages/plot3D/vignettes/volcano.pdf)

[http://www.sthda.com/english/wiki/impressive-package-for-3d-and-4d-graph-r-software-and-data-visualization](http://www.sthda.com/english/wiki/impressive-package-for-3d-and-4d-graph-r-software-and-data-visualization)

**Nice overview of 3D packages**

[http://www.r-bloggers.com/3d-plots-in-r/](http://www.r-bloggers.com/3d-plots-in-r/)

**3D scatterplots with labels**

[http://statmethods.wordpress.com/2012/01/30/getting-fancy-with-3-d-scatterplots/](http://statmethods.wordpress.com/2012/01/30/getting-fancy-with-3-d-scatterplots/)



<p id="gdcalert10" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/R-tips5.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert11">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/R-tips5.png "image_tooltip")


**3D scatterplots with spheres - rgl**

[http://casoilresource.lawr.ucdavis.edu/software/r-advanced-statistical-package/interactive-3d-plots-rgl-package/](http://casoilresource.lawr.ucdavis.edu/software/r-advanced-statistical-package/interactive-3d-plots-rgl-package/)

**3D surfaces and movies with rgl**

[http://husnusensoy.wordpress.com/2011/09/08/line-of-sight-los-analysis-part-2/](http://husnusensoy.wordpress.com/2011/09/08/line-of-sight-los-analysis-part-2/)

Also check out the <span style="text-decoration:underline;">sinclair.clover</span> example in package <span style="text-decoration:underline;">agridat:</span>

[http://cran.r-project.org/web/packages/agridat/vignettes/agridat.pdf](http://cran.r-project.org/web/packages/agridat/vignettes/agridat.pdf) (fig. on page 8)

[http://cran.r-project.org/web/packages/agridat/agridat.pdf](http://cran.r-project.org/web/packages/agridat/agridat.pdf) (code for that figure)

**Export from rgl**

Interactive 3D objects can be included in pdf documents (in U3D format) which can be rendered with Adobe Reader. Example:

[https://www.tug.org/texshowcase/Laurana.pdf](https://www.tug.org/texshowcase/Laurana.pdf) (note: download and open with Adobe Reader)

From RGL, export to PLY (see below), and then one can write to pdf (U3D format) using MeshLab. ( Not tried)

[http://www.inside-r.org/packages/cran/rgl/docs/writePLY](http://www.inside-r.org/packages/cran/rgl/docs/writePLY)

[http://meshlab.sourceforge.net/](http://meshlab.sourceforge.net/)

[http://flightriot.com/meshlab-3d-model-export-test-for-3d-pdf-generation/](http://flightriot.com/meshlab-3d-model-export-test-for-3d-pdf-generation/)

[https://www.youtube.com/watch?v=FmyRaJHqKd0](https://www.youtube.com/watch?v=FmyRaJHqKd0)

PS: PLY files can also be read by Blender.

More info on U3D:

[http://en.wikipedia.org/wiki/Universal_3D](http://en.wikipedia.org/wiki/Universal_3D)

**Alternative to RGL:  rthreejs**

[http://www.htmlwidgets.org/showcase_threejs.html](http://www.htmlwidgets.org/showcase_threejs.html)

**Overlay a grid (here (interpolation) on a globe** (with stars and all)

[http://menugget.blogspot.no/2012/03/ridiculous-proof-of-concept-xyz.html](http://menugget.blogspot.no/2012/03/ridiculous-proof-of-concept-xyz.html)

**Treemaps**

[https://stackoverflow.com/questions/21233477/performance-clustermap-in-r](https://stackoverflow.com/questions/21233477/performance-clustermap-in-r)

Packages treemapify (ggplot2 solution, see below), treemap, and portfolio.



<p id="gdcalert11" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/R-tips6.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert12">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/R-tips6.png "image_tooltip")


**“Back-to-back” histograms**

[http://www.r-bloggers.com/making-back-to-back-histograms/](http://www.r-bloggers.com/making-back-to-back-histograms/)

**“Pirate plot” - an improvement of bar plots (or dynamite plots)**

[http://rpubs.com/yarrr/pirateplot](http://rpubs.com/yarrr/pirateplot)

**dualplot() function - a function for time series plots with two time series**

[https://www.r-bloggers.com/dual-axes-time-series-plots-may-be-ok-sometimes-after-all/](https://www.r-bloggers.com/dual-axes-time-series-plots-may-be-ok-sometimes-after-all/)

**Visually weighted regression plots (watercolor plots)**

[http://www.nicebread.de/visually-weighted-watercolor-plots-new-variants-please-vote/](http://www.nicebread.de/visually-weighted-watercolor-plots-new-variants-please-vote/)

**Transition plots (boxes connected by arrows): gMisc**

[http://cran.r-project.org/web/packages/Gmisc/vignettes/transitionPlot.html](http://cran.r-project.org/web/packages/Gmisc/vignettes/transitionPlot.html)

**Sankey diagrams**

[http://www.sankey-diagrams.com/sankey-diagram-software/](http://www.sankey-diagrams.com/sankey-diagram-software/)

**Arc diagrams**

[http://gastonsanchez.wordpress.com/2013/02/02/star-wars-arc-diagram/?relatedposts_exclude=1052](http://gastonsanchez.wordpress.com/2013/02/02/star-wars-arc-diagram/?relatedposts_exclude=1052)

**“Signal plot” in R (and Python)**

[https://www.r-bloggers.com/unknown-pleasures/](https://www.r-bloggers.com/unknown-pleasures/)

**The world’s best Bezier arrow**

[http://gforge.se/2013/05/getting-to-the-point-an-alternative-to-the-bezier-arrow/](http://gforge.se/2013/05/getting-to-the-point-an-alternative-to-the-bezier-arrow/)

**Subplots / embedded plots within a larger plot: package ggsubplot**

**Also see <span style="text-decoration:underline;">cowplot</span> above**

[http://cran.r-project.org/web/packages/ggsubplot/index.html](http://cran.r-project.org/web/packages/ggsubplot/index.html)

A kind of vignette:

[http://vita.had.co.nz/papers/embedded-plots.pdf](http://vita.had.co.nz/papers/embedded-plots.pdf)

**Interactive plotting:**

[http://www.rosuda.org/iplots/](http://www.rosuda.org/iplots/)

- not able to install

[http://igraph.sourceforge.net/](http://igraph.sourceforge.net/)

[https://code.google.com/p/playwith/](https://code.google.com/p/playwith/)

**Plot by drag and drop of variables**

[https://github.com/zzawadz/dragulaR](https://github.com/zzawadz/dragulaR) 

**Positioning text using grconvertX, grconvertY**

[http://r.789695.n4.nabble.com/Specifying-relative-position-of-text-in-a-plot-td849431.html](http://r.789695.n4.nabble.com/Specifying-relative-position-of-text-in-a-plot-td849431.html)

**Visualising large amounts of hourly environmental data**

[http://metvurst.wordpress.com/2013/03/04/visualising-large-amounts-of-hourly-environmental-data-2/](http://metvurst.wordpress.com/2013/03/04/visualising-large-amounts-of-hourly-environmental-data-2/)

[http://www.openair-project.org/Default.aspx](http://www.openair-project.org/Default.aspx)

**Label placement**

[https://stackoverflow.com/questions/7611169/intelligent-point-label-placement-in-r](https://stackoverflow.com/questions/7611169/intelligent-point-label-placement-in-r)

[ggrepel](https://cran.r-project.org/web/packages/ggrepel/) - for avoiding overlapping labels in scatter plots ([blog post](http://blog.revolutionanalytics.com/2016/01/avoid-overlapping-labels-in-ggplot2-charts.html))

[directlabels](http://directlabels.r-forge.r-project.org/) for adding labels to e.g., lines

textplot() in wordcloud: [http://blog.fellstat.com/?cat=11](http://blog.fellstat.com/?cat=11) 

Move badly placed labels manually (interactively) for best annotation:

_mvlabs() in package caroline_

[http://cran.r-project.org/web/packages/caroline/index.html](http://cran.r-project.org/web/packages/caroline/index.html)

**Coefficient plots**

[http://www.carlislerainey.com/2012/06/30/coefficient-plots-in-r/](http://www.carlislerainey.com/2012/06/30/coefficient-plots-in-r/)

**Plot pie charts in a scatterplot**

pies() in package caroline

[http://cran.r-project.org/web/packages/caroline/caroline.pdf](http://cran.r-project.org/web/packages/caroline/caroline.pdf)

**Plot pie charts on a map**

Package [mapplots](https://cran.r-project.org/web/package=mapplot), add_map() function

**Plot a simple clock**

plotClock() in package caroline (see above)

**Spie charts - nice way to show proportions and over-representation \
**(see [http://www.cs.huji.ac.il/~feit/papers/Spie03TR.pdf](http://www.cs.huji.ac.il/~feit/papers/Spie03TR.pdf) )

spie() in package caroline (see above)

**Ternary diagrams (“triangular plots”) - for soils etc.**

[http://www.ggtern.com/category/example/](http://www.ggtern.com/category/example/)

**rBlocks**

[http://ramnathv.github.io/posts/rblocks-pkg/index.html](http://ramnathv.github.io/posts/rblocks-pkg/index.html)

[https://github.com/ramnathv/rblocks/issues/9](https://github.com/ramnathv/rblocks/issues/9)

**Rank line plots for multivariate data**

[http://beckmw.wordpress.com/2013/04/01/a-nifty-line-plot-to-visualize-multivariate-time-series/](http://beckmw.wordpress.com/2013/04/01/a-nifty-line-plot-to-visualize-multivariate-time-series/)

**ANOVA with multiple comparison and "standard" barplots**

[http://cran.r-project.org/web/packages/agricolae/agricolae.pdf](http://cran.r-project.org/web/packages/agricolae/agricolae.pdf)

**cloroplethr for easier cloropleth maps **

[http://www.r-bloggers.com/easy-data-maps-with-r-the-choroplethr-package/](http://www.r-bloggers.com/easy-data-maps-with-r-the-choroplethr-package/)

**Sector diagrams a la Florence Nightingale**

[http://perfdynamics.blogspot.no/2013/01/going-beyond-florence-nightingales-data.html](http://perfdynamics.blogspot.no/2013/01/going-beyond-florence-nightingales-data.html)

**Rastervis - plots for raster data (incl. vector diagrams)**

[http://rastervis.r-forge.r-project.org/](http://rastervis.r-forge.r-project.org/)

**Saving plots to file**

[http://www.stat.berkeley.edu/classes/s133/saving.html](http://www.stat.berkeley.edu/classes/s133/saving.html)

**Making SVG (Scalable Vector Graphics) for use on the web**

Either svg() in Base R or ggsave() in ggplots:

[http://www.r-bloggers.com/using-r-to-produce-scalable-vector-graphics-for-the-web/](http://www.r-bloggers.com/using-r-to-produce-scalable-vector-graphics-for-the-web/)

[http://timelyportfolio.blogspot.no/2014/10/reponsive-svg-in-your-rstudio-browser.html](http://timelyportfolio.blogspot.no/2014/10/reponsive-svg-in-your-rstudio-browser.html)

Lightweight SVG - faster, smaller files, and leaves text as it is:

[https://github.com/hadley/svglite](https://github.com/hadley/svglite)

See this “[review” of the svg produced by R and svglite](https://www.r-bloggers.com/svg-from-stats-software-the-good-the-bad-and-the-ugly/)  

For editing:

[https://inkscape.org/en/#overview](https://inkscape.org/en/#overview)

Clipping SVGs: [https://www.sarasoueidan.com/blog/css-svg-clipping/](https://www.sarasoueidan.com/blog/css-svg-clipping/) 

**Exporting plots to _Inkscape _to edit graphs**

[http://www.r-bloggers.com/making-infographics-using-r-and-inkscape/](http://www.r-bloggers.com/making-infographics-using-r-and-inkscape/)

**How to get the data behind plot.gam** (testet, it works)

[http://stats.stackexchange.com/questions/7795/how-to-obtain-the-values-used-in-plot-gam-in-mgcv](http://stats.stackexchange.com/questions/7795/how-to-obtain-the-values-used-in-plot-gam-in-mgcv)

**Advanced layout and font use**

[http://alstatr.blogspot.no/2015/02/philippine-infographic-recapitulation.html#comment-1865225996](http://alstatr.blogspot.no/2015/02/philippine-infographic-recapitulation.html#comment-1865225996)

**General advice on plotting**

[http://www.kirchkamp.de/oekonometrie/pdf/gra-p.pdf](http://www.kirchkamp.de/oekonometrie/pdf/gra-p.pdf)


## RStudio {#rstudio}

======================================================

**RStudio:**

[http://www.rstudio.com/ide/](http://www.rstudio.com/ide/)

**RStudio tips**

[Create PowerPoint presentations, filter data, custom knitr engines, magic !source comments ++](https://blog.rstudio.com/2018/11/19/rstudio-1-2-preview-the-little-things/)

[Install shortcut for debugonce](https://github.com/moodymudskipper/debugonce) 

**Some possible RStudio problems**

<span style="text-decoration:underline;">RStudio can’t find Knitr library on startup</span>

[http://stackoverflow.com/questions/14201452/rstudio-cant-find-my-library-on-startup](http://stackoverflow.com/questions/14201452/rstudio-cant-find-my-library-on-startup)

[https://support.rstudio.com/hc/communities/public/questions/202828346-Path-errors-on-start-up-in-Windows-7](https://support.rstudio.com/hc/communities/public/questions/202828346-Path-errors-on-start-up-in-Windows-7)

[Add page breaks when knitting to Word](https://stackoverflow.com/questions/35267508/how-to-create-a-new-page-using-knit-word?noredirect=1&lq=1)

[Rstudio is slow - gctorture(FALSE) to turn off very frequent garbage collection](https://stackoverflow.com/a/50591831/1734247)**  **

<span style="text-decoration:underline;">Knitting button fails running Pandoc (error: “pandoc document conversion failed with error 11”)</span>

Options:



1. Try [this](https://github.com/rstudio/rstudio/issues/4072#issuecomment-473406177) 
2. Use  \
knitr:knit("Name_of_file.rmd") \
The latter will at least produce an .md file which can be pushed to Github and shown there. But note that paths to figures will be wrong! You must manually change this `(`Remember to pull in RStudio afterwards!)
3. <span style="text-decoration:underline;">Best option?</span> Make a [github_document](https://rmarkdown.rstudio.com/github_document_format.html) and turn off html generation: \
`Output: \
  Github_document: \
	html_preview: false \
	toc: true \
`

**When RStudio output to console (execution of simple commands) is sluggish**

[Reset the state of RStudio](https://support.rstudio.com/hc/en-us/articles/200534577-Resetting-RStudio-s-State) (as suggested [here](https://support.rstudio.com/hc/en-us/community/posts/200666277--extremely-slow-execution-of-simple-commands))

But for NIVA folks: <span style="text-decoration:underline;">use C:/Data instead of H:</span>

**Section organizer in RStudio**



*   Add at least four trailing dashes (-), equal signs (=), or pound signs (#) to automatically creates a code section, which shows up in the shortcut list below the window, and is collapsible (click the tiny triangle left of the code line) 



<p id="gdcalert12" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/R-tips7.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert13">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/R-tips7.png "image_tooltip")




*   Get rid of unwanted sections:

If you have a script with lines of pound signs  (################) separating code, change these by replacing “####” with “#oooo”, then they don’t come up as unnamed code sections

**Knitting from R markdown (.Rmd) documents**

[Official](http://rmarkdown.rstudio.com/)

[Convince me to start using R Markdown](https://community.rstudio.com/t/convince-me-to-start-using-r-markdown/1636/37)

[Best practices](https://community.rstudio.com/t/best-practices-for-organizing-rmarkdown-projects/914/17) 

source() runs code just like usual. [read_chunk()](https://yihui.name/knitr/demo/externalization/) is only for the special case where you want to just read - but not evaluate - code (i.e. showing the code in the finished document). Also see [here](https://stackoverflow.com/questions/38818492/executing-external-source-in-knitr-and-printing-the-external-code-chunk) and [here](https://stackoverflow.com/questions/15501622/making-knitr-run-a-r-script-do-i-use-read-chunk-or-source). Example: changing [this result](https://github.com/yihui/knitr-examples/blob/master/113-externalization.Rmd) ([code](https://raw.githubusercontent.com/yihui/knitr-examples/master/113-externalization.Rmd)) into [this result](https://github.com/yihui/knitr-examples/blob/master/113-externalization.md) by inserting [this script](https://github.com/yihui/knitr-examples/blob/master/113-foo.R). 

**How to use markdown documents with parameters**


```
---
title: "airplanes"
params:
  carrier: AA
output: html_document
---
```{r}
# get the name of the airline
my_airline <- airlines[airlines$carrier == params$carrier, "name"]
```
This is a report about `r my_airline` and all of the wonderful arrival times that they have.
```


(see [gist](https://gist.github.com/colearendt/132e4ae84342e3aa93772a21ddf49a2a))

**Markdown itself**

[Wikipedia](https://en.wikipedia.org/wiki/Markdown)

[stackedit.io](https://stackedit.io/app#) - interactive Markdown editor (log in using Google)

[Best Markdown editors](https://www.slant.co/topics/1852/~best-markdown-editors-for-windows)  

**Using notebooks**

[Official intro](http://rmarkdown.rstudio.com/r_notebooks.html)

[Nice guide including important key combinations](https://github.com/rstudio/rstudio-conf/blob/master/2017/R_Notebook_Workflows-Jonathan_McPherson/r-notebook-workflows.Rmd)

Note that Notebooks can (and should?) also be “knitted” to more “permanent” files 

**Using projects**

[https://support.rstudio.com/hc/en-us/articles/200526207-Using-Projects](https://support.rstudio.com/hc/en-us/articles/200526207-Using-Projects)

[https://www.tidyverse.org/articles/2017/12/workflow-vs-script/](https://www.tidyverse.org/articles/2017/12/workflow-vs-script/) 

[http://stat545.com/block002_hello-r-workspace-wd-project.html](http://stat545.com/block002_hello-r-workspace-wd-project.html)  

[https://stackoverflow.com/questions/34539011/saving-in-r-studio](https://stackoverflow.com/questions/34539011/saving-in-r-studio)

**Visual debugging in RStudio:**

[http://www.r-bloggers.com/visual-debugging-with-rstudio/](http://www.r-bloggers.com/visual-debugging-with-rstudio/)

**Choosing R version on startup**

Hold down the Control key during the launch of RStudio ([ref](https://support.rstudio.com/hc/en-us/articles/200486138-Using-Different-Versions-of-R))

**4 ways to be [more productive](https://jozefhajnala.gitlab.io/r/r905-rstudio-terminal/), using RStudio's terminal**


## Organizing and restructuring data {#organizing-and-restructuring-data}

======================================================

**subset - to get data with or (especially) without a specific column**

[http://stackoverflow.com/questions/5234117/how-to-drop-columns-by-name-in-a-data-frame](http://stackoverflow.com/questions/5234117/how-to-drop-columns-by-name-in-a-data-frame)

**Permanently delete variable from data.frame**



1. `df <- subset(df, select = -c('a','c') )`

[http://stackoverflow.com/questions/4605206/drop-columns-r-data-frame](http://stackoverflow.com/questions/4605206/drop-columns-r-data-frame)

OR:


```
   2. df$a <- NULL 
```


 	NOTE: OK for data.frames, will give warnings of you use it on a [tibble](https://cran.r-project.org/web/packages/tibble/vignettes/tibble.html) 

OR:


```
   3. library(dplyr)
	df <- df %>% select(-a) 
```


 

**sapply vs. lapply vs. apply. vs. tapply vs. by vs. aggregate**

[http://stackoverflow.com/questions/3505701/r-grouping-functions-sapply-vs-lapply-vs-apply-vs-tapply-vs-by-vs-aggrega?rq=1](http://stackoverflow.com/questions/3505701/r-grouping-functions-sapply-vs-lapply-vs-apply-vs-tapply-vs-by-vs-aggrega?rq=1)

[http://lamages.blogspot.no/2012/01/say-it-in-r-with-by-apply-and-friends.html](http://lamages.blogspot.no/2012/01/say-it-in-r-with-by-apply-and-friends.html)

**matrixStats - like apply but for big data (faster and memory efficient)**

[http://www.r-bloggers.com/matrixstats-optimized-subsetted-matrix-calculations/](http://www.r-bloggers.com/matrixstats-optimized-subsetted-matrix-calculations/)

**multi.sapply - apply multiple functions to multiple columns**

[http://rsnippets.blogspot.nl/2011/11/applying-multiple-functions-to-data.html](http://rsnippets.blogspot.nl/2011/11/applying-multiple-functions-to-data.html)

or use dplyr:


```
starwars %>%
  summarise_at(vars(height:mass), list(mean=mean, sd=sd), na.rm = TRUE)
```


**Restructuring data with library _reshape2_**

NOTE: reshape2 has been superseded by <span style="text-decoration:underline;">tidyr</span>, see below

Good intro and simple reference:

[http://seananderson.ca/2013/10/19/reshape.html](http://seananderson.ca/2013/10/19/reshape.html)

[http://www.r-statistics.com/2012/01/aggregation-and-restructuring-data-from-r-in-action/](http://www.r-statistics.com/2012/01/aggregation-and-restructuring-data-from-r-in-action/)

(About the original reshape:)

[http://www.statmethods.net/management/reshape.html](http://www.statmethods.net/management/reshape.html)

**Restructuring data with _tidyr_ (and pipes)**

[https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf](https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf)

[http://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html](http://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html)

[http://blog.rstudio.org/2014/07/22/introducing-tidyr/](http://blog.rstudio.org/2014/07/22/introducing-tidyr/)

[http://garrettgman.github.io/tidying/](http://garrettgman.github.io/tidying/)

**Spread over multiple columns**

Spread over multiple columns in tidyr: use cast,  or gather + unite + spread ([example](https://stackoverflow.com/questions/30592094/r-spreading-multiple-columns-with-tidyr))

Example: we have these data:


```
df <- read.table(textConnection("
Year Month  Salt     Flu
2005  1.00  32.0  0.525 
2005  2.00  32.1  0.028
2005  3.00  32.1  0.30
2006  1.00  32.3  0.197 
2006  2.00  32.3  0.107 
2006  3.00  32.1  0.250
2007  2.00  33.1  0.412
"), header = TRUE)
```


We want this:


```
  Year Flu_1 Flu_2 Flu_3 Salt_1 Salt_2 Salt_3
1 2005 0.525 0.028  0.30   32.0   32.1   32.1
2 2006 0.197 0.107  0.25   32.3   32.3   32.1
3 2007    NA 0.412    NA     NA   33.1     NA
```


This _could_ have been the solution but doesn’t work:


```
df %>% spread(Month, Salt:Flu)
```


Solution (creates the file above):


```
df %>% gather(variable, value, Salt:Flu) %>%
  unite(x, variable, Month) %>%
  spread(x, value)
```


But if the goal actually is to look at e.g. the difference between month 1 and 2, one can also calculate this quite directly:


```
last_minus_first <- function(x)
  last(x) - first(x)
df %>%
  filter(Month %in% c(1,2)) %>%
  group_by(Year) %>%
  summarise_all(funs(last_minus_first))

df %>% spread(Month, Salt)
df %>% select(-Flu) %>% spread(Month, Salt)
df %>% spread(Month, Salt:Flu)
df %>% gather(variable, value, Salt:Flu) %>%
  unite(x, variable, Month) %>%
  spread(x, value)
```


**Pipes for more readable code**

[http://blog.revolutionanalytics.com/2014/07/magrittr-simplifying-r-code-with-pipes.html](http://blog.revolutionanalytics.com/2014/07/magrittr-simplifying-r-code-with-pipes.html)

One [quite expressive example](http://www.jakubglinka.com/2017-03-01-text_mining_part1/)

(but [not](http://www.fromthebottomoftheheap.net/2015/06/03/my-aversion-to-pipes/) [everybody](http://stackoverflow.com/a/38885239/1734247) likes them)

**Restructuring data with _plyr_**

**Note: plyr has been replaced by purrr, and is no longer under active development** ([ref](https://jennybc.github.io/purrr-tutorial/bk01_base-functions.html#why_not_plyr))

[http://www.stat.cmu.edu/~cshalizi/statcomp/lectures/12/lecture-12.pdf](http://www.stat.cmu.edu/%7Ecshalizi/statcomp/lectures/12/lecture-12.pdf)

[http://www.cerebralmastication.com/2009/08/a-fast-intro-to-plyr-for-r/](http://www.cerebralmastication.com/2009/08/a-fast-intro-to-plyr-for-r/)

<span style="text-decoration:underline;">http://www.stat.cmu.edu/~cshalizi/statcomp/11/lectures/14/lecture-14.pdf</span>

Means for all variables: more effective with reshape

[http://stackoverflow.com/questions/1407449/for-each-group-summarise-means-for-all-variables-in-dataframe-ddply-split](http://stackoverflow.com/questions/1407449/for-each-group-summarise-means-for-all-variables-in-dataframe-ddply-split)

**Restructuring data with _purrr_**

**Note: <code>purrr::by_row </code>[has been moved](http://www.brodrigues.co/blog/2017-06-19-dplyr-0-70-tutorial/) to the new purrrlyr package</strong>

[https://jennybc.github.io/purrr-tutorial/index.html](https://jennybc.github.io/purrr-tutorial/index.html) Probably the best tutorial

[https://github.com/hadley/purrr](https://github.com/hadley/purrr)

[https://blog.rstudio.org/2016/01/06/purrr-0-2-0/](https://blog.rstudio.org/2016/01/06/purrr-0-2-0/)

[http://www.r-bloggers.com/using-purrr-with-dplyr/](http://www.r-bloggers.com/using-purrr-with-dplyr/)

Adding a new variable to data.frames in a list is [not so easy](https://stackoverflow.com/questions/42028710/add-new-variable-to-list-of-data-frames-with-purrr-and-mutate-from-dplyr), though

**Example:** apply function **MSE **(returns a data frame) for each value of **station**. Using <span style="text-decoration:underline;">split</span> (not group_by) to make a list, <span style="text-decoration:underline;">'drop = TRUE'</span> to ignore stations with no data, <span style="text-decoration:underline;">map_df</span> to return a data frame (not a list), and .id = "station" to add a variable named ‘station’ to the result

(example from "K:\Avdeling\214-Oseanografi\DHJ\2016_10_dkferrybox\Analyser\06_ChlA_analysis3.R")


```
mse <- function(df, var_pred, var_obs){
  data.frame(mse = mean(x_res^2), 
       variance = mean((x_res - mean(x_res))^2),
       bias = mean(x_res))
  }
mse_all <- my_data %>%
  split(.$station, drop = TRUE) %>%
  map_df(function(x) mse(x, "Flu", "CHLA.5"), .id = "station")
```


<span style="text-decoration:underline;">Also see Broom below</span> for an example for getting regression results from lots of regressions

<span style="text-decoration:underline;">Using shorthand notation for the anonymous function in map_df (note the dot in front of x):</span>


```
  map_df(~{mse(.x, "Flu", "CHLA.5")}, .id = "station")
```


**Purrr::map for functions with 2 or more inputs**


```
fn <- function(a,b) a*10 + b
# Test: 
fn(2,8)
# Method 1 (for 2 inputs) - uses the order of arguments
map2(c(1,2,2), c(3,6,5), ~fn(.x, .y))
# Method 2 (for 2 or more inputs) - uses the name of arguments
pmap(list(a = c(1,2,2), b = c(3,6,5)), fn)
# Method 2, alternative using pipe (%>%)
list(a = c(1,2,2), b = c(3,6,5)) %>% pmap(fn)
```


**Progress bars in purrr::map**

<span style="text-decoration:underline;">version 1 (from [cderv](https://github.com/tidyverse/purrr/issues/149))</span>


```
dummy_list <- rerun(10, runif(5))
# create the progress bar with a dplyr function. 
pb <- progress_estimated(length(dummy_list))
res <- dummy_list %>%
  map(~{
    # update the progress bar (tick()) and print progress (print())
    pb$tick()$print()
    Sys.sleep(0.5)
    sum(.x)
  })
```


<span style="text-decoration:underline;">version 2 (from [rud.is](https://rud.is/b/2017/03/27/all-in-on-r%E2%81%B4-progress-bars-on-first-post/)):</span>


```
pb_add <- function(.pb) 
  if ((!is.null(.pb)) && inherits(.pb, "Progress") && (.pb$i < .pb$n))
     .pb$tick()$print()
arduously_long_nchar <- function(input_var, .pb=NULL) {
  pb_add(.pb)
  Sys.sleep(1)
  nchar(input_var)
  }
abcde <- letters[1:5]
pb <- progress_estimated(length(abcde))
map_int(abcde, arduously_long_nchar, .pb=pb)
```


**purrr:possibly()** and **purrr:safely()** (plus transpose) and as alternative to try()

`possibly()` = “would you kindly apply the function wherever possible, and if not, tell me where there was an issue”


```
possibly(some_function, otherwise = "something wrong here")
```


`safely()` = as possibly(), but returns a more complex object: it returns a list of lists: for each object, <span style="text-decoration:underline;">result</span> (the value) and <span style="text-decoration:underline;">error</span>(the message). Can be handled using` transpose()`.

[http://blog.rdata.lu/post/2017-12-21-skip-errors-in-r-by-not-writing-loops/](http://blog.rdata.lu/post/2017-12-21-skip-errors-in-r-by-not-writing-loops/) 

[https://blog.rstudio.com/2016/01/06/purrr-0-2-0/](https://blog.rstudio.com/2016/01/06/purrr-0-2-0/) (plus transpose)

**Perform function for each row_ \
_**Easiest with dplyr (below). Example: 90 percentile for all nine percentile types


```
x <- c(3.5, 9.7, 3.9, 1, 5.2, 7.3, 3.5, 1.3, 0.68)
data.frame(type = 1:9) %>% group_by(type) %>% 
  summarise(Q90 = quantile(x, 0.9, type = type))
```


**Restructuring data with _dplyr \
_**Newer/alternative version of plyr, different syntax (and does a bit less), but faster (and easier to understand, for some…)

[http://seananderson.ca/2014/09/13/dplyr-intro.html](http://seananderson.ca/2014/09/13/dplyr-intro.html)

dplyr compared with base R

[http://www.statsblogs.com/2014/02/10/how-dplyr-replaced-my-most-common-r-idioms/](http://www.statsblogs.com/2014/02/10/how-dplyr-replaced-my-most-common-r-idioms/)

Convert list of data frames (with the same variables) to a single data frame: [bind_rows](https://stackoverflow.com/questions/2851327/convert-a-list-of-data-frames-into-one-data-frame)

What to use [extract()](https://stackoverflow.com/a/25932131/1734247) for - extract one column into multiple columns using regex

**dplyr vs data.table: syntax, speed etc.**

[An overall comparison (Stack O.)](https://stackoverflow.com/questions/21435339/data-table-vs-dplyr-can-one-do-something-well-the-other-cant-or-does-poorly)

[A very early speed test by Tal Galili](http://www.r-statistics.com/2013/09/a-speed-test-comparison-of-plyr-data-table-and-dplyr/)

[A better speed test by Arun](http://arunsrinivasan.github.io/dplyr_benchmark/) (_also a nice summary of dplyr and data.table syntax_)

NOTE: my own experience (running the tests of Arun) is that <span style="text-decoration:underline;">data.table is a lot faster</span> on big data sets (but the syntax is still awkward!)

It is also possible to run [dplyr commands on data.tables](https://stackoverflow.com/questions/27511604/dplyr-on-data-table-am-i-really-using-data-table) and get some speed improvement

**dplyr vs data.table**

[http://stackoverflow.com/questions/21435339/data-table-vs-dplyr-can-one-do-something-well-the-other-cant-or-does-poorly/27718317#27718317](http://stackoverflow.com/questions/21435339/data-table-vs-dplyr-can-one-do-something-well-the-other-cant-or-does-poorly/27718317#27718317)

[http://stackoverflow.com/questions/27511604/dplyr-on-data-table-am-i-really-using-data-tabl](http://stackoverflow.com/questions/27511604/dplyr-on-data-table-am-i-really-using-data-tabl)

**Non-standard (NSE) vs. standard evaluation in dplyr (and subset)**

In short: [https://www.r-bloggers.com/non-standard-evaluation-and-standard-evaluation-in-dplyr/](https://www.r-bloggers.com/non-standard-evaluation-and-standard-evaluation-in-dplyr/)

NSE can be bad: [http://www.alshum.com/nse/](http://www.alshum.com/nse/)

NSE in dplyr: [https://cran.r-project.org/web/packages/dplyr/vignettes/nse.html](https://cran.r-project.org/web/packages/dplyr/vignettes/nse.html)

NSE chapter in ‘Advanced R’: [http://adv-r.had.co.nz/Computing-on-the-language.html](http://adv-r.had.co.nz/Computing-on-the-language.html)

**Programming in tidyverse using rlang/tidyeval (‘state-of-the-art’ approach)**

But somewhat difficult, see <span style="text-decoration:underline;">wrapr</span> below for simpler approach

[Quick demonstration of tidyeval](http://www.brodrigues.co/blog/2017-06-19-dplyr-0-70-tutorial/) (starts about 30% down the page)

[Why is tidyeval useful?](http://www.brodrigues.co/blog/2017-08-27-why_tidyeval/)

Recipes: [http://dplyr.tidyverse.org/articles/programming.html](http://dplyr.tidyverse.org/articles/programming.html)


```
Example:
Grouping variable is fixed to g1 (known as non-standard evaluation): 
df %>%
  group_by(g1) %>%
  summarise(a = mean(a))
Make function where we can choose grouping variable: 
my_summarise <- function(df, grouping_variable) {
  grouping_variable <- quo(grouping_variable)
  df %>%
    group_by(!!grouping_variable) %>%
    summarise(a = mean(a))
}
my_summarise(df, g1)
```


**Handling non-standard (NSE) - other (and older) approaches**

<span style="text-decoration:underline;">Use wrapr to make NSE functions work with variables</span>

May be considered to be [the simplest for part-time R users](http://www.win-vector.com/blog/2017/08/lets-have-some-sympathy-for-the-part-time-r-user/).

[https://www.r-bloggers.com/wrapr-for-sweet-r-code/](https://www.r-bloggers.com/wrapr-for-sweet-r-code/)


```
# EXAMPLE:
my_summarise <- function(group_var, response_var) {
  let(list(x = group_var, y = response_var),
    diamonds %>%
      group_by(x) %>%
      summarise(mean(y))
    )
}
my_summarise("cut", "price")
my_summarise("clarity", "carat")
```


- Alternative, use <span style="text-decoration:underline;">replyr</span>:

[replyr intro](http://www.win-vector.com/blog/2016/12/comparative-examples-using-replyrlet/) and [a more realistic example](http://www.win-vector.com/blog/2016/12/using-replyrlet-to-parameterize-dplyr-expressions/)

The relationship between wrapr and replyr is explained in [this video](https://www.r-bloggers.com/step-debugging-magrittrdplyr-pipelines-in-r-with-wrapr-and-replyr/)

**gapply (package replyr) **- a specialization of "The Split-Apply-Combine" strategy with all three steps wrapped into a single operator

[https://www.r-bloggers.com/a-simple-example-of-using-replyrgapply/](https://www.r-bloggers.com/a-simple-example-of-using-replyrgapply/)

**broom - add-on to plyr for converting statistical analysis objects into Tidy Data Frames**

(Also see <span style="text-decoration:underline;">purrr</span> above)

[Vignette](https://cran.r-project.org/web/packages/broom/vignettes/broom.html) and [broom + dplyr vignette](https://cran.r-project.org/web/packages/broom/vignettes/broom_and_dplyr.html)

[http://stackoverflow.com/questions/22713325/fitting-several-regression-models-with-dplyr](http://stackoverflow.com/questions/22713325/fitting-several-regression-models-with-dplyr)

Example: getting all the time trends from separate regressions of fuel economy (city miles per gallon, ‘cty’) for each car model:


```
get_reg_coef <- function(df) {
  lm <- lm(cty~year, data = df)
  subset(tidy(lm), term == "year")
}

change <- mpg %>%
  split(.$model) %>%
  map_df(~get_reg_coef(.), .id = "model") %>%
  bind_rows()

# Plot effects
# Sorted by effect size, and p-value < 0.05 marked with bold red text
change <- change %>%
  filter(!is.na(p.value)) %>%
  arrange(estimate)  # needed because of the "theme(axis.text.y = ...." part

change$model <- with(change, factor(model, levels = model)) # works change has already
                                                            # been sorted by
                                                            # 'estimate'

change$signif <- ifelse(change$p.value <= 0.05, "Significant", "Not significant")
change$signif2 <- as.numeric(change$p.value <= 0.05) + 1


ggplot(change, aes(model, estimate, fill = signif)) + 
  geom_col(color = "black") +
  scale_fill_manual(values = c("grey60", "firebrick")) +
  geom_errorbar(aes(ymin = estimate - std.error, 
                    ymax = estimate + std.error),
                width = 0.4) +
  theme(axis.text.y = element_text(
    face = c("plain", "bold")[change$signif2],
    color = c("black", "firebrick")[change$signif2])
    ) +
  coord_flip()
```




<p id="gdcalert13" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/R-tips8.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert14">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/R-tips8.png "image_tooltip")


**Getting range and mean for all numeric variables (over all rows) - plyr**


```
ldply(dat.sel[laply(dat.sel, is.numeric)], range, na.rm=TRUE)
ldply(dat.sel[laply(dat.sel, is.numeric)], mean, na.rm=TRUE)
```


**Getting mean and SD for all variables (for rows grouped by other variables) - plyr**

Note: a bit outdated, better use **summarise_all** in **dplyr**! See below… :-)

Example: mean, SD and sample size for all combinations of Date and Area


```
mdata <- melt(data, id=c("Date","Area"))
data_mean <- cast(mdata, Date + Area~variable, mean, na.rm=TRUE)
data_sd <- cast(mdata, Date + Area~variable, sd, na.rm=TRUE)
data_N <- cast(mdata, Date + Area~variable, function(x) sum(!is.na(x)))
colnames(data_mean) <- paste(colnames(data_mean), "mean", sep="_")
colnames(data_sd) <- paste(colnames(data_sd), "sd", sep="_")
colnames(data_N) <- paste(colnames(data_N), "N", sep="_")
data_aggregated <- cbind(data_mean, data_sd, data_N)
```


Same example using summarise_all in dplyr:


```
data %>% 
  group_by(Date,Area) %>%
  summarise_all(funs(median, mean))
```


**Conditional join in dplyr - cannot be done (so far)**

[https://www.mango-solutions.com/blog/in-between-a-rock-and-a-conditional-join](https://www.mango-solutions.com/blog/in-between-a-rock-and-a-conditional-join) 

**Safe joins with the [safejoin](https://github.com/moodymudskipper/safejoin) package **

[Introduction/cheatsheet, and solutions to  bunch of StackOverflow questions](https://www.reddit.com/r/rstats/comments/awoch8/introducing_package_safejoin_join_safely_using/)

**Tidying messy datasets (article by Hadley)**

[http://vita.had.co.nz/papers/tidy-data.pdf](http://vita.had.co.nz/papers/tidy-data.pdf)

**Replace codes with labels/strings from a lookup table**

[http://stackoverflow.com/questions/10002536/how-do-i-replace-numeric-codes-with-value-labels-from-a-lookup-table](http://stackoverflow.com/questions/10002536/how-do-i-replace-numeric-codes-with-value-labels-from-a-lookup-table)

**Rename variable**

<span style="text-decoration:underline;">dplyr package:</span>


```
df <- rename(df, Newname = Oldname, Newname2 = Oldname2))
```


<span style="text-decoration:underline;">reshape or plyr packages:</span>


```
df <- rename(df, replace=c("Oldname" = "Newname", "Oldname2" = "Newname2"))
```



## Maps (basic) {#maps-basic}

======================================================

There is more to find in [3. Advanced](https://drive.google.com/open?id=1z2IW4-0E8_WLxG80zzvS9xT1rA3yeMzSVxAyRstETXU) and [4. Web and interactive](https://drive.google.com/open?id=1PByB6pJydkomfaafqSTbpIgbtyY-Uw_YWOWzUK30jLI)


### Quick to-do’s {#quick-to-do’s}

**Transformation of coordinates between Long,Lat and UTM (using sp, the old system)**


```
library(sp)
crs_longlat <- "+proj=longlat"
crs_utm <- "+proj=utm +zone=32 +ellps=WGS84 +datum=WGS84 +units=m"
# note that you might want to change zone=32 to e.g. 33
```


**- from Long,Lat to UTM zone 32**


```
SP <- SpatialPoints(df[,c("Longitude", "Latitude")],
                 proj4string=CRS(crs_longlat)
                 )
SP.UTM <- spTransform(SP, CRR(crs_utm))
# Add transformed coords to data set
df$UTM_x <- SP.UTM@coords[,1]
df$UTM_y <- SP.UTM@coords[,2]
```


**- from UTM zone 32 to Long,Lat**


```
SP.utm <- SpatialPoints(df[,c("UTM_x", "UTM_y"), 
                        proj4string=CRS(crs_utm)
                        )
SP.longlat <- spTransform(SP.utm, CRS(crs_longlat))
df$Longitude <- SP.longlat@coords[,1]
df$Latitude <- SP.longlat@coords[,2]
```


**Example data (used in examples below)**


```
my_points1 <- data.frame(
  City = c("Oslo", "Bergen", "Kristiansand"),
  Long = c(10.7333, 5.33, 7.9972),
  Lat = c(59.9167, 60.3894, 58.1472),
  stringsAsFactors = FALSE
)

my_points2 <- data.frame(
  Station = c("Frierfjorden", "Hvitsten", "Akerøy"),
  Long = c(9.61800, 10.63530, 10.87016),
  Lat = c(59.10437, 59.59103, 59.04749),
  stringsAsFactors = FALSE
)
```


**Plot very simple maps** (using library _maps_ and _mapdata_)

Note that most islands (e.g. Nøttery, Tjøm, Hvaler) are absent!


```
library(maps)
very_simple_map <- map_data("world")
simple_map <- map_data("worldHires", c("Norway", "Sweden"))

# Map from library(maps)
ggplot(my_points1, aes(Long, Lat)) +
  annotation_map(very_simple_map, fill = "lightgreen") +
  geom_point() +
  coord_map("lambert", parameters = c(10.4, 59.3))
```




<p id="gdcalert14" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/R-tips9.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert15">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/R-tips9.png "image_tooltip")



```
# Map from library(mapdata)
ggplot(my_points2, aes(Long, Lat)) +
  annotation_map(simple_map, fill = "lightgreen") +
  geom_point() +
  coord_map("lambert", parameters = c(10.4, 59.3))
```




<p id="gdcalert15" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/R-tips10.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert16">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/R-tips10.png "image_tooltip")



```
# Add annotation (and change limits)
ggplot(my_points1, aes(Long, Lat)) +
  annotation_map(simple_map, fill = "lightgreen") +
  geom_point() +
  coord_map("lambert", parameters = c(10.4, 59.3), 
            xlim = c(5, 11.5), ylim = c(57.9, 60.7)) +
  geom_text(aes(label = City), hjust = 0, nudge_x = 0.1)
```




<p id="gdcalert16" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/R-tips11.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert17">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/R-tips11.png "image_tooltip")



```
Show all countries in same colour
…  + annotation_map(my_map, fill = "blue")
Make cloropleth map for country data
…  + geom_map(aes(fill = GDP), map = my_map)
```


**Show data on a dynamic map (in web browser, or in RStudio)**


```
library(leaflet)
leaflet() %>%
  addTiles() %>%
  addMarkers(lng = my_points2$Long, lat = my_points2$Lat,
         	popup = my_points2$Station)
```


See [here](https://docs.google.com/document/d/1PByB6pJydkomfaafqSTbpIgbtyY-Uw_YWOWzUK30jLI/edit#heading=h.tzl0trs7wckc) for more info on leaflet



<p id="gdcalert17" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/R-tips12.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert18">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/R-tips12.png "image_tooltip")




<p id="gdcalert18" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/R-tips13.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert19">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/R-tips13.png "image_tooltip")


**Read and plot shapefiles (using sf, the new system)**


```
[example: script "10_Check_Vannmiljo_MSMDI_RSL.Rmd" in Seksjon 214/MARTINI]
library(sf)
# Norway (coastline) in UTM coordinates
nc_norway <- st_read("K:/Kart/N1000/norge2.shp")
st_crs(nc_norway) <- "+proj=utm +zone=33"  # set coordinate system

# Rivers of Norway
# Note: we don't have to set coordinate system, it is stored in the data 
nc_rivers <- st_read("K:\\Kart\\ELVIS\\Hovedelv\\elvis_hovedelv.shp")
# Pick only the main rivers
nc_mainrivers <- nc_rivers %>% filter(STRAHLER >= 7) 

# Make point data from dataset
sf_points <- st_as_sf(my_points2,
                      	coords = c("Long", "Lat"),
                      	crs = "+proj=longlat +ellps=WGS84")

# Plotting (note: drawing the plot takes ca. 1 minute)
# Note that the map is shown with lat/long and a nice projection
ggplot(nc_norway) + 
  geom_sf()

# Add rivers - add the following lines:
+ geom_sf(data = nc_mainrivers, color = "blue")

# Add points from dataset to plot - add the following lines:
+  geom_sf(data = sf_stations, size = 4, shape = 20)

# Add labels next to points - add the following lines:
+  geom_sf_text(data = df_stations, 
                aes(label = Vannlokalitet), 
                size = 3, hjust = 0, nudge_x = 2000)

# Plot Oslofjorden only - add the following lines:

```



*   `coord_sf(xlim = c(198700, 301600), ylim = c(6553200, 6669600), `

    ```
             expand = FALSE)

    ```



### Introductions

Best intro, including simplest way of putting markers on a google map (RgoogleMaps):

**NOTE: **Getting maps from Google now requires [a little red tape](https://medium.com/superkoders/ultimate-guide-to-google-maps-d86ad945636a). See [this walkthrough](https://stackoverflow.com/a/52617929/1734247). 

[http://www.molecularecologist.com/2012/09/making-maps-with-r/](http://www.molecularecologist.com/2012/09/making-maps-with-r/)

Others:

[https://sites.google.com/site/spatialr/plottingmaps](https://sites.google.com/site/spatialr/plottingmaps)

[https://freshbiostats.wordpress.com/2014/02/16/spatial-objects-in-r-i/](https://freshbiostats.wordpress.com/2014/02/16/spatial-objects-in-r-i/)

[https://freshbiostats.wordpress.com/2014/05/19/spatial-objects-in-r-ii/](https://freshbiostats.wordpress.com/2014/05/19/spatial-objects-in-r-ii/)

**Intruduction to sf**, the new class of spatial objects replacing **sp**

Much easier to use together with ggplot. For instance, points given in lat-long can be plotted on a map given in UTM without problems, and the other way round   

[https://www.r-spatial.org/r/2018/10/25/ggplot2-sf.html](https://www.r-spatial.org/r/2018/10/25/ggplot2-sf.html) 

[https://www.r-spatial.org/r/2018/10/25/ggplot2-sf-2.html](https://www.r-spatial.org/r/2018/10/25/ggplot2-sf-2.html)

[https://www.r-spatial.org/r/2018/10/25/ggplot2-sf-3.html](https://www.r-spatial.org/r/2018/10/25/ggplot2-sf-3.html) 

[Reading/converting map data from shapefiles etc.](https://cran.r-project.org/web/packages/sf/vignettes/sf2.html#reading_and_writing_directly_to_and_from_spatial_databases) 


```
nc_norway <- st_read("K:/Kart/N1000/norge2.shp")
st_crs(nc_norway) <- "+proj=utm +zone=33"
nc_rivers <- st_read("K:\\Kart\\ELVIS\\Hovedelv\\elvis_hovedelv.shp")
nc_mainrivers <- nc_rivers %>% filter(STRAHLER >= 7) 
ggplot(nc_norway) + geom_sf() + geom_sf(data = nc_mainrivers)
```


**Using R as a GIS** - both on vector and raster data, plus Google maps

[https://pakillo.github.io/R-GIS-tutorial/](https://pakillo.github.io/R-GIS-tutorial/)

**Grid overlay over Google maps**

[http://rstudio-pubs-static.s3.amazonaws.com/16948_38af70d4c22e45df84a2fd69d8698d93.html](http://rstudio-pubs-static.s3.amazonaws.com/16948_38af70d4c22e45df84a2fd69d8698d93.html)

**Intro to Raster**

[http://rpubs.com/etiennebr/visualraster](http://rpubs.com/etiennebr/visualraster)

[Controlling legend layout](https://stackoverflow.com/a/9473333/1734247) 

While a raster can accept a factor as values, the package raster seems unable to show a legend for categorical values, e.g. land use. Then use [rastervis](https://oscarperpinan.github.io/rastervis/) ([example](https://stackoverflow.com/a/20321664/1734247))  

Need to overlay a raster by setting alpha between 0 and 1?[ Convert to a dataframe and use ggplot](https://stackoverflow.com/a/48975387/1734247) 

**Spatial cheatsheet**

[http://www.maths.lancs.ac.uk/~rowlings/Teaching/UseR2012/cheatsheet.html](http://www.maths.lancs.ac.uk/~rowlings/Teaching/UseR2012/cheatsheet.html)

**Example of <code>sp</code> classes: </strong> 

- making spatialPoints of one data set

- make spatialPolygonsDataFrame from a shapefile

- overlay to get the shape (county) of each point - function over()

[http://www.r-bloggers.com/points-polygons-and-power-outages/](http://www.r-bloggers.com/points-polygons-and-power-outages/)

- for overlap, the 

[http://r-sig-geo.2731867.n2.nabble.com/point-in-polygon-or-over-help-td7583635.html](http://r-sig-geo.2731867.n2.nabble.com/point-in-polygon-or-over-help-td7583635.html)

**Updated maps - some alternatives**

[http://www.milanor.net/blog/?p=534](http://www.milanor.net/blog/?p=534)

**Rgooglemaps**

[http://www.molecularecologist.com/2012/09/making-maps-with-r/](http://www.molecularecologist.com/2012/09/making-maps-with-r/)

[http://blog.revolutionanalytics.com/2010/01/how-to-combine-google-maps-and-data-in-r.html](http://blog.revolutionanalytics.com/2010/01/how-to-combine-google-maps-and-data-in-r.html)

**ggmap - simple static maps from Google / OpenStreetmap**

[http://www.r-bloggers.com/how-to-choose-a-new-business-location-with-r/](http://www.r-bloggers.com/how-to-choose-a-new-business-location-with-r/)

[http://wilkinsondarren.wordpress.com/tag/ggmap/](http://wilkinsondarren.wordpress.com/tag/ggmap/)

[http://blog.revolutionanalytics.com/2012/07/making-beautiful-maps-in-r-with-ggmap.html](http://blog.revolutionanalytics.com/2012/07/making-beautiful-maps-in-r-with-ggmap.html)

Cheat sheet:

[https://www.nceas.ucsb.edu/~frazier/RSpatialGuides/ggmap/ggmapCheatsheet.pdf](https://www.nceas.ucsb.edu/~frazier/RSpatialGuides/ggmap/ggmapCheatsheet.pdf)

Cropping polygons - zooming in on ggmap without getting strange polygons:

[http://stackoverflow.com/questions/13469566/polygons-nicely-cropping-ggplot2-ggmap-at-different-zoom-levels](http://stackoverflow.com/questions/13469566/polygons-nicely-cropping-ggplot2-ggmap-at-different-zoom-levels)

**Projections**

[World map projections](http://mapsanddirections.us/projections.htm)

[A really big bunch of projections (in d3.js) ](https://npm.runkit.com/d3-geo-projection)

**plotGoogleMaps - plot in dynamic (zoomable) Google maps**

[http://cran.r-project.org/web/packages/plotGoogleMaps/vignettes/plotGoogleMaps-intro.pdf](http://cran.r-project.org/web/packages/plotGoogleMaps/vignettes/plotGoogleMaps-intro.pdf)

[http://gis.stackexchange.com/questions/123816/legend-and-coloring-of-markers-with-plotgooglemaps-in-r](http://gis.stackexchange.com/questions/123816/legend-and-coloring-of-markers-with-plotgooglemaps-in-r)

[http://r-sig-geo.2731867.n2.nabble.com/Re-plotGoogleMaps-no-colours-td7583530.html](http://r-sig-geo.2731867.n2.nabble.com/Re-plotGoogleMaps-no-colours-td7583530.html)


## R for aquatic/environmental/ecological science {#r-for-aquatic-environmental-ecological-science}

======================================================

**CRAN Task View: Analysis of Ecological and Environmental Data**

[http://cran.r-project.org/web/views/Environmetrics.html](http://cran.r-project.org/web/views/Environmetrics.html)

**AquaEnv (toolbox for aquatic chemical model generation focused on (ocean) acidification and CO2 air-water exchange):**

[https://r-forge.r-project.org/R/?group_id=284](https://r-forge.r-project.org/R/?group_id=284)

**OCE - a package for oceanographers**

- includes **tidem()** for harmonic analysis, **read.ctd()** for reading CTD in different formats (Seabird, WOCE, ODF, ODV), and **ctdTrim() **for locating the descent phase, and trimming data recovered before and after

[http://dankelley.github.io/oce/](http://dankelley.github.io/oce/)

[http://cran.r-project.org/web/packages/oce/](http://cran.r-project.org/web/packages/oce/)

Shiny script for trimming CTD files

[http://www.r-bloggers.com/trimming-ctd-files-with-shiny/](http://www.r-bloggers.com/trimming-ctd-files-with-shiny/)

**Pastecs - package for analysis of ecological space-time data series**

In particular for **marine plankton/benthic biology**

[http://cran.r-project.org/web/packages/pastecs/index.html](http://cran.r-project.org/web/packages/pastecs/index.html)

**Marelac - Tools for Aquatic Sciences**

contains among others: (1) chemical and physical constants and datasets, (2) conversion factors (e.g. gram to mol to liter, barometric units, temperature, salinity); (3) physical functions, (4) thermophysical properties of the seawater

[CRAN site](https://cran.r-project.org/web/packages/marelac/index.html)** - **[vignette](http://cran.r-project.org/web/packages/marelac/vignettes/marelac.pdf)


```
# Finding the solubility of oxygen 
library(marelac)
x <- gas_O2sat(t = 8) # Saturation of O2 at 8 degrees C
x                                # in mg/L  (9.43)
x*1000/molweight("O2")           # in mmol/m3 (294.8)
x*1000/molweight("O2")*0.022391  # in ml/m3 (6.60) - see ICES below
x*1000*07                        # in ml/m3 (6.60) - see ICES below
```


NOTE: 

[ICES constants for conversion of oxygen concentration](http://www.ices.dk/marine-data/tools/Pages/Unit-conversions.aspx) and [the HELCOM guide](http://www.helcom.fi/Documents/Action%20areas/Monitoring%20and%20assessment/Manuals%20and%20Guidelines/Manual%20for%20Marine%20Monitoring%20in%20the%20COMBINE%20Programme%20of%20HELCOM_PartB_AnnexB8_Appendix3.pdf)

[ICES calculator](https://ocean.ices.dk/Tools/Calculator.aspx) 

**rLakeAnalyzer - analysis of lake physics (lake number, Schmidt index etc.)**

[http://cran.r-project.org/web/packages/rLakeAnalyzer/](http://cran.r-project.org/web/packages/rLakeAnalyzer/)

**Hydro1K - hydrologically correct DEMs along with ancillary data sets**

[https://lta.cr.usgs.gov/HYDRO1K](https://lta.cr.usgs.gov/HYDRO1K)

[http://rpubs.com/Roilan/atm_data](http://rpubs.com/Roilan/atm_data)

**Simecol - object-oriented framework for ecological modelling \
(example: an individual-based model of Daphnia)**

[http://cran.r-project.org/web/packages/simecol/vignettes/a-simecol-introduction.pdf](http://cran.r-project.org/web/packages/simecol/vignettes/a-simecol-introduction.pdf)

**enaR - Ecological Network Analysis (for trophic networks and the like)**

[http://cran.r-project.org/web/packages/enaR/vignettes/enaR.pdf](http://cran.r-project.org/web/packages/enaR/vignettes/enaR.pdf)

**Cheddar: Analysis and visualisation of ecological communities**

[http://cran.r-project.org/web/packages/cheddar/](http://cran.r-project.org/web/packages/cheddar/)

**Also see [R tips and tricks 4 - web and interactive](http://drive.google.com/open?id=1PByB6pJydkomfaafqSTbpIgbtyY-Uw_YWOWzUK30jLI)**

And finally

[4 Common Reasons You Can’t Focus On Your Work (And How To Destroy Each One)](https://blog.trello.com/why-you-cant-focus-on-anything-plus-how-to-fix-it?utm_source=newsletter&utm_medium=email&utm_campaign=trello-dec2018_newsletter1) 


<!-- Docs to Markdown version 1.0β17 -->
