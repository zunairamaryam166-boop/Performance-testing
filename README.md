# Performance Testing Suite

## Overview

A performance testing suite for **API load testing**, covering two scenarios:

### 1. Token-Based API Testing

* Generates an authentication token.
* Extracts and passes the token to the target API.
* Executes the API under configurable load.
* Measures response time, throughput, and error rate.

**Flow:**
`Create Token → Extract Token → Hit API → Validate Response → Collect Metrics`

### 2. File-Based API Testing

* Reads test data from an external file.
* Uses the data to construct API requests.
* Executes API actions under load.
* Validates responses and captures performance metrics.

**Flow:**
`Read File → Extract Data → Hit API → Validate Response → Collect Metrics`

## Key Metrics

* Response Time
* Throughput / TPS
* Error Rate
* P90 / P95 / P99
* Concurrent Users
* HTTP Status Codes

## Test Types

* Load Testing
* Stress Testing
* Endurance Testing

## Configuration

Test parameters such as **API URL, users, ramp-up time, duration, authentication details, and input file** are configurable.

## Purpose

The suite helps identify **API performance bottlenecks, scalability issues, response-time degradation, and failures under load**.
