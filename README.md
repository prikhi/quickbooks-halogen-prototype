# MOVED TO https://github.com/prikhi/quickbooks-for-communes

## QuickBooks for Communards - Halogen Prototype

**Note: This trial has been merged into the main repository: https://github.com/prikhi/quickbooks-for-communes**

This is a test frontend for our QuickBooks for Communes server written in
Purescript/Halogen.


### Build

To build the Purescript app:

```sh
npm install
npx spago install
npx spago build
```

You can rebuild on file changes:

```sh
npm run watch
```

You can start a dev server that redirects `/api/` paths to the backend:

```sh
npm run serve
```

Or build for production:

```sh
npx parcel build index.html
```


### License

GPL-3.0
