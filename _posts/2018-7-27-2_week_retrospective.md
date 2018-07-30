---
layout: post
title: Two weeks in...
description: A brief summary of how I've found the CodeClan course so far.
tags: codeclan coding n00b
---

As I near the end of my second week at CodeClan, it feels like a good time to pause and reflect a little on my experience - how I've found it, what's been challenging for me and (perhaps more importantly) if I've survived the first 14 days do I think I can survive the next 14 weeks!

But I'm probably getting ahead of myself.  For the benefit of those who are maybe thinking of undertaking the CodeClan course I should probably explain a little about the process first.  If you are accepted onto the course, your first encounter with the instructors and the rest of your class will be at one of the 'Meet the Cohort' days 3 weeks before the start of your course.  It is here that you meet and get to know your fellow classmates a little better and get given a list of pre-coursework to get on with.  The pre-work is largely based around CodeAcademy's Ruby, HTML, CSS, Git and command line courses, with a few pages of reading thrown in too.  

By and large this is all  to get you used to typing in code, and you will also have to send updates of your typing speed to the instructors every week.  I was quite proud of my 45 words per minute, only to find out someone in my cohort could regularly manage over 100!

Week One starts with you getting to know the rest of you cohort, in addition to expanding on the Ruby techniques you had learned in the pre-coursework.  This was OK for me, as I'd had some exposure to Python previously so was pretty comfortable with basic control loops and logical operators.  After a few days of all day, every day practice I was surprised at how much I'd improved.  The hardest part (for me at least) was having to use my brain again after what felt like years of inactivity.  A large part of my motivation for enrolling in this course was the dissatisfaction I'd felt with most of the jobs I'd had since leaving university, as I found I wasn't learning anything and becoming bored very quickly.  At least now I don't have to worry about getting bored - I doubt I'll have the time over the next four months.

As the course at CodeClan is created with the intention of getting you ready for a junior-level development job, you learn a lot of industry best practices along the way.  For example, every morning begins with a 10 minute 'stand up' where we go round the room and talk about any issues we had with the previous homework assignment.  I'll admit to feeling a bit nervous at first during the stand-ups (largely through worried about being judged for getting stuck at something easy), but by the time you are on day 5 you realise everyone is in the same boat with the same problems.  

The other concept you learn in week one is the one I struggled with the most - Test Driven Development (TDD).  The basic tenent of which is that for any function or method you write you begin with writing a test to prove it works _before_ you write the function itself.  At first this felt like doing things back to front, but I soon appreciated that TDD saves time and gets you thinking about what you want your code to do before you write it.  And you will be writing loads of tests in weeks one and two, so if you can't wrap your head around it you will by the end.

Having survived our first weekend homework assignment, myself and the rest of cohort G7 arrived bleary-eyed for Monday, Week Two.  Apparently one of the hardest weeks of the course, here you learn the principles of Object-Oriented Programming (OOP) and get _a lot_ of hands on practice.  I swear I will never look at the interaction of Bears, Rivers and Fish in the same way again!  OOP principles are very powerful and underpin most of the software that is in use today. By the end of Week Two I felt I had a really good grasp on how to model simple systems in Ruby and test them using MiniTest (and I'm not ashamed to admit there was also a little bit of Pry debugging required too).

Week Three will see us learning some SQL, and looking at the interaction of Classes, Ruby and SQL.  In the back of our minds we are all thinking about our first solo project that is coming in Week Five, where we get to use the skills we have been learning in conjunction with the Sinatra framework to build a simple app. I'm certainly looking forward to it and will hopefully post some of the code up here when I am done.  Now if you'll excuse me, I have some testing to do...

``` ruby
require 'minitest/autorun'
require 'minitest/rg'
require_relative '../yet_more_homework.rb'
```
