# Runtime

### What is a runtime and why does it matter to developers (motivation):&#x20;

Applications are fundamentally just code. To take an application from source code into the web apps we know today, a runtime is required to manage application resources, and importantly, application state. Standard web runtimes like Node.js, Deno, and Bun operate with the assumption of a centralized, backend server, and are classified as client-server architecture.&#x20;

For web3 apps, code runs more like a distributed system; whether partially or fully decentralized, you have execution in many configurations with different environments; onchain contracts, offchain actors like solvers, relayers, etc, and importantly, client-side execution with wallets. The client-server model does not work here. Syncing and reasoning about an application across multiple remote environments where latency can be unpredictable, behavior is unrepeatable, and observability into processes is opaque, means developers are restricted in what they build.&#x20;



### How our runtime works:&#x20;

Our runtime serves as an execution environment that enables developers to maintain a unified application state without a centralized authority like a server.&#x20;

We abstract away the line between on-chain and offchain execution, freeing developers from pluming infrastructure, or what I call 'fragmentation tax'.&#x20;

With Concordance, developers no longer write interfaces or message queues, and struggle to sync these segmented environments. They just write core application logic. Our compiler derives the messages to be passed between environments, and our runtime handles the orchestration, equipped with the cryptographic validation, to achieve secure-by-default apps. (Much better than manual audits that start and stop at the smart contract layer.)



### Why take this approach?

All systems communicate by message passing. Rather than a developer writing the message structure and the logic to send, receive, and process messages, Concordance mathematically derives the message from the code. Why does this matter? Why take this approach? Every web3 hack happens by exploiting message passing. If we secure the message construction with math and cryptography, we seal that crack between disjointed systems, making our applications secure by default without a single security audit.

<br>
