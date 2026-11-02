# Saniket and Shrejal: Wedding Invitation

An Indian (Maharashtrian) wedding invitation, in English, as a website and a short animated film.

| | Date | Time | Place |
|---|---|---|---|
| Engagement | Tue, 29 Dec 2026 | 4:00 PM | Shirke Hall, Margtamhane |
| Haldi (bride) | Wed, 30 Dec 2026 | Shared by the family | Margtamhane |
| Wedding | Fri, 1 Jan 2027 | 1:57 PM | Laxmibai Balasaheb Mate Sankul Banquet & Wedding Hall, Chiplun |

## What is in this repository

| File | What it is |
|---|---|
| `index.html` | The invitation website. A single self-contained page with a live countdown, a themed section for each function, venue links and Add to calendar buttons. |
| `video.html` | The animated invitation film (40 seconds, vertical 9:16) with flute music. It can record itself to an MP4 in the browser. |
| `wedding-invite.mp4` | The rendered film, with flute music and no song. |

## View the website

Open `index.html` in any modern browser. It needs an internet connection only for the Google Fonts and the map and calendar links.

To host it for free, turn on GitHub Pages: **Settings, Pages, Deploy from a branch, `main`, `/ (root)`**. The site will then be at `https://parthchavannn.github.io/weddinginvite-ss/`.

## The film

Open `video.html` in a recent Chrome or Edge on a computer.

- **Play** to watch it, with sound.
- **Record video (MP4)** plays the whole film in real time and saves it as an MP4. Keep the tab open and in view until it finishes.
- **Add song** lets you load your own audio file in place of the flute music. The song stays in your browser. Check you have the rights to any song you share publicly, because social platforms may mute or flag licensed tracks.

The music is generated in the page: a soft bansuri-style flute in Raga Bhoopali, a quiet tanpura drone and light bell chimes.

## Customising

Everything is plain HTML, CSS and JavaScript with no build step for the website.

- **Names, dates, venues, parents:** edit the text in `index.html`. The film text is in the scene functions inside `video.html` (`sIntro`, `sNames`, `sFamilies`, `sEng`, `sHaldi`, `sWed`, `sEnd`).
- **Haldi time:** not given yet. Add it in the Haldi section of `index.html` and in `sHaldi` in `video.html`. The calendar button for Haldi is currently an all-day entry.
- **Colours:** each function has its own theme (`.th-eng`, `.th-haldi`, `.th-wed`) defined by CSS variables near the top of `index.html`.
- **Countdown target:** `TARGET` in the script at the bottom of `index.html`, set to 1 Jan 2027, 1:57 PM IST.

## Notes

- The couple illustrations are drawn as inline SVG, so no image files are needed.
- Fonts: Yatra One and Cormorant Garamond from Google Fonts.
- The Hindu auspicious swastik symbol is used as a traditional blessing mark.
