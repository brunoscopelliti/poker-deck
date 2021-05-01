# @botpoker/cards

Basic french deck of poker cards.

The module exports an array of objects with `rank`, and `type` card's properties.

Note that the array was frozen using `Object.freeze` method. It can be used in the following way:

```js
const cards = require("@botpoker/cards");
const gameCards = Array.from(cards);
// gameCards is not frozen
```
