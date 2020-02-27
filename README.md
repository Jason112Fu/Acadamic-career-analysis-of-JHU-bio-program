# Acadamic-career-analysis-of-JHU-bio-program
![image](https://github.com/Jason112Fu/Acadamic-career-analysis-of-JHU-bio-program/blob/master/Ranking%20of%20programs.png)

Based on the proportion of graduates engaged in academic careers of each program, I divided the bio-related programs in JHU into three clusters. Cluster 1 is "high proportion upon graduation, high proportion 10 years after graduation"; cluster 2 is "high proportion upon graduation, low proportion 10 years after graduation"; cluster 3 is "low proportion upon graduation".

For a student who decided to pursue an academic career, cluster 1 programs are the best choices and cluster 3 are the worst.

industry question: What are the opportunities for graduates to enter and stay in academia for each project?

data question: cluster based on proportion of graduates in academia upon graduation and decrease over 10 years.

data answer: see the figure.

industry answer: as described above.

http://nglscoalition.org/coalition-data/#close

description:

Select the data representing proportion of graduates from each project who enter academia upon graduation and the proportion of graduates who work in academia after ten years of graduation.

Caculate the decrese with function: (upon graduation - 10 years) / upon graduation.

Normalize the "upon graduatin" data and "decrease" data.

Select three programs representing the three categories of program.

Caculate the distances of each programs to thoes three programs

Get the cluster by comparing the distances.
