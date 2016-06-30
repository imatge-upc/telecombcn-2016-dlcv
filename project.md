---
layout: page
title: Project
permalink: /project
hide: true
---

## Project Coordinator

| ![AmaiaSalvador][AmaiaSalvador-photo]  |
|:-:|:-:|:-:|:-:|:-:|:-:|
| [Amaia Salvador (AS)][AmaiaSalvador-web] |

[AmaiaSalvador-web]: https://imatge.upc.edu/web/people/amaia-salvador
[AmaiaSalvador-photo]: img/instructors/AmaiaSalvador.jpg "Amaia Salvador"


## Introduction

Projects can be developed using any of the many available deep learning frameworks. However, we encourage you to use Keras,
which is easy to learn and get used to. Students can also choose whether to run their project experiments in the 
provided server (CPUs only), or to use your personal computers. 

## Server Access & Setup

The instructions for the access to the server will be provided to students by e-mail.

Once you are logged in the server, you will need to setup your working environment. The simplest way will be to use a 
[virtual environment](http://docs.python-guide.org/en/latest/dev/virtualenvs/) to install your dependencies. As an example, if you are working with keras:

```
dlcv@imatge-dlcv:~$ virtualenv keras-env
dlcv@imatge-dlcv:~$ source keras-env/bin/activate
(keras-env) dlcv@imatge-dlcv:~$ pip install theano
(keras-env) dlcv@imatge-dlcv:~$ pip install keras
```


## Installation in personal laptops

Here is a list of resources to install the project dependencies in your laptops:

* [Docker for Deep Learning](https://github.com/saiprashanths/dl-docker). It works for Linux, MacOSX and Windows. However, GPU support
is only available for the first two.
* [TensorFlow, CUDA, OpenCV Installation Guide](https://github.com/DrewNF/Build-Deep-Learning-Env-with-Tensorflow-Python-OpenCV) by
Teaching Assistant Andrea Ferri. Please use the issues section in his repository for any questions you may have about it.
