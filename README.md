# Logistica Guru

## Usage first site
```bash
nvm use node
npm install
```

### Workflow

While developing your website, use:

```bash
nvm use node
npm run build
npm start
```

```
git checkout -b 20200303-branchname
git push origin
### make modifications
### go to github create the PR and merge
```
## Structure

```
|--site                // Everything in here will be built with hugo
|  |--content          // Pages and collections - ask if you need extra pages
|  |--data             // YAML data files with any data for use in examples
|  |--layouts          // This is where all templates go
|  |  |--partials      // This is where includes live
|  |  |--index.html    // The index page
|  |--static           // Files in here ends up in the public folder
|--src                 // Files that will pass through the asset pipeline
|  |--css              // Webpack will bundle imported css separately
|  |--index.js         // index.js is the webpack entry for your css & js assets
```

