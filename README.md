# Hi, I'm Furkan

Software engineer in Ankara. I work on [DergiPark](https://dergipark.org.tr), the national academic
publishing platform run by TÜBİTAK ULAKBİM, through Yonca Teknoloji. That code is private, so here
is a short note on what I do there:

- **Institution registry** — moved author affiliations from free text to a shared registry of
  ~105K institutions linked to ROR IDs, and re-linked 1.75M existing records with queue workers.
- **Duplicate submission detection** — file hashes plus text similarity (Elasticsearch + PHP scoring),
  thresholds tuned on a labeled set of 2,525 article pairs.
- **Journal licensing** — Creative Commons licenses from the database all the way to Crossref,
  JATS and OAI-PMH exports.
- Before that, the Symfony 2 → 7 migration as an intern.

Day to day: PHP 8 / Symfony, PostgreSQL, Elasticsearch, Docker. On the side: Go.

## Projects here

- [**anabellek-wcag**](https://github.com/FurkanBayarr/anabellek-wcag) — WCAG 2.2 scanner.
  Go crawler talking to Chrome over CDP, Symfony API, Redis Streams between them.
  The interesting part is keeping a finding's identity across scans so human decisions survive.
- [**hybrid-image-annotation**](https://github.com/FurkanBayarr/hybrid-image-annotation) — my
  graduation project. YOLOv8 suggests boxes, people fix them, the fixes retrain the model.

## How I work with AI tools

I use Claude Code and Cursor every day, with guardrails: tasks start from a written plan, protected
files are off limits, every change comes with tests, and a human approves the merge. The
`CLAUDE.md` and hooks in anabellek-wcag show the setup.

[LinkedIn](https://www.linkedin.com/in/furkan-bayar-02b8ab238)
