# Sprint Meetings

This is a brief presentation on the scope of regular meetings typically associated with Agile / Scrum.

[Made with reveal.js](http://revealjs.com/).

## Sprint Goals ## 

The goals of this process should align with our values of a company, and the company culture we wish to create as we grow. A good process:

* Allows us to react quickly and intelligently to change, both to changes in the market and internal change.
* Empowers team members to produce quality work, efficiently.
* Fosters close collaboration between team members of all types.
* Creates transparency in our process about work, knowledge, and decision-making.
* Scales. Our process should work for teams of most any size, across multiple disciplines. It is not only reproducible, but works at any level. For example, scrum often scales up to a scrum of scrums, where point people for various teams get together and discuss how their projects impact each other.

## Sprints ##
Our work is organized into sprints. Each sprint is just an arbitrary unit of time (two weeks) that we use to organize our work, make improvements to process, reflect on accomplishments, and plan for the future. Sprints aren't tied to product, feature, or software releases, which can span multiple sprints, or just part of one.

## Sprint Schedule ##
**Every Day**
* Stand-up

**Week One**
* Day 1 (Friday): Why do sprints start on a Friday? Because at the end of the sprint, there is usually a push to finish tickets and release code. We do not want to push code to production on Fridays.
  * Sprint Retrospective
* Day 5 (Thursday)
  * Sprint Prioritization
  * Team Meeting

**Week Two**
* Day 10 (Thursday): Last day of sprint. The team attempts to close out as many tickets as possible.

## Stand-up ##
Stand-up is a daily status meeting that happens every morning.

### Goal ###
The goal of stand-up is to provide transparency on what each team members is working on, and for the team to identify ways that they can help with (unblock) those tasks.

### Participants ###
* Developers and Designers 
  * The work these team members do is most often represented as tickets on the Jira board.
* Product and Project Managers
* Observers (optional)
  * Non-team members, such as senior leadership, are welcome to attend and observe stand-up from time to time. It's a great way to gain visibility on what is happening with a team, make an important announcement that might affect the day's work, or to reach out if you need help with something.

### Process ###
1. The facilitator brings up the Jira or Trello board for the sprint, and calls on each team member to give an update.
2. Each team member gives a brief (1-2 minute) update on: 
    * What they worked on yesterday
    * What they plan to work on today
    * If they are blocked on a task and need help. 
3. Announcements: this is where any team member can give a heads up to the rest of the team, e.g. a vacation coming up, a social event after work, working remote, etc.
4. Meeting end: people may stick around to have follow-up conversations on things mentioned stand-up, e.g "How do we test this feature", "When can we meet about those missing requirements?", etc.

One thing that stand-up isn't great for is communicating the status of work as a big release or deadline approaches. During crunch time, teams may opt to create another 15-minute status meeting at the end of the day for those working on a release, where micro-managing priorities around QA, bug fixes, feature completeness, stakeholder expectations, etc. can be discussed.

## Sprint Prioritization ##
Sprint prioritization happens once each sprint, usually during the first week of a sprint. During prioritization, we look ahead to work lined up for the near-future (the backlog) and discuss what we need to get it ready for the next sprint.

### Goal ###
The goal of sprint prioritization is to gather and discuss information necessary for upcoming work. At the end of the meeting, team members should have a clear understanding of the goals for the next sprint, and how to accomplish each task. Tickets should be written and roughly prioritized so that they can be pulled into a new sprint during retro/kickoff.

### Outcomes ###
The backlog is groomed, meaning each ticket:
* is placed in the backlog roughly according to priority
* has clear requirements - any team member should be able to pick up and complete a task based on only the information in the ticket. If requirements are unclear, a product manager might need to fill in more detail.
* includes required assets - wireframes, designs, copy, images, etc.
* pointed - an estimate of the level of effort (LOE) to complete a task. Note: points, as a system, don't map directly to time spent on a task.

### Participants ###
Everyone, for now. We may adjust this after a couple of weeks.

### Process ###

0. Throughout the week, all team members create tickets for tasks as they identify work that needs to be accomplished. For example, an engineer finds a bug, and spends 2 minutes to throw a description of it onto the backlog. A product manager has updated copy for a consent form and make a ticket with the language attached.
1. Product managers come to the meeting with high-level goals about what work should be prioritized. For example, "Next sprint we really need to focus on the tickets for the asthma tutorial".
2. The facilitator pulls up the backlog and opens up each ticket, one by one.
3. Each ticket is briefly discussed. The team adds requirements, agrees on how something should be implemented, and estimates the level of effort (LOE). 
  * If the team can't reach consensus on any of these elements, the ticket should be kicked out to an outside discussion where the blocking issues can be resolved.
  * If a ticket has important details missing, like assets or requirements, the stakeholders have a week before the next sprint to get those items in place.
4. If there is work that has not yet been ticketed, the team can quickly make tickets and discuss them according to step 3.

As we adjust to the sprint schedule, the conversation around priorities will most likely be more free-flowing and less structured. We understand that ticket requirements and similar work will not always be written in advance of the meeting. As time goes on and we add resources for product and project management, much of the work needed to make this meeting a success will happen outside of the meeting.

## Retrospective ##
Sprint retrospective happens once each sprint, at the very beginning or end of the sprint. During retro, we look back at the previous sprint, assess how we did as a team, and how we can improve. Remember, any part of our process is up for discussion, changes, and improvement - even the retro itself.

### Goal ###
The goal of retro is to talk both quantitatively (briefly) and qualitatively (at-length) about team dynamics and process. Retro is a time to praise things that are going well, and give constructive criticism on how to address or minimize common pain points.

### Outcomes ###
* Team bonding: recognition of successes, venting frustration
* Action items: A list of things to do to address the most important feedback from retro. This could include passing feedback on to senior leadership or stakeholders, setting up a meeting to discuss a topic in-depth, changing process (e.g. trying a new format for retro), creating documentation, etc.

### Participants ###
* Everyone

### Process ###
**Sprint closing / kickoff** (15 minutes)

A facilitator or project manager closes the current sprint and kicks off the next one. This means:

1. Making sure all tickets that are done are marked as such ("burned down")
2. Creating a new, empty sprint
3. Moving unfinished tickets ("rollover") into the new sprint
4. Moving the highest priority tickets from the back log into the sprint
5. The team discusses all work and reaches consensus on how many tickets can be fit into the sprint. This is usually an assessment of past velocity, mixed in with external factors, like upcoming deadlines or holidays.

**Retrospective** (45 minutes)

The entire team does a structured activity to give semi-anonymous feedback, then discusses as a group. Note: Laptops should be closed for this part of the meeting, except for the note taker.

0. The facilitator goes over the notes from the last retro. The team briefly discusses any action items and whether or not they have been completed.
1. The facilitator hands out stacks of post-it notes and markers to each team member, and makes four columns on the wall: "Start", "Stop", "Continue", and "Questions".

**Start** is for good ideas that we haven't tried yet, e.g:

  * **Start:** Doing real user testing to validate our features
  * **Start:** Regular phone calls with nurses to get feedback about the app
  * **Start:** Implementing better coding standards for Javascript

**Stop** is for things that negatively impact us, and we'd like to change, e.g:
  * **Stop:** Checking in code that does not pass tests
  * **Stop:** Excessive meetings with no real purpose
  * **Stop:** Releasing features on Friday afternoons

**Continue** is for things that we're constantly dunking on and want to call out for recognition, e.g:
  * **Continue:** Great collaboration between product and engineering
  * **Continue:** Patient-centric approach to designing features
  * **Continue:** Communication about the work our advisors are doing behind the scenes

**Question:** is for when we'd like more information about a topic, and it doesn't really fit into the other buckets, e.g:
  * How is our latest round of fundraising going?
  * Do we think that we can take this new feature and sell it to a new group of hospitals?
  * What does our process look like in 6 months?

2. For five minutes, all team members write ideas or feedback that fit under one of the four columns on a post-it notes. Anyone can write as few or as many post-its as they want, but only one idea on each. When a person is done writing, they walk over to the wall and put their post-its in the appropriate columns.
3. The facilitator roughly organizes feedback into groups or topics. For example, if three people write "STOP eating dirty every day for lunch", then the facilitator can group those together and make sure that topic gets appropriate time for discussion.
4. Based roughly on the frequency, the facilitator structures time for an open conversation on each topic. Some topics will need more time than others. When a topic is called out, anyone can start discussing. It doesn't have to be the person who wrote the note.
5. If there is an actionable task or process improvement that comes out of the topic, the note taker adds it to the retro notes. The notes should designate who is responsible for taking action on each task, either individually or as a group.

## Meeting Roles ##
### Facilitator ###
Each meeting usually has a facilitator, or someone whose job is it to make sure the meeting runs smoothly. This is usually a project manager, but could be anyone. For some meetings, it is common to rotate facilitation responsibilities. It is the facilitator's job to make sure meeting norms are being respected, and that the meeting accomplishes its goals in the allotted amount of time. In this sense, the facilitator may "police" the meeting by reminding people of the format, closing conversation on a topic, etc. Don't hold it against them!

### Notetaker ###
It's usually a good idea to have notes or other artifacts that represents what was discussed or decided on during a meeting. The note-taker is responsible for using e-mail, dropbox, jira, or whatever tool necessary to document the meeting or the actionable items that come from it.



