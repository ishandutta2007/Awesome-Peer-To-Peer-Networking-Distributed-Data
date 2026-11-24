# Awesome-Peer-To-Peer-Networking-Distributed-Data

# Top Peer-to-Peer Networking & Distributed Data Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Content-Addressed Storage (IPFS), QUIC P2P Dialing (Iroh/libp2p), Decentralized Storage Networks, Local-First Sync & BitTorrent Protocols*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Peer-to-Peer Networking & Distributed Data**. These tools enable direct NAT-traversing peer connections, cryptographic content addressing, decentralized blob/file storage, serverless local-first synchronization, and censorship-resistant data distribution.

**Examples** include IPFS Cloud (Pinata/Fleek/Filebase), Filecoin, BitTorrent Cloud, Resilio Connect, Syncthing Cloud, ZeroNet, Storj, Crust Network, Sia Skynet, Ethereum Swarm, and `n0-computer/iroh` (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for P2P networking stacks (`iroh`, `libp2p`, `Holepunch`), self-hosted IPFS nodes (`Kubo`), decentralized storage protocols, and peer-to-peer file sync engines — ideal for distributed systems engineers, local-first app builders, decentralized infrastructure developers, and privacy advocates.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Pinata (IPFS Cloud & Dedicated Gateways)](https://pinata.cloud)**  
  Managed IPFS pinning service, high-speed global CDN gateways, and file distribution API for content-addressed media and web3 assets.

- **[Filebase (S3-Compatible IPFS, Storj & Sia Cloud)](https://filebase.com)**  
  Geo-redundant object storage platform uniting IPFS, Storj, and Sia behind a unified Amazon S3-compatible API.

- **[Storj DCS (Decentralized Cloud Storage)](https://storj.io)**  
  Enterprise-grade distributed cloud object storage encrypting and sharding files across thousands of independent global storage nodes.

- **[Filecoin Cloud & Lighthouse / Web3.Storage](https://filecoin.io)**  
  Incentivized decentralized storage network and cryptographic proof-of-storage marketplace built atop IPFS content addressing.

- **[Resilio Active Everywhere (formerly Resilio Connect)](https://resilio.com)**  
  Commercial high-speed peer-to-peer enterprise file synchronization and edge data distribution platform built on the BitTorrent protocol.

- **[Fleek (IPFS & Edge Hosting Platform)](https://fleek.xyz)**  
  Cloud edge hosting and decentralized deployment platform for static sites, web apps, and content-addressed storage.

- **[Crust Network (Decentralized Cloud Storage)](https://crust.network)**  
  Incentivized multi-chain decentralized storage cloud layer built on IPFS with Trusted Execution Environment (TEE) storage proofs.

- **[BitTorrent Speed / BTFS Cloud](https://bittorrent.com)**  
  Commercialized BitTorrent File System (BTFS) and cloud torrent acceleration ecosystem for distributed media delivery.

- **[Ethereum Swarm (Bee Cloud & Gateways)](https://ethswarm.org)**  
  Decentralized peer-to-peer storage and content distribution service tightly integrated with the Ethereum ecosystem.

- **[Sia Network & Rentersd Cloud Services](https://sia.tech)**  
  Blockchain-backed decentralized cloud storage marketplace allowing users to rent unused hard drive capacity globally via smart contracts.


## Open-Source GitHub Projects

- **[n0-computer/iroh](https://github.com)**  
  Modern, ultra-fast open-source P2P networking library written in Rust providing direct QUIC connections, automatic NAT hole-punching, and BLAKE3 verified byte streaming.

- **[libp2p (go-libp2p / rust-libp2p / js-libp2p)](https://github.com)**  
  Modular, extensible open-source peer-to-peer networking stack powering IPFS, Filecoin, Ethereum, and Polkadot with multiplexed transports and DHT routing.

- **[IPFS Kubo (go-ipfs)](https://github.com)**  
  The reference open-source InterPlanetary File System (IPFS) implementation in Go for running content-addressed P2P nodes, Bitswap exchanges, and local HTTP gateways.

- **[Helia (IPFS for JavaScript / TypeScript)](https://github.com)**  
  Lean, modular, browser- and Node.js-native open-source IPFS implementation replacing legacy `js-ipfs` for modern web applications.

- **[Syncthing](https://github.com)**  
  Continuous, open-source peer-to-peer file synchronization program written in Go featuring end-to-end TLS encryption, block-level delta sync, and zero central servers.

- **[Holepunch / Hypercore Protocol (Pear Runtime)](https://github.com)**  
  Open-source peer-to-peer stack featuring append-only cryptographic logs (`Hypercore`), distributed filesystems (`Hyperdrive`), and DHT hole-punching (`Hyperswarm`).

- **[Storj (Open-Source Storage Node & Uplink)](https://github.com)**  
  Open-source distributed object storage software powering Storj storage operators, satellite nodes, and erasure-coded client uplinks.

- **[Lotus (Filecoin Reference Implementation)](https://github.com)**  
  Official open-source Go implementation of the Filecoin distributed storage network protocol and storage provider node.

- **[Sia `renterd` & `hostd`](https://github.com)**  
  Next-generation open-source Sia storage renter and host daemons written in Go with S3-compatible endpoints and autonomous contract management.

- **[Swarm Bee](https://github.com)**  
  Open-source Go client for connecting to and participating in the Ethereum Swarm decentralized storage and messaging network.

- **[ZeroNetX / ZeroNet](https://github.com)**  
  Open-source decentralized peer-to-peer web platform utilizing Bitcoin cryptography and the BitTorrent network to host censorship-resistant websites offline and online.

- **[WebTorrent](https://github.com)**  
  Streaming open-source BitTorrent client for Node.js and web browsers powered by WebRTC data channels for serverless browser-to-browser file transfer.

- **[qBittorrent & libtorrent (Rasterbar)](https://github.com)**  
  Industry-standard open-source C++ BitTorrent protocol library and cross-platform client supporting DHT, PEX, uTP, magnet links, and sequential streaming.

- **[Croc](https://github.com)**  
  Fast, simple open-source CLI tool written in Go enabling end-to-end encrypted, PAKE-authenticated peer-to-peer file and folder transfers across NATs.

- **[Magic Wormhole](https://github.com)**  
  Open-source Python utility and protocol for securely transferring arbitrary files and short text between computers using human-pronounceable one-time codes.

- **[Veilid](https://gitlab.com)**  
  Open-source, mobile-first peer-to-peer application framework written in Rust providing private, onion-routed networking and distributed DHT storage.

- **[Dat / Willow Protocol (`willow-rs`)](https://github.com)**  
  Next-generation open-source peer-to-peer data synchronization protocol designed for fine-grained permissions, destructive edits, and partial replication.

### Additional Strong Open-Source Options

- **[Yjs](https://github.com)** and **[Automerge](https://github.com)** for Conflict-Free Replicated Data Types (CRDTs) enabling real-time local-first collaboration over P2P transports (`y-webrtc`, `iroh`).
- **[IPFS Cluster](https://github.com)** for orchestrating automated pin replication, consensus, and failover across a fleet of self-hosted IPFS Kubo nodes.
- **[Peergos](https://github.com)** for a self-hosted, quantum-resistant end-to-end encrypted P2P cloud storage, social, and workspace platform built on IPFS.
- **[OnionShare](https://github.com)** for securely sharing files, hosting websites, and chatting anonymously directly from your machine over Tor onion services.
- Many community **IPFS-to-S3 gateways (`s3-ipfs`)**, **WebRTC signaling/STUN/TURN servers (`coturn`)**, and **libp2p GossipSub pub/sub routers**.

**Frameworks for building custom systems**: Combine **n0-computer/iroh** or **libp2p**, **IPFS Kubo / Helia**, **Automerge / Yjs** (for CRDT state sync), and **Syncthing** for resilient, serverless, peer-to-peer distributed applications.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Public IPFS, BitTorrent, and DHT networks expose participating IP addresses to connected peers by default unless routed through relays, VPNs, or onion-routed transports (e.g., Tor, Veilid); unencrypted content pinned to public CIDs is globally readable by anyone who knows the hash.
- Always encrypt sensitive files client-side before pinning or replicating data across public peer-to-peer storage networks.

---

**Made for distributed systems engineers, local-first developers, decentralization researchers, and privacy advocates.**  
Let's make networking and data distribution more resilient, peer-to-peer, and open.
