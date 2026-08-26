# Photos on journey.html

## How it works now

Your originals stay wherever you like them — `img/`, `img/explore/`, `img/friends/`,
`img/just me/`, `img/sports/`, `img/work/`. The page does **not** read those.

The page reads only **`img/site/`**, which holds 65 web-ready copies: correctly rotated,
capped at 2200px on the long edge, progressive JPEG, quality 88. Total 20.6 MB across the
whole page, all lazy-loaded.

That split means you can keep reorganising your originals without breaking anything.

## To swap a photo

Drop a replacement into `img/site/` under the same filename. No HTML change needed.
If the source is large, resize it to about 2200px wide first.

## Where each photo sits

| File | Section |
|---|---|
| `kid-ball` | Ch 01, born in Brahmapur |
| `sunrise-field` | Ch 02, the first move |
| `family-old`, `college-group`, `odisha-roots` | Ch 03, Odia-medium childhood |
| `boots`, `tradition`, `cap-garden` | Ch 04, age ten in Surat |
| `room-night`, `bus-sleep`, `train-curd` | Interlude, six relocations |
| `rooftop-home`, `teenage` | Ch 05, Grade 9 |
| `room-night` | Ch 06, Grade 10 |
| `focus-work` | Ch 07, lockdown |
| `chess-tournament`, `chess-live`, `chess-art` | Ch 08, FIDE chess |
| `wtdiyt.png`, `blazer` | Ch 09, the book and the fail |
| `desk-work`, `home-build`, `scooter` | Ch 10, the in-between year |
| `iitm-gate`, `iitm-hoodie`, `iitm-art` | Ch 11, IIT Madras |
| `charminar`, `humayun`, `mahabalipuram` | Ch 12, travel |
| `humayun-wide`, `delhi-friend`, `balloon-trip`, `monument`, `hill-view`, `viewpoint`, `trek`, `sea-alone`, `beach-sunrise`, `friends-sea` | Travel mosaic |
| `paradox`, `flat-friends`, `beach-night` | Ch 13, Chennai |
| `friends`, `friends-campus`, `friends-night`, `bus-friends`, `friends-outing`, `team-room`, `college-group`, `beach-joy` | Interlude, uncountable friends |
| `coworking`, `soapp-polo`, `laptop-stickers` | Ch 14, SoApp |
| `iith`, `football-team`, `interiit` | Ch 15, the athlete |
| `office-night` | Ch 16, the ledger |
| `sea-alone` | Ch 17, the disciplinary year |
| `aws-team`, `aws-stage`, `mirror-selfie` | Ch 18, now |
| `night-garden`, `beanbag`, `kurta`, `aws-wall`, `aws-duo`, `desk-work`, `sunrise-field` | Outtakes |
| `art-blazer`, `art-hoodie`, `art-kurta`, `iitm-art` | Closing, illustrated portraits |

Fourteen of them also run in the film strip on the cover.

## Notes

- **Rotations fixed:** `kid-ball` and `sunrise-field` were stored sideways with no usable
  EXIF. Both are corrected in `img/site/`.
- **Frame shapes:** each photo is placed in a frame matching its real aspect ratio, so
  nothing gets badly cropped. The classes are `tall` (3:4), `square` (1:1), `wide` (16:10)
  and `pano` (21:9). `iith` and `viewpoint` are panoramas and use `pano`.
- **Missing file behaviour:** if a file is absent, that frame shows a labelled placeholder
  and mosaic tiles hide themselves. The page never shows a broken-image icon.
- **Two videos** (`VID-20250111`, `VID-20250726`) are untouched. Say the word if you want
  one embedded somewhere.
