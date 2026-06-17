# Krystal Content Calendar — Editing Guide

## The file

- **Local:** `index.html` (this is the only file you need)
- **Live:** https://forge-spark.github.io/krystal-calendar/
- **Repo:** https://github.com/Forge-Spark/krystal-calendar

---

## How to edit

1. Open `index.html` in your editor
2. Find the card you want to edit (search for the date or title)
3. Update the HTML (title, captions, channels, etc.)
4. Save the file

---

## How to publish changes

1. Commit the changes:
   ```
   git add index.html
   git commit -m "Brief description of what changed"
   ```

2. Push to GitHub:
   ```
   git push
   ```

3. GitHub Pages updates automatically — changes are live in 1-2 minutes at https://forge-spark.github.io/krystal-calendar/

---

## Card structure (example)

```html
<div class="ev p1" data-chip="jul-p1" 
     data     data     data     data     data     data     data     data     data     data     data     data     data     data     data     data     data     data     data     data     data   la     data     data     data     data class="evt">Card title goes here</span>
</div>
```

Key things:
- `data-chip="month-id"` — unique ID (e.g. jul-p1, aug-cam, sep-p4)
- `data-channels` — where it posts (IG, Facebook, LinkedIn, TikTok)
- `data-fmt` — format type (Static, Carousel, Reel, e- `data-fmt` — format type (Static, Carousel, Reelis clicked
- Class `p1`/`p2`/`p3`/`p4` = color (Performance/Environmental/Human/Independence)

---

## Personas by month

| Month | Persona |
|---|---|
| July | Emma (ethical entrepreneur) |
| August | James (performance-focused) |
| September | Alex (scaling startup) |

----------------------------------------------------------------------------------------------------------------------to undo if neede------------a is in the HTML itself — no database needed (yet)
