Gulp Boilerplate for generic CSS/HTML/JS development
=============

Based on nunjucks, sass, awebpack

Structure
=============
`/src/` - thats where you write code.

`/build/` - compiled code. Do not ever edit this folder.


How to use
=============

1) `$ npm install`

2) run `$ gulp build` to build initial files for build (only for the first time)

3) `$ gulp` - it will start local server at <a href="http://localhost:8080/">http://localhost:8080/</a>

4) `$ npm run build` - it will delete your build folder first and then compile project in production mode(using code minifying etc.)