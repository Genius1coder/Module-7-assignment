# Module-7-assignment
This repository contains solutions to the assessment for module 7 topic.

QUESTION 1

 The event loop is a mechanism that enables the server to handle multiple client requests

  without blocking the execution of the program. It is a fundamental concept in Node.js

   that allows it to handle a large number of requests concurrently. The event loop

    works by processing a queue of events, where each event represents a client request

     or some other type of event. When a request comes in, it is added to the event queue.

      The event loop then processes each event in turn, executing any associated

       callbacks or handlers as necessary.

 QUESTION 2
 In Node.js, the event loop is composed of 6 different phases, each of which corresponds

  to a specific task or type of event. Here is an overview of each of the phases:

1   Timers: In this phase, the event loop will check if any timers have expired,

 and if so, it will execute    their callback functions.

2   I/O callbacks: This phase handles I/O events such as incoming data or completed

 database queries. When an I/O event occurs, its callback function is added to the

  event queue to be executed in the next tick of the event loop.

3   Idle, prepare: These are internal phases that are used to prepare the system for

 the next tick of the event loop.

4   Poll: In this phase, the event loop will wait for incoming I/O events, such as a

 new incoming connection request. If there are no events to process, it will wait

  until a new event is added to the event queue.

5   Check: This phase executes callbacks registered with setImmediate().

6   Close callbacks: This phase executes close event callbacks, such as 

when a server is closed.


 The phases are not strictly fixed and can vary depending on the specific event loop implementation and the 

 nature of the application being run. Additionally, each phase can be customized or extended through the use 

 of additional libraries or custom event handlers. 

 QUESTION 3

 Here are some best practices server side code developments: 

1.	Keep code modular and maintainable

2.	Follow coding standards

3.	Use version control

4.	Write unit tests

5.	Optimize for performance

6.	Secure your code

7.	Document your code

8.	Monitor your code

9.	Use libraries and frameworks

10.	Continuously improvement.

QUESTION 4

PM5 is a version of the Node Package Manager, a tool for managing Node.js packages and dependencies. 

It allows developers to easily install, update, and remove packages in their Node.js projects. 

To initialize a package in NPM, the following steps have to be taken:

1.	Open the terminal or command prompt and navigate to the directory where the package will be initialized.

2.	Type the command npm init. This will start the package initialization process.

3.	You will be prompted to provide information about your package, such as the package name, version, 
description, and author.

4.	Follow the prompts to complete the initialization process.

5.	Once the initialization process is completed, a package.json file will be created in the current 

directory. This file contains metadata about the package and its dependencies.

QUESTION 5

To run a script defined in the package.json file, I will use the npm run command followed by the name of the 

script. 

QUESTION 6






