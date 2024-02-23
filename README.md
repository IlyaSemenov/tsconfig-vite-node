# tsconfig-vite-node

A base TSConfig for Node apps developed with `vite-node` and/or built with `vite`.

## Install

```sh
npm install tsconfig-vite-node
```

## Use

In `tsconfig.json`:

```json
{
  "extends": "tsconfig-vite-node"
}
```

In `package.json`:

```json
{
  "type": "module",
  "scripts": {
    "dev": "vite-node --watch src/server.ts"
  }
}
```

_TODO: document building with vite._
