# GDIM32 In Class Activities

## Week 1

### Activity 1

- Read the pre-learning slides
- Make notes
- Do not procrastinate
- Use out of class tools (YouTube / Unity documents)
- Take advantage of support when in need of assistance: peers, LAs, Office hours and discord
- Ask questions
- *Learn how to use the inspector
- Create map concepts 
- Make sure your itch links work for the love of god
	
### Activity 2
- Q1: 10
- Q2: 2
- Q3: Print “hello world” in the console every frame
- Q4: MonoBehavior
- Q5: Print “x = 10” in the console when the program starts
- Q6: The “(10)” is the integer assigned to show along with the text “x = ” together that's why we need to use the “+” sign to display “x = 10”. (10) is an argument. (“x = 10” + x) is a parameter.
- Q7: The _playerTransform variable is instantiated but never used
- Q8: Transform.Translate should be replaced with _playerTransform.Translate

### Activity 3
[MG1Breakdown](https://docs.google.com/document/d/1hYNliasaT5HCwedvTw8yrg4QrNS10bXhExGOnQw6uGg/edit?tab=t.0)



## Week 2

### Activity 1
<img width="2360" height="1640" alt="IMG_9924" src="https://github.com/user-attachments/assets/a92ddf09-5491-4b64-a953-e70ab07d34a1" />

### Activity 2
[Commits](https://github.com/UCI-GDIM32-W25/mg2-Laura27Apr/commits/main/)

I have created "Player", "Coins","GameController" and "Ground" in the Unity. And I added Rigidbody2D and Capsule Collider 2D for player and coins, and I added Box Collider 2D for Ground. I also tagged each gameobjects. For coding, I created classes for them and I maded the Player jump successfully.


## Week 3

### Activity 1 & 2
Bilal Payton

### Activity 3
<img width="2360" height="1640" alt="0120" src="https://github.com/user-attachments/assets/b502c931-bb11-4542-b7ba-839801888019" />



## Week 4

### Activity 0
Bilal Payton, Alejandra Perez

### Activity 1
Only one Locator will work, and the other Locator on the other gameobjects will disappear. This is because Locator follows the Singleton design pattern.

### Activity 2
<img width="2360" height="1640" alt="0127" src="https://github.com/user-attachments/assets/a9a28b3b-18b2-444c-b9e2-d28a53ae8b10" />


### Activity 3
[Commits](https://github.com/Laura27Apr/mg4/commits/main/)
I have sliced the tiles and the birds. I also changed the camera orientation from free aspect to portrait (8:16 ratio). Moreover, I have created Player as a gameobject, and add capsule collider 2D, Rigidbody 2D, and Sprite Renderer.



## Week 5

### Activity 1
I think the design of these interfaces and abstracts work well. In this situation, the abstract class Item makes all the things to experience "Use()" and at the same time the Interface is responsible for defining the actions of items that are completely different but share some features.. I think I would keep it the same because it is clear and organized.


### Activity 2
In Demo2, EnemyStats and Item represent the Model; InventoryUI and Dialogue represent the View; and the Player and the Enemy represent the Controller.


### Activity 3


#### Scenario 1 Rhythm Game
This game used:

- ScriptableObjects: Different beats have different data.


#### Scenario 2 Team Shooter
This game used:

- Model-View-Controller: The Model might be the data of characters and their skills; the View might be the animations and VFX of the different attacks and the UI; the Controller might be the player itself and the enemy.


#### Scenario 3 Stardew Valley
This game used:

- Finite State Machine: Plants own different states.



### Activity 4
Attendance: Bilal Payton, Bella Sloan, Laura Liu

[Final Project Proposal](https://docs.google.com/document/d/11w2xkRcvvsdrWrjTOsVOLnSm630WmjlCOwrMvn1rDKk/edit?usp=sharing)


## Week 6

### Activity 1
- Gizmos can be used to visualize invisible data in the scene window;
	- I think in our game we may use Gizmos a lot since we are going to have zombies to detect the range between the Player and themselves and then give reactions. Gizmos can help us to see the attack sphere clearly.


- Profiler can be used to analyze the causes of slow game performance;
	- I think we may use this to check our GPU and CPU when there is a battle between the zombies and the Player, since battle scene may consumes a lot of them.


- Breakpoints can let us to pause the game at specific lines of code;
	- I think we will use this to check whether the Player's action is delivered to the AudioController or not when the audio does not play but the action does go.


- Merging is a good tool for mitigate conflicts when there is mutiple version of the game file or multiple people edition;
	- I think this is really a basic tool for us since this is a team project and we may have lots of the version. 


### Activity 2
Attendance: Bilal Payton, Bella Sloan, Laura Liu

[Final Project Proposal](https://docs.google.com/document/d/11w2xkRcvvsdrWrjTOsVOLnSm630WmjlCOwrMvn1rDKk/edit?usp=sharing)


## Week 7

### Activity 1

Raycast: 
- Like firing an invisible laser beam from a point in a certain direction;
- Line of sight
	- Requires origin and direction
- Obstacles Detection
	- Sphere may be more suitable since there is situation which head can go over the obstacles but the body cannot
- _raycastDir
- _raycastStart (local)

Gizmos:
- We can use different color for different GameObjects
- Gizmos.DrawRay
- Gizmos.DrawWireSphere

### Activity 2
Attendance: Bilal Payton, Bella Sloan, Laura Liu


### Activity 3


### Activity 4
[Tasks](https://trello.com/b/RdVdKvnk/gdim-32-final-project-the-goated)


### Activity 5
[Commits](https://github.com/BilalPayton/The-Goated-GDIM32-Final/commits/main/)