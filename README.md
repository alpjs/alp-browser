# alp-browser

[![Greenkeeper badge](https://badges.greenkeeper.io/alpjs/alp-browser.svg)](https://greenkeeper.io/)

Framework based on ibex.
Alp requires node v5 or higher


```js
import Alp from 'alp-browser';

const app = new Alp();
await app.init();
app.servePublic();
app.catchErrors();
app.useRouter();
app.run();
```
