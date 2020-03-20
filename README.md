### This is the script to utilise CPU and RAM metrics form a host PC.
```
## To use it you must folow below instruction:
- Python3 has to be installed.
- statsd daemon has to be installed.
- psutil daemon has to bi installed.
- you have to clone this rep or copy this file to a local PC and start script using 
Python3 metrics
- script can parse 2 parameters: "cpu" and "mem" to display according information. eg:
Python3 metrics mem
```
Script was tested on Ubuntu 18.04. So in case you have unix OS you may try next action:
```
## For more convinient usage:
chmod +x metrics
env | grep PATH
export PATH=$PATH:/full/path/to/script
- Now you can run script jyst typing 
./metrics
```
