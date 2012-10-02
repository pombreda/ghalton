Generalized Halton Number Generator
===================================

This library allows to generate quasi-random numbers according to the
generalized Halton sequence. For more information on Generalized Halton
Sequences, their properties and limits, see Braaten and Weller [1979], Faure
and Lemieux [2009], and De Rainville et al. [2012] and reference therein.


Building The Code
-----------------
To build the code you'll need a working C++ compiler. 

    $ python setup.py install


Using the Library
-----------------
The library contains two generators one producing the standard Halton sequence
and the other a generalized version of it. The former constructor takes a single argument,
which is the dimensionalty of the sequence. 

    import ghalton
    sequencer = ghalton.Halton(5)

The last code will produce a sequence in five dimension. To get the points

    



References
----------
E. Braaten and G. Weller. An improved low-discrepancy sequence for multidi- mensional quasi-Monte Carlo integration. *J. of Comput. Phys.*, 33(2):249-258, 1979.

H. Faure and C. Lemieux. Generalized Halton sequences in 2008: A comparative study. *ACM Trans. Model. Comput. Simul.*, 19(4):1-43, 2009.

F.-M. De Rainville, C. Gagné, O. Teytaud, D. Laurendeau. Evolutionary optimization of low-discrepancy sequences. *ACM Trans. Model. Comput. Simul.*, 22(2):1-25, 2012.
  