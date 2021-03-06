LinvPy is a Python package designed to solve linear inverse problems of the form y=Ax+n, where y is a vector of measured values, A a known matrix, x an unknown input vector and n is noise. The goal is to find x, or at least the best possible estimation; if the matrix A is invertible, the solution is easy to find by multiplying by the inverse. If A is not invertible, we need to use regression techniques such as least squares method to find x. The first motivation for this project is that Marta Martinez-Camara, PhD student in Communications Systems at EPFL (Switzerland) desgined some new algorithms to solve linear inverse problems (namely the Tau-Estimator), and this package is a Python implementation of these algorithms, which may not be available anywhere else than here. LinvPy also contains several other famous but not implemented or not publicly distributed algorithms such as regularization functions, loss functions or M-estimator.

To install from pip, simply run :
$ sudo pip install linvpy

PyPi link : https://pypi.python.org/pypi/linvpy

ReadTheDocs link : http://linvpy.readthedocs.org/en/latest/