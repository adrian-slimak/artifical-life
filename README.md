# Master thesis repository

**Thesis name: 
Forming herd behaviour by virtual agents using deep neural networks**

**Thesis abstract:**
A review of the literature on the evolution of artificial life herd behaviour has shown that
existing research focuses mainly on the pressure exerted by the presence of a predator and the
creation of herds by prey in response to different forms of attacks. However, there is a lack of
research that would address more broadly such key issues in nature as the need for prey to feed or
communication among predators, that could allow breaking through the form of prey defense
that is a herd.
This work fills this gap. For this purpose, a virtual environment has been constructed, which
contains the necessary mechanisms and models a selected fragment of nature to the extent
required for research. The environment is inhabited by agents, that is, artificial animals, which
are controlled by a driver based on a recurrent neural network RNN or LSTM. Based on the
observations received from the environment by the senses and their memory state, the driver
decides to change the position of the agent or to release a sound.
In this thesis, a comparison was made of the type of controller used in the research on the
formation of herd behaviour among agents, living under the pressure of predator attacks and the
need to search for food, as well as the impact of the communication mechanism present in both
preys and predators.

## Description
This repository contains source code for the master thesis.

## How to run

First you have to build virtual environment (written in C++) as a python site-package.
Navigate to "Python/setup", then run:

    python setup.py install

Once installation is complete, you can run simulation and learning process with:

    python EnvRun.py

In order to change the environment and learning parameters, edit *"config.json"* or *"Python/learning_parameters.py"* respectively.
