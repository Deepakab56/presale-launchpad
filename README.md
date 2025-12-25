<h1>Presale Launchpad Factory</h1>

<p>
A decentralized launchpad factory smart contract inspired by platforms like <strong>PinkSale</strong>.
This protocol enables token creators to create and manage fair, secure, and feature-rich token presales,
with built-in liquidity auto-locking, vesting, whitelisting, and flexible payment options —
<strong>fully on-chain and non-custodial</strong>.
</p>

<h2>📌 Table of Contents</h2>
<ul>
  <li>Overview</li>
  <li>Features</li>
  <li>Tech Stack</li>
  <li>Smart Contract Architecture</li>
  <li>Workflow</li>
  <li>Usage</li>
  <li>Deployment</li>
  <li>Security Notes</li>
  <li>License</li>
</ul>

<h2>📖 Overview</h2>
<p>
Presale Launchpad Factory allows anyone to deploy and manage token presales without intermediaries.
Each presale is created via a <strong>factory contract</strong>, ensuring standardized logic, security,
and transparency.
</p>

<p>The protocol supports:</p>
<ul>
  <li>ETH and ERC-20 based presales</li>
  <li>Automated liquidity provisioning on DEXs (e.g., Uniswap)</li>
  <li>Fair launch mechanics</li>
  <li>Vesting and locking for tokens and liquidity</li>
</ul>

<p>
Designed to be <strong>multi-chain EVM compatible</strong>, making it deployable on
Ethereum, BNB Smart Chain, Polygon, and more.
</p>

<h2>✨ Features</h2>
<ul>
  <li>✅ Create token presales with ETH or ERC-20 payment tokens</li>
  <li>✅ 100% Token Supply Entered into Presale (no reserved or hidden allocation)</li>
  <li>✅ 100% Liquidity Burn (LP tokens permanently burned, zero unlock risk)</li>
  <li>✅ Auto-listing & liquidity provision on DEXs (e.g., Uniswap)</li>
  <li>✅ Rug-proof liquidity mechanism (no LP withdrawal possible)</li>
  <li>✅ Token vesting for both buyers and project owners</li>
  <li>✅ Token burn and lock mechanisms</li>
  <li>✅ Whitelist sale support</li>
  <li>✅ Configurable soft cap, hard cap, min/max buy limits</li>
  <li>✅ Fair launch detection and validation</li>
  <li>✅ Admin withdrawal and fee settings</li>
  <li>✅ Fully on-chain and non-custodial</li>
  <li>✅ Multi-chain EVM compatible</li>
</ul>

<h2>🧩 Smart Contract Architecture</h2>

<pre>
PresaleFactory
 ├── creates   → PresaleContract
 ├── enforces  → 100% supply presale rule
 └── manages   → platform fees

PresaleContract
 ├── accepts     → 100% token supply
 ├── handles     → user contributions
 ├── adds        → 100% liquidity to DEX
 ├── burns       → LP tokens permanently
 └── distributes → vested / claimable tokens
</pre>
