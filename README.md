# mandelbrot_numba
mandelbrot implementation using Python, numpy and numba jit features
it is necessary to install, using pip or any other package installer, numpy, numba, matplotlib.pyplot
the code stores the mandelbrot calculation in an array of 4096x4096 points, and displays this array using matplotlib functions
included are three png files:
showing processing time without any optimization 
showing processing time usig numba jit optimazition (this python code)
showing processing time usig a NVIDIA GTX1070 mobile, using CUDA version 10 API
All is run on a HP OMEN laptop, having 16GB memory and a Intel Core i8 8750, with 6 cores
