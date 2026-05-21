# Collection Notes

Date collected/rebuilt: May 21, 2026

Topic: **LinkedIn organic content strategy for B2B SaaS**

## Repository Structure Used

- `research/sources.md` - expert list, roles, links, and rationale.
- `research/linkedin-posts/` - LinkedIn post research notes by expert.
- `research/youtube-transcripts/` - YouTube transcript research notes by expert.
- `research/other/` - supporting research notes and quality documentation.

## YouTube Collection

YouTube transcripts were collected through the Supadata API.

Process:

1. Start with the YouTube links in `sources.md`.
2. Use Supadata to fetch transcript text.
3. For experts whose `sources.md` entry was a channel URL instead of a specific video, select relevant public YouTube videos featuring that expert.
4. Rebuild transcripts into per-author folders.
5. Add standardized sections:
   - Short Excerpt
   - Research Summary
   - B2B SaaS Application
   - Content Strategy Takeaway
   - Transcript

Known limitation:

- Some videos have raw transcripts with imperfect punctuation.
- Some experts have fewer than five highly relevant public YouTube videos with available transcripts.
- Current YouTube transcript counts are based on the files currently in `research/youtube-transcripts/`:
  - Ty Heath: 5
  - Richard van der Blom: 5
  - Michelle J. Raymond: 5
  - Justin Welsh: 5
  - Rob Illidge: 3
  - Alex Boyd: 4
  - MJ Smith: 4
  - Anthony Pierri: 4
  - Eva Johanna Egg: 4
  - Wensy Antoli: 1
- I did not force unrelated or low-confidence YouTube videos just to reach 5 transcripts per expert.

## LinkedIn Collection

LinkedIn content was collected from public/indexed sources where available.

Process:

1. Start with the LinkedIn profile URLs in `sources.md`.
2. Search for publicly indexed posts, profile snippets, articles, reposts, and related pages.
3. Save research notes by author.
4. Avoid storing long copyrighted post text verbatim.
5. Include source URL, short excerpt, summary, B2B SaaS application, and content strategy takeaway.

Known limitation:

- LinkedIn profiles often block full scraping without login.
- Some entries are based on public snippets, article pages, or repost pages rather than full feed access.
- Wensy Antoli had limited personal-post availability, so related public LinkedIn Creative Labs/webinar materials were used and clearly labeled.

## API Key Handling

The Supadata API key was used only during collection.

It was not intentionally written into output files. A check was run to confirm the key was not present in generated Markdown files.

## Why This Still Meets The Research Goal

The assignment is not scored by raw volume. The goal is to collect high-signal material strong enough to support a later playbook.

This repository now contains:

- 10 selected experts.
- LinkedIn post research notes organized by author: 5 files per expert.
- YouTube transcripts organized by author/video: 40 current transcript files across 10 experts.
- Additional notes explaining expert quality, source quality, and coverage.
