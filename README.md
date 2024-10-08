# @elastic/ebt/*

This module implements the Analytics client used for Event-Based Telemetry. The intention of the client is to be usable on both: the UI and the Server sides.

## Client

`@elastic/ebt/client` holds the public APIs to report events, enrich the events' context and set up the transport mechanisms. Refer to the [client's docs](./src/client/README.md) for more information.

## Prebuilt shippers

Elastic-approved shippers are available as `@elastic/ebt/shippers/*` packages. Refer to the [shippers' docs](./src/shippers/README.md) for more information.
