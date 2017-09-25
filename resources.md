---
layout: page
title: Resources
---

<!-- Perhaps the best resource is Google for your particular question.   -->
We’ve collected some links that we think will be helpful, but they are more like overviews than resources that will help you with a specific thing you are trying to accomplish.

<!-- **_Table of Contents:_**

* Mechanical turk
* HTML/CSS
* JavaScript
* Github
* R
* dplyr/tidyr
* ggplot
* lme4
* Functional Experiment Templates -->

### Mechanical turk

In this class we will be running our replication projects on Amazon's Mechanical Turk (AMT/mTurk). mTurk is a platform on which **Workers** (or "Turkers") can complete Human Intelligence Tasks (**HITs**) for monetary compensation. HITs are put up by **Requesters**. mTurk originally was set up to do large-scale tasks that require human intelligence (e.g. labeling photos, finding telephone numbers, etc), but has recently been used by social scientists to conduct (large-scale) online experiments.

All replication projects will be launched using a common class account. This saves you the hassle of applying for a personal Requester account (which lately has become not-as-straightforward...), and also simplifies funding logistics. We will be giving more detailed instructions in class on how to access the class account and launch HITs etc.

**A note on design considerations.** Some Turkers multitask, and most of them do HITs for many hours a day, so appropriate designs would include attention checks, manipulation checks, etc.

**A note on ethics.** Note that Amazon workerIDs are actually tied to their (public) Amazon account, and thus constitute identifiable information. Thus, you should anonymize data by redacting workerIDs (and other identifiable information).

**A note on best research practices.** Do all analyses on anonymized data. (This is to prevent cases where others are unable to reproduce your analayses because it might rely somehow on identifiable information. If you start with anonymized data, your analyses would never use any of this information.)

