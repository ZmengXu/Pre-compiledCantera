# Pre-compiledCantera
> The pre-compiled Cantera library (C/C++ Interface) and include file. This is compi
led using gcc 5.4.0 and shows forward compatibility (better than the libcantera-deve
l in conda). It can be used for OpenFOAM+Cantera.

## download the lib
```
git clone https://github.com/ZmengXu/Pre-compiledCantera.git
cd Pre-compiledCantera
```

## switch to specific version, e.g., v2.6.0
```
git checkout v2.6.0
tar -zxvf cantera_build.tar.gz
```

## Add the lib path to system
```
export CANTERA_ROOT=$PWD/cantera_build
export CANTERA_DATA=$CANTERA_ROOT/data
export LD_LIBRARY_PATH=$CANTERA_ROOT/lib:$LD_LIBRARY_PATH
```

