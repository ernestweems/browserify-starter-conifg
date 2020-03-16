# browserify-starter-conifg
Base config to get going with browserify version 8 and Babel version 6  

browswerify must be installed at global level inorder of all this to work

```
# Babel 6 
$ npm install --save-dev babelify@8 babel-core

```
## dev 

```
  "devDependencies": {
    "babel-core": "^6.26.3",
    "babel-plugin-transform-decorators-legacy": "^1.3.5",
    "babel-preset-es2015": "^6.24.1",
    "babel-preset-stage-0": "^6.24.1",
    "babelify": "^8.0.0"
  }

```

## prests .babelrc

```
{
    "presets": ["es2015", "stage-0"],
    "plugins": ["transform-decorators-legacy"],
    "sourceMaps": "inline"
  }
  
  ```

