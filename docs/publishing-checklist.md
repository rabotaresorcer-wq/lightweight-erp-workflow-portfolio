# Publishing Checklist

Use this checklist before publishing the case on GitHub.

## Repository Review

- Confirm that `README.md` is fully in English.
- Confirm that the nine cards in `assets/linkedin-final/` are the approved final English LinkedIn version.
- Confirm that no draft RU or hh.ru assets are included.
- Confirm that no generation scripts, local exports, or working files are included by accident.

## Security Review

- Check for credentials, tokens, API keys, private URLs, and account-specific identifiers.
- Check visible card content for real client names, phone numbers, email addresses, and social handles.
- Check that any financial values shown are anonymized or synthetic demo values.
- Check that no confidential internal formulas or production automation configuration are included.

## GitHub Setup

- Create the GitHub repository only after the local files are reviewed.
- Choose public visibility only if the privacy review passes.
- Add the suggested repository description from `docs/case-notes.md`.
- Add relevant GitHub topics from `docs/case-notes.md`.
- Push only this clean case repository, not the parent project folder.

## Suggested Commit Message

```text
Add ERP workflow portfolio case study
```
