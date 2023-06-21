---
title: "Lecture 3 - Formal Elements"
keywords: Lecture
tags: [Lecture]
permalink:  lecture3.html
summary: lecture3
layout: presentation
presentationTheme: '/assets/css/napier.css' 
fig_caption: true
---
<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<textarea data-template>

# Lecture 3 - Formal Elements of Games
### SET09121 - Games Engineering

<br><br>
Babis Koniaris
<br>


School of Computing. Edinburgh Napier University


---

# Recommended Reading

Game Design Workshop. 3rd Edition. Fullerton (2014).

- Read Chapter 3 on Formal Elements.

- Physical books in the library & a digital copy through Safari
![GameDesignWorkshopBook](assets/images/gdw_book.jpg)


---

# What are the Formal Elements of Games?

- Fullerton defines eight elements.
 -  Players
 -  Objectives
 -  Procedures
 -  Rules
 -  Resources
 -  Conflict
 -  Boundaries
 -  Outcome

- The Formal Elements help us define games from a design perspective
- ** We can also use these elements to scope the technical features**


---

<!-- .slide: data-background="assets/images/players.jpg" style="background-color: rgba(0, 0, 0, 0.5); color: white; text-align: left; strong { color : #CC002A ;}" -->

- **Players**
- Objectives
- Procedures
- Rules
- Resources
- Conflict
- Boundaries
- Outcome


---

# Players: who plays and why?

- Games are designed for the players.
    - You must consider your game genre and target audience.
- A game should start with an invitation to play. You want to entice the player.
    - Cinemas dim their lights. <!-- .element: class="fragment" -->
    - A book uses a cover. <!-- .element: class="fragment" -->
    - A game has a title screen or introduction video. <!-- .element: class="fragment" -->
- What about the games you play? What made you buy them? <!-- .element: class="fragment" -->


---

# Social Games

- What about a game in an exhibit space? Where is the invitation?

- What happens if people join in without invitation?

- Any examples from games you play?

---

# Player Interaction Patterns

- A **Player Interaction Pattern** helps us define how players play the games.
- There are seven key types: <!-- .element: class="fragment" -->
    - Single-player versus the game. <!-- .element: class="fragment" -->
    - Multiple individual players versus the game. <!-- .element: class="fragment" -->
    - Player versus player. <!-- .element: class="fragment" -->
    - Unilateral competition. <!-- .element: class="fragment" -->
    - Multilateral competition. <!-- .element: class="fragment" -->
    - Cooperative play. <!-- .element: class="fragment" -->
    - Team competition. <!-- .element: class="fragment" -->

---

# Single-player versus the game

- A single player competes against the game system.

![SinglePlayerVersusGame](assets/images/SinglePlayerVersusGame.png)

---

# Multiple individual players versus the game

- Multiple players competes against the game system.
- They do not compete against each other and the action is not directed at other players.

![MultipleIndividualsVsGame](assets/images/MultipleIndividualsVsGame.png)

---

# Player versus player

- Two players directly compete.
- Inside games, the term "Player versus Player" might be used differently.

![PlayerVsPlayer](assets/images/PlayerVsPlayer.png) 

---

# Unilateral competition

- Two or more players compete against one single player.

![UnilateralCompetition](assets/images/UnilateralCompetition.png)

---

# Multilateral competition

- Three or more players compete against each other.

![MultilateralCompetition](assets/images/MultilateralCompetition.png)

---

# Cooperative play.

- Two or more players cooperate against the game system.

![CooperativePlay](assets/images/CooperativePlay.png)

---

# Team competition.

- Two or more groups compete against each other.

![TeamCompetition](assets/images/TeamCompetition.png)

---

# Guess the Interaction Pattern

![image](assets/images/witcher3.jpg)<!-- .element height="40%" width="45%" -->
![image](assets/images/wow.jpg)<!-- .element height="40%" width="45%" -->

![image](assets/images/hearthstone.jpg) <!-- .element height="40%" width="45%" -->
![image](assets/images/overwatch.jpg) <!-- .element height="40%" width="45%" -->


