
# Re-résoudre une promesse ?


Quel est le résultat du code ci-dessous ?

```js
let promise = new Promise(function(resolve, reject) {
  resolve(1);

  setTimeout(() => resolve(2), 1000);
});

promise.then(alert);
```
