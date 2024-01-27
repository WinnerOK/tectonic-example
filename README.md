# tectonic + Vs-code

A simple instruction for me on how to use [tectonic](https://github.com/tectonic-typesetting/tectonic) together with VS-Code and auto-reload

## Start project
```
tectonic -X new document_name
```
creates a `document_name` subfolder with sample files.

## Build tectonic project
```
tectonic -X build
```

### Auto-build project
For automatic builds use [Run On Save](https://marketplace.visualstudio.com/items?itemName=emeraldwalk.RunOnSave) extension and setup the hook in [workspace settings](.vscode/settings.json)