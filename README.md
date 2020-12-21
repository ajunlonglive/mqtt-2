English | [中文](./README-CN.md)

# MQTT Protocol Analysis & Coroutine Client

MQTT Protocol Analysis and Coroutine Client for PHP.

Support for `3.1`, `3.1.1` and `5.0` versions of the MQTT protocol.

Support for `QoS 0`, `QoS 1`, `QoS 2`.

[![GitHub Actions](https://github.com/simps/mqtt/workflows/test/badge.svg)](https://github.com/simps/mqtt/actions)
[![Latest Stable Version](https://poser.pugx.org/simps/mqtt/v)](//packagist.org/packages/simps/mqtt)
[![Total Downloads](https://poser.pugx.org/simps/mqtt/downloads)](//packagist.org/packages/simps/mqtt)
[![Latest Unstable Version](https://poser.pugx.org/simps/mqtt/v/unstable)](//packagist.org/packages/simps/mqtt)
[![License](https://poser.pugx.org/simps/mqtt/license)](LICENSE)
[![PHP Version](https://img.shields.io/badge/php-%3E=7.0-blue.svg)](https://www.php.net)
[![Swoole Version](https://img.shields.io/badge/swoole-%3E=4.4.19-blue.svg)](https://github.com/swoole/swoole-src)

## Install

```bash
composer require simps/mqtt
```

## Documentation

[mqtt.simps.io](https://mqtt.simps.io/#/en/) | [MQTT 3.1.1](http://docs.oasis-open.org/mqtt/mqtt/v3.1.1/mqtt-v3.1.1.html) | [MQTT 5.0](https://docs.oasis-open.org/mqtt/mqtt/v5.0/os/mqtt-v5.0-os.html)

## Examples

see [examples](./examples)

## Supports

### Version

- [x] `3.1`
- [x] `3.1.1`
- [x] `5.0`

> Perhaps the first PHP library to support the MQTT `v5.0` protocol.

### QoS

- [x] `QoS 0`
- [x] `QoS 1`
- [x] `QoS 2`

### Type

- [x] CONNECT
- [x] CONNACK
- [x] PUBLISH
- [x] PUBACK
- [x] PUBREC
- [x] PUBREL
- [x] PUBCOMP
- [x] SUBSCRIBE
- [x] SUBACK
- [x] UNSUBSCRIBE
- [x] UNSUBACK
- [x] PINGREQ
- [x] PINGRESP
- [x] DISCONNECT
- [ ] AUTH
