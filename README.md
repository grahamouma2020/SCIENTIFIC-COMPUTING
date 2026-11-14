# DATA SCIENCE AND COMPUTING
TASK M and M1
The mathematical relationship is that as the number of concurrent users increases, the server response time also increases, and it increases at a progressively faster rate.This is a positive, nonlinear (quadratic) relationship, represented by: y=ax^2+bx+c
Where:
- x = number of concurrent users.
- y = server response time in milliseconds.
- (a,b,c) = coefficients determined through curve fitting.
In summary:
1. Increasing users generally increases server response time.
2. Higher server loads produce progressively longer delays.
3. Changing the user inputs or measured response times changes the fitted curve and potentially its coefficients.
4. The graph illustrates how server performance deteriorates as concurrent traffic increases.
 The experiment demonstrates how increasing server demand affects response time using quadratic curve fitting.

TASK N and N1
The program demonstrates the mathematical relationship between position, time and speed using numerical differentiation (finite differences).It calculates how fast an object moves by dividing the change in position by the change in time.
Mathematical interpretation: As the object's position changes over time, its estimated speed increases, indicating acceleration rather than constant-speed movement.
Real-world application: The method can be used in GPS vehicle tracking to monitor vehicle speed, detect acceleration and slowing down, and improve fleet management.
Python uses GPS position and time measurements to calculate and visualize how an object's speed changes over time and can extend into a vehicle speed-monitoring program that flags vehicles exceeding a specified speed limit.

TASK Q and Q1
The program demonstrates the mathematical relationship between voltage and time in an RC charging circuit using numerical integration. It uses the solve_ivp function from SciPy to solve a differential equation and estimate the capacitor voltage at different time intervals. The graph shows that capacitor voltage increases rapidly at first and gradually approaches the 5 V supply voltage. The program also compares the numerical solution with a mathematical solution to measure accuracy. A real-world application is designing electronic circuits that use capacitors for energy storage, voltage smoothing and timing. In addtion, numerical integration solves a differential equation to show how a quantity changes over time.

Task R and R1
The program determines the most cost-effective combination  while satisfying a minimum computing-capacity requirement. It uses an objective function to minimize total cost and an inequality constraint to ensure sufficient capacity. The program also checks whole-number server combinations because physical servers cannot be purchased in fractions. A real-world application is data-centre planning, where organizations seek to meet computing demands while minimizing infrastructure costs.The key concept is about optimization to find the best solution to a problem by minimizing or maximizing an objective while satisfying given constraints.

Task S and S1
The program demonstrates Monte Carlo simulation, a mathematical technique that uses repeated random experiments to estimate probabilities. It generates random server-demand scenarios using a normal distribution and identifies how many exceed the available server capacity. It then calculates the estimated probability of overload and plots how this estimate converges as the number of simulations increases. A real-world application is cloud computing, where organizations use simulation to estimate server-overload risks and plan sufficient computing resources.Monte Carlo simulation uses repeated random experiments to estimate the probability of an event occurring.



