# An Introduction to Bitcoin

London Real Public Speaking notes: https://www.youtube.com/watch?v=z0zgngAH0DM
Pick one idea / subject
  - Take people on an emotional rollercoster
  - People will forget 99% of what you say and they'll remember 1 thing
  - Try not to promote yourself
  - Break things into small pieces

  - Non-verbal is 80% of effectiveness
  - Verbal is 20%

  - Speak slowly - important people speak slowly because they know what they're saying is important


## Understanding TCP/IP
TCP: Transmission Control Protocol
IP: Internet Protocol

TCP/IP is the basic internet protocol of the internet

Protocol: Rules and procedures used for communication

The reason why it's so hard to define Bitcoin is because it's constantly changing.

At its root, Bitcoin is a new type or protocol that allows value to be transferred between individuals.

"Users of bitcoin own keys that allow them to prove ownership of transactions in the bitcoin network, unlocking the value to spend it and transfer it to a new recipient. Those keys are often stored in a digital wallet on each user’s computer. Possession of the key that unlocks a transaction is the only prerequisite to spending bitcoins, putting the control entirely in the hands of each user." Mastering Bitcoin, introduction p3

# History / Introduction / Leadup
It's 2008, the world is melting down. Lehman brothers collapses, and we're told that the entire world economy is ready to implode.

Then the white paper is released

# Current events that are inspiring this technology
FBI wants backdoor into Apple http://www.motherjones.com/politics/2016/02/apple-tim-cook-fbi-hack-san-bernardino





# Funny / Interactive / Interesting
- http://isbitcoindead.com

- So far, the largest recorded transaction has been 150 million dollars which was transferred instantly and without any fees.
- List major vendors who accept Bitcoin
- https://blockchain.info/
- http://www.bitlisten.com/


# Bitcoin is/was
- Invented in 2008 under the alias of Satoshi Nakamoto
- Open-source, written in C++ (core) https://github.com/bitcoin/bitcoin
- like bittorrent - p2p
- Not JUST a money. It's important to think of Bitcoin as a technology and not a money. One of its most appealing use-case's right now is as a money, but there's much more potential
not a company

# Achievements and Disruptions of Bitcoin
- The field of economics has been shook with regards to the theory of money production, Mises regression theorem
- Solves the Byzantine Generals problem
- Doesn't put you at risk of identity theft, anonymous
- Similar to Linux vs IBM open-source vs closed-source -- Git vs CVS and Bitkeeper

# Current system
- We enable vendors to make "pull" requests to our data
- New system empowers us to make "push" requests only
- Ever system that touches credit cards has to be secured, firewall, encrypted, routine sweeps and scans for vulnerabilities -- PCI Compliance
- Credit cards are broken by design because the number and CCV2 is the secret key and gets exposed at every transaction. In contrast, a Bitcoin transaction can be broadcasted to the entire world without fear of compromising sensitive data (show blockchain.info at this point)

# Examples of how it's evolving
- 2 factor authentication (multi-sig)
- Majoir banks are now trying to jump onboard to take advantage of Blockchain technology
- https://ipfs.io
- OpenBazaar
- https://www.bigchaindb.com
- https://en.wikipedia.org/wiki/Named_data_networking#Current_State
  - Smart contracts
- Embedding Bitcoin transactions as emoji icons, or music lyrics. How? Take a given static character set (http://unicode.org/emoji/charts/full-emoji-list.html) and encode the Bitcoin transaction. As long as the person receiving the emoticons have access to a decoder script, everything will work
  - If they shut down twitter, I'll use Facebook, if they shut down Facebook I'll post it as a comment on Youtube. If they shut down Youtube I'll insert it into a jpg image on a website

 Take the hexadecimal representation of a bitcoin transaction, and encode it using the

# Reactions
- Governments trying to put an end to its anonymity
- Banks trying to "cleave off" the blockchain from bitcoin

# Bitcoin consists of:
1) A decentralized peer-to-peer network (the bitcoin protocol)
2) A public transaction ledger (the blockchain)
3) A decentralized mathematical and deterministic currency issuance (distributed mining)
4) A decentralized transaction verification system (transaction script)

