# Daily Paper

Automated arXiv paper collection and personalized research daily report generator.

## Features

- 🔍 **Multi-source Collection** - RSS feeds + arXiv search
- 📊 **Smart Classification** - Auto-categorize by research relevance (⭐⭐⭐⭐⭐/⭐⭐⭐⭐/⭐⭐⭐)
- 📝 **Structured Output** - Standard Markdown format reports
- 🎯 **Personalized** - Filter papers based on research interests

## Usage

1. Configure API keys in `opencode.json`
2. Set RSS information in `SKILL.md`
3. Run trigger word: "research daily"

## Output Format

Reports saved to `daily/{date}.md`, including:
- Data source statistics
- Ranked paper recommendations
- Action suggestions
- Research insights

## Dependencies

- Chrome MCP (RSS access)
- arXiv MCP (paper search)
- Large Language Model (content generation)
