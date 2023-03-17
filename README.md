# HybridMemory
Codes following Hybrid Architectures based in CPU/GPUs or CPUs only with OpenMP, and CUDA.
You can compile and execute the codes using the next instruccions:

To compile: mpicc -fopenmp <source_code>.c -o  <executable_name>

To run: mpiexec -n <processors> ./<executable_name> -steps <steps> -threads <threads> or
mpirun -np XXX <executable_name>
