# python-prometheus
Monitoring python application metrics 




## start prometheus in new terminal
```
wget https://github.com/prometheus/prometheus/releases/download/v2.11.1/prometheus-2.11.1.linux-386.tar.gz

tar -xzvf prometheus-2.11.1.linux-386.tar.gz 

sudo cp prometheus-2.11.1.linux-386/prometheus /usr/bin/prometheus

prometheus --config.file=promconfig.yaml
```
