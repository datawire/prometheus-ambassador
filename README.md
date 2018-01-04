# Monitoring

This repository contains a configuration for monitoring Ambassador using Grafana and Prometheus. It relies on the Prometheus Operator.

## Test

To test the set up without Ambassador, apply the YAML in the `test` directory. This should create a Prometheus cluster that monitors a sample app.
