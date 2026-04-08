# my-agent-skills 👩🏽‍💻

My favorite agent skills to build with. 
These are production-ready skills I use daily as a Software Developer in an AI world. They have legit saved me so many hours of work.

## Skills

| Skill | Description |
| ----- | ----------- |
| [github-issues](skills/github-issues/) | Create, update, and manage GitHub issues using MCP tools. Handles bug reports, feature requests, task issues, labels, assignees, milestones, and issue workflows. |
| [performance-engineer](skills/performance-engineer/) | Expert performance engineering — observability, distributed tracing, load testing, caching, Core Web Vitals, and end-to-end optimization. |
| [prd](skills/prd/) | Generate high-quality Product Requirements Documents with executive summaries, user stories, technical specs, and risk analysis. |
| [review-and-refactor](skills/review-and-refactor/) | Senior-engineer-level code review and refactoring based on your project's coding guidelines and best practices. |
| [security-reviewer](skills/security-reviewer/) | Secure coding review for web applications — access control, input validation, output encoding, and defense in depth. |
| [web-design-reviewer](skills/web-design-reviewer/) | Visual inspection of websites to identify and fix design issues — responsive design, accessibility, visual consistency, and layout. |

## Manual Installation

### 1. Fork & Clone

```bash
# Fork this repo, then clone it
git clone https://github.com/<your-username>/my-agent-skills.git
```

### 2. Copy a Skill into Your Project

Each skill lives in its own folder under `skills/`. Copy the skill folder you want into your project's `.github/skills/` directory (or wherever your agent looks for skills):

```bash
# Example: add the security-reviewer skill to your project
cp -r skills/security-reviewer /path/to/your-project/.github/skills/
```

### 3. Use It

Open your preferred AI agent (GitHub Copilot, Claude, Cursor, etc.) in your project — the skill is now available. Reference it by name and let the agent do its thing.

> Repeat for any additional skills you want to add.

## Claude Code Installation

Skills in Claude Code live in your `~/.claude/` directory and are automatically discovered by Claude.

### If you don't have any skills yet

Copy the entire `skills/` folder into your `~/.claude/` directory:

```bash
cp -r skills/ ~/.claude/skills/
```

### Adding a single skill

If you already have skills set up and just want to add one:

```bash
# Example: add the security-reviewer skill
cp -r skills/security-reviewer ~/.claude/skills/
```

### Using a skill in Claude Code

Once installed, reference any skill by name in your conversation with a `/` prefix:

```
/security-reviewer
/prd
/review-and-refactor
```

Or just describe what you want — Claude will pick up the right skill automatically.

### Verify your skills are installed

```bash
ls ~/.claude/skills/
```

You should see the skill folders listed there.

## Copilot CLI Installation

Skills in Copilot CLI live in your `~/.copilot/skills/` directory and are automatically discovered by GitHub Copilot.

### If you don't have any skills yet

Copy the entire `skills/` folder into your `~/.copilot/` directory:

```bash
mkdir -p ~/.copilot/skills
cp -r skills/ ~/.copilot/skills/
```

### Adding a single skill

If you already have skills set up and just want to add one:

```bash
# Example: add the security-reviewer skill
cp -r skills/security-reviewer ~/.copilot/skills/
```

### Using a skill in Copilot CLI

Once installed, reference any skill by name in your prompt with a `/` prefix:

```
/security-reviewer
/prd
/review-and-refactor
```

Or just describe what you need — Copilot will pick up the right skill automatically.

### Verify your skills are installed

```bash
ls ~/.copilot/skills/
```

You should see the skill folders listed there.

---

## Contributing

Pull requests are welcome! If you have a skill that saves you time, feel free to open a PR.

## License

[MIT](LICENSE)

---

> Happy building and follow [@itsthatladydev](https://www.instagram.com/itsthatlady.dev/) for more AI Agents + Vibecoding content 💕
