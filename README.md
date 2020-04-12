# Example

```shell
$ npm install js-words --save

```

```javascript
const { sensitiveWords } = require('js-words');

// ES2015 modules
import { sensitiveWords } from 'js-words';


const filtered = sensitiveWords(
  'The new Apple MacBook pro will have a touchbar', ['pro', 'touchbar']
)

console.log(filtered)
The new Apple MacBook ****** will have a ******
```