# ethereum-open-rpc-generator-sandbox

## Initialize execution-apis

```bash
$ git submodule update --init --recursive
$ cd execution-apis/
$ npm ci
$ npm run build
```

## Run open-rpc-generator

```bash
$ yarn open-rpc-generator generate -d execution-apis/openrpc.json -t client -l typescript
```
