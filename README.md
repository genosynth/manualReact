# manualReact
Setting up a react up without using create-react-app

1. Run npm install to install all dependencies.

```
  "dependencies": {
    "babel-loader": "^8.2.5",
    "react": "^18.1.0",
    "react-dom": "^18.1.0"
  },
```

And these development depencies where if you install them seperately you would do 
```
npm install {dependency} --save-dev
```

```
  "devDependencies": {
    "@babel/core": "^7.18.0",
    "@babel/preset-env": "^7.18.0",
    "@babel/preset-react": "^7.17.12",
    "html-webpack-plugin": "^5.5.0",
    "webpack": "^5.72.1",
    "webpack-cli": "^4.9.2",
    "webpack-dev-server": "^4.9.0"
  }
```