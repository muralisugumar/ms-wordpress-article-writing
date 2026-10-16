# Article image workflow

Generate images when requested. Otherwise propose a useful image brief when appropriate without turning a writing-only request into a paid or lengthy media job. A featured image is a cover illustration; a facial image is a portrait. If the wording is ambiguous, state a reasonable assumption for an editorial cover. An identifiable portrait of Murali requires an appropriate reference; never fabricate his appearance.

## Choose imagery that explains the article

Prefer relevant editorial illustrations, authentic screenshots, diagrams or supplied photos. Do not force the same still life, palette or visual style onto every article. Check the site's current visual language or supplied references when consistency matters. A screenshot documents a real interface; generated conceptual artwork must not be described as a screenshot or proof of results.

Use the available imagegen skill and built-in image generation tool for AI-generated raster artwork. Read its instructions before generation. Keep this article skill independent of API keys or a particular image model. Do not silently substitute an SVG, placeholder, or image search result for a requested generated image. If generation is unavailable, deliver the article and image brief and explain the specific limitation.

For deterministic charts and diagrams, use suitable plotting or diagram tools instead of inventing data or labels in generated artwork.

## Image brief

Specify the article's idea, audience, medium, composition, crop safety, visual mood, and any exact text. Text-free covers are often easier to reuse, but follow the user's preference. Avoid unrelated branding, fake logos, unreadable interface text and misleading claims. A useful prompt describes a concrete scene rather than merely asking for “a perfect professional image.”

For a standard WordPress cover, a landscape composition around 16:9 is a useful editorial default, not a Google requirement. A 1200 × 630 social crop is a common option when the sharing destination supports it. Choose dimensions for the actual theme and requested use.

## Delivery and verification

- Inspect the image for subject relevance, artifacts, accurate text if included, and safe crops.
- Save the final asset into the task's outputs directory; don't leave the only usable copy in a tool's default storage.
- Preserve the original. When useful, export a visually checked compressed WebP or other supported format and a social variant. Do not impose a universal file-size ceiling at the expense of quality. Report actual dimensions.
- Post-generation resizing or compression can use ordinary image-processing tools where permitted. Use imagegen for requested creative edits unless the user specifies otherwise.
- Provide a descriptive filename, concise alt text describing the visible image, optional contextual caption, and honest generation/source credit. Alt text is not a keyword list; decorative images may need empty alt text in their actual context.
- Keep the final prompt and generation method with saved deliverables when useful for reproducibility. Do not claim a generated image guarantees clicks or search performance.
- Uploading or changing a WordPress featured image follows the same authorization boundary as other site writes.


## Provenance and rights

Confirm usage rights for externally sourced or supplied media when relevant. Do not assume an image is reusable because search can display it. Keep original files and available provenance metadata. When optimising, avoid knowingly removing source/AI provenance metadata merely to conceal origin; document an export limitation if relevant. Do not apply ecommerce or Merchant Center-specific requirements to an ordinary editorial image without checking whether that use is in scope.
