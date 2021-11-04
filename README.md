# Efficient-Polynomial-Regression
IT
<h2> Regressione polinomiale e discesa stocastica del gradiente </h2>
<head>
<p1> Implementazione dell'algoritmo di regressione 
polinomiale in linguaggio C con alcune ottimizzazioni in linguaggio Assemblyx86 per sfruttare le forme di parallelismo SIMD e ILP-based. Sono implementati
due diversi algoritmi di regressione:  </p1>
<li>
Variante SGD che usa il meccanismo della discesa stocastica del gradiente esaminando un batch di k campioni
</li>
<li>
La variante ADAGRAD che usa l'algoritmo adagrad come acceleratore
</li>
<br>
<p1>
Le due varianti sono implementate nella versione a 32 ed a 64 bit, con l'aggiunta anche delle direttive OpenMP.
</p1>

EN
<h2> Polynomial Regression and Stochastic Gradient Descent </h2>
<head>
<p1> Implementation of Polynomial Regression algorithm in C with several optimizations in Assemblyx86 in order to exploit SIMD parallelism and ILP-based parallelism.
There are two implementations: </p1>
<li>
SGD, which uses Stochastic Gradient Descent with a batch sized k
</li>
<li>
ADAGRAD, which uses adagrad algorithm in order to accelerate the descent and improve performance
</li>
<br>
<p1>
For each algorithm, there are two versions, 32 bit and 64 bit; we also added OpenMP.
</p1>
