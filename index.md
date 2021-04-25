Kengin is a data-driven, distributed game engine. The main use case is highly connected worlds (like creating a metaverse and large multi-player worlds).

It's primary language is Rust, but other languages can be used in the processing pipeline.

![Rust - Ferris the crab](rustacean-flat-happy.png)

# Why use Kengin?
The focus of Kengin is optimising the data flow across the whole game engine. This allows for high volume real-time simulations.

Kengin is designed with a distributed architecture. This gives many advantages like:
- scaling parts of the system independently - leads to lower server costs
- no overhead for parts of the system you don't use - gives better runtime performance
- distribution of game worlds over cloud, edge servers and clients - letting you create large, responsive worlds

# Why Rust?
Each language has it's own strengths, but we chose Rust because:
- it has very little runtime overhead
- comparable performance to other low level languages (C and C++)
- it's largely memory safe
- it supports many targets (e.g. WASM)
- it has a great package manager (Cargo) which helps with a loosely coupled project
- it's a well designed language with a great community

# When can I use Kengin?
We are hard at work preparing the initial release of Kengin. The current focus is on creating an incrediably efficient underlying data flow which will underpin the rest of the engine.

We anticipate the beta release to go public in Autumn 2021. Please check back often for updates!
