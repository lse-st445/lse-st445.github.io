---
papersize: a4
documentclass: scrartcl
classoption: DIV=14
colorlinks: true
---

![LSE](images/lse-logo.jpg)
# ST445 Managing and Visualizing Data

### Michaelmas Term 2018

### Instructors

* [Steve Bell](mailto:s.c.bell@lse.ac.uk), Department of Statistics.  *Office hours*: Mondays 16-17:00, Thursdays 11-12:00, COL.8.11

### Teaching Assistant
* [Simon Scholler](mailto:L.T.Yuen@lse.ac.uk), Department of Statistics.  *Office hours*: Monday 15:00 - 16:00, COL 5.03 (from week 2, computer workshop related questions only)

### Course Information

* Lectures on Mondays 10:00–12:00 in OLD.4.10
* Classes on Wednesdays 09:00–10:30 in STC.S08

No lectures or classes will take place during School Reading Week 6.

| **Week** | **Topic**                            | **Week** | **Topic**      |
|:----------:|:--------------------------------------|:----:|:----|
| 1        | [Introduction to Data](#week-1-introduction-to-data) | 7        | [Exploratory data analysis](#week-7-exploratory-data-analysis)          |
| 2        | [Python and NumPy Data Structures](#week-2-python-and-numpy-data-structures)                  | 8        | [Exploratory data analysis (cont'd)](#week-8-exploratory-data-analysis-contd) |
| 3        | [Wrangling Data with Pandas](#week-3-wrangling-data-with-pandas)    | 9        | [Model evaluation](#week-9-model-evaluation)                   |
| 4        | [Creating and Managing Databases](#week-4-creating-and-managing-databases)       | 10       | [Dimensionality reduction](#week-10-dimensionality-reduction)           |
| 5        | [Collecting Data from the Internet](#week-5-collecting-data-from-the-internet)                  |  11       | [Graph data visualization](#week11-graph-data-visualization)           |
| 6        | _Reading Week_                       |



### Course Description

This course will cover the principles of digital methods for storing and structuring data, including data types, relational and non-relational database design, and query languages. Students will learn to build, populate, manipulate and query databases based on datasets relevant to their fields of interest. The course will also cover workflow management for typical data transformation and cleaning projects, frequently the starting point and most time-consuming part of any data science project. This course uses a project-based learning approach towards the study of online publishing and group -based collaboration, essential ingredients of modern data science projects. The coverage of data sharing will include key skills in on-line publishing, including the elements of web design, the technical elements of web technologies and web programming, as well as the use of revision- control and group collaboration tools such as GitHub. Each student will build one or more interactive website based on content relevant to his/her domain -related interests, and will use GitHub for accessing and submitting course materials and assignments.

A core objective of this course is to provide students with a well-rounded sense of "data science literacy", meaning you will become familiar with the core structures, terms, protocols, and software that forms the core material of data science and applied computing.  This is a broad category, covering abstract concepts such as database normal forms and complex data structures, but also covers a range of simple tools and formats such as markup languages, web publishing, and working with APIs (application programming interfaces).  In the second half of the course, we will focus on communicating results visually through turning data into plots and other visualizations.

On the theory side, introduce principles and applications of the electronic storage, structuring, manipulation, transformation, extraction, and dissemination of data. This includes data types, database design, data base implementation, and data analysis through structured queries. Through joining operations, we will also cover the challenges of data linkage and how to combine datasets from different sources. We begin by discussing concepts in fundamental data types, and how data is stored and recorded electronically. We will cover database design, especially relational databases, using substantive examples across a variety of fields. Students are introduced to SQL through SQLite, and programming assignments in this unit of the course will be designed to insure that students learn to create, populate and query an SQL database.  We will briefly compare relational databases to other formats of database manager, the "NoSQL" types such as MongoDB, including the JSON data format.  Students will be encouraged to work with data relevant to their own interests as they learn to create, populate and query data.

On the practical side, we will cover a variety of tools with which every data scientist should be familiar, including revision control, web publishing formats, tools and commands for reshaping and recasting data, how to work with different data formats, how to merge and link data, and how to publish a website.

In the data visualisation part of the course, we will cover a variety of principles, tools, and methods for visualizing data.

For the final project, we will provide you with a dataset, which you will be expected to transform in order to produce visualizations.



### Organization

This course is an introduction to the fundamental concepts of data and data visualization for students and assumes no prior knowledge of these concepts.

The course will involve 20 hours of lectures and 15 hours of computer workshops in the MT.

### Prerequisites

No prior experience with programming is required.

### Software

We will use some tools, notably SQLite and Python, but these will be used in coordination with MY470 (Computer Programming) where their use will be covered more formally.  Lectures and assignments will be posted on Github, Students are expected to use Github also to submit problem sets and final exam.

Where appropriate, we will use Jupyter notebooks for lab assignments, demonstrations, and the course notes themselves.

### Assessment

Project assignment (60%) and continuous assessment in weeks 3, 6, 8, 10 (10% each). Students will be expected to produce 10 problem sets in the MT.

### Schedule

------
#### Week 1. [Introduction to Data](https://github.com/lse-st445/lectures/blob/master/week01/ST445_wk1_lecture.ipynb)

In the first week, we will introduce the basic concepts of the course, including how data is recorded, stored, and shared.  Because the course relies fundamentally on GitHub, a collaborative code and data sharing platform, we will introduce the use of git and GitHub, using the lab session to guide students through in setting up an account and subscribing to the course organisation and assignments.

This week will also introduce basic data types, in a language-agnostic manner, from the perspective of machine implementations through to high-level programming languages. A short historical perspective to data science will be given.Issues concerning data integrity will be discussed. The process flow of capturing, wrangling, exploring and visualising data will be emphasised. We will introduce the notion of databases and database managers.

*Lecture Notes*:
* [Administrative overview of the course](https://github.com/lse-st445/lectures/blob/master/week01/ST445_wk1_admin.ipynb) (see also [pdf version](https://nbviewer.jupyter.org/github/lse-st445/lectures/blob/master/week01/ST445_wk1_admin_slides.pdf))
* [Lecture, Week 1](https://github.com/lse-st445/lectures/blob/master/week01/ST445_wk1_lecture.ipynb) (see also [pdf version](https://nbviewer.jupyter.org/github/lse-st445/lectures/blob/master/week01/ST445_wk1_lecture_slides.pdf))
* [Python example to fix](https://github.com/lse-st445/lectures/blob/master/week01/Python_example.ipynb)


*Readings*:
* Lake, P. and Crowther, P. 2013. _Concise guide to databases: A Practical Introduction_.  London: Springer-Verlag.  Chapter 1, [Data, an Organizational Asset](https://books.google.co.uk/books?id=SuK2BAAAQBAJ&pg=PA301&lpg=PA301&dq=Concise+Guide+to+Databases+pdf&source=bl&ots=pEJj8miMrf&sig=3nrRgpk3kF7fXzcWUWpJ_uzpfl0&hl=en&sa=X&ved=0ahUKEwiAkM3JrbHWAhXE7xQKHWseCZAQ6AEISzAH#v=onepage&q=Concise%20Guide%20to%20Databases%20pdf&f=false)
* Goodrich, M.T., Tamassia, R. and Goldwasser, M.H. 2013. _Data structures and algorithms in Python_. John Wiley & Sons Ltd.  Ch. 1, through section 1.3.
* Wickham, Hadley.  Nd.  _Advanced R_, 2nd ed.  Ch 1, [Introduction](https://adv-r.hadley.nz/introduction), and Chapter 2, [Data Structures](https://adv-r.hadley.nz/data-structures).
* [GitHub Guides](https://guides.github.com), especially: "Understanding the GitHub Flow", "Hello World", and "Getting Started with GitHub Pages".

*Further Readings*:
* "[Understanding Big and Little Endian Byte Order](https://betterexplained.com/articles/understanding-big-and-little-endian-byte-order/)".  _Better Explained_ website.
* Nelson, Meghan.  2015.  "[An Intro to Git and GitHub for Beginners (Tutorial).](http://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)"
* GitHub.  "[Markdown Syntax](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)" (a cheatsheet).
* Chacon, Scott and Ben Straub. [_Pro Git_](https://git-scm.com/book/en/v2). 2nd ed. Apress.  Chapters 1-2.
* Jim McGlone, "[Creating and Hosting a Personal Site on GitHub
A step-by-step beginner's guide to creating a personal website and blog using Jekyll and hosting it for free using GitHub Pages.](http://jmcglone.com/guides/github-pages/)".

*Lab*: [**Working with git and GitHub**](https://github.com/lse-st445/lectures/blob/master/week01/ST445_wk1_class.md).
* Installing git and setting up an account on GitHub
* How to complete and submit assignments using GitHub Classroom
* Forking and correcting a broken Jupyter notebook
* Cloning a website repository, modifying it, and publishing a personal webpage


------
#### Week 2. [Python and NumPy Data Structures](https://github.com/lse-st445/lectures/blob/master/week02/ST445_wk2_lecture.ipynb)

Firtly, we shall review fundamental Python datatypes such as lists and dicts. Then we shall introduce Numerical Python or NumPy which is the module on which Pandas is built. NumPy permits fast array based computation and is the basis for efficient pre-processing and visualisation of data. Many of the built-in NumPy methods can be used in Exploratory Data Analysis (EDA). We will also cover ways to restructure data from "wide" to "long" format, within strictly rectangular data structures.  Additional topics concerning text encoding, date formats, and sparse matrix formats are also covered.

*Readings*:
* [NumPy Documentation](https://www.numpy.org)
* Wickham, Hadley and Garett Grolemund.  2017.  _R for Data Science: Import, Tidy, Transform, Visualize, and Model Data_.  Sebastopol, CA: O'Reilly.  [Part II Wrangle](http://r4ds.had.co.nz/wrangle-intro.html), [Tibbles](http://r4ds.had.co.nz/tibbles.html), [Data Import](http://r4ds.had.co.nz/data-import.html), [Tidy Data](http://r4ds.had.co.nz/tidy-data.html) (Ch. 7-9 of the print edition).
* McKinney, Wes. 2017 (2nd Edition) _Python for Data Analysis_. Sebastopol, CA: O'Reilly

*Further Resources*:
* Reshaping data in Python: "[Reshaping and Pivot Tables](https://pandas.pydata.org/pandas-docs/stable/reshaping.html)".
* Robin Linderborg, "[Reshaping Data in Python](https://hackernoon.com/reshaping-data-in-python-fa27dda2ff77)", 20 Jan 2017.

*Lecture Notes*:
* [Lecture, Week 2](https://github.com/lse-st445/lectures/blob/master/week02/ST445_wk2_lecture.ipynb) (see also [pdf version](https://nbviewer.jupyter.org/github/lse-st445/lectures/blob/master/week02/ST445_wk2_lecture_slides.pdf))

*Lab*: [**Processing data with NumPy**](https://github.com/lse-st445/lectures/blob/master/week02/ST445_wk2_class.md)
See also:
* [Class examples in Python](https://github.com/lse-st445/lectures/blob/master/week02/ST445_wk2_python_reshaping.ipynb)

------

#### Week 3. [Wrangling Data with Pandas](https://github.com/lse-st445/lectures/blob/master/week03/ST445_wk3_lecture.ipynb)

This week we shall be exploring Pandas which is one of Python's main tools. It gives Python a DataFrame similar to the other main data science language R. Pandas can handle heterogeneous data and so it extends the capability of NumPy, which is mostly suited to homogeneous numerical data. Pandas works well with other key Python modules such as scikit-learn (machine learning) and matplotlib. We will also cover common data formats such as JSON (Javascript Object Notation).  


*Readings*:
* [10 Minutes to pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html)
* McKinney, Wes. 2017 (2nd Edition) _Python for Data Analysis_. Sebastopol, CA: O'Reilly

*Lecture Notes*:
* [Lecture, Week 3](https://github.com/lse-st445/lectures/blob/master/week03/ST445_wk3_lecture.ipynb) (see also [pdf version](https://nbviewer.jupyter.org/github/lse-st445/lectures/blob/master/week03/ST445_wk3_lecture_slides.pdf))

*Lab*: [**Cleaning and Shaping data**](https://classroom.github.com/a/UJTk4weL)  

------
#### Week 4. [Creating and Managing Databases](https://github.com/lse-st445/lectures/blob/master/week04/ST445_wk4_lecture.ipynb)

We will return to database normalization, and how to implement this using good practice in a relational database manager, SQLite.  We will cover how to structure data, verify data types, set conditions for data integrity, and perform complex queries to extract data from the database.  We will also cover authentication and how to connect to local and remote databases.   Finally, for a comparison, we will show a different (non-relational) database model through MongoDB, contrasting this to the relational paradigm.This week covers markup languages, content style sheets, and web protocols for publishing and transmitting data.  Continuing from the material covered in the first week lab session, we will cover markup languages, including HTML, XML, and Markdown,  

*Readings*:
*	Lake, Peter.  _Concise Guide to Databases: A Practical Introduction_. Springer, 2013.  Chapters 4-5, Relational Databases and NoSQL databases.
*	Nield, Thomas. _Getting Started with SQL: A hands-on approach for beginners_. O’Reilly, 2016.  Entire text.
* [SQLite documentation](https://www.sqlite.org/docs.html).
*   Bassett, L. 2015.  [_Introduction to JavaScript Object Notation: A to-the-point Guide to JSON_](http://shop.oreilly.com/product/0636920041597.do).  O'Reilly Media, Inc.
* Shay Howe. 2015.  [_Learn to Code HTML and CSS: Develop and Style Websites_](http://learn.shayhowe.com/html-css/).  New Riders.  Chs 1-8.



*Lecture Notes*:
* [Lecture, Week 4](https://github.com/lse-st445/lectures/blob/master/week04/ST445_wk4_lecture.ipynb) (see also [pdf version](https://nbviewer.jupyter.org/github/lse-st445/lectures/blob/master/week04/ST445_wk4_lecture_slides.pdf))

*Lab*: [**Working with a relational database manager**](https://classroom.github.com/a/ZmAxfNMr)  
* To complete this assignment, you will edit the .ipynb file to add your answers, and submit that.
* Here are some [additional notes that build on the lecture](https://github.com/lse-st445/lectures/blob/master/week03/ST445_wk3_class.ipynb)
* Here are some [suggestions for additional resources](https://github.com/lse-st445/assignment-3-instructions/blob/master/README.md) that could help in answering Exercise 3.


------

#### Week 5. [Collecting Data from the Internet](https://github.com/lse-st445/lectures/blob/master/week05/ST445_wk5_lecture.ipynb)

Publicly accessible _application programming interfaces_ (APIs) provide a common source of "big" data available from a variety of sources, such as social media data.  This data consists of a variety of data types, but is usually transmitted in JSON format.  In this session, we will cover the basics of APIs, including authentication and the use of protocols for interacting with APIs, and in processing the data that is obtained using these methods.  We will also discuss common problems in using text, including character encodings, working with Unicode, transforming text into numeric data, and cleaning textual data for analysis.We will cover basic web scraping, to turn web data into text or numbers.

*Readings*:
*   Cooksey, Brian.  [_An Introduction to APIs_](https://zapier.com/learn/apis/#download).  Zapier, 2014.
*   [**python-twitter** documentation](https://python-twitter.readthedocs.io/en/latest/)
* Vik Paruchuri, "[Python Web Scraping Tutorial using BeautifulSoup](https://www.dataquest.io/blog/web-scraping-tutorial-python/)", 17 November 2016.
* [Beautiful Soup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
* Justin Yek, "[How to scrape websites with Python and BeautifulSoup](https://medium.freecodecamp.org/how-to-scrape-websites-with-python-and-beautifulsoup-5946935d93fe)", 10 June 2017.

*Further Resources*:
* [Documentation on the Twitter REST API](https://dev.twitter.com/rest/public)
* Richard Ishida. 2015.  "[Character encodings for beginners](https://www.w3.org/International/questions/qa-what-is-encoding)".  W3C.

*Lecture Notes*:
* [Lecture, Week 5](https://github.com/lse-st445/lectures/blob/master/week05/ST445_wk5_lecture.ipynb) (see also [pdf version](https://nbviewer.jupyter.org/github/lse-st445/lectures/blob/master/week05/ST445_wk5_lecture_slides.pdf))

*Lab*: [**Working with social media data: Twitter**](https://classroom.github.com/a/RY-6fNBv)
* Download Twitter data using Twitter's REST APIs
* Clean and process the data
* Normalize the data and store it
* Perform basic analysis of the text and non-textual data.


------
#### Week 6. Reading Week


------
#### Week 7. Exploratory data analysis

We will introduce the basic statistical plots that are commonly used in exploratory data analysis. We will first consider standard plots for univariate data analysis, including histograms, empirical distribution functions, as well as plots of summary statistics such as boxplots and violinplots. We will then consider different variants of bar plots, which are commonly used for comparison of parallel batches of data, as well as scatter plots for exploration of correlation patterns in data.

*Readings*:
* M. Friendly, [A Brief History of Data Visualization](http://www.datavis.ca/papers/hbook.pdf), Handbook of Computational Statistics: Data Visualization (Editors C. Chen, W. Hardle and A. Unwin), Vol III, Springer-Verlag, 2006
* E. R. Tufte, The Visual Display of Quantitative Information, Second Edition, Graphics Press, 2001
* J. W. Tukey, Exploratory Data Analysis, Pearson, 1977
* [Matplotlib](https://matplotlib.org)
* [Seaborn: statistical data visualization](https://seaborn.pydata.org)

*Lab*: [**Matplotlib primer and basic statistical plots**](https://classroom.github.com/a/rWCAJErU)
* Basic plotting using Matplotlib and Seaborn libraries
* GitHub archive dataset exploratory data analysis
* [Class 7 solution](https://github.com/lse-st445/lectures/blob/master/week07/st445_wk7_class.ipynb)
* [Notebook cleaning the github json data](https://github.com/lse-st445/assignment-7-instructions/blob/master/EDA-GitHub-data-cleaning.ipynb)

------
#### Week 8. Matrix data visualization

We will consider how to visualize matrix data such as covariance and other similarity matrices and adjacency matrices of graphs such as those representing social networks. The key here is to use a suitable ordering of matrix rows and columns to visualize any possibly existing clustering structure. We will explain the underlying methods based on spectral theory of matrices, using the concepts of matrix eigenvectors and clustering based on matrix eigenvectors. In particular, we will explain the method based on *seriation* using the so-called Fiedler eigenvector and *spectral co-clustering* based on using eigenvectors in combination with k-means clustering method.

*Readings*:
* L. Wilkinson and M. Friendly, [History Corner: The History of the Cluster Heat Map](https://www.cs.uic.edu/~wilkinson/Publications/heatmap.pdf), The American Statistician, Vol 63, No 2, May 2009
* I. S. Dhilon, [Co-clustering documents and words using bipartite spectral graph partitioning](http://www.cs.utexas.edu/users/inderjit/public_papers/kdd_bipartite.pdf), Proc. of ACM KDD, 2001
* Scikit-learn documentation, [Section 2.4: Biclustering](http://scikit-learn.org/stable/modules/biclustering.html)

*Lab*: [**Statistical plots using Matplotlib and Seaborn**](https://classroom.github.com/a/4h5qIjwe)
* Synthetic matrix data visualization using seriation method
* Visualization of adjacency matrices derived from GitHub archive dataset
* Using sklearn.cluster.bicluster

------
#### Week 9. Model evaluation

In this week, we will introduce standard statistical plots for the performance evaluation of statistical models and machine learning algorithms for classification. We will introduce standard statistical plots for assessing the performance of binary classifiers, such as *receiver operating characteristic* (ROC) and *precision-recall* (PR) curves. We will learn how to interpret these plots and discuss their advantages and limitations.

We will also discuss various standard metrics used for assessing the performance of binary classifiers, such as *accuracy*, *area under the curve* (AUC) and *Gini coefficient*, discuss their relation to the ROC curve, as well as their advantages and limitations.


*Readings*:
* J. A. Sweets, R. M. Dawes and J. Monahan, [Better Decisions through Science](http://ist-socrates.berkeley.edu/~maccoun/LP_SwetsDawesMonahan2000.pdf), Scientific American, October 2000, pp 82-87
* T. Fawcet, An Introduction to ROC Analysis, Pattern recognition letters, Vol 27, pp 861-874, 2006
* N. Japkowicz and M. Shah, Evaluating Learning Algorithms: A Classification Perspective, Cambridge University Press, 2011
* API reference: [sklearn.metrics](http://scikit-learn.org/stable/modules/classes.html#sklearn-metrics-metrics)


*Lab*: [**Evaluating classifiers using sklearn.metrics**](https://classroom.github.com/a/47RFfmko)
* Comparing binary classifiers in ROC and PR space
* Comparison of ROC and PR curves
* Accuracy, AUC and other metrics

------
#### Week 10. Dimensionality reduction

We will consider how to visualize hidden structures in high-dimensional data, such as hidden clusters or embedded low-dimensional manifolds, by using dimensionality reduction methods. We will explain the underlying principles of dimensionality reduction methods such as multidimensional scaling, locally linear embedding, isomap, spectral embedding, and stochastic neighbor embedding. We will see how the geometry, linear algebra and optimisation methods give raise to different dimensionality reduction methods.

Our focus will be on the dimensionality methods that are commonly used in practice and widely available through software libraries such as sklearn.manifold. We will also consider modern tools for visualizing different dimensionality reductions such as Google embedding projector.


*Readings*:
* T. F. Cox and M. A. A. Cox, Multidimensional Scaling, Second Edition, Chapman & Hall / CRC, 2000
* I. Borg and P. J. F. Groenen, Modern Multidimensional Scaling: Theory and Applications, Second Edition, Springer, 2005
* A. Geron, Hands-on Machine Learning with Scikit-Learn & TensorFlow, O’Reilly, 2017, Chapter 8, Dimensionality Reduction
* Google's [embedding projector](http://projector.tensorflow.org)
* API reference, [scikit-learn, Section 2.2: manifold learning](http://scikit-learn.org/stable/modules/manifold.html)

*Lab*: [**Dimensionality reduction using sklearn.manifold**](https://classroom.github.com/a/DOp3TXsR)
* Dimensionality reduction plots using different methods
* Understanding the meaning of various input parameters
* Understanding the sensitivity to the input parameter values

------
#### Week 11. Graph data visualization

In the last week, we will consider basic methods for visualization of graph data such as visualizing social network relationships. We will consider different graph layouts and the principles of how they are computed. This will involve methods based on simple principles for drawing graphs that have a tree structure as well as more sophisticated methods based on spectral theory of linear algebra and dynamical systems for general graphs.

*Readings*:
* A. Hagberg, D. Schult and P. Swart, [NetworkX Reference]( https://networkx.github.io/documentation/latest/_downloads/networkx_reference.pdf)
* NetworkX: Software for complex networks, [https://networkx.github.io/](https://networkx.github.io/)
* [Graphviz – Graph Visualisation Software](http://graphviz.org/), especially manual pages, layout commands


*Lab*: [**Graph drawing using NetworkX**](https://classroom.github.com/a/yErZ9N6r)
* Loading and manipulating graphs using NetworkX
* Changing basic properties of graph visualization such as node or edge colors
* Drawing graphs using different layouts
* Using graphviz graph layouts
