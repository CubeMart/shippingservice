# CubeMart Shipping Service

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
