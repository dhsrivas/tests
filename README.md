
### AMD EPYC Linux Validation Exerciser Suite
AMD EPYC Linux Validation Exerciser Suite (ELVES) is a Linux Kernel test suite runs on AMD EPYC
servers. It is a work in progress test project created and maintained by AMD Linux test validation
team.

The purpose is to host AMD EPYC IP specific test cases that can run on upstream Linux kernel. This
test repository will include AMD EPYC IP specific feature tests like IOMMU, RAS, PQOS. In addition,
it adds details on how each of the features can be used or validated on AMD EPYC servers.

This repository contains a wrapper script and configuration files to allow the user to set up the 
Avocado Test Framework and run a suite of tests to help verify the Baremetal OS and 
Guest Virtual Machine (VM) IP specific testcases on the listed AMD EPYC Platforms.

### Steps to run

WIP


### Note:
Tests should be run with the supervisor permission (ex: root user).

### Tested Linux Distributions Version
- Ubuntu 24.04.2 LTS (Noble Numbat)

### Tested Hardware
- Genoa(1P) - AMD EPYC 9654 96-Core Processor
- Turin(2P) - AMD EPYC 9555 64-Core Processor

### Tested Kernel
- Upstream stable kernel - version string: v6.14.5

### Avocado LTS Version
- Avocado 103.0

### Credits:
This project is a fork of https://github.com/lop-devops/tests, and we are sincerely grateful to 
the original authors for their foundational work and valuable contributions. 
We have tailored this project to meet our specific needs, introducing customizations to support 
our use case. Our goal is to maintain compatibility with the original project and contribute 
back to it as opportunities arise in the future.

