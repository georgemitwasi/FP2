## My Library: (library name here)
My name: George Mitwasi

In this exploration, I started experimenting with the library that I'm using for my final project. It's a music composition library that uses high-level algorithmic representations of musical concepts to make music. Under the hood, it uses multiple programming languages (including Scheme of course) and because it's a third party project, doesn't have a direct connection to Racket like libraries on the Racket website. So instead of including a simple #lang for access, I had to download the library from http://commonmusic.sourceforge.net/ and use IDE they provided.

The library is extremely complicated and this exploration only taps into it's potential. The IDE was easy to follow. It includes an Editor Window (which you can have multiple of) and a Console Window that displays your output. My insticts told me to start with the "Help" tab, which luckily has Scheme examples and tutorials. This tab was where I spent my time in this exploration.

INSERT "Help me.jpg" HERE

I started with the tutorial section to see how much Scheme I actually knew and how much catching up I had to do. I knew more than 2/3rds of the concepts. The first concept I learned was that of loops. Loops are a convenient way of executing more a statement multiple times. You can include a 'do' tag which lets you execute more than one action statement at the same time. The 'finally' clause let's you execute a statement once at the end of the loop. Below is all the output of concepts I just described shown in Console Window. 

INSERT "Loops.jpg" HERE

The next tutorial I tried was a process.


* a narrative of what you did
* highlights of code that you wrote, with explanation
* output from your code demonstrating what it produced
* at least one diagram or figure showing your work

The narrative itself should be no longer than 350 words. Yes, you need at least one image (output, diagrams). Images must be embedded into this md file. We should not have to click a link to see it. This is github, handling files is awesome and easy!

Code should be delivered in two ways:

1. Full files should be added to your version of this repository.
1. Key excerpts of your code should be copied into this .md file, formatted to look like code, and explained.

Ask questions publicly in the email group.

## How to Prepare and Submit this assignment

1. To start, [**fork** this repository][forking]. 
  2. (This assignment is just one README.md file, so you can edit it right in github)
1. Modify the README.md file and [**commit**][ref-commit] changes to complete your report.
1. Add your racket file to the repository. 
1. Ensure your changes (report in md file, and added rkt file) are committed to your forked repository.
1. [Create a **pull request**][pull-request] on the original repository to turn in the assignment.

## Project Schedule
This is the first part of a larger project. The final project schedule is [here][schedule]

<!-- Links -->
[schedule]: https://github.com/oplS16projects/FP-Schedule
[markdown]: https://help.github.com/articles/markdown-basics/
[forking]: https://guides.github.com/activities/forking/
[ref-clone]: http://gitref.org/creating/#clone
[ref-commit]: http://gitref.org/basic/#commit
[ref-push]: http://gitref.org/remotes/#push
[pull-request]: https://help.github.com/articles/creating-a-pull-request
