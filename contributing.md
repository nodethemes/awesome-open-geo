# Contributing

Thanks for helping build this list. The bar below exists because the whole point of *Awesome Open GEO* is that you can trust every link on it — the paid-SaaS lists already cover everything else.

## What belongs here

An entry must clear **all** of these:

1. **OSI-approved license.** MIT, Apache-2.0, BSD, GPL, MPL, ISC, CC0, and friends. A `LICENSE` file must exist in the repository.
2. **Free to run yourself.** Self-hostable or runnable locally with no paid tier required for the core function. An optional hosted version is fine; a repo that is only a marketing shell for a paid product is not.
3. **Genuinely about GEO.** It helps content get discovered, parsed, cited, or measured in AI answer engines. General-purpose SEO tools only qualify if they have real AI-search functionality.
4. **Alive.** Meaningful activity in the last ~12 months, and not archived.
5. **Actually usable.** A readme that explains what it does and how to run it. Not a stub, not a placeholder.

## What does not belong here

- **Source-available licenses** — BSL, FSL, SSPL, Elastic License, "open core" where the core is not open. These are not open source, and blurring that line is how a curated list stops being useful.
- **No license file.** Without one, the default is all rights reserved, however public the repo.
- **Hosted-only products**, free tier or not.
- **Link farms and SEO-spam repos**, including keyword-stuffed readmes with no working code.
- **Duplicates.** If three projects do the same thing, the list keeps the ones that do it best, not all three.

## Bringing your own project

Self-submissions are welcome and do not need an apology — just disclose it in the pull request. Judged on the same criteria as everything else.

The maintainers list [seo-geo-audit](https://github.com/lireking/seo-geo-audit) under the same rule: one entry, same bar, no special placement.

## Format

Entries are:

```
- [Name](https://github.com/owner/repo) - What it does, and why it earns a place here.
```

- Sentence case, ending in a period.
- Say what makes it worth using — not just what category it is in. "CLI that audits llms.txt" tells a reader nothing they could not guess from the name.
- Keep it to one or two sentences.
- Sort within a section by how useful the entry is likely to be to a newcomer, not alphabetically.

## Pull requests

- One theme per pull request. Adding six unrelated tools makes review slow and rejection all-or-nothing.
- Title: `Add <project> to <section>`.
- In the description, state the license and link to the `LICENSE` file.
- Run [`awesome-lint`](https://github.com/sindresorhus/awesome-lint) before opening:

  ```sh
  npx awesome-lint
  ```

  One rule, `awesome-git-repo-age`, requires the list repository itself to be at least 30 days old. Failures on that rule alone are expected on a young list and are fine.

Removals are contributions too. If something here is abandoned, relicensed away from open source, or turned out to be worse than it looked, open an issue.
