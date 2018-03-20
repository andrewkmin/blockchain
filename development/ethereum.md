## Ethereum Guide

### Solidity:
*Official documentation*\
https://solidity.readthedocs.io/en/develop/

*General guide*\
https://ethereumbuilders.gitbooks.io/guide/content/en/solidity_tutorials.html

*Thorough tutorial -- must-read IMO*\
http://truffleframework.com/tutorials/pet-shop

*Framework for auditing*\
https://github.com/OpenZeppelin/zeppelin-solidity

### Testing: 
*Official Truffle documentation*\
http://truffleframework.com/docs/
*Ganache documentation*\
http://truffleframework.com/ganache/

*Testing with Truffle* \
https://medium.com/@angellopozo/testing-solidity-with-truffle-and-async-await-396e81c54f93

### General directions (s/o Penn Blockchain)
- Install Node (JS server framework)
- Install Truffle (Solidity testing framework)
- Install Ganache-CLI (Ethereum client) and/or Ganache GUI application (optional)

How do I run Truffle tests?
- Make sure you have Truffle and Ganache CLI installed!
- Open Terminal and type ‘ganache-cli’, which will initialize Ganache to allow for testing. 
- Open a new Terminal window, and navigate to your truffle directory. 
- Run all your tests with ‘truffle test’
*Note* - you could use the command ‘truffle develop’ instead of ‘ganache-cli’ to initialize your local blockchain for testing

When running Truffle tests, I received the error “Could not connect to your Ethereum client. Please check that your Ethereum client:""”?
- It looks like you forgot to start Ganache. Open a new terminal window and type ‘ganache-cli’, and then try to run your tests again.
