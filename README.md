# To make this work, do not forget to install pug-cli, stylus, autoprefixer-stylus, babel-cli, babel-preset-es2015 globally!
> npm i pug-cli stylus autoprefixer-stylus babel-cli babel-preset-es2015 -g


## Pug
> pug pug/index.pug --out ./ -w 

## Stylus
> stylus -u autoprefixer-stylus ./styl/main.styl --out ./assets/css  -w -m --compress

## Babel
> babel --presets es2015 ./js/main.js -d assets -w