# tsconfig-vite-node

An opinionated TSConfig for Node.js applications developed with `vite-node` and/or built with `vite`.

Highlights:

- All targets are set to `ESNext` (meaning whatever the current Node.js interpreter supports).
- `moduleResolution` is set to `"Bundler"` (allows imports without file extensions).
- `strict` and `noUncheckedIndexedAccess` are enabled by default.

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

_TODO: Document building with Vite._
