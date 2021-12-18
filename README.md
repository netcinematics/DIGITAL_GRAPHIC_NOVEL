# DIGITAL_GRAPHIC_NOVEL
GOAL: create a Digital Graphic Novel Series on the BLOCKCHAIN!

Sounds easy enough, what could be so difficult? Well, it isn't easy. With all the visuals, story and audio complete all that remains is for the CINEMATIC to be uploaded to the BLOCKCHAIN. Where a massive expanse of Web3, DApp, and Crypto technology awaits us.

## Web3 DApp and Crypto

The Web3 ecosystem is actually vast. Evaluating which technologies exist and which fit the needs of the project - is exhaustive. Here is a short list of the preferred technology stack (below). 
----
### PURPOSE
The PURPOSE of this project is to CREATE A PRECISE CONTRACT and Web3 DAPP, CAPABLE OF EXTENSIBILITY of product - without cost of blockchain storage.  
----
### TECH STACK (so far)
- OpenSea
- Polygon (on Matic) / ETH on Ethereum blockchain.
- Web3 / ethers
- Hardhat / Truffle 
- Hardhat Network / Ganache-CLI
- Unit tests in Mocha / Chai
- OpenZeppelin / ERC721 or ERC1155
- Solidity in Remix and VSCode (plugin)

In addition there are a plethora tools still under evaluation:
- https://mintnft.today/
----
### GOALS of Graphic Novel Series
Straight to the point - OpenSea does NOT do what I need it to do. The Graphic Novel Series is NOT going to be CryptoKiddies Or Vfriends. It is supposed to be a MOVIE, GAME, BOOK, APP on the Blockchain. That mints based on countdown dates, and reveals content automatically each month. Hosted (for FREE) on IPFS and GitPages, etc. Looking at current SMART CONTRACTS, it is NOT CLEAR what is needed to modify ERC721 OR ERC1155 to meet the needs.

> 1155 Upgradeable Proxy Contract.

      It seems like a proxy may be needed to add items over time. But also this might be too much, and it might be able to work with just a mapping. So that is the purpose of this project to TEST different approaches to see what a simplified SOLUTION might be.
      
> Web3 METANET
      One of the coolest innovations so far was the SOLUTION to OpenSea limitations. Using OpenSea GET requests and IPFS links and a cID (content Identifier) it was possible to LINK ALL FUTURE CONTENT EXTENSIBLY through that single ID. It is a github proof of concept BASED in Web JS, that COMBINE CONTENT based on cID, called the METANET. The BEST PART, is that it enables many different UI/UX interactions and experiences <i>in addition</i> to ALL CONTENT being available to PURCHASE and COLLECT on OpenSea. These enhanced UI/UX EXPERIENCES, are then combined to create a THREAD of EPISODIC CONTENT that can be traversed like any social media platform, SCROLL or LINK. Called the <b>METANET</b>.
      
> POLYGON Layer2 BLOCKCHAIN
       The most challenging part of the project so far is developing on Polygon, navigating the many surprises between ETH and MATIC. It is NOT SEAMLESS. After being stumped of how ETHERIUM Chain Matic does not work on OpenSea, and that POLYGON Chain Matic is required. Because COINBASE auto"matic"ally give the wrong one. And that Transak does not work in my country. And that Crypto.com does transfer the correct MATIC, but that it was at a HIGHER COST to purchase than COINBASE. I was pleasantly surprised to see yet another wrinkle in the PURCHASE of the Polygon NFT on OpenSea... requires WETH (not Matic). Shocker. That is in addition to the confusions present in navigting the Polygon Mumbai Test Network, and the super strange FAUCET FUNDING to try and test it out. Learning all of this... was NON-TRIVIAL! But I loved it anyway. 
       
### REQUIREMENTS

       What seems to be missing, at time of writing, is a PRECISE WAY TO DEVELOP the SMART CONTRACT. I'm drowning in a "sea" of OpenZeppelin variations and it is not even clear if I've arrived at a contract that works - or if it has nefarious bugs with re-entrancy or addition overflow. 
       
       > How is Solidity "more secure", and "Turing Complete" is desirable - while it includes Big Number Overflow and Underflow? This was an additional huge shock. Similar to the FALLBACK function for contract that do not implement RECEIVE. To be honest, this feels tacky. Another glaring hurdle in this cloud of confusion, in withdraw() implementation. It needs to be implemented to actually get the profits? And if it is left out - no money? Permanently? But when is it needed? It seems like that is only an issue for 721 not 1155? Why is this not a Standard mixin? Answers like that... are NON TRIVIAL to find. And Im not about to tell you "That's all!" Because I'm getting tired of seeing that, at the bottom of many tutorials. Like a rite-of-passage into the CRYPTO-WURLDZ - "That's all folks", BugsBunny. I assure you, in CRYPTO... "That is NOT all!"
       > How is there no standard CREATOR slot. I find this amazing that CREATOR, DATE, and LICENSE is not included... in a SMART CONTRACT? The answer to that is equally hilarious - "they are expensive". As a FULL STACK ARCHITECT familiar with DCMA and COPYRIGHT - word to the wise - seems like an oversight. But, I try not to laugh that a completely useless "Ticker Symbol" is included in the 721 standard. Sometimes I just cry myself to sleep (late) at night - and "That's it!". 
       > DATES will be handled on a NODE.js server - because DATES are messed up on Solidity? Also concatenating Strings is weird on Solidity? Seems like this great new technology, has another iteration waiting in the wings (please just use JS - what is the problem). Number overflows and underflows are... (may I say) ridiculous, for things as important as contract. I am 20 year vetran from C/C++/C# and others - so I can say that. 
       > How have we not come up with something ... closer to perfect ... than this? NFTs appear to be in an extreemely narrow use case. Please contact me at netcinematics (at) protonmail.com if you have the answers. I evaluated CARDANO, and SOLANA and found similar quirks there. Not a fan of the Daedalus wallet - just saying. Can anyone even spell it! Can we find a MORE CRYPTIC name... that I can barely spell to be MY WALLET please? Wait. Don't answer that.
---       
       
