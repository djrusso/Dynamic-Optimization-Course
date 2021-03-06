# Dynamic programming and Optimal Control  

## Course Information
Schedule: Winter 2020, Mondays 2:30pm - 5:45pm

Location: Warren Hall, room #416 

Professor: Daniel Russo

TAs: Jalaj Bhandari and Chao Qin 

Course Number: B9120-001


## Course description:

This course serves as an advanced introduction to dynamic programming and optimal control. The first part of the course will cover  problem formulation and problem specific solution ideas arising in canonical control problems. The second part of the course covers algorithms, treating foundations of approximate dynamic programming and reinforcement learning alongside exact dynamic programming algorithms. 

## Tentative syllabus
* Problem formulations
  * Finite horizon
  * Partially observable problems and the belief state 
  * Infinite horizon discounted
  * Continuous-time discrete-state problems
  * Brief overview of average cost and indefinite horizon problems. 
* Problem specific ideas and examples
  * Myopic policies in optimal stopping 
  * Base-stock and (s,S) policies in inventory control
  * Linear policies in linear quadratic control
  * Separation principle and Kalman filtering in LQ control with partial observability 
  * Interchange arguments and optimality of index policies in multi-armed bandits and control of queues. 
* Exact algorithms for problems with tractable state-spaces
  * Value Iterations
  * Policy Iteration
  * Linear Programming
* Foundations of reinforcement learning and approximate dynamic programming. 
  * Asynchronous value iteration 
  * Optimistic exploration 
  * Convergence of policy gradient methods 
  * Convergence of TD-learning 
  * Policy chattering in Q-learning 
  * Approximate linear programming


## Prerequisites
Markov chains; linear programming; mathematical maturity (this is a doctoral course). 

## Textbooks
Dynamic Programming and Optimal Control by Dimitris Bertsekas, 4th Edition, Volumes I and II. 

## Course requirements

You will be asked to scribe lecture notes of high quality. There will be a few homework questions each week, mostly drawn from the Bertsekas books. The main deliverable will be either a project writeup or a take home exam. 


## Grading Breakdown

I will follow the following weighting: 20% homework, 15% lecture scribing, 65% final or course project. 

## Homework 
We will have a short homework each week. Please write down a precise, rigorous, formulation of all word problems. For example, specify the state space, the cost functions at each state, etc. 

