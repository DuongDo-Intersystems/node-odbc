# quickstarts-python
This code shows PyODBC, and the Native API access.     
Note that our code and supporting wheel files are designed for Python 3 because Python 2 will retire in 2020. If you want to use Python 2, please contact us for more details.

## Contents
* `pyodbcplaystocksTask7.py`: to see how to store and retrieve data relationally from InterSystems IRIS database.
* `nativeplaystocksTask6.py`: to see how to access directly the underlying structure within InterSystems IRIS.

## Configuration files
`connection.config`: contains connection details for PyODBC and Native API.

## Installation wheels
* `nativeAPI_wheel`: contains installation wheel for using Python with Native API.
*  `pyodbc_wheel`: contains installation wheel for using Python with PyODBC.

## How to run

Navigate to the *Solutions* directory: `cd /home/project/quickstarts-python/Solutions`

### Connect to InterSystems IRIS database via PyODBC

1. Install InterSystems IRIS pyodbc wheel: `odbcinst –i –d –f pyodbc_wheel/odbcinst.ini`
2. Run `python pyodbcplaystocksTask1.py`

### Connect to InterSystems IRIS database via the Native API

1. Install InterSystems IRIS Native API wheel: `pip install nativeAPI_wheel/irisnative-1.0.0-cp34-abi3-linux_x86_64.whl`
2. Run `python nativeplaystocksTask1.py`
