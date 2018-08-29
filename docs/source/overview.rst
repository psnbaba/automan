Overview
==========

``automan`` is an open source, Python-based automation framework for numerical
computing.

It is designed to automate the drudge work of managing many numerical
simulations. As an automation framework it does the following:

- helps you organize your simulations.
- helps you orchestrate running simulations and then post-processing the
  results from these.
- helps you reuse code for the post processing of your simulation data.
- execute all your simulations and post-processing with one command.
- optionally distribute your simulations among other computers on your
  network.

This greatly facilitates reproducibility. Automan is written in pure Python
and is easy to install.

This document should help you use automan to improve your productivity. If you
are interested in a more detailed article about automan see here:
https://arxiv.org/abs/1712.04786


Installation
-------------

The easiest way to install ``automan`` is with pip_::

   $ pip install automan

If you wish to run the latest version that has not been relesed you may clone
the git repository::

  $ git clone https://github.com/pypr/automan

  $ cd automan

And then run::

  $ python setup.py develop

.. _pip: https://pip.pypa.io/en/stable/


Once this is done, move on to the next section that provides a gentle tutorial
introduction to using automan.


Citing ``automan``
-------------------

If you find automan useful and wish to cite it you may use the following
article:

- Prabhu Ramachandran, "automan: a Python-based Automation Framework for
  Numerical Computing", *IEEE Computing in Science and Engineering*,
  Accepted, 2018.

You can find a draft of the article here: https://arxiv.org/abs/1712.04786