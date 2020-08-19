# striatal_SPN_lib

This repository contains a library of striatal projection neurons used in the publication:

Lindroos and Hellgren Kotaleski 2020. 
Predicting complex spikes in striatal projection neurons of the direct pathway 
following neuromodulation by acetylcholine and dopamine. EJN

Code for simulating, analysing and plotting can be found here:
https://github.com/robban80/striatal_SPN_lib
and here:
https://bitbucket.org/rlindroos/neuron/src/cholinergic_modulation/Complex_spike/


The models are built in NEURON+python 
https://www.neuron.yale.edu/neuron/


How to run the models
---------------------

1. install NEURON with python support
2. compile the mechanisms in mechanisms/single (nrnivmodl or mknrndll)
3. execute `python example.py` 
