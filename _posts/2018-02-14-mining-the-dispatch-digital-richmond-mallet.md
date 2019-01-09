---
layout: post
title: Mining the Dispatch for Textual Data on the Civil War
description: "Using machine learning and probabilistic topic modelling specifically a tool called MALLET -created by McCallum, Andrew to analyze an archive of 112000 pieces of text, and more than 24 million words."
modified: 2018-02-14
tags: [data, charts, ]
comments: true
categories: [cool tools]
pinned: true
---
{{ page.title }}
================

![](http://chart.apis.google.com/chart?cht=lc&chs=700x300&chd=e:WtXpoQcKO.O4I9KvJMLAJuNgLyRPYMVEVPTeNBMFNsP2QVa0TZabyqp5aXWmUjUOTZSLT0QAR5cjw3c.WXZhPEQFL0Q3VNYaQcfTzLbnY9,GNHLHCFTIiJKGWK.JMJ8ObOoKUWJWrSoLENBSmQMXMUagIXARjQMQVRsTrT3UjPtO2O4URQcMHOEUDSLRhTZYga7XFcWR4QHQVYlUpNWKc&chdl=for+hire+and+wanted+ads|fugitive+slave+ads&chdlp=b&chds=0,17.74075&chxt=x,x,y&chxr=2,0,17.74075&chxl=0:|Jan|Apr|Jul|Oct|Jan|Apr|Jul|Oct|Jan|Apr|Jul|Oct|Jan|Apr|Jul|Oct|Jan|1:|1861|1862|1863|1864|2:|0%25|2%25|4%25|6%25|8%25|10%25|12%25|14%25|16%25|&chxp=0,3.85,9.62,15.38,21.15,26.92,32.69,38.46,44.23,50,55.77,61.54,67.31,73.08,78.85,84.62,90.38,96.15|1,14.42,37.5,60.58,83.655|2,0,2,4,6,8,10,12,14,16&chm=R,F2F2F2,0,0.028884615384615,0.25965384615385|R,F2F2F2,0,0.49038461538462,0.72115384615385|R,F2F2F2,0,0.95188461538462,1&chco=446688,4cb052)
#### Project Review: [Mining the Dispatch](http://dsl.richmond.edu/dispatch/) for Textual Data on the Civil War

##### Summary

Using machine learning and probabilistic topic modelling specifically a tool called MALLET a - tool created by McCallum, Andrew Kachites from UMASS- Amherst, Robert K. Nelson, Director of the Digital Scholarship Lab at the University of Richmond and other scholars. This project was created to analyze an archive of 112000 pieces of text, and more than 24 million words to paint a picture of life in Richmond in the 1900s. This was at a time when Richmond was "the center of the Civil War South" and in Robert’s own words, the most cited but least understood city of the period. Using these probabilistic topic modelling, machine learning, text analysis tools, Robert K. Nelson analyzes newspaper texts from The Dispatch- a prominent newspaper of the South in the era to examine what the texts were about, analyzing runaway slave advertisements, plain newspaper advertisements, and other articles in those newspapers.

The tools used and their strengths and weaknesses
Robert K Nelson explains how MALLET- a statistical natural language processing, document classification, clustering, topic modeling, information extraction, and other machine learning application tool, carries out a kind of "distant reading" to make sense of these large amounts of text. Nelson explains the inherent flaw in this process as being that the tool relies heavily on the frequencies of words in the articles and may not be contextually accurate in the same way a person practicing traditional close reading would be. Distant reading allows the digital humanist to carry out an analysis of an entire archive of texts while close reading allows the analysis of samples of archives of texts. Nelson shows how remarkably efficient these methods are for querying digital humanities data sets and identifying trends and patterns in larger bodies of texts and multiple sets of information.

#### Purpose and questions posed by Nelson.

This project then tries to analyze textual data en masse and then use statistical and mathematical methods to identify patterns in it and derive qualitative information from it. Nelson tries to answer qualitative questions like, "What effect did the civil war have on the rate of slave escapes?" "How important was the civil war in giving slaves a chance to run away and escape the harsh conditions in the South?" "How did slavery evolve during the civil war? Did it increase, decrease, or did it take on new shapes and forms?" The graphs that show the correlation between slave hiring advertisements over time as the civil war progressed allow the digital humanist to identify patterns and the relationship between the civil war's intensity and progress, and the demand and supply of slaves evident from the number of advertisements in The Dispatch.

Nelson queries why the market for slave labor remained largely contest over time, until a sudden inexplicable drop in the hiring market for slave labor around 1862. This method of analyzing large datasets in this way has the inherent weakness of neglecting contextual data. Nelson argues that the methods used to analyze the dispatch data sources are most useful when they enable digital humanities scholars to identify patterns they otherwise would not have identified through close reading.

#### Topics Explored

**Slavery** was a prominent part of this humanities project and Nelson analyzed these textual bodies of data to identify trends and patterns in slavery and how the civil war influenced it. In examining this project, it can be useful to inquire of Nelson about the factors that influenced the survival of slavery that did not include the war and what impact slavery had on the slaves themselves and the social fabric of the period.

![](http://journalofdigitalhumanities.org/wp-content/uploads/2013/02/chart.png)

**Nationalism and Patriotism** were analyzed in poems, articles and essays that were published in the newspaper that rallied for the support of anti-northern sentiment and support for the southern war effort.

In all, **40 different topics** are explored by this research project which identifies the relationships between different variables and metrics that influenced the politics and developments of the period. Some of these other topics include military conflict, soldiers, economy, politics, local news, and advertisements.

#### History and process.

The Mining The Dispatch digital humanities project uses a data set of newspapers of The Dispatch from the period from 1860 through 1865, spanning 112000 pieces of writing and almost 24 million words. The program uses these texts to draw conclusions based on an algorithm to give a view of sentiment on various issues such as slavery, runaway slaves based on their incidence in the newspapers and the keywords used in each article. The MALLET program used uses keywords it picks up from each article and then terms topics to deduct what an article is about based on machine learning, text analysis and probabilistic modelling. While the program is highly efficient for large data sets, for narrower data sets, the incidence of contextually inaccurate results increases.

The project also uses the Google Charts API and icons to generate charts and present data.
