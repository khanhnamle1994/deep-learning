## Installation and setup

Since the datasets are loaded in memory, 4 GB of RAM are short to run the notebooks, 8 GB will be more comfortable. The instructions are given for Mac OS, but it works on Linux as well.

I recommend to install the Python bundle [Anaconda](https://www.anaconda.com/). All the assignments have been done with Python 2.7, so download the installation script accordingly. You can then install [Jupyter Notebook](http://jupyter.org/) from ``conda``.

The next step is to install TensorFlow. At the time of writing, the latest release is r0.9, after several upgrades during the course. You can refer to the [official documentation](https://www.tensorflow.org/install/#anaconda-installation). Here is the list of commands:

```
$ conda create -n tensorflow python=2.7
$ source activate tensorflow
(tensorflow)$ export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/mac/tensorflow-0.9.0-py2-none-any.whl
(tensorflow)$ pip install --upgrade --ignore-installed $TF_BINARY_URL
```

You can now grab the assignments from here to run my code or the stubs from the [TensorFlow repository](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/udacity). All the other prerequisites (like ``numpy``) have to be installed on the fly.

## Quick start

From the repository root, start the Notebook server with ``jupyter notebook``.
