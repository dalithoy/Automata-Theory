# CS 202 : Automata Theory
 
Weightage :  
End sem: 40%  
Mid sem: 30%    
Assignments/Quizzes : 30\% (4 quizzes/assignments with equal weight)

All submissions, resources on moodle. 
Tutorials as needed. 

References: 
- Introduction to Automata Theory, Languages and Computation \\
by John. E. Hopcroft, Rajeev Motwani, J. D. Ullman (HMU) \\
Pearson

- Elements of the Theory of Computation\\
by H.R. Lewis and C. H. Papadimitrou  (LP) \\
Prentice Hall Inc.

-  Automata and Computability\\
Dexter Kozen (DK) \\
Springer.


* * * 
   
## Week 1 : Lecture 1 : Tuesday: Dec 14, 2021  
  
### Introduction lecture :    
  
- Credit structure, weights for exams.
- History of computation - Leibniz to Turing 
- Leibniz's dream, Turіng  machines. 
- Turing and his Machines. 
- Applications : Formal methods : Car crash and the deployment of air bag. 
- Applications of Automata theory (to model system) 
- Applications of Logic (to specify a property) 
- Alphabet, language, concatenation, iteration 
- examples of languages 

Reference : 
+ The road from Leibniz to Turing: Martin Davis
+ Moshe Vardi Lecture  : From Aristotle to iphone : 
                         https://www.youtube.com/watch?v=iWWqUIzDIeQ
 + HMU Section 1.5 
 
* * * 
## Week 1 : Lecture 2 : Wednesday: Dec 15, 2021    
# Deterministic Finite Automata (DFA) 
- Formal definition of DFA, run of DFA, accepting runs, non-accepting
  runs,
- acceptance of a word by a DFA
- examples : Modeling a FAN by DFA, even length strings accepting DFA.

Reference : 
 + HMU Section 2.2 

* * * 
## Week 1 : Lecture 3 : Thursday : Dec 16, 2021
# NFA
- example of DFA for a language with words having even number of a's
- Regular language definition
- Non-deterministic Finite Automata (NFA)
- Examples of NFA for language with words ending with 100
- multiple runs, acceptance by NFA
- Formal definition, \delta, \delta^{\hat} 
- Example of NFA for language with words having last letter as b. 

Reference
 + HMU Sections 2.3.1, 2.3.2, 2.3,2, 2.3.3, 2.3.4

* * * 
## Week 1 : Lecture 4 : Friday : Dec 17, 2021
# NFA and DFA equivalence, subset construction
- why NFAs? 
- DFA to NFA
- NFA to DFA construction, proof of equivalence
Reference 
 + HMU Sections 2.3.5
* * * 

## Week 2 : Lecture 5 : Tuesday : Dec 21, 2021
# Subset construction recap 
# Example of subset construction for the language with words having 2nd last letter as b 
# Incremental DFA construction 
# Example of incremental DFA construction for the language with words having 2nd last letter as b 

# Exponential size DFAs. Lower bound argument for the language with words having n-th last letter as b. 

Reference : 
+ HMU Sections 2.3.5, 2.3.6, 

* * * 

## Week 2 : Lecture 6 : Wednesday : Dec 22, 2021
# recap of lower bound argument 
# \epsilon NFA, Motivation. 
# Example of \epsilon-NFA : Language with words which do not use all letters from the alphabet. 
# \epsilon-NFA : Formal definition, extended transition function
# \epsilon-closure of states.

Reference : 
+ HMU Sections 2.3.6, 2.5 

* * * 

## Week 2 : Lecture 7 : Thursday : Dec 23, 2021
# recap of \epsilon-NFA, \epsilon-closure
# \epsilon-NFA to NFA : formal proof as an exercise.
# examples
# closure properties of Regular languages : Union, Complementation, intersection. 

Reference 
+ HMU Sections 2.5, 4.2.1 

* * * 

## Week 2 : Tutorial 1 : Friday : Dec 24, 2021
# Questions based on NFAs, DFAs, diagonalization 

* * * 

## Week 3 : *******no Classes : Four classes missed*************

* * * 


## Week 4 : Lecture 8 : Jan 4, 2022
# Properties of Languages 
# Regular Expressions : Definition, Examples, Applications. 
 
Reference 
+ HMU Sections 3.1

* * * 

## Week 4 : Lecture 9 : Jan 5, 2022
# Regular expressions - recap and new example
# Regular Languages (DFA) to Regular expressions : Proof. 

Reference
+ HMU Sections 3.2.1

* * * 
## Week 4 : Lecture 10 : Jan 6, 2022
# Regular Languages (DFA) to Regular expressions : Proof Recap
# Example
# Complete DFA

