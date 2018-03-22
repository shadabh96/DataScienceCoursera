# Course 1: The Data Scientist’s Toolbox

Instructor: http://jtleek.com/
Course: https://class.coursera.org/datascitoolbox-004/lecture
Forum: https://class.coursera.org/datascitoolbox-004/forum

Focus is on getting you set up with the tools and accounts needed for the rest of the track and to give basic overview of the main ideas.

Course's two components:

1. Conceptual introduction to ideas behind turning data into _actionable_ knowledge
    1. Types of data questions
    2. Steps a data analysis
    3. Putting the science in data science
2. Practical introduction to the tools:
    1. Version control
    2. Markdown
    3. Git
    4. Github
    5. R
    6. Rstudio

### Quizzes

You may attempt each quiz up to 3 times. Hight score will be counted. Each quiz is worth 20% of the grade.

* Quiz 1
    * Due: Sun 8 Jun 2014 4:30 PM PDT 
* Quiz 2
    * Due: Sun 15 Jun 2014 4:30 PM PDT
* Quiz 3
    * Due: Sun 22 Jun 2014 4:30 PM PDT

### Course project

* Worth 40% of the final grade.
* Course Project: setting up accounts
    * This assignment is designed to make sure you have done the basic software setup that will get you through the rest of the Data Science Specialization. Each component will be evaluated on a yes/no basis by your peers with 10 points assigned for each yes answer.
    * Part 1
        * Install R
        * Install Rstudio
        * Open Rstudio and take a screenshot
        * Submit a screenshot of Rstudio open on your screen.
    * Part 2
        * Set up a Github account (you may use your own name or a pseudonym).
        * Create a repo called datasciencecoursera
        * Submit the link to your Github account
    * Part 3
        * Create a text file called HelloWorld.md
        * Add the line "## This is a markdown file" to the document
        * Push the document to the datasciencecoursera repo you created on Github
        * Submit the link to the HelloWorld.md file on your Github repo.
    * Part 4
    * Fork the data sharing repository here: https://github.com/jtleek/datasharing
    * Submit the link to the forked repository on your Github account. 
* Due on Sun 22 Jun 4:30 pm
* You also have to evaluate at least four other peers projects



## Course Content

