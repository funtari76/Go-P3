# **_GOO - :---> NeoN-[7]_** 

<hr>

--------------------
![](/assets/media/giphy.gif)

--------------------

An interactive text-based sci-fi adventure game.

It is built using Python and runs through the Code ins
terminal on Heroku.

Welcome to <>The Cave of Query</>
![Responsive design]()

# Contents

- [**User Experience UX**](#user-experience-ux)
[Game Design](#game-design)
  - [Flowchart](#flowchart)
- [**Current Features**](#current-features)
  - [Title Page](#title-page)
  - [Game Introduction](#game-introduction)
  - [Puzzle Rooms](#puzzle-rooms)
  - [End of Game Page](#end-of-game-page)
- [**Future Features**](#future-features)
- [**Technologies Used**](#technologies-used)
- [**Testing**](#testing)
- [**Deployment**](#deployment)
- [**Credits**](#credits)
  - [**Content**](#content)
  - [**Media**](#media)
- [**Acknowledgements**](#acknowledgements)

--------------------------------
# User Experience (UX)

## Game Design

![Cave Map]()

Originally, I set up a Google Spreadsheet in the backg
the explorer and letter data, and to pull the diary da
needed to help solve the puzzles. However, although be
content, my mentor pointed out that this data could al
displayed inside the run.py file, so in the end, I rem
the Google Sheets, and kept the data inside the GitPod

[Back to top](#contents)

----------------------
## Flowchart

```



```

---

<hr>

The Cave of Query flowchart was designed using the fre
website [Diagrams.Net](https://www.diagrams.net/)

---

```


```

-- The user enters the game by inputting their name. T
validated to make sure that at least one alpha charact
then it is stored in a Name variable and the user ente

```



```

The Go neon7 consists of seven puzzle rooms and a trea
user has to work their way through each of the puzzles
treasure. This is the 'escape room' concept but turned
the user is trying to get in, not out.

```



```

Each puzzle room contains a different brain teaser for
solve. if they input the correct answer, they win a le
stored in a variable and they are given the option to 
the next room or give up.

```



```

If they give up, the game ends and resets back to the 
continue on through each puzzle room, they will reach 
chest. In order to open the chest and gain access to t
have to use all the letters they have collected along 
a word.

```



```

At the end of the game, they can choose to play again,

```



```

---

![Cave Flowchart]()

[Back to top](#contents)

# Current Features

## Title Page

---

<h>

Across the main home page screen, when you run the pro
introduced to the game title 'The Cave of Query' and y
enter your name, which starts the game.

![Homepage image](assets/images/title-page.png)

[Back to top](#contents)

---

## Game Introduction

---

Once the user has entered their name, they enter the c
given an introduction to the user story. The player is
the infamous Indiana Jones. In his last will and testa
you an old key and his diary, where he used to write a
treasure-hunting information. In the diary, you find i
the Caves of Query, a quest Indiana never managed to c

In his stead, you decide to travel to the Caves of Que
luck, after all you have the Jones' explorer genes. Yo
diary and the key with you.

I used [Ascii Art](https://emojicombos.com/cave-entran
print an image of a cave in this introduction section.
bog the user down with a whole page of introduction te
into the spirit of the game, but at the same time, I w
something to let them visualise going into the game ar
game like this relys a lot on the user's imagination s
gives them a little prompt.

![Rules Page image](assets/images/game-intro.png)

[Back to top](#contents)

-------------------------
## Puzzle Rooms

Each puzzle room contains a different type of puzzle. 
maths puzzles, to anagrams, to deciphering strange lan
user types in the wrong answer, I have tried to give t
steer them in the right direction towards the correct 
printed in green.

The validation makes the input not case sensitive, so 
correct word in either upper or lower case, it will st
correct.

The validation is printed in red to stand out to the u

![Validation and Hints]()

A lot of the puzzles contain Indiana Jones trivia. Bot
decipher puzzles are Indiana quotes, and also the libr
is one of Indiana's most famous quotes as well.

The letters collected throughout the game spell: 'Pyth
both a play on the language I have been using througho
build the game but also Indiana Jones' greatest fear; 

After each puzzle is correctly answered, the user is a
They are then shown all the letters that they have won
to this point, and these are printed in yellow.

At the end of each puzzle they are give the option to 
up. If they continue, the next puzzle room is displaye
game is over and the user is taken back to the Home Pa

![Continue or Quit Page]()

[Back to top](#contents)

## End of Game Page

---

<hr>

Once eight puzzles have been completed, and all the co
re-arranged and typed correctly into the treasure ches
treasure chest key hole is revealed.

I used [Ascii Art](https://emojicombos.com/key) to pri
key and the user wins the game and is rewarded with th
Amongst the treasure, they also find another treasure 
the option to continue their new found treasure huntin
while they are ahead. If they choose to quit, the game
choose to continue the treasure hunt, the user is take
Page to begin the game again. With future developement
would take them to a new adventure with alternative br
complete, using the newly acquired treasure map.

![End of Game Page]()

[Back to top](#contents)

## Future Features

---

<h>

In the future, I would like to add more features to th
game. These could include:

- Difficulty levels
- More puzzle rooms
- The option to choose various doors after each puzzle
[Game Design](#game-design)
- Additional levels, to make use of the treasure map f
the Game, as described previously.

One day, when I'm an expert Full Stack Software Develo
to be able to add graphics, music, characters, etc. to
make it more than just text-based if my abilities in t
allow me.

[Back to top](#contents)

-------------------------
# Technologies Used

I used the following technologies to create this websi

- Python – Content and structure
- Gitpod – Website deployment
- Github – Website code repository
- Heroku - Hosting platform for the game
- Diagrams.net - Create the game layout and flowchart

[Back to top](#contents)

# Testing

Please click [**_here_**](TESTING.md) to read more inf
testing The Cave of Query

[Back to top](#contents)

# Deployment

### **To deploy the project**

The game was deployed via an online platform called as
improve user experience when viewing a program written
Python. The deployment process is as follows:

1. Create new Heroku app from Heroku dashboard
2. Choose an app name that is available.
3. Choose the region where you are working from (Europ
4. Select the create app button
5. Select 'Settings' from the main menu
6. Scroll to 'Config Vars' section and select 'Reveal 
7. In the 'Key' field input 'PORT' in the 'Value' fiel
8. Press 'Add' to add the value just entered
9. Repeat this process to create a key called 'CREDS' 
values in from the CREDS.Json file in Gitpod to hide s
the user.
10. Scroll down to 'Add buildpack' and select it
11. Select 'Python' and save changes
12. Select 'Add buildpack' again and do the same with 
13. Link the App to your matching GitHub repository
14. Select Automatic deploy

![Deploy image](assets/images/deploy-githubconnect.png
![Deploy image](assets/images/deployment.png)

The live link to the Github repository can be found he
cave-of-query.herokuapp.com/

### **To fork the repository using GitHub**

[Back to top](#contents)

# Credits

### Content

- I researched how to begin creating a text-based adve
[www.makeuseof.com](https://www.makeuseof.com/
python-text-adventure-game-create/)
- I got brain teaser puzzle ideas from [teambuilding.c
teambuilding.com/blog/escape-room-puzzles)
- I found the Morse Code dictionary at [morsedecoder.c
morsedecoder.com/)
- I researched Indiana Jones trivia at [thoughtcatalog
thoughtcatalog.com/oliver-miller/2013/03/
50-quotes-from-the-indiana-jones-movies-in-order-of-aw
- I researched classic books at [oclc.org](https://www
worldcat/library100/top500.html)
- I learnt how to print lists into multiple columns an
user input through the [Bobby Hadz Blog](https://bobby
python-print-list-in-columns)
- I learnt how to print lists in a user friendly forma
[pythonpool.com](https://www.pythonpool.com/
remove-brackets-from-list-python/)
- I learnt how to compare two lists to validate multip
using this article from [Stack Overflow](https://stack
questions/8866652/
determine-if-2-lists-have-the-same-elements-regardless

### Media

- The ascii art images used in this game were sourced 
com](https://emojicombos.com/)

[Back to top](#contents)

# Acknowledgements

[Back to top](#contents)