# Must says
- Ask how many people have heard of bitcoin and how many people have used bitcoin

# Fundamental nature of Bitcoin
## 1) Deflationary
  - Fixed supply of 21 million coins by the year 2140 (MBC, intro p5)
  - Mimics gold in this respect
  - Every 4 years the amount of increase of bitcoins get cut in half -- the rate of "inflation" is deterministic

## 2) Decentralized
  - No honeypot for a single point of attack (recent IRS hack for example)
    - You've either been hacked or will be hacked  
  - Hayeks knowledge problem

## 3) Distributed

## 4) Distruptive
  - Subverts the very concept of national currency monopolies
  - A truly global currency, like gold in this matter, but better





# Misc Thoughts
 Blockchain tech isn't new. Blockchain is simply a comprehensive ledger. What's really interesting is a decentralized blockchain that has trust, security, and incentive structures build into maintaining it.















# Web Trends 2016 and Beyond

## IPFS (Interplanetary File System)
A content-addressable, peer-to-peer hypermedia distribution protocol. Nodes in the IPFS network form a distributed file system. IPFS is The Permanent Web.

Aiming for eventual direct browser integration

### Problems it tries to solve
1) Centralization
2) Location addressing -Host -> IP
  - The limiting feature here is that you can only communicate with a single host to retrieve data over the web
3) Latency problem -- can't go faster than the speed of light
4) Bandwidth problems -- congestion, interference, etc
5) Infastruction problems (Gov censorship, natural disasters)
6) Ubiquitous computing -- not using the web because of these problems but more so using it as a sync platform
7) Data is centralized. Gatekeepers hold the keys ultimately to the data we use everyday
8) Permanence -- Since we have centralization, if any link in the chain breaks the data could be lost forever. Internet Archive has been trying to solve this problem

### What we need
1) Decentralized access to data
2) Authenticated and encrypted data at rest
3) Offline access
4) Permanent
5) Faster



1) Sharing and transferring data between inter-planetary distances for the future

If a truly distributed web takes hold, we could see the days of centralized hosting providers completely eliminated.


The web should be distributed, not centralized -- offline first

Git + BitTorrent + Web = IPFS

### Merkle trees
In cryptography and computer science, a hash tree or Merkle tree is a tree in which every non-leaf node is labelled with the hash of the labels or values (in case of leaves) of its children nodes. Hash trees are useful because they allow efficient and secure verification of the contents of large data structures. Hash trees are a generalization of hash lists and hash chains.

The basic idea is that if you have some piece of data that is linking to another piece of data, you use the content itself as the link.

If you can break SHA256, you can run away with the entire value of the bitcoin network

Using cryptography to represent data. Meaning if the data changed, the has will change as-well.

Examples of technologies that uses Merkle Trees:
1) Git
2) Bitcoin


We say "The Web", but how much it is a true "web"?





"For the first time Ever, The bitcoin network has exceeded one Exa Hash/s, or approximately 10.8 ZettaFLOPS per second, according to bitcoinwatch.com’s aggregate metric. This makes the bitcoin network around three-hundred-thousand times more powerful than the world’s fastest supercomputer, the tianhe-2 — clocking in at ~34 PetaFLOPS, and over 43 thousand times faster than every supercomputer on the TOP500 list combined. In theory, the network could be repurposed to run a neural net AI about one hundred times as powerful as a human brain."

Tyson O'Ham, January 25, 2016 http://bitcoinist.net



# Talk about Alan Turing



# Questions
## What are the current problems that the web community is trying to solve?


# Things to remember to do
## Make slides available online
## Don't stay on .gif slides for too long. Gets annoying after ~5 seconds


# WiFi will become better -- more accessible -- making way for the internet of things
  - DSLRs
  - Raspberry Pi


Bitcoin has the "Network effect"


