
---

# `CONTRIBUTING.md`

```md
# Contributing to MedClaw

Thank you for contributing to MedClaw.

This repository is intended to host reusable medicine-focused skills for AI workflows. To keep the repository clear, practical, and maintainable, please follow the guidelines below when proposing a new skill or updating an existing one.

---

## 1. Purpose of the Repository

MedClaw is designed for medicine-related and biomedical AI skills, especially those that benefit from:

- explicit task boundaries
- structured inputs and outputs
- evidence-aware reasoning
- careful wording around medical uncertainty
- reusable workflows for medical information tasks

The repository is meant to support medical information handling, not unsafe or overconfident medical decision-making.

---

## 2. Scope

Skills contributed to MedClaw should be clearly related to medicine or biomedicine.

Examples of suitable areas include:

- medical literature retrieval
- guideline summarization
- disease and drug terminology normalization
- biomedical text extraction
- evidence organization
- structured clinical text support
- medicine-focused academic writing support

Examples of contributions that are usually out of scope:

- general-purpose writing skills with no medical specificity
- purely administrative tools unrelated to medicine
- broad “medical assistant” skills with unclear boundaries
- unsafe diagnosis or treatment recommendation workflows
- skills that mix too many unrelated functions into one package

If a skill is only weakly related to medicine, it probably needs to be narrowed or placed elsewhere.

---

## 3. Repository Structure

New skills should be placed in one of the following directories:

- `skills/.curated/` for stable, well-scoped, reusable skills
- `skills/.experimental/` for developing, exploratory, or unstable skills

Each skill should have its own dedicated folder.

Example:

```text
skills/.curated/medical-literature-search/
└─ SKILL.md