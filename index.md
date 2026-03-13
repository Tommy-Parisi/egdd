# REPLACE THIS WITH YOUR GAME NAME

# Case by Case

## Elevator Pitch

In Case By Case, 

you play the role of the defense attourney, presenting evidence to keep the on-trial function out of jail. 

you play the role of the prosecutor, presenting evidence to put the on-trial function in jail. 

--(not sure how we handle this, depending if the function is bad or good we would play a different role? will the player choose? need your thoughts on this)--

Choose your evidence carefully, craft your case, because the jury wont be easily convinced. Players learn to spot edge cases, evaluate coverage, and think about tests in a high stakes environment. 


## Influences

- The American Judicial System
  - Medium: Trial Recordings, Court TV, "True Crime" Court Case Explainations  
  - Explanation: Case By Case is set in a court room and the regular rules of this domain apply. Trials, juries, evidence, the defence and prosecution
- *Influence #2*: Jackbox Games
  - Medium: Games
  - Explanation: The visual style and and game flow of Jackbox games inspires my thinking about Case by Case. The player will have to pick between test cases on the screen and we need to make this fun and visually appealing. Smitty-style narration and quips, funky music, cool animations, and a fun court house design inspired by Jackbox.TV. 
- *Influence #3*:
  - Medium: *(Television, Games, Literature, Movies, etc.)*
  - Explanation: *In one paragraph or less, explain why this is an influence.*
- *Influence #4*:
  - Medium: *(Television, Games, Literature, Movies, etc.)*
  - Explanation: *In one paragraph or less, explain why this is an influence.*

## Core Gameplay Mechanics 

*Give a very high-level description of any core gameplay mechanics*

- Players evaluate small program functions by selecting a limited number of test cases from a larger pool.
- Each selected test case is treated as evidence about function behavior.
- Players must decide which evidence is most meaningful.
- The game issues confidence-based verdicts. 

# Learning Aspects

## Learning Domains

*Briefly list any and all of the disciplines and learning domains for this subject.*

Test evaluation and reasoning about program behavior.

## Target Audiences

Computer Science Students: intro to intermediate level
- Students learning to write unit tests for the first time who dont fully understand *why* or *which* tests matter.

Engineering Educators: not players themselves but buyers for their curriculum. This game is a good fit for a QA or Intro to CS course. 

## Target Contexts

*Describe what kinds of formal and informal learning contexts this will be used in (e.g., courses, k-12 computer labs during free time).*

## Learning Objectives

*Remember, Learning Objectives are NOT simply topics. They are statements of observable behavior that a learner can do after the learning experience. You cannot observe someone "understanding" or "knowing" something.*

- *Test Case Evaluation*: Evaluate the quality of selected test cases as evidence.
- *Coverage Reasoning*: Recognize when test coverage is insufficient for a strong verdict.
- *Edge Case Reasoning*: Reason about edge cases when assessing function behavior.

## Prerequisite Knowledge

*What do they need to know prior to trying this game?*

- *Prerequisite Learning Objective #1*
- *Prerequisite Learning Objective #2*

## Assessment Measures

*Clearly identify a set of viable assessment questions AND their grading logic. The questions should be specific examples of the kinds of questions that your game could conceivably improve student performance on. For the grading logic, it could be the correct answer, a rubric for evaluating the answer, or exact logic for deriving answers.*

# What sets this project apart?

*Give some reasons why this game is not like every other game out there. Whether the learning objective is unique, the gameplay mechanics are new, or what. You should persuade the reader that your game is novel and worthy of development. Consider arguments that would be persuasive to a Venture Capitalist, Teacher, or Researcher. These might be focused on learning needs, too.*

- Confidence in function behavior depends on selected evidence quality.
- Functions can appear correct but still lack enough evidence for a strong verdict.
- Functions can appear broken due to misleading or flawed test cases.

# Player Interaction Patterns and Modes

## Player Interaction Pattern

*Describe how people play your game, how many players are involved at once, how they interact with the system works, etc.*

## Player Modes

*Your game has one or more player modes. Describe each discrete mode, considering things like menus too. Generally describe the transitions between modes too.*

- *Player mode #1*: *Description*
- *Player mode #2*: *Description*
- *etc.*

- Title Screen: CASE BY CASE title screen with buttons: {Play} {Settings}, {}, {}
- Player picks {Play}: Court room doors open and we zoom up to the stand, a function sits at the defendant table, Judge Case sits atop the bench, jury is visible on one side.
- Main Game Loop: There exist test cases visible that we must sift through and pick a few as evidence. Exhibit A, Exhibit B, ... Exhibit N. The test cases are then applied to the function, (this is where I dont really know what happens)
- Jury Deliberation: breif time for the jury to deliberate over the evidence, im picturing sillutttes talking to eachother behind some wall or curtain, maybe showing each piece of evidence and their thoughts  
- Verdict: Jury comes back, some say guilty and others say innocent, majority rules. 

The jury's decision will be difficult to implement, they have to make decisions based on the function as well as the evidence. 

IF the function is correct or well written:
- but the evidence was poor: we may get a false imprisionment and the player will be disbarred or something. 
- and the evidence is solid: the function is innocent (yay)

