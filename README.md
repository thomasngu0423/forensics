# Forensics Cheatsheet

## Table Of Content
  * [Installing Volatility 2](#installing-volatility-2)
  * [Basic Volatility Command](#basic-volatility-command)
  * [Wireshark Cheatsheet](#wireshark-cheatsheet)


## Installing Volatility 2
1. `$ git clone https://github.com/volatilityfoundation/volatility.git`
2. `$ python2 setup.py`

## Basic Volatility Command
**OS Information**
```
python2 vol.py imageinfo -f /dump_file/
```
**Process Information**
```
python2 vol.py pslist -f /dump_file/
```
```
python2 vol.py psscan -f /dump_file/
```
```
python2 vol.py pstree -f /dump_file/
```
**Process Dump**
```
python2 vol.py -f /dump_file/ procdump ---dump-dir /directory
```
**DLLs**
```
python2 vol.py -f /dump_file/ dllist
```
**CMD (Windows)**
```
python2 vol.py -f /dump_file/ cmdline
```
```
python2 vol.py -f /dump_file/ cmdscan
```
```
python2 vol.py -f /dump_file/ consoles
```
**Network Information**
```
python2 vol.py -f /dump_file/ netscan
```
```
python2 vol.py -f /dump_file/ netstat
```
```
python2 vol.py -f /dump_file/ connscan
```
```
python2 vol.py -f /dump_file/ connections
```
```
python2 vol.py -f /dump_file/ sockets
```
**MISC**
```
python2 vol.py -f /dump_file/ malfind
```
## Wireshark Cheatsheet
![image](https://github.com/thomasngu0423/forensics/assets/100482919/6fc84d57-b80a-4862-938e-72ffb7059945)
![image](https://github.com/thomasngu0423/forensics/assets/100482919/4a88baa4-4092-45df-ab62-19fa11a72abc)