* Beginner:

    * [A gentle guide to MTurk](https://www.google.com/url?q=http://pages.ucsd.edu/~tfeenstr/resources/mturkhowto.pdf&sa=D&ust=1452640774009000&usg=AFQjCNEEsUw9MtJ9c2XtTxpKnWarDK9sOg)

        * A good place to start

    * [Guide to Mturk basics](https://docs.google.com/document/d/1MMdOvYl-rXkwAp68BdgKvGH-2rOXmIe8H9uL77GjoH8/edit?usp=sharing)

        * Filled with lots of notes and tips (Thank you James/Jamil/Noah labs)

    * [MTurkers are people](http://www.pbs.org/newshour/updates/inside-amazons-hidden-science-factory/) (& the problem with common paradigms on MTurk)

    * Setting up simple experiments

        * [Survey within MTurk platform](https://requester.mturk.com/create/projects/new)

        * [Qualtrics Link](http://research-tricks.blogspot.com/)

            * My preferred method of directing turkers to Qualtrics

* Intermediate:

    * [Turker Nation](http://www.turkernation.com/)

        * Discussion board for Turkers

    * [Creating a launch page to external site](https://github.com/ericnatsmith/Wilson-2014-just-think-replication)

        * advantage is that your study is embedded within MTurk, then opens a full page window for your task when required. Note launcher.html and task.html are separate.

    * [Getting around the ridiculous extra 20% fee for 9+ participants](https://docs.google.com/presentation/d/1Y_lvecsOefCfkXkkrdFtW1GH-NkoZidKzKXqFVJaLH4/edit#slide=id.p)

        * [MTurk fee structure](https://requester.mturk.com/pricing)

### HTML/CSS

* Beginner:

    * [Interactive HTML/CSS Tutorial](https://www.codecademy.com/learn/web) (Code Academy)

        * More structured course

    * [Quick CSS-Specific Tutorial](http://www.w3schools.com/css/default.asp) (Learn Layout)

    * [CSS Reference](http://www.w3schools.com/css/default.asp) (w3 schools)

        * Good resource with "Try it yourself" to see immediate output of code

* Intermediate:

    * [CSS Positioning Tutorial](https://www.codecademy.com/en/courses/advanced-css-positioning) (Code Academy)

        * Perhaps the most frustrating part of CSS

* Advanced

    * [Bootstrap](http://getbootstrap.com/) (Not of the statistical sort)

        * Generally better for creating full web-pages than one-off experiments, but can make introduction pages, survey websites etc. look good with minimal effort.

### JavaScript

* Beginner:

    * [Interactive JavaScript Tutorial](https://www.codecademy.com/learn/javascript) (Code Academy)

    * [JavaScript Reference](http://www.w3schools.com/js/) (w3 schools)

* Intermediate:

    * jQuery (tool for making web pages responsive)

        * [Interactive JQuery Tutorial](https://www.codecademy.com/learn/jquery) (Code Academy)

        * [JQuery Reference ](http://www.w3schools.com/jquery/)

    * [JSPsych](http://docs.jspsych.org/)

        * Great resource if your experiment fits within your constraints- specifically created for web-based psych research, and works well with MTurk.

### Github

* [Beginner GitHub Tutorial](https://try.github.io/levels/1/challenges/1) (Try Git)

* [Intermediate GitHub Tutorial](https://www.codecademy.com/learn/learn-git) (CodeAcademy)

* [Advanced Cheatsheet](https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf) (from official documentation)

* [Git for Windows](https://git-for-windows.github.io/)

### R

* Beginner

    * [Beginner R Tutorial](http://tryr.codeschool.com/) (Good place for basic start)

    * [http://r4ds.had.co.nz/](http://r4ds.had.co.nz/) (Intro + Ch. 1- Will get you most of the basic competencies)

    * [Swirl](http://swirlstats.com/students.html) (+ [Github](https://github.com/swirldev/swirl_courses) repo) (Nice in R console learning)

* Intermediate/Advanced

    * (See package-specific tutorials below)

    * [http://adv-r.had.co.nz/](http://adv-r.had.co.nz/) (Great resource for those honing R skills)

    * [Advanced guide to R’s many quirks](http://www.burns-stat.com/pages/Tutor/R_inferno.pdf) (note: this is just for fun!)

* Everything else (because the needs are so diverse)

    * [www.google.com](http://www.google.com)

### dplyr/tidyr

* Beginner:

    * [http://r4ds.had.co.nz/wrangle-intro.html](http://r4ds.had.co.nz/wrangle-intro.html)

    * [dplyr Cheat sheet](https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf)

    * [dplyr Tutorial](https://www.datacamp.com/courses/dplyr-data-manipulation-r-tutorial)

    * dplyr/tidyr tutorial in [Swirl](http://swirlstats.com/students.html) ("Getting and Tidying Data")

    * [Why tidy data?](http://vita.had.co.nz/papers/tidy-data.pdf)

        * Great way to understand purpose tidy data

* Everything else

    * [https://www.google.com/#safe=off&q=how+do+I+use+tidyr](https://www.google.com/#safe=off&q=how+do+I+use+tidyr)

### ggplot

* Beginner:

    * [http://r4ds.had.co.nz/data-visualisation.html](http://r4ds.had.co.nz/data-visualisation.html)

    * [Simple intro to ggplot basics](http://www.r-bloggers.com/a-simple-introduction-to-the-graphing-philosophy-of-ggplot2/)

    * [ggplot2 on Cookbook for R](http://www.cookbook-r.com/Graphs/)

    * [ggplot2 docs](http://docs.ggplot2.org/0.9.3.1/)

        * If you already know the kind of plot you want, they’ll usually have a load of nice examples to make it look right

* Everything else

    * [https://www.google.com/#safe=off&q=how+to+ggplot2](https://www.google.com/#safe=off&q=how+to+ggplot2)

### lme4

* Intermediate

    * [Mixed effects models](http://www.bodowinter.com/tutorial/bw_LME_tutorial2.pdf)

        * Good resource on why mixed effects models are beneficial and how to perform them in R

    * [Keep it maximal](http://idiom.ucsd.edu/~rlevy/papers/barr-etal-2013-jml.pdf)

        * You don’t have to read the paper, but consider whether the maximal model is the model that makes the most sense.  How to make the maximal model.

    * [I understand mixed models - how do I set it up in lme4?](http://www.rensenieuwenhuis.nl/r-sessions-16-multilevel-model-specification-lme4/)

* Advanced

    * [Nesting and a whole bunch of information on how to set up model](http://lme4.r-forge.r-project.org/lMMwR/lrgprt.pdf)

### Functional Experiment Templates

Here are just a few templates tfhat may be helpful to build off of as you create your own online replications, with comments.

Simpler

[Survey](https://github.com/StanfordPsych254/jimorrisProject/tree/master/Projects/oed/experiment) (Similar to Qualtrics with basic functionality) (+ [PREVIEW](https://web.stanford.edu/~jimorris/Shah_2015_Rep/shahrep.html))

* When you need to present stuff page by page and have people answer questions

[Keypress Experiment based on Stimuli](http://longouyang.github.io/even-odd/docs/even-odd.html)

* When participants see stuff and respond (quickly or slowly)

More Complex

[Typing a list of things and Working Memory Task](https://github.com/longouyang/gradisar-ospan)

* Complex randomization of presenting stimuli and responding in a list to be automatically checked

[A whole lot of common research tasks](https://expfactory.github.io/)

* Made by Stanford Psych Grad students - may require a few more tools (e.g. python), so users beware
