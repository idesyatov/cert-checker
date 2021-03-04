# Certificate expiration date check

To run, you need to describe the configuration file and execute app with him

Example with use cron:

```cron
0   11   *   *   *   cd /opt/project/monitoring && ./main ./config 2>&1 >> /var/log/monitoring.log
```
