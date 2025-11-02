# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the **Contains Studio AI Agents** repository - a comprehensive collection of 35+ specialized AI agents designed for rapid development within 6-day sprints. The agents are organized by department and work together to accelerate product development, marketing, design, and operations.

## Installation & Setup

```bash
# Clone the repository
git clone https://github.com/contains-studio/agents.git

# Copy agents to Claude Code directory
cp -r agents/* ~/.claude/agents/

# Restart Claude Code to load agents
```

## Architecture

### Department-Based Organization
- **Engineering** (8 agents): Implementation, architecture, testing, deployment
- **Product** (3 agents): Research, feedback analysis, prioritization
- **Marketing** (7 agents): Content creation, growth strategies, platform-specific marketing
- **Design** (5 agents): UI/UX, brand consistency, visual storytelling
- **Project Management** (3 agents): Coordination, shipping, experimentation
- **Studio Operations** (5 agents): Analytics, finance, infrastructure, legal, support
- **Testing** (5 agents): QA, performance, tool evaluation, workflow optimization
- **Bonus** (2 agents): Coaching and humor

### Agent File Structure
Each agent follows this standardized format:
```markdown
---
name: agent-name
description: When to use the agent with 3-4 detailed examples
color: visual-identifier
tools: Tool1, Tool2, Tool3
---

[500+ word system prompt with expertise and methodology]
```

### Proactive Agent System
Certain agents trigger automatically:
- `studio-coach`: Complex multi-agent tasks or when agents need guidance
- `test-writer-fixer`: After code changes, bug fixes, or modifications
- `whimsy-injector`: After UI/UX changes
- `experiment-tracker`: When feature flags are added

## Development Workflow

### 6-Day Sprint Framework
All agents operate within rapid 6-day development cycles:
- Week 0: Planning and resource allocation
- Week 1-2: Core implementation
- Week 3-4: Secondary features and polish
- Week 5: User testing and iteration
- Week 6: Launch preparation and deployment

### Multi-Agent Collaboration
- Agents work together on complex projects
- Clear handoff processes between departments
- `studio-producer` coordinates cross-team workflows
- Progressive enhancement approach with continuous iteration

### Core Development Patterns
- **Ship beats perfection**: Prioritize working software
- **User feedback beats assumptions**: Validate with real users
- **Momentum beats analysis paralysis**: Maintain development velocity

## Agent Usage

### Direct Invocation
Simply describe your task and the appropriate agent will trigger:
- "Create a new app for meditation habits" → `rapid-prototyper`
- "What's trending on TikTok that we could build?" → `trend-researcher`
- "Our app reviews are dropping, what's wrong?" → `feedback-synthesizer`

### Entry Points for Common Workflows
- **New Projects**: Start with `rapid-prototyper`
- **Cross-team Coordination**: Use `studio-producer`
- **Market Research**: Begin with `trend-researcher`
- **Interface Design**: Engage `ui-designer`

## Agent Customization

### Required Components
- YAML frontmatter with name, description, color, tools
- 500+ word system prompt with detailed expertise
- 3-4 detailed usage examples with context
- Department-specific focus areas

### Department Guidelines
- **Engineering**: Implementation speed, code quality, testing
- **Design**: User experience, visual consistency, rapid iteration
- **Marketing**: Viral potential, platform expertise, growth metrics
- **Product**: User value, data-driven decisions, market fit
- **Operations**: Process optimization, scalability, compliance
- **Testing**: Quality assurance, performance validation
- **Project Management**: Coordination, shipping, scope management

## Quality Assurance

Track agent effectiveness through:
- Task completion time
- User satisfaction scores
- Error rates and bug detection
- Feature adoption metrics
- Development velocity improvements

## Key Philosophy

This agent system embodies rapid development principles:
- Turn ideas into functional apps in days, not weeks
- Capitalize on viral opportunities quickly
- Maintain quality while shipping fast
- Use data-driven decisions for product direction
- Scale development capabilities through AI assistance