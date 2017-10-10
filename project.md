---
layout: page
title: Replication Project
---

This course follows the model described in Frank & Saxe (2012) and Hawkins, Smith et al. (in press): we will be doing replications of recent published papers of interest in order to provide independent, converging evidence for the reproducibility of the scientific literature. The hope is that student projects will lead to broadly-useful knowledge about the viability of published results in an online context.

The final project for this course will be a high-quality, web-based replication of a single experiment from a published paper. Your goal will be a replication report, using the Open Science Collaboration replication template for the final writeup.

**Final projects are due Friday 12/15.**

## Project Choice

For your final project in Psych 251, you will be conducting a replication of a published experimental result. We would like this project to be a result that is related to your own research program: Conducting it should give you insight into the methods, analyses, and challenges involved in doing research on a topic of interest. But you should also make sure that the methods involved are appropriately challenging. This means not choosing a difficult, reaction-time based paradigm if you have never programmed in JavaScript; but it also means pushing beyond simple survey paradigms if you are a more experienced programmer.

The default project for the course will be a web-based replication (using Amazon Mechanical Turk) of a result from the journal Psychological Science in the 2015 or 2016 volume. But you may deviate from this model (with justification) in a variety of ways:

* You may choose a paper outside of this sample if it is more relevant to your own work,
* You may choose to use a non-Turk sample, e.g. Psych1 undergraduate participants or preschoolers at Bing Nursery School, and
* You may choose to do a full reproduction of a complex analytic pipeline using existing data.

Please chat with us if you intend to do a project of this sort.

To complete your project proposal:
* Choose a paper to replicate and one experiment from this paper.
Establish a project repository in the class github organization with a name corresponding to your project’s shortcite (last name of first author)(year), e.g. smith2016.
* Put the PDF in a directory called `original_paper` in your repository
* Make a directory in your repository called `writeup.`
* In that directory, put a markdown named `project_proposal.md` file. Use all the markdown formatting conventions that you learned in class.
* Add a `.gitignore` file to ensure you don’t add future files that don’t need to be there (See example [here](https://docs.google.com/document/d/1m1i0gf_VrGGpQA6GqwIoyak_8cLj09syi7H93-Ivpgk/edit) and a brief overview in PS1 Section 7).
* But oh no!  Now your `original_paper/Smith2016.pdf` isn’t showing up when you try to add it!  Update the `.gitignore` to say, “That one pdf is okay to commit.”
* Commit the repo.
* Send a link to the instructor listserv. Put the link to your repo markdown file on github, so we can see the rendered version. Subject should be “Psych 251 Project Proposal.""

Your project proposal should contain:
* A short justification for your choice of experiment in terms of your research interests or research program (1 paragraph). This justification should tell us why you chose this particular result -- this section is especially important if you are choosing a result outside of the standard.
* A description of the stimuli and procedures that will be required to conduct this experiment, and what the challenges will be (1-2 paragraphs).

If you have concerns about your project or aren't sure if it will be doable within the framework of the quarter, please talk to the instructor or a TA before the proposal is due!

**Project proposals are due 10/8.**

## Midterm Presentations

Midterm presentations will be 5 minutes plus 2 minutes for questions.

You should make slides using Google Slides and put them in [this folder](https://drive.google.com/open?id=0B49TdRlL2Z3Eb0t5M001M2oyWlk).

You should probably have slides that cover:
1. Background
2. Experimental Design
3. Previous Data
4. Your implementation
5. Either your pilot data or the challenges you are facing in getting pilot data.

Remember, this is a good time to pose challenges to the class so you can get feedback.

Please practice your presentation several times with a timer so that you know you can complete it in the allotted time.

## Project Templates


## Final Presentations

Final presentations will be 6 minutes plus 4 minutes for questions.

Slides go in [this folder](https://drive.google.com/open?id=0B49TdRlL2Z3EbzVNc1RwTGlob00). They should be an update of what you've done before, with some of the intro compressed so you can share what you've learned via your piloting and (hopefully) what your results are.


## Emailing for Materials

Here's our author contact email. Please send a *draft* to the instructor list and we will edit/approve for sending. Before you send your draft, *check twice* that you don't have any unfilled blanks!
\
> Dear [Dr. / Professor / Title / etc.] Corresponding Author,
>
> I’m writing to ask if you would be willing to share your experimental materials from "Title" in Author1 & Author2 (Year, Journal). Specifically, I would like to request the XYZ, XYZ, and XYZ.
>
> I’m interested in your findings because … , so I chose to do a direct replication of your study as part of a graduate course, Psych 254, "Laboratory Methods in Experimental Psychology" at Stanford. I will be replicating your experiment on Amazon Mechanical Turk (mturk.com). [I know this is a deviation from the original population you tested, and I will to note this sample decision prominently in the writeup.] As I am attempting as faithful a replication as possible, any advice or insights on experimental design that I might not gather from the original article [and supplement] would be very appreciated.
>
> Just to give you a sense of my timeline, I only have a couple of weeks to re-implement your study and then my final project is due in mid-March. Once I have a version of my experiment set up, I’ll share it with you, just in case you have specific comments or concerns (though there’s of course no expectation that you respond or do a full review of the project).
>
> Thanks again,
>
> Your name
>
> Signature
>
> PS: If you have any questions or concerns about this course project, feel free to contact me or the instructor, Michael Frank (mcfrank@stanford.edu).

## Emailing for Feedback

As with the previous email, please send a draft to the instructor team to be reviewed, with all customizations.

> Dear [Dr. / Professor / Title / etc.] Corresponding Author,
>
> [Thanks for your response earlier to my queries about the materials for your study, / I’m emailing about your study] "Title" in Author1 & Author2 (Year, Journal). I’m writing to share a mock-up of a replication of [Study 1a] as part of a graduate course, to see if you have any comments or concerns that you’d like to share.
>
> Here’s a link. Any insights you have into details that differ from your own study would be much appreciated. [I will be piloting this paradigm in the next week, so I may also change some small details after collecting those data.]
>
> [I’m interested in your findings because … , so I chose to do a direct replication of your study as part of a graduate course, Psych 254, "Laboratory Methods in Experimental Psychology" at Stanford. I will be replicating your experiment on Amazon Mechanical Turk (mturk.com). [I know this is a deviation from the original population you tested, and I will to note this sample decision prominently in the writeup.] As I am attempting as faithful a replication as possible, any advice or insights on experimental design that I might not gather from the original article [and supplement] would be very appreciated.]
>
> In addition, for my project, I need to preregister a “key statistical test” from your manuscript. The idea is that this is the test that most closely corresponds to the primary hypothesis. For your experiment, I chose [give test details, e.g. “the unpaired, two-tailed t test comparing the experimental and control groups”]. Please let me know if you think this is appropriate or if there is another test that you would consider closer to being the key one for your interpretation.
>
> Of course, please feel no obligation to respond. I just wanted to be sure you had a chance to provide any comments if you wanted. Due to the quick timeframe of our course, it would be wonderful to get your feedback by [A WEEK LATER OR SUITABLE DATE], so I can incorporate your comments into the design and pre-registration.
>
> Thanks again,
>
> Your name
> Signature
>
> PS: If you have any questions or concerns about this course project, feel free to contact me or the instructor, Michael Frank.
