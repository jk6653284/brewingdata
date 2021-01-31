---
layout: post
title:  "January 2021 Project: Random Recipe Recommender"
categories: project
---

## Summary
The original idea was to create a way to easily try new recipes without having to go through multiple different websites at the same time. One of my new year goal is to try new recipes, but going through few dozen recipe blogs and recipe aggregators to get inspired is always a pain. The goal was to scrape only links from recipe sources, and randomly recommend few recipes whenever the python script is called.

Overall I am very happy with this. It's simple, but I was able to apply different skills I learnt in creating something that is so useful to me. I'm literally using this everyday and trying new recipes that I would have never found before.

[Github link](https://github.com/jk6653284/randomrecipe/)


## Goal
Ranrom recipe recommender via command line or GUI/web app


## Technical Goal
* Create it in a separate virtual environment
    * managed it. I have a bad habit of not using virtual environment when creating projects, so this forced me to work from scratch.
* Structure project
    * managed it. Still need to learn, but at least it's not all files in a single directory. And also managed to add a `yaml` file for configuration.
* Add logging
    * managed it, but for some reason I had to turn off logging due to some weird error when running GUI. Need to look into this.
* Create GUI
    * managed it! My first GUI. It's simple, nothing fancy, but I'm still proud of creating something that doesn't reside in a command line.
* Document README
    * half managed it.
* Automate scraping with airflow scheduling
    * haven't managed. Will probably work as next step in the future.
* Feedback script
    * started, but haven't managed. I need to figure how to add review in a way that I can use to create non-random recipe retrieval based on review history.

