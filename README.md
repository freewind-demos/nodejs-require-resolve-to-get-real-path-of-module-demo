NodeJS "require.resolve" to Get Real Path of Modules Demo
=========================================================

## 1. If use `npm`:

```
npm i
npm run demo
```

```
<projectPath>/node_modules/lodash/lodash.js
```

## 2. If use `pnpm`:

```
pnpm i
pnpm run demo
```

```
<projectPath>/node_modules/.registry.npmjs.org/lodash/4.17.5/node_modules/lodash/lodash.js
```

## 3. If use `yarn`:

```
yarn
yarn demo
```

```
<projectPath>/node_modules/lodash/lodash.js
```
