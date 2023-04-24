# statsd

## Introduction

This is a fork of https://github.com/alexcesaro/statsd which is currently unmaintained.

statsd is a simple and efficient [Statsd](https://github.com/etsy/statsd)
client.

## Features

- Supports all StatsD metrics: counter, gauge, timing and set
- Supports InfluxDB and Datadog tags
- Fast and GC-friendly: all functions for sending metrics do not allocate
- Efficient: metrics are buffered by default
- Simple and clean API
- 100% test coverage
- Versioned API using gopkg.in


## Documentation

https://godoc.org/github.com/oremj/gostatsd


## Download

    go get github.com/mozilla-services/gostatsd


## Example

See the [examples in the documentation](https://godoc.org/github.com/mozilla-services/gostatsd#example-package).


## License

[MIT](LICENSE)
