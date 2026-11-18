# Lives Changed

A public, independent collection of first-person stories found in public YouTube comments on [Rabbi Yosef Mizrachi’s channel](https://www.youtube.com/@RabbiYosefMizrachi/videos).

This site is **not affiliated** with the channel, Rabbi Yosef Mizrachi, or Divine Information. The quotes are public comments, collected independently.

## What’s here

- `index.html` — typography-first static page (no build step)
- `stories.json` — the quotes the page loads. Later batches can update this file and push.

Non-English stories are translated into English in `text`, with `original_text`, `translated`, and `language` filled in so the page can mark them as translated and offer the original wording.

Visitor likes are stored on [Count API](https://countapi.mileshilliard.com/) under keys beginning with `genoism-mizrachi-stories-like-`. The counts are public: anyone who knows a key can increment it.

## Local preview

Serve the repo root with any static server, for example:

```bash
python3 -m http.server 8080
```
