
1. Initiate Node project

```
node init -y
```

2. Install Babel dependencies

Babel is a compiler that convers modern JavaScript to run in older browsers.

```
npm install --save-dev @babel/core babel-loader @babel/preset-env @babel/preset-react
```

3. Install Webpack dependencies

Webpack is a static module bundler for modern JavaScript applications.

```
npm install --save-dev webpack webpack-cli webpack-dev-server
```

4. Install **HtmlWebpackPlugin**

```
npm install --save-dev html-webpack-plugin
```

5. Install React

```
npm install react react-dom
```
6. Create a React app files.

7. Configure Babel

```
touch .babelrc
```

8. Configure Webpack

```
touch webpack.config.js
```

9. Add scripts to package.json

10. Build the app and start in dev mode:

```
npm run build
npm start
```

Deployment files are in `dist` folder.