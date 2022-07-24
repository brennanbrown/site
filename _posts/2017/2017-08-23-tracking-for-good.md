---
id: 81
title: Tracking for Good
date: 2017-08-23T15:06:38+00:00
author: Brennan K. Brown
layout: post
guid: https://lastremark.wordpress.com/2017/08/23/tracking-for-good/
permalink: /tracking-for-good/
categories:
  - Blogging
tags:
  - Data Science
  - Life Lessons
  - Programming
  - Quantified Self
  - Writing
---

<figure class="wp-caption">

<img data-width="1395" data-height="910" src="https://cdn-images-1.medium.com/max/1200/1*msA1AjNO4voXDSvciwbeHA.png" /> <figcaption class="wp-caption-text"><b>Top Left: Total Productive Hours | Top Right: Total Miles Travelled | Bottom Left: Total Blog Posts | Bottom Right: Total Duolingo EXP</b></figcaption></figure>

#### What I’ve learned using Beeminder religiously for a month.

<span>F</span>or roughly the past thirty days or so, I have been experimenting on myself. I’ve attempted to diligently track aspects of my life. This has been me eating my own dog food, sort to speak — living the sort of quasi-motivational life that is feel-good on an abstract level. This is a case study, and these are my thoughts and results.

_This is an update to my previous article:_

<https://medium.com/@brennanbrown/planning-better-e0d60edbe271>

<!--more-->

#### I. Initial Problems of Self-Tracking

While I have been a fan of self-quantification for several years, I haven’t ever taken a deep plunge into it. There are a few reasons for this:

_Forewarning: I am not well-versed in data science, theses are just things I’ve discovered — the hard way — by taking a look what has and hasn’t worked for me._

1. <b>Bad Datasets</b>. It takes a deep understanding of yourself and what tools you actually use throughout your day to know what metrics you should be keeping track of. (_Eg._ I failed tracking my to-do list on <a href="https://en.todoist.com/app?lang=en" target="_blank" rel="noopener noreferrer"><em>Todoist</em></a>\_ — _only because I realized that I’m the kind of person that can only work well with my tasks on paper.)
2. <b>Lack of Meaning.</b> Similarly, there has to be good reason to track what you track — there has to be some sort of beneficial help that tracking gives. A strong and value-based purpose will give motivation to keep regularly tracking.
3. <b>Lack of Deterrent/Encouragement</b>. There should be an inherent penalty for _not_ doing something you want to track, and a reward _for_ doing it.
4. <b>Lack of Automation</b>. For the most part, my datasets are collected with APIs or <a href="https://ifttt.com/discover" target="_blank" rel="noopener noreferrer"><em>IFTTT</em></a>, or have very simple and fast manual input. Data collection shouldn’t be a chore.
5. <b>Inconsistent Data</b>. What you track has to be something that produce data on a consistent basis. If it’s too frequent, and you’ll end up too focused on tracking itself. If it’s too infrequent, you’ll end up forgetting about tracking at all.

All of these points are why I’ve discovered <a href="https://medium.com/u/e60c422184be" target="_blank" rel="noopener noreferrer">Beeminder</a> to work so well for self-quantification. For the most part, the application does all the tracking for you. All you have to do is the _work._ Beeminder works as a sort of <a href="http://jamesclear.com/keystone-habits" target="_blank" rel="noopener noreferrer">keystone habit</a>, in that if you can get yourself into the habit of checking-in on Beeminder, you can use it as a starting point for any other habit you want to change or begin.

#### II. The Tao of Bees

1. <b>Figure out what you want to change in your life.</b> All self-quantification tracking should initially begin with this. A solid purpose is everything.  
   Example 1. _I want to write more._  
   Example 2. _I want to be more physically active._
2. <b>Figure out meaningful quantification of that qualitative goal.</b> Don’t let ambiguity allow you to slip — put an exact number on what you want to accomplish.  
   Example 1. _I want to write 100,000 words in a year._  
   Example 2. _I want to run/walk 500 kilometres in a year._
3. <b>Convert your qualitative goal into a daily system.</b> Those goals above may seem daunting but they’re actually a lot more achievable when you break them down.  
   Example 1. _100,000 words / 365 days ≈ 275 words per day_  
   Example 2. _500 km / 365 days ≈1,800 steps per day_
4. <b>Figure out how to track this new daily system.</b> There are plenty of apps and tools out there for specific metrics, usually with well-established APIs that allow for data to be transferred and charted easily.   
   Example 1. _Utilize_ <a href="https://draftin.com" target="_blank" rel="noopener noreferrer"><em>Draft.in</em></a> _to sync daily word count on Beeminder._  
   Example 2. _Utilize a multitude of_ <a href="http://www.active.com/fitness/articles/17-best-health-and-fitness-apps-of-2017" target="_blank" rel="noopener noreferrer"><em>fitness apps</em></a> _and_ <a href="https://www.wareable.com/fitness-trackers/the-best-fitness-tracker" target="_blank" rel="noopener noreferrer"><em>wearables</em></a> _to sync daily step count on Beeminder._

#### III. What I’m Tracking

<a href="https://www.beeminder.com/brennanbrown/gratitude" target="_blank" rel="noopener noreferrer"><strong>Gratitude</strong></a>: I simply write out one thing a day that I’m grateful for, and go through every previous data point to see what I’ve been grateful for in the past. A great benefit from having this be manual input is that it doubles as a daily check-in for me to my other Beeminder goals.

