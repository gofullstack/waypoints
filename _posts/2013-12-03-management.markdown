---
layout: page
title: Management
tags: main
---

In the following sections, you can learn all of the details by reading the In Depth portions or grab the key takeaways by glancing at the Highlights. 

## Managing Projects
On a high level, our project management process is comprised of a series of recurring events - release planning meetings, iteration planning meetings, stand-ups, demos, and retros.

Before we jump into the specifics of each event, it's important to understand how we define work to be done, the anatomy of a story, why and how we measure velocity, and highlight the benefits of using a tool like Pivotal Tracker to help keep everything organized. 

### How Work Gets Defined and Estimated 
#### Turning Requirements Into Stories
**Highlights**  
  > Stories should be written from the perspective of customer in this format - "As an (Who *[User Role]*), I want (What *[Feature]*) so that (Why *[Problem that the feature will solve for the user]*). "

**In Depth**  
  Whether it's designing a layout or writing code for a feature, the starting point for organizing any work to be done is turning business requirements into stories. In the spirit of being agile and focusing on delivering real value to the people who use our products, we believe in structuring our work around stories written from the customer's perspective. 

 We've found that it's really easy to work on things that don't directly correlate to added value for the end users. This means wasted time and money on developing functionality that will not have the return on investment our client's really want. By filtering all of the requirements through the lens of the customers, we are able to quickly see what features are important to the users and what things we could probably hold off on. 

The anatomy of a story looks something like this:
> As an (Who *[User Role]*), I want (What *[Feature]*) so that (Why *[Problem that the feature will solve for the user]*). 

So an example story could read something like:
> As a project manager, I want a tool that let's me write and communicate stories to the developers, so that we can stay organized and build functionality that really solves problems.     

This criteria then forces the product team to think critically about the best way to solve that problem and deliver functionality that allows the user to accomplish their goal. 

