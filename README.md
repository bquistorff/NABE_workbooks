# NABE_workbooks
For use with Google Colab: `colab.research.google.com`.

I've had the notebooks download the zip files directly from GitHub, but users could upload those files themselves.

If you are trying to replicate on your own machine, the end section of the "Solutions" notebooks list the versions of key packages. This will be from the last run on Colab where this was tested. Colab, however, updates, that may cause issues. See the details of [Colab runtime versions](https://research.google.com/colaboratory/runtime-version-faq.html).

Custom package installations (not Colab runtime):
- `EconML==0.16.0` (latest)
- `dask_ml==2025.1.0` (latest) which only works well with `dask==2025.1.0` (not latest)
- `ratelimit` (doesn't change much)