# Contributing Guidelines

Welcome! We appreciate your interest in contributing to our Raid: Shadow Legends fan community resource.

## Before You Start

**IMPORTANT**: This is a fan-made, community-driven project. By contributing, you agree to:

1. Respect Plarium Games' intellectual property rights
2. Not reproduce copyrighted game content
3. Create original guides, strategies, and analysis
4. Include proper attribution and disclaimers
5. Comply with all legal guidelines in [LEGAL.md](./LEGAL.md)

## Ways to Contribute

### 1. Content Contributions

- **Strategy Guides**: Write original guides for dungeons, campaigns, or content
- **Champion Analysis**: Create original tier lists and champion evaluations
- **Build Guides**: Share original team compositions and strategies
- **Bug Reports**: Report website issues or outdated information

### 2. Code Contributions

- **Bug Fixes**: Fix identified issues
- **Features**: Develop new tools like team builders or database managers
- **Documentation**: Improve guides and documentation
- **Testing**: Help test new features

### 3. Community Contributions

- **Forum Moderation**: Help moderate discussions
- **Community Feedback**: Suggest improvements
- **Translations**: Help translate content

## Getting Started

### Step 1: Fork & Clone

```bash
git clone https://github.com/alicethewanderer93-pixel/RaidLegendsGuide.git
cd RaidLegendsGuide
```

### Step 2: Create a Branch

```bash
git checkout -b feature/your-feature-name
# or for bugfixes
git checkout -b bugfix/issue-description
```

### Step 3: Make Your Changes

- Follow the code style guidelines
- Write clear, descriptive commit messages
- Test your changes thoroughly

### Step 4: Commit & Push

```bash
git add .
git commit -m "Brief description of changes"
git push origin feature/your-feature-name
```

### Step 5: Create a Pull Request

- Provide a clear description of changes
- Link any related issues
- Include tests if applicable
- Ensure all changes comply with [LEGAL.md](./LEGAL.md)

## Content Guidelines

### For Strategy Guides

- ✅ DO: Share original strategies and analysis
- ✅ DO: Include alternative approaches
- ✅ DO: Credit other contributors
- ❌ DON'T: Copy content from other sites
- ❌ DON'T: Reproduce large sections of official game text

### For Code

```javascript
// Include disclaimer headers in files handling game data
/**
 * @fileoverview Fan-made champion data handler
 * @disclaimer This is unofficial community content related to Raid: Shadow Legends
 * Game content © Plarium Games Ltd. This code is MIT licensed.
 */
```

### For Images/Assets

- Use placeholders or fan-created artwork
- Include attribution if using community art
- Never reproduce official game screenshots excessively
- Use watermarks for original creations

## Code Style

### JavaScript/Node.js

```javascript
// Use clear variable names
const championDatabase = [];

// Include comments for complex logic
function calculateDamage(attacker, defender) {
    // Implementation
}

// Use async/await for promises
async function fetchChampions() {
    const data = await db.find();
    return data;
}
```

### CSS/Styling

```css
/* Use meaningful class names */
.champion-card {
    background: #0f3460;
    padding: 20px;
}

/* Group related properties */
.header {
    margin: 0;
    padding: 20px;
    border-bottom: 2px solid #d4af37;
}
```

## Commit Message Format

```
type(scope): subject

body

footer
```

**Types**: feature, fix, docs, style, refactor, test, chore

**Examples**:
- `feature(champions): add champion database search`
- `fix(guides): correct arena strategy guide link`
- `docs(legal): update legal disclaimer`

## Pull Request Checklist

- [ ] Code follows project style guidelines
- [ ] Changes include appropriate comments/documentation
- [ ] Content respects Plarium Games IP (see [LEGAL.md](./LEGAL.md))
- [ ] No copyrighted content reproduced
- [ ] Tested and working as intended
- [ ] PR description clearly explains changes
- [ ] Related issues are linked

## Legal Compliance Checklist

Before submitting content:

- [ ] I have reviewed [LEGAL.md](./LEGAL.md)
- [ ] My content is original or properly attributed
- [ ] I'm not reproducing extensive copyrighted material
- [ ] I've included appropriate disclaimers
- [ ] My contribution respects Plarium Games' IP rights
- [ ] I understand this is a fan project

## Reporting Issues

### Bug Reports

Include:
- Detailed description
- Steps to reproduce
- Expected vs. actual behavior
- Screenshots if applicable
- Browser/environment info

### Feature Requests

Include:
- Clear use case
- Why this feature is needed
- Proposed implementation (optional)
- Mockups (optional)

## Review Process

1. Project maintainers review your PR
2. Feedback provided (if needed)
3. You address comments
4. PR is approved and merged
5. Your contribution is published

## Code of Conduct

- Be respectful and constructive
- No harassment, discrimination, or hate speech
- Focus on ideas, not individuals
- Help others learn and grow
- Respect intellectual property rights

## Questions?

- Open an issue with label `question`
- Check existing documentation
- Review past issues and PRs
- Contact maintainers respectfully

## Attribution

Contributors will be credited in:
- Project README
- Contributors list
- Commit history
- Major feature credits

## License

By contributing, you agree your code contributions are licensed under MIT, and content contributions are subject to fair use principles regarding game-related material.

---

**Last Updated**: 2026-07-03

Thank you for helping build this community resource! 🗡️
