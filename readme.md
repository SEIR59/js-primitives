# JavaScript Arrays

## Prereqs:
* Arrays
* strings

## Getting Started

* Fork and clone this repository
* Create a file in the `js` subdirectory named `app.js`
* Make a `index.html` and `style.css`
* Be sure to link all your files to your `index.html`
* Write your solution in that file
* Run the file by typing `open index.html`

## Exercises

1.) Find the last name in the following array:

```js
const friends = [
  'Moe',
  'Larry',
  'Curly',
  'Jane',
  'Emma',
  'Elizabeth',
  'Elinor',
  'Mary',
  'Darcy',
  'Grey',
  'Lydia',
  'Harriet'
];
```

2.) Sort the list of `friends` above in alphabetical order.

3.) There is a list of names in a string below. How could we sort them alphabetically? Hint: use string and array methods.

```js
var friends = 'Moe,Larry,Curly,Jane,Emma,Elizabeth,Elinor,Mary,Darcy,Grey,Lydia,Harriet';
```

4.) List all the `friends` above in reverse alphabetical order.

5.) We have two lists of friends below. Combine the two arrays into one array, then sort them alphabetically.

```js
const myFriends = [
  'Rickon',
  'Meera',
  'Hodor',
  'Jojen',
  'Osha',
  'Rickard',
  'Maester',
  'Rodrik',
  'Jory',
  'Septa',
  'Jon'
];

const yourFriends = [
  'Bilbo',
  'Boromir',
  'Elrond',
  'Faramir',
  'Frodo',
  'Gandalf',
  'Legolas',
  'Pippin'
];
```


6.) I have a list of favorite foods below. If `Popcorn` is my favorite food and `Potato chips` my second favorite, then how would you find the rank of another food? Try finding the rank of `Pho`.

```js
const foods = [
  'Popcorn',
  'Potato chips',
  'Shrimp',
  'Chicken rice',
  'Poutine',
  'Tacos',
  'Toast',
  'French Toast',
  'Crab',
  'Pho',
  'Lasagna',
  'Brownie',
  'Lobster',
  'Donuts',
  'Ice cream',
  'Hamburger',
  'Sushi',
  'Chocolate',
  'Pizza'
];
```


7.) I made a mistake with my favorite foods. How can I find the index of `Donuts` and remove it? **(Hint: look up `splice`)**

8.) My friends want to know what my `5`th to `10`th favorite foods are. How would I find these foods?

9.) Change the word "Space" to the word "Spice".

```
let word = "Space";
```

10.) **BONUS** - Here are a list of `ages`

```js
const ages = [83, 53, 37, 29, 60, 30, 66, 19, 59, 41, 9, 64, 19, 80, 24, 53, 70, 1, 53, 40, 92, 4, 71, 65, 8, 2, 51, 80, 94, 37, 80, 64, 19, 6, 14];
```
find the `median` age. The median is the number that is halfway into the sorted set. To remember the definition of a median, just think of the median of a road, which is the middlemost part of the road.

---

## Licensing
1. All content is licensed under a CC-BY-NC-SA 4.0 license.
2. All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.
