# Bitcoin Gift Guide
My guide to gifting bitcoin to noobs while also teaching them just enough about security.

Fork this repo and customize it for your own bitcoin gift giving!


## Personalize your intro message
_I’m giving you (or your kids) a tiny bit of bitcoin! But in order to receive it I’m going to teach you a bit about how bitcoin works and give you some hands-on experience._

_After this brief ~10min exercise you’ll know more about how bitcoin works than 99.99% of the world!_

<p align="center">
  <img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/merry_bitcoin.jpg?raw=true" width="250">
</p>


## Quick Overview:
In order to receive your bitcoin gift, you will:
* Install a bitcoin wallet on your phone
* Generate a new wallet
* Securely back that wallet up
* Receive your bitcoin!


## Set up a bitcoin wallet
#### Install a wallet app:
Go to the iOS or Google Play store and download “BlueWallet Bitcoin Wallet”:

<img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/bw_appstore.jpg?raw=true" width="250">

BlueWallet is free and one of the nicer, easier to use bitcoin wallet options. It’s been pretty thoroughly vetted by the bitcoin community and is considered reasonably safe and trustworthy.


#### Generate a new wallet:
<img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/bw_addwallet_1.jpg?raw=true" width="250">

Name your new wallet anything you like. You can always rename it later. Select “Bitcoin” as the type (we can discuss what “Lightning” and “Vault” are later). Click “Create”.

<img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/bw_addwallet_2.jpg?raw=true" width="250">

The wallet will now show you 12 “seed” words for the new wallet. This is THE MOST IMPORTANT STEP!


#### Crucial interlude about bitcoin wallets:
A bitcoin “wallet” is actually a terrible, misleading name.

<img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/wallet.png?raw=true" width="250">

What it should really be called is something like a “secret store” (as in a place to store secrets) or, I suppose, a “password vault”.

The secret being stored is your “seed”. It’s essentially a huge random number that no one can guess (there are more possible seeds than there are atoms on Earth).

The seed generates a new, unique address each time you want to receive bitcoin (note: addresses should never be reused).

<img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/key_diagram.png?raw=true" width="250">

And only the seed can cryptographically “sign” (authorize) a transaction that sends any of that bitcoin to anyone else. If someone else tried to move your bitcoin with a different seed, the transaction would fail due to crypto math magic. 

Whoever has the seed has FULL CONTROL over your bitcoin.

The seed is just a bunch of nonsense text. And digital text can reside in more than one place at a time. It happens to live in BlueWallet on your phone right now. But if someone else got your seed, they could input it into their bitcoin wallet app and make any transactions they want to.

There is nothing special about the wallet on your phone! It’s just one place where your bitcoin can be controlled.

The seed is all that matters!


### Secure your backup
#### BACK UP YOUR SEED!!!!
Back to BlueWallet.

It’s now showing you 12 words that represent your seed. This is the whole game right here (if you lost that screen, don’t worry. Click on the new wallet, click the three dot menu at the upper right, click on “Export / Backup”. It’ll display your 12 words at the bottom).

Write them down--ON PAPER!!!--in order. The app will not let you take a screenshot. The app will not let you copy-and-paste them.

You should NEVER have a digital copy of your seed. You have to assume that anything digital, whether it be text files or photos or screencaps, will someday be hacked.

<img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/metal_seed.jpg?raw=true" width="250">
_It’s so important that some people even etch them into metal so they’ll survive a fire!
Um, just don’t take a picture of it!
Note: more advanced seeds use 24 words._



#### Test your backup seed
Now that you’ve created your wallet, click into it and click “receive” at the bottom

<img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/bw_receive.png?raw=true" width="250">

You’ll see a blocky QR code. Below it you’ll see the first receive address generated for your seed. It will look something like:

`bc1q733654cfld48hvluz02vxvdhagysgh3v93wv8u`

When I send you your bitcoin, you’ll have to send an address like this to me. Unlike your seed, it’s safe to share a receive address with whomever you’re transacting.

For now, note the first few characters after the “bc1” (that part will never change) and note the last few. So for my example: `q7336` and `wv8u`.

Write your beginning and end snippets down on a piece of scrap paper (this step isn’t about security and will be discarded later).

Next: Back out of this screen and DELETE YOUR WALLET!

Yep. Delete it.

<img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/bw_delete_1.jpg?raw=true" width="250">

<img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/bw_delete_2.jpg?raw=true" width="250">

Why’d we do that?

To prove that there’s nothing special about the “wallet”. All that matters is the seed.


#### Restore your wallet
Click to add a wallet again. But this time we’re going to select “Import wallet”:

<img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/bw_import_1.jpg?raw=true" width="250">

On the import screen type in your 12 seed backup words and then click “Import”.

