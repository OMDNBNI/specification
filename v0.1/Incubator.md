# Incubator

An **OMDNBNI** Incubator is the physical location of the *“sandbox”* environment where the students participate 
in a simulation of a small startup company. The incubator members are divided into the following categories:
* The *primary* group consists of 8 top students, called **[eggvelopers](#eggvelopers)**
* The *secondary* group consists of an even number of students called **[twinvelopers](#twinvelopers)**.

A **candidate** can become a **twinveloper** after passing the interview with the [**board**](#board).
 
Once the interview is passed the candidate can immediately join the **twinvelopers** w/o any waiting period.
This will provide a simulated situation where the team has to onboard a new member.

A **twinveloper** can be *“promoted”* into an **eggveloper** by the board if a vacancy is open,
and similarly an **eggveloper** can be *“demoted”* by the **board** back to a **twinveloper**.

Naturally the board can cut funds completely for any member (either **eggveloper** or **twinveloper**) 
if the need arises and thus effectively *“fire”* them.

## Twinvelopers
These members of the incubator are future [**eggvelopers**](#eggvelopers) that are undergoing a process of acquiring the necessary skill-set.
The skill-set defines what we call a *minimal viable developer* **MVD** and includes Working knowledge of using:
* a Programming Language (eg. JavaScript, GoLang, Python, ...);
* a Project management tool (eg. Jira, Redmine, Trello, ...);
* a Distributed Version Control System (eg. Git, Mercurial, ...);
* a Integrated Development Environment (eg. JetBrains, VisualStudio, ...);
* a Software Producing process (BRD, SRS, CI, CD);

The **board** is responsible for setting up the skill-set requirements per incubator instance.
   
The **twinvelopers** are organized into [pair-programming](https://en.wikipedia.org/wiki/Pair_programming) teams, 
and are given a “vanilla” project to work on and *"learn by doing"*.

The project they are working on should be either open-source or an in-house project set by the **board**.
Ideally the project should include a quality assurance (QA) component in a form of:
* analysis and refactoring of legacy code;
* analysis and development of test cases;
* analysis and revision of specification documentation;

The purpose of the process is to acquire the necessary skill set (usually technical by nature) in order for each of them 
to be *"promoted"* to an **eggveloper**. It also provides the **twinveloper** a chance to get acquainted with the
field of work that he/she was interested in and enables them to change their desired field of work,
minimising the risk of getting deeper into a field they essentially are not interested in.

They are given **60%** of the monthly allocated budget per member, as a form of a *"salary"* on a monthly basis.
 
The **board** will keep track of their progress through:
* analysing the metrics provided by the PM tool on a monthly basis
* a monthly **1h** visit where the board members can interact with the group.

If there is an odd number of **twinvelopers**, the lone member will have to continue alone until a new member arrives or 
will receive a bit more attention by the [**anarchitect**](#anarchitect) as they are lacking the collaborative dynamic
to improve at the same pace.

The incubator cannot be started w/o the existence of this group.

## Eggvelopers
These are the best-performing members of the incubator.
They are picked by the **board** from the secondary group by *"promoting"* a **twinveloper** to an **eggveloper** status.
The team skill-set distribution, required for the project is setup by the **board**. By default the distribution is:
* 3 Developers
  * 1 FE (Frontend)
  * 1 BE (Backend)
  * 1 FS|DM (Full stack|Development manager)
* 2 QA
  * 1 Test automation coder
  * 1 QA analyst (QA manager)
* 1 DevOps (Production manager)
* 1 UI/UX
* 1 Product Owner

In order for a member to become part of this group, he/she should be, mature enough and have the necessary skill-set required
to actively participate in the project.

Their progress is monitored by the board through 
* a PM tool analysis on a weekly basis and
* a monthly progress review meeting 

This progress review meeting is held at the incubator where the board can review the incubator members in person 
for no more than ***15** minutes per member* (a 2 hour total). It is expected that these meetings will take on average 
approximately ***5** minutes*.

The **eggvelopers** are rewarded by being given **80%** of the budget allocated for an incubator member 
on a monthly basis. These funds can be used by the **eggveloper** as a form of a *“salary”* in total or 
they can pull their funds and organize their own budget themselves.

The purpose of the process is to teach the members how to collaborate, interact in an efficient way, and produce deliverables
so they don’t have to  acquire these skills in the real world, where the risks are much greater.

They main responsibility of the **eggvelopers** is to work on the [Golden project](Golden Project.md),
assigned by the incubator [Board](#board).
The project is the main source of the metrics used to evaluate the progress of the **eggvelopers** in the incubator.
For this reason it must be documented and managed through a Project Management tool of choice (by the board). 

An **eggveloper** can be *“demoted”* to a **twinveloper** by the **board**, in which case the board should *“promote”* a
**twinveloper** to fill the “gap” in the **eggveloper** ranks.

## Board
The incubator **board** is the authority of the incubator and is responsible for distributing the monthly budget to the members.

It is consisted out of experts in various fields that have necessary skills to assess the incubator members.
Their function is to:
* Interview candidates that wish to enter the incubator;
* Assign and specify a project the **eggvelopers** will be working on;
* Review all reports provided by the incubator anarchitect;
* Review all **eggvelopers** on a weekly basis and once a month in person;
* Approve the continuation of funding to any member;
* Hold **monthly board review** meetings;
* Attend the **Golden Project** release presentation;
* To make the final assessment of the **Golden Project**;

### Monthly Board Review
The conclusion of the monthly board visit should be:
* to hold an up to *15 minute* review interview with each **eggveloper** individually;
* to optionally hold a *1 hour* group review meeting with the secondary group of **twinvelopers**;
* to *"promote"* or *"demote"* any member from **eggvelopers** to **twinvelopers** and vice versa;
* to approve bonuses of *20%* of the monthly allocated budget per member, to any deserving member
(**eggveloper** and **twinveloper** alike);

## Anarchitect 
The **anarchitect** is the guardian of the incubator and a guide for the members.

The incubator anarchitect’s main responsibility is the operation of the incubator and as such
has **no authority over the members**, other than guiding them to comply with set operational procedures.

It is his duty to provide guidance and advice when asked and to write *short weekly reports*
on the progress of all teams and if needed certain members.

In addition the **anarchitect** should provide the members with [**planned lectures**](Lectures.md#planned-lectures)
 based on the [**dynamic curriculum**](Lectures.md#dynamic-curriculum),
regardless whether the lectures are held by the **anarchitect** him/herself or by a board approved third party.

Aside from previously mentioned **planned lectures**, the **anarchitect**, when requested by a member or a team,
can hold [**runtime lectures**](Lectures.md#runtime-lectures) in the form of **15-30 minute** stand-up lectures
in the incubator conference room, addressing the issue that arose immediately on the spot.

The **anarchitect** has succeeded when he has become obsolete.
The aim of the **anarchitect** is to guide the members to try and resolve the issue on their own
either by member inter-communication and/or doing autonomous research,
which can be presented to the **anarchitect** for comment and clarification.

Since the **anarchitect** will be in working with the members on a daily basis,
the board should maintain the limited authority of the **anarchitect** in order to
avoid and prevent any nepotistic tendencies of such a system.

Considering that the **anarchitect** has to be able to deal with issues in real-time,
the position of the **anarchitect** is fairly demanding, so it would be advisable that the position
is not held by a single individual for a period longer than *6 months*.
