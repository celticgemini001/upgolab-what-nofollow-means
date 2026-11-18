# rel="nofollow" vs rel="nofollow,noopener" — Measured in a Real Browser

Measured in Chrome 157 with two local origins: rel=nofollow does not change the Referer header, but rel=&quot;nofollow,noopener&quot; is parsed as one token, so the link ships as dofollow. Plus a 21-cell Referrer-Policy × same-origin/same-site/cross-site matrix, the NBSP lookalike, and the window.opener trap.

**Read it with the tables and the reproduction snippets:** <https://celticgemini001.github.io/upgolab-what-nofollow-means/>

## About this repo

This repository exists to serve one measured article. Every number in it came from
ffmpeg and numpy run on real files on this machine — the commands are in the page so
you can re-run them and get the same rows. Where the measurement contradicted the
hypothesis, the page says so.

## The tool behind the notes

<https://upgolab.com> — browser-based AI upscaler for photos and short video.

## Index

All the guides are cross-linked from the hub:
<https://celticgemini001.github.io/upgolab-tools/>
