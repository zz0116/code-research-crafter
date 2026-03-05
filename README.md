# Code Research Crafter

> Craft comprehensive research proposals from code analysis to GitHub RFC publication.

A complete workflow skill for researching codebases, designing enhancement proposals, and publishing professional RFCs to GitHub.

## What It Does

This skill guides you through a 6-phase workflow:

1. **Code Analysis** - Systematic exploration of existing implementation
2. **Academic Research** - Finding relevant papers and algorithms
3. **Community Analysis** - Reviewing GitHub issues and discussions
4. **Solution Design** - Architecture design with data models
5. **Documentation** - Generating structured technical documents
6. **RFC Publication** - Writing and submitting professional RFCs

## When to Use

- Analyzing open-source codebases and proposing enhancements
- Researching technical problems with academic rigor
- Designing system architectures with evidence-based decisions
- Creating professional RFCs for open-source communities
- Documenting complex technical proposals with proper citations

## Example Outputs

This skill has been used to create:

- **Memory Consolidation RFC** - Zettelkasten + PPR + Sleep Consolidation architecture
- **Multi-Agent Collaboration RFC** - 4-layer architecture with capability profiling and token cost governance
- **Bug Fixes** - Temporal decay date pattern expansion with comprehensive test coverage
- **i18n Improvements** - Config page translation extraction and Chinese localization

## Key Features

- **Evidence-Based**: Quantifies problems with code analysis and metrics
- **Academic Rigor**: Cites recent papers (2024-2025) with proper attribution
- **Human-Centered**: Uses organization analogies for intuitive design
- **Cost-Aware**: Considers token efficiency and performance implications
- **Community-Focused**: References existing issues and invites collaboration

## Installation

```bash
npx skills install code-research-crafter
```

Or manually:
```bash
mkdir -p ~/.stepfun/skills/code-research-crafter
cd ~/.stepfun/skills/code-research-crafter
# Download SKILL.md and LICENSE.txt
```

## Usage

Load the skill when starting a research task:

```
User: "I want to improve the memory system in OpenClaw"
Assistant: [Loads code-research-crafter skill]
Assistant: "I'll help you research and craft a proposal. Let me start with Phase 1: Code Analysis..."
```

## Workflow Overview

### Phase 1: Problem Discovery & Code Analysis
- Identify target area in codebase
- Deep code analysis with glob/grep/read
- Document findings with quantified metrics

### Phase 2: Academic & Community Research
- Search for relevant papers
- Extract algorithms and data models
- Analyze GitHub issues and discussions

### Phase 3: Solution Design
- Define design principles
- Design layered architecture
- Plan implementation phases

### Phase 4: Documentation Generation
- Generate technical documents (Chinese/English)
- Create data model diagrams
- Write implementation roadmap

### Phase 5: RFC Writing
- Write professional RFC markdown
- Include academic citations
- Design ASCII architecture diagrams

### Phase 6: GitHub Publication
- Submit to GitHub issues/PRs
- Monitor community feedback
- Iterate based on comments

## Common Patterns

### Layered Architecture
```
Layer 1: Foundation (data collection)
Layer 2: Enhancement (builds on L1)
Layer 3: Intelligence (AI/ML on data)
Layer 4: Governance (control/monitoring)
```

### Dual-Track Data
```
User-defined (static): config, prompts
System-learned (dynamic): metrics, patterns
```

### Visibility Tiers
```
private: owner only
team: collaborators
global: all users
```

## Tools Used

- `glob` / `grep` / `read` - Code analysis
- `WebSearch` / `WebFetch` - Academic research
- `python-docx` - Document generation
- `browser_use_desktop` - GitHub submission
- `desktop_terminal_execute` - Git operations

## License

MIT License - See LICENSE.txt

## Contributing

This skill is designed to be extended. Feel free to adapt the workflow for your specific needs.
