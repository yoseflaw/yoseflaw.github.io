# Yosef's Braindump

Personal notebook published at <https://yoseflaw.github.io/>.

Built with [Quartz v4](https://quartz.jzhao.xyz/). Content in `content/`, deploy via GitHub Actions on push to `main`.

## Structure

```
content/
├── index.md              # landing
├── ai/
├── finance/
├── philosophy/
├── short-stories/
└── hobbies/
templates/
└── post.md               # copy this when starting a new post
```

## Write a post

1. Copy `templates/post.md` into the right folder, e.g. `content/ai/my-post.md`.
2. Fill in frontmatter and write.
3. Commit and push — the workflow deploys in ~2 minutes.

## Local preview

```bash
npm install            # first time only
npx quartz build --serve
# open http://localhost:8080
```

## Notes

- `draft: true` in frontmatter hides a post from the published site.
- Wiki-style links between posts: `[[bitcoin/my-post|custom label]]`.
- `baseUrl` and theme live in `quartz.config.ts`.
