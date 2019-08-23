Finding Longest Common Subsequence (LCS) involves comparison of two or more sequences and find the Longest Subsequence which is common to all sequences. This is a NP (Non Deterministic-Polynomial time) hard problem.

Identifying MLCS (Multiple Longest Common Subsequences) in (Biological) DNA sequences is helpful to generate Phylogenetic tree, Motif identification and DNA sequence alignment.  

For over thirty years, lot of research is going on to find an optimized solution for the LCS problem. The most of the existing solutions are based on Dynamic Programming (DP) methodology. The DP method computes the score matrix for the sequences and obtain the LCS by scanning the entire score matrix. The score matrix contains both matched and unmatched positions of the sequences. LCS occurs only at the matched positions of the sequences. The scanning of unmatched positions of the score matrix is not needed for finding LCS. This  unwanted scanning increases the time complexity of the LCS algorithms. 

The proposed Positional_LCS,  which focuses only on matched positions of the score matrix overcome this exponential time complexity. So the Positional_LCS reduces the time complexity.

Positional_LCS has been cited/used in various domain applications like: For PLC (Industrial Automation), Substring parsing, Software Testing, Pattern Matching, Protein Sequence Alignment and Web video duplicates removal, Spatial Informatics-RSS based Fingerprinting location system in GSM, Optimized Parallel algorithm using openMP for Multi-Core Architectures 

Here are the researchers and publications have cited my research in their research/implementations.

1.Nedved M, Virba P, Obitko M, “Tool for visual difference display of programs in IEC 61131-3 ladder diagrams”, Industrial Technology (ICIT), 2015 IEEE International conference On, Czech Inst. Of Robot & Cybern, Czech Tech. Univ. In Prague, Prague, Czech Republic, pp 2994-2999. 

2.Liu Yun-long, “Token-based structured code matching homology detection technology”, Application Research of Computers, Vol. 31 No.6, Jun. 2014

3.Yliopisto Oulun, “Towards test suite optimization in software component testing by finding and analysing repeats in test trace”, Master’s Thesis, Oulu University, Finland University, May’2015

4.Gupta Vibha, “Pattern Matching Algorithms for Intrusion Detection and Prevention Systems”, Master’s Thesis, Computer science and Engineering Department, Thapar University

5.Kumar Manish, “The impact of Genetic Operators in Solving multiple Protein Sequence Alignment “, International Journal of Pharma and Biosciences, Indian School of Mines, Dhanbad, April 2015

6.Citation in Chinese Journal – Remove web video duplicates (April’2015)

7.Zhongliang Deng, Enwen Hu*, Lu Yin, “A Novel Approach for RSS-based fingerprinting location system in GSM”, Beijing University of Posts and Telecommunications, TELKOMNIKA, Vol.15, No.2, June 2017, pp. 590~597.

8.Hanok Palaskar, Prof. Tausif Diwan, “AN OPTIMIZED PARALLEL ALGORITHM FOR LONGEST COMMON SUBSEQUENCE USING OPENMP”, International Research Jounrla of Engineering and Technology (IRJET), Vol 03, Issue 06, June 2016

9. Mapreduce pattern analysis implementation: 
https://github.com/placidoneto/mapreduce-designpatterns-analysis/blob/master/paper/retrieved-works.bib
