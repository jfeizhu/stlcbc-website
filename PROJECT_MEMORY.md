# STLCBC Project Memory

This file is a handoff note for future work on the STLCBC website.

## User Preferences

- When a change is ready, commit and push it without asking for approval in chat first.
- Keep the site feeling like a finished live website, not a transition/rebuild site.
- Prefer real event dates from flyers, not old WordPress publish dates.
- `old/` is only a reference source and should not be committed unless explicitly requested.

## Current Site Status

- Home page, pastor page, offering page, history page, faith page, children Sunday School page, adult Sunday School page, and events page are all built and linked.
- Sermons link goes to the church YouTube channel:
  - `https://www.youtube.com/@stlcbcsocialmedia`
- Latest hero highlights on the home page include:
  - latest church event
  - latest Timothy Fellowship
- The events page has:
  - a featured event section
  - `More Church Events`
  - a full Timothy Fellowship archive
  - local flyer/lightbox support

## Important Event Work Already Done

- Old event posts and assets were downloaded and saved locally under:
  - `source-events/archive/`
  - `source-events/posts/`
  - `images/events/`
- Church event cards were updated to use actual event dates from flyers.
- Timothy Fellowship archive was rebuilt from old category pages:
  - `https://www.stlcbc.org/?cat=6`
  - `https://www.stlcbc.org/?paged=2&cat=6`
  - `https://www.stlcbc.org/?paged=3&cat=6`
- Many Timothy Fellowship cards now use descriptive flyer-based titles instead of only `Timothy Fellowship + date`.

## Files to Check First Next Time

- [index.html](/Users/junfeizhu/Projects/church_website/stlcbc-website/index.html)
- [events.html](/Users/junfeizhu/Projects/church_website/stlcbc-website/events.html)
- [styles.css](/Users/junfeizhu/Projects/church_website/stlcbc-website/styles.css)
- [PROJECT_MEMORY.md](/Users/junfeizhu/Projects/church_website/stlcbc-website/PROJECT_MEMORY.md)

## Likely Next Improvements

- Continue replacing generic Timothy Fellowship titles with real flyer-based names where possible.
- Keep checking event card dates against flyer images when new events are added.
- If needed, build a dedicated sermons page later, but for now the YouTube channel is the sermon destination.

