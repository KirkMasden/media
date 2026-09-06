# media

Public file host for media (images and audio) published via GitHub Pages.

Files dropped onto the "Publish Media" droplet app on Kirk's Mac are copied
into this repository, committed, and pushed here. GitHub Pages then serves
each file at:

    https://kirkmasden.github.io/media/FILENAME

Those URLs are pasted into a Google Sheet (behind an AppSheet app) as
ready-to-use HTML: `<img>` tags for images, `<a href="...">PLAY</a>` links
for audio files.

Files are not meant to be browsed or edited by hand here — they are managed
entirely by `~/Scripts/media_drop.sh`.
