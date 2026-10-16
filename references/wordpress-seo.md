# WordPress and search publishing guide

## Reader-first SEO

Use the topic and reader intent to structure the page. Select a primary topic phrase and related terms naturally. Do not prescribe keyword density, “LSI keywords,” exact keyword positions, a minimum word count, a minimum image count, or FAQs for every article. An SEO-plugin score is not proof of content quality or ranking potential.

Google documentation changes. When giving current SEO advice, verify the applicable official pages rather than relying on fixed rules in this file:

- [Helpful content](https://developers.google.com/search/docs/fundamentals/creating-helpful-content)
- [SEO starter guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)
- [Title links](https://developers.google.com/search/docs/appearance/title-link)
- [Snippets and descriptions](https://developers.google.com/search/docs/appearance/snippet)
- [Image guidance](https://developers.google.com/search/docs/appearance/google-images)
- [Article structured data](https://developers.google.com/search/docs/appearance/structured-data/article)
- [AI-generated content](https://developers.google.com/search/docs/fundamentals/using-gen-ai-content)
- [Spam policies](https://developers.google.com/search/docs/essentials/spam-policies)
- [Page experience](https://developers.google.com/search/docs/appearance/page-experience)
- [Canonical URLs](https://developers.google.com/search/docs/crawling-indexing/consolidate-duplicate-urls)

Do not claim every recommendation is a Google requirement. Character-length targets are editorial preferences, not fixed limits. Do not promise indexing, ranking, featured snippets, rich results, or AI citations. If research tools or ranking data are unavailable, name that limit instead of inventing findings.

## Search planning and existing content

For a substantial new SEO-focused article, briefly inspect relevant existing posts and a small sample of current search results. Match the task's scope: an explicit search research request deserves deeper investigation; a paragraph edit does not. Note the observed query, review date and source URLs in scratch research. Treat the results as a sample, not a complete or location-independent ranking report.

- Determine the reader intent: learning, following steps, comparing options, or finding a service. Choose a suitable article format and answer that need.
- Check whether an existing article already answers essentially the same question. Suggest an update when it serves readers better; propose a separate article when the purpose is meaningfully different. Multiple pages mentioning the same topic are not automatically a problem.
- Compare information needs, missing explanations, and useful examples. Do not clone competitor outlines or copy prose.
- Keep the topic aligned with the site's audience and Murali's real knowledge. Do not create loosely related posts solely because a query appears popular.
- If Search Console or keyword-tool data is supplied or available with authorized access, use it for actual query, page, country/device and date context. Without such data, describe topic ideas qualitatively. Do not invent volumes, difficulty scores or traffic forecasts.
- If research access fails, continue with a sensible draft when possible and label the unverified planning assumptions. Do not claim competition or existing-content checks were completed.

## Site context

Default publisher/site: Murali Sugumar, https://muralisugumar.com/.

These paths were observed on the site during setup and are candidates, not a permanent guarantee. Recheck relevance and availability before using them:

- /about/ — author background
- /wordpress-development/ — WordPress services
- /website-design/ — design services
- /seo-services/ — SEO services
- /projects/ — project examples
- /blog/ — articles
- /contact/ — enquiries

Link relevant existing articles when available. Do not invent article URLs or credentials. Avoid repeating promotional links without reader benefit. Category and tag names must be verified or explicitly labelled as suggestions. The active SEO plugin, theme, and permalink structure are unknown until inspected.

## Metadata sheet

Provide a compact table or clear labelled fields:

| Field | Decision |
| --- | --- |
| Post title / H1 | Accurate, specific, readable title |
| SEO title | Useful search title; optional site branding if space suits |
| Meta description | Honest summary of the page's value; no unsupported promises |
| Slug | Concise, descriptive, readable URL segment |
| Proposed permalink | Clearly provisional until actual structure is checked |
| Excerpt | Short plain-English summary for cards and archives |
| Primary topic | Editorial focus; not a claim of keyword volume |
| Category / tags | Relevant existing taxonomy where possible |
| Author | Murali after review; do not claim review already occurred |
| Dates | Actual publication and meaningful modification dates |
| Social fields | Title, description, appropriate image, image alt text where supported |
| Canonical | Actual final preferred URL, normally self-referencing for an original post |

Do not confuse WordPress tags with SEO keywords. Do not recommend a meta-keywords tag. Google can choose different title links and snippets.

## WordPress body and images

- The title normally goes in the post title field. Exclude a duplicate H1 in the supplied body when the theme renders it. Use logical H2/H3 sections without enforcing an arbitrary count.
- Prefer the block editor's normal content styles. Avoid embedded global CSS, unnecessary scripts, or theme-specific overrides in articles.
- Supply valid block syntax if native blocks are requested. If using clean HTML, label it for a Custom HTML block; this may be less convenient to edit than native blocks. Do not call Markdown WordPress-ready HTML.
- Use real lists, table headers, descriptive links and accessible media. Preserve meaningful code formatting. Make tables usable on small screens.
- Set the featured image in WordPress's media/post settings. Whether it also appears inside the body depends on the theme; avoid accidental duplication.
- Use responsive images and width/height. Keep the initial hero loading promptly; assess lazy loading in the actual layout. Do not apply blanket loading rules to every image.
- Configure metadata with the existing SEO plugin where possible. Do not add competing SEO plugins or duplicate metadata without a demonstrated need.

## Structured data

Prefer existing plugin-generated BlogPosting/Article and BreadcrumbList markup when suitable. Ensure the real headline, author identity, image URL, page URL and dates agree with visible content. Do not fabricate publisher logos, ratings, reviews or author credentials.

Avoid a static JSON-LD sample with an invented upload path or publication date. If a standalone template is requested, mark unresolved values clearly and keep it out of ready-to-publish files until resolved. Do not duplicate plugin markup. Validate applicable markup with Google's Rich Results Test, but do not promise a search enhancement.

FAQs are for readers. Check current Google support and eligibility before recommending FAQ structured data; never assume an FAQ section earns rich results.

## Publication checks

Before publication or in a handoff checklist, address relevant checks proportionately:

- Accurate content and source links; title and author context; original examples or evidence when available.
- Final URL, canonical, no unintended noindex, crawl access and functioning links.
- Mobile readability, keyboard access, contrast, image loading and page performance.
- Sitemap inclusion and Search Console URL inspection after publication, if access is authorized.
- Correct social preview and image dimensions; no duplicate title or metadata.
- Real published state and final URL for authorized publishing actions.

Do not state that the page passed live technical checks when only a local draft was reviewed. Track search impressions and clicks after publication when data becomes available; recommend changes based on evidence and reader needs.


## Updating articles without losing context

Read the existing article before editing. Preserve its useful material, current URL and working anchors unless the requested change requires otherwise. Do not silently change a published slug. If a URL change is justified, explain the redirect and internal-link implications; execute them only within authorization. Do not combine separate articles or remove content merely to reduce overlap without considering their different purposes and user scope.

Refresh outdated claims, screenshots and links. Keep the original publication date; change the modification date only for meaningful changes. Avoid changing a year in the headline just to suggest freshness. Capture the old content or use an available revision mechanism before an authorized substantial overwrite.

Check both outward links from the article and opportunities for relevant existing pages to link to it. Do not silently edit those other pages when the task covers only the article.

## Link handling

Use normal crawlable links for relevant independent sources. Mark paid or affiliate links with appropriate sponsored relationship attributes; handle user-generated links according to their context. Do not blanket-nofollow all external citations or add links for ranking manipulation. Use anchors that describe the destination without forced exact-match repetition.

## Handoff status and measurement

Use a short, article-specific status list rather than a generic claim that “all SEO checks passed.” Mark each material item verified, pending live access, pending author evidence, or not applicable. Separate local formatting checks from WordPress preview, indexing and performance checks.

For a local package, open or render the final HTML and check headings, links, lists, tables, code, images and mobile-width behaviour when a supported preview is available. A parser alone does not verify appearance. Check native block compatibility in WordPress when access is available and authorized; otherwise state it is unverified. Do not treat local preview as proof of active-theme compatibility.

For live checks, use current official performance guidance. Distinguish real-user field data from a one-off lab test; do not promise a perfect performance score will create rankings. Report site-level blockers separately from content changes and do not expand into a full site audit unless requested.

When search data is available, compare appropriate periods, queries, pages, devices and countries. Treat low impressions, weak click-through rate and reader/conversion problems as different questions. Consider indexing, seasonality and meaningful publication changes before attributing results to the skill. Do not promise results by a fixed date. A maintenance recommendation is not authorization to create a recurring monitor.
