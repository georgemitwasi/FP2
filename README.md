## My Library: (library name here)
My name: George Mitwasi

In this exploration, I experimented with the library that I'm using for my final project. It's a music composition library that generates music using high-level algorithmic procedures. Under the hood, it uses multiple programming languages (including Scheme of course) and because it's a third party project, doesn't have a direct connection to DrRacket like libraries on the Racket website. So instead of including a simple #lang for access, I had to download the library from http://commonmusic.sourceforge.net/ and use IDE that they provided.

The library is extremely complicated and in this exploration I only tap into it's full potential. The IDE was easy to follow. It includes an Editor Window (which you can have multiple of) and a Console Window that displays your output. My insticts told me to start with the "Help" tab, which luckily has Scheme examples and tutorials. This tab was where I spent my time in this exploration.

INSERT "Help me.jpg" HERE
![Slide1](https://raw.githubusercontent.com/georgemitwasi/FP1/master/Slide1.jpg)

I started with the tutorial section to see how much Scheme I actually knew and how much catching up I had to do. I knew more than 2/3rds of the concepts. The first concept I learned was that of Loops. Loops are a convenient way of executing more a statement multiple times. You can include a 'do' tag which lets you execute more than one action statement at the same time. The 'finally' clause let's you execute a statement once at the end of the loop. Below is all the output of concepts I just described shown in Console Window. 

INSERT "Loops.jpg" HERE
![Slide1](https://raw.githubusercontent.com/georgemitwasi/FP1/master/Slide1.jpg)

The next tutorial on the list of things to be learned was Process. A 'process' is an iterative function that, upon runtime, generates a timeline of events. Note the following process:
```
(define (simple)
  (process repeat 20
           do
           (mp:midi :key (between 60 96))
           (wait 0.1)
           ))
```
A process receive a number of argument values. The 'mp:midi :key' is telling the process to play notes between 60 and 96. The 'wait' identifier tells the process how much time to wait before the next iteration. 

Now 'sprout' function is how you can hear a process play its audio (procedural content) in real time. You can play hear this process in real-time quite easily with the sprout function:
```
(sprout (simple))
```
You can sprout multiple processes by feeding sprout a list processes.

So, how will I use this might you ask? Well this function is the meat and potatoes of how you create midi output. Unfortunately, I havent't figured out how to make FL Studios (my choice Digital Audio Workstation) recieve MIDI data and create music. Though it was fairly easy to output MIDI to the Console Window.

It didn't take long to realize that I have lots of work to do until I can compose my own music with this software.
