<h1 align="center">Vexgate</h1>

<h3 align="center">Composable Open-Source Payments Infrastructure</h3>

<p align="center">
  <a href="https://github.com/juspay/hyperswitch/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-Apache_2.0-blue" />
  </a>
  <a href="https://github.com/juspay/hyperswitch/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/Made_in-Rust-orange" />
  </a>
</p>

<hr/>

<details>
<summary><strong>📁 Table of Contents</strong></summary>

- [What Can I Do with Vexgate?](#-what-can-i-do-with-vexgate)
- [Why Vexgate?](#-why-vexgate)
- [Architectural Overview](#architectural-overview)
- [Our Vision](#our-vision)
- [Community & Contributions](#community--contributions)
- [Feature Requests & Bugs](#feature-requests--bugs)
- [Versioning](#versioning)
- [License](#copyright-and-license)
- [Team Behind Vexgate](#team-behind-vexgate)

</details>

<summary><h2> What Can I Do with Vexgate?</h2></summary>

Vexgate offers a modular, open-source payments infrastructure designed for flexibility and control. Apart from our Payment Suite offering, this solution allows businesses to pick and integrate only the modules they need on top of their existing payment stack — without unnecessary complexity or vendor lock-in.

Each module is independent and purpose-built to optimize different aspects of payment processing.

<h3> Learn More About The Payment Modules </h3>
<details>

- **Cost Observability**  
  Advanced observability tools to audit, monitor, and optimize your payment costs. Detect hidden fees, downgrades, and penalties with self-serve dashboards and actionable insights.

- **Revenue Recovery**  
  Combat passive churn with intelligent retry strategies tuned by card bin, region, method, and more. Offers fine-grained control over retry algorithms, penalty budgets, and recovery transparency.

- **Vault**  
  A PCI-compliant vault service to store cards, tokens, wallets, and bank credentials. Provides a unified, secure, and reusable store of customer-linked payment methods.

- **Intelligent Routing**  
  Route each transaction to the PSP with the highest predicted auth rate. Reduce retries, avoid downtime, and minimize latency while maximizing first attempt success.

- **Reconciliation**  
  Automate 2-way and 3-way reconciliation with backdated support, staggered scheduling, and customizable outputs. Reduces manual ops effort and increases audit confidence.

- **Alternate Payment Methods**  
  Drop-in widgets for PayPal, Apple Pay, Google Pay, Samsung Pay, Pay by Bank, and BNPL providers like Klarna. Maximizes conversions with seamless one-click checkout.

</details>

<a href="#architectural-overview">
  <h2 id="architectural-overview">Architectural Overview</h2>
</a>
<img src="./docs/imgs/features.png" />
<img src="./docs/imgs/non-functional-features.png" />
<img src="./docs/imgs/hyperswitch-architecture-v1.png" />

## Why Vexgate?

Vexgate is a commercial open-source payments stack purpose-built for scale, flexibility, and developer experience. Designed with a modular architecture, Vexgate lets you pick only the components you need—whether it’s routing, retries, vaulting, or observability—without vendor lock-in or bloated integrations.

Built in Rust for performance and reliability, Vexgate supports global payment methods (cards, wallets, BNPL, UPI, Pay by Bank), exposes smart routing and retry logic, and provides a visual workflow builder in the Control Center. Whether you're integrating a full payment suite or augmenting an existing stack with a single module, Vexgate meets you where you are.

<strong>“Linux for Payments”</strong> — Vexgate is a well-architected reference for teams who want to own their payments stack.

We believe in:

- <strong> Embracing Payment Diversity:</strong> Innovation comes from enabling choice—across payment methods, processors, and flows.

- <strong> Open Source by Default:</strong> Transparency drives trust and builds better, reusable software.

- <strong> Community-Driven Development:</strong> Our roadmap is shaped by real-world use cases and contributors. 

- <strong> Systems-Level Engineering:</strong> We hold ourselves to a high bar for reliability, security, and performance.

- <strong> Maximizing Value Creation:</strong> For developers, customers, and partners alike.

- <strong> Community-Driven, Enterprise-Tested:</strong> Vexgate is built in the open with real-world feedback from developers and contributors.

## Contributing

We welcome contributors from around the world to help build Vexgate. Whether you're fixing bugs, improving documentation, or adding new features, your help is appreciated.

<a href="#feature-requests">
  <h2 id="feature-requests">Feature requests & Bugs</h2>
</a>

For new product features, enhancements, roadmap discussions, or to share queries and ideas, please open a discussion on the project repository.

For reporting a bug, please read the issue guidelines and search for existing and closed issues. If your problem or idea is not addressed yet, please open a new issue.

<a href="#versioning">
  <h2 id="versioning">Versioning</h2>
</a>

Check the [CHANGELOG.md](./CHANGELOG.md) file for details.

<a href="#copyright-and-license">
  <h2 id="copyright-and-license">Copyright and License</h2>
</a>

This product is licensed under the [Apache 2.0 License](LICENSE).

<a href="#team-behind-vexgate">
  <h2 id="team-behind-vexgate">Team behind Vexgate</h2>
</a>

The core team of engineers building Vexgate. Keep up the great work! 🥂
