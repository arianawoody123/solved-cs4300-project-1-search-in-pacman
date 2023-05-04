Download Link: https://assignmentchef.com/product/solved-cs4300-project-1-search-in-pacman
<br>
In this project, your Pacman agent will find paths through his maze world, both to reach a particular location and to collect food efficiently. You will build general search algorithms and apply them to Pacman scenarios. As in Project 0, this project includes an autograder for you to grade your answers on your machine. This can be run with the command:

<strong>python autograder.py</strong>

The code for this project consists of several Python files, some of which you will need to read and understand in order to complete the assignment, and some of which you can ignore. Download search.zip from here <a href="http://ai.berkeley.edu/search.html">http://ai.berkeley.edu/search.html</a> which will contain all the code and supporting files.

<h1>1           Files to edit</h1>

For all the problems in this project, you would have to edit just two python files namely:

<ol>

 <li><strong>py: </strong>where all of your search algorithms will reside.</li>

 <li><strong>py: </strong>where all of your search-based agents will reside.</li>

</ol>

<h1>2           Supporting files</h1>

The following python files would help you in understanding the problem and the get you familiar with the different data structures and games states in Pacman.

<ol>

 <li>py: The main file that runs Pacman games. This file describes a Pacman GameStatetype, which you use in this project.</li>

 <li>py: The logic behind how the Pacman world works. This file describes several supporting types like AgentState, Agent, Direction, and Grid.</li>

 <li>py: Useful data structures for implementing search algorithms.</li>

</ol>

<h1>3           Search in Pacman</h1>

For all the problem titles described below, please refer to the link <a href="http://ai.berkeley.edu/search.html">http://ai.berkeley.edu/ </a><a href="http://ai.berkeley.edu/search.html">search.html</a> for the problem description and what is expected of each problem. As always autograder has different test cases against which you can run your program to check the correctness. For the questions asked below, please ensure your response is brief and to the point. Please don’t write paragraphs of text as responses to these questions.

<h2>3.1         Depth First Search</h2>

<ol>

 <li>(10pts) Code Implementation</li>

 <li>(1pt) Is the exploration order what you would have expected? Does Pacman actually go to all the explored squares on his way to the goal?</li>

 <li>(1pt) Is this a least cost solution? If not, think about what depth-first search is doing wrong.</li>

</ol>

<h2>3.2         Breadth First Search</h2>

<ol>

 <li>(10 pts) Code Implementation</li>

 <li>(1 pt) Does BFS find a least cost solution? If so explain why ?</li>

</ol>

<h2>3.3         Uniform Cost Search</h2>

<ol>

 <li>(10pts) Code Implementation</li>

 <li>(1 pt) Specify the data structure used from the util.py for the uniform cost search</li>

</ol>

<h2>3.4         A* search</h2>

<ol>

 <li>(10pts) Code Implementation</li>

 <li>(2 pts) What happens on openMaze for the various search strategies? Describe your answer in terms of the solution you get for A* and Uniform cost search.</li>

</ol>

<h2>3.5         Finding All the Corners</h2>

<ol>

 <li>(10pts) Code Implementation</li>

 <li>(2 pts) Describe in few words/ lines the state representation you chose or how you solved the problem of finding all corners?</li>

</ol>

<h2>3.6         Corners Problem: Heuristic</h2>

<ol>

 <li>(10pts) Code Implementation</li>

 <li>(1 pt) Describe the heuristic you had used for the implementation.</li>

</ol>

<h2>3.7         Eating All Dots</h2>

<ol>

 <li>(13pts) Code Implementation</li>

 <li>(2 pt) Describe the heuristic you had used for the FoodSearchProblem.</li>

</ol>

<h2>3.8         Suboptimal Search</h2>

<ol>

 <li>(10pts) Code Implementation</li>

 <li>(1 pt) Explain why the ClosestDotSearchAgent won’t always find the shortest possible path through the maze.</li>

</ol>

<h1>4           Self Analysis</h1>

<ol>

 <li>What was the hardest part of the assignment for you?</li>

 <li>What was the easiest part of the assignment for you?</li>

 <li>What problem(s) helped further your understanding of the course material?</li>

 <li>Did you feel any problems were tedious and not helpful to your understanding of thematerial?</li>

 <li>What other feedback do you have about this homework?</li>

</ol>

<h1>5           Evaluation</h1>

Your code will be auto-graded for technical correctness. Please do not change the names of any provided functions or classes within the code, or you will wreak havoc on the autograder. If your code passes all the test cases in the autograder you would receive full points for the implementation.

However even if your code does not necessarily pass all the test cases, we would evaluate your code and then award you partial points accordingly. In such cases it would be even more beneficial if you could give a short description of what you tried and where you had failed and that would help us in giving you better points.