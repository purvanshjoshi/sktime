.. _estimator_types_ref:

===============
Estimator types
===============

This section lists the various object types (scitypes) available in ``sktime``.

Each object type corresponds to a specific unified interface and base class.
Every object in ``sktime`` has one or more scitypes, which can be inspected
via its ``"object_type"`` tag.

.. currentmodule:: sktime.registry._base_classes

AI algorithms
-------------

.. autosummary::
    :toctree: auto_generated/
    :template: class.rst
    :nosignatures:

    aligner
    classifier
    clusterer
    detector
    forecaster
    param_est
    regressor
    transformer

Data handling
-------------

.. autosummary::
    :toctree: auto_generated/
    :template: class.rst
    :nosignatures:

    splitter
    dataset
    catalogue

Evaluation and metrics
----------------------

.. autosummary::
    :toctree: auto_generated/
    :template: class.rst
    :nosignatures:

    metric

General types
-------------

.. autosummary::
    :toctree: auto_generated/
    :template: class.rst
    :nosignatures:

    object
    estimator
