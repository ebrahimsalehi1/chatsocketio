# chatsocketio
a simple chat application with socket io

steps to install and using this sample
1-  npm install @babel/core @babel/preset-env @babel/register babel-polyfill
2-
_babelrc file
{
    "presets":[
        "@babel/preset-env"
    ]
}
3- create start.js file

require('@babel/register')({
    presets: ['@babel/preset-env']
});

module.exports = require('./app');

4- npm install express
