---
layout: page
title: Projects
navigation: true
nav_order: 1
permalink: /projects/
---

## Projects I'm Cooking

### teeny_tiny_games - Terminal Game Collection

Forced myself to write silly TUI games in Python. Here's what I've built so far:

**Board games:**
- tic-tac-toe (98 lines, functional style, 3x3 grid with win detection)
- connect four (90 lines, OOP, 6x7 grid with ANSI colors and gravity physics)
- battleships (176 lines, 10x10 grid, random ship placement, dual-board rendering for 2 players)
- othello (207 lines, 8x8 grid with piece flipping and valid move detection)

**Arcade games:**
- snake (78 lines, WASD controls, wraparound edges, collision detection)
- tetris (234 lines, all 7 tetrominos, rotation matrix math, line clearing with garbage collection)

**Simple games:**
- hangman (55 lines, word list file I/O, 6 lives)
- rock paper scissors (78 lines, class-based, nice UI with box drawing characters)
- heads or tails (23 lines, basic probability)

**In progress:**
- blackjack (22 lines, only deck setup so far - still figuring out the rules to the game)
- text adventure (RPG with branching narrative)

Trying to  refactor all the games above into a unified library architecture. The goal is to extract the repetitive boilerplate (game loops, grid rendering, input validation, player switching) into reusable base classes.

Here's the repo if you're curious: https://github.com/craftsoldier/teeny_tiny_games

