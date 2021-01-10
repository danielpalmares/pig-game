<h1 align="center">
  PIG GAME 🐷
</h1>

<p align="center">
  <a href="#screenshots">Screenshots</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#status">Status</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#pre-requirements">Pre-requirements</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#instructions">Instructions</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rules">Rules</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#license">License</a>
</p>

---

<p align="center">
  Pig Game is a dice game in which the first who scores 100 or more points, wins. 🏆 
</p>

<p align="center">
  <a href="https://dann-pig-game.netlify.app/" target="_blank">
    <img alt="Demo on Netlify" src="https://github.com/danielpalmares/omnifood/blob/master/.github/demo-on-netlify.png">
  </a>
</p>

---

## Screenshots

![Pig Game](https://github.com/danielpalmares/pig-game/blob/master/.github/pig-game-1.png)
![Pig Game](https://github.com/danielpalmares/pig-game/blob/master/.github/pig-game-2.png)
![Pig Game](https://github.com/danielpalmares/pig-game/blob/master/.github/pig-game-3.png)

---

## Status

Project completely done! ☄️

## Pre-requirements

Before getting started, you will need to have installed in your machine these tools: 

- [Git](https://git-scm.com)

Besides that, it is a good idea to have a nice text editor like [VSCode](https://code.visualstudio.com/)

## Instructions

```bash
# Open the cmd/terminal and clone this repository
$ git clone <https://github.com/danielpalmares/pig-game>

# Go to the project folder
$ cd pig-game

# Open the index file with Live Server

# Running on port:3000
```

If you don't have the Live Server extension installed, check this link [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

## Technologies

These technologies were used in the project:

- [HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

## Rules 

#### Normal mode ❄️

- The game has 2 players, playing in rounds.
- In each turn, a player rolls a dice as many times as he whishes. Each result get added to his **ROUND** score.
- **BUT**, if the player rolls a 1, all his **ROUND** score gets lost. After that, it's the next player's turn.
- The player can choose to 'Hold', which means that his **ROUND** score gets added to his **GLOBAL** score. After that, it's the next player's turn.
- The first player to reach 100 points on **GLOBAL** score wins the game.

#### On Fire mode 🔥 (ACTIVE)

- A player looses his **ENTIRE** score when he rolls two 6 in a row. After that, it's the next player's turn. 
- Players can set the winning score, so they can change the predefined score of 100. 
- There are two dices now. The player looses his **CURRENT** score when one of them is a 1. 

## License

This project is under the MIT license. See the archive [LICENSE](https://github.com/danielpalmares/pig-game/blob/master/LICENSE) for more details.
