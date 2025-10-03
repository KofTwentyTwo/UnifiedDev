# UnifiedDev 🚀

> A unified Maven development environment that brings together enterprise QQQ framework development and personal projects under a single, streamlined build system.

[![License: Proprietary](https://img.shields.io/badge/License-Proprietary-red.svg)](LICENSE)
[![Maven](https://img.shields.io/badge/Maven-Unified%20Build-brightgreen.svg)](https://maven.apache.org/)
[![Java](https://img.shields.io/badge/Java-17-blue.svg)](https://openjdk.org/)

## 📋 Overview

**UnifiedDev** is a personal unified development repository that consolidates multiple software projects into a single top-level Maven parent project. This approach enables efficient dependency management, consistent build tooling, and streamlined development workflows across both professional (QRun.IO) and personal (Kof22) projects.

### 🎯 Purpose

This repository serves as a development workspace that:
- **Unifies Build Systems**: Single Maven build orchestrates multiple sub-projects
- **Centralizes Configuration**: Shared checkstyle, licensing, and build standards
- **Simplifies Development**: Work on multiple related projects without switching contexts
- **Manages Dependencies**: Consistent versioning and dependency resolution across projects

## 🏗️ Repository Structure

```
UnifiedDev/
├── pom.xml                    # Top-level Maven parent project
├── checkstyle/                # Shared code style configuration
│   ├── config.xml
│   └── license.txt
├── QRun-IO/                   # Enterprise QQQ framework projects
│   └── qqq/                   # Low-code application framework
└── Kof22/                     # Personal projects portfolio
    └── Website/               # Personal website and portfolio
```

## 📦 Included Projects

### 🏢 QRun.IO Projects

The **QQQ Framework** - A low-code application framework for engineers that provides backend modules, middleware, and tooling for rapid application development.

**Included modules:**
- **qqq** - Core low-code application framework
- **qbit-bom** - Bill of materials for dependency management
- **qbit-customizable-table-views** - Dynamic table view components
- **qbit-sftp-data-integration** - SFTP-based data integration
- **qbit-standard-process-trace** - Process tracing and monitoring
- **qbit-user-role-permissions** - User authentication and authorization
- **qbit-webhooks** - Webhook integration framework
- **qbit-workflows** - Workflow engine and orchestration
- **qctl** - Command-line tools for QQQ management
- **qqq-frontend-core** - Frontend framework core
- **qqq-frontend-material-dashboard** - Material Design dashboard
- **qqq-frontend-component-sequential-workflow** - Sequential workflow UI components
- **qqq-orb** - CircleCI orb for QQQ projects
- **voyage** - Additional enterprise tooling

**License:** GNU Affero General Public License v3.0  
**Homepage:** [https://github.com/Kingsrook/qqq](https://github.com/Kingsrook/qqq)

### 👨‍💻 Kof22 Personal Projects

A collection of personal projects showcasing various technologies and interests:

#### 🌐 Website
Personal portfolio and website built with modern Java/TypeScript stack.
- **Tech Stack:** Java 17, TypeScript, React, QQQ Framework
- **Features:** Portfolio showcase, blog, project documentation
- **License:** Proprietary

#### 🌸 kfmtbox
A beautiful Rust CLI tool that wraps text in elegant flower box comments.
- **Tech Stack:** Rust, CLI
- **Features:** Multi-language support, smart file detection, editor integration
- **License:** MIT

#### 🚀 Luke's Rocket Launcher
An over-engineered Arduino-based model rocket launch controller designed for safety, reliability, and maximum fun!
- **Tech Stack:** Arduino, C++, PlatformIO, SimulIDE
- **Features:** Multi-stage safety system, LCD interface, state machine architecture, comprehensive testing
- **License:** MIT

#### ☁️ K8S-Cluster-Admin
Kubernetes cluster administration tools and configurations.
- **Tech Stack:** Kubernetes, Helm, Kustomize
- **Features:** Cluster management, deployment automation

#### 🧠 SecondBrain
Personal knowledge management and note-taking system.
- **Tech Stack:** Obsidian, Markdown
- **Features:** Personal knowledge base, digital garden

#### 🚀 Website-CD-Pipeline
Continuous deployment pipeline for website hosting and automation.
- **Tech Stack:** GitHub Actions, Docker, CI/CD
- **Features:** Automated deployments, infrastructure as code

## 🚀 Getting Started

### Prerequisites

- **Java 17+** - Required for Maven and QQQ framework
- **Maven 3.8+** - For building the unified project
- **Node.js 18+** - For frontend components (optional)
- **Git** - For version control and submodule management

### Building the Project

```bash
# Clone the repository
git clone git@github.com:KofTwentyTwo/UnifiedDev.git
cd UnifiedDev

# Build all projects
mvn clean install

# Build specific module
mvn clean install -pl QRun-IO/qqq

# Skip tests for faster builds
mvn clean install -DskipTests
```

### Development Workflow

1. **Start with the unified build** - Ensures all dependencies are resolved
2. **Work in individual project directories** - Navigate to specific projects for focused development
3. **Run from top level** - Execute unified builds and tests from the repository root

## 🛠️ Technology Stack

### Backend
- **Java 17** - Primary backend language
- **Maven** - Build and dependency management
- **QQQ Framework** - Low-code application framework

### Frontend
- **TypeScript** - Type-safe JavaScript
- **React** - UI framework
- **Material Dashboard** - Material Design components

### DevOps
- **Checkstyle** - Code quality and style enforcement
- **Docker** - Containerization
- **GitHub Actions** - CI/CD automation
- **Kubernetes** - Container orchestration

### Additional Languages
- **Rust** - Systems programming (kfmtbox)
- **C++** - Embedded systems (Arduino projects)
- **Shell** - Automation scripting

## 📝 Code Style & Standards

This repository maintains consistent code quality across all projects:

- **Checkstyle Configuration**: Shared rules in `checkstyle/config.xml`
- **License Headers**: Standardized licensing in `checkstyle/license.txt`
- **Formatting**: Consistent code formatting across Java projects
- **Testing**: Comprehensive test coverage requirements

## 🤝 Contributing

This is a personal unified development repository. While the individual projects may accept contributions (check their respective repositories), this unified wrapper is maintained for personal development workflows.

For contributing to individual projects:
- **QQQ Framework**: Visit [Kingsrook/qqq](https://github.com/Kingsrook/qqq)
- **kfmtbox**: Visit [koftwentytwo/kfmtbox](https://github.com/koftwentytwo/kfmtbox)
- **Luke's Rocket Launcher**: Visit [KofTwentyTwo/Lukes-Rocket-Launcher](https://github.com/KofTwentyTwo/Lukes-Rocket-Launcher)

## 📄 License

This unified repository structure is proprietary. Individual projects maintain their own licenses:

- **QQQ Framework**: GNU Affero General Public License v3.0
- **kfmtbox**: MIT License
- **Luke's Rocket Launcher**: MIT License
- **Kof22 Website**: Proprietary
- **Other Projects**: See individual project licenses

## 🔗 Related Resources

### QRun.IO / QQQ Framework
- [QQQ GitHub Repository](https://github.com/Kingsrook/qqq)
- [QQQ Documentation](https://github.com/Kingsrook/qqq/wiki)

### Personal Projects
- [Personal Website](https://kof22.com) *(if applicable)*
- [GitHub Profile](https://github.com/KofTwentyTwo)

## 📧 Contact

- **GitHub**: [@KofTwentyTwo](https://github.com/KofTwentyTwo)
- **Project Issues**: Use individual project repositories for bug reports and feature requests

---

**Built with ❤️ by James Maes** | Unifying development workflows one build at a time 🚀
