# Getting Started with JOOMMF

The JOOMMF project is working towards a system that allows to run,
postprocess and analyse micromagnetic simulations within the Jupyter
Notebook.

At the moment (late 2016), we have a beta prototype of a Python
interface to OOMMF. This interface is called OOMMFC. The C stands for
Calculater: we use OOMMF as a micromagnetic calculator: the actual
micromagnetic computation is done by OOMMF, and the OOMMFC python
module provides a high level interface to this.

## Installation overview

To use OOMMFC, you need a working installation of OOMMF. This can
either be compiled on the computer. Or you can use a 'Docker
installation' of OOMMF.

In addition to that, you need to install the OOMMFC package itself,
which is written in Python (and thus you need a Python distribution
installed).

The best starting point are the installation instructions that are
part of the [OOMMF Documentation](http://oommfc.readthedocs.io).




