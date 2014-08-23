Private Blockchain Addresses (Dark Blockchain)
----------------------------------------------

Functional Specification.

Key: D.1 = disadvantage 1. A.3 = advantage 3

1.0 How the encrypted address is created?
-----------------------------------------
> When a normal valid address is created in the coin wallet software a second address is created based on the private key and the original address.

2.0 How the system identifies an encrypted address as valid?
------------------------------------------------------------
> When part of the system , like the wallet needs to identify weither the user owns private blockchain address, it uses the encryption function to produce the encrypted version of the address and searches for those.

> The decryption uses exactly the same mechanism as is currently done except the process now has 2 stages. For the owner of the address (public) and private key. Firstly uses his address and private key to open the encrypted address. 

> There is also an extra token to be passed when the transaction is completed by the miner, such that the miner and the receiver are passed, when a transaction occurs and is validated into the blockchain. Again that could be exactly how is done current, except, if it is an encrypted address, it would act accordingly. ie the miner might given reduced no access but can still check the key useing its key.

> It is envisaged there would be a veiwing key, which could be issued, the mining key could act similarly. That is the reuse of system values that are only known to the user or part of the transaction process, to encrypt the system to public view.

3.0 The encrypted address need to change for each transaction.
--------------------------------------------------------------

Some method of randomising the encrypted address.

> Possible "randomiseing" methods
> 3.1 Use the transaction value, or part of it to create the private address.
>> D.1 is a number (limited character range)
>> D.2 could be repeated for similar sized transactions happen.

> 3.2 Use a new password or pin or private address
>> D.1 database changes

> 3.3 Use the previous senders address or part of it to geneate the private address.
>> D.1   private

> 3.4 Store an extra private key for each private transaction.
>> D.1 database changes to wallet