IF the function is poorly written and full of bugs or errors:
- and the evidence is poor: the function may be declared innocent because edge cases or bugs were missed by the cases, this function is then out on the streets to one day reoffend and crash someones server
- and the evidence is solid: the function is found guilty and put in jail (yay)

# Gameplay Objectives

- *Primary Objective #1*:
  - Description: *Description*
  - Alignment: *Describe how this aligns with one or more learning objectives*
- *Primary Objective #2*:
  - Description: *Description*
  - Alignment: *Describe how this aligns with one or more learning objectives*
- *etc.*

- *Primary Objective #1*:
  - Description: Select meaningful test-case evidence from a larger pool.
  - Alignment: Evaluate the quality of selected test cases as evidence.
- *Primary Objective #2*:
  - Description: Build confidence-based verdicts about function behavior.
  - Alignment: Recognize when test coverage is insufficient for a strong verdict.
- *Primary Objective #3*:
  - Description: Improve reasoning about test quality, coverage, and edge cases.
  - Alignment: Reason about edge cases when assessing function behavior.

# Procedures/Actions

*Describe the control scheme and what actions a user can take in the game.*

Players select a limited number of test cases from a larger pool to evaluate each function.

# Rules

*What resources are available to the player that they make use of?  How does this affect gameplay? How are these resources finite?*

- Players cannot submit every test case.
- Each selected test case acts as evidence for the function on trial.
- Verdict strength depends on the quality of chosen evidence.

# Objects/Entities
*What other things are in the world that you need to design? These may or may not directly translate to actual objects and classes.*
- Small program functions.
- A pool of available test cases.
- Selected test cases as evidence.
- Confidence-based verdicts.
- Jury of decision makers

## Core Gameplay Mechanics (Detailed)

- *Core Gameplay Mechanic #1*: *Describe in 2 paragraphs or less, along with how it generally works*
- *Core Gameplay Mechanic #2*: *Describe in 2 paragraphs or less, along with how it generally works*
- *Core Gameplay Mechanic #3*: *Describe in 2 paragraphs or less, along with how it generally works*

- *Core Gameplay Mechanic #1*: Each function is presented as being "on trial." Players choose only a limited subset of test cases as evidence.
- *Core Gameplay Mechanic #2*: Confidence in behavior is based on evidence quality, not proof of correctness. Outcomes are confidence-based verdicts rather than binary pass/fail.
- *Core Gameplay Mechanic #3*: Players learn through identifying strong, weak, misleading, and insufficient evidence.

    
## Feedback

*Explicitly describe what visual/audio/animation indicators there are that give players feedback on their progress towards their gameplay objectives (and ideally the learning objectives).*

*Describe what longer-term feedback you detect and give that guides the player in their learning and lets them know how they are doing in regards to the learning objectives.*

- Verdicts reflect confidence based on selected evidence.
- Stronger evidence supports stronger confidence in behavior.
- Misleading or flawed evidence can produce weak or incorrect conclusions.
- A Jury will decide at the end of the trial whether or not the function is GUILTY, the jury needs a majority to convict and the amount of jurors voting either way will be displayed. (confidence-based verdict)

# Story and Gameplay

## Presentation of Rules

*Briefly describe how the player will learn the gameplay mechanics. Avoid using walls of text, since people will not read them. Think instead of natural ways of teaching mechanics iteratively and slowly.*

## Presentation of Content

*Briefly describe how the player will be taught the core material they are meant to learn. Avoid using walls of text, since people will not read them. Think instead of natural ways of teaching material iteratively and slowly.*

## Story (Brief)

*The Summary or TL;DR version of below*

Functions are framed as being "on trial," and players present test-case evidence to support confidence-based verdicts.

"ALL RISE FOR THE HONORABLE JUDGE CASE"

The gavel slams as the clock strikes 8:00 AM. Judge Case has many a trial to attend to and YOU must provide evidence to prove the GUILT or INNOCENCE of the on-trial functions.

## Storyboarding

*Go into as much detail as needs be to visually convey the Dynamics of your game. Be detailed. Create storyboards and freeze frame images that concisely capture important key elements of your game. You are strongly recommended to sketch pictures on paper and embed them here. Be sure make it clear how previously-described mechanics come through in the dynamics.*

# Assets Needed

## Aethestics

*Give a sense of the aesthetics of your game, the spirit and atmosphere. Use descriptive, evocative words that can help the reader understand the emotional response of your game.*

## Graphical

- Characters List
  - *Characters 1*
  - *Characters 2*
  - *...*
- Textures:
  - *Texture 1*
  - *Texture 2*
  - *...*
- Environment Art/Textures:
  - *Environment Texture 1*
  - *Environment Texture 2*
  - *...*


## Audio


*Game region/phase/time are ways of designating a particularly important place in the game.*

- Music List (Ambient sound)
  - *Game region/phase/time*: *Example 1*, *Example 2*
  - *Game region/phase/time*: *Example 3*, *Example 4*
  
*Game Interactions are things that trigger SFX, like character movement, hitting a spiky enemy, collecting a coin.*

- Sound List (SFX)
  - *Game Interaction*: *Example 1*, *Example 2*
  - *Game Interaction*: *Example 3*, *Example 4*


# Metadata

* Template created by Austin Cory Bart <acbart@udel.edu>, Mark Sheriff, Alec Markarian, and Benjamin Stanley.
* Version 0.0.3
