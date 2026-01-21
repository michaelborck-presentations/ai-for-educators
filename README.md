# AI for Educators

A 60-minute faculty development presentation helping educators understand and use AI thoughtfully in their teaching practice.

## Overview

This resource focuses on a core insight: **at the heart of ALL AI are instructions**. Rather than overwhelming educators with jargon like "prompt engineering" or "context engineering," we focus on giving clear instructions and developing judgment about when and how to use AI.

**Key themes:**
- Addressing AI shame and the fear of irrelevance
- Your expertise matters MORE, not less
- Three practical techniques you can use and teach
- Assessment design for the AI era
- Ethics and verification

## Live Website

**Companion Website:** [https://michaelborck-presentations.github.io/ai-for-educators/](https://michaelborck-presentations.github.io/ai-for-educators/)

## Session Structure (60 minutes)

| Time | Section | Duration |
|------|---------|----------|
| 0:00 | Opening Hook (Deloitte Case) | 3 min |
| 0:03 | Part 1: The Real Barrier | 10 min |
| 0:13 | Part 2: The Core Concept | 7 min |
| 0:20 | Part 3: Three Techniques | 20 min |
| 0:40 | Part 4: Assessment Reality | 10 min |
| 0:50 | Part 5: Ethics & Next Steps | 8 min |
| 0:58 | Wrap-up & Resources | 2 min |

## Three Core Techniques

1. **Board of Directors** - Get multiple expert perspectives in one prompt
2. **Devil's Advocate** - Force AI to argue against your position
3. **Reverse Prompting** - Let AI interview YOU before giving advice

## Repository Structure

```
.
├── docs/                    # Generated website (GitHub Pages)
│   ├── index.html          # Landing page with learning paths
│   ├── handout.html        # Educator handout with prompts
│   ├── diagnostic.html     # Personalised learning path quiz
│   ├── style-mirror.html   # Tool to help AI match your voice
│   └── content/            # Deep-dive learning modules
├── source/                  # Source files
│   ├── slides.qmd          # Presentation slides (Quarto)
│   ├── instructor-guide.md # Facilitator guide
│   ├── marketing.md        # Invitation template
│   └── images/             # Presentation visuals
├── content/                 # Deep-dive module sources (.qmd)
├── _quarto.yml             # Quarto configuration
└── README.md
```

## Companion Website Features

- **Learning Paths** - 5-minute, 20-minute, or 60-minute options
- **Diagnostic Quiz** - Get personalised recommendations
- **Educator Handout** - Copy-paste prompts ready to use
- **Style Mirror** - Help AI write in your voice
- **Deep-Dive Guides** - What is AI, LLMs, CRAFT framework, Seven Techniques

## Building the Site

This project uses [Quarto](https://quarto.org/) to generate the website.

```bash
# Install Quarto first: https://quarto.org/docs/get-started/

# Render all content
quarto render

# Preview locally
quarto preview
```

## Related Presentations

This is part of a series of AI literacy resources:

- **AI for Educators** (this repo) - 60-min faculty development
- [AI in the Curriculum](https://github.com/michaelborck-presentations/AI-in-the-Curriculum) - 20-min overview
- [AI in Pedagogical Design and Delivery](https://github.com/michaelborck-presentations/ai-in-pedagogical-design-and-delivery) - 2-hour workshop

## Author

**Dr. Michael Borck**
Curtin University
Business AI Research Group

## License

This work is shared for educational purposes. Please attribute if reusing.
