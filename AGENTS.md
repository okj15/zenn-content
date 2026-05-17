# Repository Instructions

## Purpose

This repository contains Zenn articles. Treat it as a writing repository, not an application repository.

## Language And Tone

- Write articles in Japanese.
- Use a clear, explanatory tone that feels like personal technical notes refined for readers.
- Prefer "自分の言葉で整理する" style over formal documentation.
- Keep sentences direct and readable. Avoid over-polished marketing language.
- It is acceptable to use first-person context when it explains why the topic matters, such as "携わっているため" or "改めて整理する".

## Article Style

- Start with the motivation or question the article answers.
- Use familiar analogies when explaining abstract technical concepts.
  - Existing examples include RAID parity as equations and authentication/authorization as hotel check-in and key cards.
- Prefer progressive structure:
  1. Define the concept.
  2. Explain with an analogy or small example.
  3. Compare related concepts in a table.
  4. End with a short summary.
- Use section numbers for multi-step explanations when it improves scanability.
- Use tables for comparisons.
- Use `:::message` for important caveats or easily confused points.
- Keep math and code examples minimal, only when they clarify the explanation.

## Zenn Front Matter

- Preserve Zenn front matter at the top of each article.
- Required fields:
  - `title`
  - `emoji`
  - `type`
  - `topics`
  - `published`
- Use `type: "tech"` for technical articles unless the article is intentionally non-technical.
- Do not set `published: true` on drafts unless the user explicitly asks to publish.
- Keep topics focused and lowercase where practical. Japanese topics are acceptable when they match the article.

## Editing Rules

- Do not rewrite the author's voice unnecessarily.
- Prefer targeted edits: clarify confusing wording, fix structure, add examples, or improve flow.
- When expanding an article, keep the original thesis and outline unless the user asks for a larger rewrite.
- Avoid adding unsupported claims. If a factual claim is uncertain or time-sensitive, verify it before adding.
- Keep Markdown simple and Zenn-compatible.
- Do not introduce unrelated formatting churn.

## Review Checklist

- The opening states what will be clarified.
- Each section has a clear role.
- Terminology is defined before being used heavily.
- Similar terms are compared explicitly.
- Caveats are called out near the relevant concept.
- The summary restates the core distinction or mechanism in plain language.

## Git Workflow

- Use small commits with concise messages.
- Open pull requests as drafts unless the user asks otherwise.
- For writing-only changes, no build is required unless the repository later adds validation scripts.
