Changelog
=========

Version 1.1.0
-------------

New Methods
~~~~~~~~~~~

* New decorator :class:`wyrm.misc.deprecated` that is used internally for
  marking methods as deprecated

Version 1.0.0
-------------

We bumped the version up to 1 without backwards-incompatible changes since the
last version.

New Methods
~~~~~~~~~~~

* New method :meth:`wyrm.processing.rereference` for rereferencing channels
* New method :meth:`wyrm.processing.calculate_whitening_matrix`

Improvements
~~~~~~~~~~~~

* :meth:`wyrm.plot.plot_channels` is now able to plot continuous and epoched
  data
* :meth:`wyrm.plot.plot_channels` allows for configuring the number of columns
  of the grid

Misc
~~~~

* Upgraded to Sphinx 1.3.1
* We use napoleon instead of the numpydoc plugin
* Several fixes for various docstring issues
