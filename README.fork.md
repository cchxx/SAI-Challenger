# SAI Challenger
Fork from https://github.com/opencomputeproject/SAI-Challenger.
To support run it in Python3.5 environment

## how to run

```bash
cisco@sonic:~/SAI-Challenger$ pip3 install click
cisco@sonic:~/SAI-Challenger$ pip3 install pytest
cisco@sonic:~/SAI-Challenger$ pip3 install ptf
cisco@sonic:~/SAI-Challenger$ pip3 install setuptools
cisco@sonic:~/SAI-Challenger$ pip3 install scapy
cisco@sonic:~/SAI-Challenger$ cp cli/main.py  common/
cisco@sonic:~/SAI-Challenger$ cd common/
cisco@sonic:~/SAI-Challenger/common$ python3 main.py list all
```
