---
# --- Core (always fill in) ---
title: "Post title here"                    # 50–60 chars; leads with the concept, not a teaser
description: "One-sentence pitch for search results and link previews."  # 120–160 chars; don't let Quartz fall back to the first paragraph
date: 2026-04-21                            # ISO date; used for article:published_time

# --- Discovery ---
tags:                                       # 3–5, lowercase, kebab-case, consistent across posts
  - example-tag

# --- Optional ---
# modified: 2026-04-21                      # set when you substantially update a published post
# aliases:                                  # old paths that should redirect here — add whenever you rename this file
#   - ai/old-slug
# socialImage: ./cover.png                  # override auto-generated OG card; skip for most posts
# permalink: ai/custom-slug                 # force a specific URL; rarely needed

# --- Flags ---
draft: true                                 # remove or set false to publish
# enableToc: false                          # hide the table of contents
# comments: false                           # toggle Giscus comments (if configured)
---

A short lead paragraph that introduces the piece. This shows up in link previews and search results if `description` is missing, so write both deliberately — don't rely on this as a fallback.

## First section

Body copy. Markdown works as you'd expect.

- Lists work.
- `inline code` and **bold** and *italic*.

### Code block

```python
print("hello")
```

### Wiki link to a related post

See also [[bitcoin/some-other-post|this piece on Bitcoin]].

### Callout (Obsidian-flavored)

> [!note]
> Callouts render as styled blocks. Types: note, info, tip, warning, example, quote, etc.

---

## Pre-publish checklist

- [ ] `title` is 50–60 chars and keyword-forward.
- [ ] `description` is 120–160 chars, written as a search snippet.
- [ ] `date` set; `modified` set if updating a published post.
- [ ] `tags` are lowercase-kebab and not over-broad.
- [ ] Internal wiki links resolve locally (`npx quartz build --serve`).
- [ ] Removed `draft: true`.
