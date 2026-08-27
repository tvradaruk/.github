# TV Radar

**Free UK TV listings — Freeview and Sky, seven days ahead.**

TV Radar is an independent UK television guide. It merges the public Freeview
XMLTV feed with Sky's schedule API into a single view of what is on, across
every channel we can reach, refreshed every 12 hours.

Two sites, two jobs:

| | |
|---|---|
| **[tvradar.uk](https://tvradar.uk)** | Daily editorial — what's worth watching tonight |
| **[tvradar.co.uk](https://tvradar.co.uk)** | The interactive guide — live EPG grid, per-channel schedules, sport fixtures, show lookups |

---

### What's on it

- **Live EPG grid** — every channel, scrollable by time, jumps to now
- **[Now & Next](https://tvradar.co.uk/now-and-next)** — what's playing this minute and what follows
- **[Tonight](https://tvradar.co.uk/tonight)** — primetime from 7pm, films and sport picked out
- **[Sport](https://tvradar.co.uk/sport)** — live fixtures mapped to channels, including the Sky and TNT tiers most guides skip
- **[Channels](https://tvradar.co.uk/channels)** — every channel, each with seven days of listings
- **[Shows](https://tvradar.co.uk/shows)** — find every upcoming airing of a programme, across all channels

### How it's built

Next.js 15 and React 19 on the interactive side, WordPress on the editorial
side. Schedule data lives in SQLite and is rebuilt from the source feeds twice
a day; pages are statically generated and revalidated on a timer rather than
rendered per request.

### What we don't publish

We don't republish broadcaster programme synopses, and we don't paraphrase them
either — that text belongs to the broadcasters. Listings carry times, titles,
durations and channel numbers, which are facts. Any description you read on TV
Radar is our own.

Programme artwork is the same story: stills and posters belong to the people who
made them, so we don't use them. Channel logos appear only to identify the
channel.

Full detail: **[Editorial standards and corrections](https://tvradar.co.uk/editorial-standards)**.

### Independent

Not affiliated with the BBC, ITV, Channel 4, Channel 5, Sky or Freeview. No
broadcaster pays for placement. Where we use affiliate links, we say so on the
page carrying them.

---

**Found an error?** Email [hello@tvradar.co.uk](mailto:hello@tvradar.co.uk) with
the channel and date. Mistakes in our own writing are fixed within a working
day; errors originating in a broadcaster's feed we'll trace and tell you what we
find.

[Website](https://tvradar.uk) · [X](https://x.com/tvradaruk) · [Facebook](https://www.facebook.com/tvradar.guide) · [Wikidata](https://www.wikidata.org/wiki/Q141189759)
