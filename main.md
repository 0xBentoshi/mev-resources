Hey! Welcome to this repo. I have organised all the mev stuff I've been seeing, and have also given a brief description where possible. 
I summarise the key points of each resource (video/blog/article) that I finish at my [substack](https://0xbentoshi.substack.com/). 
The ones I have not summarised yet have a star next to them. These summaries are part of a journal that tracks my mev journey -- from a (literal) noob to a (hopefully) profitable searcher.
Happy learning! 

### Meta Resources
These are some resources that aim to do the same thing I'm doing here--enable anyone to learn about mev. 
There might be an overlap between what you find in these resources and what you find in the rest of this document.
Please focus on doing and learning, and not choosing which resource to follow.
- [Flashbots Resources](https://docs.flashbots.net/flashbots-auction/other-resources)
- *[Daily Ape MEV](https://thedailyape.notion.site/MEV-8713cb4c2df24f8483a02135d657a221)
- *[0-1 Guide to MEV](https://calblockchain.mirror.xyz/c56CHOu-Wow_50qPp2Wlg0rhUvdz1HLbGSUWlB_KX9o) (i'm following this)

### Videos
- *[make $1m per month!](https://www.youtube.com/watch?v=lXq0eU8viFQ) kind of an intro to flashbots.
- *[Finding & Capturing MEV 101](https://www.youtube.com/watch?v=70WtsHtFd8Y) another intro to mev, ~30m in length.
- *[Understanding MEV on ETH](https://www.youtube.com/watch?v=6IxaLCPm6_E) an hour long episode
- *[Dip into the Mempool and MEV](https://www.youtube.com/watch?v=gi6MU6Xcmok) drippping with alpha ;)
- *[Interview with a Searcher](https://www.youtube.com/watch?v=6jfSlDvH77k) amazing mevintern interview, a must watch 
- *[Understanding MEV (Old Podcast)](https://www.youtube.com/watch?v=vCCYFSAdCFo) part of uncommon core's podcast on mev, one of the oldest vids on this
- *[MEV 2021 Year in Review](https://www.youtube.com/watch?v=V_wlCeVWMgk) quickly get up to speed on the (lots) that happened in mev in 2021

### Repositories
- *[Liquidation Bot](https://github.com/fxfactorial/liquidation-bot-fall-2020) this is good to learn how to think about doing liq. 
- *[Simple Arbitrage](https://github.com/flashbots/simple-arbitrage) simple arb bot, has a [video](https://www.youtube.com/watch?v=wn8r674U1B4) explainer too 
- *[Better Simple Arb Bot](https://github.com/jacksonConrad/better-simple-arbitrage) slight improvements from above
- *[Flashbots NFT Demo](https://github.com/flashbots/searcher-minter) has a demo application of flashbot to mint NFT.
- *[Liq. Sniping on PCS](https://github.com/Supercycled/cake_sniper) liquidity sniping on pancakeswap.
- *[Liq. Sniping on Uni](https://github.com/sszczep/UniswapSniperBot) uniswap sniper bot.
- *[Flashbots Master Repo](https://github.com/flashbots/pm) awesome repo
- *[Synthetix Arb](https://github.com/flashbots/mev-job-board/blob/main/specs/synthetix-link-wrappr.md) good insight into making creative strategies

### Threads 
- *[MEV on Solana](https://twitter.com/wireless_anon/status/1489689357955235841?s=20&t=ji2eCCploDSyhQtjMH2WiQ) not necessary for beginners
- *[Intro to JIT Liq. on uni_v3](https://twitter.com/ChainsightA/status/1457958811243778052) not necessary for beginners
- honestly there are soo many threads, I'd rather you spend time going through longer form material than threads to maximise learning. however, if you are a thread enjoooyer then check the meta resources for more threads 

### Articles 
- *[MEV Deep Dive](https://medium.com/@liamzhang/mev-a-deep-dive-part-1-3f389ef16d32) extremely well-written 2-part series. Beginner friendly.
- *[Hacking Blockchains](https://medium.com/immunefi/hacking-the-blockchain-an-ultimate-guide-4f34b33c6e8b) ease your way into learning mev.
- *[Snake in the Garden](https://hackmd.io/fvLQzbwVR-qZizmJvSnjOQ) Article on ArcherDAO (now rebranded to Eden). Just leave this for later, read other stuff first.
- *[Graph Algorithms and Currency Arbitrage](https://reasonabledeviations.com/2019/03/02/currency-arbitrage-graphs/) Interesting article on using graphs for arbitrage
- *[Architecture of Web3 Apps.](https://www.preethikasireddy.com/post/the-architecture-of-a-web-3-0-application) what the title says
- *[A Playdate with EVM](https://femboy.capital/evm-pt1) Amazing intro of sorts to EVM
- *[How tf Ethereum works](https://www.preethikasireddy.com/post/how-does-ethereum-work-anyway) don't want to read the yellowpaper? Read this
- *[Anatomy of a MEV Strategy](https://www.bertcmiller.com/2021/09/05/mev-synthetix.html) awesome article
- *[Backtest uni_v3 strats.](https://medium.com/coinmonks/a-real-world-framework-for-backtesting-uniswap-v3-strategies-88825abdcd17) skip if beginner

### Papers
- [Analysis of Uniswap Markets](https://arxiv.org/pdf/1911.03380.pdf) Best summarised [here](https://twitter.com/FloatngUpstream/status/1489730257309609985), basically gives an optimised solution to calc. path and amount of arbitrage.
- [Flashboys 2.0](https://arxiv.org/pdf/1904.05234.pdf) The holygrail of mev

### Other Stuff
MEV has 3 parts: 
- locate prey (get data-be it pending txs, pair-wise prices at various DEXs or anything else)
- see if it's worth chasing the prey (format the data to enter your logic, this logic is the logic of your strategy)
- go for the kill (if enough profit available, make calls to your smart contracts to execute smart contracts)

If you didn't get the above, don't worry. I haven't understood it enough myself to explain it succintly. The main thing here is your perserverance and you just not giving up. That's literally the only thing here. That's why there's few ppl in this space bec it "seems" intimidating. 

If I, a noob lvl 9000 coder can get on this journey, then so can you anon. First, you need to know the various tools needed (like nodejs for runtime, js for codign the strategy/logic, smart contracts that will deploy your strategy), then go through how other ppl have done it and then finally launch the shittiest v0 of your bot. Once this is done you will continue on your own.

Also, the mev community is absolute pogchamp. The reason I got into mev and coding in crypto is simply bec i was feeling a little lonely and craved a sense of community. I think I have found that here. Also, I love a good challenge, especially taking on something that looms in front of me like a tower. Feel free to ask *sensible* questions to the pogchamps in this space (I have a list on my Twitter if you want some names) and have fun. 

See you in the mempool, anon 😉
