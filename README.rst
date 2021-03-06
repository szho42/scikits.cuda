.. -*- rst -*-

CUDA SciKit
===========

Package Description
-------------------

This SciKit (toolkit for SciPy [1]_) provides Python interfaces to a
subset of the functions in the CUDA, CUDART, CUBLAS, and CUFFT
libraries distributed as part of NVIDIA's CUDA Programming Toolkit
[2]_, as well as interfaces to select functions in the basic and
premium versions of the CULA Toolkit [3]_. In contrast to most
existing Python wrappers for these libraries (many of which only
provide a low-level interface to the actual library functions), this
package uses PyCUDA [4]_ to provide high-level functions comparable to
those in the NumPy package [5]_.

Authors & Acknowledgments
-------------------------

This software was written and packaged by Lev Givon, currently at the
Bionet Group [6]_ at Columbia University. 
See the included AUTHORS file for more information and
acknowledgments.

License
-------

This software is licensed under the 
`BSD License <http://www.opensource.org/licenses/bsd-license.php>`_.
See the included LICENSE file for more information.

Contact Information
-------------------

Please direct all questions and comments pertaining to this software to

`Lev Givon <lev@columbia.edu>`_

.. [1] http://www.scipy.org/
.. [2] http://www.nvidia.com/cuda
.. [3] http://www.culatools.com/
.. [4] http://mathema.tician.de/software/pycuda/
.. [5] http://numpy.scipy.org/
.. [6] http://bionet.ee.columbia.edu/
