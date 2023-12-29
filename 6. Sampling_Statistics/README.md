
## Sampling:
  -  If X1,..., Xn are independent random variables having a common distribution F, then we say that they constitute a sample (sometimes called a random sample) from the distribution F
- Problems in which the distribution F is assumed and specified up to a set of unknown parameters are called parametric inference problems
- Problems in which  nothing is assumed about the form of distribution F are called nonparametric inference problems

## THE SAMPLE MEAN
-  Consider a population of elements with quantities µ and σ2 are called the population mean and the population variance, respectively. Let X1, X2,..., Xn be a sample of values from this population. The sample
 mean is defined by
  - X(bar) =  (X1+···+Xn) / n
- The expected value of the sample mean is the population mean µ whereas its variance is 1/n times the population variance
![Screenshot 2023-12-29 135027](https://github.com/Selvam-DG/Statistics_-and_R_programming/assets/98681717/cc850d12-e586-48d1-a91d-25898a065265)
- When the sample size increases, the variance decreases

![Screenshot 2023-12-29 135215](https://github.com/Selvam-DG/Statistics_-and_R_programming/assets/98681717/3e688a8f-509f-4b87-b8e0-ecacbf6a3ae5)

## The Central Limit Theorem
- Let X1, X2,..., Xn be a sequence of independent and identically distributed random variables each having mean µ and variance σ2. Then for n large, the distribution of \n
                               X1 +···+Xn
 is approximately normal with mean nµ and variance nσ2.\n
 It follows from the central limit theorem that
                       (X1 +···+Xn −nµ) / σ*SQRT(n)
 is approximately a standard normal random variable; thus, for n large,
           P{[(X1+···+Xn)−nµ / σ√n] <x } ≈ P{Z <x}, where Z is a standard normal random variable

















