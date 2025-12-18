# Metaverse Office Meeting – Requirements Elicitation

This repository contains a three-part requirements engineering mini-project for a 3D metaverse office meeting application, completed for the CMPT 475/982 Requirements Elicitation course. The work applies user story elicitation, agile estimation, task breakdown, and Feature-Driven Development (FDD) to the same system concept.

## Problem Overview

The goal is to design requirements for software that lets people attend office meetings in a 3D metaverse, providing at least the experience of an in-person meeting plus additional "beyond physical" features. The focus is on understanding user expectations (across demographics), capturing them as user stories, and turning those into actionable requirements and features.

## Repository Structure

```
.
├── assignment-1/         # User interviews and user stories
│   ├── interviews.md     # Interview notes from 4 interviewees
│   └── user-stories.md   # Top 20 prioritized user stories with traceability
├── assignment-2/         # Task breakdown and Work Breakdown Structure
│   ├── wbs.md            # Work Breakdown Structure (indented format)
│   ├── task-estimates.md # XP task breakdown with day-level estimates
│   └── error-analysis.md # Average relative error comparison
├── assignment-3/         # Feature-Driven Development model and features
│   ├── fdd-model.md      # Overall system model and informal feature list
│   └── features-list.md  # Detailed prioritized and estimated features
└── README.md             # This file
```

## Assignment 1 – User Stories & Prioritization

In Assignment 1, four interviewees (varied in age and gender) were interviewed about what they expect from a metaverse office meeting tool. From their input, we:

- Captured individual user stories and had each interviewee rank them using a 1–5 importance scale
- Synthesized a **top 20 user stories** list with effort estimates in weeks (0.5-week increments) and explicit traceability back to each interviewee's original stories

Examples of top stories include showing job titles for all attendees, personalized avatars, one-speaker-at-a-time audio, whisper/private chat, environment setup, security, transcription, translation, 3D screen sharing, and attendance logging.

## Assignment 2 – Task Breakdown (XP) and WBS

Assignment 2 takes the **top 10 user stories** from Assignment 1 and breaks each one into implementation tasks using Extreme Programming (XP) style day-level estimates. For each user story we:

- Defined a set of tasks (e.g., requirement validation, UI design, coding, debugging, integration) with estimates of 0.5–3 days each
- Summed task estimates to get a story-level estimate in days and computed the **average relative error** versus the original week-based estimates from Assignment 1

This shows how coarse user-story estimates differ from finer task-level planning; for example, some stories had over 50% relative error once decomposed.

## Assignment 3 – Feature-Driven Development (FDD)

Assignment 3 applies Feature-Driven Development to the same metaverse meeting system using the user stories as input. We:

- Defined an **overall model shape** (classes and links) and an **informal feature list** such as creating avatars, ghost mode, room environments, whisper options, security verification, transcription, translation, timers, and attendance logging
- Built a **detailed feature list** with feature weights in days (capped at 14 days) and used those weights as priorities for planning which features should be implemented first

## What This Project Demonstrates

This repo demonstrates end-to-end requirements work on a single system concept:

- **Requirements Elicitation**: Capturing stakeholder expectations via structured interviews
- **User Story Creation & Prioritization**: Synthesizing raw feedback into ranked, traceable user stories
- **Agile Estimation**: From high-level story estimates to fine-grained XP task breakdown
- **Effort Forecasting & Error Analysis**: Understanding estimation variability and improving accuracy
- **Feature-Driven Development**: Modeling system architecture and planning feature-based iterations

This work showcases skills in requirements thinking, stakeholder communication, traceability, and agile planning practices rather than implementing production code.

## How to Use This Repository

1. Start with **Assignment 1** to understand the problem domain and initial user expectations
2. Review **Assignment 2** to see how stories are decomposed into granular, estimable tasks
3. Examine **Assignment 3** to learn how FDD shapes a feature delivery roadmap
4. Compare estimates across all three assignments to observe the estimation lifecycle

## Key Takeaways

- Elicitation quality depends on structured, diverse interviews
- User stories and tasks serve different purposes in planning (coarse vs. fine-grained)
- Estimation error decreases with finer decomposition, but benefits diminish past a point
- FDD provides a flexible, priority-driven alternative to traditional story-based backlogs
- Traceability from interviews → stories → tasks → features is critical for maintaining coherence

---

**Author**: Sparsh Sharma
