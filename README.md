# monitoring-03-grafana
Домашнее задание к занятию 14 «Средство визуализации Grafana»
#
Задание 1
#
![alt text](image-1.png)
#
Задание 2

100 - avg(irate(node_cpu_seconds_total{job="node-exporter", mode="idle"}[1m])) * 100
#
![alt text](image-2.png)
#
avg(node_load1{job="node-exporter"})

avg(node_load5{job="node-exporter"})

avg(node_load15{job="node-exporter"})
#
![alt text](image.png)
#
node_memory_MemFree_bytes
#
node_memory_MemTotal_bytes
#
![alt text](image-3.png)
#
node_filesystem_avail_bytes
#
![alt text](image-5.png)
#
общее
#
![alt text](image-4.png)
Задание 3
#
![alt text](image-6.png)
#
Задание 4
#
[text](1.json)
#