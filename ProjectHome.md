**gridgen** is a C code that provides a command line utility for non-interactive generation of multi-corner quasi-orthogonal grids inside simply connected polygonal regions.It is based on the [CRDT](http://gridgen-c.googlecode.com/files/grid_examples.pdf) algorithm that makes it possible to handle regions with elongated channels in a numerically robust way.

[Here](http://gridgen-c.googlecode.com/files/crdt.pdf) are example grids from the **gridgen** package. You can also find a number of grids generated with **gridgen** for operational estuarine, coastal and regional models at the project's [Downloads](http://code.google.com/p/gridgen-c/downloads/list) page.

Checkout **gridgen** by running "`svn  checkout https://gridgen-c.googlecode.com/svn/gridgen`".

Remember that **gridgen** is only a tool, and one needs quite a bit of skill to generate a particular grid. It used to take up to two weeks for me to generate a grid for an operational coastal or estuarine model (including testing a few candidates for stability and performance), but it is worth it.

If you are using **gridgen** you may also need [gridutils](http://code.google.com/p/gridutils-c) to work with the grids it produces.

There are a number of front-ends to **gridgen**. [Octant](http://code.google.com/p/octant/) by Rob Hetland is a python suite that provides interactive grid generation for ROMS and GETM.

[README](http://code.google.com/p/gridgen-c/source/browse/gridgen/README)
