# Cluster-Analysis
Cluster analysis or clustering is the task of grouping a set of objects in such a way that objects in the same group (called a cluster) are more similar (in some sense) to each other than to those in other groups (clusters).

# Goals and tasks
- To use multiple survey data to group students
- Data sources are ： （1）Student course registration list (2) Students geographical location and past travel history

# Pacakges
`library(tidyr)`<br>
`library(dplyr)`<br>
`library(klaR)`<br>
`library(ggplot)`

# Results
<img src="./p1.png" alt="Editor" width="750">

The average motivation in cluster 1 is above 0 while the counterpart in cluster 2 is below 0. At large, average motivation fluctuate week by week.

It would be useful to determine how many people are in each cluster. We can do this easily with dplyr.

<img src="./p2.png" alt="Editor" width="750"> <br>
"Decide: 3 clusters is better/more informative than 2 cluters. Answer: FALSE"


<img src="./p3.png" alt="Editor" width="900">
Based on this this longtitude and latitude map, we could tell that students coming from the same place have more in common and are easily forming into clusters. To increase cultural exchange and activate classroom dynamics, it's better to have students from different clusters to team up for group work/ discussion.
