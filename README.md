# weftspun-usd-viewer

The billboard gallery's USD viewer: a WebAssembly USD viewer bundle served as static files by a small Node server.

## What it is for

The gallery shows a dataset's billboards in one USD stage. This app serves the viewer at the gallery paths the studio forwards to it, with the cross-origin isolation headers the WebAssembly build needs, so it also works when opened directly. RFD 1076 owns the design.

## Build and run

```sh
npm install
npm run build
npm start
```

## Licence

MIT. See [LICENSE](LICENSE).