<a href="https://www.beeminder.com/brennanbrown/writing" target="_blank" rel="noopener noreferrer"><strong>Writing</strong></a>: Another manual input, this being the amount of words I write per day, with each data point specifying what exactly I was mostly writing about. Usually either just daily journal writing or blog posts.

<a href="https://www.beeminder.com/brennanbrown/blogging" target="_blank" rel="noopener noreferrer"><strong>Blog Posts</strong></a>: Tracks the number of posts I upload to Medium. Unlike other activities, I retroactively added all of my older posts from Medium, and having that data in front of me really showed me how I really need to start publishing more.

<a href="https://www.beeminder.com/brennanbrown/productivity" target="_blank" rel="noopener noreferrer"><strong>Productive</strong></a><b>/**<a href="https://www.beeminder.com/brennanbrown/distraction" target="_blank" rel="noopener noreferrer"><strong>Unproductive</strong></a> **Time:</b> Both of these are tracked via the time-logger RescueTime. I try to get a certain amount of productive work done each day, whether it’s writing, or programming, or reference/learning. I also try to limit the amount of time I waste on mindless and fruitless activities.

<a href="https://www.beeminder.com/brennanbrown/fitness" target="_blank" rel="noopener noreferrer"><strong>Fitness</strong></a>: Tracks the number of miles I travel, whether it’s walking, running, or biking. I’m using _Runkeeper_ to track this, no fancy wearable. It doesn’t count all of my travelling, only when I specifically log an activity, which also gives me a GPS map of my route so I can see where I’ve gone that day.

<a href="https://www.beeminder.com/brennanbrown/github" target="_blank" rel="noopener noreferrer"><strong>Programming</strong></a>: Tracks the number of commits I push to GitHub (and other contributions like issues reported and pull requests). I admit this isn’t the best thing to track, as code shouldn’t be committed until it’s reached a point where it’s suitable to be deployed, but I’m currently working on <a href="https://flatironschool.com/" target="_blank" rel="noopener noreferrer"><em>Flatiron School</em></a>’s curriculum, which automatically pushes my assignment labs to my GitHub account, which is pretty cool.

<b>Social Media (**<a href="https://www.beeminder.com/brennanbrown/tweets" target="_blank" rel="noopener noreferrer"><strong>Twitter</strong></a>**/**<a href="https://www.beeminder.com/brennanbrown/photos" target="_blank" rel="noopener noreferrer"><strong>Instagram</strong></a>**)</b>: This might be counterintuitive to some people, but I seldom use any social media. By tracking the photos I upload and the Tweets I write, I’m encouraged to look for interesting things that happen daily and share them with my friends and family.

<a href="https://www.beeminder.com/brennanbrown/french" target="_blank" rel="noopener noreferrer"><strong>Language Learning</strong></a>: Tracks the amount of EXP I earn on Duolingo. I’ve been trying to learn French for the past few years on my own, and it’s hard, but practicing a little bit each day has helped my retention far more than just occasional cram sessions.

#### IV. Daily System

Here’s an example of what my current day would look like, following the things I track on Beeminder. This is essentially putting the theory into practice, and pen to paper. The truth is that, other than programming, these habits don’t take up much of my day at all, and I actually end up having more time to relax or try something new because of it.

1. Start the day off by writing what I’m grateful for and check on my progress on my current goals.
2. Take fifteen or twenty minutes to practice my French on Duolingo and TinyCards.
3. Go on walk or bike ride throughout my neighbourhood. Photograph anything interesting while out.
4. Spend an hour or two programming. Learn something new, document it well, and then push it onto GitHub.
5. Don’t waste time mindlessly scrolling through Facebook or Reddit. Use screen time sparingly, and do something I actually enjoy when I want to take a break. (Watch a documentary, play a video game, etc.)
6. Take a half hour to write in my journal or drafting a blog post.
7. At the end of the day, write a Tweet about anything interesting that happened during the day.

#### V. Final Thoughts

- <b>Don’t commit to anything that doesn’t make you excited.</b> The psychology of having free-will with your goals is essential. If you don’t feel like you’re doing what you’re doing for just yourself, it’ll feel like another chore. Don’t commit to anything because other people think you should. It’s only you.
- <b>Hold yourself accountable.</b> I’ve put a a public link to my Beeminder account in my Facebook and Twitter bio, so anybody can see if I fail my goals. I also wrote this article. Use public pressure as motivation and a tool for good.
- <b>Nothing falls into place by itself.</b> There are a lot of pieces to the puzzle of the self, and it might not all click at once. There is no one-size-fits-all, what works for me might not work for you. What _is_ universal is the importance of good values — if you commit to working hard, the <a href="http://www.anvari.org/fortune/Miscellaneous_Collections/342733_laws-of-serendipity-1-in-order-to-discover-anything-you-must-be-looking-for-something.html" target="_blank" rel="noopener noreferrer">law of serendipity</a> will eventually favour you.
- <b>Your first try always sucks.</b> Similar to above, don’t expect to nail anything when you first have a go at it. I’ve been using Beeminder for almost two years and just got the hang of it. The first draft of everything — not just writing — is going to be garbage.
- <b>Go slow.</b> I didn’t try to start tracking everything at once. I started with the smallest and easiest (things I was already doing) and added something new once a week. If I found something wasn’t working after a week of tracking, I’d just delete it. No big deal.
- <b>The magic bullet of success is realizing there is no magic bullet.</b> It’s just a lot of hard work, and figuring out how to be <a href="https://medium.com/@brennanbrown/work-edd9f8e23516" target="_blank" rel="noopener noreferrer">happy about doing that hard work</a>.