---

# Player Roles

- You need to define what the player's task is in the game.
- Traditional board and card games had everyone with the same role, more or less.
    - Some players had multiple roles -- e.g. Dungeons and Dragons. <!-- .element: class="fragment" -->
- Video games follow this tradition. <!-- .element: class="fragment" -->
    - Again, there are exceptions such as Team Fortress 2, Neverwinter Nights, etc. <!-- .element: class="fragment" -->
- Roles can also be defined by how the players react to the rules and procedures of the game. <!-- .element: class="fragment" -->
    - Players can be collectors, explorers, killers, etc. <!-- .element: class="fragment" -->
    - See Fullerton for further discussion. <!-- .element: class="fragment" -->
    - Consider the type of player that you are aiming for. <!-- .element: class="fragment" -->


---

<!-- .slide: data-background="assets/images/fortnite_win.jpg" style="background-color: rgba(0, 0, 0, 0.5); color: white; text-align: left;" -->

- Players
- ** -- Objectives**
- Procedures
- Rules
- Resources
- Conflict
- Boundaries
- Outcome

---

# Objectives: providing drive and challenge to the player

- Players are the heart of the game experience, objectives drive the experience.
- **Objectives** provide a challenge to the player that should be achievable.
- Objectives also set the overall feel of the game: <!-- .element: class="fragment" -->
    - FPS: killing and survival. <!-- .element: class="fragment" -->
    - RPG: exploration. <!-- .element: class="fragment" -->
- Objectives may also be made up of sub-objectives. <!-- .element: class="fragment" -->
    - Side quests are similar, but normally distinct. <!-- .element: class="fragment" -->



---

# Fullerton: six questions for objectives

- Fullerton poses six questions to help determine the objectives of a game:
    - What are some of the objectives of the games you have played? <!-- .element: class="fragment" -->
    - What impact do these objectives have on the tone of the game? <!-- .element: class="fragment" -->
    - Do certain genres of play lend themselves to certain objectives? <!-- .element: class="fragment" -->
    - What about multiple objectives? <!-- .element: class="fragment" -->
    - Do objectives have to be explicit? <!-- .element: class="fragment" -->
    - What about player determined objectives? <!-- .element: class="fragment" -->
- You should pose these questions to yourself when coming up with your game idea. <!-- .element: class="fragment" -->


---

# Common Objective Types

- Capture  <!-- .element: class="fragment" -->
    - Take or destroy soemthing from the oponent.  <!-- .element: class="fragment" -->
- Chase  <!-- .element: class="fragment" -->
    - Catch an opponunt or elude one.  <!-- .element: class="fragment" -->
- Race <!-- .element: class="fragment" -->
    - Reach the goal before all other players. <!-- .element: class="fragment" -->
- Alignment <!-- .element: class="fragment" -->
    - Arrange pieces in certain configurations or categories. <!-- .element: class="fragment" -->
- Rescue / escape <!-- .element: class="fragment" -->
    - Get a designated unit to safety. <!-- .element: class="fragment" -->
- Forbidden act <!-- .element: class="fragment" -->
    - Try to make other players perform a forbidden action (laughing, say a word, etc.). <!-- .element: class="fragment" -->

---

# Common Objective Types (cont.)

- Construction <!-- .element: class="fragment" -->
    - Build, maintain, and manage objects. <!-- .element: class="fragment" -->
- Exploration <!-- .element: class="fragment" -->
    - Explore different game areas. <!-- .element: class="fragment" -->
- Solution <!-- .element: class="fragment" -->
    - Solve a problem or puzzle. <!-- .element: class="fragment" -->
- Outwit <!-- .element: class="fragment" -->
    - Gain and use knowledge to defeat the other players. <!-- .element: class="fragment" -->

---

# Exercise

- What is the objective in Super Mario Bros?

![SuperMarioBros](assets/images/mario.jpg) <!-- .element height="60%" width="45%" -->

