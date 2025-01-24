**Advice for maintaining Weekly Journals**

These "weekly journals" are essentially a log of your studying activities each week outside of class, including the amount of time spent outside of class on class related materials. 

The direct intent behind this assignment is to help you reach your hours for studying for this class outside of class by keeping track of completed activities. The indirect outcome of this logging/journaling activity is for you to see how much you've learned by the end of the semester. Try to set up a routine, i.e. every Monday, Wednesday, Friday at 9am. Consistency of habit will make this go much easier. 

For purposes of this assignment, studying can be defined broadly. Some examples of relevant activities:

* Reading assignments, recommended videos and links  
* Trying out homework exercises and/or worksheets  
* Working on group presentation; meetings, research, planning, setting up a project board, etc  
* Summarizing articles, creating cheatsheet/reference sheet for yourself  
* Participating in study group discussions  
* Emailing classmate about an article, setting up a blog, organizing study groups  
* Reviewing specific software, trying new technology  
* Learning about or trying new study techniques, attending counseling center workshops  
* Completing tutorials on related topics  
* Attending Magner Career Center events, visiting the center, etc  
* Other Career Preparation activities (i.e. updating resume, working on your portfolio, updating linkedin profile, completing leetcode, etc).  
* Creating or engaging in a social media post/meme about a course topic to help you apply concepts  
* Working on a programming project related to one of the topics  
* If you think anything else is related and not listed here, feel free to ask me for approval

There are minimal formatting specifications provided. Since you're using a VCS to keep track of files, it will be okay to reorganize through the semester. In fact you most likely will reorganize as you realize better ways of keeping track of information as the semester progresses. I suggest starting with these files:

* Time log \- to track time, such as with a CSV file with these fields:    
  * Individual vs group time  
  * Categories for type activity. You may define your own categories (reading, summarizing, explaining to someone else, completing an assignment, etc)  
  * Hours estimated (budgeted) vs actualized time tracking values  
  * You may write about studying for other classes and what you learned in another class. Should you choose this approach please separate total hours for this class vs total studying overall   
* Changelog \- to track changes over time in the repository, specifically for management of the repository.  
* Study notes \- to track all topics into one collection  
  * For your future self to reference you may be interested in jotting down specific citations  
  * You may include the set of study notes you composed while studying. You may upload a separate document or keep your collection of notes in a github repository, notion, onenote, a blog, etc and link it here.  
* Reflections \- to track open-ended thoughts each week on what you feel is working vs not working, and brainstorm ideas on how to improve. See reflection prompts in the next section for ideas you can delve into.  
* Hype doc \- to track your accomplishments as evidence of growth, i.e. you explained something to a classmate to help them understand a concept. You can see some examples [here](https://alistapart.com/article/the-career-management-document/) and [here](https://developer.squareup.com/blog/you-are-your-own-best-hype-person/).

Over time you may decide to use subfolders to organize collections of files.

**Reflection Prompts:** 

* *Goals:* what were specific goals driving the motivations for your studying? What are short term goals (i.e. by the end of the semester)? What are your longer term, i.e. career goals?   
* *Time estimation:* how did you go about scheduling study time? Was it intentional time set aside or spontaneous?  
* *Tools*: which tools did you use to create notes and why? how did you structure your notes (i.e. do you use categories or tags)?  
* *Process:* do you journal once a day, once a week, other? How did you go about figuring out how to track data and organize your thoughts in writing it down? Does your draft look very different from the final submitted version, and if so why?  
* *Collaboration:* did you engage in any collaborative experiences? How did your group coordinate or communicate collaboratively?  
* *Expanding your comfort zone:* What is one new thing you learned or tried that you never tried before? How do you feel about it? Will you do it again? Did you learn something new, what was it? Will you keep diving further into that topic? How so?  
* *Highlights/Lowlights:* What was the most inspiring moment or topic from you studying in the past week(s)?  
* *Refinements*: Is there anything you'll modify in coming weeks on your goals, time estimation, tools, process, collaborative techniques?  
* *Extracurriculars:* What is something you hope to learn outside of school in the next 2 weeks?  
* *Professional network*: have you met someone new in recent weeks? how/where did you meet? talk about the experience a bit... 

**Tips**

**Recording session in terminal**

\# Linux  

`script --t=time-$(date +%F).txt -q -a script-$(date +%F).log`          	     \# records  
`scriptreplay --timing=time-$(date +%F).txt script-$(date +%F).log`     \# replays

\# Mac  
`script -r script-$(date +%F).log`         \# records  
`script -p script-$(date +%F).log`        \# replays  
