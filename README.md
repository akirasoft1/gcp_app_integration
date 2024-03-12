# custom:com.dynatrace.extension.google-connectors

**Latest version:** 0.0.4
This extension is built using the Dynatrace Extension 2.0 Framework.
This means it will benefit of additional assets that can help you browse through the data.

## Metrics

This extension will collect the following metrics:
* Split by :
  * Connection Status (`cloud.gcp.connectors_googleapis_com.connection.connection_status`)
  * Connection request latencies (`cloud.gcp.connectors_googleapis_com.connection.latencies`)
  * Connection node count (`cloud.gcp.connectors_googleapis_com.connection.nodes`)
  * Connection request count (`cloud.gcp.connectors_googleapis_com.connection.request_count`)
  * Connection request sizes (`cloud.gcp.connectors_googleapis_com.connection.request_sizes`)
  * Connection response count (`cloud.gcp.connectors_googleapis_com.connection.response_count`)
  * Connection response sizes (`cloud.gcp.connectors_googleapis_com.connection.response_sizes`)
  * Connection state (`cloud.gcp.connectors_googleapis_com.connection.state`)

# Configuration

## Feature sets

Feature sets can be used to opt in and out of metric data collection.
This extension groups together metrics within the following feature sets:

* default

## Variables

Variables are used in monitoring configurations for filtering and adding additional dimensions.
This extension exposes the following variables:

* `filter_conditions` (text) - Metric query filter for which metrics should be queried

