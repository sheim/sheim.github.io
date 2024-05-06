---
layout: post
title: PhD Take-aways
tags: advice
---

I've been asked to give some advice, now that I can suddenly be considered a wise and wordly postdoc, and no longer a stumbling, lost phd student.

## First and foremost, know why you're in the game.

Before starting a successful Ph.D. program at [MPI-IS in Germany](https://is.mpg.de/), I spent two years at [Tohoku University in Japan](http://www.cmplx.riec.tohoku.ac.jp/), first as a visiting scholar and then a Ph.D. student.
Quitting this program is the hardest decision I've made. For a long time, quitting was an option I didn't acknowledge: quitting was failing. Worse, quitting was choosing to fail.
It took a lot of reflection before I realized quitting was the only option.
_Why am I doing this?_ It wasn't to get a Ph.D., even though that is the tangible end-goal.
I had thought answer was clear: I like thinking about interesting questions.
But this clearly wasn't enough, and I eventually came up with more specific answers.
I care about working with others, with people who are good at what they do, who challenge me, and who are fun to discuss with.
I care about exploring different ideas, different tools, and different problems.
And I care about improving my immediate community.
Due to cultural differences, some of these values were simply incompatible to how work and academia played out in Japan.
It was then clear that leaving was the only way _not_ to fail in what I really cared about.  

This forced reflection served me well in my time at MPI: knowing what I care about made it easy to make choices and choose my battles confidently.
I invested time and effort into projects and also non-research activities at the institute that I believed in. At the same time, I found it easier to say "no" to projects that were promising but not aligned with my end-goal, or activities that were noble but not close to my heart.
This includes having the conviction to say "no" to your PI, which I find most students are not willing to do.
And usually, it's because they haven't figured out yet what they want to get out of this journey, so they still follow the guidance of their PI.

## Condense your research goal to one sentence.

Come up with a slogan that says what you're about, tweak it, adjust it, and make it yours.
I started out with _How to design natural dynamics that are easy to exploit?_, which came out of a common theme in the Dynamic Walking community, that controllers should exploit natural dynamics of the system.
This took many forms, but one of the early versions made it to the introduction of my actual thesis: _How can we enable robots to learn control model-free and directly on hardware?_
<!-- The reason I deliberately emphasize _model-free_ and _directly on hardware_ was to exclude optimal control as a tool: optimal control is a fantastic tool, but I wanted to focus on _robustness_. -->
Actually, I wanted to focus on robustness.
It is so tempting to recast the problem of robustness so that we can whack it with the optimal control sledge-hammer, but I felt that robustness is an inherently different problem (_note: I might be totally wrong_).
So I emphasized _model-free_ to eliminate the possibility of using optimal control, which inherently requires a model. The _directly in hardware_ clause, in similar fashion, ruled out deep learning.  

**Great reference for choosing projects**
Each time I picked out a new project, I could then check how well it fit with my overall theme.
Did it help me get closer to my actual goal? This also meant, when people asked me to help on projects (including things where I might not receive any credit), I could decide "will this experience help me get closer to my goal?".
If it didn't and I still wanted to pursue it, it was time to re-tweak this sentence.

**Makes it easier to tell your story**
This might not seem so obvious at first, but eventually you'll write a thesis where you need to relate all your projects into a coherent story.
It really helps if there actually is one. And there almost always is: it's also easier if you practice finding this story throughout your work, instead of trying to spin it at the end of your studies.
This also tends to help when writing applications.

## Fail fast

If you read my thesis, it sounds like I knew what I was doing right from the start.
I started with an open problem, explored it, wrote four papers addressing different aspects, and graduated.

<!-- During my Ph.D., I had 4 successful publications, and one project that was mostly finished by the time I finished and published shortly after. -->
I have completely lost count of the ideas I've had for "cool projects", pursued for some time, then dropping without anything concrete to show for it.
You can't make sure every idea you have is good, but you can make sure that every project you complete (and paper you publish) is worth while - and you do this by quickly identifying the ideas that aren't so great, and dropping them.
And the sooner you can drop them, the better.
Sometimes this is because the idea turns out not to work, and sometimes it just is harder than you thought, and harder than it's worth (especially if you're working on a robot controller, but the hardware isn't actually ready yet).
A key to dropping projects earlier is to _fail fast_.
This means, start with the simplest set of preliminary results you can think of that should work.
This doesn't have to be impressive in the least - it just needs to be easy and fast to test. A simple benchmark is often a good start.
And if it doesn't work, _great!_ You've just eliminated a "good" idea (especially good is if your simple test flat out refutes the idea).
Of course, sometimes it might not have worked just because you haven't tried hard enough, and having some tenacity is also important.
I don't have a straightforward recipe for deciding when to keep pushing and when to drop a project - I think it's a matter of experience.
But systematically starting projects with these simple tests is a great way to quickly get this experience.

## Share your ideas/results often and early
Why you should do this for your results is obvious. The purpose of (academic) research is to increase our understanding of the world: this does not happen if you fail to communicate your results to the broader community.  

More than this, take every chance you get to share your ideas and results, including work-in-progress and half-hashed ideas.
<!-- But I strongly encourage you to also share you work-in-progress and preliminary ideas, at every stage. -->
Evaluating how good your ideas are is difficult and unreliable; getting feedback from others is much better, and the earlier the better (see above).
Your immediate colleagues, journal club, or academic friends are the ideal people to bounce ideas off of.
A delegation of [AI grad students and profs are visiting from Sweden](https://wasp-sweden.org/)? Great, volunteer to present your work.
Workshops, summer schools, and even institute retreats are all good places to share your preliminary results on a project, especially if you think it is promising but are unsure of which direction to take it in.

Sharing your ideas forces you to organize everything you have so far in a coherent structure.

Sometimes, people will suggest something useful.
But more importantly, if you read between the lines, you'll get silent feedback on what is actually interesting and what isn't.
At Dynamic Walking 2017, less than half a year into my PhD, people politely listened while I explained my results.
But most, especially more senior people, didn't ask me about my main result: instead they asked me to explain parts of my graph that were that I had not yet fully understood, and only had vague grasp of at that time.
I eventually followed-up on these questions I could not fully answer at the time, and this became my [journal paper in Transactions on Robotics](https://arxiv.org/pdf/1806.08081.pdf).
Instead, what was then my main result eventually made it into a [small, minor conference paper](https://arxiv.org/pdf/1806.06569.pdf).


## More Advice from Wiser People

[S. Stearns and R. Huey, UC Berkeley](http://polypedal.berkeley.edu/?page_id=266#advice)

[Radhika Nagpal](https://blogs.scientificamerican.com/guest-blog/the-awesomest-7-year-postdoc-or-how-i-learned-to-stop-worrying-and-love-the-tenure-track-faculty-life/)

[Randy Pausch's Last Lecture](https://www.youtube.com/watch?v=ji5_MqicxSo)

[Patrick Winston's advice on giving a talk](https://www.youtube.com/watch?v=Unzc731iCUY&)

[Embracing Failure, Matthew Mason](https://www.youtube.com/watch?v=YJisNJ91uR0)


<!-- Continuously question yourself on this; the more specific your answer, the easier you'll be able to navigate pitfalls later on.
As I was finishing my master thesis, back in 2014, the answers were obvious.
I get to come up with interesting problems to work on.
I have freedom to choose how I spend my time.
I'm good at it.
<!-- I love what I'm doing: I get to come up with problems and work on them just because I think they are interesting, I enjoy the freedom that academia gives you, the student lifestyle, and I seem to be rather good at it. -->
<!-- I'm not brilliant, but I have a knack for the game.
Then I moved to Japan, to a [whacky lab](http://www.cmplx.riec.tohoku.ac.jp/) that built robots and kept a menagerie of animals (all invertebrates to avoid dealing with bureaucracy, which is a win in my book).
And I had to question everything again. _Why was I here?_
I was miserable and getting nowhere.
I was given plenty of freedom to choose my topic, but I couldn't work with anybody.
And every time I tried to 
I was given plenty of freedom to choose my topic, but I was miserable and getting nowhere. -->