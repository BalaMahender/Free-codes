---
id: 5900f4951000cf542c50ffa8
title: 'Problem 297: Zeckendorf Representation'
challengeType: 1
forumTopicId: 301949
dashedName: problem-297-zeckendorf-representation
---

# --description--

Each new term in the Fibonacci sequence is generated by adding the previous two terms.

Starting with 1 and 2, the first 10 terms will be: 1, 2, 3, 5, 8, 13, 21, 34, 55, 89.

Every positive integer can be uniquely written as a sum of nonconsecutive terms of the Fibonacci sequence. For example, 100 = 3 + 8 + 89.

Such a sum is called the Zeckendorf representation of the number.

For any integer $n>0$, let $z(n)$ be the number of terms in the Zeckendorf representation of $n$.

Thus, $z(5) = 1$, $z(14) = 2$, $z(100) = 3$ etc.

Also, for $0 &lt; n &lt; {10}^6$, $\sum z(n) = 7\\,894\\,453$.

Знайдіть $\sum z(n)$ за умови $0 &lt; n &lt; {10}^{17}$.

# --hints--

`zeckendorfRepresentation()` має повернути `2252639041804718000`.

```js
assert.strictEqual(zeckendorfRepresentation(), 2252639041804718000);
```

# --seed--

## --seed-contents--

```js
function zeckendorfRepresentation() {

  return true;
}

zeckendorfRepresentation();
```

# --solutions--

```js
// solution required
```
