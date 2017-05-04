Stoic
========
Master repo and composer for Stoic

Running
-------

Install Docker and Docker Compose then run:

```
docker-compose build
docker-compose up
```

Environment Flags
-----------------

There are a handful of environment variables to be configured.
Some of the most helpful for debugging are:
`FLASK_DEBUG` - Set to `1` for debug logging from Flask

`SSL_DISABLE` - Set to `True` to disable SSL when developing or debugging
