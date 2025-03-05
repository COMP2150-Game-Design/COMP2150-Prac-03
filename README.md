# Week 03 - Toys & Discovery
![An image of the starting "testing grounds" scene](images/testinggrounds.png)

In today's class, you will begin working on your Level Design Task by exploring the possibility space of the player avatar Ellen and some of the prefabs you'll use in the assignment.

## Tools used
Today's task uses (but is not limited to):

* Github Desktop (or your Github client of choice)
* Unity

## Assignment deliverable
Today, you will be getting familiar with the Level Design Task and by building a small "testing grounds" level and investigating the possibility space of the player character and other objects.

## Task 1 - Assignment Spec (15 min)
To start today, head over to iLear and click the link accept the Level Design Task assignment. This will give you your own repo that contains everything you need for Assignment 1. Take some time to read through the README.md file - this is your assignment spec. Note down any questions you have so you can ask in the lectures or on iLearn. Return to this document once you've read through the README.md.

...Welcome back! As you now know, the assignment asks you to create a single level using the provided toolkit. But before you dive into making your level, you need to think a little bit about the type of game you are making. Does the "toy" you are playing with better relate to a precision platformer? Maybe more of a side-scrolling puzzle game, or something very action focused? 

Before you can answer these questions, you'll need to get more familiar with the toy(s) of Ellen, the various platforming and combat objects, etc. That's what you'll be doing today.

Open up the Unity project inside the Level Design Task repo, thne open `Assets > Scenes > Testing`. You'll be building here today. This is a step towards completing your assignment, so make sure you are pushing to Github regularly.

## Task 2 - Verbs: Move, Jump, Shoot, Swing (10 min)
The scene you've opened up is a Testing Grounds for experimenting with and playing with the Ellen toy. The creation of big testing levels (sometimes called "gyms") is a common design practice that allows game designers to get a feel for the objects in the game - in this case - find what is fun about them.

The first thing we want to play with is the toy of Ellen, our player avatar. A small scene has been set-up for you that gives you space to run around as Ellen and interact with a few objects.

The darker coloured, mossy platforms are "pass through" platforms. Ellen can fall through them by pressing down and jump at the same time. To move back up, Ellen just has to jump through them.

There are also gun and staff pick-ups in the small level.

Spend some time playing around with Ellen in this space, including using weapons. Observe how Ellen moves, how jumping operates, and how using weapons feel.

Consider what is fun about the Ellen toy. What mechanics are interesting to mess around with? What dynamics emerge as you start to combine them (walking and jumping, shooting and jumping, walking and swinging, etc). Note:

* What are all the verbs of what Ellen can do? Did we miss any?
* What happens when mechanics are combined? What does combining them allow the player to do?
* What are some rules of the game world the player is beholden to? Can they jump forever? Run through walls, etc.?

This info should start to give you a good idea as to what is fun about this toy, and therefore the kind of game to build. However, we haven't seen Ellen interact with too many Objects yet...

## Task 3 - Platforming Experiments (15 min)
You've already been introduced to the two main platforming objects in the game: the passthrough platforms and the moving platforms. Have a look in the `Assets > Prefabs > Required` folder and start to build out your own small section of the Testing Grounds level using these prefabs. You can delete parts of what is already there - this is your Testing Grounds now!

For the moving platforms, you can press the "Add Node" button in the Inspector to add a new node on its movement path. WIth Gizmos turned on in the Scene view, you can reposition these nodes using the normal translation tools in the scene view.

You can also alter the speed, Platform type, and when the platform beings moving via the inspector. Make a few different types of moving platforms (naming them appropriately!), and position them in a way that you can spend some time jumping and running between them.

Note down what is fun or interesting about these moving platforms and how they operate. 

Do the same for the passthrough platforms, then try combining the two into a small sequence. Consider some low-level goals/challenges you can give yourself here, e.g. dropping from a passthrough platform onto a fast moving platform, or making a series of tricky jumps between platforms to make it to stable ground.

An example of a small testing sequence with moving platforms:

![An example gif of using moving platforms.](images/movingplatformsequence.gif)
Consider how modifications and interactions with these objects contribute to different types of player experiences.

Push your scene to Github now so you have a snapshot of this environment as it currently is.

### Hazards
So far, things are pretty safe for our player. But as we discuss in the lecture, adding hazards can allow us to create more interesting encounters and give a sense of urgency and danger for the player.

In `Assets > Prefabs > Required` there is a Spikes prefab and an Acid prefab. The Spikes will bounce Ellen back and take off one health. The acid pit will send Ellen back to the last Checkpoint (beginning of the game if there are no Checkpoints).

Again, try testing these in isolation: think about the knock back on Ellen, as well as the colliders on both the acid and spikes.

Then, try incorporating some of these hazards into your platforming design. How does play change if there are spikes on the walls? An acid pit moving along a platform? Make some notes and remember to push to github again so you can return to this version of your Testing Grounds later.

## Task 4 - Combat Experiments (10 min)
In addition to the platforming, the game also contains weapons (gun and staff) and enemies (spitters and chompers) for the player to engage with. 

Create a new section of your Testing Ground to start playing around with these enemies. Try building an area that allows you to escape if necessary. For example:

![Chomper testing area.](images/chomper.png)

Note down:

* How does the Chomper respond to the player when they get close? Are there any windows for attack?
* How far is the Spitter's range? What can the Spitter's attack go through?
* What weapons work best against the Chomper and the Spitter?
* What happens when you put a bunch of Chompers or Spitters together?

Again, try to create a sequence that is fun to mess around in and gives you a good idea as to the dynamics that emerge when engaging with the combat system's various objects and verbs (the chomper, the spitter, the gun and the staff). Think about the kind of player experience this can lead to.

Push your project to ensure you capture this version of your Testing Grounds.

## Task 5 - Puzzles and other Experiments (10 min)
By now you should have a good idea as to the flow of this prac, and have explored all Required Prefabs for the assignment that are applicable (we'll look at the keys and door another week). However, there is another folder: `Assets > Prefabs > Optional` that contain 

## Task 6 - "Your" toy and Experiments (Until end)
By now, you've been introduced to the three main categories of objects in your toolkit. However, there's plenty more to play with depending on the type of game you'd like to make. 

### Reflect
Include a section on reflection to ensure students are doing something with their knowledge in the moment.

## Next Week
Brief statement on next week's lab.