* Week1
    * Series motivation
        * Questions come first, then data to answer them
        * Data deluge
        * Statistical data science
        * Statistics is the science of learning from data.
        * Heritage Health Prize
        * R is the most commonly used language for data science. It has some great packages.
    * The data scientist's toolbox
        * Brief tour of the tools
        * R programming is the main workhorse.
        * Rstudio is the IDE to use for R
        * R programs are written in text files with .R extension
        * Markdown in .md files to generate documents
        * Git and Github
    * Getting Help
        * Use the forum for peer help
        * Google for answers
        * Accessing help in R
            * Access help file: ?rnorm
            * Search help files: help.search(“rnorm”)
            * Get arguments: args(“rnorm”)
            * Just type the function name without parenthesis to get the code corresponding to the function 
            * R reference card: [http://cran.r-project.org/contrib/Short-refcard.pdf](http://cran.r-project.org/doc/contrib/Short-refcard.pdf) 
        * Be precise when asking a question. Be specific in the title of the question.
    * Finding Answers
        * Use tag [r] as a tag in Stackoverflow for R questions
        * Use CrossValidated for more general questions
    * R programming overview
        * Some of the packages that are used for practical machine learning
            * [cran.r-project.org/web/packages/gbm/index.html](http://cran.r-project.org/web/packages/gbm/index.html)
            * http://cran.r-project.org/web/packages/caret/index.html
    * Getting and cleaning data overview 
    * Exploratory data analysis overview
    * Reproducible research overview
    * Statistical Inference overview
    * Regression Models overview
    * Practical Machine Learning overview
    * Building Data Products overview
    * Installing Outside Software on Mac OS (**Watch**)
    * Install R on Mac
        * For Mac Mavericks: http://cran.r-project.org/bin/macosx/R-3.1.0-mavericks.pkg
        * For Mac Snow Leopard and Lion: http://cran.r-project.org/bin/macosx/R-3.1.0-snowleopard.pkg
    * Install R on Windows (**Watch**)
    * Installing Rstudio
        * Install R first
        * Install from: [http://www.rstudio.com/products/rstudio/download/](http://www.rstudio.com/)
        * Mac OS download link: http://download1.rstudio.org/RStudio-0.98.507.dmg
* Week 2
    * Tips from Coursera courses
    * Command Line Interface(CLI)
        * Terminal for Mac/Linux
        * Navigate to folders, create files, folders, ...etc
        * Directories tree
        * **pwd** to print path of current working directory
        * **clear** to clear commands in the CLI window
        * **ls** to list files. -a flag to show hidden files. -l to list details of every file.
        * **cd** to change directory.With no arguments, it takes you to home directory. cd .. to go up the tree.
        * **mkdir** to create a new directory.
        * **touch** creates an empty file.
        * **cp** to copy files. Use -r flag for recursive copy of one directory contents to another.
        * **rm** to remove a file. Use -r to remove the entire directory contents.
        * **mv** to move files.
        * **date** to print the date
        * **echo** to print a message
    * Introduction to Git
        * Git Tutorial: http://www.git-tower.com/learn/ebook/command-line/introduction
        * Version control to track changes to files
        * Git is free and open source distributed version control system
        * Download Git on Mac:
            * Git 1.8: https://code.google.com/p/git-osx-installer/
            * Git 1.9: [http://sourceforge.net/projects/git-osx-installer/files/git-1.9.2-intel-universal-snow-leopard.dmg/download?use_mirror=autoselect](http://git-scm.com/download/mac)
        * Configure name and email using 'git config'
    * Introduction to Github
        * Hosting service for source code
        * Uses Git for source control
        * Allows users to push and pull changes and to collaborate with others
        * You can use it as a backup for your local repository
        * Set up a Github account using [github.com](http://github.com/)
        * Build a Github Profile
    * Creating a Github Repository
        * Two ways:
            * Create one from scratch
            * Fork another user's repository
        * Create new repo through your profile's page on [github.com](http://github.com/)
        * Public repos are free.
        * After you create a repo on github, clone it to your local machine
            * mkdir <dir> and cd to it.
            * Initialize the local git repo with git init
            * Connect it to the remote repo using 'git remote add origin <path to the remote repo> '
            * git pull origin master
        * For another user's repo using the “Fork” button on [github.com](http://github.com/)
        * git clone <remote report path> to clone a remote repo locally
    * Basic Git Commands
        * Pushing and pulling 
        * [Image: https://quip.com/-/blob/JYVAAAVAPyr/olgwUQVLlIu349spxmFK0Q]
        * Adding files:
            * git add . # Adds all new files
            * git add -u # Updates tracking for files that changed names or were deleted
            * git add -A # Does both of the previous
            * You add files before committing
        * Committing:
            * git commit -m “message” # This only updates your local repo, not the remote repo on github
        * Push saved local commits to the remote repo on github:
            * git push
        * Branches
            * git checkout -b branchname # creates a new branch
            * git branch # tells you name of your current branch
            * git checkout master # switches back to master branch
    * Basic Markdown
        * Extension is .md
        * Headings
            * ## secondary heading
            * ### tertiary heading
        * Unordered list
            * Start list items with *
    * Installing R packages
        * a ← available.pcakges() # gets list of all available packages
        * To install a package, install.packages(packageName) # put package in quotes
        * To install multiple packages, pass a vector to install.packages()
        * Or in Rstudio, Tools→Install Packages
        * To load a package, use library() function  # Do **not** put the package name in quotes
    * Installing R tools (for Windows)
* Week 3
    * Types of Questions
        * Descriptive analysis
            * Goal is to describe a set of data
        * Exploratory analysis
            * Goal is to find relationships you didn't know about
            * Correlation does not imply causation
        * Inferential analysis
            * Goal is to use a relatively small sample of data to say something about a bigger population
        * Predictive analysis
            * To use the data on some objects to predict value of another object
            * If X predicts Y, it does not mean that X causes Y
        * Causal analysis
            * Goal is to find out what happens to one variable when you make another variable change
            * Usually randomized studies are required to identify causation
        * Mechanistic analysis
            * Goal is to understand the exact changes in variables that lead to changes in other variables for individual objects
    * What is data?
        * Data are values of qualitative or quantitative variables, belonging to a set of items
        * The most important thing in data science is the question.
        * Second most important thing is the data
        * Having data can't save you if you don't have a question
        * The reason behind the explosion of interest in big data is that the price and difficulty of collecting and storing data has dramatically dropped.
    * What about big data?
        * World's information is doubling every two years
    * Experimental design
        * [figshare.com](http://figshare.com/) to share scientific data
        * Formulate your question in advance
        * Statistical inference
        * Confounding
            * Confounding variable an extraneous variable in a statistical model that correlates (directly or inversely) with both the dependent variable and the independent variable. A perceived relationship between an independent variable and a dependent variable that has been misestimated due to the failure to account for a confounding factor is termed a spurious relationship, and the presence of misestimation for this reason is termed omitted-variable bias.
            * As an example, suppose that there is a statistical relationship between ice-cream consumption and number of drowning deaths for a given period. These two variables have a positive correlation with each other. An evaluator might attempt to explain this correlation by inferring a causal relationship between the two variables (either that ice-cream causes drowning, or that drowning causes ice-cream consumption). However, a more likely explanation is that the relationship between ice-cream consumption and drowning is spurious and that a third, confounding, variable (the season) influences both variables: during the summer, warmer temperatures lead to increased ice-cream consumption as well as more people swimming and thus more drowning deaths.
            * To deal with confounding:
                * If you can (and want to), fix a variable
                * If you don't fix a variable, stratify it
                * If you can't fix a variable, randomize it

