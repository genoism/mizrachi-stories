# Lives Changed

A public, independent collection of first-person stories found in public YouTube comments on [Rabbi Yosef Mizrachi’s channel](https://www.youtube.com/@RabbiYosefMizrachi/videos).

This site is **not affiliated** with the channel, Rabbi Yosef Mizrachi, or Divine Information. The quotes are public comments, collected independently.

## Inclusion rule

A comment is included only if the writer explicitly credits Rabbi Yosef Mizrachi (his videos, lectures, teachings, or channel) as a cause or meaningful part of their change: leaving a previous religion, becoming religious as a Jew, or coming to believe in God. Mild credit counts when it is clear (for example, “your videos brought me back to Torah”).

Identity statements without that causal credit, comments that mainly agree with a point in the video, political or polemical remarks, and anything odd or unclear are left out. When in doubt, the comment is excluded.

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
