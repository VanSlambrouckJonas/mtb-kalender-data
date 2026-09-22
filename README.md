# mtb-kalender-data

Generated data feed for [mtb-kalender](https://github.com/VanSlambrouckJonas/mtb-kalender)
(a private repo). `mtb.db` here is rebuilt daily by a GitHub Actions workflow in that
repo, which scrapes www.vwb.be's public ride calendar — see that repo's README
("How this gets its data") for the full explanation.

This repo exists only so the generated file can be served over GitHub Pages with
proper `ETag`/`Last-Modified` headers; the source repo stays private.
