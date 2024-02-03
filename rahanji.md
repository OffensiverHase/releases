GET STARTET WITH RAHANJI

Rahanji is a 'modern' and not really mature functional and dynamic typed  programming language. Its designed, because I wanted to create my own programming language.
Rahanji has a hard syntax due to mayby cryptic keywords, making the programmer use his brain.
Its semantic is quite easy because its just executed from top to bottom. 
Two advantages are the low learning curve (because it doesn't really have that many features) and the portability.
It runs on every OS having a high enough java version installed.

INSTALLING RAHANJI

Just download the jar and put it in your path. 
I also made a .deb installer, but I cant upload it to github because its to big.
Not important anyway, because for some reason nobody uses linux anyway.

BASICS

imports:
There is a easy way to import things. Just putting "run('file.rahanji')" will run the specified file. This will load all functions in that file.
!The String passed as a parameter is viewed as a file name, so if the other file is in another directory specify it like that!.

the entry point: 
An entry point of a rahanji application can be every file.
The interpreter just goes through all the instructions of the specified file from top to bottom.

print to the standart output:
print prints its argument to the stdOut: print('hello world').
println prints its argument to the stdOut adding a line break: println('Hello world').

functions:
functions are declared by the keyword siu and then adding parenthesis.
There are two types of functions.
expression functions:
siu add(a, b) > a + b
returns a + b
statement functions:
siu addAndPrint(a, b):
  println(a + b)
  nasim a + b
atombome
you can see that you end a block with the keyword atombome.
you can return a value using the nasimm keyword.
functions that dont return anything will return the builting value "null".
siu sayhello() > println('hello') 
returns null.

variables:
variables can be created with the curry keyword.
curry name < "rahanji"
variables have to be initialised instantly, but you can always just give them the null value.
curry foo < null
curry foo < 20

comments:
Just like most modern languages kotlin supports komments.
#This is a comment.
Comments go until the end of a line

if expressions:
siu max(a,b):
  kim a > b jon a un b
atombome
Again there are the two types of if statements that work just like the functions types.
If statements can also be used as expressions.
curry foo < kim 1 = 1 jon 'math works'
In such a case they dont have to be exhaustive, if 1 wouldn't be equal in this case the if statement would return null

for loop:
curry items < ['apple', 'banana', 'kiwi']
messi i < 0 steph len(items) jon:
  println(items ~ i)
atombome
For loops also have the two types like every other loop.

while loop:
curry items < ['apple', 'banana', 'kiwi']
curry index < 0
ronaldo index { len(items) jon:
  println('item: ' + items ~ index)
  curry index < index + 1
atombome

lists:
Rahanji support python like lists.
curry list < [[], 1.3, 'hello', 1]
