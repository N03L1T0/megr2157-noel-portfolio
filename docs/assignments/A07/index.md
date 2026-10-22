# A7 – FEA on Bracket (and Link)

## Objective
The objective of this assignment involves the repeated use of a finite element analysis to fine-tune elements and dimensions through three attempts to get a mesh converge difference of 7% or less on both the bracket and link (2157 only). I will keep my chosen material of ATSM A36 steel, and I completed this on Creo Parametric. 

## Initial Design
1. For the first run of each analysis type, I decided to leave the bracket as-is, and change nothing to get a baseline of the original values for the bracket when I calculated the values. For the Stress analysis, I added a downward force on the cylindrical beam at the bottom of 20lbf, and a constraint on the top of the inside of the bracket, as it would normally rest on another piece there. I had a safety factor of 1.54, mass of 2.1069012e-03 LBF SEC^2 / IN, max stress of 23325 PSI as the very beginning of the top part of the cylindrical beam by the cantilever section, and a max deformation of 0.0178 inches. the results are below:
*insert stress & strain analysis 1*
2. For the next design, I saw that the thickness of the cantilever beam section, connecting the cylindrical beam and top half of the bracket was 0.0745 inches thick, and had some decent stress on it when a 20lb load was applied. I decided to decrease it to 0.070 inches to see how much of a difference it made. The mass changed to 2.1056042e-03 LBF SEC^2 / IN, the max stress was 26415.1 PSI, the max deformation was 0.0212 inches, and the safety factor was 1.36. the mesh convergence I got was 13%. I still must tweak the next design even more. Below are the results:
*insert stress & strain analysis 2*
3. For my third design, I decided to try and shorten the length of the cylindrical beam to reduce the amount of material used in the bracket, specifically from 1.5 inches to around 1.4 inches, in addition to the modified thickness of the second design. With this third design, the new max stress was 23291.5 PSI, max deformation was 0.0187 inches, safety factor of 1.54, and a mass of 2.0730750e-03 LBF SEC^2 / IN. This achieved a mesh convergence of 0.1%! I was surprised to see such a number, but it is well below the exact 7% mark I was supposed to hit. I find it hilarious that on both attempts, I am nowhere any closer to the 7% compared to the last. Below are the results:
*insert stress & strain analysis 3*

## 2157 Link Design


## Decide


## Communicate

