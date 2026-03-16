## OpenZiti

**Open-source zero trust networking for applications and infrastructure.**

OpenZiti is a platform for building secure, zero-trust connectivity into any application or network.  Every connection is authenticated with cryptographic identity, authorized by policy, and encrypted end-to-end.

In traditional networking, services are exposed, and security is layered around them. OpenZiti inverts this: **services are invisible by default, and network paths exist only once an identity is fully authorized**, whether that identity belongs to a user, service, device, or workload.

OpenZiti is fully open-source under the [Apache 2.0](https://github.com/openziti/ziti/blob/main/LICENSE) license. All core networking functionality is in the open-source project. [NetFoundry](https://netfoundry.io), which created and sponsors OpenZiti, offers a [managed service](https://netfoundry.io/docs/openziti/#deploy_an_overlay) built on the same platform.

---

### Repository Map

| Repository | Description |
|---|---|
| **[openziti/ziti](https://github.com/openziti/ziti)** | Core platform: controller, edge routers, CLI |

#### SDKs

| Repository | Language |
|---|---|
| [sdk-golang](https://github.com/openziti/sdk-golang) | Go |
| [ziti-sdk-c](https://github.com/openziti/ziti-sdk-c) | C |
| [ziti-sdk-jvm](https://github.com/openziti/ziti-sdk-jvm) | Java / Kotlin / Android |
| [ziti-sdk-swift](https://github.com/openziti/ziti-sdk-swift) | Swift / iOS |
| [ziti-sdk-nodejs](https://github.com/openziti/ziti-sdk-nodejs) | Node.js |
| [ziti-sdk-csharp](https://github.com/openziti/ziti-sdk-csharp) | C# / .NET |
| [ziti-sdk-py](https://github.com/openziti/ziti-sdk-py) | Python |

#### Tunnelers

| Repository | Description |
|---|---|
| [ziti-tunnel-sdk-c](https://github.com/openziti/ziti-tunnel-sdk-c) | Linux tunneler and core tunneler SDK |
| [ziti-tunnel-apple](https://github.com/openziti/ziti-tunnel-apple) | macOS and iOS edge clients |
| [desktop-edge-win](https://github.com/openziti/desktop-edge-win) | Windows desktop edge client |

#### Docs & Security

| Repository | Description |
|---|---|
| [ziti-doc](https://github.com/openziti/ziti-doc) | Documentation site source |
| [security](https://github.com/openziti/security) | Vulnerability disclosure policy and incident response process |

---

### Community

- [Discourse Forum](https://openziti.discourse.group/) — Questions, discussions, and help
- [YouTube](https://www.youtube.com/@OpenZiti) — Tutorials and demos
- [Blog](https://blog.openziti.io) — Project updates and deep dives
- [Twitter/X](https://twitter.com/openziti) — News and announcements

---

*OpenZiti is developed and open-sourced by [NetFoundry, Inc](https://netfoundry.io).*

