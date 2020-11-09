
# rdkit-chem gem

GEM for [RDKIT](http://rdkit.org/), an Open-Source Cheminformatics Software

## Environment

### Prerequisites
  * cmake 3.8 or later
  * curl
  * tar, sed, make (those should be present anyway)
  * SWIG 2 or later
  * python header (`python-dev`)
  * sqlite (`sqlite3-dev`)
  * boost > 1.58 (`libboost-all-dev`)
  * gcc -  **no later than 9.3.0, current code does not work with gcc-10**

For MacOS

```
brew install gcc@9
export CC=/usr/local/bin/gcc-9
```

## Install
gem install openbabel

It downloads the sources, compiles and installs RDKIT with the ruby bindings.
The installation may last very long - please be patient.

