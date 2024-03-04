In this Hidden Markov Model (HMM) project, I analyzed promoter gene sequences from UCI Machine Learning Repository from the following link:
https://archive.ics.uci.edu/ml/datasets/Molecular+Biology+%28Promoter+Gene+Sequences%29. 

There were three models used to analyze the sequences: (1) Markov chain, (2) Poisson process, and (3) Brownian motion.

Using the first model, I determine the total permutations of nucleotides to create a probability matrix and transition probabilities for promoter sequences and non-promoter sequences.
I reconstructed the popular Gambler's ruin problem and Chapman Kolmogorov equation to find the probabilities of methylating proteins being transcripted based on gene sequences.
With the following information, I was able to model the data to find CpG islands by finding repeat GC pairs.
I calculated the long-run probabilities which informed me that the matrix was irreducible, aperiodic, ergodic, and stationery.

Using the second model, I determined the number of palindromes in the sequence which allowed me to predict the probability of future palindromes in a given number of nucleotides.

Using the third model, I used the Arbitrage Theorem to simulate the amount of time until the first occurrence of a sequence is detected.
