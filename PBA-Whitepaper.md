Private Blockchain Addresses (Dark Blockchain)
----------------------------------------------
PBA - encrypted blockchain address only visible to the owner / sender and receiver.

Proposed anonymity feature : The Dark Blockchain / Private Blockchain Addresses

The Dark Blockchain
-------------------
1.0 Introduction 
----------------
1.1 Why propose PBAs - Anonymity Leakage
------------------------------------
> Bitcoin, Litecoin and Feathercoin, like most coins, have public visible transactions and addresses. i.e. a visible or "Light Blockchain". In the Feathercoin blockchain it is possible to see the transactions for each address and the amount they contain. Pseudo anonymity is maintained because the public viewer does not know who controls the addresses.

> The public blockchain is great for organisations that wish to be open and publicly accountable for what they spend, and how they spend it. However, if information is leaked through other channels, particularly when funds / coins are transferred, this reduces the perceived pseudo anonymity of the coins and transactions. It is both more secure and ethical to reduce exposure to exploits that reduced privacy might engender, if that is possible.

1.2 What - Additional encryption.
--------------------------------
> It would be advantageous to include the option of sending coins anonymously, users should be able to choose their own level of security.

> One issue is that there is a chance that regulation will allow Alternate currencies provided they do not have a certain anonymity feature, if that happened feathercoin could pull the feature.

1.3 How - Development
---------------------
> The proposal is to create a version of Feathercoin coin as a testbed for implementing private Blockchain addreses. Once tested, and debugged, offer to incorporate the features of the development into feathercoin as an option. 

> It would be available as a module which can be introduced to other coins networks, or used to create a new coin. The open development is to recognise the level of work and co-operation required, particularly to raise bounties or gain the interest of other coins developers.

2.0 Encrypting Addresses - how this could work
----------------------------------------------
2.1 Who can see the Addresses?
------------------------------
> The idea of developing PBA is to investigate whether it is possible to have a "Dark Blockchain" such that only the sender and receiver of coins can see unencrypted details of a transaction.

> The advantage for anonymity in using a Dark Blockchain is that, it  would reduces the number of people who have access to information that a transaction has taken place and to what amounts are sent to which addresses.

2.2 What is an encrypted address?
---------------------------------
> To achieve this, in the Dark Blockchain, the full blockchain is encrypted. The encrypted version of the address takes components of the transaction details. It acts exactly as an address, but changes with transaction, so the actual address used is hidden within the encryption.

> It is also possible to have a blockchain which contains both encrypted addresses and normal addresses.

2.3 How does a transaction happen now?
-------------------------------------
> Currently the fund amounts stored on the coin blockchains are unencrypted. The transfer of funds uses the address and private encryption keys to prove funds can be sent. The holder address has the key to send the coins.

> Currently when you look at the wallet you see all the amounts and addresses and you can go to a block chain viewer and see the same information.

2.4 How would a transaction take place for a Private address?
-----------------------------------------------------------
> In the Dark Blockchain system it is proposed to have an extra level of encryption, so that only the owner or sender to the address has the key to view the address or the amount of coins in that address.

> In the Dark Blockchain, the web blockchain viewer will only show encrypted addresses and the amount of coins in that address would or could be encrypted, based on the level of privacy required. For instance some coin recipients may insist they can see the amount in an encrypted address is there before continuing with transactions. Other would be happy to verify after it has been successfully received.

> The idea is that the "same" coin address is passed / viewed through different "encrypted keys" removing the leakage of private information to an outside observer. The wallet would search its normal open addresses in the blockchain, + it would search for the encrypted address of any private addresses. Your wallet would have the key to view the unencrypted private addresses in your wallet.

> Only the sender owner and receiver will see the unencrypted amount and address in their wallet as their private address will be part of the multi-signature encryption of the address..

2.5 How could this be programmed?
-------------------------------
> One way to do this is for the software have an extra function to decode encrypted version of the address and contents to extract the address as it scans the blockchain for local users coins. This could be achieved such that the encrypted address is a valid address. Or that in the software there is only one possible encrypted address for each transaction, so it could recognise either as being a valid address.

> If the Coin amount is to be encrypted, this could be done with the address and producing an addition private key. Then in that case the encrypted address is produced using the address the encrypted amount and the additional private key.

> It would be optimal, as far as software and database changes, that no additional knowledge or key or database field be required. This could be achieved by reusing the private key some other known element from the transaction to randomise the encrypted address. 

3.0 Does this PBA privacy measure engender money laundering?
------------------------------------------------------------

> The coins are just private, there is no money laundering involved.

> Where as with other privacy / dark methods, coins are swapped between addresses to hide there origin, this does not happen with the "Private Addresses" (on the dark blockchain). The addresses and amounts are just encrypted and can be viewed if permission is given.

