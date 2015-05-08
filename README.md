# docker-cmdline-jmxclient

A docker container wrapping http://crawler.archive.org/cmdline-jmxclient/

## Usage

```
docker run --rm ulich/cmdline-jmxclient <parameters passed to jmxclient>
```

e.g.

```
docker run --rm ulich/cmdline-jmxclient - localhost:9010 'ch.qos.logback.classic:Name=default,Type=ch.qos.logback.classic.jmx.JMXConfigurator' 'getLoggerEffectiveLevel=org.springframework'
```
