## Readme:

All code is in the notebook variational_circuit.ipynb. All imported packages are at the beginning of the notebook, and the Qiskit version(s) are also printed out.

# (Overlooked Issue in Code/Analysis):

There is a tiny error in the analysis of the final part where I used superposition of initial states. I noticed I used [5, 6] and [5, 5, 6] as initial input states with two different output states 0011 and 0101 respectively however when these integer representations are converted to a statevector, they are actually the same. This can be amended by simply choosing another number [5, 5, 6] -> [5, 6, 7] or something like that.

As it is past the submission date, I will not be making any sort of change in the notebook until it has been assessed, instead I am just making a note of this in the ReadMe file. 