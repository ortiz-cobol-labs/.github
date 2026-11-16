# Ortiz COBOL Labs

An organization dedicated to advanced study, practical engineering, and interoperability of high-reliability transactional systems using **COBOL**.

The core mission of **ortiz-cobol-labs** is to bridge the gap between legacy mainframe data processing (stability, strict transactional rules, and batch processing) and modern software architecture (**Go**, **.NET**, **Python**, and **C**).

---

## 🎯 Purpose & Goals

* **Mission-Critical Systems Engineering:** Designing and implementing core domain logic for banking (*Core Banking*) and insurance (*Core Assurance*).
* **Legacy & Modern Interoperability:** Building high-performance integration bridges between COBOL routines and modern microservices via APIs, gRPC, IPC, and standardized file pipelines.
* **Transactional Excellence:** Enforcing audit trails, batch reconciliation, fixed data layouts (*Copybooks*), and structured file processing (Sequential and simulated VSAM files).

---

## 🛠️ Repository Ecosystem

| Repository | Description | Technical Focus |
| :--- | :--- | :--- |
| **[`cobol-pocs`](#)** | Laboratory for syntax, data representation (`PICTURE`, `COMP`), file I/O operations, and procedural logic. | COBOL, GNUCobol, Makefile |
| **[`core-banking`](#)** | Central banking engine simulating accounts, ledger movements, balance calculations, and batch end-of-day processes. | COBOL, Copybooks, Batch |
| **[`core-assurance`](#)** | Insurance engine covering policy issuance, premium calculation, coverage periods, and claims processing. | COBOL, Financial Algorithms |
| **[`cobol-dotnet-interop`](#)** | Interoperability patterns connecting legacy COBOL routines with C# (.NET Core) APIs and services. | COBOL, .NET Core, C# |
| **[`cobol-go-interop`](#)** | High-throughput integration between COBOL batch routines and Go microservices (*Strangler Fig Pattern*). | COBOL, Go, Cgo/IPC |

---

## 🏗️ Standard Repository Architecture

All repositories within this ecosystem follow a uniform layout, decoupled from proprietary mainframe dependencies and optimized for local compilation via **GNUCobol** and **Make**:

```text
.
├── src/          # COBOL source files (.cbl / .cob)
├── copybooks/    # Data definitions and shared record structs (.cpy)
├── batch/        # Automation scripts for batch execution workflows
├── data/         # Sample dataset files (.dat, simulated VSAM datasets)
├── docs/         # Business domain rules and architectural notes
└── Makefile      # Build automation, compilation, and test execution

```

---

## 🚀 Getting Started Locally

### Prerequisites

* Open-source COBOL compiler: **GNUCobol** (`cobc`)
* Build automation utility: **Make**

### Installation (Linux / Debian / Ubuntu)

```bash
sudo apt update
sudo apt install open-cobol build-essential

```

### Build & Run Example

```bash
git clone [https://github.com/ortiz-cobol-labs/core-banking.git](https://github.com/ortiz-cobol-labs/core-banking.git)
cd core-banking
make build
make run

```

---

## 👨‍💻 Maintainer

**Ortiz David**

*Senior Software Engineer & Systems Architect*

[GitHub Profile](https://github.com/ortizdavid) • [Portfolio](https://ortizdavid.github.io)

```

```
