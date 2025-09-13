# Solana
# To Build On Solana, it is essential to understand several key concepts unique to Solana Development

# SOLANA ACCOUNT MODEL
# On Solana, all data is stored in what are referred to "accounts". The way data is organized on the Solana Blockchain resembles a key-value store, where each entry in the database is called an "account"

# TRANSACTIONS AND INSTRUCTIONS
# On Solana, transactions are sent to interact with the network. Transactions include one or more instructions, each representing a specific operation to be processed
# The Execution Logic for instructions is stored on programs deployed on Solana network, where each program  defines its own set of instructions


# FEES ON SOLANA
# The Solana Blockchain has a few different types of fees and costs that are incurred to use the network
# These can be segmented into a few types:
# 1: Transaction Fees: A fee to have validators process transactions/instructions
# 2: Prioritization Fee: An optional fee to boost transactions processing order
# 3: Rent - A with-held balance to keep data stored on-chain

# PROGRAMS ON SOLANA
# On Solana, "smart contracts" are called programs. Each program is stored in an on-chain account and contains executable code that defines specific instructions. These instructions represent the program's functionality and can be invoked by sending transactions to the network

# PROGRAM DERIVED ADDRESSES
# Program Derived Addresses provide developers on Solana with two main use cases:
# 1: Deterministic Account Addresses: PDA'S Provide a mechanism to deterministically determine an address using a combination of "optional seeds"(predefined inputs) and a specific Program ID

# 2: Enable Program Signing: The Solana runtime enables programs to "sign" for PDA's which are derived from its programId

# CROSS PROGRAM INVOCATION
# A CrossProgramInvocation refers to when one program invokes the instructions of another program. This  mechanism allows for composability of Solana Programs
# Instructions are like API endpoints that a program exposes to the network and a Cross Program Invocation  as one API internally invoking another API

# TOKENS ON SOLANA
# Tokens are digital assets that represent ownership over diverse categories of assets
# Tokenization enables the digitilization of property-rights, serving as a fundamental component for managing both  fungible and non-fungible  assets

# Fungible Tokens: represents interchangeable and divisible assets of the same type and value
# (USDC)
# Non -Fungible tokens represent ownership of Individual assets (artwork)

# CLUSTERS AND ENDPOINTS
# The Solana Blockchain has several different groups of validators known as Clusters
# Each serving different purposes and containing dedicated nodes to fulfill JSON-RPC requests
# There are three primary clusters on the Solana Network, with the following Public Endpoints:

# 1: Mainnet: https://api.mainnet-beta.solana.com  (production)
# 2: Devnet: https://api.devnet.solana.com    (developer experimentation)
# 3: Testnet: https://api.testnet.solana.com   (validator testing)


