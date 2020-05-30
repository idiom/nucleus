




Clone of Nucleus function detector.
Source: https://bitbucket.org/vusec/nucleus/src/master/


Based on the paper "Compiler-Agnostic Function Detection in Binaries",
published at EuroS&P 2017.

# Requirements:
  - libcapstone (tested with 3.0)
  - libbfd-multiarch

# Platform:
  - Tested on Ubuntu 15.10 and 16.04
  On these platforms you can install the required libraries by executing:
    make setup

# Suggested usage:
  make
  ./nucleus -e /bin/ls -d linear -i idainfo.py
  (idainfo.py can be run in IDA Pro to import the functions found by nucleus)
