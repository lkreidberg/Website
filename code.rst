.. _code:

Code
====
batman
------
I developed the ``batman`` package for fast calculation of transit light curves in Python.   The package supports calculation of light curves for any radially symmetric stellar limb darkening law, using a new integration algorithm for models that cannot be quickly calculated analytically.

In typical use, batman can calculate a million model light curves in well under 10 minutes for any limb darkening profile.


For more info, check out the `docs <http://www.cfa.harvard.edu/~lkreidberg/batman>`_.


.. image:: batlogo.png
	:height: 100px

spiderman
---------
Tom Louden and I developed the ``spiderman`` package for modeling eclipses and phase curves. The code calculates the emitted and reflected light for any user-specified brightness distribution and planet properties. See the `documentation <http://spiderman.readthedocs.io/en/latest/>`_ or `paper <https://arxiv.org/abs/1711.00494/>`_ for more detail!

.. raw:: html 

   <video controls src="_static/SPIDERMAN_output.mp4"></video> 