1. Due Monday 2/3: Vol I problems 1.23, 1.24 and 3.18.  [Solutions to 1.23,1.24](https://djrusso.github.io/Dynamic-Optimization-Course/HW1_Solns.pdf) [Solution to 3.18](http://www.athenasc.com/DP_4thEd_theo_sol_Vol1.pdf)
2. Due Monday 2/10: [Homework 2](https://djrusso.github.io/Dynamic-Optimization-Course/HW2.pdf). [Solutions to Homework 2](https://djrusso.github.io/Dynamic-Optimization-Course/HW2_Solns.pdf)
3. Due Monday 2/17: Vol I problem 4.14 parts (a) and (b). Vol II problems 1.5 and 1.14. 
4. Due Monday 2/24: [Homework 4](https://djrusso.github.io/Dynamic-Optimization-Course/HW4.pdf) 
5. Due Monday 3/2: [Homework 5](https://djrusso.github.io/Dynamic-Optimization-Course/HW5.pdf) [Solutions to Homework 5](https://djrusso.github.io/Dynamic-Optimization-Course/HW5_solutions.pdf)
6. Due Monday 3/23: [Homework 6](https://djrusso.github.io/Dynamic-Optimization-Course/HW6.pdf)
7. Due Monday 4/6: [Homework 7](https://djrusso.github.io/Dynamic-Optimization-Course/HW7.pdf)
8. Due Monday 4/13: Read Bertsekas Vol II, Section 2.4 Do problems 2.5 and 2.9
9. Due Monday 4/20: [Homework 9](https://djrusso.github.io/Dynamic-Optimization-Course/HW9.pdf)

## Reading 

1. For Class 1 (1/27): Vol 1 sections 1.2-1.4, 3.4
2. For Class 2 (2/3): Vol 1 sections 3.1, 3.2. 
3. For Class 3 (2/10): Vol 1 sections 4.2-4.3, Vol 2, sections 1.1, 1.2, 1.4
4. For Class 4 (2/17): Vol 2 section 1.4, 1.5
5. For Class 5 (2/24): Vol 2 section 1.3. [A Short Proof of the Gittins Index Theorem](https://djrusso.github.io/Dynamic-Optimization-Course/short_proof.pdf), [Connections between Gittins Indices and UCB](https://arxiv.org/abs/1904.04732)
6. For Class 6: Vol 2 Section 2.1,2.2.  
7. For Class 7: Vol 2, section 2.3.  [RTDP](https://djrusso.github.io/Dynamic-Optimization-Course/paper_RTDP.pdf), [State aggregation 1](https://djrusso.github.io/Dynamic-Optimization-Course/paper_state_agg_1.pdf), [State aggregation 2](https://djrusso.github.io/Dynamic-Optimization-Course/paper_state_agg_2.pdf)
8. For Class 8: Vol 2, section 6.3. [Fitted value iteration](https://djrusso.github.io/Dynamic-Optimization-Course/paper_fitted_vi.pdf),[Deep Q learning in Atari](https://djrusso.github.io/Dynamic-Optimization-Course/paper_dqn.pdf)
9. For Class 9: Vol 2 section 2.4, 6.4. [Alpha Go Paper](https://www.nature.com/articles/nature24270)
10. For Class 10: [Chapter 13 of Sutton and Barto](http://incompleteideas.net/book/the-book-2nd.html), [Actor critic methods](https://djrusso.github.io/Dynamic-Optimization-Course/paper_actor_critic.pdf), [Natural policy gradient](https://djrusso.github.io/Dynamic-Optimization-Course/paper_npg.pdf), [Recent convergence bounds](https://djrusso.github.io/Dynamic-Optimization-Course/paper_pg_bounds.pdf)

## Lecture Notes
1. [Class 1 Notes](https://djrusso.github.io/Dynamic-Optimization-Course/DP_Notes_1.pdf) 
2. [Class 2 Notes](https://djrusso.github.io/Dynamic-Optimization-Course/DP_Notes_2.pdf) 
3. [Class 3 Notes](https://djrusso.github.io/Dynamic-Optimization-Course/DP_Notes_3.pdf)
4. [Class 4 Notes](https://djrusso.github.io/Dynamic-Optimization-Course/DP_Notes_4.pdf)
5. [Class 5 Notes](https://djrusso.github.io/Dynamic-Optimization-Course/DP_Notes_5.pdf)
6.  [Class 6 Notes](https://djrusso.github.io/Dynamic-Optimization-Course/DP_Notes_6.pdf) and [slides on priority policies in scheduling](https://djrusso.github.io/Dynamic-Optimization-Course/priority_policies.pdf)  
7. [Class 7 Slides](https://djrusso.github.io/Dynamic-Optimization-Course/DP_slides_7.pdf) 
8. [Class 8 Slides](https://djrusso.github.io/Dynamic-Optimization-Course/DP_slides_8.pdf) 
9. [Class 9 Slides](https://djrusso.github.io/Dynamic-Optimization-Course/DP_slides_9.pdf) 
10. Class 10 Slides subsumed by class 11. [Recap given in class 10](https://djrusso.github.io/Dynamic-Optimization-Course/Recap_10.pdf)
11. [Class 10 and 11 Slides](https://djrusso.github.io/Dynamic-Optimization-Course/DP_slides_10_11.pdf)
12. [Class 12 Slides](https://djrusso.github.io/Dynamic-Optimization-Course/DP_slides_12.pdf) 


