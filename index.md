 # Dynamic programming and Optimal Control  

## Course Information
Schedule: Fall 2023, Thursdays 9:00am - 12:15pm
Location: 430 Kravis Hall

Professor: Daniel Russo
Office hours: 12:15-1:00 PM or by appointment 

TA: David Cheikhi

Course Number: B9120-001

## Course description:

This course serves as an advanced introduction to dynamic programming and optimal control. The first part of the course will cover  problem formulation and problem specific solution ideas arising in canonical control problems. The second part of the course covers algorithms, treating foundations of approximate dynamic programming and reinforcement learning alongside exact dynamic programming algorithms. 

## Prerequisites
Markov chains; Some python and some linear programming; mathematical maturity (this is a doctoral course); 

## Textbooks
Dynamic Programming and Optimal Control by Dimitris Bertsekas, 4th Edition, Volumes I and II. 



# Class notes (and *tentative* schedule) 

| # | Date  | Topic  | Notes| Reading| Extras| 
|-|-|-|-|-|-|
| | | **Part I: Problem formulation and special problem structure** |  |  |
| 1 | 9/7 | Intro  | [pdf](Notes/1A-Intro.pdf)   |  Vol 1, Sec 1.2-1.4
| 2 | 9/7 | Optimal stopping  | [pdf](Notes/1B-Optimal-Stopping.pdf)  | Vol 1, Sec 3.4  | | 
| 3 | 9/14 | Inventory control  | [pdf](Notes/2A-Inventory-Control.pdf)  | Vol 1, Sec 3.2  |  
| 4 | 9/14 | Linear quadratic control  | [pdf](Notes/2B-Linear-Quadratic-Control.pdf) | Vol 1, Sec 3.1  |  
| 5 | 9/21| Imperfect state information; reformulation as a problem with perfect state information; separation principle  | [pdf](Notes/3-Partial-Observability.pdf) |  Vol 1, Sec 4.1-4.3
|6 | 9/28| Discounted infinite horizon objectives. |  [pdf](Notes/4-discounting.pdf) | Vol 2 Sec 1.4
|7 | 10/5| Continuous time, discrete event problems; uniformization| |Vol 2 Sec 1.5 | [pdf](Notes/5A-Continuous-Time-Discrete-Event.pdf)
|8|  10/5| Gittins index theorem; Applications to scheduling and optimal learning; | [pdf1](Notes/5B-Gittins.pdf), [pdf2](Notes/5B-priority-policies.pdf), [pdf3](Notes/5B-Tsitsiklis-short-proof.pdf)| 
|9|  10/12| Gittins index theorem continued|   | 
| | 10/19| No B-school classes scheduled|  | | 
| | | **Part 2: Algorithms and approximations** |  |  |
|10| 10/26| Infinite (or indefinite) horizon problems without discounting: average cost objectives & stochastic shortest path problems. | [pdf](Notes/7A-IndefiniteHorizon.pdf)
|11| 11/2 |   Online value iteration 
|11| 11/2| State occupancy measures and performance differences. |
|12| 11/9 |  
|13| 11/16 |  
| | 11/23|  No B-school classes scheduled |  | 
|14| 11/30 | 
|15| Dec 7| 

Topics for part 2 are yet to be determined. Some possibilities include:

- Temporal difference learning and parametric value function approximation. 
- Policy gradient methods and their global convergence; differentiable simulators; 
- Efficient exploration; optimism in the face of uncertainty
-  Problems with many "weakly coupled" components;  Lagrangian relaxations


## Evaluation
Homework (90%). Lecture scribing and class participation (10%). 

## Homework 
We will have a short homework each week. Please write down a precise, rigorous, formulation of all word problems. For example, specify the state space, the cost functions at each state, etc. 

1. Due September 14. Vol 1. Problems 1.23, 1.24, 3.18. [Scan](HW/hw1_scan.pdf)
2. Due September 21. [pdf](HW/hw2.pdf)
3. Due September 29. see canvas annoucement
4. Due October 5. [pdf](HW/hw4.pdf)
5. Due October 12. [pdf](HW/hw5.pdf)
6. Due October 26. Vol 2. Problem 1.8. You may assume that the state space of each bandit process is finite. 
7/ Due November 2. [pdf](HW/hw7.pdf)



