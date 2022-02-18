---
title: Prometheus Operator Rejected Resources
weight: 20
---

# PrometheusOperatorRejectedResources

## Meaning

Resources rejected by Prometheus operator.

## Impact

Prometheus Operator will denied to manage Prometheuses/Alertmanagers.

## Diagnosis

Check newly created resources like Prometheus or ALertManager, Rules, Probes, ServiceMonitors and so on.
Check logs of Prometheus Operator pod.
Check service account tokens.

## Mitigation
