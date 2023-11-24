---
title: The short-term view of AI education over engineering
tags: education
---

A few weeks ago, I received an e-mail from the Swiss embassy for an event they were organizing.
The event would bring together current and alumni of academic exchange programs between Switzerland and North America, namely ThinkSwiss, Fulbright, and the SNSF Postdoc.Mobility: the fellowship currently funding me.  
In the invitation were also five prompts on different topics, and an invitation to propose a short essay: for each prompt, one author would have their trip sponsored and give a short talk for the event.
One of these prompts happened to be an issue our lab frequently grapples with.  

Last week, I gave the talk at the embassy. I share below the essay and talk (as near as it was given).

----
#### Prompt: Is it going too fast? Argue that artificial intelligence is/is not killing the traditional skills acquisition process.

Artificial intelligence (AI) is quickly becoming part of our everyday lives, affecting everything from the ads we see to the thermoregulation of our homes.
In many ways, this is reminiscent of how computers started as room-sized machines confined to large research or military labs, and today are in every home, pocket, and even the most mundane objects: I now need to swipe a card to open my office door.  

Indeed, the current success of AI is due primarily to the previous success of cheap and ubiquitous computing power.
Many algorithms and theoretical advances fundamental to AI today were developed in the 80s, but only became runaway successes this past decade because of the sudden availability of both big data and massive computing power.
Both of these have become available due to ubiquitous computing hardware: the massive market for computer processors and microcontrollers has driven down prices, enabled breakthroughs in distributed computing, and allowed networks of sensors that can collect more data than ever before, in a largely automated fashion.  

Yet, even as the US congress passes the 50+ billion _CHIPS for America_ bill [@1] to strengthen the domestic semiconductor industry, the Massachusetts Institute of Technology is reorganizing its Department of Electrical Engineering & Computer Science (EECS), commonly called course 6.
The department is adding a new degree in AI, and considering removing the existing degree of just Electrical Science & Engineering (EE) [@2].
For students interested in actual hardware development, the closest they can get would be a mixed EECS major, but topics such as advanced power electronics, semiconductor fabrication, etc. would eventually no longer be taught.  

Why?  

The direct reason is low enrollment: while the hardware-focused course 6.1 (EE) counts a total undergraduate enrollment of 50 in 2022, the rest of course 6 boasts 1339 [@3].
Similar trends are seen at other universities: on the other coast, UC Berkeley is limiting enrollment for "high-demand majors", as their CS faculty are overloaded [@4].
So why are so few students enrolling in hardware-focused majors?
Some may claim that hardware simply is harder, but students at these top universities are not known for avoiding difficulty.
A more subtle reason may be mainstream exposure and fame.
Big-data and AI companies (often called "FANG") are constantly grabbing headlines these days; they give out the most flamboyant swag at job fairs, pay well for internships, and offer the most perks for interns and employees.
And in the meantime, as fewer engineers are trained in hardware-focused disciplines, companies are moving their advanced production and even development (notably for semiconductors, but increasingly for other hardware as well) elsewhere.
While AI is replacing skilled labor in many areas, it is still far from replacing all of them.
At the same time, short-term demand for software developers with "AI experience" is increasingly displacing education in other disciplines, even though the long-term market for those disciplines has not changed.  

Back in Switzerland, this trend is not as extreme – yet.
Arguably, Europe has acted as a low-pass filter, and trends in America are often seen in Europe only 5-10 years later and to a lesser degree.
This gives Europe a decided advantage: in some sense, America can serve as a window into a possible future.
In Switzerland, we should be observing these trends proactively: promoting an existing course is significantly easier and more effective than trying to re-create one from scratch once it is gone.  

[@1]:https://www.congress.gov/bill/116th-congress/house-bill/7178/cosponsors  
[@2]: internal communication at MIT  
[@3]:https://registrar.mit.edu/stats-reports/majors-count  
[@4]:https://www.dailycal.org/2022/08/24/campus-college-of-letters-and-science-plans-to-limit-high-demand-majors/  

----

