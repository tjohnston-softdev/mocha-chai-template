# Mocha-Chai Unit Testing Template

This repository serves as a template for Node JS unit testing with the [Mocha](https://www.npmjs.com/package/mocha) framework. I can never remember how to set up the Mocha script so I thought I'd make a reference for myself and anyone else who might need it.

The steps that I use are as follows:

1. Install [mocha](https://www.npmjs.com/package/mocha) and [chai](https://www.npmjs.com/package/chai).
2. In the project root, create a new folder named "test". The path should look like: `./repository/test/`
3. Create a single `.js` file inside the 'test' folder. The exact name does not matter but I usually go with `index.js`
4. The file created inside 'test' will be your main script. Start writing your unit tests here. You can write unit tests in required files but the Mocha framework will execute this file directly.
5. Under the `scripts` in `package.json`, add this line: `"test": "node ./node_modules/mocha/bin/mocha"`
6. Open a terminal inside the project root and run `npm test` to perform the unit tests.

Of course, this wouldn't be the only way to set up Mocha. I'm sure there are methods that are far better than mine but this is what works for me so this is what this template uses.

---

## Usage

1. Clone this repository
2. Run `npm install` to download the unit testing suite.
3. Run `npm test` to perform the unit tests.

---

## Disclaimer

This demo project is licensed under CC0 1.0 Universal. This is just a personal template for Node JS unit testing under the [Mocha](https://www.npmjs.com/package/mocha) framework that I have made available for public reference. I do not claim any copyright over this template. This is not an official resource for the [Mocha](https://www.npmjs.com/package/mocha) or [Chai](https://www.npmjs.com/package/chai) libraries and I have no affiliation with their respective developers. I will release future versions of this template as the libraries are updated. I accept no responsibility for how you use this or what you do with it. I am perfectly aware that this is not the only way to use the [Mocha](https://www.npmjs.com/package/mocha) framework and I am completely open to any advice or feedback you may have.

---