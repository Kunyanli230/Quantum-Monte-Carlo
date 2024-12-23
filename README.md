# Quantum-Monte-Carlo

the python file **Quantum Monte Carlo** is Simpler simulations for small datasets, which is meant to give you a taste of what QMC looks like.

the jupyter notebook **QMC with Application in Necoclassical Model** is based on the Woerner and Egger (2019) paper **Woerner, S., Egger, D.J., 2019. Quantum risk analysis. npj Quantum Information 5, 1–8.
https://doi.org/10.48550/arXiv.1806.06893** It is  realistic simulations for financial modeling and risk analysis. 
The target function is defined as:

\[
f(i) = a \cdot i + b
\]

where:

\[
a = \frac{2c_s}{31}, \quad b = -c_s
\]

and the scaling constant \( c_s \) is given by:

\[
c_s = \left( \frac{3 \pi}{N} \right)^{\frac{1}{3}}
\]

Here:
- \( N = 2^n \) represents the number of applications of the QMC algorithm.
- \( a \) and \( b \) rescale the function values to fit within the range \([-c_s, c_s]\).

Acknowledgement to the researchers from Bank of Canada who wrote this paper **"Quantum Monte Carlo for Economics: Stress Testing and Macroeconomic Deep Learning." DOI: https://doi.org/10.34989/swp-2022-29.**
