
## Babel intro exercise

- Run this command **`node index.js`** and you'll see an error. Where is the problem?
- Run this command **`npm install --save-dev babel-cli babel-preset-es2015 babel-preset-stage-2`**
- You should configure babel using the presets in the .babelrc file. Let's add the following presets:
**`{
  "presets": ["es2015"]
}`**
- If this is working you should be able to see the transpiled code by running: **`babel index.js`**
- Now you can use the -o flag to output this into a file: **`babel index.js -o transpiled_index.js`**
- Now you should be able to run the transpiled file by running: **`node transpiled_index.js`**
- More questions? Don't forget to check out the docs, in particular: http://babeljs.io/docs/usage/cli/
