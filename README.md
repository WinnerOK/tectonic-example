# tectonic + Vs-code

A simple instruction for me on how to use [tectonic](https://github.com/tectonic-typesetting/tectonic) together with VS-Code and auto-reload

**Note:** `-X` option enables a V2 interface. Once V1 will get discontinued and V2 will be a default

## Start project
```
tectonic -X new document_name
```
creates a `document_name` subfolder with sample files.

## Build tectonic project
```
tectonic -X build
```

## Auto-build project
```
tectonic -x watch
```
rebuilds pdf upon _any_ file change in the directory