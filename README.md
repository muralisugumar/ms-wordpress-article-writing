# MS WordPress Article Writing

**Research-backed articles. Simple English. Practical WordPress publishing.**

Created for and maintained by **[Murali Sugumar](https://muralisugumar.com/)**, a UI/UX designer and web developer. **MS** stands for **Murali Sugumar**.

This AI skill helps coding assistants research, write, edit and prepare articles for WordPress. It combines clear editorial standards with source verification, useful SEO guidance and an optional featured-image workflow.

**Version:** 1.1.0 · **Website:** [muralisugumar.com](https://muralisugumar.com/) · **License:** [MIT](LICENSE)

## What it does

- Writes professional English that non-native readers can understand.
- Researches current facts and links claims to supporting sources.
- Helps choose between a new article and an update to existing content.
- Encourages useful examples, decision guides and documented experience.
- Prepares an editable article and a WordPress-ready body.
- Supplies SEO titles, descriptions, slugs, excerpts and social-sharing fields.
- Checks relevant internal links and provides structured-data guidance.
- Guides featured-image creation, optimisation, alt text and credits when requested.
- Separates completed checks from checks that need a live WordPress page.

It avoids invented personal stories, unsupported statistics, forced keyword placement, fixed minimum word counts and promises of Google rankings.

## Who it is for

Bloggers, freelancers, designers, developers and business owners who want clear, useful WordPress articles. The default site profile is Murali's website, but the instructions can be adapted to your own site and audience.

This is an **AI instruction skill**, not a WordPress plugin. It does not add a settings page to WordPress or publish posts by itself.

## Install in Codex

Clone this repository into your user-level skills directory:

```sh
git clone https://github.com/muralisugumar/ms-wordpress-article-writing.git \
  "${CODEX_HOME:-$HOME/.codex}/skills/ms-wordpress-article-writing"
```

If that folder already exists, inspect your existing installation first. Do not overwrite local changes. You can also copy this repository's contents into a folder named `ms-wordpress-article-writing` under your Codex skills directory.

The skill should be available on the next turn after skill discovery refreshes. If it is not listed, start a new Codex session.

To update a clean Git-based installation:

```sh
git -C "${CODEX_HOME:-$HOME/.codex}/skills/ms-wordpress-article-writing" pull --ff-only
```

Other assistants that support `SKILL.md` may be able to use these instructions, but their installation paths, browser access and media tools differ. This release was prepared for Codex; other hosts have not been verified.

## Use it

### Write a complete article

```text
Use $ms-wordpress-article-writing to write an article about choosing a
WordPress theme for a small business. Write simple, professional English.
Include the WordPress SEO package and a featured image.
```

### Improve an existing article

```text
Use $ms-wordpress-article-writing to review this article: [URL].
Check outdated claims, clarity, useful examples and internal links.
Prepare an updated draft while preserving its current URL.
```

### Make a small edit

```text
Use $ms-wordpress-article-writing to simplify the following introduction.
Keep my meaning and return only the revised introduction: [text].
```

Small edits stay small. You do not need to request a full publishing package every time.

## Typical article package

| Deliverable | Contents |
| --- | --- |
| Editable article | Clear title, useful body, examples and contextual source links |
| WordPress body | Native blocks or semantic HTML, clearly labelled by format |
| SEO fields | Search title, description, slug, excerpt, topic and taxonomy suggestions |
| Optional images | Requested artwork, alt text, filenames and suitable variants |
| Publishing notes | Author/date setup, schema guidance, checks and unresolved evidence needs |

The workflow adapts to the topic. FAQs, comparison tables, images and calls to action are used where helpful, rather than added to every article automatically.

## What it needs

The core skill consists of Markdown instructions and UI metadata; it has no bundled executable scripts or required API keys.

Research tasks need the assistant's available browsing tools. Generated images require a compatible image-generation capability; the Codex setup uses its available imagegen skill. Live WordPress actions need an authorized connection or another supported publishing method. Access to Search Console or keyword tools is optional; without it, the skill must not invent search metrics.

Missing capabilities should be reported honestly. Installing the skill does not install browser software, image models or WordPress integrations.

## Publishing and review

The default output is a draft package. A request to write an article for a website does not automatically authorize uploads, WordPress draft creation or publication.

When a user explicitly authorizes an action, the assistant should verify the destination and requested status, complete the authorized action with supported tools, and check the result. It should not repeatedly request approval already given.

Review factual claims, personal experiences and the final WordPress preview before publication. AI-generated illustrations should not be presented as real screenshots or proof of results.

## SEO approach

The skill follows a reader-first approach: useful answers, credible evidence, clear structure and a good page experience. It directs the assistant to verify current official guidance when making SEO recommendations.

Useful references:

- [Google: helpful, reliable content](https://developers.google.com/search/docs/fundamentals/creating-helpful-content)
- [Google: AI-generated content guidance](https://developers.google.com/search/docs/fundamentals/using-gen-ai-content)
- [Google: image SEO](https://developers.google.com/search/docs/appearance/google-images)
- [Google: Article structured data](https://developers.google.com/search/docs/appearance/structured-data/article)

No skill can guarantee indexing, rich results, traffic or rankings. Search outcomes depend on content, competition, the website and other factors.

## Repository structure

```text
SKILL.md                       Core workflow and scope
agents/openai.yaml             Codex display and invocation metadata
references/editorial.md        Voice, evidence and editorial checks
references/wordpress-seo.md    Search planning and WordPress publishing
references/images.md           Image creation, delivery and provenance
references/provenance.md       Source review and adaptation decisions
LICENSE                        MIT license
```

## Validation status

Version 1.1.0 passed the Codex skill validator. Local reference links and invocation metadata were checked. The instructions were reviewed against new-article, small-edit, article-update and authorized-publication scenarios.

This is structural validation and a static scenario review. It is not an independent end-to-end benchmark, a live WordPress compatibility certification or evidence of ranking improvements.

## Credits and acknowledgements

**Creator and project owner:** [Murali Sugumar](https://muralisugumar.com/) · [GitHub](https://github.com/muralisugumar)

Developed with AI assistance and tailored to Murali Sugumar's publishing requirements. The instructions were newly written after reviewing these projects:

- [Content Research Writer — ComposioHQ](https://github.com/ComposioHQ/awesome-claude-skills/blob/master/content-research-writer/SKILL.md): research, citations, voice preservation and revision.
- [WordPress SEO Blog Post — breezessky](https://github.com/breezessky/hermes-skills-pack/blob/main/skills/wordpress-seo/SKILL.md): WordPress publishing and image/metadata workflow concepts.
- [Copywriting — Corey Haines](https://github.com/coreyhaines31/marketingskills/blob/main/skills/copywriting/SKILL.md): audience awareness, clarity and supportable claims.
- [Blog Writing Guide — Sentry](https://github.com/getsentry/skills/blob/main/skills/blog-writing-guide/SKILL.md): technical specificity, limitations and useful explanations.

This repository does not bundle those skills or their publishing scripts. Their authors retain credit for their projects. No endorsement or affiliation is implied. See [the provenance notes](references/provenance.md) for the adaptation decisions.

## Contributing

Issues and focused pull requests are welcome. Explain the reader or publishing problem your change solves. Keep the skill concise, avoid unsupported SEO formulas, and preserve the distinction between drafting and live publishing. Include a realistic example when changing workflow behaviour.

## License

[MIT](LICENSE). Copyright © 2026 Murali Sugumar. Retain the copyright and license notice when redistributing the project.
