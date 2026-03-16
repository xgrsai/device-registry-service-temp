# IoT Hub Device Registry Service

Source-of-truth service for devices, metrics, and telemetry configuration.

## Purpose

The Device Registry Service manages the device catalog and the configuration required for telemetry validation and downstream processing.

## Responsibilities

- device registration and management
- metric definitions
- device-to-metric bindings
- device ownership

## Owned data

- devices
- metrics
- device metrics
- ownership relations

## Integrations

### Inbound
- frontend
- admin clients
- internal management flows

### Outbound
- configuration events for downstream services

## Technology

- Django
- PostgreSQL
- Docker
