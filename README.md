# Quick Hunt — README

The application includes Quick_Hunt utilities; do not use this code to perform unlawful or unethical activities.

- Three main feature tabs:
  - JSON Generator
  - Wordlist / URL Variant Generator
  - OSINT Github Dorks generator
---
Make sure to use the right `<path to your wordlist>` before running the ffuf tool

<img width="1234" height="891" alt="image" src="https://github.com/user-attachments/assets/186a728e-3314-4772-b71e-b43557192ab0" />

## JSON Generator
Purpose: take a list of parameter names and produce a JSON object mapping each parameter to a synthetic default payload value.

## Wordlist / URL Variant Generator
Purpose: sanitize lines of input (freeform text or pasted command output), extract or normalize URLs, generate endpoint variants for fuzzing tools and prepare downloadable lists and loop templates.

## OSINT Dorks generator
Purpose: for each target URL entered, build a per-domain list of dorks by replacing tokens in either the default template or a user-provided custom dork text, then convert them into GitHub code-search links.

Security & Ethical note:
- The dork generator automates construction of search queries and is capable of generating queries that could be used to find sensitive information on public code repositories; do not use this code to perform unlawful or unethical activities.

---
