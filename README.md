# Single Machine Scheduling with PuLP

In this study, the aim is to model single-machine scheduling problem with two different approaches and write the necessary code to solve the same problem with two different formulations.

- The first approach suggests writing necessary constraints for every starting time-job possibility to compare them in two pairs and ban any conflict.
- The second approach is based on the necessity that at every time point, there can be at most one job in process.

The below code is written to solve for 5 jobs, each having processing time and due date parameters. The code can be used for any number of jobs with custom parameters by modifying the related variables.