Reference
+ HMU Sections 3.2.1, 3.2.6 (box titles Dead states and DFA's missing
  				transitions). 
* * * 
## Week 4 : Lecture 11 : Jan 7, 2022 (1.5 hour lecture)
# Regular Expressions : properties : algebraic laws for Regular Expressions. 
# Examples of proofs of identities 
# Regular Expressions to NFAs (Thompson's construction)
# Examples of construction 
# Time complexity of NFA construction from Regular expressions. 
# Time complexity of membership of a word using NFA, DFA. 

Reference 
+ HMU sections 3.4 (algebraic laws), 3.2.3 (Reg expr to NFA), 4.3.3 (membership complexity). 

* * * 

## Week 5 : Lecture 12 + 13 : Jan 11, 2022  (1.5 Lecture) 
# Non-regular languages 
# 0^n 1^n : proof of non-regularity 
# Pumping Lemma : Proof, Example
# Adversarial argument form of Pumping Lemma
# Examples using Pumping Lemma (0^n1^n, palindromes), Exercise (well
  balanced parenthesis) 

Reference 
+ HMU Sections 4.1

Comment : Two 90 minutes lectures (11 and 12), so we have made up for 
          one missing lecture from 3rd week. Effectively we have done 
 	  13 (one hour lectures so far).  
* * * 
 
## Week 5 : Lecture 14 : Jan 12, 2022
# Checking equivalence of two states of DFA
# Definitions: equivalence states, distinguishable states
# Table-filling algorithm 
# Example

Reference 
+ HMU Sections 4.4.1

* * *
 
## Week 5 : Lecture 15 : Jan 13, 2022
# Correctness of table filling algorithm 
# construction of minimal DFA

References
+ HMU 4.4.3, 4.4.4
 
* * *

## Week 5 : Quiz 1 : Jan 14, 2022
 
* * *
 
## Week 6 : Lecture 16 : Jan 18, 2022
# Discussion on Quiz 1 

* * * 

## Week 6 : Lecture 17 : Jan 19, 2022
# MyHill Nerode Theorem
# Equivalence relation given by L on \Sigma^*, example
# Equivalence relation given by a DFA on \Sigma^*, example
 
References 
+ LP : Section 2.5

* * * 

## Week 6 : Lecture 18  and Lecture 19 : Jan 20, 2022
# MyHill Nerode Theorem
# Proof that eq-rel-of-M refines eq-rel-of-L
# Construction of Minimal Automata from eq-rel-of-L
# Corollary: L is regular iff eq-rel-of-L is of finite index.
 
References 
+ LP : Section 2.5

Note: 90 minute lecture. 
 
* * * 

## Week 7 : Lecture 19 and Tutorial 2 : Jan 21, 2022
# Example of {a^i,b^i}. Non-regular using MyHill-Nerode Theorem. 
# Tutorial 2 : questions, on a^p, product constructions, and 
  FirstHalves using Pebbble automaton. 

Note: 90 Minutes (30 Min of 19th Lecture + 60 min of Tutorial) 


* * * 

## Week 8 : Midsem Examination Week 

* * * 

## Week 9 : Lecture 20 : February 1, 2022
#Context-Free Grammars
# regular expressions as language generators : a (a*+b*)b 
# example of grammar for a regular language
# terminology : Grammar, rules, derivations, start symbol, language of a grammar 
# more examples: a^nb^n, palindromes
# exercise : Well balanced parenthesis

 
References 
+ LP : Section 3.1
 
* * *  

## Week 9 : Lecture 21 : February 2, 2022
# Context-Free Grammars
# Parse trees 
# Ambiguous Grammars, Unambiguous grammars
# examples of both for L_bal 
# Inherently ambiguous languages

References 
+ LP : Section 3.2
 
* * * 

## Week 9 :  Lecture 22 : February 3, 2022
# Unambiguous grammar : Example for L_bal
# DFA --> CFGs
# Push Down Automata

References 
+ LP : Section 3.1, 3.2, 3.3

* * * 
 
## Week 9 : Tutorial 3 : February 4, 2022
Tutorial on designing CFGs, PDAs. 

* * * 

## Week 10: Lecture 23 : February 8, 2022
# CFGs to PDAs
# Construction. 

References 
+ LP : Section 3.4 

* * * 
## Week 10: Lecture 24,25 : February 9, 2022
# CFGs to PDAs
# proof of L(G) \subseteq L(M). 

References 
+ LP : Section 3.4 

* * * 
## Week 10: Lecture 24,25 : February 9, 2022
# CFGs to PDAs
# Proof of correctness : L(G) \subseteq L(PDA).

