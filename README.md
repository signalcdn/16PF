<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>


**DAFT January 2021 Berlin**
# Practical Connections: Driving Positive Outcomes through Self-Understanding
**Brett Hunt**

## Content
- [MVP](#mvp)
- [Questions](#questions)
- [Data](#data)
- [Cleaning](#cleaning)
- [Feature Engineering](#feature-engineering)
- [Analysis](#analysis)
- [Conclusion](#conclusion)
- [MVP Next Steps](#mvp-Next-Steps)
- [Links](#links)

## MVP

Ironhack's Data Analytics bootcamp consists of 8 weeks of instruction, and 1 week to complete a final project. I aim to maximize both the personal interest in my project and the subsequent value should it yield opportunity. The potential audience of this project is a recruiter, so I will acknowledge that. If you're hiring me, you're going to want to know how I work and think, because I'm going to be doing a lot of it. 

I am a generalist extreme, and a Maven, as described in Malcolm Gladwell's ***Tipping Point***
      
      Mavens not only collect information, but they also enthusiastically share their knowledge with other people.
      
My career thus-far has consisted of a serious passion in psychology, a trip through product in the world of esports, and a few internships. People can only stay on the cusp of a limited amount of specialization, and I manage to cast both a wide net and travel with grace navigating its contents and connecting it.

**MVP Acceptance Criteria**

***As Brett Hunt, I would like to publish a final project which I can lever into a career (and I have a week to do it)***
    
    ✅ Dataset of responses to Cattel's 16 Personality Factors Test are clustered
    ❌ 3 Testable questions are explored and answered
    ✅ I can cluster myself.
    

**Additional Background**

I took a Psychology Minor in school so that I could learn about people and how myself and others relate to one another. I have had great struggles with my identity growing up, and I still don't know how I fit into the big picture or what kind of people are actually like me. I've always wanted to survey people, but knew I was lacking both hard and soft skills required to create positive impacts with my work.

* I would like to do something with data that does not involve the gamification of a metric with consequences that are not intuitively positive (unclear or intuitively negative)
* I would like to take advantage of my speed x depth multiplier at an optimal depth (medium complexity, high flow)
* I would like to drive introspection in people, not comparison
* I would like to optimize learning to, ironically, make it brainless - Granular proximal zone of development
* I need to be on a [maker's schedule.](http://www.paulgraham.com/makersschedule.html) I am extremely outgoing but I can't operate at my social energy level for long. Product Ownership is too draining if I end up on too much of a manager schedule. 


## Questions

My initial questions were quite simple. Such as:

* What factors do I value highly? 
* What categories can I categorically eliminate people upon? 
* What am I surprised there is alignment with?

I will have to earmark this for future iterating (if done) and denote iterations beyond the additional scope, as a large majority of the scope creep was focused on the presentation due to the resume connotations of winning hackshow. 

# Data
## Initial

My initial dataset came from , and came in a very clean state, with a codebook. I was seeking an interesting test which may prove useful for K-means clustering due to its multidimensionality. In our GNOD Lab Project, we had performed a similar operation using the Spotify API. It initially had n = 49159 responses.

   1. [Open Psychometrics Data](https://openpsychometrics.org/_rawdata/) ---- [Codebook](link)
   2. [personal_test.csv](link)


## Additional

I had to manipulate the data to provide myself with some additional dataframes to perform analysis on.
   1. [Test Results](link)
   2. [Cluster Means](link)
I then imported my own manually generated test result (created using the provided codebook).

## Cleaning
The data initially was solely in the form of the survey responses and had not been additionally processed. Steps taken included

    1. Respondents under 16
    2. Using response sums to determine validity
    3. Eliminating Accuracy Scores outside of the 0-100 Range
  
## Feature Engineering

  The 16 Personality Factors were then engineered and weighted using the following weights and keys.
  [16PF Key](https://ipip.ori.org/new16PFKey.htm)
    
## Analysis

📊 [Analysis](https://github.com/signalcdn/16PF/blob/main/Analysis.ipynb)

## Product Presentation

🖥[Slides](https://docs.google.com/presentation/d/1R72-R39yuZX5N6m_s9TgAdZO4dB-4qyhevQ8cyn099s/edit?usp=sharing)  


# Conclusion

Let's revisit the Acceptance Criteria:

    ✅ Dataset of responses to Cattel's 16 Personality Factors Test are clustered
    ❌ 3 Testable questions are explored and answered
    ✅ I can cluster myself.

1. Clustering worked but was not strong
2. I got focused on the product idea, a small step towards real world value > random analysis.
3. I was placed in Cluster 3.

I don't believe that there is much value in continuing analysis on this specific dataset beyond this project. Beyond the next steps that could be performed on this data; refactoring code or improving visualisations, or building a pipeline that allows people to input their own test and receive results, I believe that the highest priority next step is to try to build a real MVP of what was outlined in the presentation.

I believe I did come out of this project with the desired outcome. A renewed lease on my career aligning with lingering loose-ends of passions. 

## MVP Next Steps
**Survey**
* Target would be 50 people from 20 different online communities for an initial dataset
* Questions would need to be added to prevent bots or flag potential fake responses - There is research and like best practice on survey validity here

* Basically my entire presentation is a summary of my ideas that was compressed into a 5 minute package.
* Research will need to be done on legality, security, and other relevant topics should this idea evolve.

## Product Notes
* The Clusters are representative of any potential sample or subsample

* Data Collection creates a flywheel effect wherein the data becomes more useful the more diverse it becomes

* The project, should it be a nonprofit. Lack of data sale drives willingness to use  with it becoming more useful the more people participate

## Career Steps

1. Interviewing practitioners and experts

	I need to interview practictioners and experts to see where and when psychological testing is and isn't useful, and seek out additional ways to derive value from obtained data.
	
2. Gaining additional skills and experience
	
	I need to target a role which processes and analyses related (mental health or survey) data to build up experience, skills, and a network of thought-aligned friends. I took this data analytics bootcamp so that I could give myself the hard skills to act upon just such an idea, but I don't believe that I am ready yet. Alberta Health's [Brain Story Certification](https://www.albertafamilywellness.org/training) will be the first.
	
	
3. Ponder whether I want to live the life of a CEO.
	
	I'm serious.

## Links

[Repository](https://github.com/signalcdn)  
[Slides](https://docs.google.com/presentation/d/1R72-R39yuZX5N6m_s9TgAdZO4dB-4qyhevQ8cyn099s/edit?usp=sharing)  
[Notion](https://www.notion.so/Project-Scoping-603005eb016640909b149a1603844ed2)  
