```
let id = Symbol("id");
let user = {
  [id]: 123
};

let clone = Object.assign({}, user);
clone[id]; // 123
```
