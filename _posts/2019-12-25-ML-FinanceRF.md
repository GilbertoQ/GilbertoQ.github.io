---
layout: post
title: "Machine Learning in Finance"
excerpt: "A Machine Learning approach to predicting returns based on predefined Foregin Exchange Patterns"
categories: [Informational Blog]
comments: true
date:  2019-12-25
---

The goal was to create a model to get events which then a Random Forest Classifier can then be fit on certain statistical properties to see an improved accuracy.

The pattern to find in Foregin Exchange data was called the Tripple Barrier Method.
![Table1](/img/TB.png)
Table 1: As seen, if a certain section of the market touches the top barrier first then that means that is a positive occurrence of the class if it meets the vertical barrier or bottom barrier then it is a negative class.

Once the events are chosen then statistical properties are gathered about the event dates and a Random Forest Classifier is then fitted on the event data.

The Github: [Link](https://github.com/GilbertoQ/ML_FinanceRF)

The online version can be found here: [Link](http://54.185.193.20:8501/)