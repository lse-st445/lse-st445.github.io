# ST445 Managing and Visualizing Data


### Michaelmas Term 2017

### Instructors

* [Kenneth Benoit](mailto:k.r.benoit@lse.ac.uk), Department of Methodology.  *Office hours*: By appointment, COL 8.11
* [Milan Vojnovic](mailto:m.vojnovic@lse.ac.uk), Department of Statistics.  *Office hours*: By appointment, COL, 2.05A

### Teaching Assistant
* [Christine Yuen](mailto:L.T.Yuen@lse.ac.uk), Department of Statistics.  *Office hours*: Thursday 14:30 - 15:30, COL 5.01

### Course Information

* Lectures on Tuesdays 10:00–12:00 in CLM.2.02
* Classes on Thursdays 13:00–14:30 in TW2.4.02

No lectures or classes will take place during School Reading Week 6.

| **Week** | **Topic**                            |
|----------|--------------------------------------|
| 1        | [Introduction to Data](#week-1-introduction-to-data) |
| 2        | [The shape of data](#week-2-the-shape-of-data)                  |
| 3        | [Creating and managing databases](#week-3-creating-and-managing-databases)    |
| 4        | [Using data from the Internet](#week-4-using-data-from-the-internet)       |
| 5        | [Working with APIs](#week-5-working-with-apis)                  |
| 6        | _Reading Week_                       |
| 7        | [Exploratory data analysis](#week-7-exploratory-data-analysis)          |
| 8        | [Exploratory data analysis (cont'd)](#week-8-exploratory-data-analysis-contd) |
| 9        | [Model evaluation](#week-9-model-evaluation)                   |
| 10       | [Dimensionality reduction](#week-10-dimensionality-reduction)           |
| 11       | [Graph data visualization](#week11-graph-data-visualization)           |



### Course Description

This course will cover the principles of digital methods for storing and structuring data, including data types, relational and non-relational database design, and query languages. Students will learn to build, populate, manipulate and query databases based on datasets relevant to their fields of interest. The course will also cover workflow management for typical data transformation and cleaning projects, frequently the starting point and most time-consuming part of any data science project. This course uses a project- based learning approach towards the study of online publishing and group -based collaboration, essential ingredients of modern data science projects. The coverage of data sharing will include key skills in on-line publishing, including the elements of web design, the technical elements of web technologies and web programming, as well as the use of revision- control and group collaboration tools such as GitHub. Each student will build one or more interactive website based on content relevant to his/her domain -related interests, and will use GitHub for accessing and submitting course materials and assignments.

A core objective of this course is to provide students with a well-rounded sense of "data science literacy", meaning you will become familiar with the core structures, terms, protocols, and software that forms the core material of data science and applied computing.  This is a broad category, covering abstract concepts such as database normal forms and complex data structures, but also covers a range of simple tools and formats such as markup languages, web publishing, and working with APIs (application programming interfaces).  In the second half of the course, we will focus on communicating results visually through turning data into plots and other visualizations.

On the theory side, introduce principles and applications of the electronic storage, structuring, manipulation, transformation, extraction, and dissemination of data. This includes data types, database design, data base implementation, and data analysis through structured queries. Through joining operations, we will also cover the challenges of data linkage and how to combine datasets from different sources. We begin by discussing concepts in fundamental data types, and how data is stored and recorded electronically. We will cover database design, especially relational databases, using substantive examples across a variety of fields. Students are introduced to SQL through MySQL, and programming assignments in this unit of the course will be designed to insure that students learn to create, populate and query an SQL database.  We will briefly compare relational databases to other formats of database manager, the "NoSQL" types such as MongoDB, including the JSON data format.  Students will be encouraged to work with data relevant to their own interests as they learn to create, populate and query data.

On the practical side, we will cover a variety of tools with which every data scientist should be familiar, including revision control tools, web publishing formats, tools and commands for reshaping and recasting data, how to work with different data formats, how to merge and link data, and how to publish a website.

In the data visualisation part of the course, we will cover a variety of principles, tools, and methods for visualizing data.

For the final project, we will provide you with a dataset, which you will be expected to transform in order to produce visualizations.



### Organization

This course is an introduction to the fundamental concepts of data and data visualization for students and assumes no prior knowledge of these concepts.  

The course will involve 20 hours of lectures and 15 hours of computer workshops in the MT. 	


### Prerequisites

No prior experience with programming is required.


### Software

We will use some tools, notably SQLite, R, and Python, but these will be used in coordination with MY470 (Computer Programming) where their use will be covered more formally.  Lectures and assignments will be posted on Github, Students are expected to use Github also to submit problem sets and final exam.

Where appropriate, we will use Jupyter notebooks for lab assignments, demonstrations, and the course notes themselves.

### Assessment

Project assignment (60%) and continuous assessment in weeks 3, 6, 8, 10 (10% each). Students will be expected to produce 10 problem sets in the MT. 

### Schedule

---
#### Week 1. Introduction to Data

In the first week, we will introduce the basic concepts of the course, including how data is recorded, stored, and shared.  Because the course relies fundamentally on GitHub, a collaborative code and data sharing platform, we will introduce the use of git and GitHub, using the lab session to guide students through in setting up an account and subscribing to the course organisation and assignments.  

This week will also introduce basic data types, in a language-agnostic manner, from the perspective of machine implementations through to high-level programming languages.  We will introduce the notion of databases and database managers, and the client-server model.

*Readings*:
* Lake, P. and Crowther, P. 2013. _Concise guide to databases: A Practical Introduction_.  London: Springer-Verlag.  Chapter 1, [Data, an Organizational Asset](https://books.google.co.uk/books?id=SuK2BAAAQBAJ&pg=PA301&lpg=PA301&dq=Concise+Guide+to+Databases+pdf&source=bl&ots=pEJj8miMrf&sig=3nrRgpk3kF7fXzcWUWpJ_uzpfl0&hl=en&sa=X&ved=0ahUKEwiAkM3JrbHWAhXE7xQKHWseCZAQ6AEISzAH#v=onepage&q=Concise%20Guide%20to%20Databases%20pdf&f=false)
* Goodrich, M.T., Tamassia, R. and Goldwasser, M.H. 2013. _Data structures and algorithms in Python_. John Wiley & Sons Ltd.  Ch. 1, through section 1.3.
* Wickham, Hadley.  Nd.  _Advanced R_, 2nd ed.  Ch 1, [Introduction](https://adv-r.hadley.nz/introduction), and Chapter 2, [Data Structures](https://adv-r.hadley.nz/data-structures).
* [GitHub Guides](https://guides.github.com), especially: "Understanding the GitHub Flow", "Hello World", and "Getting Started with GitHub Pages".

*Further Readings*:
* Nelson, Meghan.  2015.  "[An Intro to Git and GitHub for Beginners (Tutorial).](http://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)"
* GitHub.  "[Markdown Syntax](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)" (a cheatsheet).  
* Chacon, Scott and Ben Straub. [_Pro Git_](https://git-scm.com/book/en/v2). 2nd ed. Apress.  Chapters 1-2.
* Jim McGlone, "[Creating and Hosting a Personal Site on GitHub
A step-by-step beginner's guide to creating a personal website and blog using Jekyll and hosting it for free using GitHub Pages.](http://jmcglone.com/guides/github-pages/)".

*Lab*: **Setting up a website using GitHub pages**, by forking a repository, staging and committing changes, and pushing these to a repository for publishing a website using Jekyll.
* Installing git and setting up an account on GitHub
* Using Jupyter notebooks on GitHub
* How to complete and submit assignments using GitHub Classroom
* Cloning a website repository, modifying it, and publishing a personal webpage


---
#### Week 2. The shape of data

This week moves beyond the rectangular format common in statistical datasets, modeled on a spreadsheet, to cover relational structures and the concept of database normalization.  We will also cover ways to restructure data from "wide" to "long" format, within strictly rectangular data structures.

*Readings*:
* Wickham, Hadley and Garett Grolemund.  2017.  _R for Data Science: Import, Tidy, Transform, Visualize, and Model Data_.  Sebastopol, CA: O'Reilly.  [Part II Wrangle](http://r4ds.had.co.nz/wrangle-intro.html), [Tibbles](http://r4ds.had.co.nz/tibbles.html), [Data Import](http://r4ds.had.co.nz/data-import.html), [Tidy Data](http://r4ds.had.co.nz/tidy-data.html) (Ch. 7-9 of the print edition).
* The [**reshape2** package](http://had.co.nz/reshape/) for R.

*Further Resources*:
* Reshaping data in Python: "[Reshaping and Pivot Tables](https://pandas.pydata.org/pandas-docs/stable/reshaping.html)".  
* Robin Linderborg, "[Reshaping Data in Python](https://hackernoon.com/reshaping-data-in-python-fa27dda2ff77)", 20 Jan 2017.

*Lab*: **Reshaping and data in R**
* Moving from wide to long data and back again, in R and Python.
* Merge and join operations.
* Using lookup and "hash" tables.
* Normalizing tables through key relations.

---

#### Week 3. Creating and managing databases

We will return to database normalization, and how to implement this using good practice in a relational database manager, SQLLite.  We will cover how to structure data, verify data types, set conditions for data integrity, and perform complex queries to extract data from the database.  We will also cover authentication and how to connect to local and remote databases.   Finally, for a comparison, we will show a different (non-relational) database model through MongoDB, contrasting this to the relational paradigm.

*Readings*:
*	Lake, Peter.  _Concise Guide to Databases: A Practical Introduction_. Springer, 2013.  Chapters 4-5, Relational Databases and NoSQL databases.
*	Nield, Thomas. _Getting Started with SQL: A hands-on approach for beginners_. O’Reilly, 2016.  Entire text.

*Further Resources*:
* [SQLite documentation](https://www.sqlite.org/docs.html).
*   Bassett, L. 2015.  [_Introduction to JavaScript Object Notation: A to-the-point Guide to JSON_](http://shop.oreilly.com/product/0636920041597.do).  O'Reilly Media, Inc.

*Lab*: **Working with a relational database manager**
* Normalizing a data structure and storing it in SQLLite
* Enforcing data integrity
* Constructing queries


---
#### Week 4. Using data from the Internet

This week covers markup languages, content style sheets, and web protocols for publishing and transmitting data.  Continuing from the material covered in the first week lab session, we will cover markup languages, including HTML, XML, and Markdown, as well as common data formats such as JSON (Javascript Object Notation).  We will cover basic web scraping, to turn web data into text or numbers.  We will also cover the client-server model, and how machines and humans transmit data over networks and to and from databases.

*Readings*:
* Shay Howe. 2015.  [_Learn to Code HTML and CSS: Develop and Style Websites_](http://learn.shayhowe.com/html-css/).  New Riders.  Chs 1-8.
* [Beautiful Soup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

*Further Resources*:

* Duckett, Jon.  _HTML and CSS: Design and Build Websites_.  New York: Wiley, 2011.
* Severance, Charles Russell.  [_Introduction to Networking: How the Internet Works_](http://www.net-intro.com).  Charles Severance, 2015.
* Vik Paruchuri, "[Python Web Scraping Tutorial using BeautifulSoup](https://www.dataquest.io/blog/web-scraping-tutorial-python/)", 17 November 2016.
* Justin Yek, "[How to scrape websites with Python and BeautifulSoup](https://medium.freecodecamp.org/how-to-scrape-websites-with-python-and-beautifulsoup-5946935d93fe)", 10 June 2017.

*Lab*: **Scraping data from the web**

---

#### Week 5. Working with APIs

Publicly accessible _application programming interfaces_ (APIs) provide a common source of "big" data available from a variety of sources, such as social media data.  This data consists of a variety of data types, but is usually transmitted in JSON format.  In this session, we will cover the basics of APIs, including authentication and the use of protocols for interacting with APIs, and in processing the data that is obtained using these methods.  We will also discuss common problems in using text, including character encodings, working with Unicode, transforming text into numeric data, and cleaning textual data for analysis.

*Readings*:
*   Cooksey, Brian.  [_An Introduction to APIs_](https://zapier.com/learn/apis/#download).  Zapier, 2014.
*   [**python-twitter** documentation](https://python-twitter.readthedocs.io/en/latest/)

*Further Resources*:
* [Documentation on the Twitter REST API](https://dev.twitter.com/rest/public)
* the [**twitteR** package for R](https://www.rdocumentation.org/packages/twitteR/versions/1.1.9)
* Richard Ishida. 2015.  "[Character encodings for beginners](https://www.w3.org/International/questions/qa-what-is-encoding)".  W3C.

*Lab*: **Working with social media data: Twitter**
* Download Twitter data using Twitter's REST APIs
* Clean and process the data
* Normalize the data and store it
* Perform basic analysis of the text and non-textual data.


---
#### Week 6. Reading Week


---
#### Week 7. Exploratory data analysis

We will introduce the basic statistical plots that are commonly used in exploratory data analysis. We will first consider standard plots for univariate data analysis, including histograms, empirical distribution functions, as well as plots of summary statistics such as boxplots. We will then consider different variants of bar plots, which are commonly used for comparison of parallel batches of data.

*Readings*:
* M. Friendly, [A Brief History of Data Visualization](http://www.datavis.ca/papers/hbook.pdf), Handbook of Computational Statistics: Data Visualization (Editors C. Chen, W. Hardle and A. Unwin), Vol III, Springer-Verlag, 2006  
* E. R. Tufte, The Visual Display of Quantitative Information, Second Edition, Graphics Press, 2001
* J. W. Tukey, Exploratory Data Analysis, Pearson, 1977
* [Matplotlib](https://matplotlib.org)
* [Seaborn: statistical data visualization](https://seaborn.pydata.org)

*Lab*: **Matplotlib primer and basic statistical plots**
* Plotting using Matplotlib, dataframe and datastream APIs
* Customizing style, axes labels, ticks, and scale
*  Histogram, boxplots and their variants
* Bar plots, horizontal, vertical and stacked

---
#### Week 8. Exploratory data analysis (cont'd)

We will continue our consideration of data visualizations for exploratory data analysis by examining various other statistical plots, primarily focusing to multivariate data analysis and time series data. We will consider the use of scatter plots and heatmaps.  

*Readings*:
* K. Dale, Data Visualization with Python & JavaScript, O'Reilly, 2016
* H. Wickham, ggplot2: Elegant Graphics for Data Analysis, Second Edition, Springer, 2016
* S. Few, Show Me the Numbers: Designing Tables and Graphs to Enlighten, Second Edition, Analytics Press, 2012
* L. Wilkinson and M. Friendly, [History Corner: The History of the Cluster Heat Map](https://www.cs.uic.edu/~wilkinson/Publications/heatmap.pdf), The American Statistician, Vol 63, No 2, May 2009

*Lab*: **Statistical plots using Matplotlib and Seaborn**
* Scatterplot and scatterplot matrix
* Matrix reordering, clustering and bi-clustering
* Time series plotting, autocorrelation plot

---
#### Week 9. Model evaluation

In this week, we will introduce standard statistical plots for the performance evaluation of statistical models and machine learning algorithms for classification. We will introduce standard statistical plots for assessing the performance of binary classifiers, such as receiver operating characteristic (ROC) and precision-recall (PR) curves. We will learn how to interpret these plots and discuss their advantages and limitations.  

We will also discuss various standard metrics used for assessing the performance of binary classifiers, such as accuracy, area under the curve (AUC) and Gini coefficient, discuss their relation to the ROC curve, as well as their advantages and limitations.


*Readings*:
* J. A. Sweets, R. M. Dawes and J. Monahan, [Better Decisions through Science](http://ist-socrates.berkeley.edu/~maccoun/LP_SwetsDawesMonahan2000.pdf), Scientific American, October 2000, pp 82-87
* T. Fawcet, An Introduction to ROC Analysis, Pattern recognition letters, Vol 27, pp 861-874, 2006
* N. Japkowicz and M. Shah, Evaluating Learning Algorithms: A Classification Perspective, Cambridge University Press, 2011
* API reference: [sklearn.metrics](http://scikit-learn.org/stable/modules/classes.html#sklearn-metrics-metrics)


*Lab*: **Evaluating classifiers using sklearn.metrics**
* Comparing binary classifiers in ROC and PR space
* Comparison of ROC and PR curves
* Accuracy, AUC and other metrics

---
#### Week 10. Dimensionality reduction

We will consider how to visualize hidden structures in a high-dimensional data, such as hidden clusters or low-dimensional manifolds, by using dimensionality reduction methods. We will explain the underlying principles of dimensionality reduction methods such as multidimensional scaling, locally linear embedding, isomap, spectral embedding, and stochastic neighbor embedding. We will see how geometry, linear algebra and optimisation methods give raise to different dimensionality reduction methods.

Our focus will be on the dimensionality methods that are commonly used in practice and widely available through software libraries such as sklearn.manifold. We will also consider modern applications for visualizing different dimensionality reductions such as Google embedding projector.


*Readings*:
* T. F. Cox and M. A. A. Cox, Multidimensional Scaling, Second Edition, Chapman & Hall / CRC, 2000
* I. Borg and P. J. F. Groenen, Modern Multidimensional Scaling: Theory and Applications, Second Edition, Springer, 2005
* A. Geron, Hands-on Machine Learning with Scikit-Learn & TensorFlow, O’Reilly, 2017, Chapter 8, Dimensionality Reduction
* Google's [embedding projector](http://projector.tensorflow.org)
* API reference, [scikit learn, Section 2.2: manifold learning](http://scikit-learn.org/stable/modules/manifold.html)

*Lab*: **Dimensionality reduction using sklearn.manifold**
* Dimensionality reduction plots using different methods
* Understanding the meaning of various input parameters
* Understanding the sensitivity to the input parameter values

---
#### Week 11. Graph data visualization

In the last week, we will consider the basic methods for visualization of graph data such as visualizing social network relationships. We will consider different graph layouts and the principles of how they are computed. This will involve methods based on simple principles for drawing graphs that have a tree structure as well as more sophisticated methods based on spectral theory of linear algebra and dynamical systems for general graphs.

*Readings*:
* A. Hagberg, D. Schult and P. Swart, [NetworkX Reference]( https://networkx.github.io/documentation/latest/_downloads/networkx_reference.pdf)
* NetworkX: Software for complex networks, [https://networkx.github.io/](https://networkx.github.io/)
* [Graphviz – Graph Visualisation Software](http://graphviz.org/), especially manual pages, layout commands


*Lab*: **Graph drawing using NetworkX**
* Loading and manipulating graphs using NetworkX
* Changing basic properties of graph visualization such as node or edge colors
* Drawing graphs using different layouts
* Using graphviz graph layouts
