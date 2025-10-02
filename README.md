# Software-Engineering-Match

# <ins>**_Project Activities_**</ins>

As a team we have discussed and reviewed each of the 3 options given to us, Jigsaw offers a highly interactive experience however there is limited complexity in gameplay, people can easily get tired of repeatedly doing the same thing. Cross word provides a strong cognitive challenge and increases critical thinking skills however for children they may find it too complex and it requires knowledge or guessing which for beginners may loose interest quickly. In the end  We have chosen to go with basing our project off of "Match". We feel we will be able to scale tasks and produce the best ideas for this concept. More so, the task can evolve to fit different themes from geography to professions, it provides a wide range of educational and fun ideas that fit multiple age demographics.

For our primary target audience, we have put into consideration that mainly two groups of people will be playing a game like Match, such as younger children in an educational environment or older people during timepass.

# <ins>**_Game Display, Rules and Mechanics_**</ins>

The game will start by displaying a prompt asking you to pick a level between child and adult. Next it will display a set of rules following the game mechanics via a prompt, Once accepted or declined the game will either print "thank you for playing" or it will load you into the game. In the beginning before the game starts there will be a prompt at the bottom saying if you want to quit at any time type "QUIT", this will be accessible for both modes. Once loaded into the game, if selected child a variety of images will pop up, you have to select/drag the right word to the right image to get a score of +1. To win the game you need to get a score of 5/5. If the child gets one wrong the game will prompt "that's incorrect try again!", it will repeat this prompt in a loop until it is correct and then the loop breaks. However if you have selected adults a variety of words will pop up with several categories and the objective is to match up the words to their corresponding categories. Once selected a variety of words into the correct category you get +1, to win you need a score of 5/5. However if you get one wrong the game will prompt "that's incorrect try again!", you get three lives before it prompts "game over" if you did not get it correct. 

The game rules will begin in the following format:

----------------------------------------------------

**Welcome to Match!**
*Please choose Child or Adult Mode* 

----------------------------------------------------

**How to Play? (Child)**

Match the word to the picture.

Once all the pairs are matched, the game is over.

Do you wish to accept ?

----------------------------------------------------

**How to play? (Adult)**

Match the word into the category 

One all the pairs are matched up, the game is over.

You have 3 lives.

Do you wish to accept ?

----------------------------------------------------


In adult mode the game is controlled by 3 lives and words, whereas in the child mode the game is controlled by pictures and infinite lives, both options are able to quit the game at any time.

# <ins>**_User Profiles_**</ins>

----------------------------------------------------

**_User Profile 1: Child gamer_** 

Name: Leah Carter

Age: 5

Location: Paris, France

Gaming experience: Plays on her mini ipad on games like colouring books, minecraft, mario kart

**Wants/Needs;**

-Easy to understand controls
  
-Bright pictures with bright colours

-Positive Feedback (well done!)

-Quick Levels

**Frustrations**

-Leah has a short attention span

-She doesn't like overly hard levels

----------------------------------------------------

**_User Profile 2: Adult Casual Gamer_**

Name: Fred Patel 

Age: 36

Location: Bournmouth, UK

Gaming experience: Casual gamer, owns and plays on a pc, enjoys puzzle games

**Wants/Needs:**

