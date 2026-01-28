# Installing Superpowers for GitHub Copilot CLI (Standalone)

Quick setup to enable Superpowers skills in the standalone GitHub Copilot CLI.

## Prerequisites

- GitHub Copilot CLI installed and authenticated

## Installation

1. **Clone superpowers repository**:
   ```bash
   mkdir -p ~/.copilot/superpowers
   cd ~/.copilot/superpowers
   git clone https://github.com/obra/superpowers.git .
   ```

2. **Create personal skills directory**:
   ```bash
   mkdir -p ~/.copilot/skills
   ```

3. **Update ~/.copilot/AGENTS.md** to include this superpowers section:
   ```markdown
   ## Superpowers System

   <EXTREMELY_IMPORTANT>
   You have superpowers. Superpowers teach you new skills and capabilities. RIGHT NOW run: `~/.copilot/superpowers/.copilot/superpowers-copilot bootstrap` and follow the instructions it returns.
   </EXTREMELY_IMPORTANT>
   ```

## Verification

Test the installation:
```bash
~/.copilot/superpowers/.copilot/superpowers-copilot bootstrap
```

You should see skill listings and bootstrap instructions. The system is now ready for use.
