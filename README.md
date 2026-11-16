### Miraculous Owonubi

I build the things you build things with. I stick my nose into nooks and crannies until I know how they work, then I build my own.

**Building**

- **[theia](https://github.com/theia-hq):** reach a machine by its public key. SSH, files, ports, fetch. This is where I'm putting it all together, starting from the link: if you're across the room, I should be able to reach you without asking a server on another continent.

**Built**

- **[Calimero](https://github.com/calimero-network/core)'s protocol:** sandboxed application logic on users' own nodes, with state synced over a P2P network. It started as my hackathon prototype. I designed both generations and built the networking, storage, sync and **[runtime](https://github.com/calimero-network/core/pull/12)** layers.
- **At NEAR:** the typed, parse-once **[AccountId](https://github.com/near/nearcore/pull/4440)**, the **[Rust JSON-RPC client](https://github.com/near/near-jsonrpc-client-rs)**, the crate compliance checks, and **[contract ABIs](https://github.com/near/near-sdk-rs/pull/893)** with the team.
- **Experiments:** **[quirk](https://github.com/theia-hq/quirk)** (a transport from scratch over UDP, to learn the layer), **[xget](https://github.com/miraclx/xget-rs)**, **[zy](https://github.com/miraclx/zy)**, **[janus](https://github.com/miraclx/janus)**, **[freyr](https://github.com/miraclx/freyr-js)**, and a long tail of smaller ones.

**Curious about**

- Networks composed over heterogeneous transports, as a radical alternative to how we build today. You're just across the room. Why does our message go through us-east-1?
- Shared state without global consensus. You and I are the authority; we just need a link and rules we both run.
- A virtual computer composed from resources rented from anyone, that can move while it runs. Where it lives becomes a detail.

If you're working on any of this, say hi. [miraclx.github.io](https://miraclx.github.io)
