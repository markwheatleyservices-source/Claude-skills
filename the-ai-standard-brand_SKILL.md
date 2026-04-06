[the-ai-standard-brand_references_typography.md](https://github.com/user-attachments/files/26503813/the-ai-standard-brand_references_typography.md)---
name: the-ai-standard-brand
description: >
  Apply The AI Standard's brand identity to any output — HTML, React, Word documents, proposals,
  social graphics, email templates, presentations, or any other deliverable. Use this skill
  whenever Mark or Fiona asks to create, update, or brand anything for The AI Standard consultancy.
  Triggers include: "brand this", "make it on-brand", "AI Standard style", "create a proposal",
  "build a template", "design a [X] for The AI Standard", or any request where the output should
  look like it came from The AI Standard. Also use when producing any client-facing document,
  social media asset, or internal template — even if the word "brand" isn't mentioned. The goal
  is that every output looks like it was made by the same hand.
---

# The AI Standard — Brand Skill

This skill governs how Claude applies The AI Standard's visual identity and tone across all output
types. Read the full brand reference below before producing any branded asset.

For detailed colour usage rules, see `references/colours.md`.
For typography rules, see `references/typography.md`.
For tone and copy guidance, see `references/tone.md`.

---

## Brand Identity at a Glance

**Name:** The AI Standard  
**Tagline:** *"Setting the benchmark for AI in business."*  
**Positioning:** Premium B2B AI consultancy. Authoritative, editorial, intelligent. Think Financial Times meets a modern strategy firm — never a startup, never a tech vendor.  
**Founders:** Mark Wheatley · Fiona Sherwood  
**Contact:** mark.wheatley@theaistandard.co.uk · fiona.sherwood@theaistandard.co.uk  
**Website:** www.theaistandard.co.uk

---

## The Logo

The wordmark is: **The *AI* Standard**

- "The" — Libre Baskerville, regular weight, navy
- "*AI*" — Libre Baskerville, **bold italic**, significantly larger than surrounding text, navy (or warm stone/white on dark backgrounds)
- "Standard" — Libre Baskerville, regular weight, navy

The *AI* letterforms are always larger and bolder — this is the defining feature of the logo. Never render the logo in a non-brand font or colour.

Tagline beneath logo (when included): *"Setting the benchmark for AI in business."* — italic, Libre Baskerville or DM Sans italic, smaller than logo, navy or stone depending on background.

---

## Colour System — Six Colours, One Standard

| Name | Hex | Primary Use |
|---|---|---|
| **Ink Navy** | `#2B304D` | Primary brand colour — backgrounds, logo, headers, buttons on light |
| **Warm Stone** | `#E5E3DF` | Page background and canvas throughout all layouts |
| **Alert Red** | `#C8102E` | Industry news and breaking AI developments **only** — no other use |
| **White** | `#FFFFFF` | Content cards, panels, text on dark backgrounds |
| **Warm Bronze** | `#CDBB78` | Premium CTAs on dark, bylines, course/event branding, eyebrow text |
| **Cool Slate** | `#5E6E8A` | Category tags, podcast labels, secondary nav, supporting UI |

**No other colours.** No exceptions, no additions without a deliberate strategic decision.

See `references/colours.md` for full do/don't rules per colour.

---

## Typography

| Role | Font | Notes |
|---|---|---|
| Brand logo / Headings | Libre Baskerville | Serif; use for all H1/H2, section titles, pull quotes |
| Body copy | DM Sans | Clean sans-serif; all body text, lists, captions |
| Labels / Metadata | Lekton | Monospace-feel; category tags, dates, eyebrow text, small UI labels |

Load from Google Fonts in HTML/React:
```
https://fonts.googleapis.com/css2?family=Libre+Baskerville:ital,wght@0,400;0,700;1,400;1,700&family=DM+Sans:wght@300;400;500;600&family=Lekton&display=swap
```

---

## Layout Principles

- **Background:** Always Warm Stone (`#E5E3DF`) for light-mode pages/documents
- **Dark sections:** Ink Navy (`#2B304D`) background with White or Warm Stone text
- **Cards / panels:** White (`#FFFFFF`) on Warm Stone background; Navy on White
- **Spacing:** Generous — this brand breathes. Avoid cramped layouts
- **Borders:** Use `#E0DDD8` (a slightly darker stone) for subtle dividers, never full black
- **Section labels / eyebrows:** Lekton, uppercase, small, Cool Slate or Warm Bronze
- **CTAs on dark backgrounds:** Warm Bronze fill with Navy text, or White outline
- **CTAs on light backgrounds:** Navy fill with White text

---

## Category Tags

Used in editorial content. Each tag has a fixed colour:

| Tag | Colour |
|---|---|
| INDUSTRY NEWS | Alert Red (`#C8102E`) |
| STRATEGY | Cool Slate (`#5E6E8A`) |
| CASE STUDY | Warm Bronze (`#CDBB78`) |
| TOOLS | Warm Bronze |
| CLIENTS | Warm Bronze |
| PODCAST | Cool Slate |

Tags: Lekton font, uppercase, white text (on Red/Slate), Navy text (on Bronze).

---

## Tone of Voice

- **Authoritative but not arrogant** — the brand knows its subject deeply
- **Editorial** — writes like a serious publication, not a sales brochure
- **Precise** — no filler words, no buzzword inflation
- **Human** — Mark and Fiona are named; the consultancy has a face
- Avoid: "leveraging", "synergies", "unlock your potential", excessive exclamation marks
- Use: Direct statements, active voice, specific numbers/outcomes where possible

See `references/tone.md` for copy patterns and examples.

---

## Output-Type Quick Reference

### HTML / React
- Stone background, Navy text, White cards
- Load all three Google Fonts
- Render the logo wordmark with inline spans to size *AI* larger and bold-italic
- Use the category tag colour system for any content labels

### Word Documents (.docx)
- Use the Node.js `docx` library (CommonJS)
- Ink Navy header band, White logo text, Warm Stone body background
- Libre Baskerville for headings (embed or map to closest available), DM Sans for body
- Bronze rule lines as section dividers

### Proposals
- Cover: full Ink Navy page, large logo in White/Stone, tagline beneath
- Interior: Stone background, Navy headings, White content cards
- Footer: Navy band, contact details in Stone/Bronze

### Social / Graphics
- Square or portrait format[Uploading the-ai-sta[the-ai-standard-brand_references_tone.md](https://github.com/user-attachments/files/26503814/the-ai-standard-brand_references_tone.md)[the-ai-standard-brand_references_colours.md](https://github.com/user-attachments/files/26503815/the-ai-standard-brand_references_colours.md)
ndard-brand_references_typography.md…]()

- Logo always top-centre on Stone, or centre on Navy
- Tagline beneath logo for brand-awareness posts
- Keep to the six-colour palette strictly

---

## Common Mistakes to Avoid

- ❌ Using any colour outside the six-colour palette
- ❌ Rendering "AI" in the logo at the same size as "The" and "Standard"
- ❌ Using Alert Red for anything other than industry news / breaking AI developments
- ❌ Using Cool Slate as a primary CTA colour (it's for labels and secondary nav)
- ❌ Full black (`#000000`) anywhere — use Navy or Stone instead
- ❌ White as a page background — use Warm Stone
- ❌ Borders in black — use `#E0DDD8`
- ❌ Mixing in additional fonts beyond the three
