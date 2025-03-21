# Blockchain-Based-Financial-Assets-Tokenization


Algorithm 1: Discrete homogeneous tokenization 


Input: Ā, N, k 

Output: a, M, CM

Function Preprocessing(Ã, k, N):

A=k. A

a = A

S = ΣN-k+1 a

B = 0

n = 2,..., k

for i Nk + 1 to N do

 S = N―k+n-1ã
 
 aN-k+1 = min(AN-k+1, S/(n − 1))
 
 8 = AN-k+n - aN-k+n
 
 B = B+ B0
 
 S = S+aN-k+n
 
return ā, B


Function Distribution (a, N, k, B):

s = ΣN ā

SM k

M = [S/k]

Bo =

for n N Bo + 1 to N do

 ân = ăn -1
 
B = B + Bo

for n = 1 to N do

 ln = Σn-1ã + 1 
 
 rn = Σn a
 
a = a/k

for i = 1 to N do

 for j = 1 to M do
 
  CM[i, j] = 0
  
for i = 1 to k do

 for j = 1 to M do
 
  Find n: In M. (i-1)+ j ≤rn 
  
  CM[n,j] = 1/k
  
return ã, M, CM
