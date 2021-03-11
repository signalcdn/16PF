<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Practical Connections: Driving Positive Outcomes through Self-Understanding
*Brett Hunt*

*DAFT January 2021 Berlin*

## Content
- [Background](#background)
- [Questions](#questions)
- [Dataset](#dataset)
- [Cleaning](#cleaning)
- [Feature Engineering](#feature-engineering)
- [Analysis](#analysis)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Workflow](#workflow)
- [Links](#links)

**MVP Description**

Ironhack's Data Analytics bootcamp consists of 8 weeks of instruction, and 1 week to complete a final project. I aim to maximize both the personal interest in my project and the subsequent value should it yield opportunity. The potential audience of this project is a recruiter, so I will acknowledge that.

**MVP Acceptance Criteria**

    **As Brett Hunt, I would like to publish a final project which I can lever into a career**
    ✅ Dataset of responses to Cattel's 16 Personality Factors Test are clustered
    ❌ 3 Testable questions are explored and answered
    ✅ I can cluster myself.

I was distracted by a product idea. I couldn't focus on the 3 testable questions. What it turned into was something that can't possibly be explained in a 5 minute presentation. Maybe 10. Discussion around this will continue throughout the readme.

**Additional Background

I took a Psychology Minor in school so that I could learn about people and how myself and others relate to one another. I have had great struggles with my identity growing up, and I still don't know how I fit into the big picture or what kind of people are actually like me. I've always wanted to survey people, but knew I was lacking both hard and soft skills required to create positive impacts with my work.

* I would like to do something with data that does not involve the gamification of a metric with consequences that are not intuitively positive (unclear or intuitively negative)
* I would like to take advantage of my speed x depth multiplier at my optimal depth (medium complexity, high flow)
* I would like to drive introspection in people, not comparison
* I would like to optimize learning to, ironically, make it brainless - Granular proximal zone of development
* I am extremely outgoing but I can't operate at my social energy level for long. Product Ownership is too draining if I end up on too much of a manager schedule.


## Questions

My initial questions were quite simple. Such as:
What factors do I value highly? What categories can I categorically eliminate people upon? What am I surprised there is alignment with?

    I will have to earmark this for future iterating and denote iterations beyond the additional scope, as a large majority of the scope creep was focused on the presentation       due to the resume connotations of winning hackshow

* What data/business/research/personal question you would like to answer?
* What is the context for the question and the possible scientific or business application?
* What are the hypotheses you would like to test in order to answer your question?  
Frame your hypothesis with statistical/data languages (i.e. define Null and Alternative Hypothesis). You can use formulas if you want but that is not required.

# Datasets
## Initial
    1. [Open Psychometrics Data](https://openpsychometrics.org/_rawdata/)
    2. Personal Test as a csv

My initial dataset came from , and came in a very clean state, with a codebook. I was seeking an interesting test which may prove useful for K-means clustering due to its multidimensionality. In our GNOD Lab Project, we had performed a similar operation using the Spotify API. It initially had n = 49159 responses.

## Additional
    1. Test Results
    2. Cluster Means

I had to manipulate the data to provide myself with some additional dataframes to perform analysis on


* Where did you get your data? If you downloaded a dataset (either public or private), describe where you downloaded it and include the command to load the dataset.
* Did you build your own datset? If so, did you use an API or a web scraper? PRovide the relevant scripts in your repo.
* For all types of datasets, provide a description of the size, complexity, and data types included in your dataset, as well as a schema of the tables if necessary.
* If the question cannot be answered with the available data, why not? What data would you need to answer it better?

# Cleaning
The data initially was solely in the form of the survey responses and had not been additionally processed. Steps taken included

    1. Respondents under 16
    2. Using response sums to determine validity
    3. Eliminating Accuracy Scores outside of the 0-100 Range
  
# Feature Engineering

  The 16 Personality Factors were then engineered and weighted using the following weights and keys.
  [16PF Key](https://ipip.ori.org/new16PFKey.htm)
    
# Analysis

I used K-means clustering to test the data and identify broad clusters based on all of the test factors. The goal here was simply to cluster.

I then imported my own manually generated test result (created using the provided codebook).
* Overview the general steps you went through to analyze your data in order to test your hypothesis.
* Document each step of your data exploration and analysis.
* Include charts to demonstrate the effect of your work.
* If you used Machine Learning in your final project, describe your feature selection process.

# Conclusion
* Summarize your results. What do they mean?
* What can you say about your hypotheses?
* Interpret your findings in terms of the questions you try to answer.

# Future Work
Address any questions you were unable to answer, or any next steps or future extensions to your project.

# Workflow
Outline the workflow you used in your project. What were the steps?
How did you test the accuracy of your analysis and/or machine learning algorithm?


## Links

[Repository](https://github.com/signalcdn)  
[Slides](https://docs.google.com/presentation/d/1R72-R39yuZX5N6m_s9TgAdZO4dB-4qyhevQ8cyn099s/edit?usp=sharing)  
[Notion](https://www.notion.so/4b480f1de32f415f942bf78e9b006bd1?v=db5d5343450045a7b9b8c934a26c86be)  
