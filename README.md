# Ladbroks

# Installing:

1) Open git Bash at this folder.
2) Type "npm install" ( Wait for node_modules folder to be fully installed ).
3.1) Type "npm start" ( Will run the project on local server )

3.2) #Development or Production enviroment:
package.json:

"scripts": {
// For development mode use "dev:*" and then enter "npm start" on terminal.
Dev mode: "start": "npm-run-all --parallel dev:*"
// For production mode use "prod:*" and then enter "npm start" on terminal.
Live mode: "start": "npm-run-all --parallel prod:*"
}

4) Type "npm run build" to minify html.
5) Type "npm run prod:img-compress" to compress al images.
6) Type "npm run prod:js-uglify" to minify js file.
