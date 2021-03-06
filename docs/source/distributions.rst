.. role:: hidden
    :class: hidden-section

pixyz.distributions (Distribution API)
======================================

.. automodule:: pixyz.distributions
.. currentmodule:: pixyz.distributions

Distribution
---------------------

.. currentmodule:: pixyz.distributions.distributions
.. autoclass:: Distribution
    :members:
    :undoc-members:

Exponential families
---------------------

.. currentmodule:: pixyz.distributions

Normal
~~~~~~~~~~~~~~~~~~~~~~~~~~
       
.. autoclass:: Normal
    :members:
    :undoc-members:

Bernoulli
~~~~~~~~~~~~~~~~~~~~~~~~~~
       
.. autoclass:: Bernoulli
    :members:
    :undoc-members:

RelaxedBernoulli
~~~~~~~~~~~~~~~~~~~~~~~~~~
       
.. autoclass:: RelaxedBernoulli
    :members:
    :undoc-members:

FactorizedBernoulli
~~~~~~~~~~~~~~~~~~~~~~~~~~
       
.. autoclass:: FactorizedBernoulli
    :members:
    :undoc-members:

Categorical
~~~~~~~~~~~~~~~~~~~~~~~~~~
       
.. autoclass:: Categorical
    :members:
    :undoc-members:

RelaxedCategorical
~~~~~~~~~~~~~~~~~~~~~~~~~~
       
.. autoclass:: RelaxedCategorical
    :members:
    :undoc-members:

Special distributions
---------------------

NormalPoE
~~~~~~~~~~~~~~~~~~~~~~~~~~

.. autoclass:: NormalPoE
    :members:
    :undoc-members:

Deterministic
~~~~~~~~~~~~~~~~~~~~~~~~~~

.. autoclass:: Deterministic
    :members:
    :undoc-members:

DataDistribution
~~~~~~~~~~~~~~~~~~~~~~~~~~

.. autoclass:: DataDistribution
    :members:
    :undoc-members:

CustomLikelihoodDistribution
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. autoclass:: CustomLikelihoodDistribution
    :members:
    :undoc-members:

Flow-based
------------------------


PlanarFlow
~~~~~~~~~~~~~~~~~~~~~~~~~~
       
.. autoclass:: PlanarFlow
    :members:
    :undoc-members:


RealNVP
~~~~~~~~~~~~~~~~~~~~~~~~~~
       
.. autoclass:: RealNVP
    :members:
    :undoc-members:

Operators
-------------------------------------

ReplaceVarDistribution
~~~~~~~~~~~~~~~~~~~~~~~~~~

.. currentmodule:: pixyz.distributions.distributions
.. autoclass:: ReplaceVarDistribution
    :members:
    :undoc-members:

MarginalizeVarDistribution
~~~~~~~~~~~~~~~~~~~~~~~~~~

.. autoclass:: MarginalizeVarDistribution
    :members:
    :undoc-members:

MultiplyDistribution
~~~~~~~~~~~~~~~~~~~~~~~~~~

.. autoclass:: MultiplyDistribution
    :members:
    :undoc-members:

Functions
------------------------

.. currentmodule:: pixyz.distributions.distributions
.. autofunction:: sum_samples

