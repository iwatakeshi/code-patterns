# How to push and pop whole numbers

## Pushing whole numbers

### Pushing a single number

```js
let sum = 0;
let value = 1;
sum = sum * 10 + value
// sum will equal to '1'
```

### Pushing a list of numbers

```js
let sum = 0;
let values = [2, 3, 4];

values.forEach(value => sum = sum * 10 + value);

// sum will equal to '234'
```


## Popping whole numbers

### Popping a single number

```js
let value = 25;

let last = value % 10;

// last is currently '5'

value = Math.floor(value / 10); /* Result must be an integer. */

// value is currently '2'

last = value % 10;

// last is currently '2'

value = Math.floor(value / 10);

// value is now '0' and we're done.

```
