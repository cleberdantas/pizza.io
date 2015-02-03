# pizza.io: The hacker way of ordering pizza

> pizza.io is a tool that allows you to order pizza directly from the command-line, you can even integrate it with your build server if you want. 


## Install
First, make sure that you have Node and Npm installed. 
In other words, type this:

```sh
$ node --version
```

If that works you are good to go.

```sh
$ npm install --global pizza.io
```


## Usage

```sh
$ pizza.io init
```
This will generate a file in your working directory, our delicious Pizzafile.js

```js
module.exports = function(pizza) {

  pizza.ingredients({
  	sauce: 'pomarola',
    toppings: ['cheese', 'olive', 'basil'],
    size: 'big'
  });
};
```
You can add more toppings if you want.

```js
$ pizza.io toppings black pepper
```
And when you are ready to go, you know, just order.

```js
$ pizza.io ordernow
```

## Help

```sh
$ pizza.io --help
```

## Can I contribute?

Of course. We want contributions to improve the project. If you're uncertain whether an addition should be made, feel
free to open up an issue and we can discuss it.


## License

MIT © [Cleber Dantas](http://www.cleberdantas.com)

## PS

Of course this is a joke :D
