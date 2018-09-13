# Example

```
$ npm install sensitive-words-luke --save
```

```javascript
const { sensitiveWords } = require("sensitive-words");
// ES2015 modules
import { sensitiveWords } from "sensitive-words";

const filtered = sensitiveWords(
    "The new Apple MacBook Pro will have a touchbar",
    ["pro", "touchbar"]
);

console.log(filtered);
// The new Apple MacBook ***** will have a *****
```
