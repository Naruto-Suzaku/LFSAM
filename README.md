# LFSAM
## package dependence：<br>
scipy<br>
numpy<br>
h5py<br>
healpy<br>
NE2001(Fortran Code needs to be compiled with python) or pyne2001
## used:
go to the dir ./LFSAM/absorption_NE2001/constant_index_minus_I_E/seiffert_test/, and run: <br>
mpiexec -n N python global_spectrum_new.py <br>
the output data will be saved in ./output
