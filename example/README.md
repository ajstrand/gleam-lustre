# lustre_counter

This is an example Lustre project. It uses [watchexec](https://github.com/watchexec/watchexec) to rebuild the Gleam project on save.

## Quick start

Initial setup:
```sh
npm install
gleam build
```

Run dev server on `localhost:3000`:
```sh
make dev
```

Make a production build under `dist` folder:
```sh
make
```

## preact support

If you want to use lustre with preact you need to install [https://github.com/preactjs/compat-alias-package](this) package.

THis package aliases React with package.json

Of course, there are other ways to alias React if you want to use a different build tool.


```sh
npm install react@npm:@preact/compat react-dom@npm:@preact/compat
```
