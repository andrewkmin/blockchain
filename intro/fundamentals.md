fundamentals.md

## Fundamentals of blockchain technology
*Explain like I'm 5*\
https://medium.freecodecamp.org/explain-bitcoin-like-im-five-73b4257ac833

#### Token fundamentals
*Take on cryptocurrencies*\
https://medium.com/@nik5ter/the-other-side-of-the-coin-f293b65b1eda

*Letter to Jamie Dimon: a case for cryptocurrencies* \
https://blog.chain.com/a-letter-to-jamie-dimon-de89d417cb80

#### Hashing algorithms
- SHA-256
- Keccak-256
- Scrypt\
What are the implications?

#### Cancelling an unconfirmed transaction
https://bitcoin.stackexchange.com/questions/23090/how-do-i-cancel-my-blockchain-transaction-still-unconfirmed \
**TLDR**: send another, identical transaction with a higher fee to try to double spend -- the tx with a higher fee will get mined first, and then the subsequent one with a lower fee will be rejected because of double spend

#### FAQ
- How do you implment escrow services? I.e. if I use Bitcoin as payment for a good that's to be shipped, how can I ensure that I'll get a legitimate item?
