---
layout: post
lang: en
ref: beautiful-charts-with-frappe
title: Beautiful Charts with Frappe Charts
medium: ''
description: "I found this really cool tool online today under Github's trending repositories. It is called Frappe Charts. "
categories: [cool tools]
tags: [charts, javascript, science, data, information]
comments: true
---

![](/assets/images/posts/beautiful-charts-with-frappe.gif)

## Frappé Charts

GitHub-inspired simple and modern charts for the web with zero dependencies.

<pre style="min-width: 100%;">
<script src="https://unpkg.com/frappe-charts@0.0.3/dist/frappe-charts.min.iife.js"></script>
<div id="chart"></div>
<script type="text/javascript">
  data = {
    labels: ["12am-3am", "3am-6am", "6am-9am", "9am-12pm",
      "12pm-3pm", "3pm-6pm", "6pm-9pm", "9pm-12am"],

    datasets: [
      {
        title: "Creativity", color: "light-blue",
        values: [80, 80, 80, 60, 10, 10, 10, 10]
      },
      {
        title: "Hunger", color: "violet",
        values: [80, 80, 80, 80, 80, 80, 80, 80]
      },
      {
        title: "Sleepiness", color: "blue",
        values: [80, 60, 50, -10, -50, -30, -10, 10]
      }
    ]
  };

  chart = new Chart({
    parent: "#chart", // or a DOM element
    title: "How I feel throughout the day",
    data: data,
    type: 'bar', // or 'line', 'scatter', 'pie', 'percentage'
    height: 250
  });
</script>
</pre>

I found this really cool [tool](https://frappe.github.io/charts/) online today under Github's trending repositories. It is called Frappe Charts.

It is a tool to display [graphs and data visualizations](https://frappe.github.io/charts/) without any complicated excel or tableu software on your website. It is so easy to implement. You can display graphs like the one below showing my mood this past semester throughout the day.

Here are all the cool charts you can plot using it!

Instructions for installing the npm package for it, and implementing it are at the bottom of this page.

<script async src="//jsfiddle.net/tanakachingonzo/emf2xLwc/embed/js,html,result/"></script>


A line chart as shown below. This is implemented by modifying this code below in the JavaScript.

<code>type: 'line', // or 'bar', 'scatter', 'pie', </code>

<pre style="min-width: 100%;">
<script src="https://unpkg.com/frappe-charts@0.0.3/dist/frappe-charts.min.iife.js"></script>

<div id="line"></div>

<script type="text/javascript">
  data = {
    labels: ["12am-3am", "3am-6am", "6am-9am", "9am-12pm",
      "12pm-3pm", "3pm-6pm", "6pm-9pm", "9pm-12am"],

    datasets: [
      {
        title: "Creativity", color: "light-blue",
        values: [80, 80, 80, 60, 10, 10, 10, 10]
      },
      {
        title: "Hunger", color: "violet",
        values: [80, 80, 80, 80, 80, 80, 80, 80]
      },
      {
        title: "Sleepiness", color: "blue",
        values: [80, 60, 50, -10, -50, -30, -10, 10]
      }
    ]
  };

  chart = new Chart({
    parent: "#line", // or a DOM element
    title: "How I feel throughout the day",
    data: data,
    type: 'line', // or 'line', 'scatter', 'pie', 'percentage'
    height: 250
  });
</script>
</pre>

A scatter chart as shown below. This is implemented by modifying this code below in the JavaScript.

<code>type: 'scatter', // or 'bar', 'scatter', 'line', </code>

<pre style="min-width: 100%;">
<script src="https://unpkg.com/frappe-charts@0.0.3/dist/frappe-charts.min.iife.js"></script>

<div id="scatter"></div>

<script type="text/javascript">
  data = {
    labels: ["12am-3am", "3am-6am", "6am-9am", "9am-12pm",
      "12pm-3pm", "3pm-6pm", "6pm-9pm", "9pm-12am"],

    datasets: [
      {
        title: "Creativity", color: "light-blue",
        values: [80, 80, 80, 60, 10, 10, 10, 10]
      },
      {
        title: "Hunger", color: "violet",
        values: [80, 80, 80, 80, 80, 80, 80, 80]
      },
      {
        title: "Sleepiness", color: "blue",
        values: [80, 60, 50, -10, -50, -30, -10, 10]
      }
    ]
  };

  chart = new Chart({
    parent: "#scatter", // or a DOM element
    title: "How I feel throughout the day",
    data: data,
    type: 'scatter', // or 'line', 'bar', 'pie', 'percentage'
    height: 250
  });
</script>
</pre>

A pie chart as shown below. This is implemented by modifying this code below in the JavaScript.

<code>type: 'pie', // or 'bar', 'scatter', 'line', </code>


<pre style="min-width: 100%;">
<script src="https://unpkg.com/frappe-charts@0.0.3/dist/frappe-charts.min.iife.js"></script>

<div id="pie"></div>

<script type="text/javascript">
  data = {
    labels: ["12am-3am", "3am-6am", "6am-9am", "9am-12pm",
      "12pm-3pm", "3pm-6pm", "6pm-9pm", "9pm-12am"],

    datasets: [
      {
        title: "Creativity", color: "light-blue",
        values: [80, 80, 80, 60, 10, 10, 10, 10]
      },
      {
        title: "Hunger", color: "violet",
        values: [80, 80, 80, 80, 80, 80, 80, 80]
      },
      {
        title: "Sleepiness", color: "blue",
        values: [80, 60, 50, -10, -50, -30, -10, 10]
      }
    ]
  };

  chart = new Chart({
    parent: "#pie", // or a DOM element
    title: "How I feel throughout the day",
    data: data,
    type: 'pie', // or 'line', 'bar', 'scatter', 'percentage'
    height: 250
  });
</script>
</pre>
