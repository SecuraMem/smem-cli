# 🧠 AntiGoldfishMode

**AI Memory Engine - Built by AI, for AI**

> *Because AI assistants shouldn't have goldfish memory!*

Transform your AI coding assistant from a stateless tool into a learning, context-aware development partner with persistent memory across all conversations.

## 🎯 **The Problem**

AI coding assistants forget everything between conversations. They can't learn from past interactions, remember your preferences, or build upon previous solutions.

## ✨ **The Solution**

AntiGoldfishMode gives AI assistants persistent memory, enabling them to:
- 🧠 **Remember** every conversation and solution
- 🔍 **Recall** relevant information from past interactions
- 📈 **Learn** from previous decisions and mistakes
- 🎯 **Adapt** to your coding style and preferences

## ⚡ **Quick Start**

```bash
# Install globally
npm install -g antigoldfishmode

# Initialize in your project
antigoldfishmode init

# Activate with license key
antigoldfishmode activate <your-license-key>
```

## 🚀 **Core Commands**

```bash
# Store important information
antigoldfishmode remember "Fixed React hydration issue by moving useState to useEffect"

# Search past memories
antigoldfishmode recall "React hydration"

# Check system status
antigoldfishmode status
```

## 🤖 **For AI Assistants**

AI assistants can use AntiGoldfishMode autonomously to build persistent memory across conversations:

```bash
# Get operating instructions
antigoldfishmode ai-guide

# Store solutions and insights
antigoldfishmode remember "User prefers TypeScript strict mode for all components"

# Search before solving problems
antigoldfishmode recall "TypeScript configuration"
```

## 📖 **Command Reference**

### `remember` - Store Information
```bash
antigoldfishmode remember "Fixed React hydration by moving useState to useEffect"
antigoldfishmode remember "User prefers functional components" --context "preferences"
```

### `recall` - Search Memories
```bash
antigoldfishmode recall "React hydration"
antigoldfishmode recall "user preferences" --limit 5
```

### `status` - System Information
```bash
antigoldfishmode status
```


## 🔍 Transparency & Replay (Glassbox)

- Plan & Mirror: see exactly what will run (trace/explain)
- Dry‑Run: safe by default for replay; supported by index/search
- Receipts v1: standardized, machine‑readable audit records
- Journal: append‑only command log
- Integrity Digests: fileListDigest (index), resultDigest (search), batch digest (replay)
- Tools: `antigoldfishmode receipt-show --last`

Examples
```bash
# Index (trace + json)
antigoldfishmode index-code --path . --max-chunk 200 --trace --json

# Search (preview + filter + json)
antigoldfishmode search-code "SymbolName" -k 10 --preview 3 --filter-path src/**/*.ts --trace --json

# Replay last (safe dry‑run)
antigoldfishmode replay --last --trace

# Inspect last receipt
antigoldfishmode receipt-show --last
```

## 🏗 **How It Works**

- **Local Storage**: All data stays on your machine in `.antigoldfishmode/`
- **SQLite Database**: Fast, reliable storage with full-text search
- **Automatic Recording**: Every interaction is logged for future reference
- **Machine-Specific**: Each installation is unique and secure

## 🎯 **Perfect For**

- **AI-Enhanced Development**: Give your AI assistant persistent memory
- **Knowledge Building**: Create a searchable repository of solutions
- **Team Collaboration**: Share insights across development sessions
- **Learning AI**: Help AI assistants learn your preferences and patterns

## 💰 **Pricing**

- **Trial**: 7 days free with full features
- **Standard**: $149/year for unlimited memory and conversation recording

## 🚀 **Get Started**

1. Install: `npm install -g antigoldfishmode`
2. Initialize: `antigoldfishmode init`
3. Activate: `antigoldfishmode activate <license-key>`
4. Start using: `antigoldfishmode remember "your first memory"`

---

**Transform your AI coding assistant from goldfish to elephant memory!** 🐘✨
