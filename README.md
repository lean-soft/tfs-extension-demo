## Install Nodejs

## Install tfc-cli
```javascript
npm i -g tfx-cli
```

## Package your extension
Packaging your extension into a .vsix file is effortless once you have the tfx-cli, simply navigate to your extension's home directory and run the following command.
```javascript
tfx extension create --manifest-globs vss-extension.json
```
