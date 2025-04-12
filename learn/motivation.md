# Motivation

While blockchain aims to be a coordination medium, solving coordination problems on-chain is complex in large part because developers have to reason about their application across multiple axes.&#x20;

Developers must not only manage state across multiple different segments of the application but must reason about how that that state mutates as the application progresses. Component _state_ and its _coordination_ evolve independently and at different rates.&#x20;

Reasoning about a web3 application is like trying to engineer a supply chain all in your head; reasoning across multiple products and their respective constraints and progress across an interdependent system.&#x20;

Because of this complexity, it is far too common that blockchain applications today are brittle, limited in scope, and costly to build.

### Simplify State Management&#x20;

Application state don’t just change at different rates—they change in different ways. On-chain state may update after a transaction, client-side state may change instantly in response to UI input, and backend state may depend on data fetched asynchronously from APIs. **All of this must work together.**&#x20;

State segmentation leads to **low** **visibility, latency, and overhead** to manage across the application.&#x20;

Existing tools treat state as static or siloed. **Great applications require&#x20;**_**dynamic, reactive**_**&#x20;state end-to-end.**

Concordance provides a runtime to unify state across the application,  **ensuring reliable and predictable mutation** across systems while abstracting the underlying complexity.

### Enable Complex Coordination&#x20;

**Once state is predictable, coordination becomes programmable.**

Today's standard of token transfer reduces on-chain value to a one-dimensional unit, typically the token's fiat value.&#x20;

Real-world coordination is multi-dimensional and interconnected, and tokens alone cannot encode this complexity.&#x20;

Even simple coordination problems become hard with this base system.&#x20;

* Today, token mechanism design is done with reserves and minting schedules. What If I wanted a minting schedule based on the rate of change of another system? &#x20;
* Performing change over these tokenized assets via the blockchain is restricted to token transfers. What if I have a partnership and want to specify an asset split with some percent ownership? What if that ownership changes over time?&#x20;

Concordance unlocks new design space for developers to coordinate complex systems without reinventing infrastructure—bringing full visibility, composability, and performance to blockchain-based applications.
