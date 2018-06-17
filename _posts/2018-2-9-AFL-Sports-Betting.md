---
layout: post
title: Predicting AFL Winners 
---

Australian's have been notorious for their addiction to gambling. Unfortunately, judging by the growth of bookies, it doesn't seem as though we're very good at it. This project
uses Logistic Regression among other techniques to predict which team would win in a game of AFL. However, to further reduce the human elements involved, our model incorporates
the use of a fractional Kelly Criterion to advise on how much we should bet.


"Using the data provided by Sportsbet and CIKM 2015 challenge. We are going to try and maximize winnnings from bet tippings in any given season of AFL. This involves two steps:\n",
"\n",
"* Part 1: Predicting with a high enough accuracy the probability of the home team winning. \n",
"\n",
"* Part 2: Calculating what the best percentage of our capital to bet is.\n"

The data for this project is sourced from several websites. The meat of the dataset is provided under the **2015 CIKM & SportsBet AFL Challenge**, with others sections such as historical ladder rankings and historical betting odds coming from \n",
