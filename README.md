# Example usage of BehaviorTree.js lib

This are working example for the [BehaviorTree.js](https://github.com/Calamari/BehaviorTree.js) lib.

## using ES modules

In the `es6/` folder you find an example using new ES modules syntax. This uses babel for transpiling which, of course, can be used within a browser via [webpack](https://webpack.js.org). Or in node via `babel-node` provided by `babel-cli`.

Try it out like this:

```js
cd es6
yarn
npx babel-node example.js
```

## using common.js (node.js)

In the `nodejs` folder you find an example that can be used within simple node.js environments.

Try it out like this:

```js
cd nodejs
yarn
node example.js
```
