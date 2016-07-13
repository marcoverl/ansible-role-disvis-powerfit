docker-powerfit
===============

Dockerfile to run powerfit on CPUs or GPUs


Introduction
------------

The image is built from the ansible-role of the following github repository:
* https://github.com/indigo-dc/ansible-role-disvis-powerfit

The NVIDIA driver version of the image has to match the one on the physical
machine. The ansible-role repository shows the version with which the current
image is built.

The ansible-role has a variable which is the NVDIDIA driver, as such if you
have a different version you will have to can run the ansible-role specifying
the correct version.
