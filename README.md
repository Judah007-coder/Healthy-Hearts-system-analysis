# **HealthyHearts Charity: Systems Analysis Project**

<img width="1254" height="1254" alt="Designer" src="https://github.com/user-attachments/assets/01f90972-056c-4cb6-859f-7a7cec81ab77" />


A systems analysis and design project for a fictional health charity, HealthyHearts. Working in a team of four, we analysed how the charity operates and proposed a single information system to replace its manual processes. I was the team leader.

Methods and tools: Agile methodology, Belbin team roles, Gantt charting, use case diagrams, data flow diagrams (DFDs), flowcharts, Miro, Microsoft Teams, WhatsApp Context: Group portfolio for IY454 Introduction to Information Systems Analysis, Nottingham Trent International College (February to April 2026)

# Note: HealthyHearts is a case study scenario set by the module, not a real client. The system described here is a design proposal. It has not been built as working software.

## **The scenario**

HealthyHearts is a small charity that runs health programmes such as fitness classes and community support groups, runs community outreach (visits to schools, clinics and fairs), and operates a charity shop selling donated and refurbished health-related products. It has limited staff, a small budget and little IT expertise, and most of its work is done by hand.

The brief: analyse the charity's needs and propose an information system that brings its activities into one place.

# My role and contributions

I was appointed team leader. My Belbin team-role profile came out as Shaper, a task-driven role that pushes the team towards its goals, and this matched how I worked on the project.

## *Leadership and coordination*

Organised the team's roles using the Belbin results and agreed who would do which task
Kept the team on schedule with weekly check-ins and confirmed tasks in writing so everyone knew their responsibilities
Helped resolve misunderstandings about task ownership when they arose

## *Analysis and design work I produced*

Wrote the functional and non-functional requirements
Drew the context-level DFD and Level 1 DFDs (with one teammate)
Drew the Level 2 DFDs
Built the project Gantt chart (with one teammate)
Wrote the justification for our choice of logical model (with one teammate)
Compiled the Harvard-style reference list (with one teammate)

Done as a team: the management strategy, use case diagrams, logical model, user interface mock-ups, description of system improvements, and the project evaluation.

# Management approach: Agile

We chose an Agile approach rather than waterfall, for four reasons tied to the charity's situation:

Flexibility. The charity's needs could change, and Agile allows requirements to be added, removed or re-prioritised.
Breaking down a big job. The scope was large, so splitting it into smaller cycles kept it manageable and lowered the risk of errors.
Feedback. Regular review lets mistakes in understanding be fixed early instead of discovered at the end.
Cost. The charity has a small budget, so the most important features can be delivered first and extended later.
## The challenge we identified

Agile depends on frequent contact with stakeholders, but a small charity has limited staff time. Our proposed solution was to agree fixed review meetings and ask the charity to nominate one person as its representative.

# **How the team worked**
Roles were allocated using the Belbin team-role results.
We held weekly meetings (in person and on calls) and used WhatsApp and Microsoft Teams in between.
The team's project files were kept in a shared folder to reduce the risk of losing work.
The main risks we identified were delays, miscommunication and lost files, and we planned around each.
## Requirements
# *Functional requirements*
#	Area	What the system should do
1	Employee management	Add and manage employee records and track roles (including staff who hold more than one role)
2	Participation and volunteer records	Store records of participants and volunteers in health programmes and support groups
3	Subscription management	Let customers request an annual subscription, let staff approve it, take payment, store customer details only after approval and payment, and send newsletters based on the customer's interests
4	Notifications	Notify programme leaders or shop managers when new employees are added
5	Community outreach tracking	Record visits to schools, clinics and fairs, and show customers where and when the next event is
6	Charity shop inventory	Record donations, check suitability, assign prices from a pricing guide, track stock and update inventory automatically when items are sold
7	Weekly staff reporting	Let authorised staff submit weekly reports on programme attendance, shop sales and outstanding payments
8	High-value purchase approval	Require board approval by email when refurbished stock costs more than £750, and record the item, date, requesting manager, reason and approving board members
Non-functional requirements
Programme scheduling, integrated with a shared Outlook calendar
Wearable device integration to capture activity during fitness programmes
Reliable integration with external tools (wearables, email, calendar)
Regular updates, especially for security
Security: protecting employee records, participant information and financial transactions
System models

All diagrams are in the diagrams/ folder.

## Use case diagram

Shows how four types of user interact with the system: staff members, customers, shop managers and board members.

Use case diagram

## Context-level DFD

Shows the system as a single process and everything that flows in and out of it. The external entities are staff members, customers, shop managers, board members and the bank (for payment verification).

## Context DFD

## Level 1 DFD

Breaks the system into six main processes: employee management, scheduling health programmes, recording events, managing inventory, creating weekly reports, and purchases and subscriptions.


## Level 2 DFDs

Each main process is broken down further, with a separate diagram for employee management, inventory, weekly reports, event recording, purchases and subscriptions, and programme scheduling.


## Logical model: flowchart

We used a flowchart to model the system's logic because it is clear to both technical and non-technical readers. It shows how a user logs in, reaches a role-based dashboard, and moves through each process, including the decision point where purchases over £750 need board approval.

Flowchart

User interface mock-ups

Screens for login and sign-up, role selection (volunteer, customer, staff member), and a dashboard for each role.

## Proposed improvements and impact
One platform instead of separate manual processes, reducing duplicated work and improving coordination
Real-time updates, so staff can see accurate information and decide faster
Role-based access, so each person only sees and manages what is relevant to them
Automated processes, which reduce manual data entry and human error
Automatic reports for the board, which also lets the system grow as needs change
Project evaluation

## What went well

Setting roles early with the Belbin results made responsibilities clear.
Regular communication kept the work moving and cleared up confusion.

## What was hard

Misunderstandings about who was doing which task caused delays that then affected later work.

## What I would do differently

Be more open early on about our individual schedules. Because we weren't, sections were finished at different times, which slowed us down. Agreeing availability on day one would have avoided most of the waiting.



## What I learned

A team project depends on communication as much as technical skill.
Planning the schedule properly at the start (the Gantt chart) saves a lot of time later.
Leading means giving direction while also listening, and being willing to help teammates who fall behind.


## *THE REPORT* 
[HealthyHearts_Systems_Analysis_Report.pdf](https://github.com/user-attachments/files/34536262/HealthyHearts_Systems_Analysis_Report.pdf)





