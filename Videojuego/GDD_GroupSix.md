# **War of the Gods - An RPG Game**

## _Game Design Document_

---

##### ** Group 6 - Luis Rico, David Vieyra, Natalia Maya, Jose Rodriguez, Miguel Cabrera, and Joaquin Saldarriaga **

##
## _Index_

---

1. [Index](#index)
2. [Glossary](#glossary)
3. [Game Design](#game-design)
    1. [Summary](#summary)
    2. [Gameplay](#gameplay)
    3. [Mindset](#mindset)
    4. [Requirements and Rules](#resandrules)
4. [Technical](#technical)
    1. [Screens](#screens)
    2. [Controls](#controls)
    3. [Mechanics](#mechanics)
5. [Level Design](#level-design)
    1. [Themes](#themes)
        1. Ambience
        2. Objects
            1. Ambient
            2. Interactive
        3. Challenges
    2. [Game Flow](#game-flow)
6. [Development](#development)
    1. [Abstract Classes](#abstract-classes--components)
    2. [Derived Classes](#derived-classes--component-compositions)
7. [Graphics](#graphics)
    1. [Style Attributes](#style-attributes)
    2. [Graphics Needed](#graphics-needed)
8. [Sounds/Music](#soundsmusic)
    1. [Style Attributes](#style-attributes-1)
    2. [Sounds Needed](#sounds-needed)
    3. [Music Needed](#music-needed)
9. [Schedule](#schedule)


## _Glossary_

---

Before delving into the definition and conceptualization of this RPG videogame, its components and characters as well, in order to fully understand it a few key concepts must be defined:

* **Software** - Term referring to the programs and data on a laptop, that operate the devices in it.

* **GDD** - Acronym for “**G**ame **D**esign **D**ocument”; It is a document in which the requirements and functions that the video game described must comply with are defined.

* **RPG** - **R**ole **P**laying **G**ame; it's a type of game that allows you to take on the role of a fictional character in an imaginary world, make decisions about how you want that character to change, and progress through a story or series of quests; while facing challenges and improving your gamer skills.

* **Requirements** - They define what the software to be developed should do, and how. There are these types:

    * **Functional** - These describe the _behavior_ of the software, under some frameworks. They always carry a _verb_; like “check date and time”.

    * **Non-functional** - These describe properties or characteristics that the software should have; they can also encompass some of the Functional ones.

    * **Restrictions** - These are factors that define the limitations of how the developer will work; whether they are costs, which include salaries and payments to be made during work time, as well as services to be used, such as Cloud or Database storage.

* System Model (UML) - The UML is a so-called “_standardized language modeling_”; it allows developers to visualize, build and document software development (miro.com, s/f).

## _Game Design_

---

### **Summary**

The game is set in a fantasy version of the CSF campus of Tec de Monterrey. The main character, one of the members of work group, will have to face four different bosses, each with their respective powers, with the giudance of a _magical lamb_.

### **Gameplay**

What should the gameplay be like? What is the goal of the game, and what kind of obstacles are in the way? What tactics should the player use to overcome them?

The game will have pixeled-like interior setting designs, and character ones as well; yet the _outer_ part of the game environment will not: [poner imágenes]

As it was mentioned, the game will have six main characters to choose from: 

1. **Luis Rico** - .

2. **David Vieyra** - .

3. **Natalia Maya** - .

4. **Jose Rodriguez** - .

5. **Miguel Cabrera** - .

6. **Joaquin Saldarriaga** - .

Whoever the player chooses, will be guided by _Borret_; the magical lamb. He will show you four different powers to choose from:

1. **'Water'** element
2. **'Fire'** element
3. **'Plant'** element
4. **'Air'** element

With which you can start the game and subsequently fight these four bosses:

1. **Gileus** - Throws 'X', 'O', '◻', and '△' symbols at the player's character. His weakness is batteries 🔋; which you will throw at him.

2. **Octerminiti** - Thwors '$:' and 'C:\' symbols. His weakness are 'Alt-F4's, which you will throw at him.

3. **SeQueLus** - Throws 'primary' and 'secondary' keys at the character. His weakness are 'NULL' values; which the player's character will throw at him.

4. **Spordus** - Throws failed codes at the character. his weakness is _water_, so the player's character will throw water buckets at him.

The main goal is to defeat them; the last one being the hardest to fight. Each clash taking place in a different spooky magic castle; with different colors and features. It must be mentioned that the main character will have to know the waknesses of the bosses _before_ facing them off.

In addition, each boss will have his henchman: 

1. **Gileus: Beria** - His weakness is the 'fire' element.

2. **Octerminiti: Astaroth** - His weakness is the 'air' element.

3. **SeQueLus: Le Oraculo** - His weakness is the 'plant' element.

4. **Spordus: Valefar** - His weakness is the 'water' element.

Note that the weaknesses of these henchmen are the _power elements_ that Borret will give the player to choose from at first; in such a way that, depending on the element that the player chooses, one of these will be easier to defeat than the others.

### **Mindset**

As a fantasy RPG game, we want the palyer to have a mindset of wanting to go on a magical adventure, with references to things like databases and game consoles; and if the player knows the _real_ campus, they'll know that each magical castle is itself one of its class buildings.

We want the player to feel like they literally have the fate of the main character in their hands; so the latter will have to choose wisely each magic power, gems and the order of the clashes against the first three bosses.

### **Requirements and Rules**

For the development of this videogame, all the _requirements_ for the job were divided into the following types: _functional_, _non-functional_ and _restrictions_. Here are some of them:

**Functional requirements**
* The different tables of the Databases will be:
    * Bosses (Attributes)
    * Player Character (Attributes)
    * Scenarios (Attributes)
    * Match scores
* There will be a 'save progress' and checkpoints, which will be registered in one same database (F.)
* There will be a user registration system. (players)
* Eventually, every group member will have to learn how to use the 'Unity' software correctly
* Each character will have its own 'sprites'.


**Non-functional requirements**
* The user interfaces will be:
    * 'Main menu' screen
    * 'Pause' screen
* Animations; music and sound effects.
* The game's concept art will be based on the Santa Fe campus.
* For the _character customization_, there'll be four powers to choose from at the beginning of the game
* The playable characters will be all six members of the group; but the player will only be able to choose one.
* Define a "Game user manual".

**Restrictions**
* Time to finish the defined videogame: 10 weeks
* Budget: $0 pesos
* Human resources: a team of 6 people
* Skills of group members
* Final delivery date: approximately, early May
* Work rate: One sprint per week
* Game genre: **RPG** (**R**ole **P**laying **G**ame)

**Rules**

In this section, the _rules_, and _mechanics_, of the game will be discussed. These are the defined rules:

1. To progress through the Classrooms, the player must solve the level's puzzles and defeat the final boss and his minions each level without losing all their lives. Each level will be more difficult than the previous one.
2. The player will only have 4 lives per level.
3. At the beginning of the game the player can only carry one weapon. As the player progresses, they will gain different tools and abilities. He will only be able to carry a sword, special ability, and a shield. So you will have to wisely choose his inventory to beat the level.
4. In the levels there will be hidden gems that will give the hero a power for 10 seconds or an extra life in the case of acquiring the red gem.
5. There will be a type of NPC (sort of "quest givers"); who will appear before each level, and will propose a challenge to the player, in exchange for a special item (sword or shield).

On the other hand, the _mechanics_ of the game are defined in the 'Technical' section of this document!

## _Technical_ [TERMINAR PARA PROXIMA ENTREGA]

---

### **Screens**

1. Title Screen
    1. Options
2. Level Select
3. Game
    1. Inventory
    2. Assessment / Next Level
4. End Credits

_(example)_

### **Controls**

How will the player interact with the game? Will they be able to choose the controls? What kind of in-game events are they going to be able to trigger, and how? (e.g. pressing buttons, opening doors, etc.)

### **Mechanics**

Regarding the 'game controls', these _mechanics_ are:
* The player can make the character move with  the following keys:
    * 'W' to go upwards/ahead.
    * 'A' to move to the left.
    * 'S' to move backwards.
    * 'D' to move to the right.
* The playable character can crouch (agachar)  with the 'SHIFT' key.
* To interact with other characters (like Borret), doors, buttons, and chests, the player will use the 'E' key.
* With the 'left-click', the main attack will be with the sword; whereas with the 'right-click' he'll use his shield to defend himself from attacks.
* With the keys 'Z', 'X' and 'C', the _special abilities_ will be used.

What's soon to be defined, for the next submission of this document, are the Physics part, the algorithms and everything else regarding them.

## _Level Design_

---

_(Note : These sections can safely be skipped if they&#39;re not relevant, or you&#39;d rather go about it another way. For most games, at least one of them should be useful. But I&#39;ll understand if you don&#39;t want to use them. It&#39;ll only hurt my feelings a little bit.)_

### **Themes**

1. Forest
    1. Mood
        1. Dark, calm, foreboding
  2. Objects
        1. _Ambient_
            1. Fireflies
            2. Beams of moonlight
            3. Tall grass
        2. _Interactive_
            1. Wolves
            2. Goblins
            3. Rocks
2. Castle
    1. Mood
        1. Dangerous, tense, active
    2. Objects
        1. _Ambient_
            1. Rodents
            2. Torches
            3. Suits of armor
        2. _Interactive_
            1. Guards
            2. Giant rats
            3. Chests

_(example)_

### **Game Flow**

1. Player starts in forest
2. Pond to the left, must move right
3. To the right is a hill, player jumps to traverse it (&quot;jump&quot; taught)
4. Player encounters castle - door&#39;s shut and locked
5. There&#39;s a window within jump height, and a rock on the ground
6. Player picks up rock and throws at glass (&quot;throw&quot; taught)
7. … etc.

_(example)_

## _Development_

---

### **Abstract Classes / Components**

1. BasePhysics
    1. BasePlayer
    2. BaseEnemy
    3. BaseObject
2. BaseObstacle
3. BaseInteractable

_(example)_

### **Derived Classes / Component Compositions**

1. BasePlayer
    1. PlayerMain
    2. PlayerUnlockable
2. BaseEnemy
    1. EnemyWolf
    2. EnemyGoblin
    3. EnemyGuard (may drop key)
    4. EnemyGiantRat
    5. EnemyPrisoner
3. BaseObject
    1. ObjectRock (pick-up-able, throwable)
    2. ObjectChest (pick-up-able, throwable, spits gold coins with key)
    3. ObjectGoldCoin (cha-ching!)
    4. ObjectKey (pick-up-able, throwable)
4. BaseObstacle
    1. ObstacleWindow (destroyed with rock)
    2. ObstacleWall
    3. ObstacleGate (watches to see if certain buttons are pressed)
5. BaseInteractable
    1. InteractableButton

_(example)_

## _Graphics_

---

### **Style Attributes**

What kinds of colors will you be using? Do you have a limited palette to work with? A post-processed HSV map/image? Consistency is key for immersion.

What kind of graphic style are you going for? Cartoony? Pixel-y? Cute? How, specifically? Solid, thick outlines with flat hues? Non-black outlines with limited tints/shades? Emphasize smooth curvatures over sharp angles? Describe a set of general rules depicting your style here.

Well-designed feedback, both good (e.g. leveling up) and bad (e.g. being hit), are great for teaching the player how to play through trial and error, instead of scripting a lengthy tutorial. What kind of visual feedback are you going to use to let the player know they&#39;re interacting with something? That they \*can\* interact with something?

### **Graphics Needed**

1. Characters
    1. Human-like
        1. Goblin (idle, walking, throwing)
        2. Guard (idle, walking, stabbing)
        3. Prisoner (walking, running)
    2. Other
        1. Wolf (idle, walking, running)
        2. Giant Rat (idle, scurrying)
2. Blocks
    1. Dirt
    2. Dirt/Grass
    3. Stone Block
    4. Stone Bricks
    5. Tiled Floor
    6. Weathered Stone Block
    7. Weathered Stone Bricks
3. Ambient
    1. Tall Grass
    2. Rodent (idle, scurrying)
    3. Torch
    4. Armored Suit
    5. Chains (matching Weathered Stone Bricks)
    6. Blood stains (matching Weathered Stone Bricks)
4. Other
    1. Chest
    2. Door (matching Stone Bricks)
    3. Gate
    4. Button (matching Weathered Stone Bricks)

_(example)_


## _Sounds/Music_

---

### **Style Attributes**

Again, consistency is key. Define that consistency here. What kind of instruments do you want to use in your music? Any particular tempo, key? Influences, genre? Mood?

Stylistically, what kind of sound effects are you looking for? Do you want to exaggerate actions with lengthy, cartoony sounds (e.g. mario&#39;s jump), or use just enough to let the player know something happened (e.g. mega man&#39;s landing)? Going for realism? You can use the music style as a bit of a reference too.

 Remember, auditory feedback should stand out from the music and other sound effects so the player hears it well. Volume, panning, and frequency/pitch are all important aspects to consider in both music _and_ sounds - so plan accordingly!

### **Sounds Needed**

1. Effects
    1. Soft Footsteps (dirt floor)
    2. Sharper Footsteps (stone floor)
    3. Soft Landing (low vertical velocity)
    4. Hard Landing (high vertical velocity)
    5. Glass Breaking
    6. Chest Opening
    7. Door Opening
2. Feedback
    1. Relieved &quot;Ahhhh!&quot; (health)
    2. Shocked &quot;Ooomph!&quot; (attacked)
    3. Happy chime (extra life)
    4. Sad chime (died)

_(example)_

### **Music Needed**

1. Slow-paced, nerve-racking &quot;forest&quot; track
2. Exciting &quot;castle&quot; track
3. Creepy, slow &quot;dungeon&quot; track
4. Happy ending credits track
5. Rick Astley&#39;s hit #1 single &quot;Never Gonna Give You Up&quot;

_(example)_


## _Schedule_

---

_(define the main activities and the expected dates when they should be finished. This is only a reference, and can change as the project is developed)_

1. develop base classes
    1. base entity
        1. base player
        2. base enemy
        3. base block
  2. base app state
        1. game world
        2. menu world
2. develop player and basic block classes
    1. physics / collisions
3. find some smooth controls/physics
4. develop other derived classes
    1. blocks
        1. moving
        2. falling
        3. breaking
        4. cloud
    2. enemies
        1. soldier
        2. rat
        3. etc.
5. design levels
    1. introduce motion/jumping
    2. introduce throwing
    3. mind the pacing, let the player play between lessons
6. design sounds
7. design music

_(example)_