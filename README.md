# SpockRockGame

This is a simple training app based on HTML, CSS, JS and external library  - [Confetti.js](https://www.cssscript.com/confetti-falling-animation/).
* Upon selecting an option (rock, paper, scissors, lizard or spock) the result is then compared with computer's choice (randomly chosen), based on the outcome the DOM is updated accordingly.
* Confetti.js library's functions are dynamically imported when they're required to make the confetti animation.
* Main game logic is stored in the <b>choices</b> object:
```
const choices = {
  rock: { name: "Rock", defeats: ["scissors", "lizard"] },
  paper: { name: "Paper", defeats: ["rock", "spock"] },
  scissors: { name: "Scissors", defeats: ["paper", "lizard"] },
  lizard: { name: "Lizard", defeats: ["paper", "spock"] },
  spock: { name: "Spock", defeats: ["scissors", "rock"] },
};
```


## Usage
Just browse to
<https://gabrielhangor.github.io/SpockRockGame/>

