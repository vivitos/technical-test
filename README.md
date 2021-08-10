# Technical test Gymlib

## Set up

Clone repository using git CLI:

```sh
git clone git@github.com:vivitos/technical-test.git
```

Install packages using yarn or npm:

```sh
# yarn
yarn
# npm
npm i
```

## Exercise 1

Given an array of strings, write a function to print groupd of anagram. Anagrams have the same letters in different order. The function should have the following signature:

```js
function groupAnagrams(words: string[]): void {
  //your code
}

groupAnagrams(["dog", "cat", "bat", "tac", "god"]);

/*
Expected output :
dog,god
bat
cat,tac
*/
```

## Exercise 2

Create a Fifo class that work as a FIFO stack.

- FIFO stands for First-in First-out, so the first element stacked should be the the first to quit it.
- The stack size should be configurable.
- This Fifo class should implement a method a `stack` method to stack a new item
