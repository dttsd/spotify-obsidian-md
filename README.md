# spotify-obsidian-md
A tool for scraping your liked artists / bands on spotify, and producing a linked markdown vault to view in Obsidian graph view. Created to view connections between band members and the bands they've moved between.

## Process
1. Pull all liked bands via Spotify API, save to file
2. Take bands from that file, find all band members for each band.
3. For each band, create `.md` file.
	1. Put basic band information - genre, date established, etc.
	2. In 'Band Members' section, list band members as wikilinks `[[band_member]]`
4. For each unique band member, create `.md` file with basic info about them.