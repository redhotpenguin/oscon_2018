## Comprehensive container based service monitoring with Kubernetes and Istio

### Overview

To get the most out of this tutorial, you should have access to an environment with the [Go programming language](https://golang.org/) installed, and the [R statistical computing language](https://www.r-project.org/about.html) installed. You should have Docker installed on your laptop, and install the [Jupyter Notebook](http://jupyter.readthedocs.io/en/latest/).

You will want to have access to a Kubernetes environment also. Google Cloud Platform offers a free [Kubernetes Engine](https://cloud.google.com/kubernetes-engine/docs/) trial that you can use for this tutorial.

The [goals of this tutorial](/#tutorial-exercises) are to:
* Get [Istio](https://istio.io) installed
* Send requests to a sample application
* Use the Istio Grafana dashboard
* Create the example metrics adapter
* Generate a statistical distribution of request latency data using R and Istio telemetry
* Use the Jupyter notebook to analyze request latency data with histograms

### K8s Resources
* [Docker for Mac with Kubernetes](https://blog.docker.com/2018/01/docker-mac-kubernetes/)
* [Minikube](https://kubernetes.io/docs/tasks/tools/install-minikube/) 
* [Google Kubernetes Engine](https://cloud.google.com/kubernetes-engine/docs/)
* [Google Cloud SDK](https://cloud.google.com/sdk/install)

### Istio Resources
* [Project homepage](https://istio.io)
* [Github](https://github.com/istio)
* [Users mailing list](https://groups.google.com/forum/#!forum/istio-users)
* [Community Links](https://istio.io/community/)
* [Istio Setup](https://istio.io/docs/setup/)
* [Bookinfo Sample Application](https://istio.io/docs/guides/bookinfo/)
* [Developer Guide](https://github.com/istio/istio/wiki/Dev-Guide)
* [Compiled in Adapter Walkthrough](https://github.com/istio/istio/wiki/Mixer-Adapter-Walkthrough)
* [gRPC Adapter Walkthrough](https://github.com/istio/istio/wiki/gRPC-Adapter-Walkthrough)
* [Mixer Using a Custom Adapter](https://github.com/istio/istio/wiki/Mixer-Using-a-Custom-Adapter)
* [Protoc (Google Protocol Buffers) binaries](https://github.com/google/protobuf/releases/tag/v3.4.0)

### Histogram Resources
* [How to Make a Histogram with Basic R](https://www.r-bloggers.com/how-to-make-a-histogram-with-basic-r/)
* [R Tutorial](http://www.r-tutor.com/)
* [Log linear histogram Go library](https://github.com/circonus-labs/circonusllhist)
* [Jupyter Notebook](http://jupyter.readthedocs.io/en/latest/)
* [Data Science for Effective Operations](https://github.com/HeinrichHartmann/DS4OPS)


### Tutorial Exercises

[Exercise 1 - Setup Istio](./exercises/1.md)

[Exercise 2 - Bookinfo Sample Application](./exercises/2.md)

[Exercise 3 - Create a metrics adapter](./exercises/3.md)

[Exercise 4 - Use R to plot a simple histogram of latency data](./exercises/4.md)

[Exercise 5 - Use the Jupyter notebook to analyze latency data](./exercises/5.md)


