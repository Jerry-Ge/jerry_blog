Sphnix Cheetsheet
=================

I use Sphnix a lot to write stuff, here're some of my commonly used stuff

Reference: https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html

Header Hierarchy 
-------------------

::
    
    ================
    Top-Level Title
    ================

    Second Level
    ------------

    Third Level
    ~~~~~~~~~~~

    Fourth Level
    ^^^^^^^^^^^^

    Fifth Level
    """""""""""

Link URLs
-------------------

::
    
    # Inline link
    `Google <https://google.com>`_
    
    # Anonymous link
    `Google <https://goole.com>`__


Code Block 
-------------------

::
    
    .. code-block:: python

    def hello():
        print("Hello, world!")