---
title: "Startup Guide"
date: 2021-12-20T10:00:48-08:00
draft: false
style: "style5 invert orient-right content-align-left image-position-right onload-image-fade-in onload-content-fade-right"
subtitle: We have put together a guide that contains some helpful steps and guides to get you up and running with Bitcoin.
image: "/images/map.webp"
button:
  label : "Back Home"
  link : "/"
---

# Purchase Bitcoin

To purchase your Bitcoin, consider using either Swan Bitcoin, Strike or both. 


## Swan Bitcoin

Swan Bitcoin is a low cost web browser option (0.99% fees) that allows you to purchase via one time purchase (min $100) or via a regular automated purchase (min $10) with a link to your bank account(s). For purchasing with a linked bank account, there is an initial maximum limit of $5000 per day that increases with usage. Larger amounts (up to $10,000,000) can be purchased by sending a bank wire to your Swan account. Bitcoin purchased is custodied for 10 days and then is free to move to your private wallet.

If you want to get started with Swan, you can use this link to get $10 free for signing up. By using this link you can help support us - it won't cost you anything extra, and Swan will pay us a portion of the transaction fee that you pay them: [swanbitcoin.com/pleberean](http://swanbitcoin.com/pleberean)


## Strike

Strike is an app (iOS and Android) that provides a $0 fee ability to purchase Bitcoin with a $0.50 minimum, but limits your ability to deposit cash from your bank account to a maximum amount per week (increases with usage). Bitcoin can be immediately sent to a private wallet upon purchase. When you fund your strike account (which instantly debits a linked bank account), the money will sit in USD. From there, you can pay to:
- Another Strike user (similar to venmo/paypal)
- A Bitcoin on-chain address (useful to send your USD straight to cold storage as BTC)
- A Bitcoin lightning invoice

