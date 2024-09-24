# Development Plan
### Team 15, SyncMasters
Mitchell Hynes\
Richard Fan\
Akshit Gulia\
Rafeed Iqbal\
Kyle D'Souza

## Revision History
***Table 1: Revision History***
  **Date** | **Developer(s)** | **Change** |
  -------- | ------------------ | ------------------------ |
  Sept 19, 2024    |  Richard Fan           | Conversion of tex to markdown |
  Date2    |  Name(s)           |      Description of changes |
  \...     |  \...              |      \... |


## Introductory Blurb 
This document outlines the development plan for the project. Further information regarding the problem is located in ~/docs/ProblemStatementAndGoals/ProblemStatement.pdf.

# 1 Confidential Information?

This project will not contain extensive confidential information warranting a
confidentiality agreement. After a team meeting with MILO, it was determined our
team will inform the City to advise us of any confidential information. We will
ensure it is not included in the source code or at the capstone expo.

# 2 IP to Protect

The project does not have any IP to protect.

# 3 Copyright License

Our team will be licencing our project under the **MIT** licence
(https://github.com/Spitgranger/capstone/blob/main/LICENSE). As our project is
done in collaboration with industry this licence makes sense due to its
flexibility. It will allow our industry partners to freely use and modify the code
as they see fit in both open source and proprietary projects. This may be the
case after the conclusion of this capstone project, hence the choice of this
licence.

# 4 Team Meeting Plan

Weekly team meetings will occur on Monday evenings. Meetings to be held online
or in-person depending on the groups preference that week.

We will meet with our industry advisor bi-weekly, but this could be more or less
depending on the needs of the capstone team as we progress through the
deliverables. Meetings will be on Microsoft Teams, with the option to meet
in-person if it is convenient for the particular meeting. Meetings will be
structured with a prepared agenda by the capstone team and the discussion with
the stakeholder chaired by the team liaison. Meeting minutes and action items
will be recorded by the capstone team.

# 5 Team Communication Plan

***Table 2: Communication Plan***
  **Type** | **Method** | 
  -------- | ------------------ | 
  Regular communications  |  Discord  |
  Assignment of tasks  | GitHub Issues |     
  Communications with professors, supervisor, the city, and other stakeholders.   |  Handled by Team Liaison Mitchell Hynes, in-person or over email.|
  Meetings      |     Discord, scheduled through outlook calendar.|

# 6 Team Member Roles

Meeting Chair: This position will coordinate meetings, ensure an agenda is set, 
and that all parties are prepared for the meeting.

Notetaker: They are responsible for the recording of meeting minutes and 
ensuring that they are entered into GitHub.

Project Manager: Responsible for ensuring that all team members are up to date 
on work being performed and that action items for needed tasks are completed.

Team Liaison: Mitchell is the team liaison. They are responsible for 
maintaining  communications between the McMaster instructional team and the 
City for the group.

Reviewer: This role is responsible for reviewing other work and ensuring the 
quality is at a required standard. This includes reviewing commits and pull 
requests.
  
# 7 Workflow Plan

-   How will you be using git, including branches, pull request, etc.?

-   How will you be managing issues, including template issues, issue
    classification, etc.?

-   Use of CI/CD

# 8 Project Decomposition and Scheduling

-   We will be using Github Projects to decompose our milestones. Each Milestone will be divided
into individual tasks which will then be assigned to different team members.
- Each document will be split into sections, and assigned individually or to groups as needed. 
- The proof of concept, revision 0 and revision 1 will be split feature-wise and assigned to individuals or groups as necessary.
- Time will be alloted for verification, validation and review after the completion of each milestone and before the due date.

-   [Our GitHub Project](https://github.com/users/Spitgranger/projects/2/views/1)

***Table 3: Milestones***
**Milestone** | **Schedule** | 
  -------- | ------------------ |
Requirements Document Revision 0 <br> Due: October 9th| Start: 24th of September. <br> End:October 5th.|
Hazard Analysis 0 <br> Due: October 23rd| Start: October 9th <br> End: October 19th.|
V&V Plan Revision 0 <br> Due: November 1| Start: October 16th <br> End: October 28th.|
Proof of Concept <br> Demonstration: November 11-22| Start: after completion of the Requirements document. <br> End: by November 4th, with improvements being made and testing being done until the day of our demonstration.|
Design Document Revision 0 <br> Due: January 15 | Start: after completion of the Proof of Concept demo <br>End: by January 11th|
Revision 0 <br> Demonstration: February 3-14| Start: alongside proof of concept (After finalizing requirements in the meeting with the city). <br> End: by February 1st.|
V&V Report Revision 0<br>Due: March 7 |Start: alongside the development of Revision 0 of the project. <br> End: by March 4th|
Final Demonstration (Revision 1) <br>Due: March 24-30 | Start: after the completion of Revision 0. <br>End: by March 20th.|
| EXPO <br> Demonstration: TBD, April| Start: 2 weeks before the day of the expo.|
Final Documentation (Revision 1) <br> Due: April 2 |Start: March 10th. <br> End: by March 30th.|

# 9 Proof of Concept Demonstration Plan

What is the main risk, or risks, for the success of your project? What
will you demonstrate during your proof of concept demonstration to
convince yourself that you will be able to overcome this risk?

# 10 Expected Technology

We will be using Git for version control, the repository for the project will
be hosted on GitHub and we will be using GitHub projects to track issues and
schedule tasks for the project. The programming languages that we intend to use
for this project are Javascript for our frontend and Python for our backend. On
the frontend, we will use the Next.js framework. We intend on using AWS to host
our application, for this, we will use AWS Cloudformation templates to define
our infrastructure.

Some of the linter tools we will be using are Ruff, Bandit, and Pylint for
Python. We will use cfn-lint for linting our Cloudformation templates. For
Javascript, we will be using Prettier and ESLint. In terms of testing
frameworks, we will be using Jest for Javascript and Pytest for Python.
For Python, a code coverage tool we intend on using is Pytest-cov.

For the CI we will be creating Github actions workflows for running linters,
formatters and unit tests on the project. We will also create actions to
automate builds to ensure PRs do not contain breaking changes, and create
actions for deploying the application into production and testing
environments.

Of course, the technology mentioned here is not final and is subject to change
as the project progresses.

# 11 Coding Standard

To enhance uniformity across developers and adherence to best practices, the
following coding standard will be adopted: 
- **Linting** -  As mentioned above, we will be using ESLint with
@typescript/es-lint plugin for TypeScript code and Pylint for Python code. The
default ruleset for both tools will be used to enforce best practices pertaining
to both syntax and semantics as identified by the community.

- **Code Style and Formatting** - Prettier will be the main code formatter used
for this project. Prettier was chosen because of its opinionated nature by
default with regard to formatting, as well as compatibility and popularity with
the TypeScript language. Code written in Python will use Ruff. Naming
conventions of variable and function names will follow the style guides provided
by the creators/maintainers of the aforementioned tools.

- **Code Documentation** - To enhance readability and maintainability, all code
which does not perform a trivial task shall be documented. When documentation is
needed, it will follow JSDoc or Pydoc conventions so that auto-generated
documentation can be produced.

- **Testability** - Although subjective, the team should try their best to write
code in a way that is testable. This includes following the principles of high
cohesion, low coupling and single responsibility.

# Appendix --- Reflection

The purpose of reflection questions is to give you a chance to assess
your own learning and that of your group as a whole, and to find ways to
improve in the future. Reflection is an important part of the learning
process. Reflection is also an essential component of a successful
software development process.

Reflections are most interesting and useful when they're honest, even if
the stories they tell are imperfect. You will be marked based on your
depth of thought and analysis, and not based on the content of the
reflections themselves. Thus, for full marks we encourage you to answer
openly and honestly and to avoid simply writing "what you think the
evaluator wants to hear."

Please answer the following questions. Some questions can be answered on
the team level, but where appropriate, each team member should write
their own response:

1.  Why is it important to create a development plan prior to starting
    the project?

2.  In your opinion, what are the advantages and disadvantages of using
    CI/CD?

3.  What disagreements did your group have in this deliverable, if any,
    and how did you resolve them?

# Appendix --- Team Charter

borrows from [University of Portland Team
Charter](https://engineering.up.edu/industry_partnerships/files/team-charter.pdf)

## External Goals
What are your team's external goals for this project? These are not
the goals related to the functionality or quality fo the project. These
are the goals on what the team wishes to achieve with the project.
Potential goals are to win a prize at the Capstone EXPO, or to have
something to talk about in interviews, or to get an A+, etc.

## Attendance

### Expectations

Team members are expected to attend all scheduled meetings as reasonably
possible. If a team member needs to miss a meeting, they should inform the team
beforehand. During the meeting, team members are expected to be on time and
stay for the entire duration of the meeting unless prior arrangements have been
made, something urgent comes up during the meeting (see _Acceptable Excuse_),
or the meeting goes over the scheduled amount of time.

### Acceptable Excuses

Acceptable excuses would include personal/family emergencies as well as
conflicts and events beyond one’s control such as a sudden power outage or a
commitment that cannot be rescheduled. These excuses, however, should be kept to
a minimum and each team member shall do their best to meet deadlines and attend
meetings. Unacceptable excuses would include, but are not limited to: 
- Poor time management: Claiming that “there wasn’t enough time” or “I forgot” 
- Personal issues that are not urgent: Being tired, or sleeping in
- Last Minute Non-Urgent Events: Missing a meeting or deadline to attend a party
at the last minute.

The examples above provide a guideline as to what is acceptable or unacceptable.
Ultimately excuses will be considered by the team on an ad-hoc basis so that the
best solution can be agreed upon given the circumstances.

### In Case of Emergency

If a team member has an emergency, team members will inform the rest of the team at their earliest 
convenience to ensure the other team members are aware that their responsibilities in the project
will be impacted. This applies to both attendance at team meetings and

In case of an emergency, a team member will:
1. Write a message in the project discord at their earliest convenience regarding what work will be missed, and during what time frame they may be unavailable.
2. Email team liaison Mitchell regarding the emergency to leave a record which can be shared with the course coordinators if necessary.

## Accountability and Teamwork

### Quality

Each team member is expected to come prepared with the agreed upon meeting
prerequisites. This includes any action items, questions, or code reviews. Each
team member to is to put forth their best effort in the course and ask for help
from their teammates or the instructional team if needed to meet the course
deliverables at a high quality of work.

### Attitude

What are your team's expectations regarding team members' ideas,
interactions with the team, cooperation, attitudes, and anything else
regarding team member contributions? Do you want to introduce a code of
conduct? Do you want a conflict resolution plan? Can adopt existing
codes of conduct.

### Stay on Track

To keep the team on track we will use GitHub projects to keep track of tasks we
need to complete and their deadlines. We will ensure that team members
contribute to the team by assigning tasks for deliverables equally amongst the
team so everyone has an equal workload and knows what they need to do. When
someone’s performance is below expectations we will first try to figure out
internally in the team if there is anything that can be done to improve their
performance. If nothing can be found within the team, then we will contact our
TA for advice. A punishment for performing below expectations might include
assigning more work to the individual in the following deliverables. For team
members who do well, we will reward them by giving them Timbits at the end of
the course.

The performance of team members will be judged based on the following:
* Completion of all assigned issues before their deadlines
* Capstone lecture attendance for software engineering lectures* >= 50%
* Internal meeting attendance* >= 80%
* Stakeholder meeting attendance* >= 90%
* For commits, we will have to see how often things are getting committed into
the repository. Still, as a general rule, we can say that if a group member has
35% fewer commits than the average number of commits for all other team members
and also 35% fewer additions than the average for all other team members, then
they are likely not meeting expectations.

*For attendance-based goals if someone has an exception for some meetings,
which is covered by the acceptable excuses, then the meetings that they were
excused for are not counted towards their attendance.

If team members do not meet their goals we will first internally discuss with
the team member why they were unable to achieve the goals and what can be done
to prevent it from happening going forward. If no resolution can be reached we
will discuss the situation with our TA or the instructor. We will not implement
punishments like “the team member needs to bring coffee to the next meeting”
because this is not productive and generally does nothing in the way of solving
the root issues. There won’t be any particular incentives for reaching targets
early other than not having to worry about reaching the targets.

### Team Building

We have been studying in the same program for nearly 5 years now, and so there
are many shared experiences which bring us together as a team. While it may not
be necessary to schedule additional activities for team building, it may prove
beneficial for stress release and increasing team cohesion. 
- Team Lunches: Between classes, days when everyone is on campus and has time
free around noon.
- Ad-hoc team activities: Other fun activities can be scheduled according to the
free time of the team members

### Decision Making
To make decisions, the group member who's role is to direct that task will
organize the rest of the group around their respective action items. All team
members will be able to contribute their opinion, and in general decisions will
require a consensus amonngst the group. If an issue is not resolved through
discussion, it will be brought to the attention of the instructional team for
mediation and feedback.

