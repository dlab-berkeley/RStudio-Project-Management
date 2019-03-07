# RStudio-Project-Management
This workshop was presented to the UC Berkeley D-Lab Digital Humanities Working Group on March 7, 2019 as an overview of data science tools and keeping them organized using RStudio Projects. 

## Resources
While comprehensive, this list of resources is far from exhaustive. There are many programs available to help manage your Themes, Teams, Tools, and Timelines in terms of your: 

- Research Design

- Data Methods and Tools

- Document Preparation

- Presentation

- Organization, and

- Preparation

## Research Design
Before all of the tech stuff, it usually helps to get your project off the ground by flexing your domain expertise. Don't skip the design basics! 

[Research question:](http://guides.lib.berkeley.edu/c.php?g=63246) learn how to ask a guided research question. 

[Literature review:](http://guides.lib.berkeley.edu/Energy/lit-review) learn how to conduct a literature review. 

[Hypotheses:](https://undsci.berkeley.edu/article/howscienceworks_19) learn about hypotheses in scientific research. 

[Statistical framework:](https://www.khanacademy.org/math/statistics-probability/designing-studies)

[fread:](https://www.r-bloggers.com/getting-data-from-an-online-source/) a favorite function from the "data.table" package for quickly importing data into your R session from the web - or otherwise. 

## Data Methods and Tools
Be sure to also consider data methods and tools in the design of your research - this can save you time, energy, and stress as your results and discussion depend on your broader research framework. 

[Importation:](https://www.datacamp.com/community/tutorials/r-data-import-tutorial) learn how to import data using R. 

[Preprocessing:](https://cran.r-project.org/doc/contrib/de_Jonge+van_der_Loo-Introduction_to_data_cleaning_with_R.pdf) learn about data preparation with R. 

[Visualization:](https://r4ds.had.co.nz/data-visualisation.html) learn about data visualization in R. 

[Statistics:](https://cran.r-project.org/web/packages/IPSUR/vignettes/IPSUR.pdf) excellent introduction to the quantitative side of things in R. 

[Inferential Thinking (Python Data8 textbook): ](https://www.inferentialthinking.com/chapters/intro.html) excellent introduction to the quantitative side of things in Python. 

[MS Excel:](https://support.office.com/en-us/article/excel-for-windows-training-9bc05390-e94c-46af-a5b3-d7c22f6990bb) Microsoft brand spreadsheet program. 

[Qualtrics:](https://www.ndsu.edu/gdc/wp-content/pdf/qualtrics-step-by-step-manual.pdf) subscription-based software for data collection and analysis; especially good for surveys!

[OpenRefine:](http://openrefine.org/documentation.html) open source data preparation and transformation. 

## Document Preparation
Use markdown to produce vibrant documents to help you rock your next presentation or publication! 

[Markdown](https://www.markdownguide.org/) a language for plain text formatting. 

[RMarkdown (.Rmd):](https://rmarkdown.rstudio.com/lesson-1.html) R-specific brand of markdown language.

[.html:](https://html.com/) markup language used to create Internet stuff. 

[.docx:](https://edu.gcfglobal.org/en/word2016/) Microsoft file format for preparing text. 

[.pdf:](https://helpx.adobe.com/acrobat/tutorials.html) Adobe file format for document preparation. 

## Presentation
Ensure that your presentation skills are up to speed to secure that next round of funding or wow potential employers and find the job of your dreams. 
[Ten rules for structuring papers:](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005619) a short paper that outlines the critical steps you must consider in your scientific writing; rubric included! 

[MS Powerpoint:](https://business.tutsplus.com/tutorials/how-to-learn-powerpoint--cms-29884) fantastic way to make slideshow presentations! 

[Omeka:](https://omeka.org/) super fun online open-source management system for digital collections. 

[Slideshows:](https://yintingchou.com/posts/ioslides-vs-slidify-in-r-markdown-presentation/) as fun as creating MS PowerPoint slides can be, you should at some point learn to use R code in a way to directly create slideshows such as ioslides and Slidify. 

[Shiny:](https://shiny.rstudio.com/articles/basics.html) awesome way to build apps and widgets using R code. 

## Organization
Stay organized! Keep track of your whos, whats, wheres, whens, whys (and especially hows). 

[Box:](https://bconnected.berkeley.edu/collaboration-services/box) a great way to backup your stuff online. 

[Dropbox:](https://www.lynda.com/Dropbox-training-tutorials/1697-0.html) another great way to back your stuff up online. 

[Google Drive:](https://gsuite.google.com/learning-center/products/drive/get-started/#!/) yet another great way to store your stuff online (notice a trend here?). 

[G Suite:](https://gsuite.google.com/learning-center/#!/) compiles many "traditional" proprietary programs into a single suite: word processing, spreadsheets, slideshow presentations, drive storage, calendaring, etc. 

[Asana:](https://asana.com/guide) web-based platform for team based management. 

## Collaboration
Don't forget to share your stuff! Whether your project is public or private, make sure you are tracking your organization. 

[RStudio Projects](https://support.rstudio.com/hc/en-us/articles/200526207-Using-Projects) and [Software Carpentry intro:](https://swcarpentry.github.io/r-novice-gapminder/02-project-intro/) RStudio projects are the file type (.Rproj) that allows you to do all of this! 

[Dependency management:](https://rstudio.github.io/packrat/) packrat allows you to keep all your versions configured correctly. 

[GitHub:](https://guides.github.com/) the premier open-source solution for tracking and sharing code. 

[ssh:](https://happygitwithr.com/ssh-keys.html) secure shell; standard secure way for for connecting computers through the command line. 

[Jupyter Notebooks:](https://realpython.com/jupyter-notebook-introduction/) go-to computational environment for Python programmers. 

## Virtual Machines
Do you need to run a particular version of a program? Learn more about: 

[Academic Environments on Demand:](http://research-it.berkeley.edu/services/analytics-environments-demand) "Researchers need easy access to analytic computing environments that are designed to fit their needs. BRC's Analytics Environments on-Demand (AEoD) service is designed for researchers who need to run analytic software packages (such as ArcGIS, Stata, SPSS, R Studio, etc.) on a platform that is scaled up from a standard laptop or workstation, in a Windows-based environment."

[Virtual Box](https://www.virtualbox.org/) open source virtual machine for home or enterprise use. 

## Containers 
You might also need to package these version configurations as reproducible environments along with your data and code as "containers". 

What is a container? "A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings". Check out: 

[Docker:](https://www.docker.com/resources/what-container) learn to package your program/application with all the essential dependencies. 

[Kubernetes](https://kubernetes.io/): Google container service. 

[Medium freeCodeCamp intro to Docker, VMs, and Containers:](https://medium.freecodecamp.org/comprehensive-introductory-guide-to-docker-vms-and-containers-4e42a13ee103) excellent resource for learning the basics of containers and virtual machines. 

## High Performance Computing
Click the links below to learn more about accessing greater compute power, memory, and storage: 

Benten GPU server - no public link...(yet?). 

[Savio](http://research-it.berkeley.edu/services/high-performance-computing/user-guide/savio-user-guide) UC Berkeley condo cluster maintained by Research IT. 
[XSEDE:](http://research-it.berkeley.edu/services/high-performance-computing/user-guide/savio-user-guide) NSF-funded supercomputer; best of the best?

[Bridges:](http://research-it.berkeley.edu/services/high-performance-computing/user-guide/savio-user-guide) seeks to bring supercomputing to those unfamiliar with it; accessible through [XSEDE User Portal](https://portal.xsede.org/#/guest).

[Jetstream](https://jetstream-cloud.org/) easily deploy virtual machines on cloud-based, on-demand systems.

## Other Resources
Take your programming to the next level! 

[Make files:](https://opensource.com/article/18/8/what-how-makefile) run and compile programs automatically to ensure your entire repository stays updated! 

[Travis CI:](https://travis-ci.org/) sync GitHub code for testing. 

[Bash:](https://guide.bash.academy/) an essential programming language for all programmers (even if you do not even know what it is yet - you will eventually!).

[Bookdown:](https://bookdown.org/baydap/bookdownplus/) learn to convert your R work to digital book formats. 

[R package tutorial:](https://support.rstudio.com/hc/en-us/articles/200486488-Developing-Packages-with-RStudio) learn how to bundle your code and share. 

[Pkgdown:](https://pkgdown.r-lib.org/) build websites for your packages!

[Overleaf (LaTeX):](https://www.overleaf.com/learn/latex/Tutorials) web-based LaTeX editor.

[Computer Information Systems:](https://en.wikibooks.org/wiki/Introduction_to_Computer_Information_Systems/System_Software) familiarize yourself with systems software. 

[Securing your computing environment:](https://nces.ed.gov/pubs2003/secureweb/ch_6.asp) although a little dated, this guide still covers many topics relevant today in simple language. 

