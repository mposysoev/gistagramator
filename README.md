# Gistogramator

Simple tool for making histograms written in Python. Accepts data in the format:

```console
123
345
123
567
435
234
...
```

It uses numpy.loadtxt function for reading data.

Dependencies: numpy, matplotlib.

## Usage

```console
python3 gistagramator

USAGE:
    python3 gistagramator <type> <bins> <file_name> 
    <type>: hist or scatter
    <bins>: int number
    <file_name>: file name
```
