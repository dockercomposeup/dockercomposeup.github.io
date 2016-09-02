---
layout: post
title: Intro to Apache Spark and Scala Notebooks
caption: Sample Scala Notebook that uses Apache Spark to analyze the Back to the Future transcript.
date: 2016-07-10 09:00:00 -0500
image: '/assets/img/'
main-class: 'spark'
tags:
- spark
- notebook
- jupyter
- scala
- python
gitrepo: https://github.com/markwatsonatx/tutorial-spark-notebook-wordcount-scala
gitfolder: tutorial-spark-notebook-wordcount-scala
---

In this sample I'll show you how to use Scala Notebooks and Apache Spark
to perform simple analysis on the Back to the Future transcript.

This tutorial uses a Docker Image that I created and can be found at:

[https://hub.docker.com/r/markwatsonatx/spark-notebook](https://hub.docker.com/r/markwatsonatx/spark-notebook)

The Docker Image contains Apache Spark 1.6.1 for Hadoop 2.6. It also includes Scala 2.10, Python 3.5,
[Anaconda](https://www.continuum.io/why-anaconda), and kernels for running Scala and Python [notebooks](http://jupyter.org/).

The Dockerfile can be found at:

[https://github.com/markwatsonatx/Dockerfiles/tree/master/spark-notebook-1.6.1](https://github.com/markwatsonatx/Dockerfiles/tree/master/spark-notebook-1.6.1)