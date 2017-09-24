# Ladbroks Task Installing:

1) Open git Bash at this folder.
2) Type `npm install` ( Wait for node_modules folder to be fully installed ).
3) Type `npm start` ( Will run the project on local server )
# More details:
4)Development or Production enviroment: <br />
package.json: <br />
"scripts": { <br />
// For development mode type `dev:*` and then enter `npm start` on terminal.
`npm-run-all --parallel dev:*` <br />
// For production mode use `prod:*` and then enter `npm start` on terminal.
`npm-run-all --parallel prod:*` <br />
} <br />
5) Type `npm run build` to minify html.<br />
6) Type `npm run prod:img-compress` to compress al images.<br />
7) Type `npm run prod:js-uglify` to minify js file.
