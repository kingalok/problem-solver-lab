---
layout: post
title: "From Spark to Dark Factory: 6 Levels of AI Delivery (+ 3 Roles)"
subtitle: "How software delivery is shifting from effort-based accounting to outcome-based execution"
date: 2026-02-22 09:00:00 +0000
tags:
  - AI Delivery
  - Agentic AI
  - Engineering Strategy
cover_image: /assets/images/ai-delivery-levels.jpg
cover_alt: "Six levels of AI delivery from Spark to Dark Factory"
cover_caption: "AI delivery maturity ladder: Spark, Solo Agent, Agent Mesh, Mission Control, Autopilot, Dark Factory"
---

We are entering a shift in how software work gets priced and measured. The framing is moving from:

- "How many developer hours did this take?"

To:

- "How many tokens did we spend, and did we get a verified outcome?"

That is why "we use AI for coding" is too vague. There are levels, and the workflow changes materially at each level.

## L0 - Spark

IDE autocomplete and hints. This is pre-agent work, mostly editor support.

## L1 - Solo Agent

Single-task AI assistance: write a function, refactor a file, fix a bug. Humans still integrate, test, and validate.

## L2 - Agent Mesh (where most teams are)

This is where things become operational.

- Repository scanning
- CI log summarization
- Docs and diagrams from scripts
- Flowcharts from pipeline metadata
- Tool access through connectors and skills (MCP-style)

At this level, humans still plan and verify, but the execution surface is distributed across specialized agents.

## L3 - Mission Control

The agent implements and opens a PR. Humans review and merge. The human remains the gate.

## L4 - Autopilot

You provide a spec and acceptance criteria. The system builds, tests, and deploys. Human focus shifts from diffs to outcomes: service behavior, data quality, and SLO compliance.

## L5 - Dark Factory

Policy-driven continuous delivery. Intent and constraints go in. Working software comes out. Humans define guardrails and handle exceptions.

![AI delivery levels visual](/assets/images/ai-delivery-levels.jpg)

## Three developer roles emerging in 2026

### 1) Orchestrator

Owns spec, acceptance, evals, budget, and timebox.

### 2) Systems Builder

Owns platform controls: identity, guardrails, auditability, CI gates, and rollback.

### 3) Domain Translator

Turns domain intent into executable workflows, specs, and tools.

![Three developer roles visual](/assets/images/three-developer-roles.jpg)

## My 2026 take

Every developer will have an AI pair mapped to them, moving quickly from assist to autowork to autopilot. Less demand for hand-written code. More demand for:

- Better specs
- Better evals
- Better guardrails
- Better platform thinking

Level 5 is no longer a distant idea. It is already visible in pockets with strong agent tooling and factory-like execution systems.

Source context: [Original long-form post](https://lnkd.in/eSC69RQZ)

## Rule-form provocation

- Code must not be written by humans
- Code must not be reviewed by humans

In controlled experiments with Codex and OpenClaw-style loops, agents can already iterate and rewrite until convergence, under guardrails.
