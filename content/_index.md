---
title: Home
menu:
  - main
  - sidebar
weight: -270
---
```javascript
[] == ![]; // -> true

!!!

->

true == []; // -> false
true == ![]; // -> false

// According to the specification

true == []; // -> false

toNumber(true); // -> 1
toNumber([]); // -> 0

1 == 0; // -> false

true == ![]; // -> false

![]; // -> false

true == false; // -> false
```
Source: https://github.com/denysdovhan/wtfjs


> The voice of the intellect is a soft one, but it does not rest until it has gained a hearing.
> — Sigmund Freud