---
layout: post
title: "How Not to Use Pivotal Tracker"
date: 2013-09-24 09:50
comments: true
categories: agile product
---
I used to work at [Pivotal Labs](http://www.pivotallabs.com), and it was an incredible gig. I loved it and learned a lot. Pivotal is known mainly for two things: [their highly-effective agile development methodology](http://www.fourhourworkweek.com/blog/2011/06/07/whats-your-start-up-bus-count-7-myths-of-entrepreneurship-and-programming/), and creating [Pivotal Tracker](http://www.pivotaltracker.com), the agile project management tool. *(N.B. The AP Style Guide insists that you always refer to the product as “Pivotal Tracker,” or “Tracker,” but never “Pivotal.” Pivotal is a company. Pivotal Labs is a consulting agency within that company.)*

I’ve [written](http://www.quora.com/Ruby-on-Rails/Whats-an-efficient-web-app-development-process/answer/Lee-Edwards?__snids__=186146892&__nsrc__=1) and [spoken](https://speakerdeck.com/ledwards/bringing-the-pivotal-process-to-an-early-startup) [a lot](http://dev.sidetour.com/post/25368076497/how-project-management-works-at-sidetour) about [how Pivotal does agile](http://www.quora.com/What-is-the-difference-between-Pivotal-Labs-and-an-outsourcing-firm). Unsurprisingly, [so has Pivotal](http://vimeo.com/52923973). Pivotal was founded in 1989, and after years of working this way, they created Pivotal Tracker as a tool for managing this particular kind of agile software development workflow.

As such, Tracker enforces that process with a degree of rigidity. This is a good thing, I think. So many of Pivotal clients, and so many startups in general, have one of several problems that Tracker tries to solve by offering strong suggestions about how to work.

1. No technical/product-focused cofounder, and hence no guidance on product development process
1. A technical cofounder with no product experience, and hence no guidance on product development process
1. A technical cofounder or employee who has only ever hacked alone, and hence has little notion of how to create a product development process as the company grows
1. A bad product development process

If you follow [the rules of using Tracker](http://www.youtube.com/watch?v=bzCZysm5lG8), you will always write specs. You will always break those specs into smaller chunks that still deliver value, called “stories.” You will estimate the stories as a team. You will work on them independently, in the order of their priority, and only one at a time. You will deliver them to QA, or “acceptance” before they can make it to production.

So Tracker is usually a breath of fresh air to these companies. A smart person can pick up the basics of how to do agile the Pivotal Way in a day or two, and really internalize and become highly effective within it by a couple weeks. Even if it's not perfect for them, it's a great place to start. Some people have called Tracker's process "training wheels". I'd say it's a little more like a damn good starter bicycle. But I don't bike, so my analogy might be off.

So what’s the problem then?

The problem is that efficiency and effectiveness is only part of what a startup’s product team needs in order to succeed. The other part is innovation, and that part is much more difficult to describe using a prescriptive process like this one. Tracker gives you no insight into how a story got into Tracker. All of that happens offline and Tracker doesn’t care about it. But as a company, you have to care about it, because you can’t build a company on bad ideas executed quickly.

We’ve tried a number of things to try to fill this space at SideTour. Some have worked, some haven’t. We’ve done several [Pivotal-style brainstorming sessions called “inceptions.”](http://pivotallabs.com/agile-inception_knowing-what-to-build-and-where-to-start/) We’ve tried several incarnations of [kanban](http://www.forbes.com/sites/stevedenning/2011/06/27/lean-startups-pt-4-using-kanban-to-validate-innovation/). We've done some of this in our [iteration planning meetings](http://pivotallabs.com/running-an-ipm/) (IPMs, also known to some as sprint planning meetings). We’ve tried various levels of strictness in adherence to [Lean Startup](http://theleanstartup.com/). We’ve spent time ignoring Tracker and focusing on more free-form development process, somewhat like [programmer anarchy](http://martinjeeblog.wordpress.com/2012/11/20/what-is-programmer-anarchy-and-does-it-have-a-future/), which we called an "internal hackathon." We did a company-wide brainstorming session during an offsite. And we’ve had a lot of ad hoc conversations and emails to define our product ideas. eEach of these has had various levels of success worthy of their own blog posts.

But the important takeaway for the purpose of this article is that you can’t use Tracker for any of this. Don’t even try. And Pivotal wouldn’t even disagree with me; it’s simply not what the tool is for. It's an agile development tool, not an ideation tool.

For that, you need something more flexible. I used to recommend card walls for this (to replace people's natural tendancy to do something horrible like store important collaborative information in Word or a moleskine), but lately, I’ve been recommending [Trello](http://www.trello.com).

With Trello, you can define your own process. Some people would say this makes it a great replacement for Tracker, and you can certainly do that. See, for example, [this Trello board I made that implements Pivotal Tracker](https://trello.com/b/m1v3aMZS/pivotal-tracker-implemented-in-pure-trello) that could serve as a starting point for modifying the Pivotal process into your own agile development process. Another option is to use Trello to track your ideas in various stages before they enter Tracker.

I don’t have a formula for how to manage the process you use to fill the backlog with successful features. If such a process existed, and I knew it, I would be on a beach in Ibiza drinking away my millions one margarita at a time instead of writing this blog post. But here is what SideTour tried during our Hackathon Week, and it both produced great ideas and raised the level of energy and engagement across the entire office by noticeable amounts.

1. Allow the team to add their own ideas to the Ideas column.
1. Encourage team-wide discussion on the ideas (turn on voting if you wish)
1. Allow the developers to pick the next thing they want to work on, based on their own opinions of the discussion and voting.1. Enter some form of agile development cycle. The phases used by Tracker are a reasonable default.
1. Measure success to help improve company intuition.

This process is not optimized for efficiency. Time developers spent discussing various product ideas could be more efficiently allocated to coding. But coders are people, not inputs to a code production engine. And the most valuable ones have product sense. They also know your product better than almost anyone else in the company. Keeping them out of the idea generation phase increases the chance that your startup is going to miss that next important idea.

It’s easy to be lulled into a false sense of security by finding success within your Tracker velocity or "Done" column. But it’s easy to see how too much focus on getting things done, without an equal or greater focus on what things need to get done, could kill your startup. For that, you need to look outside of Tracker, and inside your team.
