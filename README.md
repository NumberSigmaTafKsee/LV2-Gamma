# LV2-Gamma
gamma synthesis library

# Gamma is very useful
* It is much more useful to me than Stk really
* Stk is more about music instruments than algorithms

# I am not complaining about Stk
* I use it in the experiments

# there are things that can be improved on Gamma and Stk
* It is not my library so I do not really do it
* It need aligned memory for the allocator
* It would be good to compute frames at a time and it can be optimized by compiler or openmp simd
* I would prefer it use FFTW3 because it is simply what I have all the code for and it already is portable to Cuda like that
* I would prefer it just use std c++ library complex and arrays 

# it does not need it
* it does need aligned memory though and it is not hard to modify them to do it
* I can replace FFT with FFTW3 very easily too

# Everything else then works simply with anybody else
* By gett the pointer you can use it with IPP,Kfr or anything
* If it is aligned then it can be used by any function that require aligned memory
