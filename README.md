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
   Below is the link to the folder containing the input datasets on which we tested the KA algorithm-
   https://indianinstituteofscience-my.sharepoint.com/:f:/g/personal/vigneshr1_iisc_ac_in/EkZaFmaHWBJNgorUGemsAo0BA4o8nFtzWULvp6WiIciBFQ?e=ehpXyq
2) KS algorithm (O(n)), O(n log(n)) algorithm, O(n^2 log(n))- Naive algorithm (Second Folder)
      
   
   
   
