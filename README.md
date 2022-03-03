npm install --save-dev webpack@<v5.69.1>
"scripts": {
  "build": "webpack --config webpack.config.js"
}
npx webpack build --config ./webpack.config.js --stats verbose
npx webpack init ./my-app --force --template=vegeclub
npx webpack loader ./my-loader --template=vegeclub
npx webpack plugin ./my-plugin --template=vegeclub
npx webpack info --output json --addition-package postcss
