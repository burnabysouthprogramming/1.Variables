#Variables

[Python Compiler - Click here] (http://www.tutorialspoint.com/execute_python_online.php)

Variables are essential to any computer program. Variables hold different values that can easily be changed later in the program. In a variable, you _store_ values like how a cardboard box can store shoes. Likewise, one can label their shoe boxes for different types of shoes similarily to how someone can name variables for various purposes.

##Styles
A good variable name is short, to the point, and is descriptive enough to describe its purpose. There are styles of naming variables, especially when they get very long. It is __recommended to stick with one style__ while you code in order to keep the program neat.
Different programmers prefer different styles such as:

__The Underscore__
```py
move_block_distance = 20
character_health = 100
```
With the Underscore style, all words in the variable are lower-case, separated by an underscore.

__The Lower-Upper Case__
```py
moveBlockDistance = 20
characterHealth = 200
```
With the Lower-Upper Case style there are no underscores, however the first word is lower-case and the ones afterwards are capitalized.

The examples above are clearly defined; one can see how the variable ```move_block_distance``` is 20 which means the block movement is 20. The units (ft, meters) are not defined, but since we are working with variables, the value of ```move_block_distance``` can be changed within a program.

####Here are some examples of bad variables and bad styles:

__The Caps Abuser__
```py
ENEMYHEALTH = 36
BULLETDAMAGE = 4
FRIENDLYFIREDAMAGE = 2
```
While all caps variables are used in programs in certain cases, it is not preferable to fill up an entire document with capital words. There are also no distinct separations in words, thus making it more difficult to read.

__Mr. LongJohns__
```py
enemy_monster_tree_scare_green_health_after_two_days_at_night = 2
varTakenFromTurningBecauseItsWithThisScriptFromTheBeginning = 10
```
Variables are supposed to be descriptive, _yes_, however let a variable be a short description and one that does not take a tremendously long time to read.

__The Face Smasher / The Lazy Potato__
```py
b = 10 000
qdyu = 15
ruby = 10
Ruby = 2
wper = 12
uper = 534
mper = 20
```
The main problem for this style is that nobody, not even yourself, will be able to understand the variables created. When someone adds ```uper``` to ```qdyu``` and receive the number of ```549```, it will be more difficult to understand what the outcome means. Although a program can have hundreds of variables and can be tedious at times, it is always a good habit to created informative and readable variables.
