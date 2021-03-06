.. _api:

Developer Interface
===================

.. module:: twosheds

This part of the documentation covers all the interfaces of twosheds.

Main Interface
--------------

All of twoshed's functionality can be accessed by an instance of the :class:`Shell <Shell>` object.

.. autoclass:: twosheds.Shell
   :inherited-members:

Command Language
----------------

.. autoclass:: twosheds.language.Language
   :inherited-members:

.. autoclass:: twosheds.grammar.Grammar
   :inherited-members:

.. autoclass:: twosheds.semantics.Semantics
   :inherited-members:

.. automodule:: twosheds.transform
   :members:

Completion
----------

.. autoclass:: twosheds.completer.Completer
   :inherited-members:
