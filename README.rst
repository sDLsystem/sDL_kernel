A Jupyter kernel for sDL client

This requires IPython 3.

To install::

    pip install sDL_kernel
    python -m sDL_kernel.install

To use it, run one of:

.. code:: sDL

    jupyter notebook
    # In the notebook interface, select Bash from the 'New' menu
    jupyter qtconsole --kernel sDL
    jupyter console --kernel sDL

For details of how this works, see the Jupyter docs on `wrapper kernels
<http://jupyter-client.readthedocs.org/en/latest/wrapperkernels.html>`_, and
Pexpect's docs on the `replwrap module
<http://pexpect.readthedocs.org/en/latest/api/replwrap.html>`_