> For instance, If being accused of money laundering is a concern, then we could use multi-sig technology so the owner of a coin address could release a "viewing address code", which would let a 3rd party view the address transactions.

4.0 Encrypting to a Open Address
--------------------------------
> Being able to encrypt the Blockchain Address could also be the way you make your address public, or fully open. 

> By encrypting to a vanity public viewing address which identifies the controller of that address. This could be used, for instance, by charities or other organisations that require full public auditing of transactions. The vanity address could include their charity registration number, for instance.

> You can always send your coins to a new private address - once you have released a viewing address, to make the coins private or "dark" again.

5.0 Enhancements - addition functionality to make the system usable 
-------------------------------------------------------------------
5.1 Sending between public and private addresses
------------------------------------------------
> Initially it was envisaged that the address and amount of a designated private address would be encrypted in the blockchain. By using multi-signature and Public / Private key technology, you would pass that amount in the private address, to a public or private address based on the receivers preference. If sending to a public address is chosen the last address will be made public.

5.2 Do we trust the software?
-----------------------------
> A possible disadvantage of the Dark Blockchain is that only the sender and receiver are aware a transaction took place. Users are trusting that the software performed the required action, since no third party can look at the web blockchain viewer and confirm the transaction.

> However, where cryptographic currencies have now established a high level of security and trust in open source code methods, it would now be possible to implement Dark Blockchain features. In that, you don't have to inspect every block in the open blockchain to receive an amount of coins, the software is the arbiter of how many coins that address, holds wither it is visible publicly or not.

> It would also be possible to release a viewing password, that let a trusted 3rd party such as your accountant, or Tax office, view the transactions.

5.3 Could PBA be implemented on any blockchain?
-----------------------------------------------
> It would be possible to allow Dark Blockchain addresses as an upgrade to a running blockchain. Coins currently visible, could be sent to an encrypted address, if a user required the extra privacy. Users would be able to choose to send coins to an encrypted Dark Blockchain addresses if they wished, as an option. You would obviously need the correct wallet to view your encrypted addresses and see what is in them.

5.4 What about makeing a Dark sidechain?
----------------------------------------
> Side chains are a proposal for Bitcoin 2.0. Side-chains would effectively be new blockchains that are backed by Bitcoins, in much the same way that fiat currencies used to be backed by gold. They could be backed by Feathercoin at that stage of development the Feathercoin client would include side chain facility.

> So, one possibility is that Feathercoin could implement Dark Side Chains, assuming we can fully invent how  the Dark Blockchain / Dark Addresses will work. It would also be possible to also start a separate Dark Blockchain coin.

5.5 Why should Feathercoin consider adopting PBA?
-------------------------------------------------
> By being flexible, Feathercoin is making itself more relevant to it's community / distributed direction, for instance, by returning to GPU mining. Developing extra anonymity features is another area that could be beneficial to that philosophy. It is also an area that attract development assistance and finance from interested partners as the first major coin proposing such an update to increase user security / anonymity.

5.6 How could the amounts of coins be encrypted?
------------------------------------------------
> It may not be possible to encrypt the coin amounts due to conflicts with other accounting requirements, or to show some adaptability to the Dark blockchain.

> It may be required to issue additional private keys where the address and amount are the same could produce the same encrypted address thus reducing privacy as those transfers could be linked.

5.7 Could PBA be implemented without changeing the block chain database structure?
----------------------------------------------------------------------------------
> It may be a requirement not to change the database structure, in which case it would be advantageous that the encrypted address in private address is in the form of valid address. This would mean that private address would be indistinguishable from a public address to an public viewer of the blockchain. 

6.0 Possible further enhancements / issues
--------------------------------------------
6.1 Producing additional public viewing keys
---------------------------------------------
> A facility to send a "viewing password / address" to another user to prove funds, may be required to make the system production ready.

6.2 Using PBA to enableing Public Addresses
-------------------------------------------
> A facility to make the private encrypted address be a "Vanity Address" : which would make the address owner fully public.

6.3 Variable privacy settings
-----------------------------
> A facility to make only the address encrypted not the coin amount.

6.4 Using PBA to enable private mining payout options
-----------------------------------------------------
> It would also be possible to have mining payouts to Dark Blockchain addresses, as an option ..

6.5 Identifiable and non identifiable encrypted addresses
---------------------------------------------------------
> The encrypted address may need to conform to a standard format so the coin type can still be identified, or not? For instance encrypted addresses could start with an identifier string. Which might be a requirement for reducing the work involved scanning the blockchain for personal address. Even so, it should be possible that wallet will accept either the unencrypted or encrypted address, for speed. It would slow down the system if it had to unencrypted every address, to see if you owned it. 

> Also to consider how amount and address are encrypted. 

> For instance An encrypted address and value might look exactly as an unencrypted one. The value actually being also encrypted to show a different (possibly small) amount.