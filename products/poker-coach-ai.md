# Poker Coach AI

> **Turn your poker sessions into structured coaching.**

## Overview

**Poker Coach AI** is an AI-assisted coaching product focused on **MTT poker improvement through post-session analysis**.

The product analyzes exported hand histories, detects recurring strategic leaks and turns those findings into clear, prioritized coaching guidance.

Its core promise is simple:

**Give me your session. I will show you where you are losing value, why it matters, and what to work on next.**

**Public product · Private source code**

The product, capabilities, progress and demonstrations can be shared publicly while source code, proprietary detection logic, internal taxonomies and implementation details remain private.

---

## What makes it different

Poker Coach AI is not designed as a real-time poker assistant.

It is a **post-session coaching system** built to help players review their own decisions after play and identify patterns that are difficult to spot manually across hundreds or thousands of hands.

The product focuses on:

- recurring strategic leaks rather than isolated mistakes;
- quantified analysis rather than vague impressions;
- prioritized coaching rather than information overload;
- multi-session progression rather than one-off feedback;
- educational explanation rather than real-time assistance.

---

## Product philosophy

A central principle of Poker Coach AI is the separation between **analysis** and **explanation**.

The underlying engine detects and measures strategic patterns. The AI layer receives structured findings and turns them into understandable coaching.

In simple terms:

**The engine analyzes. The AI explains.**

This approach is designed to make the coaching more consistent, auditable and useful than asking a general-purpose chatbot to interpret raw hands freely.

---

## Current capabilities

The current engine can already support a complete post-session analysis workflow for Winamax MTT hand histories.

Publicly shareable capabilities include:

- hand-history parsing and normalization;
- deterministic strategic leak detection;
- preflop and flop leak analysis;
- structured knowledge-base support;
- AI-generated coaching from quantified findings;
- aggregated multi-session player analysis;
- prioritized recommendations and training focus.

The current CLI engine has been validated on real exported hand-history data.

---

## Player progression

Poker Coach AI is designed to move beyond a single report.

By aggregating multiple sessions, the system can progressively identify:

- persistent leaks;
- improving areas;
- recurring positional problems;
- strategic tendencies;
- priorities that deserve focused study.

The long-term goal is to build a coaching loop where each session contributes to a clearer picture of the player's progression.

```text
Play → Import → Analyze → Prioritize → Study → Review → Improve
```

---

## Anti-RTA by design

Poker Coach AI is intentionally designed for **post-session use only**.

It is not intended to provide live decision support during active poker play.

This is an important product principle: the goal is to support learning, review and progression — not real-time assistance.

---

## Technical direction

The project is currently built around a TypeScript/Node.js analysis engine with structured poker knowledge and controlled LLM usage.

The product architecture is evolving toward a complete application with:

- a REST backend;
- a user-facing web interface;
- session and player dashboards;
- historical progression tracking;
- clearer visualization of detected leaks and priorities.

The public product presentation will expand as these user-facing layers are developed.

---

## Cost-aware AI usage

The product is designed so that AI is used where it adds real pedagogical value rather than on every raw poker hand.

Structured analysis happens first, then a limited number of AI calls are used to formulate the coaching experience.

This helps keep the system more predictable, efficient and economically viable as usage scales.

---

## Product principles

**Post-session only** — no real-time poker assistance.  
**Evidence-based** — coaching starts from detected and quantified patterns.  
**Prioritized** — the player should know what to work on first.  
**Progressive** — multiple sessions should reveal long-term tendencies.  
**Educational** — AI explains findings rather than inventing them.  
**Cost-aware** — AI usage is controlled and purposeful.  
**Private by design** — proprietary detection logic and source code remain protected.

---

## Current status

**Core analysis engine operational · Product interface in development roadmap**

The parser, normalization pipeline, strategic leak detection, AI coaching layer, structured knowledge base and multi-session aggregation are already operational.

The next major product stages are the API and user-facing web experience.

---

## Long-term vision

The ambition is to turn raw poker history into a personal coaching system that helps a player understand not just **what happened in one hand**, but **how they consistently play over time**.

Instead of manually reviewing thousands of decisions, the player receives a structured view of recurring weaknesses, priorities and measurable areas of progress.

---

**Poker Coach AI**  
*Turn your poker sessions into structured coaching.*  

A **DaliDev-IA** product.