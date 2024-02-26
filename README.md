# Types for Shopware Storefront

This package provides types for window-bound classes in Shopware 6 Storefront:

- `window.PluginManager`
- `window.PluginBaseClass`
- `window.router`

and all regular imports of the Storefront.

Install this package with NPM:

```bash
npm install @shopware-ag/storefront-types --save-dev
```

To have the types active, you need to create a `tsconfig.json` (`src/Resources/app/storefront/tsconfig.json`) with the following content:

```json
{
    "compilerOptions": {
        "types": ["@shopware-ag/storefront-types"]
    }
}
```
