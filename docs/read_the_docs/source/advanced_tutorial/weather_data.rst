Weather Data
##############

The weather files can be found in the folder: `weather data <https://nrel.app.box.com/folder/108861105291>`_ . This folder contains TMY, and AMY 2012 through AMY 2017 weather file information. 


Weather Locations
=================


 - :ref:`Could not find parameter and option <could-not-find-parameter-and-option>`
 - :ref:`Required argument not provided <required-argument-not-provided>`

Once you have updated your ``options_lookup.tsv`` file and all integrity checks are passing, you can move on to :doc:`updating_projects`.

.. _could-not-find-parameter-and-option:

Could not find parameter and option
===================================

You do not have a row in ``options_lookup.tsv`` for a particular option that is sampled.

An example of this error is given below:

.. image:: ../images/advanced_tutorial/could_not_find_parameter_and_option.png

.. _required-argument-not-provided:

Required argument not provided
==============================

For the particular option that is sampled, your corresponding measure is missing an argument value assignment.

An example of this error is given below:

.. image:: ../images/advanced_tutorial/required_argument_not_provided.png
