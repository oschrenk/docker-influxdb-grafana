# README

```
git clone https://github.com/oschrenk/docker-influxdb-grafana
cd docker-influxdb-grafana
./run.sh
```

To install Influx CLI

```
brew install influxdb
```


## Configuration

```
influx -precision rfc3339
```

```
# Create a database
influx -precision rfc3339
Connected to http://localhost:8086 version 1.4.3
InfluxDB shell version: v1.4.3
> CREATE DATABASE example
```

## Usage

Open browser to `localhost:3000`

## Resources

http://simonjbeaumont.com/posts/docker-dashboard/
