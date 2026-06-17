# Carousel Pose Library

AI-Ready Visual Pose Repository for Educational, Informational, and Social Media Carousel Content using the SCRIPT Framework.

---

# Overview

Carousel Pose Library is a structured visual asset repository designed to help AI systems and content creators generate engaging carousel content while maintaining readability, information hierarchy, and visual consistency.

This repository contains:

- Pose Assets
- Pose Metadata
- Asset Usage Guidelines
- Carousel Framework Rules
- Slide Layout Rules

The repository is intended to function as a visual knowledge base for AI-assisted carousel generation.

---

# Primary Objective

The primary goal of this repository is to improve communication through supporting visual elements without sacrificing content clarity.

Pose assets should:

✓ Support storytelling

✓ Reinforce emotional context

✓ Guide user attention

✓ Increase engagement

✓ Improve visual flow

Pose assets should never:

✗ Cover text

✗ Replace information

✗ Become the primary focus

✗ Reduce readability

---

# Content Framework

This repository follows the SCRIPT Framework.

---

## S — Scroll Stopper

Purpose:

- Stop scrolling
- Create curiosity
- Trigger emotion

Examples:

- Questions
- Bold statements
- Surprising facts
- Common mistakes

---

## C — Context

Purpose:

- Explain relevance
- Establish connection
- Describe the problem

Examples:

- Pain points
- Situations
- User struggles

---

## R — Reveal

Purpose:

- Reveal hidden causes
- Introduce new perspectives
- Challenge assumptions

Examples:

- Myths
- Hidden truths
- Discoveries

---

## I — Insight

Purpose:

- Educate
- Explain
- Teach frameworks

Examples:

- Methods
- Systems
- Strategies
- Principles

---

## P — Practical Action

Purpose:

- Provide actionable guidance

Examples:

- Tips
- Checklists
- Steps
- Best practices

---

## T — Transformation

Purpose:

- Show outcomes
- Reinforce benefits
- Encourage action

Examples:

- Results
- Summary
- Call to action

---

# Repository Structure

```text
carousel-pose-library/
│
├── Poses/
│   ├── Happy.png
│   ├── Walking.png
│   ├── Wondering.png
│   ├── Sitting.png
│   ├── Hello.png
│   └── ...
│
├── ASSET_GUIDE.md
├── README.md
├── carousel_rules.md
├── pose_catalog.json
└── slide_layout_rules.md
```

---

# Repository Components

## Pose Assets

Location:

```text
Poses/
```

Contains all visual pose assets used by the carousel generation system.

Examples:

- Happy
- Walking
- Thinking
- Curious
- Shock
- Presenting
- Pointing
- AHA Moment
- Thumbs Up

---

## Pose Catalog

Location:

```text
pose_catalog.json
```

Contains metadata used for automatic pose selection.

Includes:

- Pose ID
- Emotion
- Intent
- Energy Level
- Recommended Slides
- Content Context

Used by AI systems to determine the most suitable pose for a given slide.

---

## Asset Guide

Location:

```text
ASSET_GUIDE.md
```

Defines:

- Asset usage rules
- Crop rules
- Flip rules
- Text safety rules
- Visual hierarchy rules

---

## Carousel Rules

Location:

```text
carousel_rules.md
```

Defines:

- SCRIPT implementation
- Carousel structure
- Emotional progression
- Pose recommendation logic

---

## Slide Layout Rules

Location:

```text
slide_layout_rules.md
```

Defines:

- Layout structure
- Safe zones
- Text hierarchy
- Pose placement
- Crop recommendations
- Density management

---

# Repository Loading Order

When used by AI systems, files should be interpreted in the following order:

1. README.md
2. carousel_rules.md
3. slide_layout_rules.md
4. ASSET_GUIDE.md
5. pose_catalog.json
6. Poses/

This order ensures proper understanding of:

- Framework
- Layout
- Asset rules
- Pose metadata
- Visual assets

---

# AI Usage Workflow

Recommended workflow:

```text
Read Topic
      ↓
Determine SCRIPT Stage
      ↓
Read carousel_rules.md
      ↓
Read slide_layout_rules.md
      ↓
Read ASSET_GUIDE.md
      ↓
Read pose_catalog.json
      ↓
Select Pose
      ↓
Determine Crop
      ↓
Determine Position
      ↓
Apply Flip if Needed
      ↓
Generate Slide
```

---

# Pose Placement Rules

Recommended placement:

- Bottom Left
- Bottom Right
- Middle Left
- Middle Right

Avoid:

- Headline Area
- Reading Area
- Statistics Area
- CTA Area

---

# Crop Rules

Supported crop types:

- Full Body
- Three Quarter
- Half Body
- Medium Shot
- Medium Close-Up
- Close-Up
- Extreme Close-Up

Recommended default:

```text
Half Body
```

---

# Flip Rules

Allowed:

✓ Horizontal Flip

Use when:

- Character should face content
- Character should point toward content
- Character should direct attention

Not Allowed:

✗ Vertical Flip

✗ Upside Down Rotation

---

# Text Safety Rules

Pose assets must never cover:

- Headlines
- Paragraphs
- Lists
- Statistics
- Charts
- Tables
- CTA Buttons

If overlap occurs:

1. Reposition
2. Resize
3. Crop
4. Remove Pose

---

# Pose Density Rules

Pose usage is optional.

Recommended:

30%–50% of total slides.

Example:

8-slide carousel

- 3–4 slides with pose
- 4–5 slides without pose

Avoid using poses on every slide.

---

# No Pose Scenarios

Do not use pose assets when slides contain:

- Tables
- Statistics
- Dashboards
- Charts
- Timelines
- Process Maps
- Comparison Grids
- Dense Information

Information should always take priority.

---

# AI Agent Instructions

When generating carousel content:

1. Determine SCRIPT stage.
2. Follow carousel_rules.md.
3. Follow slide_layout_rules.md.
4. Follow ASSET_GUIDE.md.
5. Select pose from pose_catalog.json.
6. Retrieve image from Poses/.
7. Verify readability.
8. Apply crop if needed.
9. Apply horizontal flip if needed.
10. Remove pose if it reduces clarity.

Priority Order:

```text
Content
↓
Readability
↓
Layout
↓
Pose
```

---

# Design Philosophy

Information First.

Visuals Second.

Every slide must remain fully understandable even if all pose assets are removed.

Pose assets enhance communication.

Content delivers communication.

---

# AI Compatibility

Compatible with:

- OpenAI GPT
- Custom GPTs
- OpenAI Assistants
- Dify
- n8n
- CrewAI
- LangChain
- LangGraph
- Flowise
- AutoGen
- LlamaIndex
- RAG Systems

---

# Version

Current Version:

```text
2.0.0
```

Framework:

```text
SCRIPT
```

Status:

```text
Production Ready
```
