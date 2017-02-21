lambdaOJ2
=========

lambdaOJ2 is the platform for the course **Data Structure** in EE of Thu.


## INSTALL

### Compile

```bash
cd lambdaOJ2
mkdir build; cd build
cmake -DCMAKE_INSTALL_PREFIX=/your/path/to/install/
make
make install
```

### Install Python3 API

Make sure:

* `liblambdaOJ2.so` is in `$LD_LIBRARY_PATH`
* `judge` is in `$PATH`

```bash
cd lambdaOJ2/python_package
python3 setup.py install --prefix=/your/path/to/install/
```

Or use pip:

```bash
pip install "git+https://github.com/kainwen/lambdaOJ2@master#egg=lambdaOJ2&subdirectory=python_package"
```

### Docs

Docs can be found [here](doc/lambdaOJ2.md).