Misc videos that may be relevent:
https://vimeo.com/152889154
http://www.svds.com/ethereum-the-rise-of-the-world-computer/#.Vs3MJboMMl0.facebook
https://www.youtube.com/watch?v=4fjmnOQuqao
https://www.youtube.com/watch?v=AZ-tISX-7Cw



Snowden tweet: https://twitter.com/Snowden/status/700795657259393024

"Offline first"

Internet of Things

Egypt shuts internet down" http://www.nytimes.com/2011/01/29/technology/internet/29cutoff.html?_r=0
Mozilla https://advocacy.mozilla.org/encrypt/


Possible names:
  - CryptoLiberty.io
  - CryptoLiberty.io



.build
.digital
.io
.tech

crypto.digital


"Trustless"

The days of monopolies are past. We now live in a world where centralized authorities are no longer needed.
































# The state of affairs
So much change -- data overload
Things are changing faster than ever

Have we been going through an acceleration in the rate of change? Yes!

- Github created February 8, 2008
- JSConf 2009 Ryan Dahl gave his NodeJS talk that propelled the JavaScript language into the stratosphere in terms of popularity

What does this all mean? Web technologies are changing incredibly fast, and have been changing fast particularly in the past 8 years

Why are things changes quicker because of these?

W












What I won't be talking about:
1. IoT (Internet of things)
2. Increase in storage space, increased speeds, accessibility of internet
3. Proliferation of cat .gifs

I'm going to discuss the more philosophical changes that are taking place within the very foundations of the internet and how we think about P2P communications. Monumental shifts have been happening deep within the cyberpunk and hacking communities that will affect us all. Changes that will be more radical and unpredictable than TCP/IP itself.


# The Future Will Not Be Centralized -- 15mins
  What's the problem?

    Centralization has a tendency to create giant honeypots for potential adversaries to attack. Innovation and improvements are hamstrung by bureaucracy. It also paves the way for moral hazard and corruption. The most troublesome problem of all, is what Hayek called the Knowledge Problem.

    "The curious task of Economics is to demonstrate to men how little they really know about what they imagine they can design." - Friedrich Hayek, The Fatal Conceit 1988 4 years before his death in 92

    Examples of failed centralized digital networks:
      Napster
        - centralized company
        - centralized network

      Kazaa
        - centralized company
        - centralized software
        - centralized network

      BitTorrent (unstoppable p2p protocol)
        - decentralized network
        - no company
        - decentralized software

      Once before you could go after a single entity, now you had to go after individual users and make examples out of them to scare the public away from using these technologies

      - Bitcoin
        - Has a major network effect
        - Has curreny valuation
        - Not going into great detail about how Bitcoin or cryptocurrencies in general work because of time. What I do want to
          explain is the most important invention that Bitcoin has contributed which is the Blockchain. Pay attention because understand how the blockchain works is important to understanding where the internet it heading.

      - Describe what paper money used to represent (silver, gold) -- benefits of those

      Cryptocurrencies
        - The most important invention since the internet itself TCP/IP

      - Namecoin

    Benefits of Blockchain:
      - Immutability -- decentralized
      - Corruption Proof
      - Cryptographic security
      - Zero downtime -- distributed



# Distributed -- 15mins
  What's the problem?

    - Ethereum
      - Contains its own executable scripting language that can be run with every transaction
      - Uses "Ether" as its currency


    - IPFS
    - OpenBazaar
    - "Trustless"
    - ChangeTip


# Crypto -- 15mins
  What's the problem?
    The revelations Edward Snowden

    - Alan Turring (One of the founders of computer science)
    - Let's encrypt -- free https
    - Amazon -- certificate authority


    - Slock.it
      - Air BnB that is fully autonomous--functions without any human intervention

Private
Secured
Crypto
Cryptography

Ethereum could be the monster that slays Facebook and Google ... at least force them to change their revenue models


Bitcoin was also created in 2009


Decentralized Dropbox
  - Renting out HD space

https://blockstack.org
https://www.ethereum.org/
https://keybase.io/
