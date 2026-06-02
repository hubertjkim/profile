# Personal Portfolio Website

## Project Overview

This repository contains my personal portfolio and CV website.

Primary goals:

1. Present my professional experience clearly.
2. Showcase selected projects with strong storytelling.
3. Provide an up-to-date online CV.
4. Make it easy for recruiters, hiring managers, collaborators, and clients to contact me.
5. Demonstrate engineering quality through the website itself.

---

# Working Model

This project uses specialized subagents.

The main Claude agent acts as a coordinator and delegates work to the most appropriate specialist whenever possible.

## Available Specialists

### portfolio-designer

Responsible for:

* UX review
* Information architecture
* Personal branding
* Recruiter experience
* Visual hierarchy
* Project presentation
* Conversion optimization

Delegate whenever the task involves:

* Layout decisions
* Homepage structure
* Navigation
* Project ordering
* User experience
* Design tradeoffs
* Personal branding

### frontend-engineer

Responsible for:

* React
* TypeScript
* HTML
* CSS
* Accessibility
* Performance
* Responsive design
* Code quality
* Technical architecture

Delegate whenever the task involves:

* Components
* Styling
* Frontend implementation
* Accessibility
* Lighthouse scores
* Performance
* Refactoring
* Technical decisions

### content-editor

Responsible for:

* Resume content
* Project descriptions
* Homepage copy
* About page content
* Writing quality
* Storytelling
* Professional positioning

Delegate whenever the task involves:

* Writing
* Editing
* Rewriting
* Resume review
* Biography updates
* Project case studies
* Professional messaging

---

# Clarification Policy

## Never Guess Requirements

Do not make significant assumptions when implementing changes.

If multiple reasonable interpretations exist, stop and ask clarifying questions before proceeding.

Examples:

* Unclear design direction
* Ambiguous feature requirements
* Multiple implementation approaches
* Missing content
* Uncertain business goals

## Clarify Before Executing

When ambiguity could materially affect the result:

1. Explain what is unclear.
2. Present the possible interpretations.
3. Ask focused questions.
4. Wait for answers before implementation.

Do not choose an implementation arbitrarily.

## Safe Assumptions

Minor assumptions are acceptable only when:

* The outcome is unlikely to change.
* The assumption is industry-standard.
* The assumption can be easily revised later.

When in doubt, ask.

---

# Core Principles

## Simplicity First

Prefer simple solutions over complex solutions.

Avoid unnecessary frameworks, libraries, animations, and abstractions.

## Performance Matters

The site should feel fast on desktop and mobile.

Prioritize:

* Fast load times
* Minimal JavaScript
* Optimized images
* Good Lighthouse scores

## Accessibility

Accessibility is a requirement, not a nice-to-have.

All features must support:

* Semantic HTML
* Keyboard navigation
* Screen readers
* Proper contrast ratios
* Responsive layouts

## Professional Tone

Content should be:

* Clear
* Concise
* Authentic
* Evidence-based

Avoid:

* Buzzwords
* Marketing jargon
* Exaggeration

## Maintainability

Code should be:

* Readable
* Predictable
* Easy to update

Optimize for future maintenance and content updates.

---

# Website Structure

Recommended pages:

* Home
* About
* Projects
* Experience
* Resume / CV
* Contact

Optional:

* Blog
* Notes
* Speaking
* Open Source

---

# Project Showcase Guidelines

Projects should emphasize:

1. Problem
2. Solution
3. Technical decisions
4. Challenges
5. Results
6. Lessons learned

Prefer case studies over simple project listings.

---

# Design Guidelines

Preferred aesthetic:

* Modern
* Clean
* Professional
* Minimal

Avoid:

* Excessive animations
* Visual clutter
* Trend-driven complexity

Whitespace is valuable.

Typography should prioritize readability.

---

# Content Guidelines

Use:

* Active voice
* Specific language
* Quantified achievements
* Outcome-oriented descriptions

Prioritize impact over responsibilities.

---

# Review Process

Before implementing significant changes:

1. Verify requirements are clear.
2. Delegate review to the most relevant specialist.
3. Evaluate accessibility implications.
4. Evaluate performance implications.
5. Evaluate maintainability implications.
6. Explain tradeoffs.

For work spanning multiple domains:

* Use multiple specialists.
* Synthesize recommendations.
* Explain conflicts and tradeoffs.

---

# Definition of Done

A task is complete only when:

* Requirements are understood.
* Accessibility requirements are met.
* Mobile responsiveness is verified.
* Performance impact is acceptable.
* Content quality is high.
* Visual consistency is maintained.
* Complexity is justified.
* User experience is improved.

## Mandatory Multi-Agent Reviews

Before merging major features:

- frontend-engineer reviews implementation quality
- portfolio-designer reviews UX and presentation
- content-editor reviews user-facing text

Major changes should not rely on a single specialist review.