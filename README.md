# Mass-cleanup-of-tasks-and-projects-in-CA-Clarity-PPM
The script is written in CA PPM implementation of Apache Jelly-based scripting language called Generic Execution Language (GEL). 
The process of cleaning up tasks and projects consists of two steps. 

The steps can be set up in any order. 
One step is dedicated to closing tasks for time entry based on the parameters that define the minimum age of tasks to be closed. 
Another step is aimed at closing projects for time entry and the step is parametrized in the same age, where you have to set up the minimu age of projects.

Both steps have a parameter that allows users to either run the process updating the tasks and projects directly or just analyse tasks and projects that would need to be processed but without actually closing them for time entry.

The closure of tasks and projects for time entry based on specific criteria is designed to be done in batches in order to avoid performance issues when the process is run in CA Clarity PPM.

The process is object-independent and therefore has to be triggered on demand or scheduled. 