> I’d like to start by asking all of you a question. What are the great challenges our society will face in the next 50 years? The challenges we will have to solve in our lifetimes?
> [silence, then someone jokes about shortage of Swiss chocolate]
> In a way, yes: our challenges will invariably be about sustainability in the face of a growing population. We will need to improve sustainable agriculture to feed a growing population. We will need to develop technologies for renewable energy to satisfy the increasing demands of a growing population. Construct more buildings to house a growing population.
> AI and data science will certainly have a role to play in facing these challenges, but many of these challenges are inevitably physical in nature, and will inevitably require innovation of a physical nature.
> The reason I point this out is that, especially here in America but also at universities in Europe, there is a growing trend of training more students in software engineering, and fewer students in traditional engineering disciplines.
> I will circle back to this later, but let me take a step back and introduce myself.
> I’m currently a postdoc at MIT where I work on learning for robotics; before this I did my PhD in Germany, and my undergraduate studies at ETH Zurich. I’ve been here for a bit over a year now, and I have to admit it was a bit of a culture shock initially. One of the biggest difference for me was seeing how much MIT, as a private school, is run as a corporation. Back in Europe we’re not really used to thinking of universities as corporations, but I started to wonder, what if I thought of my alma mater, ETH, in this way? Who would be its shareholders, who would be its clients?
> Well, as a federally funded school, its shareholder is the Swiss government. And its clients is Swiss society and Swiss industry; the raison d’être of ETH, the reason it was founded, is to train scientists who can make advancements that improve Swiss quality of life, and engineers who would strengthen Switzerland’s industry.
> On the other hand, MIT’s shareholders are its board members, mostly companies who might want to recruit MIT graduates, and its customers are the students themselves. And when you’re charging upwards of 70'000 USD a year, you better believe the customer is always right.
> The reason this is important is that, because their shareholders and customers are different, these two institutions have to reason at different timescales: if you’re serving the interests of a society or industry, you have to reason at the timescale of decades. But if your customers are the students, your timescale are the few months immediately before and after graduation: did your students get their dream job, did they get that offer from the hottest companies of the moment, which currently are Google, Facebook, Amazon, or big data startups.
> I’ve been shocked how often I talk to students or recent alumns and hear that the reason they majored in Computer Science isn’t because they were passionate about it, but because the at the first Career Fair they attended as freshman, they realized that the companies offering the best paid internships and giving out the coolest swag were all recruiting software engineers.
> This is just a personal anecdote, but let’s look at some actual numbers. Of the roughly 4500 undergraduate students at MIT, nearly a third are in the joint department of Electrical Engineering and Computer Science. But of those 1400 students, only _fifty_ are studying electrical engineering.
> These numbers have not been lost on MIT corporate either. Earlier this year, a new undergraduate degree in AI was announced, although how that would be different from CS eludes me. At the same time, they also announced that the degree in electrical engineering would be removed entirely. Roughly 10 new students a year just doesn’t justify the cost of an entire degree.
> Now, it seems they got enough pushback, because this announcement was quietly taken down, but nonetheless it appears that the future of electrical engineering at MIT, one of the most prestigious technical institutions in the world, is in a precarious state. I find this rather frightening.
> Now, the lab I work in is in the department of mechanical engineering, and our numbers are not quite as bad, but they have also been shrinking. And most students are opting for a flex-degree that includes more CS courses.
> The department has decided they need to revamp the curriculum and modernize, and Sangbae Kim, the professor I work with, is part of this task force. He started by asking the other professors their opinion, and the answers generally fell into two camps.
> The older generation of professors answered by asking the same question I asked you: “what are the great challenges we will face in the next fifty years?” And after that the answer was clear. Of course, we should design a curriculum that prepares the next generation of engineers to tackle these challenges.
> The other side, often younger, untenured professors, looked instead to their customer satisfaction. And they saw that students wanted more software engineering skills, and more courses with clear, well-defined answers, where studying hard would guarantee an “A”, since that is what gets you offers from the big companies.
> And so we’re faced with a dilemma: do we design the curriculum that we believe society needs, and risk going extinct entirely as the EE department seems to be going? Or do we compromise, and keep a watered down version of the degree that more students will find appealing?
> We’re not sure how to answer this, and if any of you have thoughts, I’d love to hear them.
> And for those of you who can influence policies, I urge you: design policies so that the interests of our corporations align with the future we’d like to live in.