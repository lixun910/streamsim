# StreamSim
A simulator for feeding streaming data

StreamSim is a simple server with explicit data API that can be called to fetch real-time data.

## Input
The actual data with time stamps can be used as input to simulate real-time feeder.

## API
A simple HTTP API is used as the interface of this simulator. 

HTTP call
```HTML
http://127.0.0.1:6565/GetData?starttime=xxx&endtime=xxx
```
