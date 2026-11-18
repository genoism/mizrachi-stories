# Lives Changed

A public, independent collection of first-person stories found in public YouTube comments on [Rabbi Yosef Mizrachi’s channel](https://www.youtube.com/@RabbiYosefMizrachi/videos).

This site is **not affiliated** with the channel, Rabbi Yosef Mizrachi, or Divine Information. The quotes are public comments, collected independently.

## Inclusion rule

A comment is included if the writer credits Rabbi Yosef Mizrachi (his videos, lectures, teachings, or channel) as a cause or meaningful part of their change: leaving a previous religion, becoming religious as a Jew, coming to believe in God, or growing closer to Hashem because of him. Mild credit counts when it is clear (for example, “your videos brought me back to Torah,” “he brought me closer to HaShem”).

“Changed my life” said to or about Rabbi Mizrachi or his videos implies credit and is included even if the writer does not name one of those change types; the closest category is used.

Identity statements without that credit, comments that mainly agree with a point in the video, political or polemical remarks, credit to someone else (including other rabbis, or a friend’s story), and anything odd or unclear are left out. When in doubt, the comment is excluded, except that a clear first-person “changed my life” about him, or “closer to Hashem” because of him, is enough to include.

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