#### How We Manage The Stories
**Highlights**  
> We use Pivotal Tracker to manage stories. You should read the [Getting Started Guide](https://www.pivotaltracker.com/help/gettingstarted) to familiarize yourself with the workflow.

**In Depth**  
Fortunately, there is already a great solution for project managers to communicate and track stories for development projects. We prefer to use [Pivotal Tracker](https://www.pivotaltracker.com) to keep track of our stories as a product team. For the sake of brevity, i'll refer you to their [Getting Started Guide](https://www.pivotaltracker.com/help/gettingstarted) to get the background you need on how to use the tool, how to understand the different types of stories (Features, Chores, Bugs, and Releases), and basic workflow. 

#### Understanding The Story Status and Lifecycle
**Highlights** 
>*"Start"* when you begin working on the story. *Finish* when you're ready for code review. *Deliver* when it's ready for acceptance from a product owner or QA. *Restart* to fix the defects when the story gets rejected.

**In Depth**  
It is important to know the basic workflow for managing story statuses. The lifecycle of a story follows this general timeline:

1. Story is created in the icebox and requirements are added. Once it's time for the big show, the story is dragged over to the backlog and prioritized.
2. Each week, the team spends a bit of time grooming the backlog by going through un-estimated stories, reviewing the requirements, and estimating their story point value. 
3. When the story comes up in the queue for the weekly iteration and a team member is ready to start working on it, they *"start"* the story. 
4. Once the team member has completed the story and is ready for collaborative review, they *"finish"* the story. This indicates the majority of the work is done, but it's not ready for final QA and acceptance testing. 
5. When the story makes its way onto staging or somewhere that it can be officially tested, the team member *"delivers"* the story. 
6. At this point, the product owner reviews the fully functioning deliverables of the story and either *"accepts"* or **"rejects"* the story based on whether or not it meets the "done done" criteria. 
7. If the story is accepted, it's considered completed. If it is rejected, the story has a *"restart"* state. Once the team member working on story restarts it, it follows the same process and flow in steps #4-#6. 

#### Estimating Stories
**Highlights**
> One story point equals an ideal day for you with no blockers or unknowns.
> Break stories down into smaller stories to keep estimates for each story under 3.
> All team members are responsible for looking at the backlog throughout an iteration and estimating new stories that have been moved over from the icebox. 

**In Depth**  
One of the challenges of building software is estimating how long tasks will take. This is inherently complex and unreliable due to the nature of software development. Solving problems that have never been solved before means there is a large amount of risk. 

To mitigate this over the long run, we work together as a team to estimate stories with story points. For our projects, 1 story point equals an ideal developer or designer day with no interruptions, blockers, or unknowns. As stories are written and placed in the backlog, team members review the requirements and estimate those stories based on what they feel is the difficulty level and how long they think it will take them. 

During the initial stages of a project and a team working together, estimates are usually really off and that's ok. The longer a team works together on solving a problem, the more the team learns about the domain. This translates to fewer unknowns and eventually more accurate estimates. 

We've found it most helpful to try and break stories down so they can completed in a day. If stories get into the 5+ range, it's more likely things will get off track because the scope of the deliverable is too large. Again, build things in small chunks so they can be shipped more quickly. The faster we get feedback, the faster we can iterate, obtain validated learning, and respond to the market demands.

As weekly iterations progress and stories are delivered, the team begins to establish a velocity. The team's velocity represents the number of story points delivered per iteration. Velocity is calculated as a moving average of the previous 4 iterations. This allows us to look through the backlog, see the total number of story points, compare the work that needs to be done in the future with the historical performance of the team, and abstract out a timeline for major milestones and releases. 

So let's look at a real example of velocity in action. During a recent project, we established a team velocity of 7 over the course of several iterations. So our team is able to deliver 7 story points per iteration. Looking at the backlog in Pivotal Tracker, I see there are about 35 points worth of stories that need to be delivered before we can release the next version of the app. If we're delivering approximately 7 story points per week, then as a project manager, I can reasonably predict that it will take roughly 5 weeks to complete the remaining deliverables. 

Beyond that, project managers use the velocity to extrapolate out budgets and resource allocations for projects. Let's say those 7 story points are delivered by a team of 2 developers and a part time designer. Each week, those three people spend roughly 85 hours(35+35+15=85) working on the project. So if it's currently taking 85 hours to deliver 7 story points, that works out to about 12.14 hours per story point. If I know there are 35 points remaining the backlog, and each point takes 12.14 hours, then the total budget and resource allocation needed to complete the backlog is about 425 hours. 

This is definitely not an exact science, but it is a very effective way of using past historical performance to provide a better picture for predicting the future. It's also a great tool to understand where we are spending time as a team. Since Feature stories are the only type of stories that get estimates (read the Pivotal Tracker guide if you haven't yet), a team's velocity can be diminished by an increase in the number of defects or chores that need to be accomplished each iteration. 

At its core, story points are not just for estimation, but represent the amount of time spent by the team working on delivering new value for the end users of the products we build.

### Release Planning Meetings (Monthly or As Needed)
**Highlights**
> The goal for these meetings is to scope out on a high level the features and functionality in the form of stories that will be the focus of the product team's activities leading up to the next release.  This is where we understand more about business requirements and how our work correlates to specific business objectives.

**In Depth**  
These meetings are held once a month with all team members and stakeholders. The goal of the meeting is to come away with high level milestones for product development for the next four iterations, specifically what major features and functionality we want to launch in the next release. Sometimes products are on monthly releases, sometimes new features are released every week. There is no hard and fast rule that says you must have a release planning meeting once a month. The cadence of the product development team and the clarity of deliverables for the  next several iterations is usually what dictates when a release planning meeting needs to happen. If the backlog is thoroughly prioritized and scheduled out for the next six weeks and there isn't a need to deviate much from that, then a monthly release planning meeting doesn't make sense. It really depends on the specific business, the product lifecycle, and how new features are being delivered to the market.  

This is where we begin taking rough business requirements and turning them into high-level stories. We talk through how features should behave, what value they provide to the end users, how we can create the functionality in the most efficient way possible from a UX and technical perspective, and what the most logical way of chunking the work out is. 

At this point, stories and requirements might be a little bit rough in terms of complete scope and requirements, but they are usually sufficient to provide an initial story point estimate. There are still unknowns, but that is OK. Release planning allows us to start giving shape to turning ideas into tangible work output.  

### Iteration Planning Meetings (Weekly)
**Highlights**
> Recurring weekly meeting where the team reviews business objectives specified by the stakeholders and makes commitments to deliverables for the week.  Detailed requirements are discussed and story point estimates are updated where applicable.  The final priorities and queue order for the tasks are set by the stakeholders, based on both business objectives and the teams feedback. 

**In Depth**  
Iteration planning happens once a week on the same day, every week. It represents the start of a new cycle and provides the opportunity for the team to re-align development priorities with the current business objectives. The bulk of the call is spent taking higher level stories and discussing them in as much detail as possible with the goal of removing any unknowns or potential blockers before the story comes up in the work queue that week. 

Most stories in the backlog should have a story point estimate by now. During the process of reviewing the requirements and deliverables for each target task for the iteration, the team re-estimates the story if needed based on new information that has come to light since the last time it was estimated. Usually more is known about how to solve the problem, or the business needs have changed in the several weeks the story has been queued in the backlog.  

Once the ideal goals for the week have been outlined, the team decides what they can and cannot commit to delivering for the given iteration. It's easy to take this part of the planning process lightly, but making commitments is not a trivial matter in our opinion. We define commitments as, "the state or quality of being dedicated to a cause, activity, etc." The act of the team making commitments to deliver features symbolizes their willingness to dedicate themselves to delivering on those stories within the normal working parameters each team member has. This sets reasonable expectations for what will be finished and by when. The important thing to note here, only the team has the power to make specific commitments. They are free to decline if they feel it's unreasonable. 

At that point, we go back to the drawing board and break down the work into even smaller chunks until it feels achievable to complete and ship within the given time frame. It's also OK to fail on meeting commitments. It's NOT OK to fail on meeting commitments and not communicate your impending fate until the day things are supposed to be done. The main outcome of following this process every week is accurately managing expectations of every individual who has a stake in the product - from clients to investors to engineers. 

It's also important to note that, as much as possible, once commitments are made, stakeholders do not change the priorities for the current iteration. Only hotfixes and immediate or critical threats to the success of the business are allowed to take precedence over the previously agreed upon priorities for any given iteration. This safeguards and prevents the team from being jerked around; providing increased stability and focus to delivering their stories to the best of their ability throughout the week. 

### Stand-ups (Daily)
**Highlights**
> Daily get together with the team to give status updates on work completed the previous day, tasks that will be worked on for the current day, and blockers preventing individuals from completing their stories. Stakeholders and product owners do not actively participate, but act as representatives of the end users should the team have questions on desired behavior or functionality. 

**In Depth**  
Maintaing the expectations throughout the week on target deliverables is where the importance of daily standups come in. Depending on the team size, standups should last anywhere from 5 to 15 minutes. The basic structure of a standup is each team member reporting:
1. What they worked on yesterday. 
2. What they are going to work on today. 
3. What blockers they have (if any) in completing their stories; which ultimately puts delivering on their commitments at risk. 

Standups got their name because the idea is to literally stay standing the entire meeting. This forces everyone to be succinct, to the point, and get their reports in quickly so we can all sit back down and return to being productive. Everyone hates meetings, so the shorter, the better. If blockers are identified, we wait on discussing them until the end of the standup. We grab whoever needs to be involved and hold a breakout on the specific blockers to figure out what we can do immediately to remove them, thus allowing the team to return to operating at the most efficient levels possible. 

If it's identified on the second or third day of the iteration that the initial commitments made during the weekly planning session are no longer achieveable, the entire team needs to break out on it immediately after standup. This usually happens if things that were previously unknown before a story was started rear their ugly head in the middle of trying to implement a rather seemingly straightforward task; or if a hotfix gets pushed through the backlog into the current iteration. It's the entire teams responsibility to communicate effectively about why the commitment won't be delivered; as well as discussing alternatives for completing the story such that it can still be done during the iteration. This usually means making hard decisions, but again this is where it's the entire teams job to talk through the pros and cons, and to provide the stakeholders and clients with as much information as possible to make the best decision they can.  

We've found that it's best if discussion during standups is limited specificly to team members with assigned stories and the facilitator of the standup. It's easy for a client or product owner to want to weigh in, but uninvited interference from stakeholders and clients during standups usually turns them from a 5 minute meeting to a 45 minute discussion where an entire team just lost 13% of their day to a meeting. If clients or stakeholders need to discuss requirements, it's best to request a breakout with the project or product manager assigned to the team. And even more so, if these mid-iteration breakout meetings are frequent, it's usually a sign of process problems up the stream either during release planning, backlog grooming, or iteration planning. 

### Demos (Weekly)
**Highlights**
> Show of a working component of the product that represents the stories (and value) the team delivered the previous week. 

**In Depth**  
We usually like to hold demos right before we begin iteration planning for the week. The purpose of the demo is to visibly display the work completed by the team during the previous iteration. If everything goes well, the demo happens on a staging environment or somewhere that it's a command or two away from being shipped and deployed to production. Doing weekly demos provide a powerful collaboration and feedback mechanism for stakeholders to be intimately involved in the iterative growth of their product over the development lifecycle. This empowers stakeholders to make informed decisions on priorities for the upcoming iteration, as well as a way to see tangible progress towards their business goals. 

Doing demos and shipping functionality each week also grants the ability to immediately begin testing and validating features before the entire product is "done done." Getting users involved early and shipping often is the best way to ensure that the vision of the product aligns with the actual need it's trying to address within the given market. 

### Retros (Bi-Weekly)
**Highlights**
> The goal is to imrpove our process as a team.  We do this by identifying things we liked as well as point points we experienced. We then extrapolate out problems that need solutions, brainstorm possible approaches to solving the problem, then ending the meeting by identifying a few actionable steps we can take the following week to test whether or not they move the need in solving our identified problems. 

**In Depth**
Retros are an invaluable time for the team and stakeholders to come together and identify specific pain points, enjoyable things, and solutions to improve the project management and product development process as a whole. The goal is not to focus on individuals, but to focus on identifying impediments that are slowing the team down and preventing them from firing on all cylinders. 

Our adopted motto for retrospectives is, "“Regardless of what we discover today, we understand and truly believe that everyone did the best job they could, given what they knew at the time, their skills and abilities, the resources available, and the situation at hand.”

We conduct retros by colloboratively writing notes in a Google Drive drawing, then organizing them according to things that we enjoyed and pain points. We then go over each note on a high level and extrapolate out identified problems. We then spend some time brainstorming possible solutions to the problems. The meeting ends by clearly selecting a few possible solutions we will focus on implementing the following week to test their validity in solving the problems we have. 

## Managing The Creative Process


## Managing Code
