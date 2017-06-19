Simple examples of OpenCL code
===============================

Simple examples of OpenCL code, which I am using to learn heterogeneous and GPU computing with OpenCL. 

# Examples included

- `add_numbers`: add a list of numbers together. Includes detailed error handling which makes the code harder to read and understand
- `square_array`: computes *array*^2 (I am playing mostly with this one)
- `sum_array`: sums two arrays
- `cf4cl`: testing OpenCL C wrapper
- `Hello_World`: OpenCL "Hello World" by Apple
- `mandelbrot`: my attempt at a simple Mandelbrot set calculation
- `N-BodySimulation`: Apple's N-body simulator which clearly illustrates the speedup gained by using the GPU. Requires Xcode
- `RayTraced_Quaternion_Julia-Set_Example`: Apple

Note: So far, only two of the examples below clearly demonstrate the computational advantage of using a GPU for processing–`N-BodySimulation` and `RayTraced_Quaternion_Julia-Set_Example`, both developed by Apple programmers. As I understand OpenCL better, the codes will improve and the advantages of GPU will become apparent (hopefully).

# Info about OpenCL devices

To learn about your OpenCL devices, try:

    clinfo

To install `clinfo` on MacOS:

    brew install homebrew/science/clinfo

# References

## Slides

- [OpenCL introduction](https://www.eecis.udel.edu/~cavazos/cisc879/Lecture-06.pdf), S. Grauer-Gray
- [OpenCL introduction](http://smai.emath.fr/cemracs/cemracs16/images/FDesprez.pdf), F. Desprez

## Code walkthroughs 

- [Vector addition in OpenCL](https://www.olcf.ornl.gov/tutorials/opencl-vector-addition/) (Oak Ridge National Lab)
- [Getting started with OpenCL and GPU computing](https://www.eriksmistad.no/getting-started-with-opencl-and-gpu-computing/), by E. Smistad
- [A gentle introduction to OpenCL](http://www.drdobbs.com/parallel/a-gentle-introduction-to-opencl/231002854), Dr. Dobbs. Includes interesting analogies, but may be too hard as a first read

## Courses

- Hands-on OpenCL
- AMD OpenCL course
- Introduction to OpenCL, Manchester

# TODO

- [ ] get workgroup size automatically