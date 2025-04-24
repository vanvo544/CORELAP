# CORELAP
*Using CORELAP Algorithm for arranging Layout Optimization*

CORE LAP (Computerized Relationship Layout Planning) is a heuristic algorithm used for optimal facility layout by arranging departments based on their **closeness relationships**. 
It aims to **maximize the adjacency** of highly related departments, **enhancing process efficiency** and communication.

# In my code:
- Input: The inter-machine **order flow matrix**
- Process:
  + Converts flow intensity **into relationship categories**.
  + Method based on the departmental relationship **A=5, E=4, I=3, O=2 U=1**
  + **Calculates Total Closeness Rating (TCR)** of each machine to define priority in placement.
  + Falls back on TCR when multiple candidates or no strong relationship exists.
  + **After placing each machine, a layout diagram is displayed**.
  + Layout is saved as a .png image, perfect for reports or presentations
- Output: **A final layout image** showing each machine placed on a grid (without considering machine dimensions)
  + Converts the inter-department order flow matrix into AEIOU symbolic relationships.
  + Identifies the optimal sequence for placing machines.
  + Generates visual diagrams for each step of the machine placement process.
