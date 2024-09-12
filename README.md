# Shreyesh Chennagouni
### Badminton
Badminton offers a unique blend of __physical exercise__ and **mental challenge** that keeps players engaged. It is an __intense__ sport that combines agility, precision, and strategy.

---
#### Player Ranking
1. Shi Yuqi
2. Viktor Axelsen
3. Lee Zii Jia
4. Li Shifeng
5. Anders Antonsen
#### Places you can play the sport
* Badminton Court
* Playground
* Backyard
* Garden

[My favourite Dish](MyDish.md)

---
### Favourite Quotes
> "I’m afraid of heights. I’m also afraid of widths. I have a lot of fears."
> 
> "It’s amazing that the amount of news that happens in the world every day always just exactly fits the newspaper."
> 
> _Jerry Seinfeld_

---
### How to Update an existing file in Node.js
Add to an existing file’s contents without overwriting the file and only updating at the end.
~~~

const fileSystem = require('fs');

const updateFile = (fileName, text) => {
	fileSystem.appendFile(fileName, text, (error) => {
		if (error) throw error;
		console.log('Updated the file!');
	});
};  
~~~
[Snippet Source](https://stackoverflow.com/questions/10685998/how-to-update-a-value-in-a-json-file-and-save-it-through-node-js)
