## Project setup

```
npm install
```

After creation, your project should look like this:

```
my-app/
  node_modules/
  src/
    img/
    js/
    pug/
      layout/
      modules/
      pages/
      utils/
    scss
      modules/
      utils/
      main.scss
    index.js
  .babelrc
  package.json
  README.md
  webpack.base.config.js
  webpack.build.conf.js
  webpack.dev.conf.js
```

### Compiles and hot-reloads for development

```
npm run dev
```

Runs the app in the development mode.<br> Open
[http://localhost:8081](http://localhost:8081) to view it in the browser.

The page will reload if you make edits.<br> You will also see any lint errors in
the console.

## Folder values

- `src/js` folder for storing your scripts
- `src/pug/layout` folder for storing specific layouts for certain pages
- `src/pug/modules` folder for storing your components (header, footer, section)
- `src/pug/pages` folder for storing your pages
- `src/pug/utils` folder for storing files, that facilitate work (mixins)
- `src/scss/modules` folder for storing styles of your components
- `src/scss/utils` reset styles (reset.scss), connecting css libraries
  (libs.scss), custom styles (vars.scss)
- `src/scss/main` main scss file
- `src/index.js` main js file, connecting js libraries

### Compiles and minifies for production

```
npm run build
```

Builds the app for production to the `dist` folder.<br> It correctly optimizes
the build for the best performance.

The build is minified and the filenames include the hashes.<br> Your app is
ready to be deployed!

```
  dist/
    css/
    img/
    js/
    index.html
    indexPug.html
    indexSass.html
```
