<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [What is Agile?](#what-is-agile)
- [Scrum Team Roles](#scrum-team-roles)
- [Product Backlog](#product-backlog)
- [Sprint Backlog](#sprint-backlog)
- [Story Points](#story-points)
- [The Agile Lifecycle](#the-agile-lifecycle)
  - [Backlog Priority and Estimation](#backlog-priority-and-estimation)
  - [Sprint Planning](#sprint-planning)
  - [Sprint Review](#sprint-review)
  - [Sprint Retrospective](#sprint-retrospective)
  - [Daily Standup](#daily-standup)
- [Definition of Done](#definition-of-done)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


# What is Agile?

Agile is an umbrella term for a number of methodologies such as Scrum, Lean, Kanban and XP among others. In RHMAP we follow a Scrum approach but please note that we use the term Scrum / Agile interchangeably to represent the methodology we are following.

Agile bases itself around a number of principles which are embodied in a document known as the [Agile Manifesto](http://www.agilemanifesto.org/). In short it states that we can improve how we work by placing value and emphasis on certain approaches. It states that we value:

* **Individuals and interactions** over Processes and tools
* **Working software** over Comprehensive documentation
* **Customer collaboration** over Contract negotiation
* **Responding to change** over Following a plan

The crucial point about this is we place value in the items on the right but we place more value in the items on the **left**.


# Scrum Team Roles

* Scrum Team
The Scrum Team is made up of individuals from various parts of the organisation such as Engineering, Operations, QA, Support, Technical Writer, Sales, Marketing etc. The Scrum Team is normally put together around the thematic area of work that they are involved in, meaning that the team can change over time depending on what expertise is required within the group. Within a Scrum Team, there are, deliberately, no assigned roles. This is intended to promote the idea that any member of the team is free to take on any piece of work. People with a particular skill set or expertise will naturally gravitate towards the tasks that the feel most comfortable with.

* Product Owner
Product owners control the vision for their product or group. They are focused on understanding business, technical and market requirements, then prioritizing the work to be done by the scrum team accordingly. Within Sustaining Engineering our Product Owners can be representatives of various groups that we work with, for example, Operations and Support, who help set our agenda.

* Scrum Master
Scrum Masters are the champion for scrum within their team. They coach the team, the product owner, and the business on the scrum process and look for ways to fine-tune their practice of it. They are a guiding hand for the team and act as a shield to help protect the team and keep them focused on the work at hand. A main role they play is unblocking a team member if they have an issue. The Scrum Master is not the "leader" of the team - Scrum teams are self organizing. Rather, the Scrum Master is a "Master" of the "Scrum" principles and should be viewed as a facilitator.


# Product Backlog
The Product Backlog is an ordered list of all the items that the product owner wants done. A scrum team should typically spend approx 10% of their time reviewing and refining the items on the product backlog - breaking down large items into smaller, more achievable tasks and estimating the effort required to complete these tasks. At any time, the Scrum Team should have enough items identified and broken down into to small tasks to populate approx 2 sprints. This gives the Scrum Team some flexibility when planning a sprint as they should always have more than enough tasks ready to bring into a sprint. As part of backlog refinement, the Scrum Team should be looking several sprints out (typically 5 sprints) at the work on the horizon, and be starting to break this work down into smaller tasks. This ensures that any dependencies on other teams can be identified and flagged early, provides time to engage with the product owner to seek clarification and allows for investigation or "spike" tasks to be prioritised so that further refinement can be done.

# Sprint Backlog
The Sprint backlog represents the work that the Scrum Team have committed to trying to complete within a given sprint. These items could be new feature requests or bug fixes, among other tasks. Like the product backlog, the sprint backlog should be ordered, with high priority items moving to the **top of the backlog**. Ideally, new items discovered during a sprint should not be added to the Product backlog rather than the Sprint Backlog - unless they are deemed necessary to achieve the sprint goal. When this happens, a discussion with the product owner may be necessary to negotiate which task(s) will be dropped from the sprint to accommodate this new work. Alternatively, the Scrum Team may decide that they have capacity to take on this new work without the need to drop any other work from the sprint.

# Story Points

Items within the Backlogs have an associated **Story Point** value. Story Points are a measure of effort/complexity, capturing how much work will be required to achieve the goals of a particular item. Effort/complexity is not directly related to time and we are trying to move away from time based estimates which have many known issues. Story points are based off of a loose Fibonacci scale of 0,1,2,3,5,8,13,21,34,50 and 100. For reference, we define the effort/complexity of three of these items, allowing us have a baseline for estimating issues.

1. A complexity of 1 is a simple version bump on a project, no thought process necessary
2. A complexity of 2 is a something with a minor amount of complexity that involves some form of research e.g. adding more logging statements to a file, conceptually very easy but first you need to identify what is of value to be logged.
3. A complexity of 100, is something that is too large to estimate or is something that we are missing information on. This task will need to be broken down into smaller tasks as part of backlog refinement. This will typically require engagement with the Product Owner for clarification.

# The Agile Lifecycle

Agile follows a lifecycle which consist of several parts, all wrapped around the concept of a **Sprint**. A sprint is a timeboxed effort, typically two weeks, which has the potential to deliver something of value or something that is shippable to a customer. Within the two weeks we commit to trying to complete a certain number of tasks which we aim to complete in their entirety. All of the following stages of the Agile lifecycle are attended by the three main roles of Scrum Team, Product Owner and Scrum Master as well as any other interested attendee.

## Backlog Priority and Estimation

The Backlog should constantly be prioritisated and any item within the backlog should have an appropriate estimate. It is also recommended if any work is obvious that known SubTasks are created to help gain a better estimation, as SubTasks help to identify the larger picture required to get a particular issue over the line. However, if these Subtasks are estimated to be more than 2 to 3 days effort, they should be created as stand alone tasks, which can then have SubTasks added to get to a greater level of detail.

## Sprint Planning

With the backlog already in a prioritised state and estimated accordingly, the team meet and decide what should make up the Sprint. The Product Owner will have helped us arrive at this state and is available for any clarification. Typically a Sprint will revolve around a Thematic area to help focus the team and allows work to commence on related issues. Within planning the team use the Story Point measure to gauge the complexity of the work they are about to undertake and arrive at the contents of the sprint guided by that measure. How many story points that a team can complete in a given sprint is termed the **Velocity** and over time it will help the team gauge how much work they can comfortably take on.

## Sprint Review

After the sprint has concluded, typically on the last day of the sprint, we have a review. Within the review we can share to wider teams what we achieved. This is an opportunity to demo or showcase the outputs of the sprint. The audience for that meeting is entirely dependent on the focus of the sprint.

## Sprint Retrospective

This is typically the most important stage of the lifecycle. Here we give the members who participated within the Sprint an opportunity to share their experiences in an attempt to positively impact the Agile process that we are following. Typically the format follows a format of sharing:

1. What we thought worked well -- to reinforce it and make sure we keep going in the right direction
2. What we thought didn't work so well -- to raise an awareness that the process might need reviewing
3. Action Points -- typically what will we do for the next sprint, what will we change, any follow on work etc.

The Sprint Retrospective is a core pillar of Scrum. As a team we want to constantly learn from our experiences in order to refine and improve how we work as a team. Within Scrum it is known as the principle of do, learn and adapt.

## Daily Standup

Every day within the sprint we hold a daily standup, which is a strict timeboxed checkpoint for the team. This is an opportunity for the team to share their current status and to flag any issues that are blocking them. Three core questions are asked:

1. What did you achieve yesterday?
2. What will you look at today?
3. Are there any blockers stopping you from progressing your work?

Questions 1 and 2 help to distribute the work among the team and ensure that the Sprint is progressing in the correct manner. The third question is very important to alert the team to a potential issue stopping you completing your work. Obviously this should be brought up through other forms of communication ahead of the Standup but the Standup provides an opportunity to share this widely with the team.

## Team ownership

Agile promotes the concept of team ownership and self organisation of the teams. Every item or task within a sprint is owned by the team and thus eligible to be completed by any members of the team. What helps here is to have multiple sub tasks to help promote overall ownership.

# Definition of Done

Agile teams works on the principle of a definition of done. We promote complete flexibility within the team to ensure that HOW we get something done is up to the team. We wish to empower smart people to allow the right choices and approach emerge in order to complete something. This is complemented by us already understanding the WHAT (should be done) and WHY (should it be done) which we receive from our Product Owner. The definition of done is often written with a level of freedom as not all tasks we complete are black and white so the list is deliberately not strict.

Here is a sample definition of done from an Engineering Team perspective:

* Code is commented where appropriate
* Code added has appropriate tests (where applicable)
* Code is checked in to a relevant branch
* Code has passed a quality check
* Code is deployed somewhere and another engineer has verified the work



Going back to the WHAT, WHY and HOW, taking the definition of done in that capacity we can begin to see a rationale emerging.

* Code is commented where appropriate
 * **WHAT** = Adding comments to new code / files
 * **WHY** = Maintainability of code for future bug fixes
 * **HOW** = write relevant comments on complex or mission critical code e.g. don't comment on a logging statement


* Code added has appropriate tests (where applicable)
 * **WHAT** = Testing new code that we added
 * **WHY** = Important that we have some form of coverage to protect our code
 * **HOW** = write unit tests for code that is testable.


* Code is checked in to a relevant branch
 * **WHAT** = version control
 * **WHY** = Need to have code version controlled
 * **HOW** = could be a branch, or master checkin depending on the code / release


* Code has passed a quality check
 * **WHAT** = some form of quality pass has occured
 * **WHY** = we want to improve the quality of our work not add to a technical debt mountain
 * **HOW** = Maybe we use SonarQube, maybe we use the PR guidelines, maybe we use pair programming.


* Code is deployed somewhere and another engineer has verified the work
 * **WHAT** = Validation on a machine and with a person that is not the developer who made the changes
 * **WHY** = Because it avoids confirmation bias, it ensures it works on multiple machines
 * **HOW** = Deploy on a Virtual Machine and ask someone to validate the work
