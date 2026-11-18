# Lives Changed

A public, independent collection of first-person stories found in public YouTube comments on [Rabbi Yosef Mizrachi’s channel](https://www.youtube.com/@RabbiYosefMizrachi/videos).

This site is **not affiliated** with the channel, Rabbi Yosef Mizrachi, or Divine Information. The quotes are public comments, collected independently.

## Inclusion rule

A comment is included if the writer credits Rabbi Yosef Mizrachi (his videos, lectures, teachings, or channel) as a cause or meaningful part of their change: leaving a previous religion, becoming religious as a Jew, coming to believe in God, growing closer to Hashem because of him, or growing in Torah learning or observance because of his lectures or videos. Mild credit counts when it is clear (for example, “your videos brought me back to Torah,” “he brought me closer to HaShem,” “I’ve grown so much in my Torah learning, thanks to your lectures”).

“Changed my life” said to or about Rabbi Mizrachi or his videos implies credit and is included even if the writer does not name one of those change types; the closest category is used. Growing in Torah learning or observance credited to his lectures or videos also counts, similar to growing closer to Hashem.

Identity statements without that credit — including bare identity plus “I listen to your lectures,” conversions that are not attributed to him, and requests or aspirations — are left out, as are comments that mainly agree with a point in the video, political or polemical remarks, credit only to someone else (including other rabbis, or a friend’s story), and anything odd or unclear. Shared credit counts: if the writer names Rabbi Mizrachi alongside other rabbis as causes of the change, the comment is included. If credit goes only to others, or he was a later influence after the change began, it is excluded. When in doubt, the comment is excluded, except that a clear first-person “changed my life” about him, “closer to Hashem” because of him, or growth in Torah learning or observance credited to his lectures or videos, is enough to include.

A comment that credits him with an awakening (“you opened my eyes”) and also describes a concrete resulting step toward deeper Torah life (for example, buying a Zohar set and Talmud in order to learn more, or starting to keep mitzvot) is included: the credit plus an action shows real change. Believing in Torah and learning to observe while only mentioning “what you teach,” without saying he caused the change (as in a comment like @luciagarcia6611), is not enough. A comment that names him alongside other rabbis as causes of the change (as in @JustKate43: “because of yourself and some other Rabbi’s … I left idolatry and returned home to Hashem”) is included. If the journey started before the writer found him and credit goes to others, such as Aish (as in a comment like @elliotdavid3), he was a later influence, not a cause, and the comment is excluded.

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
