Introduction to katdal
======================

Data access library for data sets in the MeerKAT Visibility Format (MVF)

Overview
--------

This module serves as a data access library to interact with the chunk stores
and HDF5 files produced by the MeerKAT radio telescope and its predecessors
(KAT-7 and Fringe Finder). It uses memory carefully, allowing data sets to be
inspected and partially loaded into memory. Data sets may be concatenated and
split via a flexible selection mechanism. In addition, it provides a script to
convert these data sets to CASA MeasurementSets.