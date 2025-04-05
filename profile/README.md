# ENS PIN

<div align="center">

> Contribute to the Decentralization of IPFS Network by helping to launch a backend node that automatically pin and backup the files the users add to their ENS name

*This is a hackathon project for ETHGlobal Taipei tackling the bounty track offered by ENS (Etherenum Name Service)*

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTMrwMjPceIWEJWp4DCLES6futffCesqkkSWQ&s" alt="ENS PIN Logo" width="50">
<img src="https://images.credly.com/images/c970e3b3-bd27-475d-851c-b690ac1a5ffa/blob.png" alt="APU Logo" width="50">
<img src="https://ethglobal.b-cdn.net/events/taipei/square-logo/default.png" alt="ETHGlobal Taipei Logo" width="50">

</div>

## What is ENSPin📍 ?
ENSPin is a backend service that automatically pins IPFS files linked to ENS names, ensuring they stay online and accessible. It helps prevent broken links and disappearing content, making ENS a more reliable layer for decentralized identity and storage.

## Product Description
### Problem Statement❓
Many users store important information such as avatars, website links, and metadata on IPFS, referencing it via their ENS names. However, IPFS is not inherently persistent and if no node is actively pinning the file, it may disappear from the network.

This creates a critical vulnerability for decentralized identity and content:
> What’s the point of decentralized naming if the data it points to isn’t reliably accessible?

Most users don’t run their own IPFS nodes or don’t know their content needs to be pinned. This leads to:
- Missing metadata
- Inconsistent user experiences

### Vision🚩
ENSPin empowers the ENS ecosystem with reliable and decentralized content persistence.

## Unique Value Proposition🌟
| Feature | Description |
|--------|-------------|
| 🔗 **ENS-Linked Pinning** | Automatically detects new IPFS links in ENS names and pins them |
| 💡 **Plug-and-Play Infra** | Anyone can deploy the backend node to contribute to the decentralized pinning network |
| 🛡️ **Data Redundancy** | Multiple nodes can independently pin and verify the same files |
| 🚀 **Zero Effort for Users** | Users just use ENS as usual — no extra steps to protect their data |

## Motivation
**ENS PIN** solves this by auto-pinning ENS-linked content, helping ensure data stays available — reinforcing ENS as a reliable identity layer for Web3.

## Repositories📁
- **Backend Service**: [`ens-pin-backend`](https://github.com/ens-pin/ens-index-ipfs-service) – monitors ENS names, pins IPFS content, and maintains pin status.
- **Frontend Dashboard**: [`ens-pin-frontend`](https://github.com/ens-pin/control-dashboard) – visualizes pin status for ENS names.

## Contribution🤝
We welcome contributors who want to help decentralize data storage for ENS!
