# realtime_drop_landing_estimation

This project provides a modular LSTM-based model to estimate vGRF and KEM with werable IMUs in real-time during single- and double-leg drop landings 

## Getting started

To run develop.py to training the model and evaluate the model. The develop.py defines varied cofniguratons and setup of models

The IMU configurations and LSTM unit number can be setup in develop.py


- estimation_study.py has a train_test_loop, which is a rountine of training and testing of a model.
- estimation_assessement contains scripts for model evaluations, including calculate scores, exxcution_time, performance visualization etc.
- estimation_models contains the model definitions

