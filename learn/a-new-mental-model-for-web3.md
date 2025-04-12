---
noRobotsIndex: true
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: false
---

# A New Mental Model for Web3

All blockchain technologies can be grouped into two segments.&#x20;

<figure><img src="../.gitbook/assets/image (1) (1).png" alt="" width="375"><figcaption></figcaption></figure>

### Segment 1: Blockchains are State Machines&#x20;

Blockchains are deterministic finite state automata, which know only their current state, an acceptable set of states, and the state transition function. A blockchain's entire state is contained as its ledger.

### Segment 2: Everything else is a Data Abstraction&#x20;

To expand blockchain capabilities (and enable DeFi, DeSci, GameFi), we employ intermediaries like bridges, oracles, and indexers. These trusted intermediaries manage nondeterministic data processes that a deterministic state machine cannot.&#x20;

<figure><img src="../.gitbook/assets/image (3).png" alt="" width="375"><figcaption></figcaption></figure>

For any action in web3 beyond state transition, users and builders must choose from the intermediaries available, accept the outlined constraints of their specialized process, adopt their tenants, and pay their toll.&#x20;

<figure><img src="../.gitbook/assets/image (2).png" alt="" width="375"><figcaption></figcaption></figure>

i.e. Bridges bring transaction data cross-chain. You must accept their version of synthetic, wrapped, or minted tokens, trust their security, and pay their fee.&#x20;

### Concordance Solves for Data Abstraction&#x20;

We propose Convoy; a new protocol for arbitrary data abstraction. &#x20;

This protocol removes intermediaries who facilitate processes of data abstraction, and allow for both objective and subjective data-dependent applications to run fully on-chain.&#x20;

## How

We abstract data through an interface, for any arbitrary data processes. Users and builders can define their own on-chain processes.&#x20;

Our protocol optimizes data compression, and secure package transfer, and enables responsive I/O from the client.&#x20;

## Why

#### Blockchain shouldn't be an afterthought in application design.&#x20;

We build with blockchain integration in mind.&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2024-10-16 at 4.12.51 PM.png" alt=""><figcaption></figcaption></figure>



**Developers need tools, not constraints, to develop the best blockchain-based technology possible.**&#x20;

Developers should focus on enabling the solutions they want using blockchain instead of fighting with infrastructure, compromising on the features they can create, or making appchains, sidechains, or rollups that fragment liquidity and compromise strong security.

**Blockchain should be trustless.**&#x20;

The core of web3 is permissionless, trustless compute.&#x20;

Developers should not have to rely on intermediaries to facilitate transactions. &#x20;

**Give users transparency and control over their data.**&#x20;

Users should know what happens to their data when they provide it as required on the internet.
