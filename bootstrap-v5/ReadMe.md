## Commands

- Node version

```bash
$ node -v             
v16.14.0
$ npm -v                                                          
8.3.1

- Install dependencies
$ npm init

$ npm install --save-dev saas
$ npm install --save bootstrap
$ npm install --save @fortawesome/fontawesome-free
$ npm install postcss-cli autoprefixer --save
```

- Generate CSS
```bash
$ mkdir scss        
$ touch scss/style.scss   

$ npm run compile:sass

> bootstrap-v5@1.0.0 compile:sass
> sass scss:assets/css
```


- Create file

```bash
$ touch scss/_custom.scss
$ touch theming-kit.html 
```