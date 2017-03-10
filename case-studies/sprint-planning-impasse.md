---
layout: case-study
title:  "Sprint Planning Impasse"
date:   2017-03-09 21:43:01 -0800
categories: case-study
author: michael
readingTime: "3 minutes"
prepTime: "15 minutes"
environment: corporate
context: software-engineering
traitsExplored: forward-looking
---

You’re sitting in a sprint planning meeting with a scrum master and five other developers. You’re a senior software engineer, and your engineering manager relies on you to be her surrogate (e.g., the tech lead) most of the time. Today, she’s nowhere to be found since she’s got two other teams and projects to keep track of too. 

Your team works on an internal web app that helps your company’s internal reps schedule and track deliveries for Hot Stuff Delivered (“HSD”), an established online meal delivery service in Southern California. Your main logistics partner, a smaller company providing on demand delivery called Wheels.com, powers important parts of your internal app. Your app interacts with Wheels through version 2.7.1 of their REST-based API. 

A few weeks ago, Wheels.com released a completely revised version of the API, version 3.0, that’s going to require substantial rework for your team soon. In today's sprint planning meeting, the scrum master just proposed a tech “spike” story to do a rough prototype integration with the new API and demo how it works at the end of the sprint (in two weeks) to the rest of the team before fully diving into a full-blown rework of your code base.

You’re not the only senior software engineer in the room. Arnot is too. He’s been with the company for almost ten years -- nine years longer than you -- since HSD’s earliest days. Arnot wrote the original integration with Wheels.com. Most days, most people on the team try to avoid Arnot, including you and your manager.

During today's spring planning, Arnot has been quiet while you and the scrum master discuss the proposed spike prototype story. That's good in a way, but annoying too because Arnot has forgotten more about the Wheels API than you’ve learned in the past year. 

Suddenly exasperated, Arnot leans forward in his chair with his jaw tightly clenched and says, “What’s the f***ing point of writing code we’re just going to throw away? We need to spend time analyzing and designing to the new API before we write a single line of code.” 

The room gets very quiet.

Very quiet that is until the engineering manager pops in the room and asks you to step out. She says, “Hey, how’s it going in there? Never mind, I heard Arnot, and I don’t care what he says. I need to show something to senior management at the end of the sprint because they’re freaked out about whether we can respond to Wheels’s API change fast enough. I’m counting on you to make sure we have a story where we have something can show them by the end of this meeting.” She walks off before you can respond.

You turn to walk back into the room. Even from here, you can hear Arnot still fuming about the “throw away code.” 

**What are you going to do?**