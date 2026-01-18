# My RSS Feeds

This repository contains my personal RSS feed subscriptions in OPML format.

## Usage

You can import these feeds into any RSS reader that supports OPML format.

### Using rss-tui (fork of russ)

First, clone this repository or download the `feeds.opml` file:

```bash
git clone https://github.com/shalloran/rss-feeds
cd rss-feeds
```

Then import the feeds:

```bash
rss-tui import -o feeds.opml
```

Alternatively, if you have the raw URL to the OPML file (e.g., from GitHub), you can import directly:

```bash
rss-tui import -o <raw-url-to-feeds.opml>
```

### Using other RSS readers

Most RSS readers support importing OPML files. Look for an "Import" or "Subscribe from OPML" option in your reader's settings.

## Feed Categories

- Security & Cybersecurity
- Technology News
- Reddit Feeds

## Last Updated

This feed list is my own and updated as needed, hopefully it can serve as a template for your own workflows.