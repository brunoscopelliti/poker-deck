# poker-deck

Basic french deck of poker cards.

The module exports an array of objects with `rank`, and `type` card's properties.

Note that the array was frozen using `Object.freeze` method. It can be used in the following way:

```js
const deck = require("poker-deck");
const gameDeck = Array.from(deck);
// gameDeck is not frozen
```
