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
There is a easy way to import things. Just putting "run('file.rahanji')" will run the specified file. This will load all functions in that file
!The String passed as a parameter is viewed as a file name, so if the other file is in another directory specify it like that!

the entry point: 
An entry point of a rahanji application can be every file.
The interpreter just goes through all the instructions of the specified file from top to bottom.

print to the standart output:
print prints its argument to the stdOut: print('hello world')
println prints its argument to the stdOut adding a line break: println('Hello world')

functions:
functions are declared by the keyword siu and then adding parenthesis
There are two types of functions
expression functions:
siu add(a, b) > a + b
returns a + b
statement functions:
siu addAndPrint(a, b):
  println(a + b)
  return a + b
atombome
You can see that you end a block with the keyword atombome
