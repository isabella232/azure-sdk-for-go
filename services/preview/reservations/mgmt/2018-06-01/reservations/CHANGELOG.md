Generated from https://github.com/Azure/azure-rest-api-specs/tree/3c764635e7d442b3e74caf593029fcd440b3ef82

Code generator @microsoft.azure/autorest.go@~2.1.161

## Breaking Changes

- Function `NewOperationListPage` parameter(s) have been changed from `(func(context.Context, OperationList) (OperationList, error))` to `(OperationList, func(context.Context, OperationList) (OperationList, error))`
- Function `NewOrderListPage` parameter(s) have been changed from `(func(context.Context, OrderList) (OrderList, error))` to `(OrderList, func(context.Context, OrderList) (OrderList, error))`
- Function `NewListPage` parameter(s) have been changed from `(func(context.Context, List) (List, error))` to `(List, func(context.Context, List) (List, error))`
