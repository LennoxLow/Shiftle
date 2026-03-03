# Shiftle

A Wordle clone with a twist — the target word can shift as you play.

## How to play

Guess the 5-letter word in 6 tries. After each guess, tiles show:

- 🟩 **Green** — correct letter, correct position
- 🟨 **Yellow** — correct letter, wrong position
- ⬛ **Grey** — letter not in the word

## The twist

If your guess matches fewer than 2 letters (green or yellow combined), the target word shifts to a different word — but any green positions you've already locked in are preserved. The word can keep shifting until you're cornered into the answer.

## Word list

Uses Donald Knuth's Stanford GraphBase list of 5,757 common five-letter English words.

## Running

Just open `index.html` in a browser. No dependencies, no build step.
