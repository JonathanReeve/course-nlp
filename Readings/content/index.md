---
title: Natural Language Processing, Fall 2021
author: Jonathan Reeve
date: 2021-04-14
---

Welcome! Here you'll find all the course information for Natural Language Processing, a course taught at Columbia University in Fall 2021. Please read this syllabus completely.

## Course Details 

  - STAT 1234: Natural Language Processing 
  - Department of Statistics, Columbia University
  - Instructor: Jonathan Reeve
  - Discussion sections: 13:00–14:00, New York City time, [in the course chatroom on Zulip](https://nlp2021.jonreeve.com)
  - Lab time: Fridays, 14:00-15:00, [in live video chat on Jitsi](https://meet.jit.si/nlp2021)
  - Email address: jonathan.reeve@columbia.edu 
    - Although please message me on Zulip instead
  - [Classroom/chatroom on Zulip](https://nlp2021.zulipchat.com/)
  - [Course website and course readings](https://nlp2021.jonreeve.com)
  - [Course repository](https://github.com/JonathanReeve/course-computational-literary-analysis)

[Get Started!](#getting-started)

## Description

This course is an introduction to statistical natural language processing, with no computer programming prerequisites. We will learn the basics of the Python programming language in parallel with techniques of computational text analysis, such as topic modeling, stylometry, authorship detection, and word embeddings. 

We will attempt to answer questions such as:

  - Which US president had the largest working vocabulary? 
  - What are the characteristic speech patterns of the narrators in Wilkie Collins's *The Moonstone*?
  - Which novels of the nineteenth century are the most similar to each other? Which are the most different?

## Objectives

Although this course is focused on the analysis of literature, and British literature in particular, the skills you will learn may be used to computationally analyze any text. These are skills transferable to other areas of the digital humanities, as well as computational linguistics, computational social science, and the computer science field of natural language processing. There are also potential applications across the humanistic disciplines—history, philosophy, art history, and cinema studies, to name a few. Furthermore, text- and data-analysis skills are widely desired in today's world. Companies like Google and Facebook, for instance, need ways to teach computers to understand their users' search queries, documents, and sometimes books. The techniques taught in this course help computers and humans to understand language, culture, and human interactions. This deepens our understanding of literature, of our fellow humans, and the world around us.

## Prerequisites

This course presumes no prior knowledge of programming, computer science, or quantitative disciplines. Those with programming experience, however, won't find this boring: the level of specialization is such that only the first few weeks cover the basics.

### Lecture Videos

In place of in-person lectures, I'll post lecture videos, every Wednesday, or earlier. Each video is between 30-70 minutes long, and is required viewing. Please watch the lecture videos before coming to discussion sections, so that we can all discuss it synchronously. Links will be posted to this syllabus. **Please resist the urge to watch lecture videos in advance, since they may change as I revise the course content.**

### Discussion Sections

In place of in-person classroom dialogue and activities, we'll hold discussion sections online, on [this Zulip server](https://nlp2021.zulipchat.com/), every Wednesday during class time, from 13:00–14:00. Zulip is a text-based chat platform, with email-like threading. You can use it to join an existing discussion thread, or create a new one. Please familiarize yourself with Zulip ahead of our first meetings. 

Attendance in these discussions is required. If you need to participate asynchronously one week, for whatever reason, just let me know in advance (on Zulip).

As in a traditional classroom, some days you will want to speak (i.e., write in the chatroom) more than others, and that's fine. But please say something thoughtful **at least once per class**. This way there is a record of your participation.

### Course Communication 

Feel free to chime in on the course chat throughout the week, with any questions or comments you might have. I'll usually be there once every couple of days. Please use the public channels for any course-related questions you have, unless they are of a private nature (e.g., grades), in which case please message me privately on Zulip, as I will answer faster there than through email. Discussion about specific textual passages might be better placed in annotations, in the margins of the text, using our annotation platform. See [Annotations](#annotations), below. 

### Labs

These are synchronous videoconferences that happen every week, on Friday, from 14:00--15:00, [here on Jitsi](https://meet.jit.si/ComputationalLiteraryAnalysis). They are less formal than the discussion sections, and an ideal place to come and chat about the readings and/or programming assignments in real time. I recommended you attempt the homework assignments before coming, so that you can ask any questions you have about them during the lab. You're also welcome to join and just quietly work for the hour. I won't take attendance, but these labs are strongly recommended. 

## Getting Started

To get set up for this course, you will need:

  - Access to a computer that runs Linux, MacOS, or Windows.
  - An Internet connection. I've tried my best to make our course software work as globally as possible, but if you're attending class remotely, from a country that has restricted Internet, you might want to look into setting up a VPN, either through the university, or through a private provider. Please get in touch as soon as possible if you run into any connectivity issues.

Now that we have that, let's get started! First, let's set up a couple of accounts:

1. Create an account on [our Zulip chatroom](https://nlp2021.zulipchat.com/). **Please use your real/preferred name as your username and display name, so that I can identify you.**
2. Complete your profile on Zulip. Please add a picture of yourself, and fill out all the profile fields.
3. Introduce yourself to everyone in the chatroom. 
4. Sign up for a user account on [hypothes.is](https://hypothes.is), our annotation platform. **Please use the same username you used for Zulip.**
5. Download and install [Anaconda](https://www.anaconda.com/products/individual), a Python distribution, which contains a lot of useful data science packages.

## Extra Resources

You will likely need some extra help at some point. Don't worry. That's totally normal. 

### Programming Resources

If you want some extra help, or want to read a little more about some of the things we're doing, there are plenty of resources out there. If you want a second opinion about a question, or have questions that we can't answer in the chatroom, a good website for getting help with programming is [StackOverflow](https://stackoverflow.com). Also, the Internet is full of Python learning resources. One of my favorites is [CodeCademy](https://codecademy.com), which has a game-like interactive interface, badges, and more. There's also the fantastic interactive textbook [How to Think Like a Computer Scientist](https://runestone.academy/runestone/books/published/thinkcspy/index.html), which is the textbook for *Computing in Context,* the introduction to Python at Columbia's Computer Science department.

Resources related to text analysis include, but are by no means limited to:

  - [The NLTK Book](http://www.nltk.org/book/)
  - [My introduction to text analysis tutorial](https://github.com/JonathanReeve/dataviz-workshop-2017)
  - [My advanced text analysis tutorial with SpaCy](https://github.com/JonathanReeve/advanced-text-analysis-workshop-2017)

A colleague and I have also put together a few guides for beginning programming: 

 - [Common Error Messages and How to Fix Them](https://github.com/JonathanReeve/course-computational-literary-analysis/blob/master/Resources/errors.md)
 - [A glossary of frequently used Python terminology](https://github.com/JonathanReeve/course-computational-literary-analysis/blob/master/Resources/frequently_used_terms.md)

## Requirements

Coursework falls into three categories:

  - Weekly Notecards and Discussions (40% of final grade)
    - Thus: 20% notecards, 20% class discussions. 
  - Homework Assignments (30% of final grade)
  - Final Project (30% of final grade)

And of course, there are three course readings: one novel and two short story collections. Reading these closely is crucial: this will allow you to contextualize your quantitative analyses, and will prepare you for the close reading tasks of the final paper.

### Readings

 - Manning, Christopher. /Foundations of Statistical Natural Language Processing/. MIT Press, 1999. 
 - Bird, Stephen, et al. /Natural Language Procssing with Python/. <http://www.nltk.org/book/>

### Notecards

For each reading assignment, please write a short notecard with your response to the reading. Good notecards are: 

  - Concise (think: a long tweet)
  - Well-written (although not too formal)
  - Observant (rather than evaluative)

### Homework

Four short homework assignments, of 3-15 questions each, will be assigned, and are due the following week, before our discussion starts. Jupyter notebook templates for each will be provided. **Since we'll review the homework answers at the beginning of each week, late work cannot be accepted**. Please submit homework assignments on CourseWorks. If you're auditing the course, or not yet in the course roster, just email me your homework notebook.

Feel free to consult with others, on Zulip, for hints or directions for homework problems. Just don't share any answers, and make sure that your work is ultimately your own.

### Final Project

The final project should be a short essay, created from the application of one or more of the text analysis techniques we have learned, toward the analysis of a text or corpus of your choosing. Should you choose to work with a text or corpus other than the ones we've discussed in class, please clear it with me beforehand. Your paper should be a single Jupyter notebook, including prose in Markdown, code in Python, in-text citations, and a bibliography. A template will be provided. The length, not including the code, should be about 2,000 to 3,000 words (I provide [a script you can use to count your words](https://github.com/JonathanReeve/course-computational-literary-analysis/blob/master/Resources/wordcount.py)). You're allowed a maximum of three figures, so produce plots selectively.

During the final week of class, we'll have final project presentations. Your paper isn't required to be complete by then, but you'll be expected to speak about your project for 4 minutes. Consider it a conference presentation.

Final papers will be evaluated according to the:

  - Quality of the argument presented
  - Quality of the close readings of the text or corpus
  - Quality of the Python text analysis
  - Integration of the computational analysis with the argument

As with homework, please submit these on CourseWorks, or email them to me if you don't have access to CourseWorks. You may optionally submit your final project to the course git repository, making it public, for a 5% bonus.

[For a more thorough set of recommendations and instructions for the final project, see the final-project-instructions.md file in the course repository.](https://github.com/JonathanReeve/course-computational-literary-analysis/blob/master/Resources/final-project-instructions.md)

# Schedule

Note: this schedule is subject to some change, so please check the course website for the most up-to-date version.

## Week 1, 2020-09-09: Course Intro.

  - [Lecture 1: Introduction.](https://us.tv/videos/watch/0c8e453b-18ce-4ceb-b622-2ac81011ce3d)
  - [Lecture 2: Getting Started](https://us.tv/videos/watch/ac6f30c0-1336-4ea0-8463-83f34855e58f)
  - Read the syllabus in full. 
  - Complete the steps in the section "Getting Started," above.

## Week 2, 2020-09-16: Python Basics

  - [Lecture 3: String Methods and For Loops](https://us.tv/videos/watch/807b10f3-e40a-4fd0-ada0-b849cecb8b11)
  - [Lecture 4: If, Lists, Dictionaries](https://us.tv/videos/watch/88b2a638-b10b-4880-bc25-3b7368679a3d)
  - Reading: Manning Ch. 1

## Week 3, 2020-09-23: Text Analysis Basics

  - [Lecture 5: Working with Files](https://us.tv/videos/watch/45d9ff42-5122-4ece-a778-b2c1241a8afa)
  - [Lecture 6: Introducing the NLTK](https://us.tv/videos/watch/af7600f0-8f0e-4d04-bd8f-65053e4f66af)
  - Reading: Manning Ch. 2
  - [Homework 1 assigned.](https://github.com/JonathanReeve/course-computational-literary-analysis/blob/master/Homework/Yourname-HW1.ipynb)

## Week 4, 2020-09-30: Working with Words

  - [Lecture 7: Stems, Lemmas, Functions](https://us.tv/videos/watch/d6f4351c-e1e8-4eac-a83b-55e882ea50e4)
  - Reading: Manning Ch. 2
  - **Homework 1 due**

## Week 5, 2020-10-07: Word Frequencies

  - [Lecture 8: Types, Tokens, Counting Words](https://us.tv/videos/watch/15ea8d80-1a38-4a04-bbe4-36f793899147)
  - [Lecture 9: Pandas for Word Frequency Analysis. Distinctive words.](https://us.tv/videos/watch/8af751af-51dc-44f3-82e9-e4f0df49a9b9)
  - Reading: Manning Ch. 3

## Week 6 2020-10-14: Lexical Techniques

  - [Lecture 10: Narrative Time Analysis and N-Grams](https://us.tv/videos/watch/2c9850e7-c674-4ccc-89b6-a126b3653808)
  - [Lecture 11: WordNet and WordNet-Based Analysis](https://us.tv/videos/watch/43e864f3-455b-41f3-a10f-db2a697ab6e4)
  - Reading: Manning Ch. 4
  - [Homework 2 Assigned](https://github.com/JonathanReeve/course-computational-literary-analysis/blob/master/Homework/Yourname-HW2.ipynb)

## Week 7 2020-10-21: Syntactic Analysis

  - [Lecture 12: POS cont'd. Corpora.](https://us.tv/videos/watch/c02e002e-013e-4333-a785-5db7508fec71)
  - Reading: Manning Ch. 5
  - **Homework 2 due**


## Week 8 2020-10-28: Corpus Linguistics

  - Reading: Manning Ch. 5
  - [Lecture 13: Corpora continued. Scikit-learn.](https://us.tv/videos/watch/32f6b7e5-b882-4ad8-bac7-c084b4afb30d)
  - [Lecture 14: Stylometry, Corpus-DB](https://us.tv/videos/watch/052b57d0-08d6-4908-ae6a-92fb448c7738)
  - [Homework 3 assigned.](https://github.com/JonathanReeve/course-computational-literary-analysis/blob/master/Homework/Yourname-HW3.ipynb)

## Week 9 2020-11-04: Text Categorization: Naive Bayes Categorizers

  - [Lecture 15: Text Categorization.](https://us.tv/videos/watch/dfc972c8-8b31-4312-a509-fcf98faa764a)
  - Reading: Manning Ch. 6
  - **Homework 3 due**

## Week 10: 2020-11-11: Probabilistic Approaches

  - Reading: Manning Ch. 7
  - [Lecture 17: SpaCy and Named Entity Recognition](https://us.tv/videos/watch/de141ebc-7107-460b-8b08-2028d87d0c2f)
  - [Lecture 18: Sentiment Analysis and Macro-Etymological Analysis](https://us.tv/videos/watch/dfc8dc0f-c7f0-4761-b176-425cbd8b27c3)
  - [Homework 4 assigned.]()

## Week 11 2020-11-18: Syntactic Analysis II

  - Reading: Manning Ch. 8
  - [Lecture 19: Sentence Structure Analysis Using SpaCy](https://us.tv/videos/watch/3685dcb2-1bc2-4618-b227-7ad00fb811b4)
  - **Homework 4 Due**

## Week 12 2020-12-02: Graph (Network) Analysis

  - [Lecture 20: Social Network Analysis](https://us.tv/videos/watch/f0d5cd5c-e162-4c0b-ac4a-1c59bc36c1f0)
  - Reading: Manning Ch. 9

## Week 13 4.1 2020-12-09: Final Project Presentations, and Wrap-Up 

  - Final project presentations due. See [final-project-instructions.md](https://github.com/JonathanReeve/course-computational-literary-analysis/blob/master/Resources/final-project-instructions.md) 
  - Reading: Manning Ch. 10

## Finals Week: 12-16

 - Final projects due, on CourseWorks. See [final-project-instructions.md](https://github.com/JonathanReeve/course-computational-literary-analysis/blob/master/Resources/final-project-instructions.md) 
