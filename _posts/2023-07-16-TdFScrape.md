---
layout: post
title: Scraping for the Tour de France
# author: Aran
---

Following some good advice, I've started web scraping and found it a rewarding learning experience.

It all began with my wanting to write up a little project on the Tour de France, probably the most famous cycling race. I wanted to dig into the details of how bike riders are trending, what kind of person tends to win it, and, given the extreme tactical and team-based nature of the sport, what is the best team makeup to ensure a winner?

I intially began working from a [Kaggle dataset](https://www.kaggle.com/datasets/pablomonleon/tour-de-france-historic-stages-data) was available, to really get the in-depth data I was interested in, I instead used the [procyclingstats](https://www.procyclingstats.com/race/tour-de-france/) website to extract full stage information. This involved writing a number of functions to scrape then correctly format data, including team time trials.