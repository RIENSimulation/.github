# R.I.E.N - Resilient Infrastructure Emulation Network

[![License](https://img.shields.io/badge/license-AGPL%203.0-blue.svg)](LICENSE)
[![Documentation](https://img.shields.io/badge/docs-latest-brightgreen.svg)](docs/)

## 🎯 Mission

R.I.E.N is a comprehensive distributed testing framework designed to simulate, stress-test, and validate complex distributed systems at scale. Our mission is to help teams build more resilient systems by making chaos engineering and distributed testing accessible and reproducible.

## 🌟 Key Features

- **Distributed Test Orchestration**: Coordinate multiple test agents across your infrastructure
- **Time Control**: Manipulate and synchronize time across distributed components
- **Chaos Engineering**: Built-in entropy injection through our Antropy Proxy
- **Rich Agent Ecosystem**: Simulate various actors including:
  - Human Users
  - Robot Users
  - Web Browsers
  - Infrastructure Components (Databases, APIs, Storage)
  - CRONs
  - Adversarial Actors
- **Comprehensive Observability**: Built-in tracing, metrics, and logging
- **Infrastructure as Code**: Deploy and manage tests using familiar tools

## 🏗️ Architecture

R.I.E.N consists of three main components:

1. **Control Plane**
   - Simulation Orchestrator
   - Configuration Management
   - Event Store
   - Result Store
   - Invariant Checker

2. **Test Agents**
   - Process Management
   - Entropy Proxy
   - Metrics Collection
   - Time Scheduling

3. **Observability Stack**
   - Distributed Tracing
   - Log Aggregation
   - Metrics Store
   - Dashboards

## 📚 Documentation

- [Core Concepts](docs/core-concepts.md)
- [Architecture Guide](docs/architecture.md)
- [Test Agent Development](docs/agent-development.md)
- [API Reference](docs/api-reference.md)
- [Best Practices](docs/best-practices.md)

## 📜 Project Status

R.I.E.N follows a phased development approach:

- 🏗️ Phase 1: Core Infrastructure (In Progress)
- 📅 Phase 2: Core Testing Capabilities (Planned)
- 📅 Phase 3: Data and State Management (Planned)
- 📅 Phase 4: Infrastructure Integration (Planned)
- 📅 Phase 5: Advanced Features (Planned)
- 📅 Phase 6: Observability and Control (Planned)

## 📄 License

R.I.E.N is released under the GNU Affero General Public License v3.0. See the [LICENSE](LICENSE) file for details.

---

<div align="center">
  <i>Building resilient systems through comprehensive distributed testing</i>
</div>
