## Written Responses

1. Describe the general process of how blocks are added to a blockchain.

Blocks in a blockchain can contain different types of information. With Bitcoin and other cryptocurrencies, for example, the blocks will contain a ledger of transactions. The chain is initialized with a starter block, also known as the genesis block, generated at a node. As blocks are added to the chain, they undergo a hashing process, which produces a unique code or hash depending on the input that is passed through the hashing function. Even the change of a single character in the block would result in a different hash. Each block that is added to chain stores the hash of the block before it, so that a change to one block would result in a change in the hashes stored in every single block following the changed block. Different clients can make requests to the node for the last block that exists in the chain. Using the hash of the previous block, clients work to  perform the computation that is necessary to generate the next unique code that satisfies whatever condition is established when the blockchain is initialized. 

2. How can blockchain users mine coins?

A blockchain establishes a standard or a condition that must be satisfied by the code or hash of a block. For example, with Bitcoin, the resulting hash of the block must have 70 leading zeroes. Miners essentially run a guess and check type operation on their own machine, in which they utilize their computational power to try to generate a solution that satisfies the established condition. Once a miner finds a solution that satisfies the condition, it passes the solution back to the node and to other clients that are attempting to mine; if no other block has already been generated and the solution is indeed valid, the block can be added to the chain and the miner can be rewarded with coins.

3. Explain how simulations like Conway's Game of Life can be used in real-world applications.