Here is a link to get $5 free when signing up for Strike: [https://invite.strike.me/8G3IWS](https://invite.strike.me/8G3IWS)

Video guide: 
* Strike {{< youtube id="4-vJ7zZQ4wU" class="youtube-embed" >}}

We would recommend avoiding using large exchanges like BlockFi, Binance, Coinbase, Kraken, or Gemini to purchase Bitcoin. There are several reasons for this, both philosophical as well as practical. These large exchanges charge significantly higher fees than the options mentioned above, and they also facilitate the degenerate trading of worthless “altcoins”, effectively running a meme-coin casino. Swan and Strike are both built to help users save their life savings in Bitcoin only, and are explicitly not built for trading (Swan doesn’t even have a sell button!)

---

# Self-Custody Your Bitcoin

After purchasing your Bitcoin, the next step is to change the ownership of your Bitcoin to a private key controlled by a wallet. Bitcoin is NOT stored on any device and therefore a wallet is a poor name. Think of it as a device that allows for safe, convenient storage of your private key that authenticates your Bitcoin ownership on the distributed ledger. An example I often use is a (unforgeable!) wax signet ring - anyone can create a transaction, but nobody will accept it unless it has been signed by the corresponding ring. 

Learning how to protect your money by holding your own private key is an important step for all new Bitcoiners. We recommend using either a Hot Wallet such as Muun or BlueWallet on your phone or a Cold Wallet that is disconnected from your computer such as the ColdCard. 


## Hot Wallets

Hot Wallets are free and easy to set up and allow for easy access to your Bitcoin using on-chain storage/transaction or using the Lightning network. The downside of a Hot Wallet is that it is on an internet enabled device that could be compromised or lost. Make sure to secure one or more copies of your seed words to protect your private key in the event that your mobile device is lost or corrupted. Paper copies are a good start and you can consider moving to a metal storage mechanism if needed. The advantage to metal plates is that they are impervious to water damage, and will fare much better than paper in a house fire. There are a variety of metal products available to give you the ability to record your seed words in metal plates. DO NOT have a third party engrave your seed words for you as you are giving them your private key and hence your claim on your Bitcoin.

Metal Seed Backup Solutions:



* [http://bitcoinseedbackup.com/](http://bitcoinseedbackup.com/)
* [https://cyphersafe.io/](https://cyphersafe.io/)

Video guides:

* Muun Wallet {{< youtube id="5SbpyInuIJk" class="youtube-embed" >}}
* BlueWallet {{< youtube id="R9mq1a8bLbQ" class="youtube-embed" >}}

---

# Cold Wallets

Cold Wallets are easy to use, but are not free. Make sure that you purchase directly from the manufacturer and DO NOT purchase a used wallet. Once you have one or more, you can secure your Bitcoin for long term storage and higher security. There are multiple reputable cold wallets (ColdCard, Ledger, Trezor, and more), but we recommend the ColdCard ([www.coldcard.com](www.coldcard.com)) as it provides the security of storing your private key on a device that is not internet-enabled and can be isolated electrically from your computer if needed. You will need to download and install a desktop bitcoin wallet to work with your ColdCard. ([Sparrow](https://sparrowwallet.com) wallet is a great option, and they have an [excellent guide for setting up your coldcard](https://sparrowwallet.com/docs/coldcard-wallet.html).)

Video guides:

* Sparrow {{< youtube id="qJ_SpQX_YKw" class="youtube-embed" >}}
* Coldcard {{< youtube id="kocEpndQcsg" class="youtube-embed" >}}

---

# Upgrade to Multi-Signature Security

For larger amounts of Bitcoin or enhanced security, consider multi-signature storage. In a multi-signature setup, multiple private keys are linked together to establish ownership of Bitcoin in a way that requires multiple keys to sign a transaction. An example would be having 3 private keys linked together such that any 2 of them can sign a transaction to send or receive Bitcoin. 

There are two great companies that provide a concierge service that can help you acquire hardware wallets and set up multi-signature security if you are not comfortable setting it up yourself. These companies are Unchained Capital ([https://unchained.com](https://unchained.com/)) and Casa ([https://keys.casa/](https://keys.casa/)).

If you are technically inclined and would like to try setting up your own multi-signature setup, you can download and install a wallet application that supports generating a multisig wallet. [Sparrow Bitcoin Wallet](https://www.sparrowwallet.com) or [Specter Desktop](https://specter.solutions) are great options, but there are others ([Electrum](https://electrum.org/#home), [Wasabi](https://wasabiwallet.io), etc) that will work as well. 

---

# Get Comfortable

Once you have Bitcoin, it is good to practice moving it around by sending it to yourself or a family member. This can help you learn how to use public addresses and Lightning invoices.

Here are some sample workflows that can help you understand how Bitcoin public addresses and Lightning invoices work and how private keys can be generated and restored. 


### Workflow 1: Demonstrating wallet recovery
1. Generate a Bitcoin Wallet on BlueWallet
2. Write down your 12 recovery seed words on a piece of paper
3. Delete the Wallet on the App
4. Restore the Wallet using your Seed Words


### Workflow 2: Conducting an on-chain transaction
1. Generate a Bitcoin Wallet on Muun or BlueWallet
2. Generate a public address to Receive Bitcoin
3. Purchase $1.00 or more of Bitcoin on Strike
4. Paste your public address into the Send function on Strike and verify that the address matches the public address you generated. 
5. Send the Bitcoin to your public address
6. View the transaction details on your Muun or BlueWallet and visit a Block Explorer (such as [mempool.space](https://mempool.space) or [blockstream.info](https://blockstream.info)) to see the fees, confirmations, and transaction ID.


### Workflow 3: Instant settlement and interoperability with Lightning
1. Deposit $1 into Strike
2. Find a family member or friend with a phone and help them setup and fund a Lightning Wallet (using BlueWallet or Muun)
3. Generate a lightning invoice for 1000 sats on the receiving device
4. In Strike, click Pay, then click on the QR code icon in the top right and scan the QR code on the Lightning Invoice on the other device to move Bitcoin instantaneously from one Lightning Wallet to another.