# AuditForge MCP Server 🛡️⚡💎

Universal Smart Contract Security Auditor, Honeypot Analyzer & Gas Optimization Engine MCP Server for **Cursor, Claude Code, and Windsurf**.

## 🌟 Core Capabilities:
- 🛡️ **Static Smart Contract Audit:** Pinpoint Reentrancy (SWC-107), tx.origin auth bypasses (SWC-115), Unchecked Transfers, and Access Control vulnerabilities with auto-remediation.
- 🍯 **Honeypot & Tax Trap Detection:** Analyze token mechanics for predatory 99% sell taxes, blacklist transfers, hidden mints, and pause switches.
- ⚡ **Gas Optimization Engine:** Identify storage slot packing opportunities, calldata optimizations, custom errors vs string requires, and immutables.
- 🪙 **Production ERC20 / SPL Token Generator:** OpenZeppelin v5 compliant contracts with Permit (EIP-2612) and Foundry unit test suites.

## 🚀 Server URL
`https://auditforge-api.agentweb-hub.workers.dev/mcp`


## 🔴 NEW in v1.1 — Live Tool: `scan_solidity_vulnerabilities`

Statically scans pasted Solidity source with REAL pattern analysis: tx.origin, delegatecall, reentrancy surface, unchecked calls and access-control gaps - with line-level findings from YOUR code.

No API key needed — works out of the box.

## 💰 Pricing

**Start free — 10 requests/day, no signup, no card.** Upgrade only if it earns a place in your workflow.

| Plan | Price | Pay with |
|------|-------|----------|
| **Free** | $0 | 10 requests/day — no signup needed |
| **Pro** (this server only) | **$7.99** lifetime | 💳 Gumroad **or** 🪙 Solana USDC |
| **All-Access Suite** (all 44+ servers) | **$14.99** lifetime | 💳 Gumroad **or** 🪙 Solana USDC |

### 💳 Option 1 — Gumroad (PayPal & Credit Cards)

👉 **[amygraphics.gumroad.com/l/mcp-pro](https://amygraphics.gumroad.com/l/mcp-pro)** — select *Single MCP Server* ($7.99) or *All-Access Lifetime Suite* ($14.99). Instant license key delivery.

### 🪙 Option 2 — Solana USDC (instant, no account needed)

Send **$7.99 USDC** (single) or **$14.99 USDC** (all-access) to:

```
8sDLX3okSV974wdjdeKhN9uWLZDr45DeGCJ28zgTLEdJ
```

Then POST your transaction signature to the `/verify-solana` endpoint to activate your lifetime license instantly.
