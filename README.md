# Final Project: Article Summarizer

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

We recommend a guided version of the project, starting with this repo: https://github.com/wmnlp-materials/article-summarizer

# Objectives

This exercise is used to apply your web mining and NLP skills in a project of your choice. What do you wish we had covered more?  Explore options - your project can focus on article summarization, using an API, doing sentiment analysis, working through an online tutorial, or gathering any text corpus and finding the most common words (ideas) used, and/or using visualization to provide useful insights. 

As data analysts, our task is to find actionable, useful information and present it clearly. Many students use this to provide a unique, custom project for their online portfolios. As such, you may name your repo as you like. Credit will be earned based on the type of project selected and your ability to present your exploration professionally. Enjoy! 

### Virtual Environment Set Up

```python -m venv .venv```

```.venv\Scripts\activate```

"Select Kernel" in notebook to use virtual environment.

### Packages Required *(Cannot import to notebook without installing first)*

[Find list of packages here](https://github.com/Bdowdle4/bd-article-summarizer/blob/main/requirements.txt)

```pip install -r requirements.txt```

[Code to install spaCy here](https://spacy.io/usage)

### Convert notebook to HTML

```!jupyter nbconvert --to html "file name".ipynb```

# Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Polarity score printed with an appropriate label: 1 pt
* (Question 2) Number of sentences printed: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Histogram shown with appropriate labelling: 1 pt
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Cutoff score seems appropriate given histograms: 2 pts (1/score)
* (Question 8) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 8) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 9) Polarity score printed with an appropriate label: 1 pt
* (Question 9) Number of sentences printed: 1 pt
* (Question 10) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 10) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 11) Polarity score printed with an appropriate label: 1 pt
* (Question 11) Number of sentences printed: 1 pt
* (Question 12) Thoughtful answer based on reported polarity scores: 1 pt
* (Question 13) Thoughtful answer based on summaries: 1 pt
