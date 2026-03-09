# OpenZiti

**Open-source zero trust networking for applications and infrastructure.**

OpenZiti is a platform for building secure, zero-trust connectivity into any application or network.  Every connection is authenticated with cryptographic identity, authorized by policy, and encrypted end-to-end.  

In traditional networking, services are exposed, and security is layered around them. OpenZiti inverts this: **services are invisible by default, and network paths exist only once an identity is fully authorized**, whether that identity belongs to a user, service, device, or workload.

Created and sponsored by [NetFoundry](https://netfoundry.io). Licensed under [Apache 2.0](https://github.com/openziti/ziti/blob/main/LICENSE).

------

## Use Cases

OpenZiti enables you to extend zero-trust anywhere for any use case, including non-human workloads and workflows, and across multiple networks and third parties. The following are some common use cases:

- **Replace VPNs**: Secure remote access without VPN clients, split tunneling issues, or concentrator bottlenecks
- **Dark APIs & Services**: Expose services only to authorized identities, not to the internet
- **IoT & Non-Human Identity**: Per-device cryptographic identity for machines and non-human workloads
- **Zero Trust Workloads**: Authenticated, encrypted service-to-service communication across clouds and environments
- **Multi-Cloud Connectivity**: Single overlay network spanning AWS, Azure, GCP, on-prem, and edge
- **Self-Hosted Access**: Reach home lab services from anywhere without opening router ports
- **Kubernetes & Cross-Cluster**: Service connectivity without sidecar complexity, works beyond Kubernetes
- **Agentic AI**: Private and secure connectivity to MCP Servers and private LLMs.

## Key Capabilities

| Capability | What It Means |
|---|---|
| **Dark Services** | Services have zero listening ports and are invisible to network scanners and unauthorized users |
| **Identity for Everything** | Cryptographic identity for users, services, IoT devices, and non-human workloads |
| **Identity-Based Operations** | Manage networks through identities and policies instead of IP addresses and firewall rules. Simplifies operations and eliminates manual network configuration |
| **End-to-End Encryption** | Traffic is encrypted from source to destination using libsodium. No trust required in the network path |
| **No VPNs or Open Ports** | Connections route through OpenZiti's overlay.  No VPN clients or concentrators needed |
| **Programmable Overlay** | Works across any network, cloud, on-prem, hybrid, edge, with smart routing |
| **Flexible Deployment** | Embed SDKs in applications, or use tunnelers for existing software. No code changes required to get started |

## Works for New and Existing Applications

OpenZiti supports three deployment models. You can start with zero code changes and adopt stronger zero trust over time:

| Model | How It Works | Code Changes? |
|---|---|---|
| **Network Access** | Route traffic through an OpenZiti edge router in a trusted zone | None |
| **Host Access** | Run a lightweight tunneler on the host alongside your service | None |
| **Application Access** | Embed OpenZiti SDKs directly in client and server applications | Yes (strongest security) |

Mix and match within the same network. Start with tunnelers for existing applications. Add SDK-based zero trust for new development or high-security workloads.

## Repository Map

| Repository | Description |
|---|---|
| **[openziti/ziti](https://github.com/openziti/ziti)** | Core platform: controller, edge routers, CLI |
| **SDKs** | |
| [sdk-golang](https://github.com/openziti/sdk-golang) | Go |
| [ziti-sdk-c](https://github.com/openziti/ziti-sdk-c) | C |
| [ziti-sdk-jvm](https://github.com/openziti/ziti-sdk-jvm) | Java / Kotlin / Android |
| [ziti-sdk-swift](https://github.com/openziti/ziti-sdk-swift) | Swift / iOS |
| [ziti-sdk-nodejs](https://github.com/openziti/ziti-sdk-nodejs) | Node.js |
| [ziti-sdk-csharp](https://github.com/openziti/ziti-sdk-csharp) | C# / .NET |
| [ziti-sdk-py](https://github.com/openziti/ziti-sdk-py) | Python |
| **Tunnelers** | |
| [ziti-tunnel-sdk-c](https://github.com/openziti/ziti-tunnel-sdk-c) | Linux tunneler and core tunneler SDK |
| [ziti-tunnel-apple](https://github.com/openziti/ziti-tunnel-apple) | macOS and iOS edge clients |
| [desktop-edge-win](https://github.com/openziti/desktop-edge-win) | Windows desktop edge client |
| **Docs** | |
| [ziti-doc](https://github.com/openziti/ziti-doc) | Documentation site source |

## Get Started

- [Main Repository](https://github.com/openziti/ziti): Source code, releases, and getting started
- [What is OpenZiti?](https://netfoundry.io/docs/openziti/learn/introduction/): Introduction and core concepts
- [Quickstart Guides](https://netfoundry.io/docs/openziti/learn/quickstarts/): Get a network running locally or in Docker
- [Zero Trust Models](https://netfoundry.io/docs/openziti/learn/core-concepts/zero-trust-models/overview/): Understand the three deployment approaches

## Community

- [Discourse Forum](https://openziti.discourse.group/): Questions, discussions, and help
- [YouTube](https://www.youtube.com/@OpenZiti): Tutorials and demos
- [Blog](https://blog.openziti.io): Project updates and deep dives
- [Twitter/X](https://twitter.com/openziti): News and announcements

## Managed Solution

For zero-trust networking without managing infrastructure, [NetFoundry](https://netfoundry.io/docs/openziti/#deploy_an_overlay) provides a fully managed, globally distributed OpenZiti network as a service.

---

*OpenZiti is developed and open-sourced by [NetFoundry, Inc](https://netfoundry.io).*
