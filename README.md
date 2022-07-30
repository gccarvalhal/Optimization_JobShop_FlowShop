# Optimization: JobShop X FlowShop

**PROJECT DESCRIPTION:** : The practical assignment consists of choosing an optimization problem, designing and testing both a mathematical programming (MIP) model and a constraint programming (CP) model for the problem, and reporting on the findings of the analysis of each model and comparison of the two models. It is divided into two stages: design, implementation and test of the MIP model; and design, implementation and test of the CP model, as well as comparison between the MIP and CP models.


**CASE GOAL:** Find the local optimal solution for the problem of scheduling tasks with two diferrent strategies:
- **FLOW SHOP SEQUENCING** with 20 jobs and 5 machines 
- **JOB SHOP SCHEDULING** with 15 jobs and 15 machines 

Both strategies were implemented with CP model (or constrained programming) and MIP models (mixed integer linear programming). The goal is to analyse which of them found the best optimal local soluiton to the problem and verify the correctness and efficiency.

1)	**Database Files:** all the data are in the data.xlsx and jobs.csv
2)	**Download Script:** Job Shop and Flow Shop Scripts

_(make sure you have downloaded Python or Anaconda on your computer to run the script)_

3)  **Outputs:** _(read **Report.pdf** for further information)_

### Result of the algorithms with CP and MIP strategies:
![outputs](https://user-images.githubusercontent.com/95027395/181941750-06819247-a6a4-4702-b43d-4116dbb4137d.PNG)

### Constraint Programing Plots:

#### Job shop scheduling Gantt chart
![Job Shop Scheduling CP Solution](https://user-images.githubusercontent.com/95027395/181941015-71919cbc-24d4-4ab7-a13a-05794937708c.png)

#### Flow shop scheduling Gantt chart
![Flowshop](https://user-images.githubusercontent.com/95027395/181940983-5219b0e9-2e22-4242-be32-7c6bd2e03200.png)
