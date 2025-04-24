# CORELAP
Using CORELAP Algorithm (Computerized Relationship Layout Planning) for arranging Layout Optimization

- Method based on the departmental relationship A=4, E=3, I=2, U=0, X=-1
- Using the total closeness rating (TCR) to allocate the department.
- TCR is the total relationship ranged by numbers of allocated department with the others.

###Rule:
- Allocate the department has the largest TCR. If we the same largest TCR is obsevered within some department, allocate the department havingmore
A, then E and so on.
- Once the department has the X relationship with re-arraganged department, It will be establised in the the final step. If we have a lot X department, re-arragnged it by decsent of TCR.
- The next department will be allocated based on the close- relationship with the first one (A,E,I). Using TCR if we have more than one possible
outcome.
- Make the loop of process until all deparments has been arranged. 
