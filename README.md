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
python2 vol.py pslist -f /dump_file/
```
```
python2 vol.py psscan -f /dump_file/
```
```
python2 vol.py pstree -f /dump_file/
```
2. Process Dump
```
python2 vol.py -f /dump_file/ procdump ---dump-dir /directory
```
3. DLLs
```
python2 vol.py -f /dump_file/ dllist
```
4. CMD (Windows)
```
python2 vol.py -f /dump_file/ cmdline
```
```
python2 vol.py -f /dump_file/ cmdscan
```
```
python2 vol.py -f /dump_file/ consoles
```
