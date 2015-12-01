# sac-matlab
Read and write SAC seismic data file into Matlab.

rdsac.m reads a seismic data file encoded in the IRIS/SAC binary format, and returns a time vector, a data vector and all header variables in a structure (field names correspond to exact IRIS variable names).

mksac.m writes a seismic data file in the IRIS/SAC binary standard format, from any data vector, origin time, and header field that user wants to define.

See functions documentation for detailed syntax and examples.
