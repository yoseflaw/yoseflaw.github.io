---
title: "Post title here"
description: "One-sentence summary used for previews, meta tags, and OG cards."
date: 2026-04-21
tags:
  - example-tag
draft: true
# translation: en/ai/my-post   # uncomment to link to the other-language version
---

A short lead paragraph that introduces the piece. This shows up in link previews and search results, so write it for a reader who hasn't opened the post yet.

## First section

Body copy. Markdown works as you'd expect.

- Lists work.
- `inline code` and **bold** and *italic*.

### Code block

```python
print("hello")
```

### Wiki link to a related post

See also [[en/bitcoin/some-other-post|this piece on Bitcoin]].

### Callout (Obsidian-flavored)

> [!note]
> Callouts render as styled blocks. Types: note, info, tip, warning, example, quote, etc.

---

## Checklist before you remove `draft: true`

- [ ] Title, description, date filled in.
- [ ] `tags` reflect the post (lowercase, kebab-case).
- [ ] Internal links work locally (`npx quartz build --serve`).
- [ ] If a translation exists, the `translation:` field points to it.
