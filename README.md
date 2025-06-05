# Quantum Firewall System (QFsense)

**QFSense** is an alternative distribution of **pfSense®**, designed to integrate within a broader ecosystem (Giteria platform, cloud, edge, data center) while offering a modernized interface, extended API capabilities, and native interoperability with other security and network administration tools.

> 🔐 QFSense positions itself as a modern, open-source, and scalable firewall/router solution — built for developers, SMBs, sysadmins, service providers, and embedded infrastructure.

---

## 🚀 Goals

- Provide a **modernized alternative** to pfSense.
- Seamless integration with a **centralized cloud dashboard**: [Admin Cloud Platform](https://admin.qfsense.org).
- Expose a **secure administration API** (REST/GraphQL).
- Support for **modular system plugins and third-party extensions**.
- Native coupling with other components from the [Giteria](https://giteria.com) ecosystem.
- Embedded versions intended for **network appliances and custom hardware**.

---

## ⚙️ Key Features

- 🔥 Powerful firewall based on **pf** (BSD Packet Filter).
- 🌐 Full support for NAT, DNS, DHCP, VLANs, VPNs (IPsec, OpenVPN, WireGuard).
- 🧠 Revamped Web UI using **TypeScript + React** (in progress).
- 🔄 Cloud sync and remote configuration deployment.
- 🔐 2FA, LDAP, SSO authentication support.
- 📡 RESTful API (documentation coming soon).
- 📦 Future support for plugins (DPI, antivirus, network analyzers, etc.).

---

## 🖥️ Web Interface

The user interface is being reengineered using **React + Tailwind CSS**, replacing the legacy pfSense PHP interface.  
It's modular and optimized for performance, accessibility, and mobile-friendliness.

---

## ☁️ Cloud Version

A full-featured cloud offering is in development:

- Centralized control panel via `admin.qfsense.org`
- Remote rule and config deployment
- Unified monitoring across instances
- Native Giteria CI/CD and DevSecOps integration

---

## 📦 Installation

QFSense is built atop **FreeBSD**. A bootable ISO image is currently in development.

```bash
# Manual prototype installation
git clone https://github.com/Sky-Genesis-Enterprise/qfsense-os.git
cd qfsense-os
./install.sh
````

---

## 📜 About pfSense®

This project is based on the source code of [pfSense® CE](https://www.pfsense.org/), a community firewall/router OS originally developed by Netgate.
QFSense is an **independent alternative distribution**, released under the **AGPLv3 license**, and **is not affiliated with or endorsed by Netgate**.

> The original codebase is respectfully acknowledged. QFSense aims to expand upon pfSense’s capabilities while forging its own technical direction.

---

## 🤝 Contributing

We welcome all contributions!

* UI/UX improvements
* Feature suggestions
* Plugin modules
* Hardware compatibility
* Documentation and translations

See [`CONTRIBUTING.md`](./github/CONTRIBUTING.md) for details.

---

## 🔗 Useful Links

* Official site: [qfsense.org](https://qfsense.org)
* Cloud Admin UI: [Admin Cloud Platform](https://admin.qfsense.org)
* Documentation: (coming soon)
* Support: [support@qfsense.org](mailto:support@qfsense.org)

---

## 📖 License

QFSense is licensed under the **GNU Affero General Public License v3.0 (AGPLv3)**.
Any public deployment of the software must provide access to the corresponding source code.