# Happy Birthday, Niko! 🎉

A birthday surprise website for **Priya "Niko" Tomar** — 30 October.

Live (once GitHub Pages is on): https://kushagra31-coder.github.io/happy-birthday-niko/

## What she'll go through

1. **Date gate** — "Enter the Special Date" with an on-screen keypad (DD MM YYYY).
   The code is her birthday, 30 10 + her birth year.
2. **Tap to unwrap** — a gift box that takes 21 taps to open.
3. **Party room** — turn on the lights, release balloons, blow out 5 candles, cut the cake.
4. **The surprise** — highlight-reel slideshow, photo-dump polaroids, three gift
   boxes, a scratch card, a birthday song corner, six flip-a-wish cards,
   birthday-by-numbers, and a letter at the end.

Platonic, by design. No love meter, no romance — just a friend being extra.

## Personalise it (one place: `CONFIG` at the top of the script in `index.html`)

- `birthYear` — set Priya's real birth year to lock the gate exactly.
  Left `null`, the gate accepts 30 10 with any year from 1990–2015.
- `photos` — add image paths/URLs to fill the polaroid photo dump.
- `songYoutubeId` — swap the Happy Birthday sing-along for her favourite song.

Single file, no build step, no dependencies except Google Fonts.
Just open `index.html` or serve the folder.
