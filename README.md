# TF Vision Lab

This project is simply an extension of the Tensoflow Models repo, adding a package called 'experiments, in the research folder.

In there there are features designed to allow easy experimental runs. The results to which get traked using Sacred. A seperate open project, for experiment tracking.

This project is really just the glue to bind these two projects together in an accessible way. 

## Recommended quick start:

* If you haven't already, install Tensorflow 1.4 or above with GPU support for a compatible GPU
* Clone this repo
* `# From tensorflow/models/research/
protoc object_detection/protos/*.proto --python_out=.`
* `# From tensorflow/models/research/
export PYTHONPATH=$PYTHONPATH:`pwd`:`pwd`/slim`


# TensorFlow Models

This repository contains a number of different models implemented in [TensorFlow](https://www.tensorflow.org):

The [official models](official) are a collection of example models that use TensorFlow's high-level APIs. They are intended to be well-maintained, tested, and kept up to date with the latest stable TensorFlow API. They should also be reasonably optimized for fast performance while still being easy to read. We especially recommend newer TensorFlow users to start here.

The [research models](https://github.com/tensorflow/models/tree/master/research) are a large collection of models implemented in TensorFlow by researchers. They are not officially supported or available in release branches; it is up to the individual researchers to maintain the models and/or provide support on issues and pull requests.

The [samples folder](samples) contains code snippets and smaller models that demonstrate features of TensorFlow, including code presented in various blog posts.

The [tutorials folder](tutorials) is a collection of models described in the [TensorFlow tutorials](https://www.tensorflow.org/tutorials/).
