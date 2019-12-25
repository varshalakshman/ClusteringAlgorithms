CSE 601: Data Mining and Bioinformatics
Project 2: Clustering Algorithms

Submitted By: Karan Manchandia | karanman | 50290755
              Divya Srivastava | divyasri | 50290383
              Varsha Lakshman  | varshala | 50288138

Folder Hierarchy: 
> project2
   > Code
      > DBSCAN.ipynb
      > GMM.ipynb
      > HAC.ipynb
      > K-means.ipynb
      > Spectral.ipynb
      > README.txt
   > Report
      > Cluster_report.pdf
      

Requirements: Python3.6

*********************************Part1: K-Means Clustering******************************************

How to run the code:

The following inputs would be required to execute K-means on jupyter notebook:
1) Enter the name of the gene expression data file: cho.txt
2) Do you want to enter initial centroids (Y or N): Y
3) Enter initial centers indices: 1,3,5,7,9
4) Enter the total number of iterations: 100

The input parameters can be changed as per the requirement keeping the input format same.


**************************Part2: Hierarchical Agglomerative Clustering*******************************

How to run the code:

1)Before running the code you need to make some configuration settings for the jupyter notebook.
2)Open Command Prompt and type the command "jupyter notebook --generate-config"
3)The output on Command Prompt will be a file location.
4)Go to the file location and open the jupyter configuration file in Notepad.
5)Find the commented line similar to "#c.NotebookApp.iopub_data_rate_limit = 1000000".
6)Uncomment this line and change it to "c.NotebookApp.iopub_data_rate_limit = 1000000000"
7)Save the notepad file and close it.
8) Now, find the HAC.ipynb file inside the Code folder. The Code folder can be found inside the submitted Project folder.
9) Note that in order to run the code you need to place the data files (cho.txt, iyer.txt) inside the same folder in which the HAC.ipynb is placed. 
10) Open the HAC.ipynb file in the Jupyter Notebook.
11) Run all the cells to see the outputs.
   [Note that for some cells in the jupyter notebook you need to enter the data-file name and number of clusters as input.]  

*********************************Part3: Density-Based Clustering**************************************

How to run the code:

The following inputs would be required to execute DBSCAN on jupyter notebook:
1) Enter the gene-expression data file name:DBSCAN.txt
2) Enter the epsilon radius:0.25
3) Enter the minimum points:5

The input parameters can be changed as per the requirement keeping the input format same.

*************************************Part4: Mixture Model Clustering************************************

How to run the code:

The following inputs would be required to execute GMM on jupyter notebook:
1) Enter the name of the gene expression data file:cho.txt
2) Do you want to enter parameters(mu, pi and sigma). Y/N?N
3) Enter the number of clusters5
4) Enter the number of maximum iterations100
5) Enter the threshold value1e-08
6) Enter the smoothing value0.0001

The input parameters can be changed as per the requirement keeping the input format same.

********************************Part4: Spectral Clustering*******************************

How to run the code:

The following inputs would be required to execute DBSCAN on jupyter notebook:
1) Enter the name of the gene expression data file:cho.txt
2) Do you want to enter sigma (Y or N): Y
3) Enter sigma: 10
4) Enter the total number of centroids: 5
5) Do you want to enter initial centroids (Y or N): Y
6) Enter initial centers indices: 1,3,5,7,9

The input parameters can be changed as per the requirement keeping the input format same.
