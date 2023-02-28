# Hadoop Multi-Node Cluster Setup

# Course
DS3011	Big Data Analytics <br />

# Link

Follow the tutorial at the link below for multimode cluster setup for Hadoop <br />
https://medium.com/@jootorres_11979/how-to-set-up-a-hadoop-3-2-1-multi-node-clusteron-ubuntu-18-04-2-nodes-567ca44a3b12 <br />

# Learning Outcomes

• Networking <br />
• Virtual Machines <br />
• Password less remote log in <br />
• Better understanding of UNIX/Linux <br />
• Understanding of Yarn Resource Manager <br />
• Deeper Understanding of Hadoop components <br />
• Stepping in the direction of becoming Big Data Architect <br />

# Requirements
# Master Node
1. There need to be minimum 3 nodes configured for multi node setup.
2. The cluster is to be evaluated on the text file provided (“books_large_p1.txt” 2.52/2.3 GB).
3. A Screenshot displaying all the data nodes that are up and sending their heartbeat to the Master Node.

# Slaves Node
1. A Screen shot showing the cluster metrics including total Pooled Memory and the number of Active Nodes.
2. A Screenshot displaying the directory of the cluster.
3. A Screenshot showing live nodes, total configured capacity etc.
4. A Screenshot that shows the head of the results with “Availabilty” parameter showing how many slave nodes were involved in processing these results.
5. A Screenshot of the output using cat command running on “part-00000”.

# Prove Task 
•	Prove that the 2.5 GB file was chunked, distributed, and processed on multiple nodes.
•	Change the number of reducers to be equal to the number of Data Nodes.
•	Prove how many mappers and reducers are configured on the cluster. By default, there is only one reducer which becomes the bottleneck of the whole process.


# Note
The Description.pdf contains the detailed description of this repository.
The Project.pdf contains screenshot of the project's requirements






