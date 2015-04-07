# parse-params
simple node module to parse parameters of a function

npm install parseparams

var parse = require('parseparams');

var func = function(param1, param2){

};

console.log(parse(func)) // ['param1','param2']
