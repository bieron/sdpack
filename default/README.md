# Pack In, Pack Out
----

This Pack offers the bleeding edge Source&Destination functionality. It will be continuously upgraded with advancement of the epic.

Right now it offers just the rudimentary TCP ingestion at 0.0.0.0:7312 that gets directly QCed to 0.0.0.0:2137 egress. There's also a datagen so you only need to listen on the destination to observe the traffic. You can use the builitin cribl nc functionality for that purpose:
```sh
bin/cribl nc -p 2137 -o
``` 

Have thoughts or bug reports? Contact the Control Plane team at on [#proj-config-mp](https://cribl.enterprise.slack.com/archives/C07AA4AMYB1)