MLFlow Sandbox [![travis-badge][]][travis]
=======

[travis]:                https://travis-ci.org/mycaule/mlflow-sandbox
[travis-badge]:          https://travis-ci.org/mycaule/mlflow-sandbox.svg?branch=master

This repository is for tests and learning the framework.

### Pre-Requisites

The followings are recommended:
- Python 2.7

### Usage

```sh
# Compile sources and test files
$ pip install -r requirements.txt
# Train the models
$ python train.py
$ python train.py <alpha> <l1_ratio>
$ mlfow ui


$ mlflow sklearn serve mlruns/0/<run_id>/artifacts/model -p 1234
```

### Getting started

The example was extracted from [`mlflow/example`](https://github.com/mlflow/mlflow/tree/master/example).

### Roadmap

- [ ]

### References

* [MLFlow Documentation](https://www.mlflow.org/docs/latest/tutorial.html)
