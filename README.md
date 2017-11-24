# Flik Style Guide
Welcome to the Flik Style Guide. Here you will find a list of guidelines to follow when writing code or strings/documents for Flik.

## 1. Writing JavaScript/ECMAScript
When writing JavaScript or ECMAScript, here are a few guidelines.  

1. **Use arrow functions whenever possible.**  
Arrow functions are an aesthetically pleasing alternative to the old `function() {}` syntax.  
		Converting a function to an arrow function looks like this:
	```js
	const log = function(message) {
		console.log(message)
	}
	```
	```js
	const log = message => console.log(message)
	```
2. **Do not use semicolons.**  
	Omitting semicolons helps make our code look more minimal and clean.  
	Simply change
	```js
	let type = "message";
	```
	to  

	```js
	let type = "message"
	```
## 2. Writing
Our writing style is similar to the [material design writing guidelines](https://material.io/guidelines/style/writing.html).
1. **Use contractions when possible.**  
	`You can not view this image!` becomes `You can't view this image!`.
2. **Use American English, no extraneous "u"s.**  
	`colour, favourite, centre` becomes `color, favorite, center`.  
	`initialising, specialising` becomes `initializing, specializing`.
3. **Use active voice instead of passive voice when possible.**  
	`You have been blocked by Justin` becomes `Justin has blocked you`.
