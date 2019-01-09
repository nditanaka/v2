---
layout: post
title: A short intro to text mining examples and algorithms in python
description: "LDA topic modelling process uses probability statistics to divide a corpus into groups of words to determine what the topics/ themes of the constituent words of the corpus are. The system works by doing this continuously, over and over again, choosing a word, and then comparing it to all the words in each category, and determining which category the word best fits into. After enough iterations, all the words are grouped in the correct themes and they no longer need to be moved from one category to another."
modified: 2018-04-11
tags: [information, data]
comments: true
categories: [information]
pinned: true
---
{{ page.title }}
================
![David Mimno LDA topic modelling](https://databricks.com/wp-content/uploads/2015/03/20newsgroups.png)

[David Mimno](http://www.mimno.org/)'s LDA topic modelling process uses probability statistics to divide a corpus into groups of words to determine what the topics/ themes of the constituent words of the corpus are. The system works by doing this continuously, over and over again, choosing a word, and then comparing it to all the words in each category, and determining which category the word best fits into. After enough iterations, all the words are grouped in the correct themes and they no longer need to be moved from one category to another.

My immediate question reading this is that of whether Mimno approached this as a purely mathematical probability statistics problem or a natural language processing one, and how he got the probability program to account for the vague and ambiguous natures of words. Did he use dictionaries or existing databases of words under subtopic like the the [Corpora](https://github.com/dariusk/corpora) repository. I find this a daunting technical problem to solve because I expect some margin of error owing to words having multiple contextual meanings.

# How does LDA topic modelling account for stop words and words like nouns?

These words have no strict definition or in other languages for which no strict topic is readily available? I assume the topic model compares them against a dictionary of stop words that are predefined. Another thought I have is the efficiency of such a system. What is the relationship between the corpora size and time taken to finish topic modelling it? Is the relationship linear? Does the time taken to finish sorting the words into their categories increase as the number of words increases at a linear rate, or exponential rate, or is it constant for corpora of roughly the same size? Related to this, I am curious about the number of iterations the program must go through for a given corpora of size n before text is sorted into the right categories. The LDA topic modelling technique strikes me as ingenious even without fully grasping the probability statistics that powers it.
