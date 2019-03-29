# Dobbelsteen

This is just an automated die-rolling system written in Scyndi. If you want to see the compiled version in action [click here](http://tricky1975.github.io/Dobbelsteen/).
I guess you don't need much imagination that "dobbelsteen" is the Dutch word for "die" (the noun, NOT the verb). 


# Compile

Assuming you have the latest version of Scorpion, properly compiled and configured the compile command would be
~~~sh
scorpion -target WebJS Dobbelsteen
~~~

Scorpion will then translate the code to JavaScript and create a directory called "Dobbelsteen.sout" (s-output), and you'll see index.html and Dobbelsteen.js

Just load index.html into any browser and the app should work ;)
