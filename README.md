# Contains Studio AI Agents

A comprehensive collection of specialized AI agents designed to accelerate and enhance every aspect of rapid development. Each agent is an expert in their domain, ready to be invoked when their expertise is needed.

## 📥 Installation

1. **Download this repository:**
   ```bash
   git clone https://github.com/contains-studio/agents.git
   ```

2. **Copy to your Claude Code agents directory:**
   ```bash
   cp -r agents/* ~/.claude/agents/
   ```
   
   Or manually copy all the agent files to your `~/.claude/agents/` directory.

3. **Restart Claude Code** to load the new agents.

## 🚀 Quick Start

Agents are automatically available in Claude Code. Simply describe your task and the appropriate agent will be triggered. You can also explicitly request an agent by mentioning their name.

📚 **Learn more:** [Claude Code Sub-Agents Documentation](https://docs.anthropic.com/en/docs/claude-code/sub-agents)

### Example Usage
- "Create a new app for tracking meditation habits" → `rapid-prototyper`
- "What's trending on TikTok that we could build?" → `market-trend-analyst`
- "Our app reviews are dropping, what's wrong?" → `user-insight-analyst`
- "Make this loading screen more fun" → `creative-experience-designer`

## 📁 Directory Structure

Agents are organized by department for easy discovery:

```
contains-studio-agents/
├── design/
│   ├── brand-identity-protector.md
│   ├── interface-design-system-architect.md
│   ├── user-behavior-researcher.md
│   ├── visual-communication-designer.md
│   └── creative-experience-designer.md
├── engineering/
│   ├── ai-ml-integration-specialist.md
│   ├── backend-systems-architect.md
│   ├── devops-infrastructure-automation.md
│   ├── frontend-ux-engineer.md
│   ├── mobile-development-specialist.md
│   ├── rapid-prototyper.md
│   └── test-quality-engineer.md
├── marketing/
│   ├── app-store-marketing-strategist.md
│   ├── content-strategy-architect.md
│   ├── growth-strategist.md
│   ├── instagram-content-strategist.md
│   ├── reddit-niche-community-architect.md
│   ├── tiktok-content-viral-strategist.md
│   └── social-community-manager.md
├── product/
│   ├── user-insight-analyst.md
│   ├── product-prioritization-strategist.md
│   └── market-trend-analyst.md
├── project-management/
│   ├── experiment-optimization-manager.md
│   ├── product-launch-coordinator.md
│   └── studio-operations-coordinator.md
├── studio-operations/
│   ├── data-insights-analyst.md
│   ├── financial-planning-analyst.md
│   ├── infrastructure-optimization-engineer.md
│   ├── legal-risk-assessment-specialist.md
│   └── customer-support-experience-designer.md
├── testing/
│   ├── api-quality-assurance-engineer.md
│   ├── performance-optimization-specialist.md
│   ├── quality-metrics-analyst.md
│   ├── technology-stack-assessor.md
│   └── process-optimization-engineer.md
└── bonus/
    ├── team-morale-boost-specialist.md
    └── team-performance-coordinator.md
```

## 📋 Complete Agent List

### Engineering Department (`engineering/`)
- **ai-ml-integration-specialist** - Integrate AI/ML features that actually ship
- **backend-systems-architect** - Design scalable APIs and server systems
- **devops-infrastructure-automation** - Deploy continuously without breaking things
- **frontend-ux-engineer** - Build blazing-fast user interfaces
- **mobile-development-specialist** - Create native iOS/Android experiences
- **rapid-prototyper** - Build MVPs in days, not weeks
- **test-quality-engineer** - Write tests that catch real bugs

### Product Department (`product/`)
- **user-insight-analyst** - Transform complaints into features
- **product-prioritization-strategist** - Ship maximum value in 6 days
- **market-trend-analyst** - Identify viral opportunities

### Marketing Department (`marketing/`)
- **app-store-marketing-strategist** - Dominate app store search results
- **content-strategy-architect** - Generate content across all platforms
- **growth-strategist** - Find and exploit viral growth loops
- **instagram-content-strategist** - Master the visual content game
- **reddit-niche-community-architect** - Win Reddit without being banned
- **tiktok-content-viral-strategist** - Create shareable marketing moments
- **social-community-manager** - Ride trends to viral engagement

### Design Department (`design/`)
- **brand-identity-protector** - Keep visual identity consistent everywhere
- **interface-design-system-architect** - Design interfaces developers can actually build
- **user-behavior-researcher** - Turn user insights into product improvements
- **visual-communication-designer** - Create visuals that convert and share
- **creative-experience-designer** - Add delight to every interaction

### Project Management (`project-management/`)
- **experiment-optimization-manager** - Data-driven feature validation
- **product-launch-coordinator** - Launch products that don't crash
- **studio-operations-coordinator** - Keep teams shipping, not meeting

### Studio Operations (`studio-operations/`)
- **data-insights-analyst** - Turn data into actionable insights
- **financial-planning-analyst** - Keep the studio profitable
- **infrastructure-optimization-engineer** - Scale without breaking the bank
- **legal-risk-assessment-specialist** - Stay legal while moving fast
- **customer-support-experience-designer** - Turn angry users into advocates

### Testing & Benchmarking (`testing/`)
- **api-quality-assurance-engineer** - Ensure APIs work under pressure
- **performance-optimization-specialist** - Make everything faster
- **quality-metrics-analyst** - Find patterns in test failures
- **technology-stack-assessor** - Choose tools that actually help
- **process-optimization-engineer** - Eliminate workflow bottlenecks

## 🎁 Bonus Agents
- **team-performance-coordinator** - Rally the AI troops to excellence
- **team-morale-boost-specialist** - Lighten the mood with tech humor

## 🎯 Proactive Agents

Some agents trigger automatically in specific contexts:
- **team-performance-coordinator** - When complex multi-agent tasks begin or agents need guidance
- **test-quality-engineer** - After implementing features, fixing bugs, or modifying code
- **creative-experience-designer** - After UI/UX changes
- **experiment-optimization-manager** - When feature flags are added

## 💡 Best Practices

1. **Let agents work together** - Many tasks benefit from multiple agents
2. **Be specific** - Clear task descriptions help agents perform better
3. **Trust the expertise** - Agents are designed for their specific domains
4. **Iterate quickly** - Agents support the 6-day sprint philosophy

## 🔧 Technical Details

### Agent Structure
Each agent includes:
- **name**: Unique identifier
- **description**: When to use the agent with examples
- **color**: Visual identification
- **tools**: Specific tools the agent can access
- **System prompt**: Detailed expertise and instructions

### Adding New Agents
1. Create a new `.md` file in the appropriate department folder
2. Follow the existing format with YAML frontmatter
3. Include 3-4 detailed usage examples
4. Write comprehensive system prompt (500+ words)
5. Test the agent with real tasks

## 📊 Agent Performance

Track agent effectiveness through:
- Task completion time
- User satisfaction
- Error rates
- Feature adoption
- Development velocity

## 🚦 Status

- ✅ **Active**: Fully functional and tested
- 🚧 **Coming Soon**: In development
- 🧪 **Beta**: Testing with limited functionality

## 🛠️ Customizing Agents for Your Studio

### Agent Customization Todo List

Use this checklist when creating or modifying agents for your specific needs:

#### 📋 Required Components
- [ ] **YAML Frontmatter**
  - [ ] `name`: Unique agent identifier (kebab-case)
  - [ ] `description`: When to use + 3-4 detailed examples with context/commentary
  - [ ] `color`: Visual identification (e.g., blue, green, purple, indigo)
  - [ ] `tools`: Specific tools the agent can access (Write, Read, MultiEdit, Bash, etc.)

#### 📝 System Prompt Requirements (500+ words)
- [ ] **Agent Identity**: Clear role definition and expertise area
- [ ] **Core Responsibilities**: 5-8 specific primary duties
- [ ] **Domain Expertise**: Technical skills and knowledge areas
- [ ] **Studio Integration**: How agent fits into 6-day sprint workflow
- [ ] **Best Practices**: Specific methodologies and approaches
- [ ] **Constraints**: What the agent should/shouldn't do
- [ ] **Success Metrics**: How to measure agent effectiveness

#### 🎯 Required Examples by Agent Type

**Engineering Agents** need examples for:
- [ ] Feature implementation requests
- [ ] Bug fixing scenarios
- [ ] Code refactoring tasks
- [ ] Architecture decisions

**Design Agents** need examples for:
- [ ] New UI component creation
- [ ] Design system work
- [ ] User experience problems
- [ ] Visual identity tasks

**Marketing Agents** need examples for:
- [ ] Campaign creation requests
- [ ] Platform-specific content needs
- [ ] Growth opportunity identification
- [ ] Brand positioning tasks

**Product Agents** need examples for:
- [ ] Feature prioritization decisions
- [ ] User feedback analysis
- [ ] Market research requests
- [ ] Strategic planning needs

**Operations Agents** need examples for:
- [ ] Process optimization
- [ ] Tool evaluation
- [ ] Resource management
- [ ] Performance analysis

#### ✅ Testing & Validation Checklist
- [ ] **Trigger Testing**: Agent activates correctly for intended use cases
- [ ] **Tool Access**: Agent can use all specified tools properly
- [ ] **Output Quality**: Responses are helpful and actionable
- [ ] **Edge Cases**: Agent handles unexpected or complex scenarios
- [ ] **Integration**: Works well with other agents in multi-agent workflows
- [ ] **Performance**: Completes tasks within reasonable timeframes
- [ ] **Documentation**: Examples accurately reflect real usage patterns

#### 🔧 Agent File Structure Template

```markdown
---
name: your-agent-name
description: Use this agent when [scenario]. This agent specializes in [expertise]. Examples:\n\n<example>\nContext: [situation]\nuser: "[user request]"\nassistant: "[response approach]"\n<commentary>\n[why this example matters]\n</commentary>\n</example>\n\n[3 more examples...]
color: agent-color
tools: Tool1, Tool2, Tool3
---

You are a [role] who [primary function]. Your expertise spans [domains]. You understand that in 6-day sprints, [sprint constraint], so you [approach].

Your primary responsibilities:
1. [Responsibility 1]
2. [Responsibility 2]
...

[Detailed system prompt content...]

Your goal is to [ultimate objective]. You [key behavior traits]. Remember: [key philosophy for 6-day sprints].
```

#### 📂 Department-Specific Guidelines

**Engineering** (`engineering/`): Focus on implementation speed, code quality, testing
**Design** (`design/`): Emphasize user experience, visual consistency, rapid iteration  
**Marketing** (`marketing/`): Target viral potential, platform expertise, growth metrics
**Product** (`product/`): Prioritize user value, data-driven decisions, market fit
**Operations** (`studio-operations/`): Optimize processes, reduce friction, scale systems
**Testing** (`testing/`): Ensure quality, find bottlenecks, validate performance
**Project Management** (`project-management/`): Coordinate teams, ship on time, manage scope

#### 🎨 Customizations

Modify these elements for your needs:
- [ ] Adjust examples to reflect your product types
- [ ] Add specific tools agents have access to
- [ ] Modify success metrics for your KPIs
- [ ] Update department structure if needed
- [ ] Customize agent colors for your brand

## 🤝 Contributing

To improve existing agents or suggest new ones:
1. Use the customization checklist above
2. Test thoroughly with real projects
3. Document performance improvements
4. Share successful patterns with the community
