.. _TestUdPowerCycle:

TestUdPowerCycle
***********************************

Wrapper for SAM Simulation Core model: `cmod_test_ud_power_cycle.cpp <https://github.com/NREL/ssc/blob/develop/ssc/cmod_test_ud_power_cycle.cpp>`_

Input Consistency Warning
==================================

As described in :ref:`Possible Problems <possible_problems>`, some input parameters are interdependent but the equations 
that enforce consistency are not available in this PySAM module. Therefore,
the onus is on the PySAM user to check that interdependencies are correctly handled. The variables which may require
additional logic include:


Provided for each of these inputs is a list of other inputs that are potentially interdependent. 

Creating an Instance
===================================

Refer to the :ref:`Initializing a Model <initializing>` page for details on the different ways to create an instance of a PySAM class.

**TestUdPowerCycle model description**

.. automodule:: PySAM.TestUdPowerCycle
	:members:

Functions
===================================

.. autoclass:: PySAM.TestUdPowerCycle.TestUdPowerCycle
	:members:

Common Group
======================================================

.. autoclass:: PySAM.TestUdPowerCycle.TestUdPowerCycle.Common
	:members:

Outputs Group
======================================================

.. autoclass:: PySAM.TestUdPowerCycle.TestUdPowerCycle.Outputs
	:members:

