---
layout: default
title:  "Workshop 1: Welcome to the Team"
date:   2017-02-14 05:40:01 -0800
categories: workshops
author: michael
excerpt_separator: <!--more-->
---

This workshop presents a common and ambiguous situation that we can all relate to. In this workshop, you are a new, junior software engineer on a team at a big company. Work through the ambiguity to find moments to lead, get some results, and contribute to improving the engineering team's culture and effectiveness. 

<!--more-->

### Narrative

You started a new job at a big financial services company three months ago as a junior software engineer. Before this, you were working at a startup for two years (fresh out of computer science school). It flamed out but not before you got amazing full stack, agile experience. Actually, the startup didn’t really follow agile "processes,"" it just *was* agile. You shipped lots of times per day. Code coverage was dependable, integration tests were fast, and frictionless to deploy. You touched the whole code base. Any tool you wanted, you could have. If a framework made sense, all you had to do was present it and the team would generally adopt it if it made sense. The code base was constantly refactored and groomed. 

#### Your New Company
You loved the experience, but you're also tired after all those late nights and weekends, so you joined a bigger, older financial services company. They snapped you up because you knew Ruby and they liked your full stack experience. With over 100,000+ full time employees, this place seems enormous compared to your last job. 

The managers talk about “going digital” and as a proof point to Wall Street they want to dramatically improve and modernize their investor relations portal. (An investor relations portal is a usually a section of a company’s site where investors and financial analysts can interact.) 

You joined the investor relations engineering team to work on a four year old Ruby code base that has many holes in its code coverage. It was originally written by an outside agency. Almost nobody at the compay knows Ruby. The app uses many frameworks, much of the code hasn’t been touched for years, and it slows down and sometimes crashes under load but nobody is certain why. The company wants to rework it to make it faster, mobile friendly, and the person from the business keeps talking about more “digital” features, whatever that means.

#### The Current Engineering Culture

It took a few weeks to get your laptop, badge, and access to all the code, but now you’re three months on the job and you’ve been through a few sprints. At your old company, you spoke your mind freely. It could get chaotic and arguments would break out, but the best ideas seemed to win. Here, the engineers are quiet and rarely speak during the “standups,” which are held sitting down in a conference room. Most bring their laptops and keep working through the standup. 

At first, you felt awkward and outspoken as you tried to participate in the standups by asking lots of questions. For example, once you asked someone why they didn’t refactor some old code rather than struggling with an ehnancement story that spanned three sprints. Another time you asked what the branching strategy was. You didn’t get very clear answers to questions like this. 

In the past month or so you’ve fallen into the rhythm of things and dutifully give your updates at the standups. You don’t ask as many questions.

#### Your New Team

The team consists of three junior engineers like you, an architect, and an engineering manager. The manager is pleasant and talks about how she wants to support the team and create a safe environment, but you don’t see her much; she’s in meetings or in her office on the phone almost all day. She scheduled a series of 1:1s with you when you started. She’s had to cancel most of them due to calendar conflicts. 

The architect has been with the company for almost ten years. He’s been working on the investor relationships code base ever since the company insourced site and fired the agency who originally built it. It seems like the engineering manager adopts, without question, any decisions the architect makes. He does not engage you often, but the business talks to him a lot, which is a relief because the people that come in from the investor relations team seem impatient and demanding. Like the manager, he’s in meetings almost all day, every day. You did get a chance to talk to him recently, however. You suggested changing the logging framework because the current code base uses some home-grown thing that doesn’t give you much information when you’re trying to debug. He said, “I own all that core code, and I just don’t have time to do stuff like that right now,” before running off to another meeting. 

#### Your Story and Task

A few weeks ago, during sprint planning for Sprint 32, the engineering manager asked you to work closely with another software engineer to change to a new stock price provider’s API (a big part of the investor relations portal is displaying current and historical stock price of the company). The new API is supposed to provide faster stock quotes, which might be one of the performance problems, in addition to some data analytics features. It’s a REST-based, JSON API that seems straightforward to integrate with.

The software engineer you’re working with joined the team from another group about a year ago. After the sprint planning session for Sprint 32 )three weeks ago), you asked the engineer to hang out in the conference room for a bit to talk through the approach and do a little design. “Sure, but let me look at the docs for a while and then we’ll do it... tomorrow maybe,” was the response you got. 

Unfortunately, the other engineer got pulled into a production support issue, never did talk in detail about the API, repeatedly saying more time to think about it was needed. To your surprise, the engineer announced toward the end of Sprint 32 that some of the functionality was working and asked you to write some unit tests for it. Near the end of Sprint 32, the engineer announced that the stories wouldn’t get done because of the production support issues, however.

During Sprint 33 planning, you and the other engineer were asked to make a “commit” to the two stories, which have now been revised as “spike” stories. One was to get the company’s stock price to show up from the new API in the development environment. The second is to present an approach for how to do fully integrate the stock price into the site to the team. The other engineer committed; not sure what else to say, you went along.

We’re now two days into Sprint 33. The other software engineer got pulled into another production issue and made some vague promises about working with you on the two stories and walking through the little bit of code that did get written during the last sprint, which still hasn’t been checked in. None of the other engineers on the team can help because they have their own sprint commitments and don’t know anything about the new stock price API. 

It's Wednesday. There are eight days left in this sprint. What will you do now?

### Workshop Instructions

#### How to Organize the Workshop

1. Ask participants to read the narrative (but not necessarily these instructions) before starting the workshop
2. Ask four participants to play the role of (a) the new software engineer, (b) the other software engineer, (c) the architect, and (d) the engineering manager
3. Ask the junior engineer to do act out what he or she would do in the situation and interact with the people in the other roles
4. Ask the audience to discuss the performance

A variation on the workshop may, instead, be to review the narrative as a panel (or even roundtable) discussion. The group can discuss the problems with the situation and how they would address it. Under this variation, it may be a good idea to have at least one or two participants come prepared with a point of view to get the conversation going.

#### Possible Questions to Raise During the Workshop

* Explore what you (as the new engineer) really wants in the situation? Do you want the situation to be different?
* If you do, articulate in detail what the future look like for the team?
* What choices do you have to make for yourself if you want to lead the change?
* What internal decisions do you, as the junior engineer, need to make, if any, when you decide to change the situation?
* If you do want to drive change, how do you teal with the reality that you’re not the manager and you’re new? How can you lead, nonetheless?
* What do you need to be honest with yourself in the situation? (Hint: that this isn’t working, that this situation isn’t really “agile” and probably doesn’t align with your engineering values.)
* How can you “inspire” your partner? Inspiring is about showing enthusiasm, excitement, and energy about the possibilities ahead. It shows energy signaling personal commitment. Do you see any here?
* Even as a new member of the team, you come with a lot of competence and skill. What are some ways you could you demonstrate it here?
* How would you articulate a vision for this feature and how to implement it? Who would you enlist to help?

#### Give Us Feedback!

We want to know how the workshop went. Fork this repo and submit a pull request or just drop an email to [Michael Rice](mailto:me@michaelrice.com).
