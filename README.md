# require.resolve(scopedModule)

Test combination of `require.resolve` and Scoped module.

```js
// resolve path of @npm/acl-client
const resolvePath = require.resolve("@npm/acl-client");
console.log("Path:" + resolvePath);
```