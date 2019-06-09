# EarthquakeLALNPrediction
This repository contains code submitted to Kaggle for the EartquakeLALNPrediction Challenge.
Challenge Link : https://www.kaggle.com/c/LANL-Earthquake-Prediction

The data are from an experiment conducted on rock in a double direct shear geometry subjected to bi-axial loading, a classic laboratory earthquake model (fig. a)

Two fault gouge layers are sheared simultaneously while subjected to a constant normal load and a prescribed shear velocity. The laboratory faults fail in repetitive cycles of stick and slip that is meant to mimic the cycle of loading and failure on tectonic faults. While the experiment is considerably simpler than a fault in Earth, it shares many physical characteristics. (fig. b)

Los Alamos' initial work showed that the prediction of laboratory earthquakes from continuous seismic data is possible in the case of quasi-periodic laboratory seismic cycles. In this competition, the team has provided a much more challenging dataset with considerably more aperiodic earthquake failures.

To solve this challenge i generated a set of features and used that in XGBosstRegressor.
