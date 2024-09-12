# Epoch Protocol Docs

# **Epoch Protocol - Overview**

The Web3 ecosystem has seen exponential growth in protocols, dApps, and chains in the last few years. For users, this has massively increased the complication of navigating dapps and for developers to integrate with protocols. Transactions often require multi-step processes involving different gas tokens, bridging and swapping, and protocol-specific interactions.

It has also resulted in fragmented liquidity and complex asset management across multiple networks. Multiple rollups, increasing protocols, and shifting paradigms will all add more to the problem and fragment the UX and liquidity even further.

## **Our Solution**

With Epoch Protocol, Users and dApps can give their input using declarative Intents and state constraints, and leave them to purpose-specific intent solvers within Epoch Network to optimise for state flows and necessary state updates, talk to multiple homogeneous and heterogeneous consensus and execution environments, do the right counter-party discovery and ultimately make the final settlement on the desired settlement layers.

Epoch also lets users define conditions for execution with their intents, once those conditions are met, the most optimal state updates are figured out and executed within the constraints for the state set by the user.

## **Unique Approach and Features:**

1. **A Complete Middle Layer for Abstraction:** Epoch Protocol is a middleware layer consisting of Intent Solver Orchestrators, internal and external Intent Solvers, Observers(Hyperions), Transaction Bundlers, and Smart Accounts, that allow dapp and users to interact with web3 in an abstracted manner.
2. **Multiple Purpose-Specific Intent Solvers:** Epoch Protocol allows querying multiple purpose-specific and external solvers to ensure users always get the most optimal settlement.
3. **Observers(Hyperions):** Epoch Protocol has pluggable observers that can constantly monitor the chain to see if desired conditions are met for executing the intent.
4. **Liquidity Pools for bridging:** Epoch's Liquidity Pools are a unique approach to bridging funds, where solvers take on risks of bridging assets and give users their assets instantly on the destination chain and after submitting a valid proof take the assets to be bridged from users on a different chain.
5. **Account Abstraction Power:** The protocol's use of Account Abstraction unlocks advanced wallet permissions management, transaction automation, self-custody of funds, and more flexibility over a transaction getting executed. With the evolving state of Account Abstraction and the advent of ERC-7702 soon EOAs will be able to benefit as well.
6. **Pluggable for All:** Be it users, dApps or protocols, the protocol provides a pluggable solution to cater to diverse needs in the Web3 ecosystem.
    1. DApps can get their users in the right state, get discovered, and be more creative in terms of UX and features to offer users.
    2. On the other hand, Users can be free of the cognitive hurdles of countless choices, complicated multi-step transactions and protocol discovery issues.
7. **State Constraints:** Epoch adds an extra layer of security with on-chain verification of state with wallet-level constraints, so users can ensure the solution achieves the desired state updates.
8. **SAFE Module Integration:** Seamlessly use SAFE vault actions, automate and/or intentify use of funds.

## **What can be done with Epoch right now -**

1. Automating transactions which are time or event-dependent across any dapp in web3 using SAFE smart accounts.
2. Recording/Getting intentions from dApps using wallet connect and transaction hashes.
3. Setting different on-chain event-based triggers for their intents.
4. Deploying SAFE smart accounts for users and gasless transactions.

## **What's coming next -**

1. On-chain verification of execution constraints and conditions.
2. Sub Intent Orchestrators, Hyperions V2 and Modular Intent Solvers - to find the optimal solution for the declarative intents.
3. Epoch Liquidity Pools for instant user-facing bridging of funds.
4. Epoch Registry to allow updating context for future intents and transactions.

**Introducing: Epoch Protocol - An Intent-Centric Abstraction Layer for Web3**

The vision of Epoch is to use the new intent-based interaction paradigm to build an infrastructure layer that completely abstracts away the Web3 complexities for the user such as chains, protocols, gas, balance, and even execution.

# **The Problem of Complexity and Fragmentation in Web3**

### **aka Web3’s Sophies’ Choices**

1. **The Exponential Growth of Protocols, dApps, and Chains**
    
    Users often find it overwhelming to navigate the web3 ecosystem, identify the best protocols, and manage their assets across multiple chains.
    
    These countless choices aren’t just a barrier for new users - they also make it tough for developers to build dApps that might need to interact with other protocols to get the user in the correct state to use their dApp.
    
2. **Fragmented Liquidity and Assets**
    
    Users' funds are often scattered across multiple networks and assets, making fund management and cross-chain dApp interaction a painful task.
    
3. **Mentally Taxing User Experience**
    
    Performing transactions often involve multiple steps, long wait times, and interaction with newer unfamiliar dApps and protocols. Users must deal with different gas tokens, bridges, network conditions, and protocols.
    
4. **Lack of Non-Custodial Automation**
    
    Currently, there is no way to automate transactions in a non-custodial manner, maintaining full control over one's funds. All transactions are manual, requiring users to be terminally online to execute transactions at the right moment. There’s no way to make transactions that depend on and adapt automatically to the ever-changing on-chain and off-chain conditions.
    
5. **Inconsistent Offerings from Protocols**
    
    Different protocols offer varying rates, speeds, fees, privacy, and even MEV protection for the same actions across multiple chains. Aggregators have been great till now for verticals like bridging and swapping but as the variety of things we do on-chain increases even these aggregators would fall short of meeting the exponential growth. This would mean users must spend considerable time and effort finding the best rates for staking, swapping, lending, and other activities.
    
6. **Limited Intent Solvers**
    
    dApps that try to give a one-stop-shop solution for users often have a fixed list of protocols and chains they interact with, which means they cannot always offer the best possible rates or routes for users' transactions. Plus they cannot expand as quickly to the newest chains and protocols that might be more lucrative for users.
    

# **Epoch’s Solution: Using the Intent Paradigm along with Declarative Intent Input, Trigger Observers, Smart Account Level Permissions, and Fast Finality Bridge to offload the problems to sophisticated solvers.**

