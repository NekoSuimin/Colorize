# Colorize
### Lighweight Node.Js library for colorized console output
#### I didn't publish this on npm, but you can use basic functions by including index.js in your project
```javascript
const { Colorize } = require('./index.js');
```
### Usage
Create new instanse of Colorize class: 
```javascript
const colored = new Colorize();
```
Output colored text in console by using color methods: 
```javascript
colored.green('Hello world');
```
Use random style from colored.styles: 
```javascript
colored.random('Hello world');
```
Every letter is colored in random color from colored.styles:
```javascript
colored.allColors('Hello world');
```
Also you can use custom escape sequense or style saved in colored.styles: 
```javascript
colored.styled(colored.styles.underline, 'Hello world');
```
