# K8S Host Based Routing Demo

```
$ curl service-a.testenv.site
ServiceA

$ curl service-b.testenv.site
ServiceB

$ curl -H "Host: service-a.host" service.testenv.site
ServiceA

$ curl -H "Host: service-b.host" service.testenv.site
ServiceB
```
