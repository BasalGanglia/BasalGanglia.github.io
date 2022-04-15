---
layout: post
title: Learning InfluxDB
author: User
summary: Summary of the article
---
I tried the cloud option but quickly ran into limitations:

![ouch](../assets/images/2022-04-15-influx_db_explorations/2022-04-15-13-20-48.png)

So I decided to deploy it to my local docker desktop:

![launching as docker container](../assets/images/2022-04-15-influx_db_explorations/2022-04-15-13-16-38.png)

installing influxdb cli locally

![](../assets/images/2022-04-15-influx_db_explorations/2022-04-15-13-56-01.png)![](../assets/images/2022-04-15-influx_db_explorations/2022-04-15-13-56-33.png)

![configuring the cli to point to influxdb running in local docker container at port 8089](../assets/images/2022-04-15-influx_db_explorations/2022-04-15-13-56-45.png)

The influxdb University seems like a very nice resource!
![directions from influxdb uni course](../assets/images/2022-04-15-influx_db_explorations/2022-04-15-13-59-01.png)

some additional commands
![](../assets/images/2022-04-15-influx_db_explorations/2022-04-15-14-04-00.png)

![](../assets/images/2022-04-15-influx_db_explorations/2022-04-15-14-04-41.png)

![](../assets/images/2022-04-15-influx_db_explorations/2022-04-15-14-08-52.png)

but of course it was not so easy...
![](../assets/images/2022-04-15-influx_db_explorations/2022-04-15-14-11-07.png)

# Influxdb theory

![](../assets/images/2022-04-15-influx_db_explorations/2022-04-15-14-14-28.png)

![](../assets/images/2022-04-15-influx_db_explorations/2022-04-15-14-15-26.png)

output from flux:
![](../assets/images/2022-04-15-influx_db_explorations/2022-04-15-14-17-14.png)

# InfluxDB Line Protocol

![](../assets/images/2022-04-15-influx_db_explorations/2022-04-15-14-18-54.png)

![](../assets/images/2022-04-15-influx_db_explorations/2022-04-15-14-20-52.png)

Points:

![definition of points](../assets/images/2022-04-15-influx_db_explorations/2022-04-15-14-23-48.png)

