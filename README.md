<div align="center">

<img src="./assets/banner.svg" alt="Awesome Code Knowledge Graph and Static Analysis Ecosystem" width="100%" />

# 🌐 Awesome Code Knowledge Graph & Static Analysis

### *Curated Hub of Knowledge Graphs, AST/CPG Code Intelligence, Static Code Analysis (SAST) & Semantic Indexing for Modern Software Architecture and AI Agents*

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Code-Knowledge-Graph-Static-Analysis/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Code-Knowledge-Graph-Static-Analysis?style=social" alt="GitHub_Stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Code-Knowledge-Graph-Static-Analysis/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Code-Knowledge-Graph-Static-Analysis?style=social" alt="GitHub forks" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

**Last updated: November 2026** &bull; **Maintained by [@ishandutta2007](https://github.com/ishandutta2007)**

</div>

## 📑 Table of Contents

- [🔍 Overview](#-overview)
- [📈 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [🏢 SaaS & Commercial Hosted Platforms](#-saas--commercial-hosted-platforms)
- [💻 Open-Source Ecosystem & Frameworks](#-open-source-ecosystem--frameworks)
- [🤝 How to Contribute](#-how-to-contribute)
- [⭐ Support & Community](#-support--community)
- [📊 Star History](#-star-history)
- [⚖️ Disclaimer](#️-disclaimer)

---

## 🔍 Overview

This repository is an authoritative directory indexing tools, engines, and frameworks that turn source code into **Code Knowledge Graphs**, **Abstract Syntax Trees (AST)**, **Code Property Graphs (CPG)**, and **Static Application Security Testing (SAST)** pipelines. 

As codebases scale into millions of lines and AI coding assistants become autonomous agents, understanding code dependencies, symbol call hierarchies, data-flow taint analysis, and architectural boundary violations has transitioned from an optional developer luxury into core platform infrastructure.

Whether you are building codebase-aware Retrieval-Augmented Generation (RAG) contexts for LLMs, auditing microservices for zero-day vulnerabilities, or untangling monolithic circular dependencies, this guide categorizes both leading commercial SaaS platforms and premier open-source repositories.

---

## 📈 Sector Overview & Market Dynamics

The global **Static Code Analysis and Software Intelligence** market is estimated at **$1.15 billion to $1.45 billion in 2025–2026**, expanding rapidly at an 8%–14% CAGR, while specialized cloud-native Static Application Security Testing (SAST) and AI-driven code context engines exceed 20%+ annual growth fueled by regulatory compliance (such as the EU Cyber Resilience Act and federal SBOM mandates).

The sector exhibits a **hybrid market structure**:
- **Enterprise Core (Concentrated):** The top tier for enterprise security, continuous compliance, and governance is highly concentrated among mega-cap conglomerates and well-funded leaders (Microsoft/GitHub, Sonar, Synopsys, CAST, Veracode) with substantial multi-year enterprise contracts.
- **Developer Tooling & Knowledge Graphs (Moderately Fragmented):** Conversely, the developer-first code navigation, architectural visualization, and AI coding agent context tier remains moderately fragmented, where agile open-source engines (Tree-sitter, Semgrep, Joern, SCIP, Zoekt, Repomix) innovate rapidly and serve as the composable building blocks for the next generation of code intelligence.

---

## 🏢 SaaS & Commercial Hosted Platforms

The following SaaS and hosted software intelligence platforms provide deep repository indexing, automated PR quality gates, architectural compliance, and cloud-hosted code knowledge graphs.

> *Sorted in descending order by parent company scale (valuation / annual revenue).*

| Platform | Parent Company Scale (Valuation / Revenue) | Starting Price (Paid Tier) | Free Tier / Free Trial Limits | Core Focus & Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[GitHub Code Scanning (CodeQL)](https://github.com)** | **$3.6T+ Market Cap** (Microsoft) / **$2B+ ARR** (GitHub) | **$30 / active committer / month** (GitHub Code Security SKU) | **Free forever for all public repositories**; 30-day trial for GitHub Enterprise Cloud private repos | Enterprise semantic code analysis engine querying codebases like relational data to trace data flow and taint vulnerabilities. |
| **[SonarQube Cloud (SonarCloud)](https://sonarsource.com)** | **$4.7B Valuation** (Series B) / **~$100M+ ARR** (Sonar) | **$34 / month** (Team Plan for 100,000 LOC) | **Free forever for private repos up to 50,000 LOC** (up to 5 users); **Unlimited free analysis for all public/open-source repos** | Continuous automated static analysis, security vulnerabilities, code smell detection, and automated PR quality gates across 30+ languages. |
| **[Sourcegraph](https://sourcegraph.com)** | **$2.6B Valuation** (Series D) / **~$50M ARR** | **~$19 / user / month** (Enterprise starter tier; annual billing) | **14-day full feature trial** (Direct enterprise evaluation); Free individual Cody plans sunsetted in favor of enterprise Cody & universal search | Multi-repo semantic code intelligence, SCIP symbol graph search, cross-repository symbol navigation, and Cody codebase context engine. |
| **[Embold](https://embold.io)** | **$4B Valuation** (Parent BrowserStack) / **~$200M+ ARR** | **Quote-based Enterprise license** (Starting around $299/mo for platform tiers) | **14-day free enterprise trial** (Full engine analysis on internal codebases; cloud free tier deprecated in favor of on-prem enterprise deployments) | AI-assisted static analysis and software analytics evaluating design anti-patterns, maintainability metrics, and security smells. |
| **[CAST Imaging](https://castsoftware.com)** | **~$150M+ Valuation** (€139M Bridgepoint Buyout) / **~$50M ARR** | **Custom enterprise quote** (Tiered by application portfolio volume) | **30-day free trial** (CAST Imaging Express limited to 1 application under 250,000 LOC) | Reverse-engineers complex enterprise software architectures into interactive multi-layer knowledge graphs, data schemas, and transaction call paths. |
| **[GitKraken (GitLens & Workspaces)](https://gitkraken.com)** | **~$15M ARR** (Private Equity backed by Resurgens) | **$4.00 / user / month** (Pro tier; billed annually at $48/yr) | **Free forever for local & public repositories** (Commit Graph, blame annotations, CodeLens); **14-day free trial** of Pro features for private repos | Visual Git repository intelligence, visual interactive commit graph, code ownership maps, and multi-repo workspace tracking. |
| **[CodeScene](https://codescene.com)** | **€11.8M Raised** (Series A Neqst/Luminar) / **~$5M ARR** | **€18 (~$20) / active author / month** (Standard tier, billed annually) | **Free forever for open-source / public repositories**; **30-day fully functional free trial** for private repositories (no credit card required) | Behavioral code analysis combining static code health metrics with version-control history hotspots, developer knowledge distribution, and team coupling. |
| **[Understand by SciTools](https://scitools.com)** | **Bootstrapped / Private** (Leading specialized IDE) | **$100 / user / month** ($1,200/yr per user seat; annual minimum) | **15-day free trial** (Full desktop analysis for evaluation; **Free lifetime academic license** for verified students and qualifying OSS projects) | Comprehensive static analysis IDE delivering control-flow graphs, call trees, dependency matrices, architecture linting, and metric enforcement. |
| **[Structure101 (Sonar Architecture)](https://structure101.com)** | **Acquired by Sonar** ($4.7B valuation ecosystem) | **Integrated into Sonar Enterprise** | **Legacy free trial suspended** (Capabilities integrated directly into Sonar's enterprise architectural governance solution) | Visual software architecture modeling and dependency governance suite detecting cyclic dependencies and enforcing strict layering boundaries. |

---

## 💻 Open-Source Ecosystem & Frameworks

Explore leading open-source repositories powering AST parsing, Code Property Graphs (CPGs), semantic code search, architectural linting, and LLM codebase context packagers.

> *Sorted in descending order by GitHub_Stars_Count.*

| Repository | GitHub_Stars | Primary Language | Description |
| :--- | :--- | :--- | :--- |
| **[colbymchenry/codegraph](https://github.com/colbymchenry/codegraph)** | [![GitHub_Stars](https://img.shields.io/github/stars/colbymchenry/codegraph?style=social&color=white)](https://github.com/colbymchenry/codegraph/stargazers) | TypeScript / Python | Open-source code knowledge graph and codebase indexing tool engineered to map symbols, relationships, and structural dependencies for developer exploration and AI agent context. |
| **[Aider-AI/aider](https://github.com/Aider-AI/aider)** | [![GitHub_Stars](https://img.shields.io/github/stars/Aider-AI/aider?style=social&color=white)](https://github.com/Aider-AI/aider/stargazers) | Python | AI pair programming terminal tool featuring **RepoMap**, an incremental Tree-sitter powered semantic graph generator that compresses relevant repository symbols into LLM context prompts. |
| **[swc-project/swc](https://github.com/swc-project/swc)** | [![GitHub_Stars](https://img.shields.io/github/stars/swc-project/swc?style=social&color=white)](https://github.com/swc-project/swc/stargazers) | Rust | Super-fast 20x–70x Rust-based JavaScript/TypeScript compiler providing lightning-fast AST construction, code analysis, and transformation primitives. |
| **[yamadashy/repomix](https://github.com/yamadashy/repomix)** | [![GitHub_Stars](https://img.shields.io/github/stars/yamadashy/repomix?style=social&color=white)](https://github.com/yamadashy/repomix/stargazers) | TypeScript | Powerful repository context packager that consolidates codebases, directory file trees, and source metadata into structured formats optimized for LLM code understanding. |
| **[tree-sitter/tree-sitter](https://github.com/tree-sitter/tree-sitter)** | [![GitHub_Stars](https://img.shields.io/github/stars/tree-sitter/tree-sitter?style=social&color=white)](https://github.com/tree-sitter/tree-sitter/stargazers) | C / Rust | Foundational incremental parsing library providing concrete syntax trees with zero latency; powers modern IDE syntax highlighting, code search, and symbol graph extraction. |
| **[facebook/flow](https://github.com/facebook/flow)** | [![GitHub_Stars](https://img.shields.io/github/stars/facebook/flow?style=social&color=white)](https://github.com/facebook/flow/stargazers) | OCaml / Rust | Precise static type checker for JavaScript designed to catch common errors, enforce sound type contracts, and optimize large monorepo developer tooling. |
| **[semgrep/semgrep](https://github.com/semgrep/semgrep)** | [![GitHub_Stars](https://img.shields.io/github/stars/semgrep/semgrep?style=social&color=white)](https://github.com/semgrep/semgrep/stargazers) | OCaml / Python | Fast, lightweight static analysis engine for finding bugs, detecting CVEs, and enforcing security policies using intuitive pattern queries that look like actual source code. |
| **[ast-grep/ast-grep](https://github.com/ast-grep/ast-grep)** | [![GitHub_Stars](https://img.shields.io/github/stars/ast-grep/ast-grep?style=social&color=white)](https://github.com/ast-grep/ast-grep/stargazers) | Rust | Lightning-fast CLI tool and library for code structural search, linting, and programmatic code rewriting based on abstract syntax trees across dozens of languages. |
| **[CoatiSoftware/Sourcetrail](https://github.com/CoatiSoftware/Sourcetrail)** | [![GitHub_Stars](https://img.shields.io/github/stars/CoatiSoftware/Sourcetrail?style=social&color=white)](https://github.com/CoatiSoftware/Sourcetrail/stargazers) | C++ | Iconic cross-platform interactive source code explorer that merges interactive dependency graphs, concise code inspection views, and fast symbol lookup for C, C++, Java, and Python. |
| **[facebook/infer](https://github.com/facebook/infer)** | [![GitHub_Stars](https://img.shields.io/github/stars/facebook/infer?style=social&color=white)](https://github.com/facebook/infer/stargazers) | OCaml | Advanced static analyzer developed by Meta that applies separation logic and bi-abduction to prove the absence of null pointer exceptions, resource leaks, and concurrency race conditions. |
| **[microsoft/pyright](https://github.com/microsoft/pyright)** | [![GitHub_Stars](https://img.shields.io/github/stars/microsoft/pyright?style=social&color=white)](https://github.com/microsoft/pyright/stargazers) | TypeScript | Blazing-fast static type checker and type-inference engine for Python, powering Pylance and deep symbol resolution in VS Code. |
| **[SonarSource/sonarqube](https://github.com/SonarSource/sonarqube)** | [![GitHub_Stars](https://img.shields.io/github/stars/SonarSource/sonarqube?style=social&color=white)](https://github.com/SonarSource/sonarqube/stargazers) | Java | Industry-standard self-hosted open-source continuous inspection platform for automated static analysis, security vulnerabilities, technical debt measurement, and coverage tracking. |
| **[github/codeql](https://github.com/github/codeql)** | [![GitHub_Stars](https://img.shields.io/github/stars/github/codeql?style=social&color=white)](https://github.com/github/codeql/stargazers) | QL / C++ | Industry-standard open-source queries and libraries for semantic code analysis that treats source code as relational database records to track data taint flows and zero-days. |
| **[checkstyle/checkstyle](https://github.com/checkstyle/checkstyle)** | [![GitHub_Stars](https://img.shields.io/github/stars/checkstyle/checkstyle?style=social&color=white)](https://github.com/checkstyle/checkstyle/stargazers) | Java | Static code analysis tool checking Java source code against coding standards and architectural conventions, highly configurable via AST traversal. |
| **[sverweij/dependency-cruiser](https://github.com/sverweij/dependency-cruiser)** | [![GitHub_Stars](https://img.shields.io/github/stars/sverweij/dependency-cruiser?style=social&color=white)](https://github.com/sverweij/dependency-cruiser/stargazers) | JavaScript | Validates and visualizes JavaScript, TypeScript, and ESM dependencies; enforces architectural boundary rules and exports graphs into SVG, DOT, and Mermaid formats. |
| **[google/error-prone](https://github.com/google/error-prone)** | [![GitHub_Stars](https://img.shields.io/github/stars/google/error-prone?style=social&color=white)](https://github.com/google/error-prone/stargazers) | Java | Static analysis tool for Java that hooks directly into the javac compiler to catch common programming bugs and design flaws at compile time. |
| **[facebook/pyre-check](https://github.com/facebook/pyre-check)** | [![GitHub_Stars](https://img.shields.io/github/stars/facebook/pyre-check?style=social&color=white)](https://github.com/facebook/pyre-check/stargazers) | OCaml / Python | Performant type checker and static security analysis tool for Python with full taint-tracking capabilities (Pysa) engineered for giant codebases. |
| **[pmd/pmd](https://github.com/pmd/pmd)** | [![GitHub_Stars](https://img.shields.io/github/stars/pmd/pmd?style=social&color=white)](https://github.com/pmd/pmd/stargazers) | Java | Extensible cross-language static code analyzer that scans source code for bugs, duplicate code, suboptimal logic, and cyclomatic complexity. |
| **[oracle/opengrok](https://github.com/oracle/opengrok)** | [![GitHub_Stars](https://img.shields.io/github/stars/oracle/opengrok?style=social&color=white)](https://github.com/oracle/opengrok/stargazers) | Java | Fast and usable source code search and cross-reference engine designed to parse, index, and navigate massive enterprise code repositories. |
| **[MaskRay/ccls](https://github.com/MaskRay/ccls)** | [![GitHub_Stars](https://img.shields.io/github/stars/MaskRay/ccls?style=social&color=white)](https://github.com/MaskRay/ccls/stargazers) | C++ | C/C++/Objective-C language server providing lightning-fast cross-references, call hierarchies, inheritance trees, and symbol indexing backed by Clang. |
| **[TNG/ArchUnit](https://github.com/TNG/ArchUnit)** | [![GitHub_Stars](https://img.shields.io/github/stars/TNG/ArchUnit?style=social&color=white)](https://github.com/TNG/ArchUnit/stargazers) | Java | Extensible Java architecture testing library that validates layer dependencies, cyclic references, package isolation, and class design rules directly as JUnit tests. |
| **[joernio/joern](https://github.com/joernio/joern)** | [![GitHub_Stars](https://img.shields.io/github/stars/joernio/joern/stargazers) | Scala | Open-source code analysis platform built on **Code Property Graphs (CPGs)**—merging AST, Control Flow Graphs (CFG), and Program Dependence Graphs (PDG) into a high-performance graph database. |
| **[clangd/clangd](https://github.com/clangd/clangd)** | [![GitHub_Stars](https://img.shields.io/github/stars/clangd/clangd?style=social&color=white)](https://github.com/clangd/clangd/stargazers) | C++ | High-performance LLVM-based language server providing deep AST inspection, cross-referencing, semantic highlighting, and code graph indexing for C/C++. |
| **[google/kythe](https://github.com/google/kythe)** | [![GitHub_Stars](https://img.shields.io/github/stars/google/kythe?style=social&color=white)](https://github.com/google/kythe/stargazers) | C++ / Go | Pluggable, language-agnostic ecosystem developed by Google for building tools that analyze and index source code into an interoperable semantic graph. |
| **[thebjorn/pydeps](https://github.com/thebjorn/pydeps)** | [![GitHub_Stars](https://img.shields.io/github/stars/thebjorn/pydeps?style=social&color=white)](https://github.com/thebjorn/pydeps/stargazers) | Python | Visualizes Python module dependency graphs, detects internal cycles, and outputs visual graphs to highlight structural architecture. |
| **[sourcegraph/zoekt](https://github.com/sourcegraph/zoekt)** | [![GitHub_Stars](https://img.shields.io/github/stars/sourcegraph/zoekt?style=social&color=white)](https://github.com/sourcegraph/zoekt/stargazers) | Go | Blazing-fast trigram-based regex code search engine (developed by Google & Sourcegraph) optimized for large monorepos and cross-repository search indexes. |
| **[seddonym/import-linter](https://github.com/seddonym/import-linter)** | [![GitHub_Stars](https://img.shields.io/github/stars/seddonym/import-linter?style=social&color=white)](https://github.com/seddonym/import-linter/stargazers) | Python | Custom architecture linter for Python applications that guarantees clean separation of layers and prevents unwanted imports between internal sub-packages. |
| **[sourcegraph/scip](https://github.com/sourcegraph/scip)** | [![GitHub_Stars](https://img.shields.io/github/stars/sourcegraph/scip?style=social&color=white)](https://github.com/sourcegraph/scip/stargazers) | Protobuf / Go | SCIP Code Intelligence Protocol (modern successor to LSIF) establishing cross-language schemas and fast indexers for precise go-to-definition and symbol dependency graphs. |
| **[github/stack-graphs](https://github.com/github/stack-graphs)** | [![GitHub_Stars](https://img.shields.io/github/stars/github/stack-graphs?style=social&color=white)](https://github.com/github/stack-graphs/stargazers) | Rust | GitHub's framework for fast, incremental, zero-build name resolution and symbol definitions using scoped name-binding graphs built on Tree-sitter. |
| **[vitsalis/PyCG](https://github.com/vitsalis/PyCG)** | [![GitHub_Stars](https://img.shields.io/github/stars/vitsalis/PyCG?style=social&color=white)](https://github.com/vitsalis/PyCG/stargazers) | Python | Practical static call graph generator for Python repositories supporting higher-order functions, class inheritance, and dynamic attribute lookups. |

---

## 🛠️ Architecture Recommendation Stack

Looking to assemble an end-to-end code intelligence pipeline? Here is a tested reference architecture:

```mermaid
flowchart TD
    subgraph Ingestion ["1. Parsing & AST Extraction"]
        A["Source Code (Polyglot Monorepo)"] --> B["Tree-sitter / SWC / Clangd"]
    end

    subgraph Graphing ["2. Code Property & Knowledge Graphs"]
        B --> C["SCIP Indexing (Symbol Navigation)"]
        B --> D["Joern (AST + CFG + PDG Graph)"]
        B --> E["colbymchenry/codegraph (Graph DB)"]
    end

    subgraph Analysis ["3. Verification & Security Engine"]
        C --> F["Zoekt (Trigram Code Search)"]
        D --> G["CodeQL / Semgrep (Taint Analysis & SAST)"]
        D --> H["ArchUnit / Dependency-Cruiser (Boundary Linting)"]
    end

    subgraph Consumption ["4. Delivery & AI Agents"]
        F --> I["Developer IDE (Hover, Definitions, Call Hierarchy)"]
        G --> J["CI/CD PR Quality Gates & Compliance"]
        E --> K["AI Coding Agent RAG Context (Aider / Repomix)"]
    end
```

---

## 🤝 How to Contribute

Contributions are warmly encouraged! To propose a new tool or suggest updates:

1. **Fork** this repository.
2. **Add or edit entries** in [README.md](file:///C:/Users/ishan/Documents/Projects/Awesome-Code-Knowledge-Graph-Static-Analysis/README.md) preserving table formatting and descending order conventions.
3. **Include details**: Tool Name, Link, Parent valuation/revenue or Stars_Count, pricing/limits, and a concise 1–2 sentence capability description.
4. **Submit a Pull Request** with a clear explanation of why the tool is valuable for code knowledge graphs or static analysis.

---

## ⭐ Support & Community

If this curated ecosystem helps your software architecture, platform engineering, security audit, or AI context pipeline:

- ⭐ **Star this repository** to help fellow engineers and researchers find it.
- 🍴 **Fork & Share** with your colleagues on [X (Twitter)](https://twitter.com), [LinkedIn](https://linkedin.com), and developer forums.
- 💬 **Join the Discussion** in our [Discord Community](https://discord.gg/jc4xtF58Ve) to discuss code knowledge graphs, SAST patterns, and AI agent architectures.
- ☕ **Support Ongoing Maintenance**: If you'd like to sponsor continued updates and new project evaluations, you can buy me a coffee via the **[GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007)**!

<div align="center">

[![Sponsor @ishandutta2007](https://img.shields.io/badge/Sponsor-%E2%99%A5-ea4aaa?style=for-the-badge&logo=github-sponsors)](https://github.com/sponsors/ishandutta2007)

</div>

---

## 📊 Star History

[![Star History Chart](https://www.star-history.com/svg?repos=ishandutta2007/Awesome-Code-Knowledge-Graph-Static-Analysis&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Awesome-Code-Knowledge-Graph-Static-Analysis&type=date&legend=top-left)

---

## ⚖️ Disclaimer

- This is an independent, community-curated list. Product names, logos, and trademarks belong to their respective owners.
- Public GitHub_Stars_Counts, pricing figures, and corporate metrics are sampled and updated periodically. Check official project documentation for active licensing requirements and enterprise SLA specifications.
- Indexing large-scale monorepos into deep Code Property Graphs (`Joern`, `CodeQL`) requires adequate RAM and disk IOPS during the initial compilation and indexing pass.

<div align="center">
  <sub>Engineered with care for software architects, AppSec teams, platform engineers, and AI coding agent developers.</sub>
</div>
