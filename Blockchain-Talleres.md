
# Blockchain stuff — Anders Brownworth’s Blockchain Demo

This is the best place that I’ve found that explains the blockchain technology with simple concepts, a couple of videos, and with a really cool online demo.

Quoting Brownworth, the Blockchain Demo is:
> A web-based demonstration of blockchain concepts.
> This is a very basic visual introduction to the concepts behind a blockchain. We introduce the idea of an immutable ledger using an interactive web demo .

Here is the post (2019/06) from the personal website where he explains a little bit about the demo with the videos.
[**Blockchain Demo - AndersBrownworth.com**
*I created a visual demo of blockchain technology which attempts to explain the technology by building up from simple…*andersbrownworth.com](https://andersbrownworth.com/cms/460/blockchain/demo)

## Following the video walkthrough with the demo

### Demo website

Here’s the demo website to play around with Hash, Block, Blockchain, Distributed Blockchain, Tokens and Coinbase.
[**Blockchain Demo**
*A live blockchain demo in a browser.*andersbrownworth.com](https://andersbrownworth.com/blockchain/)

Here, I’m going to follow Part 1 of this Blockchain 101 video to try to understand all of this stuff.

### Part 1: Blockchain 101 — A Visual Demo

<YouTube youTubeId="_160oMzblY8" />



### Hash

A digital fingerprint of the data that is written. The length of the hash is fixed no matter what information is stored.

![](https://cdn-images-1.medium.com/max/2316/1*f3cbKp8uQ8cbJhAkEKXe1w.png)

### Block

The hash includes Block (number), Nonce (another number), and Data.

When the data is empty it has a particular hash (note the initial 4 zeros): 0000f727854b50bb95c054b39c1fe5c92e5ebcfa4bcb5dc279f56aa96a365e5a

![](https://cdn-images-1.medium.com/max/2316/1*xSWRICMqo9m49aqS1bgLhQ.png)

When some data is added the hash changes to a particular number. The box turns red because the Nonce number does not match the hash (does not have the 4 zeros at the beginning), it is not a valid or not a signed block.

![](https://cdn-images-1.medium.com/max/2316/1*WLhoAAZ5vJr3Fy5wO5Alag.png)

The Nonce number can be changed until the hash begin with 4 zeros (0000). This process could be done by manually change a number from 1, 2, 3 and so on. The number could be found by this method taking the required time or machine, but it could be just too long.

![](https://cdn-images-1.medium.com/max/2316/1*n3WDkkc10tBMDNShB5gFmw.png)

![](https://cdn-images-1.medium.com/max/2316/1*2igVq1OtLWotlIPU5l7GlA.png)

If the Mine button is pressed, the Nonce iterates until there’s a match (the hash begins with 4 zeros 0000…). In this case, the block is verified for the Nonce 1771.

![](https://cdn-images-1.medium.com/max/2316/1*VMGb0OVOvb2lj_KQa_nAPw.png)

### Blockchain

Now, there could be a chain of this blocks, from Block #1 to Block #5. Each one connected with the previous one

![](https://cdn-images-1.medium.com/max/2890/1*oa50GDAXjB6JQwsy8a_GYw.png)

![](https://cdn-images-1.medium.com/max/2890/1*3odBS709nVRSmRzgHDSvlw.png)

![](https://cdn-images-1.medium.com/max/3814/1*AGhlkCPQ4gFA75KK3CXadA.png)

If there’s a change in Block #4 from it’s initial empty state, the block will be invalid and the chain will be broken. The previous hash in Block #5 would not match the hash from Block #4, but not affecting the Block #3, #2 and #1.

![](https://cdn-images-1.medium.com/max/3814/1*ZzL0QFglVGJjk1x0HgUiHg.png)

If the Block #4 is mined, a Nonce will be found and validate the current Block but not the next one in the chain.

![](https://cdn-images-1.medium.com/max/2836/1*yg3GfpmFBVLnVekZBacXkQ.png)

If the Block #5 is mined, it will valid by matching the hash of the previous block.

![](https://cdn-images-1.medium.com/max/2836/1*t7LBys9ebOk2njAWWsT9Uw.png)

### Distributed Blockchain

Now, there can be a distributed chain of this blocks with some peers with identical blocks.

![](https://cdn-images-1.medium.com/max/2836/1*jYqfrXGsLRl_jlyc6u-KKw.png)

![](https://cdn-images-1.medium.com/max/2836/1*0T_2hm_MMBVOAmVMdyxO8w.png)

![](https://cdn-images-1.medium.com/max/2836/1*-xm8__zzd_ndcMawfvnudQ.png)

If a change is made in Block #4 of Peer B, it will affect this particular Block, but won’t affect the other blocks nor peers

![](https://cdn-images-1.medium.com/max/2836/1*Ih4UFCYgH2cGGv0m6clVgA.png)

If Block #4 and Block #5 are mined, both blocks will be valide a the whole chain will be ok. However the hash in Block #5 in Peer B is not the same as Block #5 in Peer A nor in Peer C.

![](https://cdn-images-1.medium.com/max/2836/1*74LfPGRO_wgP7DRfZJsWpA.png)

![](https://cdn-images-1.medium.com/max/2836/1*ITyxhSqSe5bGyJ_D8l2LFQ.png)

By having a distributed blockchain a change in the past can be noted and traced by examining the blocks. Next, we can do a Token on a blockchain.

### Tokens

If more relevant information where to be stored, for example a list of transactions like the ones below, it could be relevant to keep track of them and know if at a certain point a change has been made that breaks the chain. This is making a Token on a blockchain.

![](https://cdn-images-1.medium.com/max/3756/1*UiNZqt9BNRgT6GDoZLDxnQ.png)

A change is made in the blockchain. This is the point of keeping track of stuff happening in the past by using a blockchain to remember tokens.

![](https://cdn-images-1.medium.com/max/3756/1*FVLBuAuYj0h30T3-vBEnPQ.png)

But up to this point, the system does not know if Darcy has a particular amount of something, the only thing that is known is that D has made a transaction to B.

### Coinbase Transactions

Now a coinbase transaction is added to the blocks. An initial amount is registered to A in Block #1 and then a couple of transactions are made in the blockchain.

![](https://cdn-images-1.medium.com/max/2858/1*7WTLw2aXD3o0NpRJIwJklQ.png)

A block could be examined to check that a person has the amount to give to another one, since it can be traced by the hash (and peers) if something is weird and does not match.

![](https://cdn-images-1.medium.com/max/3800/1*GQE2LukHs4zN_dtD8suzCw.png)

## Part 2: Blockchain Demo: Public / Private Keys & Signing

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/xIDL_akeras" frameborder="0" allowfullscreen></iframe></center>

Now we play around with Public/Private Key Pairs, Signatures, Transactions and Blockchain.

### Public / Private Key Pairs

The Private Key is meant to keep secure and not shared. The Public Key can be shared but can’t be used to trace back to the Private one.

![](https://cdn-images-1.medium.com/max/2250/1*-rvYO460VkMO7sYVLKt0BQ.png)

### Signature

A message has been added. This message has a particular private key.

![](https://cdn-images-1.medium.com/max/2250/1*VY1kYk2CSbDQBQZ06YhAkw.png)

If we sign it, it creates a message signature.

![](https://cdn-images-1.medium.com/max/2250/1*JPovFhEjRcv28FZavQntrA.png)

If we share the public key to another person, the message can be verified with the match of the public key and the signature.

![](https://cdn-images-1.medium.com/max/2250/1*oksJn8X6L_6pWU39yIqwaA.png)

### Transaction

We can make a transaction of $20.00 from a particular public key to another public key. The private key can be used to sign the message.

![](https://cdn-images-1.medium.com/max/2250/1*wAyR_DeWSTBn_N8CunL3UQ.png)

![](https://cdn-images-1.medium.com/max/2250/1*k2CbiVKYj2bZt7yymgmZdg.png)

By hitting sign, we get a message signature. The signature can be checked against the public key to see if the private key behind it signed this message.

### Blockchain

The next step is to use this in a blockchain.

![](https://cdn-images-1.medium.com/max/3800/1*aBG84M_adKKADYCxz52GJQ.png)

Here, there are not names, just public keys sending stuff to another public key with a message signature.

![](https://cdn-images-1.medium.com/max/3800/1*I-UxY_U12o-VDqYOaLYqdg.png)

If there’s a change in the transaction, in Block #5, it breaks the block and the signature, now the signature is not verified.

![](https://cdn-images-1.medium.com/max/3800/1*PsbD8ehj8rON5hNu9oXRQg.png)

A miner could take this altered block and re-mine it, they are going to end up with a signed block (cool) but the signature is still invalid. This is because the miner has no access to the private key, just the public key, so the right signature can’t be made up.

![](https://cdn-images-1.medium.com/max/3800/1*8e0bvf-NCOO_KFFcwGlNDQ.png)

In this way, the transactions can be protected with public/private keys from any interference. Makes sense, since in order to create a new address (public key) we can come back and create another random number (private key) without going to a centralized authority to create this key pair.

Its seems like this can be a somewhat efficient way to keep track of stuff or handling agreement on what has happened in the past.

Definitely what I have done here is very simplified, leaving a lot of stuff behind that I have no idea whatsoever, but it helped me to understand a little bit of what is going on with this.

I invite you to do this on your own following the highly recommend videos of Brownworth.

I hope this was helpful and thank you for reading it.
> BTC: bc1qqmpwwn5lsvh8vfcu2m5vpre3fjezruay0kzgzh
> ETH: 0x2400AC8BE2a0392b80d5425e663aB306EaADC385
