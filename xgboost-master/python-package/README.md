XGBoost Python Package
======================
* To make the python module, type ```./build.sh``` in the root directory of project
* Make sure you have [setuptools](https://pypi.python.org/pypi/setuptools)
* Install with `python setup.py install` from this directory.
* Refer also to the walk through example in [demo folder](../demo/guide-python)
* **NOTE**: if you want to run XGBoost process in parallel using the fork backend for joblib/multiprocessing, you must build XGBoost without support for OpenMP by `make no_omp=1`. Otherwise, use the forkserver (in Python 3.4) or spawn backend. See the sklearn_parallel.py demo.
