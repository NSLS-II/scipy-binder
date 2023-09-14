# Scientific Python Binder for NSLS-II

This defines the container image run on https://jupyter.nsls2.bnl.gov.

Note that this only includes the Jupyter _server_ environment, which includes
various Jupyter server extensions. It does not include the Jupyter _kernels_
where the user code is executed. Those are managed separately in
[nsls2-conda-envs/nsls2-collection-tiled](https://github.com/nsls2-conda-envs/nsls2-collection-tiled)
and mounted into the container under `/nsls2/conda/`.
