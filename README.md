# Efficient Learning Noise - Data Repo

An alternative source of this data is DataDryad at https://doi.org/10.5061/dryad.q83bk3jf0

This contains the data from the IBMQ 14 used to create the charts and analysis in "Efficient learning of quantum noise". https://arxiv.org/abs/1907.13022 and https://doi.org/10.1038/s41567-020-0992-8

The twirls themselves are generated using a set of simultaneous RB circuits. Either single Clifford twirls or a combination of single and double Clifford twirls. This is detailed in the paper. Software allowing you to create the runs and sumbit them to an IBMQ Experience machine can be found at https://github.com/rharper2/query_ibmq (this is likely to be out of date pretty quickly).

The data is in the data zip file, the python notebook to read the pickles in the jupyter notebook folder.

Complete code to interpret the data and reproduce the plots in the paper can be found as part of Julia package at https://github.com/rharper2/Juqst.jl








