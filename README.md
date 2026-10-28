# xm-channel-scrape

Track sirius xm channels in git based on [Simon Willison’s Weblog](https://simonwillison.net/2020/Oct/9/git-scraping/)

- `lineup.tsv` - one line per channel (number, name, genre, description), easiest way to see what changed
- `all_channels.json` - every channel from the feed, minus fields that churn daily or are cosmetic (featured artists, app deep links, colors, logos)
- `only_music.json` - music channels only
