# Gamejam
Landing page for LiU Game Jam

## Development
This prototype site is using a modified Google Web starter kit as base for the development environment

### Installing
To start development or check running the site locally you need to install the neccessary packages. Run

```
npm install
```

### Running Browsersync
Included in WSK is the Browersync plugin which allows for Live Browser Reloading whilst developing, start the server by running:

```
gulp serve
```

### Deployment
To deploy the site to the Github pages, i.e to push the built files to the gh-pages branch you just run the following gulp task.

```
gulp deploy
```

The built files are both minified and concatinated to improve performance, to build the files locally and not deploying simply run gulp:

```
gulp
```

### Web performance testing
WSK has support for running pagespeed insights as a gulp task, which shows metrics for how well the site performs on mobile and desktop. 

```
gulp pagespeed
```

