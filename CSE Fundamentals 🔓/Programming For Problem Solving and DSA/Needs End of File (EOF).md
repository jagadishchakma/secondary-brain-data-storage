# C
- EOF
- while(scanf() != EOF)
# C++
- cin
- while(cin >> a)
# JS
- readline module
```js
const readline = require("readline");

  

const rl = readline.createInterface({

	input: process.stdin,

	output: process.stdout

});

function processInput(input){

	const [a, b] = input.split(' ').map(Number);

	console.log(`${a} ${b}`);

};

  

rl.on("line",processInput)
```
