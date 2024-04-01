FROM nlknguyen/alpine-mpich:onbuild

COPY project/ .

# Normal build command
RUN mpicc -o mpi_hello_world mpi_hello_world.c

