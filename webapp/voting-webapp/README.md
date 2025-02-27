# Voting Webapp optimization

This set of examples shows how to use StormForge Optimize Pro to optimize a webapp using the [voting-webapp example](./voting-webapp). We optimize for the `cost` and `latency` using metrics provided by two load test generators:
- [Locust](https://locust.io)
- [StormForge Performance Testing](https://www.stormforge.io/performance-testing/)

## Prerequisites

You must have a Kubernetes cluster. We recommend using a cluster with 4 nodes, 16 vCPUs (4 on each node) and 32GB of memory (8 on each node). Additionally, you will need a local configured copy of `kubectl`.

Additionally, you will need to initialize StormForge Optimize in your cluster. You can download a binary for your platform from the [installation guide](https://docs.stormforge.io/getting-started/install/) and run `stormforge init` (while connected to your cluster).