# DS_202_Project_Suffix_Arrays
Suffix array construction algorithms- Comparison of runtime of O(n), O(n log(n)) and naive algorithms on real genomes.
1) KA algorithm (corresponding folder)-
   Implemented Ko and Aluru's algorithm for linear time construction of Suffix Arrays (Pang Ko and Srinivas Aluru. Space efficient linear time 
   construction of suffix arrays. Journal of Discrete Algorithms, 3(2-4):143–156, June 2005)
   Repository used for implementation- https://github.com/kopang/LinearSuffixArray.git
   Use the Makefile provided to compile the code (executable named test would be present)
   Now, to execute the linear suffix array construction algorithm on a given dataset, use the following command-
    ./test seq_Y_chrom.fasta
   You can replace seq_Y_chrom.fasta with any other input file provided below (with appropriate location if not present in the current directory)
   The runtime of the algorithm would also be printed in the terminal (standard output).
   The pre-compiled executable file is also included in the folder.
   Below is the link to the folder containing the input datasets on which we tested the KA algorithm-
   https://indianinstituteofscience-my.sharepoint.com/:f:/g/personal/vigneshr1_iisc_ac_in/EkZaFmaHWBJNgorUGemsAo0BA4o8nFtzWULvp6WiIciBFQ?e=ehpXyq
3) KS algorithm (O(n)), O(n log(n)) algorithm, O(n^2 log(n))- Naive algorithm (Second Folder)-
   Here, as mentioned above, this folder contains the implementation of the three algorithms and a comparison of their actual runtimes.
   KS Algorithm- (Juha Karkkainen, Peter Sanders, and Stefan Burkhardt. Linear work suffix array construction.
   Journal of the ACM, 53(6):918–936, November 2006)
   Repository used for implementation- https://github.com/6851-2021/suffix-array.git
   You can also refer to the README of the original repository retained in the folder for further details and specifics.
   Again, use the Makefile provided in the folder to compile the code (an executable named sa would be present).
   Now, to execute any of the above three suffix array construction algorithms on a given dataset, use the following command-
   To run the linear algorithm (KS)-
   ./sa linear 10  < inputs/seq_Y_chrom.fasta
   To run the O(n log(n)) algorithm-
   ./sa nlogn 10  < inputs/seq_Y_chrom.fasta
   To run the naive algorithm-
   ./sa naive 10  < inputs/seq_Y_chrom.fasta
   The runtime of the algorithm would also be printed in the terminal (standard output).
   Sample output: Average elapsed time: 12.2509 seconds (over 10 runs)
   The pre-compiled executable file is also included in the folder.
   Replace 10 with the number of times (iterations) of the algorithm you desire (for computing average runtime).
   You can replace seq_Y_chrom.fasta with any other input file provided below (with appropriate location- on your system).
   Below is the link to the folder containing the input datasets on which we tested the above three algorithms-
   
   
   
   
   
   
   
   
   
   
     
   
      
   
   
   
