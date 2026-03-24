Market Equilibrium Price Determination using MATLAB

⸻

→ Project Overview

This project focuses on determining the market equilibrium price by modeling demand and supply as nonlinear functions and solving them numerically using MATLAB.

The equilibrium point is where:
• Demand equals Supply
• Market clears without surplus or shortage

The project demonstrates how numerical methods (Bisection Method) and graphical visualization can be used to solve real-world economic problems.

⸻

→ Objective

The main objectives of this project are:
• To understand the concept of market equilibrium
• To model demand and supply as nonlinear equations
• To incorporate multiple economic factors (income, cost, etc.)
• To determine equilibrium price numerically
• To visualize demand-supply intersection using MATLAB

⸻

→ Problem Description

A market system is modeled with:
• Nonlinear demand function
• Nonlinear supply function
• Multiple influencing variables like income, cost, and technology

The goal is to compute the equilibrium price where demand equals supply.

⸻

→ Mathematical Formulation

Demand Function

D = a - bp - cp^2 + dI + eP_s - fP_c

Supply Function

S = g + hp + ip^2 - jC + kT

Where:
• p = Price of product
• I = Consumer income
• P_s = Price of substitute goods
• P_c = Price of complementary goods
• C = Cost of production
• T = Technology level

• a, b, c = Demand coefficients
• d, e, f = External demand factors
• g, h, i = Supply coefficients
• j, k = Cost and technology influence

(From your notes on page 2 of the file  ￼)

⸻

→ Equilibrium Condition

At equilibrium:

Demand = Supply

D - S = 0

This nonlinear equation is solved numerically.

⸻

→ Assumed Values

The following values are used in the model (page 3):
• I = 10
• P_s = 8
• P_c = 6
• C = 5
• T = 3

⸻

→ Methodology

The equilibrium price is determined using the Bisection Method:
	1.	Define function f(p) = D - S
	2.	Choose initial bounds x_l and x_u
	3.	Compute midpoint x_r
	4.	Check sign change
	5.	Repeat until error tolerance is satisfied
	6.	Final value of p gives equilibrium price

⸻

→ MATLAB Implementation

The MATLAB program performs:
• Definition of parameters and variables
• Formation of nonlinear equation
• Implementation of Bisection Method
• Computation of equilibrium price
• Plotting demand and supply curves

(Code from page 4–5  ￼)

⸻

→ Results

The computational analysis gives:

• Equilibrium Price ≈ 9.7443

The graph shows:
• Downward sloping demand curve
• Upward sloping supply curve
• Intersection point = equilibrium

(Shown in output graph on page 5  ￼)

⸻

→ Key Concepts Demonstrated

This project illustrates:
• Nonlinear equation modeling
• Demand-supply analysis
• Numerical methods (Bisection Method)
• MATLAB programming
• Graphical interpretation of economic models

⸻

→ Engineering & Economic Significance

This analysis is useful in:
• Market price prediction
• Economic modeling
• Policy analysis
• Production planning
• Computational economics

It shows how engineering tools like MATLAB can solve economic problems efficiently.

⸻

→ How to Run the Project
	1.	Open MATLAB
	2.	Copy the provided .m file
	3.	Run the script
	4.	Observe:
• Equilibrium price output
• Demand & Supply graph
• Intersection point

⸻

→ Author

Rusheel Amin
Mechanical Engineering Student
Computational Engineering Laboratory (CEL)

⸻

→ Project Summary

This project successfully demonstrates how market equilibrium can be determined using numerical methods and computational tools, highlighting the importance of MATLAB in solving nonlinear real-world problems.

⸻