References 
+ LP : Section 3.4 

* * * 
## Week 10: Lecture 26 : February 10, 2022
# CFGs to PDAs
# Proof of correctness : L(G) = L(PDA).

References 
+ LP : Section 3.4 

* * * 

## Week 11: Lecture 27 : February 14, 2022
#PDAs to CFGs
#Example 

References 
+ LP : Section 3.4 

* * * 

## Week 11: Lecture 28 and 29 : February 16, 2022
# Properties for CFLs
# Closure under union, concatenation, and Kleene Star
# Pumping Lemma for CFLs, statement, proof and examples : a^nb^nc^n, and a^p where p is prime. 
# CFLs are not closed under intersection and complementation 
# CFLS are closed under intersection with regular languages, example : 
  Language with equal  number of a's, b's and c's.  

References 
+ LP : Section 3.5 

* * * 
## Week 11: Tutorial 4 : February 18, 2022
On PDA construction, properties of CFLs, Stronger version of Pumping
Lemma.

#Note : 60 hours of Tutorial and 30 min of lecture. 
* * * 
 
## Week 12 : Discussion of Quiz 1 Solutions: February 22, 2022
# Quiz 1 solutions and cribs

* * * 

## Week 12 : Lecture 30, 31 : February 23, 2022
# Turing Machines
# a^n b^n, a^nb^nc^n
# IDs, configurations, language of a TM
# TMs for addition and subtraction. 

References :

# Section 8.2 of HMU

* * * 

## Week 13 : Lecture 32, 33 : March 3, 2022
# Turing Machines 
# Multi-track TMs
# Multi-tape TMs
# 2-stack Machines
# 2-counter machines. 
# Proof of equivalence of TMs with 2-counter machines (multi-stage proof, using all these machines). 
 
References : 
# Section 8.3.2 of HMU (multi-track machines)
# Section 8.4.1, 8.4.2 of HMU (multi-tape machines, equivalence with multi-track machines)
# Section 8.5.2, 8.5.3, 8.5.4 of HMU (multi-stack machines, counter machines, and their equivalence). 

Note : this was a 90 minute lecture. 
Combined with 18 th February's 30  minutes lecture, 
We have done extra lecture, so in total 33 lectures so far. 

* * * 
 
## Week 13 : Lecture 34 : March 4, 2022
# Turing Machines 
# Non-deterministic TMs and Deterministic TMs equivalence
# TMs and Enumerating machines equivalence
# Recursively enumerable languages
# Church-Turing Thesis : Effective computability 
# TMs and Computers equivalence  

References : 
# Lectures 28 of DK (Church-Turing Thesis)
# Lectures 30 of DK (Enumeration machines)
# Section 8.4.4 HMU (Non-deterministic TMs and equivalence to deterministic TMs)
# Section 8.6 of HMU (Turing Machines and computers)

Note : this was a 90 minute lecture. 

* * * 

 
## Week 14 : Lecture 35 : March 8, 2022
# Recursively enumerable languages, Recursive languages
# Encoding of TMs as binary strings. 
# Example of non-r.e. language : L_d : The diagonalization language.

References 
# Section 9.1 of HMU

* * * 
 
## Week 14 : Lecture 36, 37 : March 9, 2022
# complements of Rec and RE languages
# Universal TMs. 
# L_u the universal language is r.e.
# L_halt the halting problem is r.e.
 
Reference:
# Section  9.2 of HMU (for complements of r.e. and rec languages)
# Lecture 31 of DK

Note: This was 90 minutes lecture. Combined with 90minute lecture on
March 4, we did lecture 37 today. 

* * * 

## Week 14 : Lecture 38 : March 11, 2022
# Reductions: Thm
# example of reductions: L_e is r.e. (reduction from L_u) 
# Show that L_ne is non r.e. as corollary 


Reference : 
   + Section 9.3.1, 9.3.2 of HMU

* * * 

## Week 15 : Lecture 39: March 15, 2022
# Rice's theorem, proof, applications
# One more examples of reduction : 
  + Set of TMs halting on empty tape 
  + set of TMs halting on some input
  + set of TMs halting on all inputs  
 
Reference : 
   + Section 9.3.3 of HMU for Rice's theorem. 
   + Section 5.4 of LP for other problems.  
 
Notes : 90 minutes lecture. 

* * * 

## Week 15 : Lecture 40 and 41 :March 16, 2022
Discussion of Midsem and Quiz 2 questions. 

Note : 90 Minutes Lecture (combined with the previous one we are done
with Lecture 41). 
* * * 

## Week 15 : Tutorial 5: March 18, 2022
Tutorial on DCFLs and TMs. 
* * * 


