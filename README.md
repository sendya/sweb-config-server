Spring cloud config server
====

config path: https://github.com/sendya/sweb-cloud-config/cloud-test-config/  

get config: http://localhost:8801/sweb/dev  

config json:

```json
{
    "name": "sweb",
    "profiles": ["dev"],
    "label": null,
    "version": "1f358fc7ae65e59b337ede63e72a624dd2607f81",
    "state": null,
    "propertySources": [{
        "name": "https://github.com/sendya/sweb-cloud-config/cloud-test-config/application-dev.yml",
        "source": {
            "sweb.name": "dev-config",
            "sweb.config.requestLogin": true,
            "sweb.config.v": 1.0,
            "sweb.config.boot": "localhost",
            "sweb.base.test": "111s"
        }
    }]
}
```