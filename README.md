# Software Development 2 Sprint 1

# Game Design Document

# User/System Requirements

## User requirements
| User Requirement | What needs to be done | Acceptenance Criteria |
| ---------------- | ---------------- | ---------------- |
| Gameplay loop | As a player, I want to receive 5-15 objectives each shift that require 2-5 minutes each to complete. <br> <br> So that i have a clear set of tasks that I can complete during the 30 minute shift. | A list of randomise objectives given to the player. <br> <br> Objectives can be completed within 30 minutes while still having enough free time to roam around and explore. <br><br> Objectives have different types like cleaning, npc quests, etc). <br> <br> Random events occuring at random. |
| Interactive NPC | As a  | ---------------- |
| Enemies | Enemies that chase the player when in a certain distance, and attacks players. When no players, roam around the map | AI walks, Roams around, follows players, attacks player by damaging |
| Objectives | A list of objectives players can do to get paid at the end | A list of Side Tasks, Main Tasks, Extra Tasks |
| Shop | ---------------- | ---------------- |
| ---------------- | ---------------- | ---------------- |

## System Requirements
| System Requirement | What needs to be done | Acceptenance Criteria |
| ---------------- | ---------------- | ---------------- |
| Day and night System | As a developer, I want a day and night system acting as a round system to give players a break. So that it feels like a real job | Day and night must last 30 minutes combined. By the end of the day the players get a paycheck. |
| Paycheck | As a developer, I want a paycheck that occurs at the end of the day, depending on how many objectives they completed. If the player fails to complete half of the objectives they get punished. So it gives reason for players to do objectives instead of doing nothing, and to reward those that do all the objectives | Total of objectives the player has will be half and rounded up to the highest number is the total of objetives they need to complete. The punishment must be punishing enough to emit fear but fair enough. |
| Database | As a developer, I want to store players data on Roblox Servers through using their api. So I can make players data to be used in game. Example: Money, that will be used in shops. | Data being stored, can be retrieved, and is separate for every other player. |
| Entity Mood system | As a developer, Entities contained in a cell will have a 0-100% chance of escaping the cell. The chance is manipulated based on the action revolving around the Entity interaction. So that Entities don't just stay in place the whole day, they have a chance to escape so players have to monitor the entities while balancing time to do objectives| 3 things to change the chances, those 3 things are also the main task to complete. 1. Players can send test to see its beheaviour, this will increase chances, 2. To feed entities, decrease chance, 3 is chatting which can increase and decrease chance |
| ---------------- | ---------------- | ---------------- |

# Backlog
### Product Backlog
<img width="978" height="710" alt="image" src="https://github.com/user-attachments/assets/debe93fd-f134-47c2-8c9d-21a074cb28d9" />

## Sprint Backlog
### Week 1-2 Review

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

### Week 3-4 Review

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

### Week 5 Review

**7 February 2026 - 14th March 2026**

**What we completed**

**Sprint Backlog**

**In general**

**What's next**

**Problem faced**


# Project Design

This is the part where the design choices for creating the game are made.
Exploring the overall design, devleopment strategies, the game story, characters, encironment, levels, gameplay and more.

---

## Overall Design
### Atmosphere
+ The Game will be a horror simulator game, with objectives to do and creatures roaming around.
+ Every time a player dies they experience consequences.

### Development Strategy

**Methodology: Agile/Scrum**

Agile/Scrum methodology is zz
The type of methodology that will be used during


### Game Story

### Characters

### Reward & Challenges

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

<h1><u>Challenges</u></h1>


### Game rules
No exploiting

### State Diagram

### Programming & Platform

### Map
<img width="1293" height="791" alt="image" src="https://github.com/user-attachments/assets/c3004389-9b71-479a-9998-c469ac0a712b" />
### Extra

<details>
  <summary>Click to expand</summary>

  This content is hidden until clicked.
  
  You can put **markdown** here too!

</details>



# Project Management

Input Backlog, meetings
sprint backlog?

# Tools used

The game was created on the Platform called "Roblox". Where thousands of games created by millions are stored in Roblox Servers. The way players create games is through Roblox Studio, a 3d Space where players can build anything and code with the customised lanaguage of LUA created by Roblox called LUAU.

Game engine: LUAU used by Roblox

Game Hosted: Roblox Platform

# Test plan

Two Types of Test
Manual: Requires User Input to activate
Automatic: Can be activated with no issue.
| What's being tested | How is it being tested | What should happen | What actually happened | Evidence | Comment |
| ---------------- | ---------------- | ---------------- | ---------------- | ---------------- | ---------------- |
| Database | Joining | When joining it creates data for the player | Done exactly like that | <img width="1478" height="651" alt="image" src="https://github.com/user-attachments/assets/8b132417-1b69-46f8-974d-f482e3592dd6" /> <br> <br>  <img width="710" height="600" alt="image" src="https://github.com/user-attachments/assets/3a97a951-1f66-43ea-aea6-bf84a4b9cabf" /> | N/A |
| Database saving | Leaving and seeing if data been saved | When leaving a message in the server should say the data been saved. Checking the database the information should be updated | No Issue | <img width="982" height="69" alt="image" src="https://github.com/user-attachments/assets/cf3a092f-a1b3-4823-9c45-c342da9bfa7f" /> <br> <br> Before: <img width="644" height="398" alt="image" src="https://github.com/user-attachments/assets/b2a84381-966c-411c-91b6-e489d48da4f9" /> <br> <br> After: <img width="672" height="626" alt="image" src="https://github.com/user-attachments/assets/9f3de3b6-f704-4de5-871e-4c25dc5f0f3c" /> | ---------------- |
| Day & Night System | ---------------- | ---------------- | ---------------- | ---------------- | ---------------- |
| ---------------- | ---------------- | ---------------- | ---------------- | ---------------- | ---------------- |

