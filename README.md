#Foundation 6 Starter Template

## Use
  
Before you start you have to update Foundation with:

```bash
npm install
bower install
```

We also have to include gulp-uglify and pump to minify the js files on the go. 
Keep in midn that minifier is disabled by default. Go to gulpfile.js and change "production" to "true"

```bash
npm install --save-dev gulp-uglify
npm install --save-dev pump
```

BTW, any package can be included to the project, for example to optimize images or any other usefull for your project from https://www.npmjs.com/



Finally, run 
```bash
npm start
```
to run the Sass and Js compiler. It will re-run every time you save a Sass or JS file.


## Upgrading

If you'd like to upgrade to a newer version of Foundation down the road just run:

```bash
bower update
```


## Compile sass using compass

Install `Ruby` on your computer
Install `Compass` gem
```bash
gem install compass
 ```
 
Configure your `config.rb` file (already configured for Foundation 6) and run compass
 
```bash
compass w or compass watch
```