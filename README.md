# Memory Dump Cheatsheet

## Table Of Content
  * [Installing Volatility 2](#installing-volatility-2)
  * [Volatility Cheatsheet](#volatility-cheatsheet)


## Installing Volatility 2
1. `$ git clone https://github.com/volatilityfoundation/volatility.git`
2. `$ python2 setup.py`

## Volatility Cheatsheet
1. Process Information
```
python2 pslist -f /dump_file/
```
```
python2 psscan -f /dump_file/
```
