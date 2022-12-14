---
title: Day 1 - NLP
weight: 1
disableToc: true
draft: false
---

## Practical info
Place: DHØ 1.52
Time: 11:40


## Schedule for the day

* Session 1: Review Hate-speech classifier [Notebook](https://colab.research.google.com/github/aaubs/ds-master/blob/main/notebooks/M2-hatespeech-nlp-explainer-tm.ipynb)
* Session 2: Work on NLP case in groups
* Session 3 - 15:00-16:00: Guest Webinar - AI Implementations in SMEs (in collaboration with AI Denmark and AI 4 The People)


### Context - Exercise: Presidential Debate 2020


Yes, we are going back in time to the Presidential Debate in the US 2020 - the time of lots of unhappy Tweeting. It's just too good a dataset and case to let it go...

![](https://ichef.bbci.co.uk/news/800/cpsprodpb/E505/production/_114692685_uspresidentialdebate2020timedonaldtrumpandjoebiden.jpg)

### Data

* Political tweets: `https://github.com/SDS-AAU/SDS-master/raw/master/M2/data/pol_tweets.gz` from https://github.com/alexlitel/congresstweets We've preprocessed a bit to make things easier. 1: Dems. 0: Rep.

* Tweets around the time of the debate in oktober 20 (8000): `https://github.com/SDS-AAU/SDS-master/raw/master/M2/data/pres_debate_2020.gz`

Both datasets are in JSON format.
Task: Build a classifier that can distinguish Dem/Rep tweets. Bonus: 1. Explore discussed topics; 2. find out what drives predictions.

## In class Notebooks

* [R Solution](https://sds-aau.github.io/DSBA-2022/notebooks/NLP_workshop_1_debate_tweets.nb.html)
* [Python Solution](https://colab.research.google.com/github/aaubs/ds-master/blob/main/notebooks/DSBA_M2_W2_NLP_Tweets.ipynb)

<!---

### Introduction 

#### Context: The Danish Power Elites

* [Antons PhD Thesis](https://magtelite.dk/wp-content/uploads/2015/09/Anton-Grau-Larsen-PhD-Elites-in-Denmark.pdf)
* [Brief Summary of findings (CBS)](https://www.cbs.dk/en/alumni/news/a-look-the-danish-power-elite)
* [Journal Paper in Sociology](https://journals.sagepub.com/doi/abs/10.1177/0038038512454349)
* More to be found with googleling...

#### Data

* [Github (R Repository)](https://github.com/antongrau/eliter)
* [Magteliten website](https://magtelite.dk/data/)
* Or, easier... on [our github](https://github.com/SDS-AAU/SDS-master/raw/master/00_data/networks/elite_den17.csv)

### Tasks

* Who are the most central persons?
* Communities?
* What characterizes them?
* * Link up with additional data?

## Workshop: AI as a Service

By guest: Andreas Markussen 

{{< panopto "https://cbs.cloud.panopto.eu/Panopto/Pages/Embed.aspx?id=4ee56e3e-6770-413e-abea-adc3010a580d&autoplay=false&offerviewer=true&showtitle=true&showbrand=false&captions=false&interactivity=all">}}

### Introduction 

The purpose is to demonstrate a minimum viable product of an ML model deployment. Keeping with the DSBA spirit, I would keep the section hands-on. I would cover a minimal ML pipeline using data that is already preprocessed. The model will be saved to a static file and served through an API. When done, we will have created a web service from scratch, that can be used by any user in their browser. The project will be conducted in Python, with a little HTML added.


### Structure:

- Very brief introduction to how the web works - 15 mins
- Building model and exporting to static file - 15 mins
- Building Flask web app - 10 mins
- Adding APIs - 10 mins
- Adding some HTML and concluding the complete web service - 10 mins
- Deployment to Heroku free account, short showcase of extensions and other applications (no code here) and rounding off - 15 mins

### Preperation

To get most of this workshop, you should have: 

- Some existing knowledge of Python
- A local installation of Python
- Good understanding of an ML flow.
- No understanding of the web in general


### Materials


- [Data {{< awesome fas fas fa-database >}}:](https://www.appliedcoding.net/uploads/all_vintages_data_set.csv)
- [Repo {{< awesome fab fa-github >}}:](https://github.com/andreas-mar/DSBA-14-10-2021/tree/master)
- [Slides](https://github.com/SDS-AAU/DSBA-2021/raw/master/static/notebooks/DSBA%20presentation.pdf)



{{< tabs >}}

{{< tab name="Joint recordings">}}
  <h2>Assignment 1 handout</h2>
  {{< panopto  "https://panopto.aau.dk/Panopto/Pages/Embed.aspx?id=4b2660d2-790f-49cf-84be-ada900ea3083&autoplay=false&offerviewer=true&showtitle=true&showbrand=false&start=0&interactivity=all" >}}

{{< /tab >}}



{{< tab name="R Application">}}
<div>

  <h2>R: Recording</h2>
 
 coming soon

</div>
{{< /tab >}}



{{< tab name="Python Application">}}
<div>
  
  
  <h2>Python group recoding </h2>
  {{< panopto "https://panopto.aau.dk/Panopto/Pages/Embed.aspx?id=3c6006e6-e8e2-4ac4-a0a8-ada900ea85bc&autoplay=false&offerviewer=true&showtitle=true&showbrand=false&start=0&interactivity=all" >}}
</div>
{{< /tab >}}

{{< /tabs >}}
 --->


