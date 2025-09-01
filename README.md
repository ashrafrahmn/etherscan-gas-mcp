# etherscan-gas-mcp
A lightweight MCP integration with Etherscan's  Gas Oracle API powering live Ethereum gas fee insights.
# Etherscan Gas MCP

A lightweight Model Context Protocol (MCP) server that fetches live Ethereum gas fees from the [Etherscan Gas Oracle API](https://docs.etherscan.io/api-endpoints/gas-tracker).  
Built for integration with ChainOpera AI agents (e.g., *Gas Fee Guru*).

---

## 🚀 Features
- Fetches Safe, Propose, and Fast gas prices in real-time  
- Built with Node.js + Express + Axios  
- Secure: uses environment variable for your API key (never hard-coded)  
- Deployable via GitHub → ChainOpera MCP integration

---

## 📦 Installation (local testing)

Clone and install dependencies:
`bash
git clone https://github.com/YOUR_USERNAME/etherscan-gas-mcp.git
cd etherscan-gas-mcp
npm install
