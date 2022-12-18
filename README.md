## Info

Tabby, a new Scratch API implementation. **This is CURRENTLY a WIP (work in progress)**
This library isn't entirely functional nor production ready as of right now.

## Implementation Progress
- [x] Session
- [ ] Cloud WSS
- [ ] Proxy API
- [ ] Comments API
- [ ] Projects API
- [ ] Users API
- [ ] Explore & Search API's

## Example Usage

Create a session with Tabby:

```js
import { Session } from "tabbykat";

const tabby = new Session({ username: "ScratchCat", password: "catsarecool" });
tabby.on("authenticated", () => console.log("Authenticated with Scratch! :D"));

tabby.login();
```