-Short sessions (able to play during lunch breaks

-Smooth and aesthetic UI

-More challenging levels (challenging topics with a timer to complete level in)

-Option to quit at any time

**Frustrations:**

-Doesn't have enough time to spend a long time on one level

-Hates games that don't include lives or a way you can loose

----------------------------------------------------

The game will be based off of 2 user profiles; **Child and Adult**. These profiles will serve as difficulty levels, the child variation catering towards an easier mode, with images. This is to make the game more interactive and easily accessible for a younger person. The younger person will want a game that is easy to play/understand, that does not require a range of skills and a game that interests them with colourful photos. The childs needs will be a simplistic game mode with few functions that make it fun and enjoyable to play. 

The adult mode will be based on categories and lives to which general words can be matched. This is to add difficulty to the game concept, and force the user into decision making. The adult person will want a game that can be challenging at times, something that is a bit more intellectual (word categories instead of photos) as well as the ability to loose the game via volume of lives they have. Their needs include similar things where the game has multiple levels and functions with ability to quit the game at any point. 

# <ins>**_Functional Specifications_**</ins>

**Minimum Requirements**
- Processor: 1.6 GHz or faster
- RAM: 4 GB
- Storage: 4 GB available space
- Operating System: Windows 10
- A desktop with input devices

# <ins>**_High Level Applicational Functions_**</ins>

- An interactive menu, that prompts user to choose between the two user profiles / gamemodes available "Child" and "Adult".
- A rules and instructions screen that displays the objectives of whichever mode is chosen by the user.
- A "drag and drop" mechanism for the child mode, to match the images.
- A quit function that is accessible throughout the entirety of the playthrough, by typing "quit" to exit.
- A scoring and penalty system, that awards +1 points for each correct match, setting a win condition at 5 points, while deducting -1 point per incorrect match (for adult mode), ending the game at 0 lives.
- Replayability function, as offered by the prompt to replay at the end of each round.
- A timer mechanism will be included within the adult user profile, serving as added difficulty, where there can be a short timer per round for the adult to be able to make their decision, otherwise they will lose a life.
- AI Logic is necessary for a more dynamic difficulty, such as being able to adjust accordingly according to the user profile chosen. 
- Collisions will be involved primarily in the child user profile, to detect if the images are dragged and dropped where they should be.

# <ins>**_High Level Non Funtional specifications_**</ins>

**Aesthetics** 

The Match game will have a clean and minimalistic layout/design. For the child mode the aesthetic will contain colourful and playful images (shapes, cartoons, animals). The font will be a nice simplistic font that is easy to read and comprehend, finally the images for the child mode will be high quality and large enough to properly gather what the image displays. 

**Usability**

The game will have a simple navigation system with clear visual cues to understand what next to do, the game allows users of all ages to understand the game mechanics and get started to play the game without any prior skills or experience. There will be two different modes for adults and children so we cater for all ages.

**Feedback style**

Users playng the game will immediately receive feedback/comments after selecting "complete" when the user wants to see if they haved passed or failed the level. More so there will be positive reinforcement once a correct action is completed users will be rewards with a "correct!" +1

**Basic needs**

There will be two different modes that you can choose "adult" or "child", inside this there will be a possibility for a variety of levels for this game. Upon the game starting after selecting adult or child, the game will display the apropriate rules and instructions based on the mode selected. There will also be an option to restart and quit at any time, this will be via a user typing "QUIT", this will break the entire game at any time. 


**Error handling** 

If a user selects the wrong answer, they will be prompted to try again. If you have selected the child mode, the incorrect answer will trigger a repeat prompt until it is correct, however for the adult mode, the player will be given three chances before the game ends with a prompt saying "Game Over!".

# <ins>**_StoryBoards_**</ins>

**Storyboard 1 (Welcome Screen)**

Title: "Welcome to the Matching Game!"

Prompt: “Please choose your level:”

[Child Mode]

[Adult Mode]

Note at bottom: “To quit at any time, type ‘QUIT’.”



**Storyboard 2 (Rules & Mechanics)**

Title: "Game Rules"

Text changed based on level selected

Child Mode: “Match the word to the correct image. Get 5 right to win! If you make a mistake, you’ll try again until it’s correct.”

Adult Mode: “Match the word to the correct category. You have 3 lives. Get 5 right to win!”

Prompt

[Accept Rules]

[Decline Rules]



**Storyboard 3 (Decline Rules Flow)**

Text: “Thank you for playing!”

Action: Game ends.



**Storyboard 4 (Game Start)**

Text (bottom of screen): “To quit at any time, type ‘QUIT’.”

Storyboard 5: Child Mode – Game Play Loop

Visual: 3–5 images displayed (e.g., dog, apple, car)

Draggable words: "Dog", "Banana", "Car", etc.

User Action: Drag the correct word to correct image.

Feedback:

✅ Correct: +1 Score. Move to next image.

❌ Incorrect: Prompt – “That’s incorrect. Try again!” (Loop until correct)

Score Tracking: Score displayed at top (e.g., “Score: 3/5”)

End Condition: When Score = 5/5 → Go to Win Screen.



**Storyboard 6 (Adult Mode – Game Play Loop)**

Visual: Categories displayed (e.g., Animals, Fruits, Vehicles)

Words appear: "Dog", "Car", "Banana", etc.

User Action: Drag words into correct categories.

Feedback:

✅ Correct: +1 Score

❌ Incorrect: “That’s incorrect. Try again!”

Lose 1 life

Show remaining lives (e.g., "Lives: 2/3")

Lose Condition: If 0 lives → “Game Over”

Win Condition: Score = 5/5 → Go to Win Screen



**Storyboard 7  (Win Screen)**

Text: “Congratulations! You won the game!”

Prompt: [Play Again] or [Exit]

Storyboard 8: Game Over (Adult Only)

Text: “Game Over! Better luck next time.”

Prompt: [Try Again] or [Exit]

----------------------------------------------------

# <ins>**_Mockups_**</ins>

**MAIN MENU:**

<img width="1118" height="710" alt="image" src="https://github.com/user-attachments/assets/bf875143-7467-4cb4-995a-b6caebfc5aa6" />

----------------------------------------------------

**CHILD GAME MENU:**

<img width="1214" height="809" alt="image" src="https://github.com/user-attachments/assets/11d79890-6e0c-470e-9f05-a4637d323c0c" />

----------------------------------------------------

**ADULT GAME MENU:**

<img width="1473" height="836" alt="image" src="https://github.com/user-attachments/assets/e1d09872-7151-4384-94ed-517d71525685" />


# <ins>**_Project Risks_**</ins>

**Technical Knowledge**

We are both a bit rusty and might lack some coding experience for some of the planned aspects for the game, the learning curve introduced from this can slow overall progress.

**Project Scope**

There are many planned features and implementations for the project, as such it's possible we might not be able to do everything to the best of our abilities, as we may have planned outside of what's capable for us in the time given.

This can lead to game breaking bugs.

**Testing**

If we are pressed for time, testing which usually comes in the final phases of software projects, can be done incomplete or not to the extent it should be done, which can give room for hidden bugs or problems to show during release.

**Integration of many features**

Due to so many features being planned for the game, it will be difficult to be able to make everything work together, as issues such as incompatible libraries can happen.

**Player Experience**

We have to ensure both modes are fully playable and enjoyable for their intended playerbases. If for "Child Mode" images aren't interactive then they will struggle, if the timer is too short or broken on "Adult Mode" then the game will be frustrating and unplayable.

# <ins>**_Software Development Strategy_**</ins>


