# Contributing to Atmabodha

Thank you for your interest in contributing to Atmabodha. This project aims to provide accurate, respectful, and accessible knowledge rooted in Hindu philosophy, mythology, scriptures, and culture. To maintain high quality and consistency, please follow the guidelines below before submitting issues or pull requests.

---

## 1. Contribution Areas

You may contribute in the following areas:

### Content

* New articles based on approved templates
* Updates or corrections to existing content
* Youth-friendly simplified versions
* Glossaries, summaries, or cross-references

### Design

* Logo refinements
* Iconography, motifs, and illustration assets
* UI components, wireframes, and design system elements

### Documentation

* Enhancements to PRD, roadmap, or style guides
* Edits for clarity, structure, or accuracy

### Engineering (future phases)

* Next.js components
* CMS schema and integrations
* Automated tools for validation or formatting

---

## 2. Standards for Content Contributions

To preserve consistency and authenticity across the platform, all contributors must follow these content rules:

### Writing Principles

* Use a clear, neutral, educational tone.
* Avoid persuasion, personal opinions, or religious prescriptions.
* Provide layered explanations (simple, intermediate, deeper insights).
* Use inclusive language suitable for global learners.

### Structure

All articles must use one of the official templates located in:

```
content/templates/
```

Available templates:

* concept-template.md
* deity-template.md
* scripture-template.md
* culture-template.md

### Accuracy and Sources

* Verify information using credible, well-established references.
* Paraphrase instead of quoting scripture directly unless absolutely necessary.
* Avoid disputed historical dating unless academic consensus exists.
* Flag any uncertainty or ambiguity in the description.

### Youth Content Requirements

If contributing youth-friendly versions:

* Keep language simple and non-technical.
* Use short stories or analogies.
* Ensure all values presented are universal (kindness, truth, courage, compassion).

---

## 3. Standards for Design Contributions

* Follow the visual direction documented in `docs/design`.
* Maintain consistency with established geometry, motifs, and style rules.
* Include source files (SVG/PNG) and place them in the correct folder in `/assets`.
* Update design documentation if introducing new elements.

---

## 4. Standards for Engineering Contributions

* Follow the coding conventions and architecture outlined in `docs/engineering`.
* Ensure all components are modular, documented, and scalable.
* Validate builds and avoid introducing breaking changes.
* Update related tests or documentation when required.

---

## 5. Filing Issues

Before opening an issue:

1. Search existing issues to avoid duplicates.
2. Choose the correct issue template:
   * General Issue
   * Content Request
   * Design Task
3. Provide enough detail for maintainers to understand the request.

Issues without sufficient context may be closed or returned for clarification.

---

## 6. Submitting Pull Requests

When submitting a PR:

1. Use the provided Pull Request template.
2. Keep changes focused and scoped; avoid mixing unrelated edits.
3. Confirm that:
   * Content uses the correct template
   * Design files are added in correct directories
   * Documentation updates are included where necessary
4. Reference related issues using:
   ```
   Closes #ISSUE_NUMBER
   ```
5. Wait for review before merging.

PRs may require revisions to meet project standards.

---

## 7. Folder Structure Expectations

To help maintain consistency, follow the established repository structure:

* Content under `content/`
* Product and design documentation under `docs/`
* Visual assets under `assets/`
* UI and component scaffolding under `ui/`

Do not create new top-level directories without discussion.

---

## 8. Code of Conduct

Contributors are expected to maintain professionalism, respect cultural sensitivity, and interact constructively. Disrespectful or inflammatory behavior is not tolerated.

---

## 9. Getting Help

If you have questions about structure, style, accuracy, or contribution requirements:

* Review the documentation in `docs/product` and `docs/design`.
* Open an issue with the label **question**.
* Provide examples or context so maintainers can assist effectively.
