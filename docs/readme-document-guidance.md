# README Document Guidance

This document is the primary, authoritative definition of the README format. Its
parent document is the [`kexxer-readme` README](../README.md).

This is guidance version `0.4.0`.

A repository README is a short entry point that explains the repository and
links to focused developer documentation. Link to this guidance instead of
embedding a copy of its rules.

## Guidance Reference

- Give the README a descriptive project title using one `#` heading.
- Below the title, link to this guidance using its authoritative Kexxer URL.
- Add `Guidance version: <version>` below the link, recording the version the
  README was last synchronized with.
- Before editing a README, compare its recorded version with this guidance. If
  it is older or missing, read the current guidance and bring the README into
  compliance before updating its recorded version. Do not update the version
  merely because newer guidance exists.
- Keep the guidance rules here. Do not embed them or add a separate guidance
  section to each README.

## Document Shape

- After the title, guidance link, and version, use exactly two main `##`
  sections: `Overview` and `Developer Notes`.
- Overview is a short free-form description of what the repository is and
  contains.
- Developer Notes contains `###` subsections, each with one to three bullets,
  preferably fewer than 140 characters each.
- Developer Notes subsections should be small and specific, such as "The Car
  Class," rather than broad, such as "Security."
- Each bullet describes its subsection topic.
- A Developer Notes subsection may include one code block after its bullets.
- If a subsection needs more than three bullets, keep its README entry to
  exactly three: two summary bullets and one link to a fuller `docs/` document.
- Fully capture the repository's nature in one short file without making it
  difficult to read.

## Supporting Documents

- Keep reusable procedures and detailed explanations in focused `docs/`
  documents linked from Developer Notes.
- Sub-documents may use as many bullets as needed; avoid creating
  sub-sub-documents.
- Each sub-document should reference its repository README as its parent.

## Adopting This Version

- Replace the old embedded `Guidance For This Document` block with the guidance
  link and recorded version.
- Preserve useful repository information while organizing it into the required
  sections and moving lengthy procedures into supporting documents.
- Check incoming links when changing headings or moving content.

## Starting Structure

```markdown
# Project Name

[README guidance](https://github.com/kexxer-ui/kexxer-readme/blob/main/docs/readme-document-guidance.md)

Guidance version: 0.4.0

## Overview

Briefly describe what the repository is and contains.

## Developer Notes

### Specific Topic

- Describe the topic briefly.
- Link to a focused supporting document when details are needed.
```
