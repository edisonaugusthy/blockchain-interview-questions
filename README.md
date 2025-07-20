# Blockchain Developer Interview Questions & Answers

> A comprehensive collection of 300+ blockchain interview questions and answers for developers at all levels.

## 📚 Table of Contents

| No. | Questions                                                                                                                                    |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [What is Blockchain?](#what-is-blockchain)                                                                                                   |
| 2   | [What is the difference between Blockchain and traditional databases?](#what-is-the-difference-between-blockchain-and-traditional-databases) |
| 3   | [What are the key characteristics of Blockchain?](#what-are-the-key-characteristics-of-blockchain)                                           |
| 4   | [What is a smart contract?](#what-is-a-smart-contract)                                                                                       |
| 5   | [What is Solidity?](#what-is-solidity)                                                                                                       |
| 6   | [What are the different types of blockchain networks?](#what-are-the-different-types-of-blockchain-networks)                                 |
| 7   | [What is consensus mechanism?](#what-is-consensus-mechanism)                                                                                 |
| 8   | [What is the difference between Proof of Work and Proof of Stake?](#what-is-the-difference-between-proof-of-work-and-proof-of-stake)         |
| 9   | [What is a block?](#what-is-a-block)                                                                                                         |
| 10  | [What is a hash function?](#what-is-a-hash-function)                                                                                         |
| 11  | [What is gas in Ethereum?](#what-is-gas-in-ethereum)                                                                                         |
| 12  | [What are function modifiers in Solidity?](#what-are-function-modifiers-in-solidity)                                                         |
| 13  | [What is the difference between memory and storage in Solidity?](#what-is-the-difference-between-memory-and-storage-in-solidity)             |
| 14  | [What are events in Solidity?](#what-are-events-in-solidity)                                                                                 |
| 15  | [What is a reentrancy attack?](#what-is-a-reentrancy-attack)                                                                                 |
| 16  | [What are ERC standards?](#what-are-erc-standards)                                                                                           |
| 17  | [What is the difference between ERC-20 and ERC-721?](#what-is-the-difference-between-erc-20-and-erc-721)                                     |
| 18  | [What is DeFi?](#what-is-defi)                                                                                                               |
| 19  | [What is an oracle in blockchain?](#what-is-an-oracle-in-blockchain)                                                                         |
| 20  | [What is a Merkle tree?](#what-is-a-merkle-tree)                                                                                             |
| 21  | [What is layer 2 scaling?](#what-is-layer-2-scaling)                                                                                         |
| 22  | [What are rollups?](#what-are-rollups)                                                                                                       |
| 23  | [What is a 51% attack?](#what-is-a-51-attack)                                                                                                |
| 24  | [What is cryptocurrency mining?](#what-is-cryptocurrency-mining)                                                                             |
| 25  | [What is a wallet?](#what-is-a-wallet)                                                                                                       |
| 26  | [What is the double-spending problem?](#what-is-the-double-spending-problem)                                                                 |
| 27  | [What is Byzantine Fault Tolerance?](#what-is-byzantine-fault-tolerance)                                                                     |
| 28  | [What is sharding?](#what-is-sharding)                                                                                                       |
| 29  | [What are zero-knowledge proofs?](#what-are-zero-knowledge-proofs)                                                                           |
| 30  | [What is MEV (Maximal Extractable Value)?](#what-is-mev-maximal-extractable-value)                                                           |
| 31  | [What is a DAO?](#what-is-a-dao)                                                                                                             |
| 32  | [What is IPFS?](#what-is-ipfs)                                                                                                               |
| 33  | [What is cross-chain interoperability?](#what-is-cross-chain-interoperability)                                                               |
| 34  | [What is a bridge in blockchain?](#what-is-a-bridge-in-blockchain)                                                                           |
| 35  | [What is staking?](#what-is-staking)                                                                                                         |
| 36  | [What are the different types of keys in cryptography?](#what-are-the-different-types-of-keys-in-cryptography)                               |
| 37  | [What is a nonce?](#what-is-a-nonce)                                                                                                         |
| 38  | [What is finality in blockchain?](#what-is-finality-in-blockchain)                                                                           |
| 39  | [What is slashing?](#what-is-slashing)                                                                                                       |
| 40  | [What is the blockchain trilemma?](#what-is-the-blockchain-trilemma)                                                                         |
| 41  | [What is the difference between public and private keys?](#what-is-the-difference-between-public-and-private-keys)                           |
| 42  | [What is a digital signature?](#what-is-a-digital-signature)                                                                                 |
| 43  | [What is elliptic curve cryptography?](#what-is-elliptic-curve-cryptography)                                                                 |
| 44  | [What is the purpose of the require function in Solidity?](#what-is-the-purpose-of-the-require-function-in-solidity)                         |
| 45  | [What is the difference between assert and revert in Solidity?](#what-is-the-difference-between-assert-and-revert-in-solidity)               |
| 46  | [What are view and pure functions in Solidity?](#what-are-view-and-pure-functions-in-solidity)                                               |
| 47  | [What is the purpose of the payable keyword?](#what-is-the-purpose-of-the-payable-keyword)                                                   |
| 48  | [What is a fallback function?](#what-is-a-fallback-function)                                                                                 |
| 49  | [What is inheritance in Solidity?](#what-is-inheritance-in-solidity)                                                                         |
| 50  | [What are interfaces in Solidity?](#what-are-interfaces-in-solidity)                                                                         |
| 51  | [What are libraries in Solidity?](#what-are-libraries-in-solidity)                                                                           |
| 52  | [What is the difference between delegatecall and call?](#what-is-the-difference-between-delegatecall-and-call)                               |
| 53  | [What are mappings in Solidity?](#what-are-mappings-in-solidity)                                                                             |
| 54  | [What is struct packing?](#what-is-struct-packing)                                                                                           |
| 55  | [What are immutable and constant variables?](#what-are-immutable-and-constant-variables)                                                     |
| 56  | [What is the receive function?](#what-is-the-receive-function)                                                                               |
| 57  | [What are custom errors in Solidity?](#what-are-custom-errors-in-solidity)                                                                   |
| 58  | [What is the difference between tx.origin and msg.sender?](#what-is-the-difference-between-tx-origin-and-msg-sender)                         |
| 59  | [What are proxy patterns?](#what-are-proxy-patterns)                                                                                         |
| 60  | [What is the transparent proxy pattern?](#what-is-the-transparent-proxy-pattern)                                                             |
| 61  | [What is UUPS (Universal Upgradeable Proxy Standard)?](#what-is-uups-universal-upgradeable-proxy-standard)                                   |
| 62  | [What is the diamond pattern?](#what-is-the-diamond-pattern)                                                                                 |
| 63  | [What are the risks of upgradeable contracts?](#what-are-the-risks-of-upgradeable-contracts)                                                 |
| 64  | [What are time locks in smart contracts?](#what-are-time-locks-in-smart-contracts)                                                           |
| 65  | [What is integer overflow/underflow?](#what-is-integer-overflow-underflow)                                                                   |
| 66  | [What is front-running?](#what-is-front-running)                                                                                             |
| 67  | [What is sandwich attacking?](#what-is-sandwich-attacking)                                                                                   |
| 68  | [What is flash loan attack?](#what-is-flash-loan-attack)                                                                                     |
| 69  | [What is oracle manipulation?](#what-is-oracle-manipulation)                                                                                 |
| 70  | [What is governance attack?](#what-is-governance-attack)                                                                                     |
| 71  | [What are time-based attacks?](#what-are-time-based-attacks)                                                                                 |
| 72  | [What is the verifier's dilemma?](#what-is-the-verifiers-dilemma)                                                                            |
| 73  | [What are Sybil attacks?](#what-are-sybil-attacks)                                                                                           |
| 74  | [What is censorship resistance?](#what-is-censorship-resistance)                                                                             |
| 75  | [What is key extraction attack?](#what-is-key-extraction-attack)                                                                             |
| 76  | [What are smart contract security best practices?](#what-are-smart-contract-security-best-practices)                                         |
| 77  | [How do you secure private keys?](#how-do-you-secure-private-keys)                                                                           |
| 78  | [What is defense in depth for blockchain?](#what-is-defense-in-depth-for-blockchain)                                                         |
| 79  | [What is formal verification?](#what-is-formal-verification)                                                                                 |
| 80  | [What are bug bounty programs?](#what-are-bug-bounty-programs)                                                                               |
| 81  | [What is ERC-1155?](#what-is-erc-1155)                                                                                                       |
| 82  | [What is ERC-777?](#what-is-erc-777)                                                                                                         |
| 83  | [What is ERC-4626?](#what-is-erc-4626)                                                                                                       |
| 84  | [What are wrapped tokens?](#what-are-wrapped-tokens)                                                                                         |
| 85  | [What is token burning?](#what-is-token-burning)                                                                                             |
| 86  | [What are governance tokens?](#what-are-governance-tokens)                                                                                   |
| 87  | [What is token vesting?](#what-is-token-vesting)                                                                                             |
| 88  | [What are utility tokens vs security tokens?](#what-are-utility-tokens-vs-security-tokens)                                                   |
| 89  | [What are stablecoins?](#what-are-stablecoins)                                                                                               |
| 90  | [What is an Automated Market Maker (AMM)?](#what-is-an-automated-market-maker-amm)                                                           |
| 91  | [How does Uniswap work?](#how-does-uniswap-work)                                                                                             |
| 92  | [What is impermanent loss?](#what-is-impermanent-loss)                                                                                       |
| 93  | [What is slippage in DEX trading?](#what-is-slippage-in-dex-trading)                                                                         |
| 94  | [What are liquidity pools?](#what-are-liquidity-pools)                                                                                       |
| 95  | [What is yield farming?](#what-is-yield-farming)                                                                                             |
| 96  | [What is liquidity mining?](#what-is-liquidity-mining)                                                                                       |
| 97  | [What are flash loans?](#what-are-flash-loans)                                                                                               |
| 98  | [How do lending protocols work?](#how-do-lending-protocols-work)                                                                             |
| 99  | [What is overcollateralization in DeFi?](#what-is-overcollateralization-in-defi)                                                             |
| 100 | [What is liquidation in DeFi lending?](#what-is-liquidation-in-defi-lending)                                                                 |
| 101 | [What are synthetic assets?](#what-are-synthetic-assets)                                                                                     |
| 102 | [What is a decentralized exchange (DEX)?](#what-is-a-decentralized-exchange-dex)                                                             |
| 103 | [What are prediction markets?](#what-are-prediction-markets)                                                                                 |
| 104 | [What is composability in DeFi?](#what-is-composability-in-defi)                                                                             |
| 105 | [What are money legos?](#what-are-money-legos)                                                                                               |
| 106 | [What is Total Value Locked (TVL)?](#what-is-total-value-locked-tvl)                                                                         |
| 107 | [What is optimistic rollup?](#what-is-optimistic-rollup)                                                                                     |
| 108 | [What is ZK-rollup?](#what-is-zk-rollup)                                                                                                     |
| 109 | [What are state channels?](#what-are-state-channels)                                                                                         |
| 110 | [What is Lightning Network?](#what-is-lightning-network)                                                                                     |
| 111 | [What are sidechains?](#what-are-sidechains)                                                                                                 |
| 112 | [What is plasma framework?](#what-is-plasma-framework)                                                                                       |
| 113 | [What are commit chains?](#what-are-commit-chains)                                                                                           |
| 114 | [What is data availability sampling?](#what-is-data-availability-sampling)                                                                   |
| 115 | [What are fraud proofs?](#what-are-fraud-proofs)                                                                                             |
| 116 | [What is the challenge period in optimistic rollups?](#what-is-the-challenge-period-in-optimistic-rollups)                                   |
| 117 | [What are exit mechanisms in Layer 2?](#what-are-exit-mechanisms-in-layer-2)                                                                 |
| 118 | [What are atomic swaps?](#what-are-atomic-swaps)                                                                                             |
| 119 | [What are relay chains?](#what-are-relay-chains)                                                                                             |
| 120 | [What are the security risks of cross-chain bridges?](#what-are-the-security-risks-of-cross-chain-bridges)                                   |
| 121 | [What is Delegated Proof of Stake (DPoS)?](#what-is-delegated-proof-of-stake-dpos)                                                           |
| 122 | [What is Proof of Authority (PoA)?](#what-is-proof-of-authority-poa)                                                                         |
| 123 | [What is Practical Byzantine Fault Tolerance (PBFT)?](#what-is-practical-byzantine-fault-tolerance-pbft)                                     |
| 124 | [What is Proof of History (PoH)?](#what-is-proof-of-history-poh)                                                                             |
| 125 | [What is Tendermint consensus?](#what-is-tendermint-consensus)                                                                               |
| 126 | [What is the CAP theorem in blockchain context?](#what-is-the-cap-theorem-in-blockchain-context)                                             |
| 127 | [What is fork choice rule?](#what-is-fork-choice-rule)                                                                                       |
| 128 | [What is gasper (Ethereum 2.0's consensus)?](#what-is-gasper-ethereum-20s-consensus)                                                         |
| 129 | [What are eclipse attacks?](#what-are-eclipse-attacks)                                                                                       |
| 130 | [What is the stake grinding attack?](#what-is-the-stake-grinding-attack)                                                                     |
| 131 | [What is SHA-256?](#what-is-sha-256)                                                                                                         |
| 132 | [What is the avalanche effect?](#what-is-the-avalanche-effect)                                                                               |
| 133 | [How are Bitcoin addresses generated?](#how-are-bitcoin-addresses-generated)                                                                 |
| 134 | [What is the secp256k1 curve?](#what-is-the-secp256k1-curve)                                                                                 |
| 135 | [What are zk-SNARKs vs zk-STARKs?](#what-are-zk-snarks-vs-zk-starks)                                                                         |
| 136 | [What is homomorphic encryption?](#what-is-homomorphic-encryption)                                                                           |
| 137 | [What are commitment schemes?](#what-are-commitment-schemes)                                                                                 |
| 138 | [What is a Merkle proof?](#what-is-a-merkle-proof)                                                                                           |
| 139 | [What is the birthday paradox in cryptography?](#what-is-the-birthday-paradox-in-cryptography)                                               |
| 140 | [What is a replay attack?](#what-is-a-replay-attack)                                                                                         |
| 141 | [How do you prevent replay attacks?](#how-do-you-prevent-replay-attacks)                                                                     |
| 142 | [What is the scalability trilemma?](#what-is-the-scalability-trilemma)                                                                       |
| 143 | [What is transaction sharding vs state sharding?](#what-is-transaction-sharding-vs-state-sharding)                                           |
| 144 | [What is block size optimization?](#what-is-block-size-optimization)                                                                         |
| 145 | [What is transaction compression?](#what-is-transaction-compression)                                                                         |
| 146 | [What are parallel execution models?](#what-are-parallel-execution-models)                                                                   |
| 147 | [What is pipelining in blockchain?](#what-is-pipelining-in-blockchain)                                                                       |
| 148 | [What is the data availability problem?](#what-is-the-data-availability-problem)                                                             |
| 149 | [What are erasure codes in blockchain?](#what-are-erasure-codes-in-blockchain)                                                               |
| 150 | [What is optimistic processing?](#what-is-optimistic-processing)                                                                             |
| 151 | [What is Hyperledger Fabric?](#what-is-hyperledger-fabric)                                                                                   |
| 152 | [What is a channel in Hyperledger Fabric?](#what-is-a-channel-in-hyperledger-fabric)                                                         |
| 153 | [What is chaincode?](#what-is-chaincode)                                                                                                     |
| 154 | [What is the ordering service in Hyperledger Fabric?](#what-is-the-ordering-service-in-hyperledger-fabric)                                   |
| 155 | [What is membership service provider (MSP)?](#what-is-membership-service-provider-msp)                                                       |
| 156 | [What is R3 Corda?](#what-is-r3-corda)                                                                                                       |
| 157 | [What is JPMorgan's Quorum?](#what-is-jpmorgans-quorum)                                                                                      |
| 158 | [What is blockchain-as-a-service (BaaS)?](#what-is-blockchain-as-a-service-baas)                                                             |
| 159 | [What are private blockchain challenges?](#what-are-private-blockchain-challenges)                                                           |
| 160 | [What is Truffle framework?](#what-is-truffle-framework)                                                                                     |
| 161 | [What is Hardhat?](#what-is-hardhat)                                                                                                         |
| 162 | [What is Ganache?](#what-is-ganache)                                                                                                         |
| 163 | [What is Remix IDE?](#what-is-remix-ide)                                                                                                     |
| 164 | [What is Web3.js?](#what-is-web3js)                                                                                                          |
| 165 | [What is Ethers.js?](#what-is-ethersjs)                                                                                                      |
| 166 | [What is Metamask?](#what-is-metamask)                                                                                                       |
| 167 | [What are testnets?](#what-are-testnets)                                                                                                     |
| 168 | [What are faucets in blockchain development?](#what-are-faucets-in-blockchain-development)                                                   |
| 169 | [What is contract verification?](#what-is-contract-verification)                                                                             |
| 170 | [What is continuous integration for smart contracts?](#what-is-continuous-integration-for-smart-contracts)                                   |
| 171 | [What is account abstraction?](#what-is-account-abstraction)                                                                                 |
| 172 | [What are the benefits of account abstraction?](#what-are-the-benefits-of-account-abstraction)                                               |
| 173 | [What is EIP-4337?](#what-is-eip-4337)                                                                                                       |
| 174 | [What is a central bank digital currency (CBDC)?](#what-is-a-central-bank-digital-currency-cbdc)                                             |
| 175 | [What are privacy coins?](#what-are-privacy-coins)                                                                                           |
| 176 | [What is the metaverse and blockchain's role?](#what-is-the-metaverse-and-blockchains-role)                                                  |
| 177 | [What is regenerative finance (ReFi)?](#what-is-regenerative-finance-refi)                                                                   |
| 178 | [How will quantum computing affect blockchain?](#how-will-quantum-computing-affect-blockchain)                                               |
| 179 | [What is the future of blockchain scalability?](#what-is-the-future-of-blockchain-scalability)                                               |
| 180 | [How might AI integrate with blockchain technology?](#how-might-ai-integrate-with-blockchain-technology)                                     |
| 181 | [What is gas optimization?](#what-is-gas-optimization)                                                                                       |
| 182 | [What are gas optimization techniques?](#what-are-gas-optimization-techniques)                                                               |
| 183 | [What assembly optimizations improve performance?](#what-assembly-optimizations-improve-performance)                                         |
| 184 | [How do you handle large datasets in blockchain applications?](#how-do-you-handle-large-datasets-in-blockchain-applications)                 |
| 185 | [What is automated smart contract auditing?](#what-is-automated-smart-contract-auditing)                                                     |
| 186 | [What is static analysis for smart contracts?](#what-is-static-analysis-for-smart-contracts)                                                 |
| 187 | [What is dynamic testing for smart contracts?](#what-is-dynamic-testing-for-smart-contracts)                                                 |
| 188 | [What is responsible disclosure in blockchain?](#what-is-responsible-disclosure-in-blockchain)                                               |
| 189 | [What is incident response for blockchain systems?](#what-is-incident-response-for-blockchain-systems)                                       |
| 190 | [What is a multi-signature wallet?](#what-is-a-multi-signature-wallet)                                                                       |
| 191 | [What are threshold signatures?](#what-are-threshold-signatures)                                                                             |
| 192 | [What is key management?](#what-is-key-management)                                                                                           |
| 193 | [What is operational security for crypto?](#what-is-operational-security-for-crypto)                                                         |
| 194 | [What is a hardware wallet?](#what-is-a-hardware-wallet)                                                                                     |
| 195 | [What is a cold wallet vs hot wallet?](#what-is-a-cold-wallet-vs-hot-wallet)                                                                 |
| 196 | [What is seed phrase recovery?](#what-is-seed-phrase-recovery)                                                                               |
| 197 | [What is deterministic wallet generation?](#what-is-deterministic-wallet-generation)                                                         |
| 198 | [What is hierarchical deterministic (HD) wallets?](#what-is-hierarchical-deterministic-hd-wallets)                                           |
| 199 | [What is a brain wallet?](#what-is-a-brain-wallet)                                                                                           |
| 200 | [What is paper wallet?](#what-is-paper-wallet)                                                                                               |
| 201 | [What is address reuse?](#what-is-address-reuse)                                                                                             |
| 202 | [What is coin mixing/tumbling?](#what-is-coin-mixing-tumbling)                                                                               |
| 203 | [What is ring signature?](#what-is-ring-signature)                                                                                           |
| 204 | [What is stealth address?](#what-is-stealth-address)                                                                                         |
| 205 | [What is confidential transaction?](#what-is-confidential-transaction)                                                                       |
| 206 | [What is bulletproof?](#what-is-bulletproof)                                                                                                 |
| 207 | [What is Mimblewimble?](#what-is-mimblewimble)                                                                                               |
| 208 | [What is Zcash's zk-SNARKs implementation?](#what-is-zcashs-zk-snarks-implementation)                                                        |
| 209 | [What is Monero's privacy features?](#what-is-moneros-privacy-features)                                                                      |
| 210 | [What is a mixnet?](#what-is-a-mixnet)                                                                                                       |
| 211 | [What is transaction graph analysis?](#what-is-transaction-graph-analysis)                                                                   |
| 212 | [What is address clustering?](#what-is-address-clustering)                                                                                   |
| 213 | [What is blockchain forensics?](#what-is-blockchain-forensics)                                                                               |
| 214 | [What is chain analysis?](#what-is-chain-analysis)                                                                                           |
| 215 | [What is compliance in crypto?](#what-is-compliance-in-crypto)                                                                               |
| 216 | [What is AML/KYC in blockchain?](#what-is-aml-kyc-in-blockchain)                                                                             |
| 217 | [What is FATF travel rule?](#what-is-fatf-travel-rule)                                                                                       |
| 218 | [What is regulatory sandboxes?](#what-is-regulatory-sandboxes)                                                                               |
| 219 | [What is MiCA regulation?](#what-is-mica-regulation)                                                                                         |
| 220 | [What is the Howey test?](#what-is-the-howey-test)                                                                                           |
| 221 | [What is securities law in crypto?](#what-is-securities-law-in-crypto)                                                                       |
| 222 | [What is taxation of cryptocurrency?](#what-is-taxation-of-cryptocurrency)                                                                   |
| 223 | [What is GDPR and blockchain?](#what-is-gdpr-and-blockchain)                                                                                 |
| 224 | [What is right to be forgotten vs immutability?](#what-is-right-to-be-forgotten-vs-immutability)                                             |
| 225 | [What is data sovereignty in blockchain?](#what-is-data-sovereignty-in-blockchain)                                                           |
| 226 | [What is blockchain voting system design?](#what-is-blockchain-voting-system-design)                                                         |
| 227 | [What is supply chain traceability?](#what-is-supply-chain-traceability)                                                                     |
| 228 | [What is digital identity on blockchain?](#what-is-digital-identity-on-blockchain)                                                           |
| 229 | [What is self-sovereign identity (SSI)?](#what-is-self-sovereign-identity-ssi)                                                               |
| 230 | [What is verifiable credentials?](#what-is-verifiable-credentials)                                                                           |
| 231 | [What is decentralized identifier (DID)?](#what-is-decentralized-identifier-did)                                                             |
| 232 | [What is identity verification on blockchain?](#what-is-identity-verification-on-blockchain)                                                 |
| 233 | [What is reputation system on blockchain?](#what-is-reputation-system-on-blockchain)                                                         |
| 234 | [What is decentralized social media?](#what-is-decentralized-social-media)                                                                   |
| 235 | [What is content moderation in Web3?](#what-is-content-moderation-in-web3)                                                                   |
| 236 | [What is decentralized storage?](#what-is-decentralized-storage)                                                                             |
| 237 | [What is Filecoin?](#what-is-filecoin)                                                                                                       |
| 238 | [What is Arweave?](#what-is-arweave)                                                                                                         |
| 239 | [What is Swarm?](#what-is-swarm)                                                                                                             |
| 240 | [What is content addressing?](#what-is-content-addressing)                                                                                   |
| 241 | [What is peer-to-peer networking?](#what-is-peer-to-peer-networking)                                                                         |
| 242 | [What is distributed hash table (DHT)?](#what-is-distributed-hash-table-dht)                                                                 |
| 243 | [What is BitTorrent and blockchain?](#what-is-bittorrent-and-blockchain)                                                                     |
| 244 | [What is incentivized storage networks?](#what-is-incentivized-storage-networks)                                                             |
| 245 | [What is data redundancy in blockchain storage?](#what-is-data-redundancy-in-blockchain-storage)                                             |
| 246 | [What is proof of replication?](#what-is-proof-of-replication)                                                                               |
| 247 | [What is proof of spacetime?](#what-is-proof-of-spacetime)                                                                                   |
| 248 | [What is proof of storage?](#what-is-proof-of-storage)                                                                                       |
| 249 | [What is retrieval mining?](#what-is-retrieval-mining)                                                                                       |
| 250 | [What is storage mining?](#what-is-storage-mining)                                                                                           |
| 251 | [What is NFT metadata storage?](#what-is-nft-metadata-storage)                                                                               |
| 252 | [What is NFT royalties?](#what-is-nft-royalties)                                                                                             |
| 253 | [What is NFT fractionalization?](#what-is-nft-fractionalization)                                                                             |
| 254 | [What is dynamic NFT?](#what-is-dynamic-nft)                                                                                                 |
| 255 | [What is soulbound token (SBT)?](#what-is-soulbound-token-sbt)                                                                               |
| 256 | [What is proof of attendance protocol (POAP)?](#what-is-proof-of-attendance-protocol-poap)                                                   |
| 257 | [What is NFT lending/borrowing?](#what-is-nft-lending-borrowing)                                                                             |
| 258 | [What is NFT marketplace design?](#what-is-nft-marketplace-design)                                                                           |
| 259 | [What is Dutch auction for NFTs?](#what-is-dutch-auction-for-nfts)                                                                           |
| 260 | [What is bonding curve?](#what-is-bonding-curve)                                                                                             |
| 261 | [What is automated market making curve?](#what-is-automated-market-making-curve)                                                             |
| 262 | [What is constant product formula?](#what-is-constant-product-formula)                                                                       |
| 263 | [What is constant sum formula?](#what-is-constant-sum-formula)                                                                               |
| 264 | [What is constant mean formula?](#what-is-constant-mean-formula)                                                                             |
| 265 | [What is concentrated liquidity?](#what-is-concentrated-liquidity)                                                                           |
| 266 | [What is just-in-time (JIT) liquidity?](#what-is-just-in-time-jit-liquidity)                                                                 |
| 267 | [What is MEV protection?](#what-is-mev-protection)                                                                                           |
| 268 | [What is private mempool?](#what-is-private-mempool)                                                                                         |
| 269 | [What is commit-reveal schemes?](#what-is-commit-reveal-schemes)                                                                             |
| 270 | [What is fair ordering protocols?](#what-is-fair-ordering-protocols)                                                                         |
| 271 | [What is batch auction?](#what-is-batch-auction)                                                                                             |
| 272 | [What is time-weighted average price (TWAP)?](#what-is-time-weighted-average-price-twap)                                                     |
| 273 | [What is volume-weighted average price (VWAP)?](#what-is-volume-weighted-average-price-vwap)                                                 |
| 274 | [What is constant function market maker (CFMM)?](#what-is-constant-function-market-maker-cfmm)                                               |
| 275 | [What is dynamic market making?](#what-is-dynamic-market-making)                                                                             |
| 276 | [What is algorithmic trading on DEX?](#what-is-algorithmic-trading-on-dex)                                                                   |
| 277 | [What is arbitrage trading?](#what-is-arbitrage-trading)                                                                                     |
| 278 | [What is triangular arbitrage?](#what-is-triangular-arbitrage)                                                                               |
| 279 | [What is statistical arbitrage?](#what-is-statistical-arbitrage)                                                                             |
| 280 | [What is market making strategies?](#what-is-market-making-strategies)                                                                       |
| 281 | [What is grid trading?](#what-is-grid-trading)                                                                                               |
| 282 | [What is mean reversion trading?](#what-is-mean-reversion-trading)                                                                           |
| 283 | [What is momentum trading?](#what-is-momentum-trading)                                                                                       |
| 284 | [What is dollar-cost averaging (DCA)?](#what-is-dollar-cost-averaging-dca)                                                                   |
| 285 | [What is rebalancing strategies?](#what-is-rebalancing-strategies)                                                                           |
| 286 | [What is portfolio optimization?](#what-is-portfolio-optimization)                                                                           |
| 287 | [What is risk management in DeFi?](#what-is-risk-management-in-defi)                                                                         |
| 288 | [What is value at risk (VaR)?](#what-is-value-at-risk-var)                                                                                   |
| 289 | [What is liquidity risk?](#what-is-liquidity-risk)                                                                                           |
| 290 | [What is smart contract risk?](#what-is-smart-contract-risk)                                                                                 |
| 291 | [What is oracle risk?](#what-is-oracle-risk)                                                                                                 |
| 292 | [What is governance risk?](#what-is-governance-risk)                                                                                         |
| 293 | [What is regulatory risk?](#what-is-regulatory-risk)                                                                                         |
| 294 | [What is counterparty risk?](#what-is-counterparty-risk)                                                                                     |
| 295 | [What is systemic risk in DeFi?](#what-is-systemic-risk-in-defi)                                                                             |
| 296 | [What is correlation risk?](#what-is-correlation-risk)                                                                                       |
| 297 | [What is basis risk?](#what-is-basis-risk)                                                                                                   |
| 298 | [What is tail risk?](#what-is-tail-risk)                                                                                                     |
| 299 | [What is black swan events in crypto?](#what-is-black-swan-events-in-crypto)                                                                 |
| 300 | [What is stress testing for DeFi protocols?](#what-is-stress-testing-for-defi-protocols)                                                     |

---

## 1. What is Blockchain?

Blockchain is a **distributed ledger technology** that maintains a continuously growing list of records (blocks) linked and secured using cryptography.

**Detailed Explanation:**
Blockchain combines cryptographic hashing, peer-to-peer networking, and consensus mechanisms to create an immutable, transparent database. Each block contains transaction data, timestamp, and the hash of the previous block, forming an unbreakable chain. The distributed nature means no single point of failure, while cryptographic security ensures data integrity. This enables trustless transactions without intermediaries, solving the double-spending problem in digital currencies and enabling programmable money through smart contracts.

**[⬆ Back to Top](#-table-of-contents)**

## 2. What is the difference between Blockchain and traditional databases?

Blockchain is **decentralized and immutable**, while traditional databases are **centralized and mutable** with administrator control.

**Detailed Explanation:**

| Aspect         | Blockchain                | Traditional Database |
| -------------- | ------------------------- | -------------------- |
| Architecture   | Distributed across nodes  | Centralized server   |
| Data Integrity | Cryptographically secured | Admin-controlled     |
| Trust Model    | Trustless                 | Requires trust       |
| Performance    | Slower (consensus)        | Faster (direct CRUD) |
| Consistency    | Eventually consistent     | ACID properties      |
| Scalability    | Limited by consensus      | Highly scalable      |

Traditional databases excel in enterprise applications requiring fast queries and complex relationships. Blockchain is optimal for trustless interactions, immutable audit trails, and decentralized coordination without intermediaries.

**[⬆ Back to Top](#-table-of-contents)**

## 3. What are the key characteristics of Blockchain?

**Decentralization, immutability, transparency, security, consensus, and programmability** are the core characteristics.

**Detailed Explanation:**

- **Decentralization:** No single point of control or failure
- **Immutability:** Data cannot be altered once recorded
- **Transparency:** All transactions publicly verifiable
- **Security:** Cryptographic protection at multiple layers
- **Consensus:** Network agreement on validity without central authority
- **Programmability:** Smart contract capabilities for automation

**[⬆ Back to Top](#-table-of-contents)**

## 4. What is a smart contract?

A smart contract is a **self-executing contract with terms directly written into code** that automatically enforces agreements when predetermined conditions are met.

**Detailed Explanation:**
Smart contracts are deterministic programs deployed on blockchain networks that execute automatically when triggered. They contain business logic, state variables, and functions that manipulate data based on predefined rules. Once deployed, they operate autonomously without human intervention, eliminating intermediaries and reducing costs. Common applications include decentralized finance (automated loans, trading), supply chain tracking, insurance claims processing, and governance systems.

**[⬆ Back to Top](#-table-of-contents)**

## 5. What is Solidity?

Solidity is a **statically-typed programming language** designed for writing smart contracts on Ethereum and EVM-compatible blockchains.

**Detailed Explanation:**
Solidity draws syntax inspiration from JavaScript, C++, and Python while being purpose-built for smart contract development. It features object-oriented programming with inheritance, libraries, and complex data types. The language compiles to EVM bytecode and includes blockchain-specific features like gas optimization, event emission, and cryptographic functions.

**[⬆ Back to Top](#-table-of-contents)**

## 6. What are the different types of blockchain networks?

**Public, private, consortium, and hybrid** blockchains serve different use cases and access models.

**Detailed Explanation:**

- **Public blockchains:** Fully open, permissionless networks (Bitcoin, Ethereum)
- **Private blockchains:** Restricted access to specific organizations
- **Consortium blockchains:** Semi-decentralized, controlled by a group
- **Hybrid blockchains:** Combine public and private elements

**[⬆ Back to Top](#-table-of-contents)**

## 7. What is consensus mechanism?

A consensus mechanism is a **protocol that enables distributed nodes to agree on the blockchain's state** without requiring central authority.

**Detailed Explanation:**
Consensus mechanisms solve the fundamental problem of achieving agreement in distributed systems where participants may be malicious or unreliable. They ensure all nodes maintain identical ledger copies while preventing double-spending and maintaining network integrity. Different mechanisms balance security, scalability, and decentralization.

**[⬆ Back to Top](#-table-of-contents)**

## 8. What is the difference between Proof of Work and Proof of Stake?

**PoW uses computational power for mining**, while **PoS uses economic stake for validation** with different security and efficiency models.

**Detailed Explanation:**

- **Proof of Work:** Miners solve cryptographic puzzles, high energy consumption, battle-tested security
- **Proof of Stake:** Validators chosen by stake amount, low energy, economic penalties for malicious behavior

**[⬆ Back to Top](#-table-of-contents)**

## 9. What is a block?

A block is a **data structure containing transaction data, timestamp, and cryptographic link to the previous block** in the blockchain.

**Detailed Explanation:**
Each block consists of a header (previous block hash, Merkle root, timestamp, nonce) and body (transaction data). Blocks are cryptographically linked through hash pointers, ensuring immutability. Block size limits affect transaction throughput and network performance.

**[⬆ Back to Top](#-table-of-contents)**

## 10. What is a hash function?

A hash function is a **mathematical algorithm that converts input data of any size into a fixed-size output** with specific cryptographic properties.

**Detailed Explanation:**
Cryptographic hash functions provide deterministic output, avalanche effect, and one-way computation. They're collision-resistant and provide the foundation for blockchain security, including block linking, data integrity verification, and proof-of-work mining.

**[⬆ Back to Top](#-table-of-contents)**

## 11. What is gas in Ethereum?

Gas is a **unit measuring computational effort required for operations**, paid in ETH to prevent infinite loops and spam.

**Detailed Explanation:**
Gas serves as Ethereum's resource allocation mechanism. Each operation consumes specific gas amounts. Users set gas price and limit, with total cost = gas used × gas price. EIP-1559 introduced base fee burning and priority fees for more predictable fee estimation.

**[⬆ Back to Top](#-table-of-contents)**

## 12. What are function modifiers in Solidity?

Function modifiers are **reusable code snippets that modify function behavior**, typically used for access control and validation.

**Detailed Explanation:**
Modifiers contain code executing before/after main function logic using `_` placeholder. Common uses include access control (onlyOwner), state validation (nonReentrant), and pre/post conditions. They improve code reusability and security.

**[⬆ Back to Top](#-table-of-contents)**

## 13. What is the difference between memory and storage in Solidity?

**Storage is persistent blockchain storage**, while **memory is temporary function-scope storage** with different gas costs.

**Detailed Explanation:**

- **Storage:** Persistent, expensive, organized in 256-bit slots
- **Memory:** Temporary during execution, cheaper, linear and expandable
- **Calldata:** Read-only memory for function parameters, cheapest option

**[⬆ Back to Top](#-table-of-contents)**

## 14. What are events in Solidity?

Events are **logging mechanisms that emit data for external consumption** by dApps and blockchain indexers.

**Detailed Explanation:**
Events provide cheap logging for blockchain applications, storing data in transaction logs. They enable dApps to monitor contract activity and build indexing systems. Events can have indexed parameters (up to 3) for efficient filtering.

**[⬆ Back to Top](#-table-of-contents)**

## 15. What is a reentrancy attack?

A reentrancy attack occurs when **external contracts call back into the original contract before state updates complete**, potentially draining funds.

**Detailed Explanation:**
Reentrancy exploits execution flow where external calls trigger callbacks before the calling contract finishes operations. Prevention includes checks-effects-interactions pattern, reentrancy guards, and pull payment patterns. The DAO hack demonstrated this vulnerability's devastating potential.

**[⬆ Back to Top](#-table-of-contents)**

## 16. What are ERC standards?

ERC (Ethereum Request for Comments) standards are **technical specifications defining common interfaces** for tokens and smart contracts on Ethereum.

**Detailed Explanation:**
ERC standards ensure interoperability between tokens and dApps. Key standards include ERC-20 (fungible tokens), ERC-721 (NFTs), and ERC-1155 (multi-token). These enable wallets, exchanges, and dApps to interact with any compliant token.

**[⬆ Back to Top](#-table-of-contents)**

## 17. What is the difference between ERC-20 and ERC-721?

**ERC-20 defines fungible tokens** (interchangeable units), while **ERC-721 defines non-fungible tokens** (unique digital assets).

**Detailed Explanation:**

- **ERC-20:** Divisible, interchangeable, identical tokens for currencies and utilities
- **ERC-721:** Indivisible, unique tokens for digital art, collectibles, certificates

**[⬆ Back to Top](#-table-of-contents)**

## 18. What is DeFi?

DeFi (Decentralized Finance) is a **blockchain-based financial ecosystem** that recreates traditional financial services without intermediaries.

**Detailed Explanation:**
DeFi leverages smart contracts for permissionless financial services including lending, borrowing, trading, and derivatives. Key benefits include global access, transparency, and composability, but faces challenges like smart contract risks and scalability.

**[⬆ Back to Top](#-table-of-contents)**

## 19. What is an oracle in blockchain?

An oracle is a **bridge that provides external data to smart contracts**, enabling blockchain interaction with real-world information.

**Detailed Explanation:**
Oracles solve the "oracle problem" - blockchains cannot natively access external data. They provide price feeds for DeFi, weather data for insurance, and sports results for betting. Challenges include maintaining decentralization and preventing manipulation.

**[⬆ Back to Top](#-table-of-contents)**

## 20. What is a Merkle tree?

A Merkle tree is a **binary tree structure where each leaf represents transaction data and each node contains the hash of its children**, enabling efficient verification.

**Detailed Explanation:**
Merkle trees allow efficient verification of large data sets through mathematical proofs. They enable light clients to verify transaction inclusion without downloading entire blocks, requiring only the transaction, hash path, and block header.

**[⬆ Back to Top](#-table-of-contents)**

## 21. What is layer 2 scaling?

Layer 2 scaling refers to **protocols built on top of blockchain networks** that increase transaction throughput while inheriting base layer security.

**Detailed Explanation:**
Layer 2 solutions move computation off-chain while maintaining security through cryptographic proofs or fraud detection. Types include optimistic rollups, ZK-rollups, state channels, and sidechains, each with different trade-offs.

**[⬆ Back to Top](#-table-of-contents)**

## 22. What are rollups?

Rollups are **layer 2 solutions that bundle multiple transactions into a single on-chain transaction**, reducing costs while maintaining security.

**Detailed Explanation:**

- **Optimistic rollups:** Assume validity, use fraud proofs during dispute period
- **ZK-rollups:** Use zero-knowledge proofs for immediate validity verification

**[⬆ Back to Top](#-table-of-contents)**

## 23. What is a 51% attack?

A 51% attack occurs when **an entity controls majority network power**, enabling transaction reversal and double-spending.

**Detailed Explanation:**
Controlling >50% of hash rate (PoW) or stake (PoS) allows attackers to manipulate the longest chain. However, such attacks are economically irrational in healthy networks due to massive costs and value destruction.

**[⬆ Back to Top](#-table-of-contents)**

## 24. What is cryptocurrency mining?

Cryptocurrency mining is the **process of validating transactions and creating new blocks** through computational work in proof-of-work systems.

**Detailed Explanation:**
Miners compete to solve cryptographic puzzles, with the first valid solution receiving block rewards. Mining serves three purposes: transaction validation, network security, and currency distribution.

**[⬆ Back to Top](#-table-of-contents)**

## 25. What is a wallet?

A wallet is a **software or hardware tool that manages private keys** and enables interaction with blockchain networks.

**Detailed Explanation:**
Wallets don't store cryptocurrency but manage cryptographic keys. Types include hot wallets (online, convenient) and cold wallets (offline, secure). Features include address generation, transaction signing, and blockchain interface.

**[⬆ Back to Top](#-table-of-contents)**

## 26. What is the double-spending problem?

The double-spending problem is the **risk of digital currency being spent multiple times**, which blockchain solves through consensus and immutability.

**Detailed Explanation:**
Unlike physical currency, digital files can be copied. Blockchain solves this through distributed consensus - the network agrees on transaction order and validity. Once confirmed and included in the blockchain, the same inputs cannot be spent again.

**[⬆ Back to Top](#-table-of-contents)**

## 27. What is Byzantine Fault Tolerance?

Byzantine Fault Tolerance is the **ability of distributed systems to continue operating correctly** despite some nodes acting maliciously or failing arbitrarily.

**Detailed Explanation:**
BFT systems can tolerate up to 1/3 of nodes being faulty while maintaining correct operation. PBFT algorithms ensure safety and liveness through multiple communication rounds and cryptographic signatures.

**[⬆ Back to Top](#-table-of-contents)**

## 28. What is sharding?

Sharding is a **scaling technique that partitions blockchain state and processing** across multiple parallel chains to increase throughput.

**Detailed Explanation:**
Sharding divides the blockchain into smaller pieces that process transactions in parallel. Each shard maintains a portion of global state. Challenges include maintaining security with smaller validator sets and managing cross-shard communication.

**[⬆ Back to Top](#-table-of-contents)**

## 29. What are zero-knowledge proofs?

Zero-knowledge proofs are **cryptographic methods proving knowledge of information without revealing the information itself**.

**Detailed Explanation:**
ZK proofs enable privacy-preserving verification with three properties: completeness, soundness, and zero-knowledge. zk-SNARKs provide succinct proofs but require trusted setup. zk-STARKs are transparent and quantum-resistant.

**[⬆ Back to Top](#-table-of-contents)**

## 30. What is MEV (Maximal Extractable Value)?

MEV is the **maximum value extractable by reordering, including, or excluding transactions** within blocks beyond standard fees.

**Detailed Explanation:**
MEV arises from transaction ordering control. Common extraction methods include arbitrage, liquidations, and sandwich attacks. Solutions include MEV-resistant AMMs, fair ordering protocols, and private mempools.

**[⬆ Back to Top](#-table-of-contents)**

## 31. What is a DAO?

A DAO (Decentralized Autonomous Organization) is an **organization governed by smart contracts and token holders** rather than traditional management structures.

**Detailed Explanation:**
DAOs enable collective decision-making through token-based voting. Governance proposals are voted on by token holders, with smart contracts executing approved decisions. Challenges include voter apathy and governance attacks.

**[⬆ Back to Top](#-table-of-contents)**

## 32. What is IPFS?

IPFS (InterPlanetary File System) is a **distributed file system that uses content addressing** to create permanent, decentralized file storage.

**Detailed Explanation:**
IPFS addresses files by content hash rather than location, ensuring integrity and enabling deduplication. Files are distributed across network nodes, providing redundancy and censorship resistance.

**[⬆ Back to Top](#-table-of-contents)**

## 33. What is cross-chain interoperability?

Cross-chain interoperability is the **ability for different blockchain networks to communicate and exchange value or data**.

**Detailed Explanation:**
Enables asset transfers, data sharing, and protocol interaction across chains. Solutions include bridges, relay chains, and atomic swaps. Challenges involve maintaining security and handling different consensus mechanisms.

**[⬆ Back to Top](#-table-of-contents)**

## 34. What is a bridge in blockchain?

A bridge is a **protocol that connects two blockchain networks**, enabling asset and data transfer between them.

**Detailed Explanation:**
Bridges lock assets on one chain and mint representations on another. Types include trusted bridges (centralized operators) and trustless bridges (smart contract-based). Security risks include centralization and smart contract vulnerabilities.

**[⬆ Back to Top](#-table-of-contents)**

## 35. What is staking?

Staking is the **process of locking cryptocurrency to participate in network validation** and earn rewards in proof-of-stake systems.

**Detailed Explanation:**
Validators stake tokens as collateral to propose and validate blocks. Rewards are earned for honest behavior, while malicious actions result in stake slashing. Enables network security without energy-intensive mining.

**[⬆ Back to Top](#-table-of-contents)**

## 36. What are the different types of keys in cryptography?

**Symmetric keys (shared secret) and asymmetric keys (public-private pairs)** are the main cryptographic key types.

**Detailed Explanation:**
Symmetric keys use the same key for encryption/decryption (fast, shared secret required). Asymmetric keys use key pairs where public keys encrypt and private keys decrypt (slower, no shared secret needed).

**[⬆ Back to Top](#-table-of-contents)**

## 37. What is a nonce?

A nonce is a **number used once in cryptographic operations** to ensure uniqueness and prevent replay attacks.

**Detailed Explanation:**
In blockchain, nonces serve multiple purposes: proof-of-work mining (finding valid block hash), transaction ordering (preventing replay), and randomness generation. Each use ensures one-time validity.

**[⬆ Back to Top](#-table-of-contents)**

## 38. What is finality in blockchain?

Finality is the **guarantee that a transaction cannot be altered or reversed** once confirmed.

**Detailed Explanation:**
Probabilistic finality (Bitcoin) increases confidence over time with more confirmations. Instant finality (some PoS systems) provides immediate assurance. Finality time affects user experience and system usability.

**[⬆ Back to Top](#-table-of-contents)**

## 39. What is slashing?

Slashing is the **penalty mechanism that destroys a validator's stake** for malicious or negligent behavior in proof-of-stake systems.

**Detailed Explanation:**
Validators lose staked tokens for actions like double-signing, going offline, or attacking the network. Slashing rates vary by severity. Creates economic incentives for honest behavior and network security.

**[⬆ Back to Top](#-table-of-contents)**

## 40. What is the blockchain trilemma?

The blockchain trilemma refers to the **trade-off between decentralization, security, and scalability** where improving one often compromises others.

**Detailed Explanation:**
Traditional blockchains struggle to optimize all three simultaneously. Bitcoin prioritizes security and decentralization over scalability. Various solutions attempt to solve this through layer 2 scaling and consensus innovations.

**[⬆ Back to Top](#-table-of-contents)**

## 41. What is the difference between public and private keys?

**Public keys are shareable for receiving funds**, while **private keys must remain secret for spending control**.

**Detailed Explanation:**
Public keys derive from private keys and create wallet addresses. Private keys enable digital signatures and transaction authorization. Losing private keys means permanent loss of access to funds.

**[⬆ Back to Top](#-table-of-contents)**

## 42. What is a digital signature?

A digital signature is a **cryptographic proof that verifies message authenticity and sender identity** using private key encryption.

**Detailed Explanation:**
Digital signatures use asymmetric cryptography where private keys sign messages and public keys verify signatures. They provide authentication, non-repudiation, and integrity verification for blockchain transactions.

**[⬆ Back to Top](#-table-of-contents)**

## 43. What is elliptic curve cryptography?

Elliptic curve cryptography is a **public key cryptography approach using elliptic curve mathematics** for efficient security.

**Detailed Explanation:**
ECC provides equivalent security to RSA with smaller key sizes, improving performance and storage efficiency. Bitcoin and Ethereum use the secp256k1 curve for generating key pairs and digital signatures.

**[⬆ Back to Top](#-table-of-contents)**

## 44. What is the purpose of the require function in Solidity?

The require function **validates conditions and reverts execution with error message** if conditions fail.

**Detailed Explanation:**
Used for input validation, access control, and state verification. Refunds remaining gas when failing. Syntax: `require(condition, "error message")`. Essential for smart contract security and user feedback.

**[⬆ Back to Top](#-table-of-contents)**

## 45. What is the difference between assert and revert in Solidity?

**Assert checks internal errors and consumes all gas**, while **revert handles expected failures and refunds gas**.

**Detailed Explanation:**
Assert indicates bugs and should never fail in correct code. Revert handles user errors and business logic failures. Require is preferred over revert for better error messages.

**[⬆ Back to Top](#-table-of-contents)**

## 46. What are view and pure functions in Solidity?

**View functions read blockchain state without modification**, while **pure functions neither read nor modify state**.

**Detailed Explanation:**
View functions access state variables and other contracts but don't change state. Pure functions perform computations without blockchain interaction. Both are gas-free when called externally.

**[⬆ Back to Top](#-table-of-contents)**

## 47. What is the purpose of the payable keyword?

The payable keyword **allows functions and addresses to receive Ether payments**.

**Detailed Explanation:**
Functions marked payable can receive Ether via msg.value. Address payable can receive transfers. Without payable, functions reject Ether transactions. Essential for payment processing in smart contracts.

**[⬆ Back to Top](#-table-of-contents)**

## 48. What is a fallback function?

A fallback function is **executed when a contract receives Ether or calls to non-existent functions**.

**Detailed Explanation:**
Triggered when no other function matches the call data. Must be marked payable to receive Ether. Used for simple payments or proxy patterns. Limited gas available from external calls.

**[⬆ Back to Top](#-table-of-contents)**

## 49. What is inheritance in Solidity?

Inheritance allows **contracts to derive properties and functions from parent contracts** using object-oriented principles.

**Detailed Explanation:**
Supports single and multiple inheritance with `is` keyword. Child contracts inherit state variables, functions, and modifiers. Virtual and override keywords enable function customization in derived contracts.

**[⬆ Back to Top](#-table-of-contents)**

## 50. What are interfaces in Solidity?

Interfaces define **contract blueprints with function signatures but no implementation**.

**Detailed Explanation:**
Cannot have state variables, constructors, or function implementations. Used for contract interaction standards and ensuring compatibility. All functions are implicitly virtual and external.

**[⬆ Back to Top](#-table-of-contents)**

## 51. What are libraries in Solidity?

Libraries are **reusable code deployed once and called by multiple contracts** to reduce deployment costs.

**Detailed Explanation:**
Cannot have state variables or receive Ether. Functions execute in calling contract's context. Linked at compile time or deployed separately. Used for common mathematical operations and utilities.

**[⬆ Back to Top](#-table-of-contents)**

## 52. What is the difference between delegatecall and call?

**Delegatecall executes code in the caller's context**, while **call executes in the called contract's context**.

**Detailed Explanation:**
Delegatecall preserves msg.sender and msg.value, modifying caller's storage. Call changes context to called contract. Delegatecall enables proxy patterns and upgradeable contracts.

**[⬆ Back to Top](#-table-of-contents)**

## 53. What are mappings in Solidity?

Mappings are **hash tables that store key-value pairs** with unique keys and deterministic storage locations.

**Detailed Explanation:**
Syntax: `mapping(keyType => valueType)`. Keys cannot be enumerated, and non-existent keys return default values. Efficient for large datasets and user balances. Storage-only, not available in memory.

**[⬆ Back to Top](#-table-of-contents)**

## 54. What is struct packing?

Struct packing is **optimizing storage by arranging variables to minimize storage slots** and reduce gas costs.

**Detailed Explanation:**
Solidity packs variables into 32-byte storage slots. Ordering smaller types together reduces slots used. Example: `uint128` + `uint128` = 1 slot, but `uint256` + `uint128` = 2 slots.

**[⬆ Back to Top](#-table-of-contents)**

## 55. What are immutable and constant variables?

**Constant variables are set at compile time**, while **immutable variables are set during deployment** and never change afterward.

**Detailed Explanation:**
Constants must be assigned at declaration with literal values. Immutable variables can be set in constructor with computed values. Both save gas by avoiding storage reads.

**[⬆ Back to Top](#-table-of-contents)**

## 56. What is the receive function?

The receive function **handles plain Ether transfers with no call data** to a contract.

**Detailed Explanation:**
Replaces unnamed payable fallback for simple payments. Syntax: `receive() external payable {}`. Limited to 2300 gas from transfer/send. Used for contracts that accept donations or payments.

**[⬆ Back to Top](#-table-of-contents)**

## 57. What are custom errors in Solidity?

Custom errors are **user-defined error types that provide gas-efficient error handling** with descriptive names and parameters.

**Detailed Explanation:**
Defined with `error` keyword and thrown with `revert`. More gas-efficient than string error messages. Enable structured error handling and better debugging information.

**[⬆ Back to Top](#-table-of-contents)**

## 58. What is the difference between tx.origin and msg.sender?

**tx.origin is the original external account that initiated the transaction**, while **msg.sender is the immediate caller of the current function**.

**Detailed Explanation:**
tx.origin remains constant throughout the call chain. msg.sender changes with each internal call. Using tx.origin for authentication enables phishing attacks, so msg.sender is preferred.

**[⬆ Back to Top](#-table-of-contents)**

## 59. What are proxy patterns?

Proxy patterns **separate contract logic from data storage** to enable upgradeable smart contracts.

**Detailed Explanation:**
Proxy contracts forward calls to implementation contracts using delegatecall. Storage remains in proxy while logic can be upgraded by changing implementation address. Enables bug fixes and feature additions.

**[⬆ Back to Top](#-table-of-contents)**

## 60. What is the transparent proxy pattern?

The transparent proxy pattern **uses admin/user distinction to prevent function selector collisions** between proxy and implementation.

**Detailed Explanation:**
Admin calls interact with proxy functions, user calls forward to implementation. Prevents conflicts when proxy and implementation have same function signatures. Adds gas overhead for admin checks.

**[⬆ Back to Top](#-table-of-contents)**

## 61. What is UUPS (Universal Upgradeable Proxy Standard)?

UUPS is **a proxy pattern where upgrade logic resides in the implementation contract** rather than the proxy.

**Detailed Explanation:**
More gas-efficient than transparent proxy as no admin checks needed. Implementation contracts control their own upgrades. Risk of deploying non-upgradeable implementation that breaks upgrade path.

**[⬆ Back to Top](#-table-of-contents)**

## 62. What is the diamond pattern?

The diamond pattern **enables unlimited contract size by using multiple implementation contracts** (facets) with a single proxy.

**Detailed Explanation:**
Function selectors map to different facet contracts. Enables modular upgrades and overcomes contract size limits. More complex to implement but provides maximum flexibility.

**[⬆ Back to Top](#-table-of-contents)**

## 63. What are the risks of upgradeable contracts?

Risks include **centralization of upgrade control, storage layout conflicts, and potential for malicious upgrades**.

**Detailed Explanation:**
Admin keys create single points of failure. Storage layout changes can corrupt data. Malicious upgrades can steal funds. Mitigation includes timelock delays, multisig governance, and careful testing.

**[⬆ Back to Top](#-table-of-contents)**

## 64. What are time locks in smart contracts?

Time locks are **delay mechanisms that prevent immediate execution of critical operations** for security and governance.

**Detailed Explanation:**
Proposed changes must wait a specified period before execution. Enables community review and emergency response. Used in governance systems and upgradeable contracts for security.

**[⬆ Back to Top](#-table-of-contents)**

## 65. What is integer overflow/underflow?

Integer overflow/underflow occurs when **arithmetic operations exceed variable type limits**, potentially causing unexpected behavior.

**Detailed Explanation:**
Solidity 0.8+ includes automatic overflow checks. Earlier versions required SafeMath library. Can lead to security vulnerabilities like balance manipulation or access control bypass.

**[⬆ Back to Top](#-table-of-contents)**

## 66. What is front-running?

Front-running is **exploiting knowledge of pending transactions** to place profitable transactions before them execute.

**Detailed Explanation:**
Attackers monitor mempool for profitable opportunities, then submit transactions with higher gas prices to execute first. Common in DEX trading and NFT minting. Mitigation includes commit-reveal schemes and private mempools.

**[⬆ Back to Top](#-table-of-contents)**

## 67. What is sandwich attacking?

Sandwich attacking is **front-running and back-running a target transaction** to extract value through price manipulation.

**Detailed Explanation:**
Attacker places buy order before and sell order after victim's trade, profiting from price impact. Requires significant capital and precise timing. Protected against with slippage limits and MEV protection services.

**[⬆ Back to Top](#-table-of-contents)**

## 68. What is flash loan attack?

Flash loan attacks **borrow large amounts without collateral within single transaction** to exploit protocol vulnerabilities.

**Detailed Explanation:**
Borrows must be repaid in same transaction or it reverts. Enables arbitrage, liquidations, and complex exploit strategies. Protocols must account for flash loan scenarios in their security models.

**[⬆ Back to Top](#-table-of-contents)**

## 69. What is oracle manipulation?

Oracle manipulation involves **attacking price feeds to exploit protocols** that rely on external data sources.

**Detailed Explanation:**
Attackers manipulate underlying markets or oracle mechanisms to report false prices. Can trigger liquidations or enable profitable trades. Mitigation includes multiple oracles, time delays, and circuit breakers.

**[⬆ Back to Top](#-table-of-contents)**

## 70. What is governance attack?

Governance attacks **exploit voting mechanisms to gain unauthorized control** over protocol parameters or funds.

**Detailed Explanation:**
Methods include vote buying, flash loan governance, and proposal spam. Can result in parameter changes, fund extraction, or protocol shutdown. Protection includes vote delegation, time locks, and proposal thresholds.

**[⬆ Back to Top](#-table-of-contents)**

## 71. What are time-based attacks?

Time-based attacks **exploit predictable timestamp or block number dependencies** in smart contract logic.

**Detailed Explanation:**
Miners can manipulate timestamps within bounds. Block numbers are predictable. Contracts shouldn't rely on precise timing for critical security decisions. Use block hash randomness carefully.

**[⬆ Back to Top](#-table-of-contents)**

## 72. What is the verifier's dilemma?

The verifier's dilemma describes **the conflict between verification costs and network security** in blockchain systems.

**Detailed Explanation:**
Full verification is expensive, incentivizing users to trust others. This reduces decentralization and security. Solutions include fraud proofs, sampling techniques, and efficient verification methods.

**[⬆ Back to Top](#-table-of-contents)**

## 73. What are Sybil attacks?

Sybil attacks involve **creating multiple fake identities to gain disproportionate influence** in network decisions.

**Detailed Explanation:**
Attackers create numerous nodes or accounts to manipulate consensus, voting, or reputation systems. Prevented through proof-of-work, proof-of-stake, or identity verification mechanisms.

**[⬆ Back to Top](#-table-of-contents)**

## 74. What is censorship resistance?

Censorship resistance is **the ability to prevent transaction or content blocking** by any single authority.

**Detailed Explanation:**
Achieved through decentralization, where no single entity controls the network. Multiple miners/validators ensure transactions cannot be permanently blocked. Essential for permissionless financial systems.

**[⬆ Back to Top](#-table-of-contents)**

## 75. What is key extraction attack?

Key extraction attacks **recover private keys through side-channel analysis** or cryptographic weaknesses.

**Detailed Explanation:**
Methods include timing attacks, power analysis, and mathematical cryptanalysis. Prevented through secure hardware, proper randomness, and constant-time algorithms. Critical for wallet and exchange security.

**[⬆ Back to Top](#-table-of-contents)**

## 76. What are smart contract security best practices?

Best practices include **input validation, access controls, reentrancy guards, and comprehensive testing**.

**Detailed Explanation:**
Use established patterns, avoid external calls in loops, implement circuit breakers, conduct formal verification, and maintain upgrade mechanisms. Regular audits and bug bounties enhance security.

**[⬆ Back to Top](#-table-of-contents)**

## 77. How do you secure private keys?

Private key security involves **hardware storage, multi-signature schemes, and air-gapped environments**.

**Detailed Explanation:**
Use hardware wallets, never store plaintext keys online, implement key splitting, use secure random generation, and maintain offline backups. Consider social recovery mechanisms for accessibility.

**[⬆ Back to Top](#-table-of-contents)**

## 78. What is defense in depth for blockchain?

Defense in depth applies **multiple security layers to protect against various attack vectors** in blockchain systems.

**Detailed Explanation:**
Combines network security, smart contract audits, formal verification, monitoring systems, incident response, and user education. No single point of failure should compromise the entire system.

**[⬆ Back to Top](#-table-of-contents)**

## 79. What is formal verification?

Formal verification uses **mathematical methods to prove smart contract correctness** against specifications.

**Detailed Explanation:**
Provides stronger guarantees than testing by proving all possible execution paths. Tools include model checkers and theorem provers. Expensive but valuable for high-stakes contracts.

**[⬆ Back to Top](#-table-of-contents)**

## 80. What are bug bounty programs?

Bug bounty programs **incentivize security researchers to find and report vulnerabilities** before malicious exploitation.

**Detailed Explanation:**
Offer rewards proportional to vulnerability severity. Create responsible disclosure channels and clear scope guidelines. Help identify issues missed by internal audits and formal verification.

**[⬆ Back to Top](#-table-of-contents)**

## 81. What is ERC-1155?

ERC-1155 is a **multi-token standard supporting both fungible and non-fungible tokens** in a single contract.

**Detailed Explanation:**
Enables batch operations, reducing gas costs for multiple token transfers. Supports metadata for both token types. Popular for gaming applications with multiple asset types.

**[⬆ Back to Top](#-table-of-contents)**

## 82. What is ERC-777?

ERC-777 is an **advanced fungible token standard with hooks and operators** for enhanced functionality.

**Detailed Explanation:**
Provides send/receive hooks for custom logic, authorized operators for delegation, and backwards compatibility with ERC-20. Enables more sophisticated token behaviors and integrations.

**[⬆ Back to Top](#-table-of-contents)**

## 83. What is ERC-4626?

ERC-4626 is a **standardized vault interface for yield-bearing tokens** in DeFi protocols.

**Detailed Explanation:**
Defines common interface for depositing tokens and receiving yield-bearing shares. Enables composability between yield strategies and aggregation protocols. Simplifies integration for DeFi applications.

**[⬆ Back to Top](#-table-of-contents)**

## 84. What are wrapped tokens?

Wrapped tokens are **tokenized representations of assets from other blockchains** or traditional systems.

**Detailed Explanation:**
Enable cross-chain asset usage by locking original assets and minting equivalent tokens. Examples include WETH (Wrapped Ether) and WBTC (Wrapped Bitcoin). Require trusted custodians or bridge protocols.

**[⬆ Back to Top](#-table-of-contents)**

## 85. What is token burning?

Token burning is **permanently removing tokens from circulation** to reduce total supply.

**Detailed Explanation:**
Sends tokens to unrecoverable addresses (burn address). Often used to increase scarcity and value for remaining holders. Common in deflationary tokenomics and protocol revenue distribution.

**[⬆ Back to Top](#-table-of-contents)**

## 86. What are governance tokens?

Governance tokens **grant voting rights in decentralized protocol management** and parameter decisions.

**Detailed Explanation:**
Enable community control over protocol upgrades, parameter changes, and treasury allocation. Voting power typically proportional to token holdings. Key component of DAO governance systems.

**[⬆ Back to Top](#-table-of-contents)**

## 87. What is token vesting?

Token vesting **gradually releases tokens over time** to align long-term incentives and prevent immediate selling.

**Detailed Explanation:**
Common for team tokens, investor allocations, and employee compensation. Prevents market dumping and ensures continued participation. Implemented through time-locked smart contracts.

**[⬆ Back to Top](#-table-of-contents)**

## 88. What are utility tokens vs security tokens?

**Utility tokens provide access to products/services**, while **security tokens represent investment contracts** with profit expectations.

**Detailed Explanation:**
Utility tokens grant platform usage rights. Security tokens offer ownership stakes or profit-sharing. Regulatory treatment differs significantly, with securities requiring compliance with investment laws.

**[⬆ Back to Top](#-table-of-contents)**

## 89. What are stablecoins?

Stablecoins are **cryptocurrencies designed to maintain stable value** relative to reference assets like USD.

**Detailed Explanation:**
Types include fiat-collateralized (USDC), crypto-collateralized (DAI), and algorithmic (UST). Provide price stability for DeFi applications while maintaining blockchain benefits.

**[⬆ Back to Top](#-table-of-contents)**

## 90. What is an Automated Market Maker (AMM)?

An AMM is a **decentralized exchange protocol using mathematical formulas** instead of order books for trading.

**Detailed Explanation:**
Enables permissionless trading through liquidity pools and algorithmic pricing. Users trade against pools rather than other users. Examples include Uniswap's constant product formula.

**[⬆ Back to Top](#-table-of-contents)**

## 91. How does Uniswap work?

Uniswap uses **constant product formula (x \* y = k) to determine token prices** based on liquidity pool ratios.

**Detailed Explanation:**
Liquidity providers deposit token pairs, earning fees from trades. Price determined by ratio changes after swaps. Automated market making eliminates need for order books and centralized matching.

**[⬆ Back to Top](#-table-of-contents)**

## 92. What is impermanent loss?

Impermanent loss is the **opportunity cost of providing liquidity versus holding tokens** when prices diverge.

**Detailed Explanation:**
Occurs when token prices change after depositing to liquidity pools. Loss is "impermanent" because it disappears if prices return to original ratio. Compensated by trading fees over time.

**[⬆ Back to Top](#-table-of-contents)**

## 93. What is slippage in DEX trading?

Slippage is the **difference between expected and actual execution prices** due to market movement or low liquidity.

**Detailed Explanation:**
Large trades relative to liquidity cause price impact. High volatility increases slippage risk. Traders set maximum slippage tolerance to prevent unfavorable execution.

**[⬆ Back to Top](#-table-of-contents)**

## 94. What are liquidity pools?

Liquidity pools are **smart contracts holding token reserves** that enable automated trading and earning fees.

**Detailed Explanation:**
Liquidity providers deposit tokens and receive LP tokens representing their share. Pools facilitate trades through AMM algorithms. Providers earn proportional fees from all trading activity.

**[⬆ Back to Top](#-table-of-contents)**

## 95. What is yield farming?

Yield farming is **optimizing returns by moving funds between DeFi protocols** to earn highest yields.

**Detailed Explanation:**
Involves lending, providing liquidity, staking, and claiming rewards across multiple protocols. Requires active management and understanding of various risk factors and reward mechanisms.

**[⬆ Back to Top](#-table-of-contents)**

## 96. What is liquidity mining?

Liquidity mining **incentivizes liquidity provision through additional token rewards** beyond trading fees.

**Detailed Explanation:**
Protocols distribute governance tokens to attract liquidity. Creates bootstrap mechanism for new protocols. Participants earn both trading fees and token rewards for providing liquidity.

**[⬆ Back to Top](#-table-of-contents)**

## 97. What are flash loans?

Flash loans are **uncollateralized loans that must be repaid within the same transaction** or revert completely.

**Detailed Explanation:**
Enable arbitrage, liquidations, and complex DeFi strategies without upfront capital. Smart contracts ensure atomic execution - either all operations succeed or transaction reverts entirely.

**[⬆ Back to Top](#-table-of-contents)**

## 98. How do lending protocols work?

Lending protocols **enable users to deposit assets earning interest and borrow against collateral** through smart contracts.

**Detailed Explanation:**
Interest rates determined algorithmically based on supply and demand. Borrowers must maintain collateralization ratios above liquidation thresholds. Enables efficient capital allocation without traditional intermediaries.

**[⬆ Back to Top](#-table-of-contents)**

## 99. What is overcollateralization in DeFi?

Overcollateralization requires **borrowers to deposit collateral worth more than borrowed amount** to account for volatility.

**Detailed Explanation:**
Protects lenders from collateral value decline and borrower default. Typical ratios range from 125-200%. Enables trustless lending without credit checks or personal guarantees.

**[⬆ Back to Top](#-table-of-contents)**

## 100. What is liquidation in DeFi lending?

Liquidation is the **automated sale of collateral when loan-to-value ratios exceed safe thresholds** to protect lenders.

**Detailed Explanation:**
Triggered when collateral value drops below liquidation threshold. Liquidators purchase collateral at discount to repay debt. Incentivizes healthy borrowing ratios and protocol solvency.

**[⬆ Back to Top](#-table-of-contents)**

## 101. What are synthetic assets?

Synthetic assets are **tokenized derivatives that track external asset prices** without requiring direct ownership.

**Detailed Explanation:**
Created through collateralized debt positions or oracle-based pricing. Enable exposure to traditional assets, commodities, or indices on blockchain. Examples include synthetic stocks and commodities.

**[⬆ Back to Top](#-table-of-contents)**

## 102. What is a decentralized exchange (DEX)?

A DEX is a **peer-to-peer trading platform operating through smart contracts** without central authority.

**Detailed Explanation:**
Users maintain custody of funds and trade directly from wallets. No KYC requirements or geographic restrictions. Types include AMM-based (Uniswap) and order book-based (dYdX) exchanges.

**[⬆ Back to Top](#-table-of-contents)**

## 103. What are prediction markets?

Prediction markets are **platforms where users bet on future event outcomes** with market prices reflecting probability estimates.

**Detailed Explanation:**
Enable price discovery for uncertain events through crowd wisdom. Participants buy shares representing outcome beliefs. Prices converge to probability estimates, providing valuable information.

**[⬆ Back to Top](#-table-of-contents)**

## 104. What is composability in DeFi?

Composability is the **ability to combine different DeFi protocols** to create new financial products and services.

**Detailed Explanation:**
Smart contracts can interact seamlessly, enabling complex strategies spanning multiple protocols. Creates "money legos" where protocols build upon each other, fostering innovation and efficiency.

**[⬆ Back to Top](#-table-of-contents)**

## 105. What are money legos?

Money legos refer to **modular DeFi protocols that can be combined** to create complex financial applications.

**Detailed Explanation:**
Each protocol provides specific functionality (lending, trading, derivatives) that others can build upon. Enables rapid innovation through composition rather than rebuilding from scratch.

**[⬆ Back to Top](#-table-of-contents)**

## 106. What is Total Value Locked (TVL)?

TVL measures **the total dollar value of assets deposited in DeFi protocols** as a metric of adoption and scale.

**Detailed Explanation:**
Calculated by summing all deposited assets at current market prices. Use

## 🚀 Contributing

Feel free to contribute additional questions or improve existing explanations by submitting a pull request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.
