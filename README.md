# @chuyik/husky

> Git hooks made easy

This is a fork of [husky](https://github.com/typicode/husky/tree/master) v4 with a few changes:

- prevents git hooks skipped on GUI app like Tower / SourceTree with [run-node](https://github.com/sindresorhus/run-node)
- throws error if hook is skipped
- fix monorepo issue (https://github.com/typicode/husky/issues/677)

# install

```sh
yarn add --dev @chuyik/husky
```