<font size=3>(Source: https://en.wikipedia.org/wiki/File:NES_Super_Mario_Bros.png)</font>

- Saving the princess?
- Reaching the end of the level?
- Jump on enemies?


---


<!-- .slide: data-background="assets/images/ed_controls.png" style="background-color: rgba(0, 0, 0, 0.5); color: white; text-align: left;" -->

- Players
- Objectives
- ** -- Procedures**
- Rules
- Resources
- Conflict
- Boundaries
- Outcome


---

# Procedures: how we interact with and control the game

- **Procedures** describe how we interact with the game world and how we can act within the game world.
- Video games typically define procedures via the input control mechanisms.
- Procedures can be broadly broken down into four categories:
    - Starting actions.
    - Progression of action.
    - Special actions.
    - Resolving actions.

---

# Example: Mario's Jump

- Mario's jump is one of the best examples of a 'simple' procedure <!-- .element: class="fragment" -->
- But it gives a huge amount of freedom and flexibility <!-- .element: class="fragment" -->

<iframe width="560" height="315" src="https://www.youtube.com/embed/7daTGyVZ60I" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> <!-- .element: class="fragment" -->

---

# System Procedures

- Video games are complex systems.
- Numerous background processes are running in a game.
    - Compare Dungeons and Dragons to a video game RPG.
- Physics, AI, etc. are all procedures within a game.
- The game engine we are developing will feature these background procedures.
- Systems are examined in the next lecture.

![image](assets/images/dnd.jpg) <!-- .element width="40%"  -->
![image](assets/images/neverwinter.jpg) <!-- .element width="40%"  -->


---

<!-- .slide: data-background="assets/images/portal2.jpg" style="background-color: rgba(0, 0, 0, 0.5); color: white; text-align: left;" -->

- Players
- Objectives
- Procedures
- ** -- Rules**
- Resources
- Conflict
- Boundaries
- Outcome

---

# Rules: defining objects and actions

- **Rules** define the objects and their possible actions in the game.

- Fullerton again poses some questions for defining rules: 
    - How do players learn the rules? <!-- .element: class="fragment" -->
    - How are the rules enforced? <!-- .element: class="fragment" -->
    - What kinds of rules work best in certain situations? <!-- .element: class="fragment" -->
    - Are there patterns to rule sets? <!-- .element: class="fragment" -->
    - What can we learn from these patterns? <!-- .element: class="fragment" -->
- Consider the rules for the game you want to develop: <!-- .element: class="fragment" -->
    - Are your game rules obvious, or do you have to provide instructions? <!-- .element: class="fragment" -->
    - Are your rules correct for the type of gameplay experience you are aiming for? <!-- .element: class="fragment" -->

---

# Defining Objects and Actions

- Rules can help us define the game objects within our game world.
    - We will discuss entities next week.
- Consider a shotgun in a FPS:
    - Cost: $500, Damage: 20 <!-- .element: class="fragment" -->
    - Spread: 10, Range: 5 <!-- .element: class="fragment" -->
    - Ammo: 2, Magazine: 12 <!-- .element: class="fragment" -->
- We can directly implement this idea in our game -- it is just an object definition. <!-- .element: class="fragment" -->
- We can also use rules to restrict certain actions for progression purposes. <!-- .element: class="fragment" -->
    - For example: Assassin's Creed series, Batman Arkham series.
- Providing all capabilities at once can confuse and frustrate the player. <!-- .element: class="fragment" -->


---

# Determining Effects

- Rules that trigger events or effects are very useful when
    considering the procedures of our game.
- We can boil down such rules to a collection of `if` statements:
    - `if player’s health == 0 then player dies.`
    - `if player pickup apple; health += 10.`
    - etc.
- It is likely that most of your rules will be effect based.


---

<!-- .slide: data-background="assets/images/blands_inventory.jpg" style="background-color: rgba(0, 0, 0, 0.5); color: white; text-align: left;" -->


- Players
- Objectives
- Procedures
- Rules
- ** -- Resources**
- Conflict
- Boundaries
- Outcome


---

# Resources: providing in-game assets


A **resource** is an asset that provides the player with an advantage, allows the player to reach certain objectives, or allows the player to perform certain procedures.


- Resources are ubiquitous in games:
 - Monopoly has money and property.
 - Command & Conquer has Tiberium.
 - Halo has health, ammunition, and shields.

 ![BorderlandsLootBox](http://lootmaster.weebly.com/uploads/3/8/1/3/38139257/7052736.jpg) <!-- .element height="250px" -->
 ![UThealthPack](assets/images/uthealthpack.jpg) <!-- .element height="250px" -->

---

# Resource Types


**Obvious Resources**

- Lives
- Units
- Health
- Currency
- Inventory
- Special terrain


**Not Obvious Resources**

- Actions
- Power-ups
- Time



---

# List Resources in the Games You Play 

List the five games you have played most recently and list the resources available in each. 

Note any similarities, particularly in games of the same genre.


---

<!-- .slide: data-background="https://i.imgur.com/nAfAZLr.gif" style="background-color: rgba(0, 0, 0, 0.5); color: white; text-align: left;" -->

- Players
- Objectives
- Procedures
- Rules
- Resources
- ** -- Conflict**
- Boundaries
- Outcome


---

# Conflict: the contradiction in objectives, procedures, rules, and resources

- **Conflict** occurs due to the contradiction between the objectives, the procedures, the rules, and the resources.
    - A great example is golf.
    - The objective is simple: put the ball in the hole ...
    - ...but the hole and ball are small ...
    - ...and you can only move the ball with a little stick ...
    - ...and the hole is away over there!
- Conflict increases challenge, which increases the fun.
- Some Conflict examples:
    - Obstacles: physical or conceptual.
    - Opponents: NPCs or other players.
    - Dilemmas: putting real choice in a game.


---

# Conflict

- It is **NOT** just "My players will shoot something".
- How will they shoot the thing?
- What makes it possible?
- What makes it difficult?
- Is there a challenge to it? Where does it come from?

---

<!-- .slide: data-background="https://i.redd.it/opkdxg3ag1my.jpg" style="background-color: rgba(0, 0, 0, 0.5); color: white;" -->


- Players
- Objectives
- Procedures
- Rules
- Resources
- Conflict
- ** -- Boundaries**
- Outcome


---

# Boundaries

- **Boundaries** define where the game is taking place.
- Games exist in a world where the formal elements exist.
    - Sometimes called the magic circle.
- Boundaries can be physical.
    - The normal approach in video games.
    - Screen boundaries, 3D world boundaries, etc. are all examples of this.
- Boundaries can be conceptual.
    - The players make an agreement to stay within the rules of the game.


---

<!-- .slide: data-background="https://i.imgur.com/pS3Pk58.jpg" style="background-color: rgba(0, 0, 0, 0.5); color: white;" -->

- Players
- Objectives
- Procedures
- Rules
- Resources
- Conflict
- Boundaries
- ** -- Outcome**


---

# Outcome

- The **outcome** is the expected payoff from playing the game.
- How do we resolve the objectives that the game sets out?
- What, if any, is the end state of the game?
- Winning is a traditional end point.
    - The game state where one of the winning conditions (objectives) has been met.
- Some games continue without end points.
    - Sim City, Factorio (if you ignore the rocket), The Sims


---

# Summary


---

# Try Describing a Game Using the Formal Elements

- After class, try and describe a game (board, video, or social) using the vocabulary of formal elements.

- Try to go into some real depth: it will help you understand games more.

- Think about the formal elements whenever you play a game. Try and pick apart the individual elements of the game to get a better understanding of how it is put together.


---

# Summary

- **Players**: who is playing our game?
- **Objectives**: what is the goal of playing the game?
- **Procedures**: how is the game played?
- **Rules**: what are the restrictions on how the game is played?
- **Resources**: what assets are available in the game?
- **Conflict**: How do the objectives, procedures, rules, and resources constrain each other?
- **Boundaries**: where is the game played?
- **Outcome**: how is the game resolved?
