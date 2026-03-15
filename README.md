# Software Development 2 Sprint 1 / Game Design Document

## What is the Project about?

The project is to develop a game.
The game I'm developing is a horror simulator game where you work inside a government facility as scientist. In a world filled with different creaures your goal is to research said creatures contained in the facility while doing objectives.

Inspired by Lobotomy Corporation created by Project Moon and SCP Foundation which is a fictiona organization that contains stories from writiers contributing to a wiki contain different creatures.

## Table of Contents
- [1.0 User & System Requirements](#10-usersystem-requirements)
  - [1.1 User Requirements](#11-user-requirements)
  - [1.2 System Requirements](#12-system-requirements)
- [2.0 Backlog](#20-backlog)
- [Section Three](#section-three)
# 1.0 User/System Requirements

In this section. The User and System Requirements are explained in Scrum style user stories and Acceptenance requirements.


## 1.1 User requirements

This section will explore the players needs and what should be expected when developing the game. 

| | |
|---|---|
| **Title** | Gameplay loop |
| **Sprint #** | 1 |
| **Priority** | Very High |
| **Difficulty** | MEDIUM |


### Story
As a player, I want to receive 5-15 objectives each shift that require 2-5 minutes each to complete.
As well as a Reward and Punishment system..

So that i have a clear set of tasks that I can complete during the 30 minute shift. And a goal to reach while trying to be efficient with time 

### Definition of Done
-  Objectives generate randomly at shift start
-  Objectives can be completed within 30 minutes while still having enough free time to roam around and explore.
-  Random events occuring at random wihthin the 30 minute time.
-  Objectives have two types. Objectivee given by System and NPC Quests.
-  By the end of the day players are rewarded or punished based on performance.

---

---

| | |
|---|---|
| **Title** | Interactive NPC |
| **Sprint #** | 1 |
| **Priority** |  High |
| **Difficulty** | MEDIUM / Low High |

### Story
As a player, I want to be capable of interacting with different characters inside the gamme.

So I can learn more about the world building and hidden lore. As well as to learn more about the characters.

### Definition of Done
-  Certain NPC can be interacted with
-  Some NPC may give tasks to do
-  Entities can be talk to as well.

---

---

| | |
|---|---|
| **Title** | Enemies |
| **Sprint #** | 1 |
| **Priority** |  High |
| **Difficulty** | Low High |


### Story
As a player, I want Enemies that chase around the player, and attack me

So I have to be checking my surrounding at all times if an enemy is hunting me down.
### Definition of Done
- AI walks to waypoints
- Follows players when they are nearby
- Attacks player when close enough


---

---

| | |
|---|---|
| **Title** | Objectives |
| **Sprint #** | 1 |
| **Priority** | Medium |
| **Difficulty** | MediuM |

### Story
As a player, I want a list of objectives players can do to get paid at the end.

So I can be engaged with the game and have something to do


### Definition of Done
.
- Objectives being Side tasks, Main tasks, Extra Tasks.
- Side and Main tasks being given from the system
- Extra Tasks given by npc

---

---

| | |

| | |
|---|---|
| **Title** | Shop |
| **Sprint #** | 1 |
| **Priority** | Low |
| **Difficulty** | Medium |

### Story
As a player, I want to use the money I obtained through to gain items

So I have a goal to keep playing the game and to make it more fun.

### Definition of Done
- The shop must be able to take away money from the player
- The shop must give items in store to the player


## 1.2 System Requirements


| | |
|---|---|
| **Title** | Day and night System |
| **Sprint #** | 1 |
| **Priority** | Medium |
| **Difficulty** | Low Medium |


### Story
As a developer, I want a day and night system acting as a round system to give players a break. So that it feels like a real job

So I have a goal to keep playing the game and to make it more fun.

### Definition of Done
- Day and night must last 30 minutes combined.
- By the end of the day the players get a paycheck.

---

---

| | |
|---|---|
| **Title** | Punishment & Reward System |
| **Sprint #** | 1 |
| **Priority** | Low |
| **Difficulty** | Easy |


### Story
As a developer, I want a paycheck that occurs at the end of the day, depending on how many objectives they completed. If the player fails to complete half of the objectives they get punished. 

So it gives reason for players to do objectives instead of doing nothing, and to reward those that do all the objectives
### Definition of Done
- Total of objectives the player has will be half and rounded up to the highest number is the total of objetives they need to complete.
- The punishment must be cruel enough but fair enough.

---

---

| | |
|---|---|
| **Title** | Database |
| **Sprint #** | 1 |
| **Priority** | Very High |
| **Difficulty** | Medium |


### Story
As a developer, I want to store players data on Roblox Servers through using their API

So I can make players data to be used in game. Example: Money, that will be used in shops and other things.

### Definition of Done
- Data being stored, can be retrieved, and is separate for every other player. 

---

---

| | |
|---|---|
| **Title** | Entities Mood System |
| **Sprint #** | 1 |
| **Priority** | Low |
| **Difficulty** | Eay |


### Story
As a developer, Entities contained in a cell will have a 0-100% chance of escaping the cell. The chance is manipulated based on the action revolving around the Entity interaction. 

So that Entities don't just stay in place the whole day, they have a chance to escape so players have to monitor the entities while balancing time to do objectives

### Definition of Done
- 3 things to change the chances, those 3 things are also the main task to complete.
- 1. Players can send test to see its beheaviour, this will increase chances
- 2. To feed entities, decrease chance
- 3. Chatting can increase and decrease chance 

---

---

# 2.0 SCRUM Style Backlog
### Product Backlog
<img width="978" height="710" alt="image" src="https://github.com/user-attachments/assets/debe93fd-f134-47c2-8c9d-21a074cb28d9" />

## 2.1 Sprint Backlog
### 2.1.1 Week 1-2 Review

**6th February 2026 - 20th February**

**What we completed**

**Sprint Backlog**
+ Objectives
+ PayCheck
+ DataBase

**In general**
+ Objectives Generation
+ Database to store player information
+ Increased Objectives
+ Day and Night System
+ Round System
+ PayCheck

**What's next**
+ NPC Creation
+ Better AI

**Problems faced**
+ Pathfinding
+ Burnout
+ Lack of time 

### 2.1.2 Week 3-4 Review

**21 February 2026 - 7th March 2026 **

**What we completed**
+ UI showing objective


**Sprint Backlog**



**In general**
+ Made objectives be connected to the UI
+ Completed a bit of the map


**What's next**
+ NPC Giving side quests
+ Rework AI Pathfinding
+ Complete more of the map
+ Script more objectives.


**Problem faced**
+ Ai Pathfinding
+ Lack of time

### 2.1.3 Week 5 Review

**7 February 2026 - 14th March 2026**

**What we completed**

**Sprint Backlog**

**In general**

**What's next**

**Problem faced**


# 3.0 Project Design

This is the part where the design choices for creating the game are made.
Exploring the overall design, devleopment strategies, the game story, characters, encironment, levels, gameplay and more.

---

## 3.1 Overall Design

### 3.1.1 Atmosphere
+ The Game will be a horror simulator game, with objectives to do and creatures roaming around.
+ Every time a player dies they experience consequences.

---

### 3.2 Development Strategy

**Methodology: Agile/Scrum**

Agile/Scrum methodology
The Project will follow the agile Methodology. Using Scrum Framework.
Agile Methodology is used in software development. Where people focus in delivering small parts of the projects and thinking

---

### 3.3 Game Design

**Game Lore**

Once in a peaceful world, suddenly turned chaotic during an eclipse. As creatures began manifesting from the dark. Causing terror across the globe. Humanity military were deployed to deal with the new threeat, all attempts were in vain as the creatures were too vast in numbers and powers. Causing humanity to create an Organization called the (CRC) to Contain, Research and Combat the creatures found in the world in hopes to restore peace in the world. 


> [!NOTE]
> This incident was named "The Eclipse Collapse" ever since the creatures manifested.


CRC
Contain: Contain all entities found in the wild.
Research: Research all information about the entities.
Combat: Combat all entities for a better future



### 3.3.1 Characters

**Main Characters**

| Name | Role | Info| 
| --- | ---| ---|
| The PLayer | Recruited Scientist | Recently Hired by the CRC |
|Emily Forrest | Head Scientist | Responsible for managing the scientist |
| Jack Uchi | Senior Security Guard | 
| James Pello | Junior Security Guard | 
| Sara Yuwilno | Junior Scientist | 

**Facility Roles**

| Role | What they'll do | Other info | 
| --- | --- | --- | 
|Scientist | Research entities and find out how to combat the entity long terms. | Normally responsible for cleaning the facility, other entities cell as well as delivering documents and testing entities |
| Guard | Ensure the entities are contained and protect Scientist | All Security guards must sacarfise their lives if a scientist is endanger. |
| Test Subject | To be test on entities | Death row inmates that were transferred and now to be tested on |



**Entities contained in the facility**

Each entity will be Catelogged using this

Number: Assigned Number 

Danger level: 
+ 1 being not aggressive
+ 5 being super aggressive

Risk of escaping:
+ 1 being unlikely they'll escape
+ 5 being monitor at all times

Classified: Animated or non-animate

Final Designation: E-111A

---

E-134A

<details>
  
  
  <summary>Click to expand</summary>
  <br>
  Name: Skin Keeper/Mimic
  
  <br>
  Danger level: 3
  <br>
  Risk of escaping: 4
  <br>
  Classified: Animated
  <br>
  Designation: E-134A (Designated number, Danger Level, Risk of Escaping, Classificatiion)
  <br><br>
  info:  <br>
  
E-134A is a humanoid shape figure covered in an unknown black liquid substance. 

E-134A normally has skin attached to their body, the skin is from their last victim they stole it from. A unique property of E-134A is the skin it steals rot faster than normal.

E-134A is generally docile. However when the skin decays to a certain degree, it will become hostile and hunt for humans, ignore animals unless attacked by one. When reaching its target, it will kill and take the skin and wear it. After enough skin has been collected, E-134A will become docile agaiin.

The Skin Keeper was contained during the beginning of the Eclipse Collapse, found in a house, docile. It later escape containment during the time it's skin fully rotted.

</details>



---

Name: The Invisible Watcher

Danger level: 3

Risk of escaping: 3

Classified: Animated

Designation: E-233A


Info:

E-223A is a tall and lanky humanoid figure, with their arms and torso being stretch than normal. E223A constantly disguises itself based on the surroundings it's in.

E-223A has shown hostile behaviour to staff and had been violent during an outbreak in Site-██. Causing it to be relocated mutiple times.

The Invisible watcher was captured in the Amazon Forest after 3 missing people suddenly appeared and warned of a tall creature. Task Force was dispatched and only a trapped creature was sent back as the rest of the Task Force were MIA.

---

Name: The Wise Banana

Danger level: 1

Risk of escaping: 1

Classified: Non-Animated

Designation: E-311NA

info:

The wise Banana was brought into containment after a Scientist had predicted multiple events such as power outage, creatures escaping, and even large scale incidents that were to happen to cities.

It was later found that the Scientist held a speaking Banana that predicted the future. The scientist had been put on administrative leave due to mishandling an entityy.

E-311NA is an ordinary banana when ripen, and will slowly unpeel itself. When unpeeled with no human interference, a face will grow on the Banana and it will develop a mind of its own, often warning dangers of events that will happen before peeling itself and ripening again to repeat the cycle.

---

Name: The unknown

Danger level: 4

Risk of escaping: 1

Classified: Non-Animated

Designation: E-441A

Info:

E-441a has no confirmed form on what it looks like. Any attempts on looking at the entity, directly or indirectly will make the viewer be forced to look away, this has been called the "Don't look effect" where no matter the life form, the head, eyes, or torso will be turned to look away no matter what. This includes to animals, robots, any concept of "looking".

This has resulted in 93 casuality from employees alike, due to the "Don't Look" effect snapping their neck as their head is turned 180 degree.

It's unknown how this Entity was brought into the custody of the CRC. Some Speculate that the facility was built around E-441A, while others say that E-441A teleported inside the cell.

---

### 3.3.2 Reward & Challenges

<h4><u>Rewards</u></h4>

Players are given a random amount of objectives to do.

Objectives are combined into three categories.

**Main Objectives**

These objectives mainly revolve around the entities.

They give higher rwards when completed.


**Side Objectives**

These objectives involve the facility itself.

It includes cleaning around the facility, restocking supplies, etc.

These don't give much reward. However there's more objectives than main.

**Requests**

These are objectives that are given by NPC and are specific to their respected NPC.

They give random rewards, Some Higher than main objective, some lower than side objectives.

---

<h1><u>Challenges</u></h1>

**Consequences**

The Consequence occur when
+  you fail to complete half of the total Objectives
+  You die

If any of these occur, your "RiskOfFiring" will be increased by one

The consequences is getting you money taken away and you getting kicked from the game if you cannot pay back the amount of value you owe --REDO THIS PART FUTURE ME

**Entities**

There will be multiple entities in the game with different mechanics. So players will have to learn how to adapt to them

Each entity will have a risk of escaping **(RIE)** value that is 1-100. The RIE can be increase and decrease by certain actions, however, the RIE will increase passviely regardless of any player input. Meaning entities must be monitored at all times.






---

### 3.3.3 Game rules



### 3.1.7 State Diagram

**Enemy AI**



### 3.1.8 Programming & Platform

LUAU a customise version of LUA

On the platform Roblox. A storage filled with thousands of games created by many. 

### 3.1.9 Map
<img width="1293" height="791" alt="image" src="https://github.com/user-attachments/assets/c3004389-9b71-479a-9998-c469ac0a712b" />
### Extra

<details>
  <summary>Click to expand</summary>
  
  This content is hidden until clicked.
  
  You can put **markdown** here too!

</details>



# 4.0 Project Management

Input Backlog, meetings
sprint backlog?
### 4.1 Test plan

Two Types of Test
Manual: Requires User Input to activate
Automatic: Can be activated with no issue.

# 5.0 Tools used

For logging Backlog, and what needs to be done. I used Jira.


The game was created on the Platform called "Roblox". Where thousands of games created by millions are stored in Roblox Servers. The way players create games is through Roblox Studio, a 3d Space where players can build anything and code with the customised lanaguage of LUA created by Roblox called LUAU.

Game engine: LUAU used by Roblox

Game Hosted: Roblox Platform

# 6.0 Test 

| What's being tested | How is it being tested | What should happen | What actually happened | Evidence | Comment |
| ---------------- | ---------------- | ---------------- | ---------------- | ---------------- | ---------------- |
| Database | Joining | When joining it creates data for the player | Done exactly like that | <img width="1478" height="651" alt="image" src="https://github.com/user-attachments/assets/8b132417-1b69-46f8-974d-f482e3592dd6" /> <br> <br>  <img width="710" height="600" alt="image" src="https://github.com/user-attachments/assets/3a97a951-1f66-43ea-aea6-bf84a4b9cabf" /> | N/A |
| Database saving | Leaving and seeing if data been saved | When leaving a message in the server should say the data been saved. Checking the database the information should be updated | No Issue | <img width="982" height="69" alt="image" src="https://github.com/user-attachments/assets/cf3a092f-a1b3-4823-9c45-c342da9bfa7f" /> <br> <br> Before: <img width="644" height="398" alt="image" src="https://github.com/user-attachments/assets/b2a84381-966c-411c-91b6-e489d48da4f9" /> <br> <br> After: <img width="672" height="626" alt="image" src="https://github.com/user-attachments/assets/9f3de3b6-f704-4de5-871e-4c25dc5f0f3c" /> | ---------------- |
| Day & Night System | ---------------- | ---------------- | ---------------- | ---------------- | ---------------- |
| ---------------- | ---------------- | ---------------- | ---------------- | ---------------- | ---------------- |

