# Proposal

## What will (likely) be the title of your project?

Scheduling optimizer cleanser

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")

A code that can first open data, then take the important and usable components to be easily interpreted for a nontechnical sponsor. Using this data key metrics will be recorded (i.e. different players averages, mins, maxes).

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?

The code will take in a fairly large(4,000 row) sheet of data and trim the unnecessary information. Then it will compile the important data in a neat and easily interpreted fasion. From there, the usable data will have many metrics tracked such as averagesfor different players, mins and maxes for both players and games. This would be greatly valuable for the sponsor's staff to interpret results quickly, as well as for my team and the Phillies analytical staff to have important information analyzed quickly. The data comes in the form of an Excel linear optimization model in which pitchers are scheduled for 162 games of the Phillies' regular season. Players receive a binary decision variable if they are scheduled to pitch with a 1 denoting a selection and a 0 denoting not being selected. The data with zeros must be cleaned and the ancillary data for the chosen pitchers must be analysed.

## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

This would be an ancillary component to my senior design project. All the data will be generated from the senior design prototype, but the interpretation of the data will be made easier using the python code.

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

n/a

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

Data is cleaned of all the unnecessary information and compiled into a neat and quickly understood spreadsheet or text file. This will enable Phillies coaching staff to interpret the information quickly as they do not have the time to learn the technical features of the model.

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

The next most important component of the project is tracking a few metrics to have a summarized understanding of the data, the workload of each pitcher and what is required of the pitching staff as a whole. This will likely come in the form of dictionaries and named variables containing player player information. There are many components to the model so a cohesive summary of all the constraints, decisions, etc. would be a thorough endeavor. This should certainly be within reach of doing well.

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

The best case schenario would involve graphical displays to further drive home the ease of interpretation and analysis. This is something that would be incredibly tedious to do in excel for different trial runs, so achieving this would be an incredible asset to my team. This would be the most out of reach component as it has been touched on in class the least, but definitely attainable with outside learning. 

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

While the immediate steps are within my understanding, the best case scenario of the project would include the creation of graphical displays, which I would have to learn using online resources. All data formulation would be done in a neigboring sheet to the model, which is something I am not experienced with doing. Each game represents 24 rows of data, so it will likely require two for loops to iterate throw each game, then another for the game's data taking all necessary data compiling it as it iterates.
