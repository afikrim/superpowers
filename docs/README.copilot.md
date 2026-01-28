# Installing Superpowers for GitHub Copilot CLI (Standalone)

Complete guide for enabling Superpowers with the standalone GitHub Copilot CLI.

## Prerequisites

- GitHub Copilot CLI installed and authenticated
- Git installed

## Installation Steps

### 1. Clone Superpowers

```bash
mkdir -p ~/.copilot/superpowers
cd ~/.copilot/superpowers
git clone https://github.com/obra/superpowers.git .
```

### 2. Create personal skills directory

```bash
mkdir -p ~/.copilot/skills
```

### 3. Update ~/.copilot/AGENTS.md

Add this section:

```markdown
## Superpowers System

<EXTREMELY_IMPORTANT>
You have superpowers. Superpowers teach you new skills and capabilities. RIGHT NOW run: `~/.copilot/superpowers/.copilot/superpowers-copilot bootstrap` and follow the instructions it returns.
</EXTREMELY_IMPORTANT>
```

## Verification

```bash
~/.copilot/superpowers/.copilot/superpowers-copilot bootstrap
```

You should see skill listings and bootstrap instructions. The system is now ready for use.

## Updating

```bash
cd ~/.copilot/superpowers
git pull
```
