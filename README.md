## Dataset and simulation scripts for
# Insight into liquid polymorphism from the complex phase behaviour of a simple model

Albert B. Bartok, Gyorgy Hantal, Livia B. Partay

Physical Review Letters 127, 015701 (2021)

<https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.127.015701>

### Content:

The ``structures`` folder contains the unit cell configurations for the new structures, and
an example output trajectory for a Nested Sampling run.

The ``HOOMD_simulation_scripts`` folder contains jupyter notebooks to perform NPT and Grand-canonical 
simulations of the Jagla model with the HOOMD package. Note that the user defined potential only works with
HOOMD if installed with the JIT package, which is not included in the default conda install! (See instructions 
in the HOOMD-Blue manual.)

The file ``nested_sampling_input.inp`` is an example input file to perform nested sampling calculations on the Jagla
model, with the pymatnest package at constant pressure.  

[TI scripts to be added] 
