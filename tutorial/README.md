# Final Tutorial

Instead of a Final Exam in this course you will be responsible for generating a tutorial that will walk users through the entire data science pipeline: data curation, parsing, and management; exploratory data analysis; hypothesis testing and machine learning to provide analysis; and then the curation of a message or messages covering insights learned during the tutorial. Students may choose an application area and dataset(s) that are of interest to them; please feel free to be creative about this!

In the interest of building students' public portfolios, and in the spirit of "learning by doing", students will create a self-contained online tutorial to be posted publicly and a 7-10 minute presentation in class. This tutorial can be created individually or in a small group (max 2 people). This assignment will be a publicly-accessible website that provides an end-to-end walk-through of identifying and scraping a specific data source, performing some exploratory analysis, and providing some sort of managerial or operational insight from that data.  We will have several milestones associated with the final project including the following.  These are each discussed below in more detail.

1. **Milestone 1:** Identifying a dataset and establishing a GitHub.io Site. (\~25 points)
2. **Milestone 2:** Extraction, Transform, and Load (ETL) + Exploratory Data Analysis (EDA). (\~50 points)
3. **Deliverable 1:** A final, in class presentation. (\~50 points)
4. **Deliverable 2:** A final tutorial and website. (\~75 points)

## Milestone 1: Groups, Data, and Website

For Milestone 1 you should generate a roughly 1 page writeup (500 words) listing a partner (if any) and one to three datasets that you are considering working with and why.  This is just an outline to make sure you are thinking.  This will be published on your GitHub IO page so this also makes sure you’ve figured out how to get it uploaded!

### Possible Sources of Data

This list is just to give you some ideas.  Please feel free to scrape websites (legally!) or to find other sources of data that you may find important or interesting.

* [Data.Gov](https://www.data.gov/): US-centric agriculture, climate, education, energy, finance, health, manufacturing data, and more.
* [BigQuery (Google Cloud)](https://cloud.google.com/bigquery/public-data/) public datasets (bikeshare, GitHub, Hacker News, NOAA,...) and many more.
* [Kaggle Competition Datasets](https://www.kaggle.com/datasets) Billboard Top 100 lyrics, credit card fraud, crime in Chicago, global terrorism, world happiness, etc...
* [Amazon AWS Public Data](https://aws.amazon.com/public-datasets/) AWS-hosted, various (NASA, a bunch of genome stuff, Google Books n-grams, Multimedia Commons, etc.)
* [Data is Plural](https://docs.google.com/spreadsheets/d/1wZhPLMCHKJvwOkP4juclhjFgqIY8fQFMemwKL2c64vk/edit#gid=0)Lots of interesting and strange datasets in a Google spreadsheed.
* [Corgies Datasets](https://think.cs.vt.edu/corgis/) Curated set of data from Virginia Tech.
* [GitHub Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets) list of datasets that are open and public around the Internet.
* [Think Stats Datasets](https://docs.google.com/spreadsheets/d/e/2PACX-1vQlv2BpO7TsU2UAE7iQwCUxvxn9LTXEPPj5EnA0l9-DJSwCDZU0xg_IhWBItZ7bNvZ_BnznuOrYYy0i/pubhtml) list of interesting datasets from a class very much like this one.
* [Data.Nola.Gov](https://data.nola.gov/browse) list of open datasets from NOLA including lots of financial, voting, etc.

### Github Pages
GitHub provides a service called Pages <https://pages.github.com/> that provides website hosting functionality backed by a GitHub-based git repository. We would like you to host your final project on a GitHub Pages project site. To do this, you will need to:
1. Create a GitHub account (or use the one you already have from Project0) with your username `username`.
2. Create a git repository titled `username.github.io`; make sure `username` is the same as whatever you chose for your global GitHub account.
3. Create a project within this repository. This is where you’ll dump your iPython Notebook file and an HTML export of that Notebook file.

These instructions are also given directly on the front page of <https://pages.github.com/>; following those instructions should be fine!

You should submit the notebook through [Canvas](https://tulane.instructure.com/).  The first cell of your notebook in the markdown **must be a clickable link to the webpage and the webpage must be live**.  If you do this in a group, both students must submit the notebook through Canvas but it should be the same notebook.

### Scoring Rubric (25 Points)
* 10 Points: Website is up, link was submitted on time.
* 15 Points: Project plan is in place, relevant data is identified, there are draft questions.

---

## Milestone 2: Extraction, Transform, and Load (ETL) + Exploratory Data Analysis (EDA)

Your notebook from Part 1 but expanded to include the data being loaded and showing that you have figured out how to get the data into your system. Your notebook expanded to include some graphs, visualizations, and stats that show you can manipulate your data and understand the dataset you are working with.


### Scoring Rubric (50 Points)

---

## Deliverable 1: Final Presentation

You (and your partner) will give a 7-10 minute presentation in class.  In this presentation you are role playing a bit -- your job is to convince the audience that the problem you investigated was interesting and meaningful.  Furthermore, you should give some detail of the analysis and you should make specific policy or outcome recommendations as the conclusion of your analysis.

## Scoring Rubric (50 Points)

* Professionalism: Are the slides well constructed?  Are the graphs labeled and clear?
* Organization: Was the talk clearly organized?  Did you explain where your data came from, why the question was important, and what the outcomes are?  You should address each stage of the DataScience LifeCycle in this talk.
* Motivation: Does the talk make the reader believe the topic is important (a) in general and (b) with respect to data science?

---

## Deliverable 2: Final Tutorial

In general, the tutorial should contain at least 1500 words of prose and 150 lines of (nonpadded, legitimate) Python code, along with appropriate documentation, visualization, and
links to any external information that might help the reader.

Some example tutorials from a similar class at the University of Maryland are:
* Predicting a win in Rainbow Six: Siege: <https://jiglesia3.github.io/>
* Maryland and peer institutions’ faculty/student counts: https://krixly.github.io/
* Analysis of crime data in College Park: https://andresgogo.github.io/

## Scoring Rubric (75 Points)
* Motivation: Does the tutorial make the reader believe the topic is important (a) in general and (b) with respect to data science?
* Understanding: After reading the tutorial, does the reader understand the topic?
* Further Resources: Does the tutorial “call out” to other resources that would help the reader understand basic concepts, deep dive, related work, etc?
* Prose: Does the prose in the Markdown portion of the .ipynb add to the reader’s understanding of the tutorial?
* Code: Does the code help solidify understanding, is it well documented, and does it include helpful examples?
* Subjective Evaluation: If somebody linked to this tutorial from Hacker News, would people actually read the whole thing?


