# std-gamma
gamma synthesis library

# gamma is a synthesis library
* I do not know who makes it
* I think the license is BSD
* It is the same license as Gamma

# GPU
* experiment with running on the NVidia
* mostly compile with the openmp simd and gpu openacc
* the fft need to be replaced with cufft or vkfft
* it is not possible to vectorize filters and algorithms with delays that I know how
* if you do you will get very cool effects but it doesn't work right
* you can vectorize fft fir filter 
* any algorithm with delay or that is recursive argument of itself only run in streams
* you can run many streams at a time each in their own channel/voice

# Raspberry/Banana Pi
* make it work on the raspberry easy
* I use ubuntu/debian pi os
