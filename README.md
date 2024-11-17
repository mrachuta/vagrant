## Project name

Collection of Vagrant configurations

## Table of contents
- [Project name](#project-name)
- [Table of contents](#table-of-contents)
- [General info](#general-info)
- [kubernetes](#kubernetes)

## General info

Repo contains Vagrant configurations to spin up VM's for various purposes using Virtualbox.
Make sure you have Virtualbox installed before you will be trying to use these configurations.
Each configuration is assuming that you haven't changed Virtualbox's default network configuration (IP addresses etc.)

## kubernetes

Vagrant configuration to run VM instances that can be used to create kubernetes cluster for training purposes. Features:
- externalized & parametrized configuration,
- exposed ports for ingress,
- support for custom SSH keys.

Before provisioning, create your own *config.yaml* file based on shipped example.