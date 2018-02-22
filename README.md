# Babel exercise

The goal of this exercise is to understand some basics of Babel.

## Get started

If you have npm:
`git clone https://github.com/leanjscom/babel-exercise.git && cd babel-exercise && npm install`

## Exercise

1- Run this command **`node index.js`** and you'll see an error. Where is the problem?

2- Run this command **`npm install --save-dev babel-cli babel-preset-es2015`**

3- You should configure babel using the presets in the .babelrc file. Let's add the following presets:
**`{
  "presets": ["es2015"]
}`**

4- If this is working you should be able to see the transpiled code by running: **`npm run babel`**

5- Now you can use the -o flag to output this into a file: **`npm run babel:save`**

6- Now you should be able to run the transpiled file by running: **`node transpiled_index.js`**

7- More questions? Don't forget to check out the docs, in particular: http://babeljs.io/docs/usage/cli/
