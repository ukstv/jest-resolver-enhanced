# Jest Resolver Enhanced

Resolver for jest:
- use [enhanced-resolve](https://www.npmjs.com/package/enhanced-resolve) from Webpack by default,
- ff enhanced-resolve fails, use vanilla Jest resolver.

Allows Jest to handle [conditional exports](https://nodejs.org/api/packages.html#packages_conditional_exports).
Uses `node` and `require` conditions.