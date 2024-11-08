# voyage-project-tier1-mobilephone

## Table of Contents

* [Overview](#overview)
* [General Instructions](#general-instructions)
* [Requirements & Specifications](#requirements-specifications)
* [Acknowledgements](#acknowledgements)
* [About Chingu](#about-chingu)

## Overview

Welcome, Chingu Data Scientists!

In this day and age almost everyone has a mobile phone, and our lives seem
to revolve around them!

Since mobile phones are so ubiquitious wouldn't it be interesting to explore
how they are being used and the behaviours of their owners?

In this voyage, your team has been provided with a dataset containing a
mobile device usage patterns and user behavior classifications. It contains 700
samples of user-oriented metrics such as app usage time, screen-on time,
battery drain, and data consumption.

Each entry is categorized into one of five user behavior classes, ranging from
light to extreme usage, allowing for insightful analysis.

Your task will be to use your data science skills to uncover interesting and
meaningful relationships from this data. Read on to learn more!

![Mobile Device Usage and User Behavior Dataset](./assets/user_behavior_dataset.csv)

## General Instructions

This project is designed to be worked on by a team rather than an individual
Chingu. This means you and your team will need to thoroughly read and
understand the requirements and specifications below, **_and_** define and
manage your project following the _Agile Methodology_ defined in the
[Voyage Handbook](https://github.com/chingu-voyages/Handbook/blob/main/docs/guides/voyage/voyage.md#voyage-guide).

As you create this project make sure it meets all of the requirements, but once
it reaches MVP, start implementing the optional features or get creative and
extend it in ways we haven't envisioned. In other words, use the power of
teamwork to make it distinctive and unique.

Take note that we haven't given specific direction on what your UI/UX should
look like or how results are to be rendered. However, you may choose to create
either a web site or a [Jupyter notebook](https://jupyter.org/). This is
another area where you and your team can put your creativity to work!

## Requirements & Specifications

### What You Need to Do

The following define the minimum requirements and ideas for features you may
implement to enhance this app, if time permits.

#### Structure

* [ ] You may use any languages, tools, or libraries you prefer when designing and building this app.
* [ ] You may build a Web application for your users or you may use a DS tool like Jupyter.
* [ ] You may **_NOT_** use AI-base solution generators like GitHub CoPilot.
* [ ] We've included a csv file containing the raw data in the /assets directory in this repo.
* [ ] Useful links and resources:
  * This data was obtained from the Kaggle dataset [Mobile Device Usage and User Behavior Dataset](https://www.kaggle.com/datasets/valakhorasani/mobile-device-usage-and-user-behavior-dataset?resource=download)

#### Styling

* [ ] Surprise us!!! Use your teams creativity to make this app distinctive.
* [ ] Be sure to add a link to your teams GitHub repo.
* [ ] Include an attribution to the data source you solution is based on.
* [ ] If you are developing a Web app you may find these resources helpful:
  * In general, you will find these [UI design principles](https://www.justinmind.com/ui-design/principles) helpful.
  * We recommend using this resource for [clean CSS](https://israelmitolu.hashnode.dev/writing-cleaner-css-using-bem-methodology).

#### Functionality

* Overview

  * [ ] As with any dataset you shouldn't assume that the data is 100% clean. Ensure that you understand the data and have scanned it to identify invalid column values before you start your analysis.

* Basic Functionality

  * Analyze the data based on several general categories to first understand the popularity of different devices and operating systems.
    * [ ] Display a summary of the most popular devices based on user age & gender.
    * [ ] Display a summary of the most popular Operating system types by user age & gender

  * Analyze the data and provide answers for the following questions:
    * [ ] How is the rate of battery drain impacted by device model and operating system?
    * [ ] How is the rate of battery drain impacted by app usage time, screen on time, and data usage?
    * [ ] Is batter drain impacted by any other category, like the number of apps or the gender of the user?
    * [ ] Does the users age or gender impact screen on time or number of apps installed?
    * [ ] For each analysis include the appropriate summary metrics such as range of scores, mean score, average score, standard deviation, and any other metric that supports your findings.
    * [ ] You should also include data visualizations of your choice to add value to the results. For example, a graph of the most popular device models and operating system by user age and gender. Don't limit yourself to just this analysis though. Add visualizations for any or all of your analyses.
    * [ ] The metrics and visualizations you create should be clearly labelled and organized in a way that makes it easy for the user to understand what they are.
    * [ ] Make sure that your results are displayed in manner that's easy for the user to interpret.

  * [ ] Based on your analysis what recommendations would you make to Apple (Ios) and Google (Android) that would help them improve the appeal of devices running their operating systems?

* User Interface and Experience

  * [ ] Ensure the application provides a seamless user experience.
  * [ ] Implement intuitive UI/UX elements to guide users through the process of displaying your results.
  * [ ] Use responsive design techniques to ensure the application is accessible and functional across various devices and screen sizes.

### Extras (Not Required)

* [ ] Implement filters and search functionality to easily find specific sets of results.
* [ ] Come up with your own questions and implement analytics for all categories of data or any combinations of categories you think are useful or interesting to the reader:

## Acceptance Criteria

* Basic Functionality

  * [ ] The analysis should meet the Basic functionality described above.
  * [ ] Your analysis should be performant. In other words, end users should be able to display the results in a reasonable amount of time (e.g. less than 10 seconds)
  * [ ] Users should be able to view the menu in an organized manner, with categories clearly delineated.

* User Interface and Experience

  * [ ] The application must provide an intuitive and seamless user experience for browsing the menu and placing orders.
  * [ ] Responsive design techniques must be used if you are implementing a web app to ensure functionality across various devices and screen sizes.

## Acknowledgements

Many thanks to [Kaggle](https://kaggle.com) and it's contributors for providing many datasets to help Data Scientist build and refine their skills.

## About Chingu

If you aren’t yet a member of [Chingu](https://chingu.io) we invite you to join us. We help our
members transform what they’ve learned in courses & tutorials into the
practical experience employers need and want.
