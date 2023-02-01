# Runn Pair Programming Exercise

You will be asked to create a basic app / feature that is similar to some of the problems we solve every day working at Runn. You will be driving, when an engineer from Runn helping you when you get stuck, giving you advice, and ensuring you don't go off track. While you are primary problem solver, we are here to help so please ask for it.

This is also open-book and real world, please do google, look up docs, and talk to our follow engineer to talk through problems are get advice. You can use any additional libraires you like (but dont get bogged down on this). There is no 'solution' to this -- like in the real world, it just needs to meet specifications.

We provide the same pair programming exercise for juniors to seniors to our VP -- so don't worry about finishing it all, no one has yet. We are just here to ensure you can write good code, work well with others, and solve problems.

## The Exercise
We need to understand how many hours are being working each day, taking from a series of assignments across multiple projects and people. 
The goal is to be able to enter assignment data, view the amount of work through a variety of lens such as total hours worked in a day, hours for each person, hours for each project.

You'll be building everything - The UI, the form, the calculations and any visuals. 

You don't need to make it fancy and you don't need to dive too deep into edge cases or performance optomisations.
Feel free to mention what you might do, or the interviewer might through in an edge case, or ask for an optomisation when they want to explore some of your knowledge deeper.

Generally its easiest to follow the specs in order -- but it's up to you.

## Specifications

1. Create an input form that accepts: Description, Hours Per Day, Start Date, End Date
2. Create a table of all assignments with the data as above
3. Create some test data, in the same format as the form. Ensure the test data is updated every time a new input is submitted.
4. Create table/list/etc that shows the total numbers of hours worked each day, for any day an assignment falls on.
5. Add unit tests for the calculations
6. Display on a graph the total amount of hours being worked each day
7. Add a "Project" field, and show the total hours worked on a project
8. Add a "Person" field, and then split the daily hours worked calculations out by person
