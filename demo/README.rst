Toga Demo
=========

A demonstration of the capabilities of the `Toga widget toolkit`_.

**Toga requires Python 3**

Quickstart
----------

For details of Toga's pre-requisites, see the `toga repository on GitHub`_.

Once those pre-requisites have been met, in your virtualenv, install Toga Demo,
and then run it::

    $ pip install toga-demo
    $ toga-demo

This will pop up a GUI window.

If you have cloned the toga repository, install the dependent packages in your virtualenv::

    $ cd toga
    $ pip install -e ./core

Then install the platform specific code::

    $ pip install -e ./cocoa      # macOS
    $ pip install -e ./gtk        # Linux
    $ pip install -e ./winforms   # Windows

Finally navigate to the demo directory and run the application::

    $ cd demo
    $ python -m toga_demo

Community
---------

Toga Demo is part of the `BeeWare suite`_. You can talk to the community through:

* `@pybeeware on Twitter`_

* The `beeware/general`_ channel on Gitter.

Contributing
------------

If you experience problems with Toga Demo, `log them on GitHub`_. If you
want to contribute code, please `fork the code`_ and `submit a pull request`_.

.. _BeeWare suite: http://beeware.org
.. _Read The Docs: http://toga-demo.readthedocs.org
.. _Toga widget toolkit: http://beeware.org/toga
.. _toga repository on GitHub: https://github.com/beeware/toga
.. _@pybeeware on Twitter: https://twitter.com/pybeeware
.. _beeware/general: https://gitter.im/beeware/general
.. _log them on Github: https://github.com/beeware/toga/issues
.. _fork the code: https://github.com/beeware/toga
.. _submit a pull request: https://github.com/beeware/toga/pulls
