# Jack Off The Beaten Path

Trail journal for the 2026 southbound Appalachian Trail thru-hike. GitHub Pages builds this site. A commit to `main` publishes [jackoffthebeatenpath.com](https://jackoffthebeatenpath.com).

## Add a journal entry

1. Open `_journal/`.
2. Add a file such as `day1.md`. The filename is the link: `day1.md` becomes `/blog/day1/`.
3. Start it like `_journal/day0.md`:

```markdown
---
layout: post
title: "Day 1 – Katahdin"
date: 2026-06-22
location: Baxter State Park, ME
miles_today: 5.2
miles_total: 5.2
summary: One sentence for the journal list.
---

Write the entry here. Blank line between paragraphs.

## A section

More notes.
```

4. Commit. The journal page updates itself. Do not edit `blog/index.html`.

`date` is `YYYY-MM-DD`. `summary` is the line on the card. `miles_today` and `miles_total` are optional.

## Add a photo

1. Upload the picture into `images/gallery/` (jpg, png, webp, or gif).
2. Commit. It shows up on Photos with no other step.

Optional caption: add one line to `_data/captions.yml`.

```yaml
your-file-name.jpg: "What is in the picture"
```

The name has to match the file exactly. Leave it out if you do not want a caption.

Newest-first order: start the filename with the date, `2026-06-22-summit.jpg`.

## Gear

Edit the text in `gear/index.html` below the first `---` block.
