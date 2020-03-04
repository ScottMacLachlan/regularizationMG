# regularizationMG

Repo for LaTeX source for manuscript describing a multigrid method for a class of regularized inverse problems

## Todo list

* Stopping criterion for outer iteration
* Plot data error (normalized against noise norm) and reg. error 
* Second example: heart & lungs phantom??  MRI phantom??
* Test new MG algorithm: robustness to noise and examples
* Third(?) example: image deblurring, problem: Diagonal of K'K, try out:
  * diag(P'diag(diag(K'K))P)
  * sparse approximation on coarse level

## Numerical results

* Radon, full angle: Shepp Logan, sizes=64,128,256
* Radon, limited angle: grains, sizes=64,128,256
* Deblurring: Spaniel
* Noise levels: norm(noise)/norm(rhs) = 1e-2,2e-2,5e-2,1e-1 (whatever works)
* Comparison of V(0,1), V(1,1), V(1,2), V(2,2) for 2e-2 noise Shepp Logan size=64
* Show effect of using zero initial guess, same example
* Full L-curve vs. truncated, same example
* Graph of linear iterations vs. outer iterations (average over lambdas), one additional plot showing the behavior
* Table of error vs. noise level

## Outline / writing tasks
* Write introduction (Misha)
* Description of problem setup and outer/inner algorithm
* Description of the MG algorithm (Matthias/Scott)
* Description of L-curve trimming (Scott?)
* Numerical results (Matthias)
* Conclusions
