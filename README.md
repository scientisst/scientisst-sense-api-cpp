# scientisst-sense-api-cpp
The ScientISST SENSE C++ API

## Repository structure

```
- ext
  - rapidjson       : A json library
- src
  - main.cpp        : A test example source file that uses the scientisst class to perform a live mode acquisition
  - scientisst.cpp  : The scientisst class source file
```
## Dependencies

### Linux
- libbluetooth-dev

## Installing
```sh
# Getting this repository 
git clone https://github.com/scientisst/scientisst-sense-api-cpp.git --recursive
```

## Running (Linux/MacOS)
```sh
cd scientisst-sense-api-cpp
# Example usage
./scientisst E8:9F:6D:D2:1F:5E output.csv
```
