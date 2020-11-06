# CatSec-Syn-Flood
Python3 SYN Flood Attack


## Dependencies
```
apt install python3-scapy
```

## Installation

```
git clone https://github.com/catsecorg/CatSec-Syn-Flood.git
cd CatSec-Syn-Flood
```

## Usage

```
python3 catsec_synflood.py -t 10.20.30.40 -p 8080 -c 5

```
```
usage: py3_synflood_cmd.py [-h] [--target TARGET] [--port PORT]
                           [--count COUNT] [--version]

optional arguments:
  -h, --help            show this help message and exit
  --target TARGET, -t TARGET
                        target IP address
  --port PORT, -p PORT  target port number
  --count COUNT, -c COUNT
                        number of packets
  --version, -v         show program's version number and exit

Usage: python3 catsec_synflood.py -t 10.20.30.40 -p 8080 -c 1
```