Spelling matters. Order matters. If you wrote them down wrong, better to know it now before any real bitcoin is sent to that seed.

With your wallet restored, once again click “receive”. Note the receive address. It should start and end with the same snippets you noted above.

Remember that each receive address is unique and can ONLY be generated by your seed. If you see the same receive addr, then you can be sure that you’re working from the same seed.

If you had actual bitcoin in this wallet, you would now have regained full control over it.

The wallet on your phone doesn’t matter.

The seed is everything.


#### Safely store your seed backup words
Take the piece of paper with your 12 backup words and store it somewhere safe. You are now the biggest security flaw. You’ll forget where you put the piece of paper. You’ll accidentally recycle it. You’ll spill a drink on it. Your dog will eat it.

Many people have a fireproof box for certain precious documents. That’d be a good idea.

<img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/firebox.jpg?raw=true" width="250">

The good news is that this is just practice. We’re not talking about securing your life savings here (not yet, at least). But if you have no way to reasonably secure a simple piece of paper, you’ve got some work to do.



## Receive your bitcoin gift!
Let me know when you’ve completed these steps. I’ll send you your bitcoin and answer any questions you have along the way.

<p align="center">
  <img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/bitcoin_gift.jpg?raw=true" width="400">
</p>


## Next steps
Don’t lose your bitcoin, don’t spend your bitcoin, and, ideally, just forget about it until at least 2025.

Not a bad idea to delete the wallet from your phone and keep your seed backup words secure.

If you do keep the wallet "hot" (on your phone), be sure to click into the security settings and add additional protections to restrict access to your fingerprint and/or a password.



### Bonus next steps
#### Can I import the bitcoin on “paper wallets” that you’ve given me in the past?
Yes! It’s a good idea to consolidate them into a wallet controlled by your new seed. Paper wallets are fun and convenient but too fragile for long-term storage.

<img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/paper_wallet.jpg?raw=true" width="250">

You can import it into BlueWallet (I haven’t actually tested this step yet myself; contact me first!). Instead of entering the 12 backup words you’d click “Scan or import a file”. Carefully unfold the paper wallet and scan the private key QR code that’s under the protective flap. That private key is the paper wallet’s seed. You now have full control over those funds.

HOWEVER, paper wallet seeds have one important oddity: you have to move ALL of the funds off of it at the same time.

So get a new receive addr from the wallet we created earlier, then go back to the newly imported paper wallet and send the full amount to your receive addr.

It will have to deduct some transaction fees to do so. If you have the option, select the lowest fee (i.e. slowest) possible. It might take as long as a day or so, but the paper wallet btc will eventually get transferred.

Once you’ve confirmed the transfer, it’s safe to delete the imported paper wallet and toss the original printed paper.


#### How do I buy bitcoin myself?
The easiest way to start is via the Cash App.

<img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/ca_buy_1.jpg?raw=true" width="250">

It’s simple to set up. Like any banking app you have to link a checking account and provide ID documentation. They do charge fees on bitcoin purchases but for now that’s fine. 

But the most important part: You can withdraw your bitcoin into the wallet you control; bitcoin sitting within Cash App should not be considered safe until it’s withdrawn.

Just get a new receive addr in BlueWallet and paste that into the Cash App’s bitcoin withdrawal flow. 

<img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/ca_send_1.jpg?raw=true" width="250">

Note: Cash App denotes bitcoin in “sats” (short for “satoshis”). Sats are fractions of a bitcoin, similar to how a cent is 1/100th of a dollar. Except in this case one sat is 1/100,000,000th of a bitcoin.

1 sat = 0.00000001 btc

<img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/ca_send_2.jpg?raw=true" width="250">

Notice that I’m using my first receive addr in this example. Once an addr is used, BlueWallet will know to generate a new receive addr the next time you want to receive more bitcoin. Don’t reuse addresses!

<img src="https://github.com/kdmukai/bitcoin_gift_guide/blob/main/img/ca_send_3.jpg?raw=true" width="250">

What if I want to get serious about investing more money in bitcoin?
The more you invest, the more you have to step up your security game. Controlling your seed in a bitcoin wallet on your phone is fine for small amounts. But it is too dangerous for serious money.

The next step is a hardware wallet. It’s a secure storage device that contains your seed and replaces the wallet on your phone. Assume your phone can get hacked. The hardware wallets, thus far, have proven much, MUCH safer.

As for bigger purchases, Cash App’s fees aren’t great if you’re going to keep buying in greater amounts. Exchanges like Coinbase Pro offer essentially free transaction fees (0.15%!) but are a lot less friendly to beginners.

And if you get to holding serious net worth in bitcoin, then you step up your security even further to a “multisig” approach.
