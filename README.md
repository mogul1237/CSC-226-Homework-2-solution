# CSC-226-Homework-2-solution

Download Here: [CSC 226 Homework 2 solution](https://jarviscodinghub.com/assignment/csc-226-homework-2-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

will be marked, since the main function will be deleted before marking begins. Please read through the comments in the template file before starting.
2 Input Format
The testing code in the main function of the template reads a sequence of graphs in a weighted adjacency matrix format and uses the ShortestPath function to compute the weight of a minimum 0-1 path for each graph. A weighted adjacency matrix A for an edge-weighted graph G on n vertices is an n x n matrix where entry ( i , j ) gives the weight of the edge between vertices i and j (or 0 if no edge exists). For example, the matrix
corresponds to the edge-weighted graph in the previous section. Note that the weighted adja- cency matrix for an undirected graph is always symmetric. The input format used by the testing code in main consists of the number of vertices n followed by the n x n weighted adjacency matrix. The graph above would be specified as follows:
8
0 0 0 0 0 12 13 0 0 0 6 0 0 0 0 3 0 6 0 4 0 0 0 5 0 0 4 0 10 0 0 7 0 0 0 10 0 11 8 9 12 0 0 0 11 0 1 0 13 0 0 0 8 1 0 2 0 3 5 7 9 0 2 0
3 Test Datasets
A collection of randomly generated edge-weighted graphs has been uploaded to conneX. Your assignment will be tested on graphs similar but not identical to the uploaded graphs. You are encouraged to create your own test inputs to ensure that your implementation functions correctly in all cases.
3
4 Sample Run
The output of a model solution on the graph above is given in the listing below. Console input is shown in blue.
Reading input values from stdin. Reading graph 1 8 0 0 0 0 0 12 13 0 0 0 6 0 0 0 0 3 0 6 0 4 0 0 0 5 0 0 4 0 10 0 0 7 0 0 0 10 0 11 8 9 12 0 0 0 11 0 1 0 13 0 0 0 8 1 0 2 0 3 5 7 9 0 2 0 Graph 1: Minimum weight of a 0-1 path is 18 Processed 1 graph. Average Time (seconds): 0.00
5 Evaluation Criteria
The programming assignment will be marked out of 50, based on a combination of automated testing and human inspection, based on the criteria in the table below. The running times in the table assume an input graph with n vertices and m edges.
Score (/50) Description 0 – 5 Submission does not compile or does not conform to the provided template. 6 – 25 The implemented algorithm is not that of Dijkstra or is substantially inaccurate on the tested inputs.
26 – 35 The implemented algorithm is accurate on all tested inputs and has an O(n 2 + m log(n)) running time. 36 -50 The implemented algorithm is accurate on all tested inputs, uses a heap-based priority queue to select the next vertex at each step and has an O(n 2 + m log(n)) running time.
To be properly tested, every submission must compile correctly as submitted, and must be based on the provided template. You may only submit one source file. If your submission does not compile for any reason (even trivial mistakes like typos), or was not based on the template, it will receive at most 5 out of 50. The best way to make sure your submission is correct is to download it from conneX after submitting and test it. You are not permitted to revise your submission after the due date, and late submissions will not be accepted, so you should ensure that you have submitted the correct version of your code before the due date. The conneX site will usually allow you to change your submission before the due date if you notice a mistake. After submitting your assignment, conneX will automatically send you a confirmation email. If you do not receive such an email, your submission was not received. If you have problems with the submission process, send an email to the instructor before the due date.
