# Blockchain
they have information, hash (block identidication) and previous hash block (with this each block is connected with the others blocks), it's a decentralized architecture.
<br />
<img src="images/1.png" /> <br />
<img src="images/2.png" /> <br />
<img src="images/3.jpg" /> <br />

## Hash
it is a block id, but there are many eyes see this. The hash is created with the block content, if the block contect is changed the hash will be changed too.
<br />
If this happen (hash change), this blok won't be connected with the others.
<br />
There is not a unique databases, each user has a copy of then.
<br />
If a user change his copy the community knows it.
<br />
The Miners perform the new blocks creation.

# Remix IDE
it is an online IDE: https://remix.ethereum.org/

```
HTTP vs HTTPS

Be careful with the https vs http domain. Remix stores edited files in localstorage of the browser. If your smart contracts are suddenly gone, look at the protocol.

In this course we work with http, not https. This is especially important later when we do private blockchains which require CORS to be setup correctly.
```

https://ethereum-blockchain-developer.com/2022-01-remix-introduction/01-setup-remix/