# CubeMart Shipping Service

![CubeMart](https://img.shields.io/badge/CubeMart-Shipping-0f766e)
![Go](https://img.shields.io/badge/Go-Service-00ADD8)
![gRPC](https://img.shields.io/badge/gRPC-Shipping-1f2937)

The Shipping service provides shipping quotes, tracking IDs, and fulfillment flow support for CubeMart orders.

## Local

Run the following command from the repo root to vendor Go dependencies locally:

    go mod vendor

## Build

From the repo root, run:

```
docker build ./
```

## Test

```
go test .
```
