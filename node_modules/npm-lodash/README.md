# npm-lodash

[npm-lodash](https://www.npmjs.com/package/npm-lodash)  

`npm login`  

`npm publish`  

check npm `https://www.npmjs.com/settings/jacobhsu/packages`  

## Reference

[lodash](https://github.com/lodash/lodash)  
`npm i lodash` node_modules\lodash

## Installation

`npm i npm-lodash`

```js
const findKey = require('npm-lodash/findKey');

var users = {
  barney: { age: 36, active: true },
  fred: { age: 40, active: false },
  pebbles: { age: 1, active: true },
};
var ans = findKey(users, function (o) {
  return o.age < 40;
});
console.log(ans) // barney
```
