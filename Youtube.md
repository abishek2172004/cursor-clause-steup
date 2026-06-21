# YouTube Transcripts

Transcripts/notes are organized by video, one markdown file per video:
`<author-slug>__<short-title-slug>.md`

Each file contains:
- Video title, channel, publish date, and URL
- How the transcript was obtained (API used, or manual notes if no
  transcript API access was available)
- Key timestamped takeaways relevant to AI-powered SEO content production
- A short paraphrased summary (not a full verbatim transcript dump, to
  respect copyright and keep the file useful as research signal rather
  than a copy of the source)

## Method
Transcripts were pulled using a transcript-fetching approach (e.g. a
YouTube transcript API such as Supadata, or `yt-dlp` + auto-captions where
available). Where automated transcript retrieval wasn't possible for a
specific video (private captions, no captions available, API limits),
manual viewing notes are used instead and explicitly marked as such.
