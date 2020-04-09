

```
consul agent -dev

mvn spring-boot:run -Dtsf.swagger.enabled=false

tail -f /data/tsf_apm/trace/logs/trace_log.log
```
