# Obscura Agent Skills

Agent skills for Solana development with Obscura DEX and ecosystem tools.

## Available Skills

### 🔹 percolator

Percolator perpetual futures protocol development. Educational research project for predictable risk management using profit-as-junior-claims model.

**Covers**:
- Core risk engine (Rust with formal verification)
- Solana programs and architecture
- CLI tools and scripting
- Matcher development (passive/vAMM)
- Oracle integration (Pyth, Chainlink)
- Testing and stress testing
- Formal verification with Kani

**Install**: 
```bash
npx skills add agentic-reserve/AGENT_SKILL/percolator
```

### 🔹 solana-mobile

Solana Mobile development with Mobile Wallet Adapter (MWA), Seeker device integration, and SeedVault secure storage.

**Covers**:
- Mobile Wallet Adapter (MWA) protocol
- Seeker device detection and verification
- SeedVault secure key storage
- React Native integration patterns
- Sign-In With Solana (SIWS)
- Transaction and message signing
- dApp Store publishing

**Install**:
```bash
npx skills add agentic-reserve/AGENT_SKILL/solana-mobile
```

## Quick Start

Install both skills:

```bash
# Percolator protocol development
npx skills add agentic-reserve/AGENT_SKILL/percolator

# Solana Mobile development
npx skills add agentic-reserve/AGENT_SKILL/solana-mobile
```

## Usage

Once installed, these skills are automatically discovered by AI agents when working on relevant tasks:

- **Percolator**: Activated when working on perpetual futures, risk engines, or Solana programs
- **Solana Mobile**: Activated when working on mobile dApps, wallet integration, or React Native

## Supported Agents

These skills work with 40+ AI coding agents including:

- Kiro
- Claude Code
- GitHub Copilot
- Cursor
- Windsurf
- Cline
- Roo
- And many more

## Skills Format

Each skill follows the [Agent Skills](https://github.com/agentskills/agentskills) open standard with:

- `SKILL.md` - Main skill file with YAML frontmatter
- Supporting documentation files
- Code examples and templates
- Best practices and patterns

## Contributing

Contributions welcome! To add or improve skills:

1. Fork this repository
2. Create a new skill folder or update existing
3. Follow the SKILL.md format with proper frontmatter
4. Submit a pull request

## License

Apache 2.0

## Resources

- **Obscura DEX**: https://github.com/your-org/obscura
- **Skills.sh**: https://skills.sh
- **Agent Skills Spec**: https://github.com/agentskills/agentskills
- **Solana Mobile**: https://docs.solanamobile.com

---

**Maintained by**: Agentic Reserve  
**Last Updated**: February 18, 2026
