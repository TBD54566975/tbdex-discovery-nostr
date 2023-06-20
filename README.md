# tbDEX discovery using nostr

PFI (Participating Financial Institutions) need a way to advervise their wares to the world. This project is a simple example of how to use the nostr API to do that.

Nostr is a permissionless protocol (with existing "relays" around the world) that can be utilised for this today.  

## Introduction

It is possible to use the nostr protocol directly from browsers. The example `customer.html` shows how to do that: where you can subscribe to advertisements from a PFI advertising a currency pair (and thus obtain their DID). Once you have their DID you can then issue Request For Quotes and other tbDEX protocol activities. 

From the PFI perpective, publishing or advertising is simple: an event of a certain type in a specified format can be relayed around. 

You can try this by opening `customer.html` in a browser, and then opening `pfi.html` in another browser. Start listening on the customer side, and then publish on the PFI side. You should see the event appear on the customer side in the console in the browser. 

## Try it out: 

1) Launch <a href="https://raw.githack.com/TBD54566975/tbdex-discovery-nostr/main/customer.html" target="_blank">the client</a> and open the console, and start listening. 
2) Launch <a href="https://raw.githack.com/TBD54566975/tbdex-discovery-nostr/main/pfi.html">PFI side</a> and publish an event with a chosen currency pair, and note that the client will see matches in the console.


## Credits

This project was originally based on the example of accessing nostr via vanilla JS: https://github.com/supertestnet/vanilla-js-nostr 


## Project Resources

| Resource                                   | Description                                                                    |
| ------------------------------------------ | ------------------------------------------------------------------------------ |
| [CODEOWNERS](./CODEOWNERS)                 | Outlines the project lead(s)                                                   |
| [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md) | Expected behavior for project contributors, promoting a welcoming environment |
| [GOVERNANCE.md](./GOVERNANCE.md)           | Project governance                                                             |
| [LICENSE](./LICENSE)                       | Apache License, Version 2.0                                                    |
