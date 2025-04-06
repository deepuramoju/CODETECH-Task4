**Name:** Ramoju Gnana Deepika

**Company:** CODETECH IT solutions

**Id:** CT6WSFC

**Domain:** Data Science

**Duration:** February 25th to April 10th, 2025

**Mentor:** N.Santhosh

###  Project Overview: Factory Production Optimization Using Linear Programming
## Objective
To solve a business problem using optimization techniques — specifically Linear Programming (LP) — to determine the optimal number of products a factory should manufacture in order to maximize profit while staying within the constraints of machine availability.

## Business Scenario
A manufacturing company produces two products — Product A and Product B. Each product requires a specific amount of time on Machine 1 and Machine 2, both of which have limited availability. The company wants to maximize total profit based on profit per unit and machine capacity.

## Data & Assumptions
Product 	                   Profit per Unit	                          Machine 1 Time (hrs)	                      Machine 2 Time (hrs)
  A	                            $40	                                            2                                          	1
  B         	                  $30                                           	1                                         	1
  
Machine 1 is available for 100 hours
Machine 2 is available for 80 hours

## Mathematical Formulation
Let:
x = Number of units of Product A
y = Number of units of Product B

## Objective Function:
--**Maximize profit:**
Z = 40x + 30y

--**Constraints:**
2x +  y ≤ 100     (Machine 1 availability)
 x +  y ≤ 80      (Machine 2 availability)
x, y ≥ 0          (Non-negative production)

## Tools & Libraries
--Python

--PuLP library for LP problem modeling and solving

--Optional: Matplotlib for constraint visualization

## Implementation Steps
--Model the LP problem in Python using PuLP

--Define decision variables, objective function, and constraints

--Solve using the default solver

--Print and interpret the optimal values

## Output
--Optimal Units of Product A: 30

--Optimal Units of Product B: 50

--Maximum Profit: $2900

--Machine resources are fully utilized.

## Conclusion
--**Using Linear Programming, the company can:**

Achieve maximum profit of $2900

Efficiently utilize all machine hours

Make data-driven decisions for resource allocation
