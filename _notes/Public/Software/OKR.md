---
title : OKR
subtitle: OKR for product teams
feed: show
date : 24/02/2023
permalink: /okr
status: draft
reviews:
  - { date: 02/24/2023, comment: 'seeded' }
  - { date: 02/24/2023, comment: 'tended' }
---
The idea here is not to defend or not the OKR technique, it has his flows. But if you want to experiment it then there are few guidelines to follow to not reproduce known issues with OKR. And writing them properly will save you few quarters of experimentation and learning.

Let's begin with a definition

> **Objectives and key results** (**OKR**, alternatively **OKRs**) is a goal-setting framework used by individuals, teams, and organizations to define measurable goals and track their outcomes.  

*source: [wikipedia](https://en.wikipedia.org/wiki/OKR)*

There two important terms here:
- measurable goals
- outcomes

**Measurable goals** is critical for the key result (KR) part. If you can't measure it, it's not going to work.
**Outcomes** this is maybe the trickiest part for product teams used to deal with output (roadmap, deadlines...). If you focus on the output or delivery then you'll end up having unmeasurable KR transformed into roadmap deadline.

Let's have a look into another definition of OKR from Marty Cagan in his book [Inspired, How to create tech products customers love](https://www.goodreads.com/book/show/35249663-inspired)

>*The OKR technique is a **tool** for management, focus, and alignment.* - Marty Cagan, Inspired

It's a tool, that you use to help prioritize the right thing to build in your product. It should not dictate what you will plan but measuring the outcome of what you are planning.

With that in mind let's build a first objective. 
We realized that we had a lot of bugs customers are complaining about. Sometimes critical sometimes less but it always triggers customer non satisfaction.

So what's about this objective?

**Objective (v1)**
*Reduce the number of bugs in production by X%*

What is the problem here? 

One critical point regarding OKR objectives in Inspired is the following
>*Objectives should be quantitative; key results need to be quantitative/measurable* - Marty Cagan, Inspired

Here we don't have a quantitative but a qualitative objective. So this should belongs to one key result (KR).

**Objective (v2)**
*Increase customer satisfaction*
- KR1: *Fix 5 critical bugs*

Now we have a qualitative objective to focus on and a key result to follow. Is it good enough?

Let's have a second look into another important characteristic of KR
>*Key results should be a measure of business results, not output or tasks* - Marty Cagan, Inspired

So KR should demonstrate and measure the impact of what you deliver at a business level. By measurable it means something you can track over time with the team.

So let's rewrite it:

**Objective (v3)**
*Improve user satisfaction*
- KR1: *Reduce calls to level 1 support to less than 100 per month*
- KR2: *Reduce number of open bugs in production to 25 maximum per month*
- KR3: *Reduce average response time of user backend to 150ms*

With this kind of KR if you plan a new feature that might impact the response time or if you are not confident of delivering bug free feature then it's definitely not a good candidate.
But if you decide as a team to focus your effort on bug fixing and performance improvement there are more chances that you'll reach the objective.

Another important aspect here, is regarding what the team will communicate. If you focus on output and delivery, you might communicate to the organization:

> *We managed to fix 15 critical bugs and deliver performance improvement on component X and Y in the product*

How does this message is aligned with the objectives? 

But if you focus on the outcome and the KR then it's much easier to communicate something focusing on the business impact.

> *This month we manage to reduce the average response time to 100ms and reduce the incident to only 15. Which had a tremendous impact on support with only 75 direct calls. Our customer satisfaction is much better according to the latest discussions with them*

What do you prefer to hear or communicate within your organization? What do you think will have the most impact? 