# MA-PRALINE extras

Analysis notebooks and other support code used in the MA-PRALINE article. This code is provided as-is; we don't
provide any support for it, but you may find it helpful if you want to reparametrise (MA-)PRALINE for another kind
of motif annotation, for example.

`benchmark` contains the Jupyter analysis notebooks used when compiling the 'SP score versus motif score' benchmark.
`homstrad` contains the Jupyter notebooks used in the generation of the 'alpha star' statistics and figure.

## Dependencies

To get the code to run, at least a couple of dependencies need to installed:
* Python 2.7
* Jupyter
* BioPython
* MA-PRALINE and PRALINE
* Matplotlib
* Probably something else I've forgotten. If Python gives import errors, there's likely another missing dependency. :-)

Additionally, some database files need to be downloaded and provided:
* BAliBASE 4 (http://www.lbgi.fr/balibase/)
* HOMSTRAD (http://mizuguchilab.org/homstrad/)
* PROSITE (https://prosite.expasy.org/)
