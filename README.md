# Technical test Gymlib

## Set up

Clone repository using git CLI:

```sh
git clone ...
```

Install packages using yarn or npm:

```sh
# yarn
yarn
# npm
npm i
```

## Excercise

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
