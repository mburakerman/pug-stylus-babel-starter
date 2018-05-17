## To make this work, do not forget to install pug-cli, stylus, autoprefixer-stylus, babel-cli, babel-preset-es2015 globally!
```js
npm i pug-cli stylus autoprefixer-stylus babel-cli babel-preset-es2015 -g
```

Open 3 terminals and run the commands below. They compile pug to html, stylus to css(with prefix) and es6 to es5.

### Pug
> pug pug/index.pug --out ./ -w 


### Stylus
> stylus -u autoprefixer-stylus ./styl/main.styl --out ./assets/css  -w -m --compress


### Babel
> babel --presets es2015 ./js/main.js -d assets -w
