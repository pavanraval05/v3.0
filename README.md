Version 3.0\
Create a new directory in your Github repo called v3.0 and initialize a new hardhat project.\
Copy over any files you can reuse from the previous versions of this project into the directory for this version.\
Create a new contract called NFTDutchAuction_ERC20Bids.sol. It should have the same functionality as NFTDutchAuction.sol but accepts only ERC20 bids instead of Ether. \
The constructor for the NFTDutchAuction_ERC20Bids.sol should be: constructor(address erc20TokenAddress, address erc721TokenAddress, uint256 _nftTokenId, uint256 _reservePrice, uint256 _numBlocksAuctionOpen, uint256 _offerPriceDecrement)\
Write test cases to thoroughly test your contracts. Generate a Solidity coverage report and commit it to your repository under this version’s directory.

