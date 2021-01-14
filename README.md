# CS50-0
### Harvard CS50 - Lecture 0 - Scratch
https://cs50.harvard.edu/x/2021/weeks/0/

It has been a year since I first started this journey on taking Harvards' Computer Science 50 course. Things happened in my life and I wasn't able to continue. However, since I have a winter break from my school now is the perfect time to start back again. :rocket:

Going forward, I still plan to log my progress so I can have a reference on what I did and how long I took to complete certain sections and problem sets. I already know this journey is not a piece of cake. However, I am determined to complete it because it's important for my personal and professional growth. This time around, **Github** will be my main source of recording my progress. Here inside the *README.md* file will be where I will keep a journal and lecture notes on every section I come across. 

--- 

In **Lecture 0**, David Millan gives us a brief description on what the class entails and what *Computer Science* is about. 

He opens the class prompting us to think about what **Computer Science?** is? 
  - Simply put, *Computer Science* is fundamentally problem solving.
  - There's an `input —> instructions (algorithm) —> output`

It's important to understand the concept of **Binary** and how it relates to powering electronics. We are usually taught to count in a *unary* way where a digit is a single value. But, instead of using a *base 10* system, it's easier for computers to use *binary, base two, 0 and 1s*. Each binary digit is called a **bit**. With this in mind, we use binary to controll and operate a off & on light switch where 0 is off and 1 is on.

**ASCII** or **American Standard Code for Information Interchagne** is the standard mapping of letters, symbols, characters, and colors which we are constantly using everyday to operate electronics. It helps us use keyboards to write out commands and emails, or to simply send out a text message to our friends so they can watch the latest news trends. Although it might seem straight forward, we need a way to acces more characters in order to create more bits/characters. With that in mind, **byte* or **eight bits** is now the standard way of accessing *256* different values!

Images and videos are too value of 0s and 1s. To represent color we use a term called **RGB** that stands for **Red, Green, and Blue**. Each of the three *byte* represents a color from 0 to 256 (*8-bits / 00000000*). Depeneding on the color you're trying achieve making sure the values are properly represented by that color.

**Algorithms** - are a set of *instructions* that solve problems. 

Writing out algorithms in plain English is called **Pseudocode**. This technique helps the human interpret the code/steps more easier because you are not using certain language syntax which can be confusing. 

When writing *pseudocode* we use **verbs** to express what **actions** we want done. Some examples are: *pick up*, *open to*, *look at*, *call*, *open to*, and *quit* are all actions.
``` 
1  Pick up phone book
2  Open to middle of phone book
3  Look at page
4  If person is on page
5      Call person
6  Else if person is earlier in book
7      Open to middle of left half of book
8      Go back to line 3
9  Else if person is later in book
10     Open to middle of right half of book
11     Go back to line 3
12 Else
13     Quit
```
There are also a lot of times that **conditions** are used when determining decision making. Using `If` , `Else if`, and `Else` statements helps knock-out different paths in order to achieve the correct statement.

Along with *conditions* and *verbs* there are **Boolean** expressions that usually result in a `true` or `false` (1 or 0 / yes or no) value. From the example above, `person is on page`, `person is earlier in book`, and `person is later in book` are all examples of a true or false statement. 

**Loops** is last thing that was covered in this lecture. They can create a repeating cycles where you are able to repeat sections of your program.

---
# Problem Set 0
### Scratch
Instruction: https://cs50.harvard.edu/x/2021/psets/0/scratch/

###### Pseudocode —
  0. Find maze, sumo sprite, cake, and sound effects
  1. Place sprites in correct location of the game/maze 
  2. Add a game message on sumo-sprite
  3. Once sumo-sprite is clicked, place sprite on the starting point of maze and play a game music.
  4. Make sumo-sprite small to fit the maze.
  5. Use arrow keys to move sprite through the maze. 
  6. If sprite comes in contact with the walls, display message, play a sound, and replace sprite to the starting position of the game.
  7. When the sprite reaches the cake, clear the board.
  8. Display a new image of sumo eating the cake with a new winning message.
  9. Play an eating tone.
  10. Once the user clicks on the ‘green flag,’ it restarts the game.

The finished product:
https://scratch.mit.edu/projects/357371336
