---
name: code-research-crafter
description: A complete workflow for researching codebases, designing enhancement proposals, and publishing RFCs to GitHub. Covers code analysis, academic research, solution design, documentation generation, and RFC publication.
license: MIT
---

# Code Research Crafter

Craft comprehensive research proposals from code analysis to GitHub RFC publication.

## Overview

This skill provides a complete 6-phase workflow for deep codebase research and professional proposal crafting:

1. **Code Analysis** - Understanding existing implementation through systematic exploration
2. **Academic Research** - Finding relevant papers, algorithms, and prior art
3. **Community Analysis** - Reviewing GitHub issues, discussions, and maintainer feedback
4. **Solution Design** - Architecture design with data models and phased implementation plans
5. **Documentation** - Generating structured technical documents (Chinese/English)
6. **RFC Publication** - Writing and submitting professional RFCs to GitHub

## When to Use

Use this skill when you need to:
- Analyze an open-source codebase and propose enhancements
- Research technical problems with academic rigor
- Design system architectures with evidence-based decisions
- Create professional RFCs for open-source communities
- Document complex technical proposals with proper citations

## Workflow

### Phase 1: Problem Discovery & Code Analysis

**Step 1: Identify the target area**
- Search for relevant files in the codebase using glob patterns
- Look for GitHub issues related to the topic
- Check existing documentation (docs/, README, etc.)

**Step 2: Deep code analysis**
```bash
# Find relevant source files
glob **/[module]*/**/*.ts
glob **/[component]*.ts

# Read key implementation files
read src/[module]/[key-file].ts

# Search for specific patterns
grep "[pattern]" src/**/*.ts
```

**Step 3: Document findings**
- Note current architecture limitations
- Identify specific code locations causing issues
- Quantify problems with metrics (token counts, performance data, etc.)

### Phase 2: Academic & Community Research

**Step 4: Search for academic papers**
```
WebSearch: [topic] [domain] 2024 2025 paper
WebSearch: "[specific technique]" LLM agent [year]
```

**Step 5: Extract key insights from papers**
- Core innovations and algorithms
- Data models and architectures
- Experimental results and benchmarks
- Applicability to target codebase

**Step 6: Analyze GitHub community**
```
WebSearch: site:github.com/[org]/[repo]/issues [keywords]
```

- Read issue descriptions and discussions
- Identify common pain points
- Note maintainer responses and status
- Find related PRs and their outcomes

### Phase 3: Solution Design

**Step 7: Define design principles**
- Progressive enhancement (each layer independently valuable)
- Human organization analogies (HR records, team Slack, etc.)
- Backward compatibility
- Cost-awareness (token efficiency, performance)

**Step 8: Design architecture**
```
Layer N: [Name] ("Human analogy")
├── Problem: [Current limitation]
├── Solution: [High-level approach]
├── Data Model: [SQL schemas or interfaces]
├── Workflow: [Step-by-step process]
└── Integration: [How it fits existing code]
```

**Step 9: Design data models**
- SQL table schemas with field descriptions
- JSON structures for configurations
- TypeScript interfaces for type safety

**Step 10: Plan implementation phases**
| Phase | Scope | Dependencies | Effort | Value |
|-------|-------|--------------|--------|-------|
| P1 | ... | None | Small | ... |
| P2 | ... | P1 | Medium | ... |

### Phase 4: Documentation Generation

**Step 11: Generate technical document**
```python
from docx import Document

doc = Document()
# Sections:
# 1. Problem Analysis (with code evidence)
# 2. Academic Frontiers (paper summaries)
# 3. Solution Design (layered architecture)
# 4. Layer Synergy (complete scenario)
# 5. Implementation Plan
# 6. Open Questions
```

### Phase 5: English RFC Writing

**Step 12: Write RFC markdown**
```markdown
## [RFC] [Title]

### Motivation
[Problem statement with quantified impact]

### Prior Art & Related Issues
| Issue | Proposal | Status |

**Key academic references:**
- **Paper** (Authors, Year) — Key insight

### Proposed Architecture
[ASCII diagram]

#### Layer N: [Name] ("Analogy")
**Problem:** ...
**Solution:** ...
**Data model:** ```sql ... ```

### Implementation Plan
| Phase | Scope | Dependencies | Effort |

### Open Questions
1. ...

### Call for Collaboration
[Work split]
```

### Phase 6: GitHub Publication

**Step 13: Submit to GitHub**
- Open issue/PR creation page
- Fill title with [RFC] or [feature] prefix
- Paste complete markdown
- Submit and monitor feedback

## Key Principles

### 1. Evidence-Based Analysis
- Quote specific code locations
- Quantify problems with metrics
- Reference actual GitHub issues

### 2. Academic Rigor
- Find recent papers (2024-2025 preferred)
- Extract specific algorithms and data models
- Properly cite with arXiv/DOI links

### 3. Human-Centered Design
- Use human organization analogies
- Design for gradual adoption
- Consider technical and social aspects

### 4. Cost Awareness
- Track token/performance implications
- Design for efficiency
- Provide budget control mechanisms

### 5. Community Engagement
- Reference existing issues and contributors
- Invite collaboration with specific work splits
- Acknowledge prior art

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

## Tools & Resources

- `glob` / `grep` / `read` - Code analysis
- `WebSearch` / `WebFetch` - Academic research
- `python-docx` - Document generation
- `browser_use_desktop` - GitHub submission
- `desktop_terminal_execute` - Git operations

## Example Outputs

This skill has been used to create:
- Memory Consolidation RFC with Zettelkasten + PPR + Sleep Consolidation
- Multi-Agent Collaboration RFC with Capability Profiling + Shared Blackboard
- Temporal Decay bug fixes with expanded date patterns
- i18n translation improvements for config pages

## Success Metrics

- RFC receives community engagement (comments, reactions)
- Problems quantified with code evidence
- Solutions reference academic research
- Implementation plan is phased and actionable
- Documentation is clear for all audiences
