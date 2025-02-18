Format an object to a .env:

```
import { dotEnvFormat } from 'dotenv-formatter';
const dotEnvString = dotEnvFormat({
  KEY: 'lol',
});
console.log(dotEnvString);
```
