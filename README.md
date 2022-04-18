
### Contributors
- Evan Laferriere
- Rudy Esquerra
- Patrick Froerer
- Youngjung Kim
- Douglas Lam


### Requirements:
- Create a Spark Application that processes COVID data
- Analysis of COVID data
- Produced a .jar file for your analysis.
- Determined Trends from Data
- Implemented logging
- Used Tableau for showing trends and data analysis
- Implemented Agile Scrum methodology for Group Project



### Presentations
- Provided an overview of our results
- High level overview of the process used to achieve our results



### Technologies
- Apache Spark
- Spark SQL
- YARN
- HDFS
- SBT
- Scala 2.12.10
- Git + GitHub
- Tableau



### Getting Started
How to run the app using spark-submit in WSL-Ubuntu

<ul>
<li>Start the Hadoop DFS daemons, the namenode and datanodes with => <i>startdfs</i></li>
<li>Start the resource manager with => <i>startyarn</i></li>
<li>create src/main/source directories in your home directory (/home/username/src/main/source) using the following command: <br>
<i>hdfs dfs -mkdir -p src/main/source</i></li>
<li>Jump into the directory where the jar is located (e.g. /mnt/c/Users/username/Desktop)</li>
<li>run the following command => <i>spark-submit --class QueryTesting project2_2.12-0.1.0.jar</i>
</ul>