[https://mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2FqjaMQlqmXsnyL6NZHFhX2.png&w=3840&q=75](https://mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2FqjaMQlqmXsnyL6NZHFhX2.png&w=3840&q=75)

Epoch Protocol sits between users, other protocols, and chains and provably optimizes for best conditions for all the involved steps - it figures out the intent → finds the best routes for desired actions → and/or waits for better routes → automatically performs intermediate steps like bridge funds if deficit → makes necessary swaps → handles the gas payment and ultimately settles user’s or protocol’s intent in a non-custodial way.

**Intent-Centric dApp Discovery** With Epoch’s Composable and Modular Intent Solver, solvers can plug modules specific to certain web3 verticals, protocols, and even other intent solver networks through adapters. They can either propose the most optimal partial solution or a complete solution.

**Multiple Intent Solvers and Optimized Rates** Epoch Protocol provides a network of these modular intent solvers that can join the network and counterparty discovery and solver competition the network can ensure that users always get the most optimal solution.

**Time Abstracted Intent and Execution** Epoch Protocol leverages SAFE smart wallets and account abstraction to offer fully non-custodial automation. Users maintain complete control over their funds while automating transactions based on on-chain or off-chain triggers. This ensures security and convenience without sacrificing control. This will become easier and more widely adopted through EIP-7702, ERC-7579, and ERC-7715 and various other discussions going around Smart Wallets.

**Building an Inter-Compatible Solver Network** At Epoch we believe that the intent solver networks shouldn’t be built in silos. The composability of Epoch Protocol means that through adapters there can be a two-way connection between Epoch Intent Solvers and other intent solvers.

### **Components of Epoch Protocol**

Epoch Architecture

[https://mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2FiO2ZyQboAW7CO2quPD3Rc.png&w=3840&q=75](https://mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2FiO2ZyQboAW7CO2quPD3Rc.png&w=3840&q=75)

**Epoch Node:** Divided into environments like Transaction Bundler, Context Setter, Observer, Composable Solver Environment, and Consensus to handle different stages of intent execution.

- **On-Chain Contracts:** Includes Registry and Gatekeeper, SAFE smart wallets, Epoch Plugin(ERC-7579 compatible), Epoch Hook, Liquidity Pool, and a cross-chain Epoch Paymaster for secure and efficient transaction management.
- **Epoch SDK:** Provides dApp developers with tools to easily integrate, use intent solvers, and automate transactions, reducing development time and effort by not internalising a bunch of protocols and writing custom smart contracts.

# **What does it mean for Users and Protocols**

### **For dApps**

- Simplified user onboarding by automating the acquisition of necessary tokens and positions and bridging - getting users in the correct state.
- Automate transaction execution and permission management for their users.
- Streamlined transactions across multiple chains, reducing the need for integrating and maintaining protocols.

### **For Users**

- Declarative Intent-based input would mean users can give their transaction conditions and triggers in natural language too.
- Automated staking, lending, swapping, social, gaming, and much more based on optimal on-chain conditions.
- Simplified management of fragmented liquidity across chains.
- Better security as intent solvers can pick secure protocols and verify execution.

# **There’s More Coming…**

[https://mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2FO5cgvs6klw4OgN5SWja4C.png&w=3840&q=75](https://mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2FO5cgvs6klw4OgN5SWja4C.png&w=3840&q=75)

We’ll share more information about the Epoch Protocol in the coming days.

We’d love to connect with

- **developers** who can make dApps and Modules for Epoch Protocol
- **dApps** who want to use intents to simplify user and development experience. Give a smoother experience to users.
- **protocols** who’d like to have their modules in the Epoch Module library.

Follow us on Twitter - [@0xEpochProtocol](https://x.com/0xepochprotocol) and Join our Discord Community - [Here](https://discord.com/invite/Pd4yZmqYjb)

# **Support us now and get your Epoch Early Supporters NFT**

Give our dApp a try and you can mint the special edition NFT - app.epochprotocol.xyz

# Litepaper

## **Abstract**

Epoch Protocol is an intent-centric abstraction layer for Web3, designed to leverage the declarative intents paradigm to build an infrastructure layer that abstracts the complexities of chain interactions. The protocol's vision is to create a system where users can express their desired state outcome without needing to understand the underlying mechanisms of chains, protocols, gas fees, or execution paths.

Epoch Protocol is positioned between users, protocols, and chains to disburden dapps and users from constrictive execution environments and static execution flows. This opens the door for the conception of novel Web3 applications that will be free from these shortcomings.

Epoch's "Sub-Intent orchestrators" first deconstruct users' intent into sub-intents, then coordinate and reconcile the competing solver market and users' state constraints. This makes Epoch Protocol distinctly unique in a way that it can solve for a multifaceted and comprehensive set of intent(s) rather than being limited to a class of predetermined or application-tailored intents.

## **Complexity and Fragmentation in Web3**

The advent of Rollups and multichain-verse has exponentially increased the complexity of achieving desired on-chain states -

- **Users** face significant challenges in navigating numerous dApps, protocols, and chains to make transactions, managing assets dispersed across various chains/rollups, and dealing with different gas token requirements to name a few.
- Constrictive execution environments restrict the creativity of **dApp builders** and internalizing protocols result in static execution paths which don't always provide the most optimal solution for the user.

Moreover, certain user intentions extend beyond simple, instantaneous execution, requiring persistent preferences for recurring actions and time-dependent or arbitrary condition-dependent constraints.

This complexity not only results in a bad user experience but also is a significant barrier to the mass adoption of Web3 and the development of user-centric applications.

## **Solution**

Epoch Protocol is a network of composable and modular **Intent Solvers,** **Sub-Intent Orchestrators(SIO),** and **Epoch Hyperions(Observers)** that compete and collaborate to achieve the most optimal solution for arbitrary user intents.

Epoch facilitates counterparty discovery and efficient solving processes by placing Sub-Intent Orchestrators at the helm of solution discovery, alongside other actors such as Hyperions and Intent Solvers.

### **Intent Input, Sub-Intent Orchestration, Solving, and Settlement**

**Intent Input** - Users or dApps can use the declarative paradigm to provide their intents to the network for resolution.

The intent could have the following attributes -

- Approvals
- Task
- Optimization Factor
- Constraints
- Deadline
- Triggers
- Proposed Fee Rewards
- List of Preferred Solvers

**Sub-Intent Orchestration and Solving**

SIOs approach the intents by -

- Deconstructing intents based on the desired end-state for possible state flows.
- Communicating with **Hyperions** for on-chain and off-chain states and conditions.
- Propagating sub-intent to the internal and external solvers for the most optimal partial state update solution.
- SIOs also solve constraint optimization problems where the possible state flow solutions are then weighted as per the users' optimization factor and intent constraints maximizing the user output.
- Individual solvers are asked to fulfill their partial state update, all of which are then settled atomically regardless of the execution environment.

**Settlement**

To commit and validate state updates in the execution environments and hold user assets, preferences, and continuing permissions, Epoch uses smart contract wallets with Epoch Plugins and Hooks.

Epoch leverages multiple EIP/ERC standards like ERC-4337, EIP-7702, ERC-7579, ERC-7715, and others to manage wallets.

### **Architectural Topology**

### **Epoch Node**

The node is divided into different environments

### **Execution Client**

- Execution client maintains two mempools for intents and transactions.
- It also maintains an alternate mempool for transactions and intents that are supposed to be executed when a better on-chain/off-chain condition is found.
- It propagates intents and transactions across all the nodes through the P2P gossip layer.
- This also executes the final transaction on the settlement layer after receiving the intent solution from SIO.
- All the execution is done through an ERC4337 compliant transaction bundling.

**Context Setter**

- The context setter breaks down the intent into two pieces - the intent and execution condition.
- It analyses the user requirements, context, and triggers.
- It conveys the trigger condition to the Hyperions and other transaction-related context to the Solver environment.

**Epoch Hyperions(Observers)**

- The hyperions on each block, analyzes the chain state then observers if the user’s conditions are met, and ultimately marks the transaction or the intent to be ready to be sent.
- The observer environment has pluggable observers and the Intent can specify a specific class of observer specialised in some niche of Web3.
- There is an inherent storage which can be utilised for consequent calculations or analysis.

**Solver Environment**

- **Sub-Intent Orchestrator (SIO)** and purpose specific **Intent Solvers Modules**
- SIOs can connect to several modules inside this environment and derive the order in which each module should be called.
- A single module finds the best route for a single action ("Stake", "Lend", "Swap" etc).
- Multiple modules are used in the solver environment, through their individual optimised partial state update solutions an aggregated state flow solution is dervied.
- This aggregated solution is then sent to the consensus layer.
1. **Sub-Intent Orchestrator (SIO)**
- SIO anaylzes the intent and looks at the desired end state.
- Through it's own composable logic, SIO can deconstruct the intent into sub-intents.
- For every individual sub-intent, It queries internal and external Intent Solvers and weighs all the possible partial state update solutions.
- SIO connects the initial and end state with the most optimal partial state transition solution.
- Node runner can tweak ISO if they want or use their own business logic for obtaining sub-intents.
1. **Intent Modules**
- Intent Modules contains the business logic and optimsation model for a particular task a node is willing to solve for ("Stake", "Lend", "Swap" etc).
- This logic can be plugging in multiple Intent Solvers, Adapter, using AI-based models, AI-generated Intent Solvers, 3rd party plugins/services, etc.
- Node runners can pick which modules they want to plug in and utilise.

**Consensus**

- All the interested node operators, using SIOs would propose their solution to the consensus.
- All the solutions are simulated, the one that achieves the desired final state in most optimal way is picked, all the necessary calculations, state validity, and decisions are verified, and then it is sent for final settlement.
- A ZK proof for the on-chain verifiability of the calculations, used for reward and liquidity dispersal.

Epoch Node Arch

[https://docs.epochprotocol.xyz/~gitbook/image?url=https%3A%2F%2F2952380122-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FuD7AmV6zHVSdf9W2Sjm4%252Fuploads%252FIqw1gFnU8qszzOy7GMlB%252FScreenshot%25202024-07-22%2520at%25206.14.59%25E2%2580%25AFPM.png%3Falt%3Dmedia%26token%3D35e6a086-36ac-43ad-a58a-c457bffbb01b&width=768&dpr=4&quality=100&sign=d142997f&sv=1](https://docs.epochprotocol.xyz/~gitbook/image?url=https%3A%2F%2F2952380122-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FuD7AmV6zHVSdf9W2Sjm4%252Fuploads%252FIqw1gFnU8qszzOy7GMlB%252FScreenshot%25202024-07-22%2520at%25206.14.59%25E2%2580%25AFPM.png%3Falt%3Dmedia%26token%3D35e6a086-36ac-43ad-a58a-c457bffbb01b&width=768&dpr=4&quality=100&sign=d142997f&sv=1)

### **On-chain Contracts**

Epoch Protocol utilizes various contracts on the execution environments like chains to provide more on-chain verifiability.

**Registry and Gatekeeper**

- This contract acts as a registry and verifies all conditions and proofs that can be verified on-chain.
- Transaction data is added to this with a multi-send call when the transaction is being executed, it allows us to easily verify transaction conditions and maintain on-chain records without sending in multiple transactions for the same intent.
- This contract is a source of truth for hooks and plugins (discussed below).
- This contract also acts as an information store, it provides transactions and intents that are supposed to be executed in the future with more context.

**SAFE | Smart Contract Wallets**

- This is a standard smart contract wallet with support for Plugins and Hooks.
- It maintains custody of the user funds, assets and privileges.
- The user or owner(in the case of multisig) are the only signers, Epoch does not hold any signing keys.
- It facilitates execution and automation of transactions without users giving custody of funds to protocol or intent solvers.
- Once EIP-7702 goes live users can hold funds in their EOA and still be able to leverage Epoch Features.

**Epoch Plugin**

- Epoch Plugin is an extension of Smart Wallet for Intent Settlement and Validity.
- This plugin links the Intent Solution with Epoch Registry and GateKeeper contracts to enable transaction execution.
- It prepares a complete transaction and sends it to the smart wallet for final execution.

**Epoch Hook**

- This contract verifies the execution conditions, Two different checks can be made, pre-transaction and post-transaction.
- The hook contract gets information from the Registry and Gatekeeper contract and then verifies if all the state constraints are being met.
- This provides additional on-chain security and verification.

**Epoch Paymaster**

- Paymaster helps with paying gas fees on different networks.
- Users will not have to worry about having the right gas token on the final settlement layer and can be paid through other chains as well.

**Epoch Liquidity Pools**

- Permissioned pools that maintain working liquidity for the protocol.
- It is used as an alternative to bridging assets to give a near instantaneous experience to user.
- Transaction will be executed on the destination chain first, while user assets on the source chain will be held in escrow. Proof of transaction execution will be communicated through our partners from the destination chain to the source chain and then assets from escrow can be added back to the liquidity pool.
- There is one pool on each chain and liquidity will be balanced constantly by our partner projects.
- Using the pools will incur a minimal fees, which will be distributed to liqudity providers and network participants.

Flow for Epoch Contracts

[https://docs.epochprotocol.xyz/~gitbook/image?url=https%3A%2F%2F2952380122-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FuD7AmV6zHVSdf9W2Sjm4%252Fuploads%252FyYJIjiHzxySLeudQEGyI%252FScreenshot%25202024-04-29%2520at%25204.35.16%25E2%2580%25AFPM.png%3Falt%3Dmedia%26token%3Dca8a01a4-a13e-4219-9a01-834241c923ca&width=768&dpr=4&quality=100&sign=3a5923e8&sv=1](https://docs.epochprotocol.xyz/~gitbook/image?url=https%3A%2F%2F2952380122-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FuD7AmV6zHVSdf9W2Sjm4%252Fuploads%252FyYJIjiHzxySLeudQEGyI%252FScreenshot%25202024-04-29%2520at%25204.35.16%25E2%2580%25AFPM.png%3Falt%3Dmedia%26token%3Dca8a01a4-a13e-4219-9a01-834241c923ca&width=768&dpr=4&quality=100&sign=3a5923e8&sv=1)

### **Epoch SDK**

- Epoch SDK is the primary component that dapp developers interact with to easily construct and send signed intents.
- It helps in cutting down development time from days to hours.
- It also helps in setting the right constraints for users' intents and transactions.
- It adds all the necessary calls to the userOp that will aid in on-chain verification, by Epoch Registry and GateKeeper Contract.
- It also allows developers to prepare userOp and transaction data to automate non-intent-based transactions.

All these moving components work together in stitching a solution that allows users and protocols to provide an unparalleled experience even for some Web2 flows.

It also reduces efforts to build dApps by offloading extra work to Epoch Protocol.

## **Use cases**

**dApps**

1. DApps can be part of Epoch’s Intent solver repository and be part of various proposed solutions.
2. DApps can get the user in the right state for using their dApp, with just one click, something like getting the right tokens or positions, by using Epoch Protocol.
3. Craft various strategies for investing tokens or earning APRs.
4. DApps that need users to bridge assets from another network or swap tokens can simply use epoch to get all the right transactions in place, with the most optimal rates and everything instantly and atomically including bridging.

**Users**

1. Users can lend and stake based on changing on-chain conditions and APRs.
2. Users will not have to care about their fragmented liquidity, they will be able to make transactions involving any tokens available on any chain.
3. Instantaneous bridging of assets
4. Users will be able to tell their requirements in natural language.

## **Conclusion**

Epoch Protocol, leveraging the new declarative intent-centric interaction paradigm, would be a game changer for both dApps and users.  Everchanging multichain web3-verse with fragmented liquidity, complicated multi-steped actions to reach to a specific state, and difficult-to-understand transactions becomes a major cognitive hurdle for users to leverage web3.

Epoch Protocol will not only optimize for the desired user state but also observe for better conditions, explore all chains for options and finally give the most optimal solution. It will help users deal with all the complexities that come with interacting with web3.

With Epoch, dApps would be able to build solutions that were not possible before, UX flows that rivals or even better than web2 UX.

# **Links**

**Website** - [https://epochprotocol.xyz](https://www.epochprotocol.xyz/)

**Twitter** - [https://x.com/0xEpochProtocol](https://x.com/0xEpochProtocol)

**Farcaster -** [https://warpcast.com/0xepochprotocol](https://warpcast.com/0xepochprotocol)

**Mirror** - [https://mirror.xyz/0x62BF6561db8D0105839B70c7bd4210bca3d6aCF2](https://mirror.xyz/0x62BF6561db8D0105839B70c7bd4210bca3d6aCF2)

**Medium** - [https://medium.com/@to.epochprotocol](https://medium.com/@to.epochprotocol)

**Discord** - [https://discord.com/invite/Pd4yZmqYjb](https://discord.com/invite/Pd4yZmqYjb)

### **ERC 4337**ERC 4337 Account Abstraction: The Next Generation of Ethereum Wallets

Account abstraction is a new approach to managing crypto assets that has the potential to revolutionize the way users interact with the Ethereum blockchain, allowing users to use smart contracts as their primary accounts instead of externally owned accounts (EOAs).

## **Externally Owned Accounts ( EOA )**

EOAs are the traditional type of account used on Ethereum. They are controlled by private keys, which must be kept secret in order to prevent unauthorized access to the account's funds. However, EOAs have a number of limitations,including:

- They are vulnerable to theft and loss of private keys.
- They are not very flexible or programmable.
- They can be expensive to use, due to the need to pay gas fees.

## **Smart Contract wallet**

Smart contracts, on the other hand, are much more powerful and flexible. They can be programmed to implement a wide variety of features, such as multi-signature authorization, social recovery, and automatic gas fee payment.

[ERC 4337 (Account Abstraction via Entry Point Contract specification)](https://eips.ethereum.org/EIPS/eip-4337) uses an entry point contract to achieve account abstraction without changing the consensus layer protocol of Ethereum.

Instead of modifying the consensus layer protocol of Ethereum, ERC-4337 introduces a higher-level system called the UserOperation mempool. Users send `UserOperation` objects to this mempool, which package up their intent along with signatures and other data for verification. Miners or bundlers can then package up a set of UserOperation objects into a single "bundle transaction", which is then included in a block.

### **Benefits**Benefits of using Smart contracts over EOA

ERC 4337 account abstraction would allow users to take advantage of the power and flexibility of smart contracts while still maintaining the security and ease of use of EOAs. Here are some of the key benefits of ERC 4337 account abstraction:

- **Improved security:** Smart contracts can be programmed to implement a variety of security features, such as multi-signature authorization and social recovery. This would make it more difficult for hackers to steal users' funds.
- **Enhanced functionality:** Smart contracts can also be programmed to implement additional functionality, such as the ability to automatically pay gas fees or to execute transactions based on certain conditions. This would make it easier for users to interact with the Ethereum compatible network and to use more complex decentralized applications (DApps).
- **More user-friendly experience:** Account Abstraction would allow users to interact with the Ethereum network without having to manage their own private keys or to worry about gas fees. This would make the Ethereum network more accessible to a wider range of users.
- **More control over transactions:** Smart contracts also have more control over transactions, checking for scam and phishing before initiating a transactions, Bundling / Batching on multiple transaction, gas payment in ERC-20 tokens, gas-less transactionf or users and much more.

### **Use-cases**Account abstraction use-cases

ERC 4337 account abstraction would also enable a number of new and innovative features, such as:

- **Automation:** With Account Abstraction you can automate transctions to trigger based on any On-Chain and Off-Chain triggers, like Time Scheduling a transaction or Sending a transaction when ETH price reaches 2000$.
- **Bundling:** Account Abstraction also let you to bundle several transactions together together, to save gas fee while sending a large number of transactions.
- **Pay gas fees with ERC-20 tokens:** Currently, gas fees must be paid in ETH. This can be expensive and inconvenient for users, especially when gas prices are high. ERC 4337 account abstraction would allow users to pay gas fees using any ERC-20 token. This would make gas fees more affordable and more predictable.
- **Social recovery:** Social recovery is a mechanism that allows users to recover their accounts if they lose their private keys. ERC 4337 account abstraction would make it easier to implement social recovery mechanisms for Ethereum wallets.
- **Account recovery:** Account recovery is a mechanism that allows users to recover their accounts if they are lost or stolen. ERC 4337 account abstraction would make it easier to implement account recovery mechanisms for Ethereum wallets.
- **Multi-signature authorization:** Smart contract wallets can be configured so that transactions require the signatures of multiple users. This can help to protect users' funds from theft, even if one user's account is compromised.
- **Account freezing:** Smart contract wallets can be frozen if a device is lost or compromised. This prevents unauthorized users from accessing the wallet's funds.
- **Transaction limits:** Smart contract wallets can be configured to limit the amount of money that can be transferred from the wallet in a given period of time. This can help to protect users from losing all of their funds if their account is hacked.
- **Whitelists:** Smart contract wallets can be configured to only allow transactions to certain addresses. This can help to protect users from sending money to fraudulent addresses.

### **More Readings**More reading and References used in the docs

- [erc4337.io](https://www.erc4337.io/)
- [Account abstraction panel discussion from Devcon Bogota](https://www.youtube.com/watch?app=desktop&v=WsZBymiyT-8)
- ["Why account abstraction is a game changer for dapps" from Devcon Bogota](https://www.youtube.com/watch?v=OwppworJGzs)
- ["Account abstraction ELI5" from Devcon Bogota](https://www.youtube.com/watch?v=QuYZWJj65AY)
- [Vitalik's "Road to Account Abstraction" notes](https://notes.ethereum.org/@vbuterin/account_abstraction_roadmap#Transaction-inclusion-lists)
- [Vitalik's blog post on social recovery wallets](https://vitalik.ca/general/2021/01/11/recovery.html)
- [EIP-2938 notes](https://hackmd.io/@SamWilsn/ryhxoGp4D#What-is-EIP-2938)
- [EIP-2938 documentation](https://eips.ethereum.org/EIPS/eip-2938)
- [EIP-4337 notes](https://medium.com/infinitism/erc-4337-account-abstraction-without-ethereum-protocol-changes-d75c9d94dc4a)
- [EIP-4337 documentation](https://eips.ethereum.org/EIPS/eip-4337)
- [EIP-2771 documentation](https://eips.ethereum.org/EIPS/eip-2771)
- ["Basics of Account Abstraction" -- What is Account Abstraction Part1](https://www.alchemy.com/blog/account-abstraction)

### **How to use Epoch Protocol for Intent Automation**How to use Epoch Protocol to automate any of your web3 intents(batch of transactions), head over to https://app.epochprotocol.xyz

---

We have created a easy to follow video series and written tutorial that you can follow to learn how to use Epoch Protocol to automate any of your web3 actions.

Follow the steps:

1. [Onboarding](https://docs.epochprotocol.xyz/use-epoch-protocol-automation-dapp/onboarding)
2. [Connect to Dapp](https://docs.epochprotocol.xyz/use-epoch-protocol-automation-dapp/connect-to-dapp)
3. [Record a transaction](https://docs.epochprotocol.xyz/use-epoch-protocol-automation-dapp/record-a-transaction)
4. [Bonus Add NFT Action](https://docs.epochprotocol.xyz/use-epoch-protocol-automation-dapp/bonus-add-nft-action)
5. [Execute Transaction right now](https://docs.epochprotocol.xyz/use-epoch-protocol-automation-dapp/execute-transaction-right-now)
6. [Time-Based triggers](https://docs.epochprotocol.xyz/use-epoch-protocol-automation-dapp/time-based-triggers)
7. [Token Received Trigger](https://docs.epochprotocol.xyz/use-epoch-protocol-automation-dapp/token-received-trigger)
8. [Reporting a bug and common fixes](https://docs.epochprotocol.xyz/use-epoch-protocol-automation-dapp/reporting-a-bug-and-common-fixes)

# **Onboarding**

Head over to [https://app.epochprotocol.xyz](https://app.epochprotocol.xyz/) to use Epoch Protocol.

We are currently in Beta, so first check if your wallet is whitelisted or not by simply connecting your metamask wallet to the app.

- If your wallet is not whitelisted head over to our Discord: [https://discord.com/invite/Pd4yZmqYjb](https://discord.com/invite/Pd4yZmqYjb) and let any of the `@Admins` roles know that you want to be a part of our Beta testers.

Follow the below video to onboard to Epoch Protocol or read the steps below

How to Onboard to Epoch Protocol

1. Step 1: Find "Connect Wallet" button on the header, and connect your desired wallet to the Epoch Protocol.
2. Step 2: This is optional for now since we have enabled paymaster in most of the chains, send some Gas tokens to the Account Abstraction enabled Smart wallet to cover transaction fee.
3. Step 3: Just click on "Deploy" to deploy your AA wallet, this is a one time thing for each chain.
4. Step 4: Send any other tokens (like USDT, DAI, etc) that you want to use with Epoch Protocol or any other dapp.

### **Connect to Dapp**How to connect to any Dapp using Wallet Connect

Follow the steps in video or read the steps below.

How to connect to any dapp using wallet connect

1. Step 1: Go to any dapp example [https://app.aave.com](https://app.aave.com/) in a new tab.
2. Step 2: Find "Connect Wallet" button on the dapp
3. Step 3: Select "WalletConnect" option from the list
4. Step 4: Once the WalletConnect pop-up is on the screen, find the "copy URL" icon and copy the URL.
5. Step 5: Go back to Epoch Protocol dapp and Select the "WalletConnect" option from "Sources" and paste the copied URL in the field.
6. Step 6: Click on connect, now the dapp is connected with Epoch Protocol.

# **Record a transaction**

Follow the steps in the video or read the step below.

How to record a transaction using WalletConnect or Transaction Hash

There are 2 ways in which you can add transaction to automate them.

### **1. Record via WalletConnect**

1. Step 1: Connect to dapp using WalletConnect, follow steps in [Connect to Dapp](https://docs.epochprotocol.xyz/use-epoch-protocol-automation-dapp/connect-to-dapp)
2. Step 2: Once dapp is connected go back to the dapp and do any transaction.
3. Step 3: When you do a transaction on dapp you need to come back to Epoch Protocol, and you will see a popup to add transaction into Epoch Protocol

### **2. Record via Transaction Hash**

1. Step 1: Go to the Blockchain Scan like Polygonscan or optimistic.etherscan.io.
2. Step 2: Find the transaction that you want to copy, and copy its transaction hash.
3. Step 3: Once copied, go back to Epoch protocol and select "Transaction Hash" under the "Sources".
4. Step 4: Finally paste the transaction hash you copied into the input field, and click on "Fetch Details".
5. Step 5: Once the details are fetched, you can either keep the data unchanged or edit the calldata if you want to.
6. Step 6: Finally hit the "Submit" button to add the transaction to Actions.

### **Bonus Add NFT Action**Using Add NFT Action to test Epoch Protocol

There is a new way that we have introduced for users to quickly add a action using "Add NFT Action", and test the triggers.

This Action will mint a test NFT to your smart wallet account on Polygon chain.

### **Follow the steps below to use "Add NFT Action"**

1. Step 1: Connect you Metamask or other wallet as mentioned in [Onboarding](https://docs.epochprotocol.xyz/use-epoch-protocol-automation-dapp/onboarding) and switch to Polygon network.
2. Step 2: Once your wallet is connected find the "Add NFT Action" button in the "Sources".
    
    Find the "Add NFT Action"
    
    [https://docs.epochprotocol.xyz/~gitbook/image?url=https%3A%2F%2F2952380122-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FuD7AmV6zHVSdf9W2Sjm4%252Fuploads%252FObDyaqBkL6pBziDdPEH7%252FScreenshot%25202024-03-22%2520at%25203.14.56%25E2%2580%25AFPM.png%3Falt%3Dmedia%26token%3D50dc16c0-4099-4238-a478-db12febd497f&width=768&dpr=4&quality=100&sign=4e317e89&sv=1](https://docs.epochprotocol.xyz/~gitbook/image?url=https%3A%2F%2F2952380122-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FuD7AmV6zHVSdf9W2Sjm4%252Fuploads%252FObDyaqBkL6pBziDdPEH7%252FScreenshot%25202024-03-22%2520at%25203.14.56%25E2%2580%25AFPM.png%3Falt%3Dmedia%26token%3D50dc16c0-4099-4238-a478-db12febd497f&width=768&dpr=4&quality=100&sign=4e317e89&sv=1)
    
3. Step 3: Once the action is added you can go ahead and place any kind of trigger to this Action, by going through [Execute Transaction right now](https://docs.epochprotocol.xyz/use-epoch-protocol-automation-dapp/execute-transaction-right-now), [Time-Based triggers](https://docs.epochprotocol.xyz/use-epoch-protocol-automation-dapp/time-based-triggers) or [Token Received Trigger](https://docs.epochprotocol.xyz/use-epoch-protocol-automation-dapp/token-received-trigger)

### **Execute Transaction right now**How you can execute any actions right now

Executing any transaction right now is very important in cases where you want to create a workflow, transaction like "Approve tokens" are need to be executed right now in order to create a automated workflow.

### **Follow the step in video or read the steps below:**

Execute a transaction right now using epoch protocol

1. Step 1: Follow the steps in [Record a transaction](https://docs.epochprotocol.xyz/use-epoch-protocol-automation-dapp/record-a-transaction) to record a transaction.
2. Step 2: Once you have recorded a transaction, scroll below and click on "Execute Now" button to execute the actions right now.
3. Step 3: You will see a metamask popup, sign the metamask transaction, it won't cost you any gas on chains where we have enabled paymaster.

### **Time-Based triggers**Now let's see how can we add time based triggers to any transaction

Follow the steps in video or read the steps below.

How to set time based triggers

1. Step 1: Follow the steps in [Record a transaction](https://docs.epochprotocol.xyz/use-epoch-protocol-automation-dapp/record-a-transaction) to record a transaction.
2. Step 2: Once the transaction are added to actions list, scroll down to Triggers and select "Time Based" trigger.
3. Step 3: Pick a Date and Time when you want this scheduled transaction to be sent on-chain.
4. Step 4: Once you are all set click "Schedule Now" to schedule the actions.
5. Step 5: Sign the metamask transaction, it won't cost you any gas on chains where we have enabled paymaster, once signed you will see the action in "Scheduled Actions" section.

### **Token Received Trigger**How can you set a token received trigger on action recorded with Epoch Protocol

Setting action using a token received trigger can be important and used at times when you want to send a transaction when you receive a token with optional token amount.

### **Follow the steps in video or Read the steps below**

How to set Token Received trigger on any action

1. Step 1: Follow the steps in [Record a transaction](https://docs.epochprotocol.xyz/use-epoch-protocol-automation-dapp/record-a-transaction) to record a transaction.
2. Step 2: Once the transaction are added to actions list, scroll down to Triggers and select "Token Received" trigger.
3. Step 3: Choose a Token from the drop-down list or paste a Token address in the field below.
4. Step 4: Optionally, you can also include "Minimum Amount Received" amount in the field below, if included action will only go on-chain if you receive a minimum amount of token in your account.
These value is considered to be greater than or equal to, so if you receive any amount equals or greater than this amount action will be executed.
5. Step 5: Once you are all set click "Schedule Now" to schedule the actions.
6. Step 6: Sign the metamask transaction, it won't cost you any gas on chains where we have enabled paymaster, once signed you will see the action in "Scheduled Actions" section.

### **Reporting a bug and common fixes**If you face any issues while trying to use Epoch Protocol, here is how you can report the bug and try some common fixes

There are some common issue that you may face while using Epoch Protocol, here are some common fixes that you can try out.

### **WalletConnect not working or facing some issue?**

In case of any problem related to recording of transaction or connecting with dapp using WalletConnect, try clearing cache and cookies of "Epoch Protocol" app and the dapp which you want to use.

### **Issues with network switching in dapp?**

If you ever face some issue when you try to switch network in Epoch Protocol dapp

1. First disconnect the WalletConnect dapp from Epoch protocol and dapp side.
2. Optionally: You can clear cache and cookies for both Epoch protocol and dApp.
3. Once Epoch Protocol and dApp are both disconnected from each other, switch the network in Epoch protocol which you want to use in the respective dApp.
4. Go back to dApp and again connect it to Epoch protocol using WalletConnect.

### **Approve token is required to create an automated workflow?**

Sometimes, you may want to start a new automated workflow in which the dapp that you want to use asks you to approve the token first before you can do any other transaction.
In cases like this, record the "approve token transaction" from that dapp and use "Execute Now" to approve the token immediately.
Once token is approved you can go ahead and record the next transaction in your workflow.

### **Reporting a bug**

If you face any other bugs, we encourage you to report the bug using our discord.

Head over to `#report-a-bug` channel in our Discord: [https://discord.com/invite/Pd4yZmqYjb](https://discord.com/invite/Pd4yZmqYjb) and let any of the `@Admins` or `@dev` roles know about the bug that you are facing.

# **Getting Started**

We are rapidly building and iterating thus expect a lot of breaking changes and new features.

Epoch Protocol relies on the power of Account Abstraction (AA) to supercharge your Web3 transactions. With AA under the hood, you can do more than simple transactions. Here are key resources to get you started

1. [https://notes.ethereum.org/@vbuterin/account_abstraction_roadmap](https://notes.ethereum.org/@vbuterin/account_abstraction_roadmap)
2. [https://github.com/eth-infinitism/bundler](https://github.com/eth-infinitism/bundler)
3. [https://www.alchemy.com/learn/account-abstraction](https://www.alchemy.com/learn/account-abstraction#:~:text=Account%20Abstraction%20proposes%20people%20use,will%20need%20their%20own%20SCA.&text=Fully%20programmable%20accounts%20with%20built,Externally%20Owned%20Accounts%20(EOAs).)

# **Epoch Bundler**

Epoch Bundler is Compliant with ERC-4337 Spec tests, but it also adds additional functionalities.

You can find all the default bundler RPC endpoints [here](https://github.com/eth-infinitism/bundler/blob/633fb4d8298b432a5b0fa0dc48f2265b80c3a5a5/packages/bundler/src/BundlerServer.ts#L132).

### **Additional Endpoints in Epoch's Bundler Implementation**

**eth_sendUserOperation**

This method works as it does in a normal bundler, but also accepts some additional parameters.

This includes `advancedUserOperation` - This includes [triggers](https://docs.epochprotocol.xyz/use-epoch-sdk/intent-automation-module/triggers) and evaluation statement.

**eth_getUserOperations**

This RPC endpoint returns a list of transactions with bundler that are supposed to be executed in the future.

It simply takes user's smart contract wallet address as a parameter and returns a list of queued Userops.

**Request**

Copy

```
{
     method: "eth_getUserOperations",
     params: [
       "0xb28884540Dc4FA18568Bbc8564386eBd342e3a04"
     ],
}
```

**Response**

Copy

```
{
    "jsonrpc": "2.0",
    "id": 1,
    "result": [
        {
            "chainId": "0x13881",
            "userOp": {
                "sender": "0x037241C85415fcC94D830d972bBec26e079165Aa",
                "nonce": "0xc6168aeedaeb650000000000000000",
                "initCode": "0x",
                "callData": "0xb61d27f60000...0000000000000",
                "callGasLimit": "0x16e4a0",
                "verificationGasLimit": "0x186a0",
                "preVerificationGas": "0xb47c",
                "maxFeePerGas": "0x59682f20",
                "maxPriorityFeePerGas": "0x59682f00",
                "paymasterAndData": "0x",
                "signature": "0xf28148f085d947222...21bd7818ef1e94c7411b",
                "advancedUserOperation": {
                    "triggerEvent": {
                        "contractAddress": "0xBfa045514a...1E087AE82e3",
                        "eventSignature": "event Sync(uint112 reserve0, uint112 reserve1);",
                        "evaluationStatement": ":reserve1: / :reserve0: >= 9"
                    }
                }
            },
            "entryPoint": "0x5FF137D4b0FDCD49DcA30c7CF57E578a026d2789",
            "prefund": "0x0",
            "userOpHash": "0xc61060d21d9719...79de49ab3d3827f5",
            "lastUpdatedTime": "0x18c917978fb"
        }
    ]
}
```

**eth_deleteUserOperation**

This RPC endpoint will delete from the queue the userop with the same nonce as the one received in the body of this request.

# **Epoch SDK**

To send transactions, manage smart contract wallet addresses and signing you can use Epoch SDK

### **Install SDK**

Copy

```
yarn add @epoch-protocol/sdk
# or
npm i @epoch-protocol/sdk
```

### **Setting up Bundler Instance**

Bundler Instance is needed to connect to the bundler and perform bundler specific actions like send userOps, getUserOps, getUserOperationHash etc.

You need to the bundlerUrl, [ENTRY_POINT](https://github.com/eth-infinitism/account-abstraction/tree/develop/deployments) address and the chain id to setup Bundler Instance

Copy

```
import { HttpRpcClient } from '@epoch-protocol/sdk'

const bundlerInstance = new HttpRpcClient(bundlerUrl, ENTRY_POINT, parseInt(network.chainId.toString()));
const network = await provider.getNetwork();
```

### **Setting up Account API**

The Account API is essential to manage user's Smart Contract Wallet.

There are 2 Implementations of the Account API in Epoch's SDK

### **Simple Account API**

Account API Implementation for Eth-Infinitism [SimpleAccount.sol](https://github.com/eth-infinitism/account-abstraction/blob/develop/contracts/samples/SimpleAccount.sol)

You can get the ENTRY_POINT and FACTORY_ADDRESS from the Github [here](https://github.com/eth-infinitism/account-abstraction/tree/develop/deployments)

Copy

```
import { SimpleAccountAPI } from "@epoch-protocol/sdk";

const ENTRY_POINT = "0x5FF137D4b0FDCD49DcA30c7CF57E578a026d2789";
const FACTORY_ADDRESS = "0x4A4fC0bF39D191b5fcA7d4868C9F742B342a39c1";

const walletAPIInstance = new SimpleAccountAPI({
  provider,
  entryPointAddress: ENTRY_POINT,
  owner: signer,
  factoryAddress: FACTORY_ADDRESS,
});
```

### **SAFE Account API**

Account API Implementation for SAFE Wallet and [ERC4337 Module](https://github.com/safe-global/safe-modules/blob/master/4337/contracts/Safe4337Module.sol)

For SAFE Account API we need the SAFE Config like below, you can use the SAFE config from the SDK itself or you can pass you own.

Copy

```
export interface SafeConfig {
    safeProxyFactory: string;
    singleton: string;
    fallbackModule: string;
    aaModule: string;
    addModuleLib: string;
    salt: BigNumber;
}
```

The **safeConfig** and **salt** are essential to **calculate an address for your SAFE Account**. If the salt changes the address will change as well. So make sure you keep a standardised Salt for your application.

Copy

```
import { SafeAccountAPI } from "@epoch-protocol/sdk";
import { safeDefaultConfig } from "@epoch-protocol/sdk/dist/src/SafeDefaultConfig";

const walletAPIInstance = new SafeAccountAPI({
    provider,
    entryPointAddress: ENTRY_POINT,
    owner: signer,
    safeConfig: safeDefaultConfig[network.chainId],
    salt: safeDefaultConfig[network.chainId].salt,
});
```

**Note** -

- ERC4337 Module only works for **[SAFE Version 1.4.1 and above.](https://github.com/safe-global/safe-contracts/releases)** The wallet deployed using our SDK will have that version
- Connecting an **existing ERC4337 Compatible Address is WIP** and we'll soon add support for it. For now if you know the correct safeConfig and salt you can use that address as well.

### **Generating Valid Nonce for UserOP**

### **Nonce For Normal Transactions**

You don't need to do anything for a normal transaction to calculate nonce. The SDK takes care of it or you can manually pass in the nonce if you like.

Copy

```
const userOp = await walletAPI.createSignedUserOp({
        target: someAddress,
        data: "0x",
        value: 100000000n,
        // nonce: BigInt(someNonce),
});
```

### **Nonce For Automated Transactions**

Nonce management through Epoch SDK is slightly different when compared to the usual approach for automated transactions, this is to make sure there are no nonce clashes in case you have many user ops in the queue.

Copy

```
let userOp = {...};

const key = await bundler.getValidNonceKey(userOp);
const nonce = await walletAPI.getNonce(key);

userOp.nonce = nonce;
```

### **Sending Transactions**

Sending transactions is straightforward.

Copy

```
const userOpHash = await bundler.sendUserOpToBundler(userOp);

// In case of non advanced userops
const txid = await walletAPI.getUserOpReceipt(userOpHash);
```

### **Getting Queued UserOps**

To get a list of all the transactions that are with the bundler simply run these

Copy

```
const queuedUserOpsList = await bundler.getUserOperations(userAddress);
```

### **Deleting Queued UserOp**

To delete a specific userOp in the automation queue you need to send a new userOp with the same nonce as the userOp you want to delete.

Copy

```
const deleteOp = await walletAPI.createSignedUserOp({
        target: userSCWalletAddress,
        data: "0x",
        value: 0n,
        nonce: BigInt(userOpToDelete.nonce).toString(),
});

const deleteUserOpHash = await bundler.deleteAdvancedUserOpFromBundler(deleteOp);
```

# **Triggers**

### **Event-Based Trigger**

A trigger event can be passed to advancedUserOperation, in this, a contract address, event signature, and an evaluation statement can be specified.

### **Contract Address**

The address of the contract to listen to the events

**Event Signature**

The ABI of the event which you wanna trigger the event on

**Evaluation Statement**

An evaluation statement can be a small mathematical operation, you can use +, -, *, /, <=, >=, and == to calculate or evaluate something from an event. For example in the below snippet event emits reserve0 and reserve1, for this, we can write an evaluation statement like

Copy

```
const evaluationStatement = `:reserve1: / :reserve0: <= ${somerationumber}`;
```

Copy

```
{
  ...signedUserOp,
  advancedUserOperation: {
    triggerEvent: {
      contractAddress: "0x123",
      eventSignature: "event Sync(uint112 reserve0, uint112 reserve1);",
      evaluationStatement
    }
  }
}
```

Check full example [here](https://docs.epochprotocol.xyz/use-epoch-sdk/intent-automation-module/examples/schedule-eth-transfer-on-event-trigger)

### **Time-Based Trigger**

Transactions can also be sent based on specific time, executionStartWindow and executionEndWindow need to be specified which is compared with the block-time of a chain.

Copy

```
{
    ...signedUserOp,
    executionTimeWindow : {
        executionWindowStart: 12341234,
        executionWindowEnd: 12312123
    }
}
```

Check full example [here](https://docs.epochprotocol.xyz/use-epoch-sdk/intent-automation-module/examples/schedule-token-payment)

### **Every Block Trigger**

Copy

```
Coming Soon...
```

### **Off-Chain Webooks Trigger**

Copy

```
Coming Soon...
```

# **Examples**

- [How to Initialise the Epoch SDK](https://docs.epochprotocol.xyz/use-epoch-sdk/intent-automation-module/examples/how-to-initialise-the-epoch-sdk)
- [How to Get User's SC Wallet Address](https://docs.epochprotocol.xyz/use-epoch-sdk/intent-automation-module/examples/how-to-get-users-sc-wallet-address)
- [Check If User's SC Wallet is Deployed or Not](https://docs.epochprotocol.xyz/use-epoch-sdk/intent-automation-module/examples/check-if-users-sc-wallet-is-deployed-or-not)
- [Deploy User's SC Wallet if not Deployed](https://docs.epochprotocol.xyz/use-epoch-sdk/intent-automation-module/examples/deploy-users-sc-wallet-if-not-deployed)
- [Schedule Token Payment](https://docs.epochprotocol.xyz/use-epoch-sdk/intent-automation-module/examples/schedule-token-payment)
- [Schedule ETH Transfer on Event Trigger](https://docs.epochprotocol.xyz/use-epoch-sdk/intent-automation-module/examples/schedule-eth-transfer-on-event-trigger)

# **How to Initialise the Epoch SDK**

## **Simple Account API**

Copy

```
import { useEffect, useState } from "react";
import { HttpRpcClient, SimpleAccountAPI } from "@epoch-protocol/sdk";
import { useEthersProvider, useEthersSigner } from "~~/utils/scaffold-eth/common";

export const useBundler = () => {
  const ENTRY_POINT = "0x5FF137D4b0FDCD49DcA30c7CF57E578a026d2789";
  const FACTORY_ADDRESS = "0x4A4fC0bF39D191b5fcA7d4868C9F742B342a39c1";
  const bundlerUrl: string = process.env.BUNDLER_URL ?? "http://localhost:14337/80001";

  const [walletAPI, setWalletAPI] = useState<SimpleAccountAPI | null>(null);
  const [bundler, setBundler] = useState<HttpRpcClient | null>(null);

  const provider = useEthersProvider(); // Ethers Provider
  const signer = useEthersSigner(); // Ethers Signer

  useEffect(() => {
    (async () => {
      if (signer && provider) {
        const network = await provider.getNetwork();
x
        const walletAPIInstance = new SimpleAccountAPI({
          provider,
          entryPointAddress: ENTRY_POINT,
          owner: signer,
          factoryAddress: FACTORY_ADDRESS,
        });
        setWalletAPI(walletAPIInstance);

        const bundlerInstance = new HttpRpcClient(bundlerUrl, ENTRY_POINT, parseInt(network.chainId.toString()));
        setBundler(bundlerInstance);
      }
    })();
  }, [signer, provider, bundlerUrl]);

  return { walletAPI, bundler };
};

```

## **SAFE Account API**

Copy

```
import { useEffect, useState } from "react";
import { HttpRpcClient, SafeAccountAPI } from "@epoch-protocol/sdk";
import { safeDefaultConfig } from "@epoch-protocol/sdk/dist/src/SafeDefaultConfig";
import { useEthersProvider, useEthersSigner } from "~~/utils/scaffold-eth/common";

export const useBundler = () => {
  const ENTRY_POINT = "0x5FF137D4b0FDCD49DcA30c7CF57E578a026d2789";
  const bundlerUrl: string = process.env.BUNDLER_URL ?? "http://localhost:14337/80001";

  const [walletAPI, setWalletAPI] = useState<SafeAccountAPI | null>(null);
  const [bundler, setBundler] = useState<HttpRpcClient | null>(null);

  const provider = useEthersProvider();
  const signer = useEthersSigner();

  useEffect(() => {
    (async () => {
      if (signer && provider) {
        const network = await provider.getNetwork();

        const walletAPIInstance = new SafeAccountAPI({
          provider,
          entryPointAddress: ENTRY_POINT,
          owner: signer,
          safeConfig: safeDefaultConfig[network.chainId],
          salt: safeDefaultConfig[network.chainId].salt,
        });
        setWalletAPI(walletAPIInstance);

        const bundlerInstance = new HttpRpcClient(bundlerUrl, ENTRY_POINT, parseInt(network.chainId.toString()));
        setBundler(bundlerInstance);
      }
    })();
  }, [signer, provider, bundlerUrl]);

  return { walletAPI, bundler };
};

```

Note - The Address in the above examples are for Polygon Mumbai

# **How to Get User's SC Wallet Address**

Copy

```
import { useEffect, useState } from "react";
import { useBundler } from "./useBundler";

export const useUserSCWallet = () => {
  const { walletAPI } = useBundler();

  const [userSCWalletAddress, setUserSCWalletAddress] = useState<any>("");

  useEffect(() => {
    (async () => {
      if (walletAPI) {
        setUserSCWalletAddress(await walletAPI.getAccountAddress());
      }
    })();
  }, [walletAPI]);

  return userSCWalletAddress;
};

```

# **Check If User's SC Wallet is Deployed or Not**

Copy

```
import { useEffect, useState } from "react";
import { useBundler } from "./useBundler";

export const useIsWalletDeployed = () => {
  const [isUserWalletNotDeployed, setIsUserWalletNotDeployed] = useState<boolean>(false);

  const { walletAPI } = useBundler();

  useEffect(() => {
    (async () => {
      if (walletAPI) {
        const isNotDeployed = await walletAPI.checkAccountPhantom();
        if (isNotDeployed) {
          setIsUserWalletNotDeployed(true);
        }
      }
    })();
  }, [walletAPI]);

  return isUserWalletNotDeployed;
};

```

# **Deploy User's SC Wallet if not Deployed**

**Note** - You need to send some Native Token for Gas to the SC Wallet Address before you can deploy it.

Copy

```
const { walletAPI, bundler } = useBundler();
const isUserWalletNotDeployed = useIsWalletDeployed();
const account = useAccount();

if(isUserWalletNotDeployed && userSCWalletBalance > 0) {
  const op = await walletAPI.createSignedUserOp({
    target: account.address,
    data: "0x",
    value: 0n,
  });

  const deployWalletUserOp = await bundler.sendUserOpToBundler(op);
}
```

# **Schedule Token Payment**

Initialise the Bundler Instance and Account API Instance.

Make sure you have the tokens you want to schedule in your SC Wallet Address.

Copy

```
import { BigNumber } from "ethers";
import { encodeFunctionData, parseUnits } from "viem";

const abi = [
  // Read-Only Functions
  "function balanceOf(address owner) view returns (uint256)",
  "function decimals() view returns (uint8)",
  "function symbol() view returns (string)",
  // Authenticated Functions
  "function transfer(address to, uint amount) returns (bool)",
  // Events
  "event Transfer(address indexed from, address indexed to, uint amount)",
];

const data = encodeFunctionData({
  abi,
  args: [recipientAddress, parseUnits(transferAmount.toString(), token.decimals)],
  functionName: "transfer",
});

const unsignedUserOp = await walletAPI.createUnsignedUserOp({
  target: token.address,
  data,
  maxFeePerGas: BigNumber.from("90000000000"), // average value for the token transfer
  maxPriorityFeePerGas: BigNumber.from("1500000000"), // average value for the token transfer
  gasLimit: BigNumber.from("2000320"), // average value for the token transfer
  value: 0n,
});

const newUserOp: any = {
  sender: await unsignedUserOp.sender,
  nonce: await unsignedUserOp.nonce,
  initCode: await unsignedUserOp.initCode,
  callData: await unsignedUserOp.callData,
  callGasLimit: await unsignedUserOp.callGasLimit,
  verificationGasLimit: await unsignedUserOp.verificationGasLimit,
  preVerificationGas: await unsignedUserOp.preVerificationGas,
  maxFeePerGas: await unsignedUserOp.maxFeePerGas,
  maxPriorityFeePerGas: await unsignedUserOp.maxPriorityFeePerGas,
  paymasterAndData: await unsignedUserOp.paymasterAndData,
  signature: await unsignedUserOp.signature,
};

const key = await bundler.getValidNonceKey(newUserOp);
const nonce = await walletAPI.getNonce(key);
newUserOp.nonce = nonce;

const signedUserOp = await walletAPI.signUserOp(newUserOp);

const advancedOp = {
  ...signedUserOp,
  advancedUserOperation: {
    executionTimeWindow: {
      executionWindowStart: epochTimeofScheduledTime,
      executionWindowEnd: epochTimeofScheduledTimeWindowEnd,
    },
  },
};

const userOpHash = await bundler.sendUserOpToBundler(advancedOp);
```

# **Schedule ETH Transfer on Event Trigger**

Initialise the Bundler Instance and Account API Instance.

Make sure you have the ETH you want to schedule in your SC Wallet Address.

Transferring ETH if Proposal statusCode is equal to 2 in the example below.

Copy

```
import { BigNumber } from "ethers";
import { encodeFunctionData, parseUnits } from "viem";

const unsignedUserOp = await walletAPI.createUnsignedUserOp({
  target: recipientAddressForETH,
  data: "0x",
  maxFeePerGas: BigNumber.from("90000000000"), // average value for the token transfer
  maxPriorityFeePerGas: BigNumber.from("1500000000"), // average value for the token transfer
  gasLimit: BigNumber.from("2000320"), // average value for the token transfer
  value: 1000000n, // Transfering ETH to recipient
});

const newUserOp: any = {
  sender: await unsignedUserOp.sender,
  nonce: await unsignedUserOp.nonce,
  initCode: await unsignedUserOp.initCode,
  callData: await unsignedUserOp.callData,
  callGasLimit: await unsignedUserOp.callGasLimit,
  verificationGasLimit: await unsignedUserOp.verificationGasLimit,
  preVerificationGas: await unsignedUserOp.preVerificationGas,
  maxFeePerGas: await unsignedUserOp.maxFeePerGas,
  maxPriorityFeePerGas: await unsignedUserOp.maxPriorityFeePerGas,
  paymasterAndData: await unsignedUserOp.paymasterAndData,
  signature: await unsignedUserOp.signature,
};

const key = await bundler.getValidNonceKey(newUserOp);
const nonce = await walletAPI.getNonce(key);
newUserOp.nonce = nonce;

const signedUserOp = await walletAPI.signUserOp(newUserOp);

const advancedOp = {
  ...signedUserOp,
  advancedUserOperation: {
    triggerEvent: {
      contractAddress: propsalContractAddress,
      eventSignature: "event ProposalResult(address indexed recipient, uint statusCode);",
      evaluationStatement: ":statusCode: == 2",
    },
  },
};

const userOpHash = await bundler.sendUserOpToBundler(advancedOp);
```

# **Contracts**

## **Entrypoint**

Copy

```
0x5FF137D4b0FDCD49DcA30c7CF57E578a026d2789
```

## **Epoch SAFE Module**

Copy

```
Coming Soon...
```

## **SAFE Contracts**

### **Polygon**

Copy

```
Epoch Paymaster 0xC6FceF87459420c710a74568B00ED47b883e6127
```

### **Mumbai**

Copy

```
Epoch Paymaster 0x089E74F33764F6134C69389bcc4Dea8D9843ec6e
```

### **Linea**

### **Linea Mainnet**

Copy

```
SAFE 1.4.1

SimulateTxAccessor - 0x3d4BA2E0884aa488718476ca2FB8Efc291A46199
SafeProxyFactory - 0x4e1DCf7AD4e460CfD30791CCC4F9c8a4f820ec67
TokenCallbackHandler - 0xeDCF620325E82e3B9836eaaeFdc4283E99Dd7562
CompatibilityFallbackHandler - 0xfd0732Dc9E303f09fCEf3a7388Ad10A83459Ec99
CreateCall - 0x9b35Af71d77eaf8d7e40252370304687390A1A52
MultiSend - 0x38869bf66a61cF6bDB996A6aE40D5853Fd43B526
MultiSendCallOnly - 0x9641d764fc13c8B624c04430C7356C1C7C8102e2
SignMessageLib - 0xd53cd0aB83D845Ac265BE939c57F53AD838012c9
SafeL2 - 0x29fcB43b46531BcA003ddC8FCB67FFE91900C762
Safe - 0x41675C099F32341bf84BFc5382aF534df5C7461a

SAFE ERC4337 Module

AddModulesLib 0x8EcD4ec46D4D2a6B64fE960B3D64e8B94B2234eb
Safe4337Module 0xa581c4A4DB7175302464fF3C06380BC3270b4037

Epoch Paymaster 0x161c0aad35cbc5b922e3ac55394ed844e4c3fbfd
```

### **Linea Testnet**

Copy

```
SAFE 1.4.1

SimulateTxAccessor 0x3d4BA2E0884aa488718476ca2FB8Efc291A46199
SafeProxyFactory 0x4e1DCf7AD4e460CfD30791CCC4F9c8a4f820ec67
TokenCallbackHandler 0xeDCF620325E82e3B9836eaaeFdc4283E99Dd7562
CompatibilityFallbackHandler 0xfd0732Dc9E303f09fCEf3a7388Ad10A83459Ec99
CreateCall 0x9b35Af71d77eaf8d7e40252370304687390A1A52
MultiSend 0x38869bf66a61cF6bDB996A6aE40D5853Fd43B526
MultiSendCallOnly 0x9641d764fc13c8B624c04430C7356C1C7C8102e2
SignMessageLib 0xd53cd0aB83D845Ac265BE939c57F53AD838012c9
SafeL2 0x29fcB43b46531BcA003ddC8FCB67FFE91900C762
Safe 0x41675C099F32341bf84BFc5382aF534df5C7461a

SAFE ERC4337 Module

AddModulesLib 0x8EcD4ec46D4D2a6B64fE960B3D64e8B94B2234eb
Safe4337Module 0xa581c4A4DB7175302464fF3C06380BC3270b4037
```

### **Optimism**

### **OP Mainnet**

Copy

```
SAFE ERC4337 Module

AddModulesLib 0x8EcD4ec46D4D2a6B64fE960B3D64e8B94B2234eb
Safe4337Module 0xa581c4A4DB7175302464fF3C06380BC3270b4037
Epoch Paymaster 0x07a14059f027ee1bc8b5cbff89136a8d3f7238a7
```

### **OP Sepolia**

Copy

```
SAFE ERC4337 Module

AddModulesLib 0x8EcD4ec46D4D2a6B64fE960B3D64e8B94B2234eb
Safe4337Module 0xa581c4A4DB7175302464fF3C06380BC3270b4037
```

### **BSC**

Copy

```
SAFE ERC4337 Module

AddModulesLib 0x8EcD4ec46D4D2a6B64fE960B3D64e8B94B2234eb
Safe4337Module 0xa581c4A4DB7175302464fF3C06380BC3270b4037
```

### **Arbitrum One**

### **Arbitrum Mainnet**

Copy

```
SAFE ERC4337 Module

AddModulesLib 0x8EcD4ec46D4D2a6B64fE960B3D64e8B94B2234eb
Safe4337Module 0xa581c4A4DB7175302464fF3C06380BC3270b4037
```

### **Arbitrum Sepolia Testnet**

Copy

```
SAFE ERC4337 Module

AddModulesLib 0x8EcD4ec46D4D2a6B64fE960B3D64e8B94B2234eb
Safe4337Module 0xa581c4A4DB7175302464fF3C06380BC3270b4037
```