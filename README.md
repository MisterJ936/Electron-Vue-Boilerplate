# Electron Vue Template
This is used for starting a Vue-Cli projecj that can deploy as a website or deploy as a software using electron.

## Clone this Project and setup
using this command will install the dependencies needed
```
npm install
```

### Serve for Development(Hot Reload)
```
npm run serve //this command runs the app in web form and can be opened using any browser
npm run electron:serve //this command will run the app in electron app
```

### Compile Only The dist

```
npm run build //this command only builds the index.html files inside a dist file
npm run electron:build //this command will bundle the electron app using electron-builder
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
