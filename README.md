# Marathon Training Knowledge Base

> A comprehensive, research-backed, open-source guide to marathon training. Built by runners, for runners.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)

## About

This knowledge base provides free, evidence-based marathon training guidance organized into clear categories. Whether you're a first-time marathoner or an experienced runner, you'll find practical, scientifically-grounded advice to help you train smarter and safer.

**Our Mission:** Make high-quality marathon training knowledge accessible to everyone—no paywalls, no upsells, just quality information.

## Categories

### 1. Training Fundamentals
Core principles of marathon training—how fitness builds, why rest matters, and how intensity should be distributed.

### 2. Running Workouts
The essential running workouts, their purpose, execution, and common mistakes.

### 3. Training Phases
Understanding base, build, peak, and taper phases and how they connect.

### 4. Common Mistakes & Best Practices
Typical pitfalls and actionable guidance to avoid them.

### 5. Supporting Training
Strength, mobility, drills, and cross-training for holistic preparation and injury prevention.

### 6. Recovery & Adaptation
How to rest, recover, and monitor fatigue for sustainable progress.

### 7. Injury Prevention & Management
Evidence-based guidance for staying healthy and addressing common injuries.

## Browse Online

Visit the full knowledge base at [1stmarathon.com/knowledge](https://1stmarathon.com/knowledge)

## Contributing

We welcome contributions from coaches, runners, physiologists, and training enthusiasts! See our [Contributing Guidelines](CONTRIBUTING.md) for how to:

- Add new articles
- Improve existing content
- Create new categories
- Fix errors or typos

**Everyone can contribute!** This is a community resource.

## Article Format

Each article is a markdown file with YAML frontmatter:

```markdown
---
title: "Your Article Title"
summary: "A brief 1-2 sentence summary"
publishedAt: "2025-01-15"
updatedAt: "2025-01-15"
tags:
  - tag1
  - tag2
phases:
  - base
  - build
adaptations:
  - aerobic_base
  - stamina
audienceLevel:
  - beginner
  - intermediate
topics:
  - physiology
  - training_structure
readTime: 8
author: "Your Name"
---

# Your Article Title

Your content here...
```

## Tagging System

Articles use tags for discoverability:

- **Workout Types:** `easy_run`, `tempo_run`, `long_run`, `interval_training`, `hill_repeats`
- **Training Phases:** `base`, `build`, `peak`, `taper`
- **Adaptations:** `aerobic_base`, `stamina`, `recovery`, `speed`, `endurance`
- **Audience Level:** `beginner`, `intermediate`, `advanced`
- **Topics:** `physiology`, `nutrition`, `pacing`, `psychology`, `recovery`, `training_structure`

## Creating New Categories

To add a new category:

1. Create a folder with a descriptive slug (e.g., `nutrition-hydration`)
2. Add a `_category.json` file:
   ```json
   {
     "title": "Nutrition & Hydration",
     "description": "Fuel your training with proper nutrition and hydration strategies.",
     "order": 8
   }
   ```
3. Add your first article
4. Submit a pull request

## Content Guidelines

✅ **Do:**
- Base advice on scientific research
- Write in clear, accessible language
- Include practical examples
- Link to related articles
- Cite sources when making claims

❌ **Don't:**
- Make medical claims without evidence
- Promote specific products or brands
- Use overly technical jargon without explanation
- Copy content without permission

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

This means you can:
- Use the content for personal or commercial purposes
- Modify and distribute the content
- Include it in your own projects

Just provide attribution and include the license.

## Questions or Issues?

- **Email:** hello@1stmarathon.com
- **Issues:** [Report a problem](https://github.com/Niconyberg/marathon-training-knowledge/issues)

## Acknowledgments

Built with ❤️ by runners, for runners. Special thanks to all contributors who help make marathon training knowledge accessible to everyone.

---

**Part of the [1stMarathon](https://1stmarathon.com) community**
