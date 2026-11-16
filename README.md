### Miraculous Owonubi

Systems engineer. I like the layer underneath: transports, runtimes, storage, protocols. Mostly Rust, since just before 1.0.

**Building**

- **[theia](https://github.com/theia-hq):** reach a machine by its public key. SSH, files, ports, fetch. Access is a capability the host hands out and takes back.
- **[quirk](https://github.com/theia-hq/quirk):** a QUIC-shaped transport written from scratch over UDP, to learn the layer.

**Built**

- **[Calimero](https://github.com/calimero-network/core)'s protocol:** sandboxed application logic on users' own nodes, with state synced over a P2P network. It started as my hackathon prototype. I designed both generations and built the networking, storage, sync and **[runtime](https://github.com/calimero-network/core/pull/12)** layers.
- **At NEAR:** the typed, parse-once **[AccountId](https://github.com/near/nearcore/pull/4440)**, the **[Rust JSON-RPC client](https://github.com/near/near-jsonrpc-client-rs)**, the crate compliance checks, and **[contract ABIs](https://github.com/near/near-sdk-rs/pull/893)** with the team.
- **[freyr](https://github.com/miraclx/freyr-js)**, **[xget](https://github.com/miraclx/xget-rs)**, **[zy](https://github.com/miraclx/zy)**, **[janus](https://github.com/miraclx/janus)**, and a long tail of smaller experiments.

**Curious about**

- Moving a running process to another machine and having it carry on.
- QUIC over links that aren't IP.

[miraclx.github.io](https://miraclx.github.io)
