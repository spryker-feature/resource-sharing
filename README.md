# Spryker Feature: Resource Sharing

Resource Sharing is a generic feature, that allows you to create Unique URL for any entity in the Spyker Commerce OS. For each entity, you should use additional connector-module. For example, to share Cart through URL, Resource Sharing feature should be combined with Persistent Cart Sharing.

## Installation

```
composer require spryker-feature/resource-sharing
```

## Recommended feature dependencies
- [spryker-feature/customer-account-management](https://github.com/spryker-feature/customer-account-management)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [ResourceShareExtension ^1.0.0](https://github.com/spryker/resource-share-extension) (Extension)
- [Shop.ResourceSharePageExtension ^1.0.0](https://github.com/spryker-shop/resource-share-page-extension) (Extension)
