# Source Quality Matrix

This matrix documents how reliable each source type is for later synthesis.

## High Confidence Sources

Use these for core findings, frameworks, and strategic claims.

| Source Type | Examples In Repo | Confidence | Notes |
|---|---|---:|---|
| Full YouTube transcripts collected through Supadata | `research/youtube-transcripts/{author}/` | High | Best raw material for extracting frameworks, long-form context, and repeated themes. |
| Public LinkedIn post pages | `research/linkedin-posts/{author}/` where direct post URLs are available | High | Good for post-level examples, short excerpts, and content strategy patterns. |
| Public LinkedIn articles/newsletters by the expert | Michelle J. Raymond, Rob Illidge, Anthony Pierri materials | High | Useful because the source is authored and stable, even if not a short-form post. |
| Official or expert-owned sources | Vulse, Scripe, LinkedIn Marketing Solutions, expert channels | High/Medium | Strong when the expert is directly involved and the page clearly identifies them. |

## Medium Confidence Sources

Use these for directional themes and supporting context.

| Source Type | Examples In Repo | Confidence | Notes |
|---|---|---:|---|
| Public profile activity previews | LinkedIn profile snippets surfaced by search | Medium | Useful when full LinkedIn feed access is blocked, but should not be treated as complete scraping. |
| Repost pages exposing snippets | Company/repost pages referencing expert posts | Medium | Good for identifying themes, less ideal for exact wording. |
| Webinar or event pages featuring an expert | Wensy Antoli/Sprout/B2B Marketing Society materials | Medium | Strong for topical relevance, but not the same as a personal LinkedIn post. |
| YouTube search-selected videos | Richard and Michelle replacements for channel URLs | Medium/High | Acceptable when the original source was a channel and the selected video clearly features the expert. |

## Lower Confidence Sources

Use only for discovery or supporting notes.

| Source Type | Examples In Repo | Confidence | Notes |
|---|---|---:|---|
| Search snippets | Any result where only a snippet was visible | Low | Useful for finding sources, not enough for exact claims. |
| Third-party creator-analysis pages | Some MJ Smith post discovery | Low/Medium | Useful where LinkedIn blocks direct access, but should be verified before final publication. |
| Auto-generated transcripts with weak punctuation | Some YouTube transcript files | Medium | Useful as raw material, but quotes should be checked before reuse. |

## Known Collection Limits

- LinkedIn blocks or limits profile scraping without login.
- Some LinkedIn entries are based on indexed public snippets, reposts, or articles instead of full personal feed access.
- Some YouTube entries in `sources.md` were channel URLs, not specific video URLs.
- Current YouTube transcript counts vary by expert based on relevant public videos with available transcripts: Ty Heath 5, Richard van der Blom 5, Michelle J. Raymond 5, Justin Welsh 5, Rob Illidge 3, Alex Boyd 4, MJ Smith 4, Anthony Pierri 4, Eva Johanna Egg 4, and Wensy Antoli 1.
- I did not force unrelated YouTube videos just to reach 5 transcripts per expert.
- Wensy Antoli had limited public personal LinkedIn post availability, so related LinkedIn Creative Labs/webinar materials were used and clearly labeled.

## Verification Rule For Later Playbook Work

Before using any specific claim or quote in a final playbook:

1. Prefer full transcript or direct LinkedIn post/article sources.
2. Check the original URL.
3. Use short quotes only.
4. Paraphrase when exact wording is not essential.
5. Label lower-confidence sources as directional, not definitive.
