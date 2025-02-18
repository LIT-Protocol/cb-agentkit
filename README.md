# cb-agentkit

**Coinbase Agent Kit Integration with Lit Protocol and Lit Agent Wallet**

This repository contains the integration of Coinbase's agent kit with the Lit Protocol and Lit Agent Wallet. It provides tools and examples for building chatbots that interact with EVM wallets, execute Lit Actions, and perform ERC20 token transfers using the Lit Agent Wallet.

The project includes implementations in both TypeScript and Python, with examples for each language.

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Repository Structure](#repository-structure)
3. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
4. [Usage](#usage)
   - [TypeScript](#typescript)
   - [Python](#python)
5. [Important Files](#important-files)
6. [Contributing](#contributing)
7. [License](#license)

---

## Project Overview

The `cb-agentkit` project demonstrates how to integrate Coinbase's agent kit with the Lit Protocol and Lit Agent Wallet. It includes:

- A chatbot implementation that interacts with EVM wallets.
- Tools for executing Lit Actions (e.g., a "Hello World" example).
- A Lit Agent Wallet implementation for performing ERC20 token transfers.

The project is designed to be modular and extensible, allowing developers to build on top of the provided examples.

---

## Repository Structure

The repository is organized as follows:
cb-agentkit/
├── typescript/
│ ├── examples/
│ │ └── langchain-cdp-chatbot/
│ │ ├── chatbot.ts # Chatbot implementation with EVM wallet integration
│ │ ├── litActionProvider.ts # Basic Lit Action tool (Hello World)
│ │ └── litAgentWalletTransfer.ts # ERC20 transfer using Lit Agent Wallet
│ └── ... # Other TypeScript files and configurations
├── python/
│ ├── examples/
│ │ └── langchain-cdp-chatbot/
│ │ ├── chatbot.py # Chatbot implementation with EVM wallet integration
│ │ ├── litActionProvider.py # Basic Lit Action tool (Hello World)
│ │ └── litAgentWalletProvider.py # ERC20 transfer using Lit Agent Wallet
│ └── ... # Other Python files and configurations
└── README.md # This file

Copy

---

## Getting Started

### Prerequisites

Before running the examples, ensure you have the following installed:

- **Node.js** (for TypeScript) or **Python** (for Python examples)
- **Yarn** or **npm** (for TypeScript)
- **pip** (for Python)
- A basic understanding of EVM wallets, Lit Protocol, and ERC20 tokens.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cb-agentkit.git
   cd cb-agentkit
Install dependencies for the desired language:

TypeScript:

bash
Copy
cd typescript/examples/langchain-cdp-chatbot
yarn install
Python:

bash
Copy
cd python/examples/langchain-cdp-chatbot
pip install -r requirements.txt
Usage
TypeScript
Navigate to the TypeScript examples folder:

bash
Copy
cd typescript/examples/langchain-cdp-chatbot
Run the chatbot:

bash
Copy
yarn start
Explore the chatbot.ts, litActionProvider.ts, and litAgentWalletTransfer.ts files to understand how the EVM wallet, Lit Actions, and ERC20 transfers are implemented.

Python
Navigate to the Python examples folder:

bash
Copy
cd python/examples/langchain-cdp-chatbot
Run the chatbot:

bash
Copy
python chatbot.py
Explore the chatbot.py, litActionProvider.py, and litAgentWalletProvider.py files to understand how the EVM wallet, Lit Actions, and ERC20 transfers are implemented.

Important Files
TypeScript:

chatbot.ts: Implements the chatbot with EVM wallet integration.

litActionProvider.ts: Provides a basic "Hello World" Lit Action tool.

litAgentWalletTransfer.ts: Implements an ERC20 transfer using the Lit Agent Wallet.

Python:

chatbot.py: Implements the chatbot with EVM wallet integration.

litActionProvider.py: Provides a basic "Hello World" Lit Action tool.

litAgentWalletProvider.py: Implements an ERC20 transfer using the Lit Agent Wallet.

Contributing
We welcome contributions! If you'd like to contribute to the project, please follow these steps:

Fork the repository.

Create a new branch for your feature or bugfix.

Commit your changes and push to your fork.

Submit a pull request with a detailed description of your changes.

License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it as needed.

Copy

You can copy this directly into your `README.md` file. Let me know if you need further assistance!
