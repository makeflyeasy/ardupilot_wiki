.. _common-powermodule-landingpage:

====================================
Battery Monitors (aka Power Modules)
====================================

.. image:: ../../../images/PowerModule_landingpage.jpg

The links below have information about the most commonly used power modules

.. note:: In firmware versions 4.0 and later, up to 10 batteries can be monitored. In addition, a new battery "type" = SUM, that consolidates all following (higher numbered) battery monitors into a single report, has been added to each monitor.

.. toctree::
    :maxdepth: 1

    Common Power Module <common-3dr-power-module>
    AirbotPower Power Module <common-airbotpower-power-module>
    Mauch Power Modules <common-mauch-power-modules>
    Power Module Configuration <common-power-module-configuration-in-mission-planner>
    Smart Batteries <common-smart-battery>
    Fuel Monitors <common-fuel-sensors>

Power modules provide these benefits:

- Provides a stable power supply to the flight controller and reduces the chance of a brown-out
- Allows real-time monitoring of the battery’s voltage and current and triggering a low battery failsafe
- Allows compensating for the interference on the compass from the motors using the COMPASS_MOT_x and COMPASS_PMOT_x parameters, see :ref:`common-compass-setup-advanced` .
