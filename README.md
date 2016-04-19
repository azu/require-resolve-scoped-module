# require.resolve(scopedModule)

Test combination of `require.resolve` and Scoped module.

```js
// resolve path of @npm/acl-client
const resolvePath = require.resolve("@npm/acl-client");
console.log("Path:" + resolvePath);
```

## Installation

    npm install

## Usage

    npm test
    # show correct path


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

MIT