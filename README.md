# Awesome-Code-Knowledge-Graph-Static-Analysis

## Top Code Knowledge Graph & Static Analysis Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  

*Focused on Code Knowledge Graphs, AST/Call-Graph Indexing, Semantic Code Search, Static Analysis (SAST) & Architecture Dependency Visualization*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Code Knowledge Graph & Static Analysis**. These tools index, parse, query, visualize, and audit large codebases into interactive dependency graphs, symbol call graphs, semantic search indexes, and static analysis rules across multi-repository architectures, CI/CD pipelines, and AI coding agent context engines.



**Examples** include Sourcetrail, Sourcegraph, CodeQL, SonarQube, CAST Imaging, Understand by SciTools, GitKraken CodeBase, Embold, CodeScene, Structure101, and colbymchenry/codegraph (the category leaders and popular runtimes). 



**Open-source emphasis**: This section is heavily expanded with every major active project for code knowledge graphs & call-graph indexing (`colbymchenry/codegraph`, `Sourcetrail`, `CodeQL`, `Joern`, `Tree-sitter`, `LSIF/SCIP`), self-hosted code search (`Zoekt`), and open-source static analysis & architecture linting (`SonarQube Community`, `Semgrep`, `Dependency-Cruiser`, `ArchUnit`) — ideal for software architects, platform engineers, AppSec researchers, and AI agent developers building codebase-aware RAG systems.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Support & Share](#support--share)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Sourcegraph](https://sourcegraph.com)**  

  Enterprise code intelligence and universal code search platform combining cross-repository symbol navigation, SCIP code graphs, and Cody AI codebase context.



- **[SonarQube Cloud (SonarCloud)](https://sonarsource.com)**  

  Cloud-based continuous code quality and static security analysis service detecting bugs, code smells, cognitive complexity, and vulnerabilities across 30+ languages.



- **[CAST Imaging](https://castsoftware.com)**  

  Automated software intelligence platform that reverse-engineers complex enterprise applications into interactive multi-layer architectural blueprints and data-call graphs.



- **[Understand by SciTools](https://scitools.com)**  

  Commercial static analysis and code comprehension IDE providing deep dependency graphs, control-flow charts, metrics, and cross-language symbol inspection.



- **[CodeScene](https://codescene.com)**  

  Behavioral code analysis platform combining static code health metrics with Git history hotspots, team coupling, and technical debt prioritization.



- **[Structure101 (Sonar Architecture)](https://structure101.com)**  

  Software architecture modeling and dependency governance suite for visualizing layered architecture, detecting cyclic dependencies, and enforcing structural rules.



- **[Embold](https://embold.io)**  

  AI-assisted software analytics platform evaluating code quality, design anti-patterns, security vulnerabilities, and maintainability across enterprise repositories.



- **[GitKraken (GitLens & Cloud Workspaces)](https://gitkraken.com)**  

  Visual Git and repository intelligence suite offering commit graphs, code ownership heatmaps, and multi-repo workspace insights.



- **[GitHub Code Scanning (CodeQL Enterprise)](https://github.com)**  

  Managed cloud semantic code analysis service running CodeQL queries across pull requests to uncover zero-day vulnerabilities and taint-tracking flows.





## Open-Source GitHub Projects



- **[colbymchenry/codegraph](https://github.com)**  

  Open-source code knowledge graph and codebase indexing tool engineered to map symbols, relationships, and structural dependencies for developer exploration and AI agent context.



- **[Sourcetrail (`CoatiSoftware/Sourcetrail`)](https://github.com)**  

  Iconic cross-platform open-source interactive source code explorer combining a visual dependency graph, concise code view, and fast symbol search for C, C++, Java, and Python.



- **[GitHub CodeQL (`github/codeql`)](https://github.com)**  

  Industry-standard open-source semantic code analysis engine and query language (`QL`) that treats code as relational data to trace data-flow paths and security vulnerabilities.



- **[Joern (`joernio/joern`)](https://github.com)**  

  Open-source code analysis platform built on Code Property Graphs (CPGs)—merging AST, Control Flow Graph (CFG), and Program Dependence Graph (PDG) into a queryable graph database.



- **[Tree-sitter (`tree-sitter/tree-sitter`)](https://github.com)**  

  Foundational open-source incremental parsing system and concrete syntax tree generator in C/Rust powering modern IDE navigation, structural diffing, and code knowledge graphs.



- **[Zoekt (`sourcegraph/zoekt`)](https://github.com)**  

  Blazing-fast open-source trigram-based code search engine written in Go (developed by Google/Sourcegraph) supporting regex queries, symbol ranking, and large monorepos.



- **[SonarQube Community Build (`SonarSource/sonarqube`)](https://github.com)**  

  Leading self-hosted open-source continuous inspection platform for static code analysis, test coverage tracking, duplication detection, and technical debt management.



- **[Semgrep (`semgrep/semgrep`)](https://github.com)**  

  Fast, open-source AST-aware static analysis tool allowing engineers to write custom code-pattern rules in YAML without wrestling with compiler internals.



- **[SCIP (`sourcegraph/scip`)](https://github.com)**  

  Open-source SCIP Code Intelligence Protocol (successor to LSIF) providing Protobuf schemas and language indexers for precise go-to-definition and find-references graphs.



- **[Dependency-Cruiser (`sverweij/dependency-cruiser`)](https://github.com)**  

  Popular open-source JavaScript/TypeScript dependency validator and visualizer that enforces architectural boundary rules and renders interactive SVG/DOT dependency graphs.



- **[ArchUnit (`TNG/ArchUnit`)](https://github.com)**  

  Open-source Java library for checking software architecture rules—validating package dependencies, layer isolation, cyclic dependencies, and class annotations as unit tests.



### Additional Strong Open-Source Options



- **[RepoMap / Aider Tree-sitter Repo Mapper (`Aider-AI/aider`)](https://github.com)** and **[Repomix (`yamadashy/repomix`)](https://github.com)** for packing repository AST maps and dependency structures into LLM-ready context representations.

- **[Stack Graphs (`github/stack-graphs`)](https://github.com)** for GitHub's open-source Rust framework building incremental, zero-build name-resolution graphs using Tree-sitter.

- **[pydeps (`thebjorn/pydeps`)](https://github.com)** and **[Import Linter (`seddonym/import-linter`)](https://github.com)** for visualizing Python module dependency graphs and enforcing clean hexagonal/layered architectures.

- **[Clangd / CCLS (`MaskRay/ccls`)](https://github.com)** for open-source C/C++/Objective-C Language Server Protocol indexers providing deep call hierarchies and inheritance graphs.

- **[OpenGrok (`oracle/opengrok`)](https://github.com)** for a fast, self-hosted open-source source code search and cross-reference engine supporting large enterprise repositories.



**Frameworks for building custom systems**: Combine **Tree-sitter + SCIP** or **colbymchenry/codegraph** for symbol and call-graph extraction, **Joern** or **CodeQL** for deep data-flow and taint analysis, and **SonarQube Community + Semgrep** for automated CI/CD static analysis.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Support & Share



If you find this curated list helpful, consider supporting the project:



- ⭐ **Star this repository** to help others discover it.

- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.

- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!



[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Note that `Sourcetrail` was archived as open-source in late 2021 (with active community forks maintaining modern compiler support), and GitHub's `CodeQL` CLI/queries are open-source for public repositories and research while requiring GitHub Advanced Security for private enterprise repositories.

- Indexing large monorepos into Code Property Graphs (`Joern`, `CodeQL`) requires substantial RAM and disk I/O during initial database construction.



---



**Made for software architects, platform engineers, AppSec researchers, AI coding agent builders, and open-source contributors.**  

Let's make code knowledge graphs and static analysis more open, navigable, and transparent.
