The tar archives and original sources codes for HDF5-1.8.9 
and MPICH2-1.4.1 are not stored here in order to keep the archive
files size reduced.

Please find the tar files in:

/backup/smsaleeb/AA.RAMS.code.tests/rams-hdf5-mpi-software

------------------------------------------------------------------
Note:

In January 2020, my Linux OS was upgraded to the latest version
of Debian at the time. This seems to use a different GLIBC 
version that required me to recompile HDF5 and MPICH2. This may
be an issue when using these precompiled binaries on remote
supercomputing systems such as NSF-Cheyenne, ONR-conrad,
DOE-stratus, NASA-pleiades, etc. As such, you can try compiling
RAMS with these precompiled binaries, but they may not work. Your
best bet is to use the HDF5 and MPICH2 or OPEN-MPI on the 
supercomputing system. Note that HDF5-1.8 is required as of 
beginning of 2020. At some point we will update RAMS to use
HDF5-1.10+ which requires RAMS code changes.

The code compiled "pre2020" used an older version of Debian prior
to 2020. The code compile "post2020" used a version of Debian
valid as of Janary 2020. These likely used different GLIBC versions.
