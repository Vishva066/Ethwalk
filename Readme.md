
# ETHWALK ERC721 DEMO

A simple contract to deploy ERC 721 Token to sepolia testnet.


## Tools Used

**Wallet:** Metamask

**IDE:** Remix IDE

**Blockchain** Ethereum Testnet Sepolia

**Contract:** Openzepplin

**IPFS:** Pinata


## Functions

**balanceOf:** This function is used to return the number of NFTs (Non-Fungible Tokens) owned by a specific address.

**ownerOf:** This function returns the address of the owner of a specific token. Each ERC721 token is unique, represented by an ID. This function allows users or applications to determine the owner of the token based on its unique ID.

**safeTransferFrom (without data)** This function safely transfers the ownership of a specific token from one address to another. This function checks if the recipient is a smart contract. If it is, it must implement a specific function (onERC721Received) to accept the transfer.

**transferFrom:** This function is used to transfer the ownership of a token from one address to another. It is generally used when the sender has been approved to transfer the token.

**approve:** This function is used to give approval to an address to transfer a specific token. This allows for delegated transfers, where an owner can allow another party to transfer a token on their behalf.

**getApproved:** This function is used to get the approved address for a specific token. If there is no approved address for the token, this function will return a null address.

**setApprovalForAll:** This function allows an owner of one or more tokens to approve or revoke approval for an operator to manage all of their tokens.

**isApprovedForAll:** This function is used to check if an operator is approved to manage all of an owner's tokens.

**safeTransferFrom (with data):** This function is similar to safeTransferFrom (without data) but with an additional data parameter. This extra data can be used to pass additional information during the transfer if the recipient is a smart contract. This function also checks if the recipient is a smart contract and whether it implements the onERC721Received function.

