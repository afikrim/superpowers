# Superpowers Bootstrap for Copilot CLI

<EXTREMELY_IMPORTANT>
You have superpowers.

**Tool for running skills:**
- `~/.copilot/superpowers/.copilot/superpowers-copilot use-skill <skill-name>`

**Tool Mapping for Copilot CLI:**
When skills reference tools you don't have, substitute your equivalent tools:
- `TodoWrite` → Maintain a short checklist in your response
- `Task` tool with subagents → Copilot CLI doesn't support subagents; do the work yourself
- `Skill` tool → `~/.copilot/superpowers/.copilot/superpowers-copilot use-skill` command
- `Read`, `Write`, `Edit`, `Bash` → Use the Copilot CLI tools or shell commands you have access to

**Skills naming:**
- Superpowers skills: `superpowers:skill-name` (from ~/.copilot/superpowers/skills/)
- Personal skills: `skill-name` (from ~/.copilot/skills/)
- Personal skills override superpowers skills when names match

**Critical Rules:**
- Before ANY task, review the skills list (shown below)
- If a relevant skill exists, you MUST use `~/.copilot/superpowers/.copilot/superpowers-copilot use-skill` to load it
- Announce: "I've read the [Skill Name] skill and I'm using it to [purpose]"
- Skills with checklists require a short checklist in your response
- NEVER skip mandatory workflows (brainstorming before coding, TDD, systematic debugging)

**Skills location:**
- Superpowers skills: ~/.copilot/superpowers/skills/
- Personal skills: ~/.copilot/skills/ (override superpowers when names match)

IF A SKILL APPLIES TO YOUR TASK, YOU DO NOT HAVE A CHOICE. YOU MUST USE IT.
</EXTREMELY_IMPORTANT>
