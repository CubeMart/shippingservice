# CubeMart Shipping Service

![CubeMart](https://img.shields.io/badge/CubeMart-Shipping-0f766e)
![Go](https://img.shields.io/badge/Go-Service-00ADD8)
![gRPC](https://img.shields.io/badge/gRPC-Shipping-1f2937)

The Shipping service provides shipping quotes, tracking IDs, and fulfillment flow support for CubeMart orders.

## Local

Run the following command to restore dependencies to `vendor/` directory:

    dep ensure --vendor-only

## Build

From `src/shippingservice`, run:

```
docker build ./
```

## Test

```
go test .
```
