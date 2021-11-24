# TensorFlow lessons
[![codecov](https://codecov.io/gh/nepito/tf_lessons/branch/main/graph/badge.svg)](https://codecov.io/gh/nepito/tf_lessons)
[![PyPI Version](https://img.shields.io/pypi/v/tf_lessons)](https://pypi.org/project/tf_lessons/)
![example branch parameter](https://github.com/nepito/tf_lessons/actions/workflows/build.yml/badge.svg)
![example branch parameter](https://github.com/nepito/tf_lessons/actions/workflows/actions.yml/badge.svg)

This is the lesson of Machine Learning from this
[video](https://www.youtube.com/watch?v=_Z9TRANg4c0).

We fit a model using a neural network. The data came from the linear model 2 _x_ - 1.

To install
```bash
pip install tf_lessons
```

To run the example
```python
import tf_lessons as tfl
neuron = tfl.Neuron()
prediction = neuron.predict([10.0])
```
The prediction will be around 19.0

---
 ## Run with jupyterlab

Desde afuera:

 ```bash
 make build_demo
 make run_demo
 ```
 

