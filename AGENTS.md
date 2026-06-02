# AGENTS.md

## Project role

You are working on a pre-sales UX/UI prototype for the French Constitutional Council website, Lot 1: conception, web design and UX/UI approach.

The prototype is not the final product.
It is a proof of vision, UX strategy and interface direction.

## Product brain

Before making any change, read:

- `/docs/product-brain/PROJECT_CONTEXT_CC_V1.md`
- `/docs/product-brain/01_FOUNDATION_MVP_CC_V1.md`
- `/docs/product-brain/02_VALUE_MVP_CC_V1.md`
- `/docs/product-brain/03_EXPERIENCE_MVP_CC_V1.md`
- `/docs/product-brain/04_BRAND_MVP_CC_V1.md`
- `/docs/product-brain/05_MVP_LOGIC_CC_V1.md`
- `/docs/product-brain/06_CHALLENGE_MVP_CC_V1.md`

## Core concept

The prototype must demonstrate:

> Un site citoyen en entrée, expert en profondeur.

The interface must help citizens understand constitutional decisions while keeping expert legal tools accessible.

## UI direction

The interface must be:

- republican;
- modern;
- clear;
- sober;
- trustworthy;
- close to a premium public media experience;
- institutional without being cold;
- expert without being unreadable.

Avoid:

- startup style;
- heavy glassmorphism;
- sensational media style;
- cold outdated administration style;
- unreadable legal database style;
- excessive text;
- generic SaaS cards.

## Prototype scope

Create a limited but high-quality prototype with these routes:

- `/` — homepage
- `/recherche` — guided search and decision list
- `/decisions/2024-863-qpc` — decision page, citizen reading mode
- `/decisions/2024-863-qpc?mode=expert` — same decision, expert reading mode

## Required features

The prototype must include:

- main navigation with maximum 5 entries;
- central search;
- guided search cards;
- hidden/displayable expert filters;
- reading mode selector;
- badge: `Aide à la compréhension — seul le texte officiel fait foi`;
- validated editorial summary;
- official text;
- official references;
- expert tools;
- related decisions;
- citation/share/export actions;
- visible link to `Découvrons notre Constitution` as an external educational resource.

## Key interaction

The signature moment is the transition from:

- `Comprendre simplement`

to:

- `Lecture expert`

This must feel like progressive depth, not a full personalization by profile.

## Critical constraints

Do not:

- create full personalization by user profile;
- dynamically reorganize the homepage by profile;
- present AI as a visible user-facing feature;
- promise simplified content for every decision;
- merge `Découvrons notre Constitution`;
- create a chatbot;
- create automatic legal interpretation;
- overbuild the product.

## Accessibility and maintainability

Use:

- semantic HTML;
- accessible labels;
- visible focus states;
- sufficient contrast;
- keyboard-friendly interactions;
- reusable components;
- simple design tokens;
- clean mock data separated from UI components.

## Development workflow

Before coding, always:

1. Summarize the task.
2. Propose the component plan.
3. List files to create or modify.
4. Ask for validation if the task is broad.

When coding:

- keep components small;
- use mock data;
- avoid unnecessary dependencies;
- document only structural decisions;
- keep the prototype easy to iterate.
