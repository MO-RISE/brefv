# brefv

A public message set aimed at maritime usecases maintained by Maritime Operations - RISE.

# Getting Started

Brefv messages are handed out by a MQTT server. The topic specifies who generates the information:

```
/<parent_type>/<parent_id>/<child_type>/<child_subtype>/<child_id>
```

For example:

```
/external/sjofartsverket/ais/vessels/mmsi

/test_vessel/729/sensor/gnss/0

/test_vessel/729/control/rudder/0


```
