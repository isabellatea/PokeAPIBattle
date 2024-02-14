
# PokeAPI Battle
* **Level:** Intermediate
* **Description:** Utilizing PokeAPI, pull random pokemon and battle them to determine a winner.
* **Created By:** Stephanie Burgos (coach-stephanie)

Example Solution: https://coach-stephanie.github.io/pokebattle/

(Screenshot Coming Soon)

## Installation
Before running the PokeAPI Battle project, ensure you have the following installed:

  - Node.js: visit the official website (https://nodejs.org/en) to install

Once Node.js is installed, follow these steps to setup the project locally:

1. Fork the repository to your Github account
2. Clone the repository to your local machine using this command:
```
git clone https://github.com/username/PokeAPIBattle.git
```
3. Navigate to the project directory:
```
cd PokeApiBattle
```
4. Install the necessary dependencies using npm:
```
npm install
```
5. After installing the dependencies, start the development server by running:
```
npm start
```

## Lesson

### JSON Objects
JSON Objects are typically data sets of objects within a larger object.
Utilizing your knowledge of how to reference values in objects and arrays, you can access JSON data through deeper references.

### Objects and For-In Loops
Objects are data structures denoted by curly brackets, and key-value pairs.
```javascript
let myObject = {
  name: "bella",
  github: "isabellatea",
  number: 6,
  likesPuppies: true
  }
```

To reference a specific item in an object, use that item's key.
```javascript
myObject["name"] // bella
myObject["github"] // isabellatea
myObject["number"] // 8
myObject["likesPuppies"] // true
```
Note that you can reference a value by it's key using `myObject["KEY_NAME"]` or `myObject.KEY_NAME` if the key name is known.

To loop over objects, you can use a For-In Loop (mind that it's different than a for loop for arrays):

```javascript
for (var key in objectName) {
  //code to be applied to each value
}
```



### API Introduction & PokeAPI
[PokeAPI Docmentation](https://pokeapi.co/docs/v2.html)



## Challenges
* **Challenge One:**
  - Write the API call similar to *getRandomPokemonLeft* that gets a random Pokemon for the right side.
  - Write jQuery .click() functions to execute these API calls when their corresponding “Get Random Pokmon!” buttons are clicked.
  - Confirm data is being retrieve in the console.


* **Challenge Two:**
  - Utilizing the pokeData, create template strings with details of how you want each pokemon to be displayed by referencing data in it’s JSON object.
  - Append your template strings to their corresponding sides.
  - Help your neighbor! Teaching is an excellent way to test your own understanding.


* **Challenge Three:**
  - The page is quite basic looking… customize your page by adding your flair to the CSS!
  - We will be working on the “Battle” mechanics and general win/lose game design algorithms next week. If you feel that you want to start this now, feel free to do so :)  

## Game Mechanics
* **Random Pokemon:**
  - You must get a random pokemon on each battle side using the PokeAPI and put them to battle to determine the winner


* **Battle Mechanics:**
  - There is the possibility for a winner, loser, or a tie. The battle mechanics are up to you but there must be these three possibilities. In the example solution above, the battle is based solely on which Pokemon's attack stat is higher. Other battle mechanics may include summing up all base stats and determining which total is higher or finding the higher difference between the opponent's health stat and the attack stat of the other Pokemon.

  - There are several possibilities for battle mechanics but these are some suggestions for starting out, it can go much more in-depth such as to add moves, health bar, etc.





## Solution Gist
[All Files](https://gist.github.com/isabellatea/bad5b5e568d54dc94d9a48e26ef1fb0d)
