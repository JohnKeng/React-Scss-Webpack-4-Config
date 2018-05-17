# React Scss Webpack4 Config
The webpack.config.js optimized bundle based on best practices.

install dependencies

```
mkdir myapp
cd myapp
npm init -y
npm install --save-dev webpack babel-loader babel-preset-react babel-core babel-preset-env css-loader style-loader sass-loader node-sass file-loader url-loader lodash-webpack-plugin
npm install react react-dom moment lodash
```

1. Create .babelrc in the root and copy the contents from below

```
{
  presets: [
    [
      'env',
      {
        modules: false
      }
    ],
    'react'
  ]
}
```

2. Create folders src and dist and create your index.js file in src folder and index.html in the dist folder
