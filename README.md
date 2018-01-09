munin_exporter
==============

The munin exporter is a daemon serving munin metrics via HTTP/JSON for Prometheus consumption.

Based on https://github.com/prometheus-junkyard/munin_exporter

Original contribution by Soundclound, provided by @discordianfish


to build in docker `docker run -it --rm -v "$PWD":/go/src/github.com/pvdh/munin_exporter -w /go/src/github.com/pvdh/munin_exporter golang:1.8 bash -c "go get && go build && cp /go/bin/munin_exporter ." `
